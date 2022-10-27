![](media/image1.png)

PRACTICAL GPL COMPLIANCE

实用的 GPL 合规性

A GUIDE FOR STARTUPS, SMALL BUSINESS AND ENGINEERS

初创企业、小型企业和工程师指南

Copyright © 2017 Linux Foundation

版权所有 @2017 Linux 基金会

All rights reserved. This book or any portion thereof may not be reproduced or used in any manner whatsoever without the express written permission of the publisher except for the use of brief quotations in a book review and certain other noncommercial uses permitted by copyright law.

版权所有。未经出版商明确的书面许可，不得以任何方式复制和使用本书或其任何部分，但在书评中使用简短引文和版权法允许的其他非商业用途除外。

Printed in the United States of America First Edition, 2017

美国印刷，2017年 第一版

ISBN: 978-0-9989078-0-2

1 Letterman Drive
Building D
Suite D4700
San Francisco CA 
94129 

莱特曼大道1号，D栋，套房D4700，加利福利亚旧金山，邮编：94129

Phone/Fax: +1 415 723 9709

电话/传真：+1 415 723 9709

https://linuxfoundation.org

## About the Authors

关于作者

##### ![](media/image4.png){width="1.189915791776028in" height="1.1631802274715661in"}Shane Coughlan

Shane Coughlan is an expert in communi- cation, security, and business
development. His professional accomplishments include spearheading the
licensing team that elevated Open Invention Network into the largest
patent non-aggression community in

history, establishing the leading professional network of open source
legal experts, and aligning stakeholders to launch both the first law
journal and the first law book dedicated to open source. He currently
leads the OpenChain community as Program Manager.

Shane has extensive knowledge of open source governance, internal
process development, supply chain management, and community building.
His experience includes engagement with the enterprise, embedded,
mobile, and automotive industries.

##### ![](media/image5.png){width="1.189915791776028in" height="1.1560968941382328in"}Armijn Hemel

Armijn Hemel is the owner of Tjaldur Software Governance Solutions. He
is an active re- searcher of and internationally recognized expert in
open source license compliance and supply chain management. He studied
computer science at Utrecht University in

The Netherlands, where he pioneered reproducible builds with NixOS. In
the past he served on the board of NLUUG and was a member of the
coreteam of gpl-violations.org. Currently he is a board member at
NixOS Foundation.

## To Kate, for tirelessly driving the compliance community forward

ARMIJN HEMEL

## To Lana, who has a sense of curiosity that spans the whole world

SHANE COUGHLAN

# "Don't Panic."

DOUGLAS ADAMS

## Introduction

Practical GPL Compliance is a compliance guide for startups, small
businesses, and engineers, particularly focused on complying with the
versions of the GNU General Public License (GPL). It is designed for
engineers shipping products with GPL-licensed software included (e.g.,
consumer electronics, drones, IoT devices). Its goal is to provide
practical information to quickly address common issues. It is intended
to be useful for solving real-world challenges rather than providing
perfection in an imperfect world and to serve as the basis for
empowering a compliance engineer or compliance team to get their job
done as efficiently as possible. Hopefully, the practices laid out in
this guide will assist you in complying with other open source license
terms as well.

This book begins by introducing the tools used to practice GPL
compliance. It then expands on the goals of our approach, and follows
with an explanation of how to accomplish those goals. It continues
with a "checklist" of pitfalls frequently encountered by compliance
engineers and a list of steps that can be applied in common situations
when releasing a product or product family. It ends with some handy
flowcharts to visualize key approaches or best practices.

If you have a physical copy of this book, it should end up as a
battered, dog-eared reference text lurking beside your keyboard. If
you have a digital copy, it should be something that appears in your
favorites list or your desktop. Compliance engineering is not
something easily memorized and finished. It is a process

--- an approach backed by tools and knowledge of best practices

--- and we do best in this field when we continually refresh and hone
our skills.

Thankfully, compliance engineering is no longer a "black box" mastered
by only a few. Today, with texts like this or *Open Source*

*Compliance in the Enterprise*1, every engineer can support the
excellent use of third-party code. Licenses like the GPL, once
regarded as challenging to fully adhere to, can become understandable
and addressable by large and small entities alike.

Practical GPL Compliance and Open Source Compliance in the Enterprise
work together to help engineers, startups, small companies, and
enterprises master open source license compliance. However, they do
not exist in isolation, and you can find more materials via the Linux
Foundation Open Compliance Program at
[**https://compliance.linuxfoundation.org**](https://compliance.linuxfoundation.org/).
To get you started, Appendix 1 contains an overview of other
publications available and a list of useful compliance templates.

You may also be interested in Appendix 2: Compliance Standards,
Appendix 3: Professional Networks, and Appendix 4: Tools and
Infrastructure. There is a wealth of free resources available via The
Linux Foundation and from other parties to ensure that knowledge of
best practices and processes is readily available to you. Or..., just
go to the next page and get started right away with our cheat sheet.

1.  [**http://go.linuxfoundation.org/open-source-compliance-ebook**](http://go.linuxfoundation.org/open-source-compliance-ebook)

## The GPL Compliance Engineer Task-Based Cheat Sheet

No time to read a book? Welcome to our world. We suggest copying this
page, pinning it to your desk, and using it as a shortcut for getting
things done.

[What you need to do 2](#context)

[The tools you can use 6](#toolbox)

[How to deal with binary code 8](#_bookmark4)

[Find problem binaries 10](#source-code-analysis-and-rebuild)

[Rebuilding a binary 14](#performing-a-rebuild)

[Finding incorrectly licensed code
19](#finding-incorrectly-licensed-code)

[Common pitfalls 22](#_bookmark8)

[Releasing software 37](#_bookmark17)

[Buying software 42](#_bookmark22)

[Building a FOSS code center 48](#_bookmark26)

[Get checklists to help 52](#checklists)

[Get flowcharts to help 54](#step-4)

## Table of Contents

##### [Chapter 1: Approach 1](#_bookmark0)

[Context 2](#context)

[Compliance Requirements 3](#_bookmark2)

[Compliance Goals 3](#_bookmark2)

[Toolbox 6](#toolbox)

[Analysis of Binary Files 8](#_bookmark4)

[Source Code Analysis and Rebuild
10](#source-code-analysis-and-rebuild)

##### [Chapter 2: Common Pitfalls 22](#_bookmark8)

[Pitfall #1: Toolchain 23](#pitfall-1-toolchain)

[Pitfall #2: Android 24](#_bookmark10)

[Pitfall #3: "Out of tree" Linux Kernel Modules 27](#iproute2)

[Pitfall #4: Rescue Mode/Install Mode Systems
30](#pitfall-4-rescue-modeinstall-mode-systems)

[Pitfall #5: Bootloader 31](#pitfall-5-bootloader)

[Pitfall #6: Missing Build System 31](#pitfall-5-bootloader)

[Pitfall #7: Incorrect or Missing BusyBox Configuration Files
32](#_bookmark14)

[Pitfall #8: Incorrect or Missing Linux Kernel Configuration Files
33](#_bookmark15)

[Pitfall #9: Not Including the Version Number in Firmware and
35](#_bookmark16)

[Source Code Archive Names](#_bookmark16)

##### [Chapter 3: Scenarios for Releasing Software 37](#_bookmark17)

[Scenario #1: Software On A Device/Offline Distribution
38](#scenario-1-software-on-a-deviceoffline-distribution)

[Scenario #2: Providing A Manual Download From Website
39](#_bookmark19)

[Scenario #3: Providing An Automatic Download/ 40](#_bookmark20)

[Over The Air](#_bookmark20)

[Scenario #4: Field Engineer Applied Updates 41](#_bookmark21)

[Chapter 4: Scenarios for Buying Software 42](#_bookmark22)

[Context 43](#context-1)

[Scenario #1: SupplyChain Solutions For SoC Vendors 43](#context-1)

[Scenario #2: Supply Chain Solutions For ODMs 45](#_bookmark24)

[Scenario #3: Supply Chain Solutions For Others 46](#_bookmark25)

[Chapter 5: Building a FOSS Code Center 48](#_bookmark26)

[Context 49](#context-2)

["FOSS Code Center" As A Requirement 49](#context-2)

[Keep Firmware And Source Code Together 50](#_bookmark28)

[Chapter 6: Tracking Tasks and Processes 51](#_bookmark29)

[Checklists 52](#checklists)

[Flowcharts 54](#step-4)

[Appendices 63](#appendices)

[Appendix 1: The Open Compliance Program
64](#appendix-1-the-open-compliance-program)

[Appendix 2: Compliance Standards
68](#template-for-an-approval-request-form-for-the-use-of-free-and-open-source-software)

[Appendix 3: Professional Networks 69](#_bookmark37)

[Appendix 4: Tools & Infrastraucture
70](#appendix-4-tools-and-infrastructure)


