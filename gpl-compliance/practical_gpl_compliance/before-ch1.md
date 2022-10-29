![](media/image1.png)

## PRACTICAL GPL COMPLIANCE
## 实用的GPL合规性

A GUIDE FOR STARTUPS, SMALL BUSINESS AND ENGINEERS

初创企业、小型企业和工程师指南

Copyright © 2017 Linux Foundation

版权所有 @2017 Linux基金会

All rights reserved. This book or any portion thereof may not be reproduced or used in any manner whatsoever without the express written permission of the publisher except for the use of brief quotations in a book review and certain other noncommercial uses permitted by copyright law.

版权所有。未经出版商明确的书面许可，不得以任何方式复制和使用本书或其任何部分，但在书评中使用简短引文和版权法允许的其他非商业用途除外。

Printed in the United States of America First Edition, 2017

美国印刷，2017年第一版

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
## 关于作者

##### ![](media/image4.png)Shane Coughlan

Shane Coughlan is an expert in communication, security, and business development. His professional accomplishments include spearheading the licensing team that elevated Open Invention Network into the largest patent non-aggression community in history, establishing the leading professional network of open source legal experts, and aligning stakeholders to launch both the first law journal and the first law book dedicated to open source. He currently leads the OpenChain community as Program Manager.

Shane Coughlan是通信、安全和业务拓展方面的专家。他的专业成就包括带领许可团队，将开放创新网络(Open Invention Network)提升为历史上最大的专利非侵犯社区，建立领先的开源法律专家专业网络，以及协调利益相关者推出致力于开源的第一本法律期刊和第一本法律书籍。他目前是OpenChain社区的项目经理。

Shane has extensive knowledge of open source governance, internal process development, supply chain management, and community building. His experience includes engagement with the enterprise, embedded, mobile, and automotive industries.

Shane在开源项目治理、内部流程开发、供应链管理和社区建设方面拥有广泛的知识。他的经验在于与企业打交道，包括嵌入式、移动和汽车行业等。

##### ![](media/image5.png)Armijn Hemel

Armijn Hemel is the owner of Tjaldur Software Governance Solutions. He is an active researcher of and internationally recognized expert in open source license compliance and supply chain management. He studied computer science at Utrecht University in The Netherlands, where he pioneered reproducible builds with NixOS. In
the past he served on the board of NLUUG and was a member of the coreteam of gpl-violations.org. Currently he is a board member at NixOS Foundation.

Armijn Hemel是Tjaldur软件治理解决方案的创始人。他是开源许可合规和供应链管理领域的活跃研究人员，也是国际公认的专家。当年他在荷兰乌得勒支大学计算机科学专业学习时，就率先使用NixOS进行可重复的项目构建。过去，他曾在NLUUG董事会任职，并且是gpl-violations.org组织的核心团队的成员之一。现在他是NixOS基金会的董事会成员。

## To Kate, for tirelessly driving the compliance community forward
## 感谢Kate, 感谢她孜孜不倦地推动合规社区向前发展
ARMIJN HEMEL

## To Lana, who has a sense of curiosity that spans the whole world
## 感谢Lana，她拥有跨越全世界地好奇心
SHANE COUGHLAN

# "Don't Panic."
# “不要恐慌。”
DOUGLAS ADAMS

## Introduction
## 简介

Practical GPL Compliance is a compliance guide for startups, small businesses, and engineers, particularly focused on complying with the versions of the GNU General Public License (GPL). It is designed for engineers shipping products with GPL-licensed software included (e.g., consumer electronics, drones, IoT devices). Its goal is to provide practical information to quickly address common issues. It is intended to be useful for solving real-world challenges rather than providing perfection in an imperfect world and to serve as the basis for empowering a compliance engineer or compliance team to get their job done as efficiently as possible. Hopefully, the practices laid out in this guide will assist you in complying with other open source license terms as well.

实用的GPL合规性是针对初创公司、小型企业和工程师的合规指南，特别关注遵守GNU通用公共许可证(GPL)的版本。 它是特意为基于GPL许可发行软件的工程师设计的，主要针对如消费电子产品、无人机、物联网设备等领域。其目的是提供实用信息，以快速解决一些常见问题。它旨在帮助解决真实的问题，而不是在不完美的世界中保证完美，它提供一种基础方案，希望能辅助授权合规工程师或合规团队尽可能高效地完成工作。希望本指南中列出的实践方法也能帮助您遵守其他开源许可条款。

This book begins by introducing the tools used to practice GPL compliance. It then expands on the goals of our approach, and follows with an explanation of how to accomplish those goals. It continues with a "checklist" of pitfalls frequently encountered by compliance engineers and a list of steps that can be applied in common situations when releasing a product or product family. It ends with some handy flowcharts to visualize key approaches or best practices.

本书首先介绍了用于实践GPL合规性的工具。然后它扩展了我们方法的目标，并解释了如何实现这些目标。之后它列出了合规工程师经常会遇到的陷阱“清单”，以及通常在发布一个产品或一系列产品时可以应用的步骤列表。最后展示了一些便捷的流程图，可以快速查找关键方法或最佳实践。

If you have a physical copy of this book, it should end up as a battered, dog-eared reference text lurking beside your keyboard. If you have a digital copy, it should be something that appears in your favorites list or your desktop. Compliance engineering is not something easily memorized and finished. It is a process --- an approach backed by tools and knowledge of best practices--- and we do best in this field when we continually refresh and hone our skills.

如果您拥有这本书的纸质书，那么它最终应该是潜伏在键盘旁边的破旧、折角的参考书。如果您拥有电子版，它应该在您的收藏夹中或桌面上。合规工程不是一件容易记住和快速完成的事情。它是一个过程，也是一种由工具和最佳实践知识支持的方法---当我们不断更新和磨练我们的技能时，相信我们在这个领域是做得最好的。

Thankfully, compliance engineering is no longer a "black box" mastered by only a few. Today, with texts like this or *Open Source Compliance in the Enterprise*1, every engineer can support the excellent use of third-party code. Licenses like the GPL, once regarded as challenging to fully adhere to, can become understandable and addressable by large and small entities alike.

值得庆幸的是，合规工程不再是只有少数人掌握的“黑匣子”。如今，有了这本书或《企业中的开源合规》1，每个工程师都可以出色地使用第三方代码。像GPL这样的许可证，曾经被认为很难完全遵守，现在无论大小团体都可以理解并快速解决。

Practical GPL Compliance and Open Source Compliance in the Enterprise work together to help engineers, startups, small companies, and enterprises master open source license compliance. However, they do not exist in isolation, and you can find more materials via the Linux Foundation Open Compliance Program at [**https://compliance.linuxfoundation.org**](https://compliance.linuxfoundation.org/). To get you started, Appendix 1 contains an overview of other publications available and a list of useful compliance templates.

企业中的实用GPL合规性和开源合规性，可以帮助工程师、初创公司、小公司和企业掌握开源代码许可合规性。除此之外，您还可以通过Linux基金会开放合规计划 (https://compliance.linuxfoundation.org/)找到更多资料。为帮助您快速入门，附录1包含了其他出版物的概述和一些有用的合规模板列表。

You may also be interested in Appendix 2: Compliance Standards, Appendix 3: Professional Networks, and Appendix 4: Tools and Infrastructure. There is a wealth of free resources available via The Linux Foundation and from other parties to ensure that knowledge of best practices and processes is readily available to you. Or..., just
go to the next page and get started right away with our cheat sheet.

附录2：合规标准，附录3：专业网络，附录4：工具和基础设施，可能您都会比较感兴趣。Linux基金会和其他各方提供了大量免费资源，以确保您可以随时获得最佳实践和流程的知识。或者...，只需转到下一页并立即开始使用我们的备忘单。

1.  [**http://go.linuxfoundation.org/open-source-compliance-ebook**](http://go.linuxfoundation.org/open-source-compliance-ebook)

## The GPL Compliance Engineer Task-Based Cheat Sheet
## GPL合规工程师基于任务的备忘单

No time to read a book? Welcome to our world. We suggest copying this page, pinning it to your desk, and using it as a shortcut for getting things done.

没时间看书？那就欢迎来到我们的世界。我们建议复印此页面，将其固定在您的办公桌上，并将其用作完成工作的捷径。

[What you need to do 2](#context) 你需要做什么

[The tools you can use 6](#toolbox) 你可以使用的工具

[How to deal with binary code 8](#_bookmark4) 如何处理二进制代码

[Find problem binaries 10](#source-code-analysis-and-rebuild) 找出有问题的二进制代码

[Rebuilding a binary 14](#performing-a-rebuild) 重新编译

[Finding incorrectly licensed code 19](#finding-incorrectly-licensed-code) 找出不合规的代码

[Common pitfalls 22](#_bookmark8) 常见的陷阱

[Releasing software 37](#_bookmark17) 发布软件

[Buying software 42](#_bookmark22) 购买软件

[Building a FOSS code center 48](#_bookmark26) 构建一个FOSS代码中心

[Get checklists to help 52](#checklists) 获取帮助清单

[Get flowcharts to help 54](#step-4)  获取便捷的流程图

## Table of Contents
## 目录

##### [Chapter 1: Approach 1](#_bookmark0) 第一章：方法1

[Context 2](#context) 背景介绍

[Compliance Requirements 3](#_bookmark2) 合规要求

[Compliance Goals 3](#_bookmark2) 合规的目标

[Toolbox 6](#toolbox)  工具盒

[Analysis of Binary Files 8](#_bookmark4)  分析二进制文件

[Source Code Analysis and Rebuild 10](#source-code-analysis-and-rebuild) 源代码分析及重构

##### [Chapter 2: Common Pitfalls 22](#_bookmark8)  第二章：常见的陷阱

[Pitfall #1: Toolchain 23](#pitfall-1-toolchain)  陷阱#1：工具链

[Pitfall #2: Android 24](#_bookmark10)   陷阱#2：安卓系统

[Pitfall #3: "Out of tree" Linux Kernel Modules 27](#iproute2) 陷阱#3：“主干之外”的Linux内核模块

[Pitfall #4: Rescue Mode/Install Mode Systems 30](#pitfall-4-rescue-modeinstall-mode-systems) 陷阱#4：救援模式/安装模式系统

[Pitfall #5: Bootloader 31](#pitfall-5-bootloader)  陷阱#5：引导加载程序

[Pitfall #6: Missing Build System 31](#pitfall-5-bootloader)  陷阱#6：缺少构建系统

[Pitfall #7: Incorrect or Missing BusyBox Configuration Files 32](#_bookmark14) 陷阱#7：BusyBox配置文件不正确或已丢失

[Pitfall #8: Incorrect or Missing Linux Kernel Configuration Files 33](#_bookmark15) 陷阱#8：Linux内核配置文件不正确或已丢失

[Pitfall #9: Not Including the Version Number in Firmware and Source Code Archive Names 35](#_bookmark16) 陷阱#9：固件或源代码的存档名称中未包含版本号

##### [Chapter 3: Scenarios for Releasing Software 37](#_bookmark17)  第三章：发布软件的场景

[Scenario #1: Software On A Device/Offline Distribution 38](#scenario-1-software-on-a-deviceoffline-distribution) 场景#1：设备上安装的软件/离线分发

[Scenario #2: Providing A Manual Download From Website 39](#_bookmark19)  场景#2：提供网站下载的方式

[Scenario #3: Providing An Automatic Download Over The Air 40](#_bookmark20)   场景#3：提供自动无线下载的方式

[Scenario #4: Field Engineer Applied Updates 41](#_bookmark21)  场景#4：实用于现场工程师的下载方式

##### [Chapter 4: Scenarios for Buying Software 42](#_bookmark22) 第四章：购买软件的场景

[Context 43](#context-1)  背景介绍

[Scenario #1: SupplyChain Solutions For SoC Vendors 43](#context-1) 场景#1：SoC方案供应商的供应链解决方案

[Scenario #2: Supply Chain Solutions For ODMs 45](#_bookmark24)  场景#2：ODM的供应链解决方案

[Scenario #3: Supply Chain Solutions For Others 46](#_bookmark25)  场景#3：其他场景的供应链解决方案

##### [Chapter 5: Building a FOSS Code Center 48](#_bookmark26)  第五章：构建一个FOSS代码中心

[Context 49](#context-2)  背景介绍

["FOSS Code Center" As A Requirement 49](#context-2) “FOSS代码中心”作为一个要求

[Keep Firmware And Source Code Together 50](#_bookmark28) 将固件和源代码放在一起

##### [Chapter 6: Tracking Tasks and Processes 51](#_bookmark29) 第六章：跟踪任务和进程

[Checklists 52](#checklists)  清单列表

[Flowcharts 54](#step-4)   流程图

[Appendices 63](#appendices)  附录

[Appendix 1: The Open Compliance Program 64](#appendix-1-the-open-compliance-program)  附录1：开放合规计划

[Appendix 2: Compliance Standards 68](#template-for-an-approval-request-form-for-the-use-of-free-and-open-source-software) 附录2：合规标准

[Appendix 3: Professional Networks 69](#_bookmark37)  附录3：专业网络

[Appendix 4: Tools & Infrastraucture 70](#appendix-4-tools-and-infrastructure) 附录4：工具和基础设施


