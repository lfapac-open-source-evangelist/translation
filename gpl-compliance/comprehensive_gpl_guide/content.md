
# Copyleft and the GNU General Public License: A Comprehensive Tutorial and Guide

# Copyleft和GNU通用公共许可证：全面教程和指南

Copyright &copy; 2018      Chestek Legal.

Copyright &copy; 2003--2005, 2008, 2014--2015, 2018        Bradley M. Kuhn.

Copyright &copy; 2014--2015        Anthony K. Sebro, Jr.

Copyright &copy; 2014              Denver Gingerich.

Copyright &copy; 2003--2007, 2014  Free Software Foundation, Inc.

Copyright &copy; 2008, 2014        Software Freedom Law Center.

版权所有©2018 Chestek Legal。

版权所有©2003--2005，2008，2014--2015，2018 Bradley M. Kuhn。

版权所有©2014--2015 Anthony K. Sebro, Jr。

版权所有©2014 Denver Gingerich。

版权所有©2003--2007，2014自由软件基金会。

版权所有©2008，2014软件自由法律中心。

The copyright holders grant the freedom to copy, modify, convey, adapt, and/or redistribute this work (except Appendices [B](#_bookmark256)[--E](#_bookmark261)) under the terms of the Creative Commons Attribution Share Alike 4.0 International License. A copy of that license is available at <https://creativecommons.org/licenses/by-sa/4.0/legalcode>.

版权持有者授予自由复制，修改，传播，适应和/或重新分发本作品（除附录B--E外），根据知识共享署名相同4.0国际许可协议的条款。该许可证的副本可在https://creativecommons.org/licenses/by-sa/4.0/legalcode找到。

Appendices [B--E](#_bookmark261) include copies of the texts of various licenses published by the FSF, and they are all licensed under the license, "Everyone is permitted to copy and distribute verbatim copies of this license document, but changing it is not allowed.". However, those who seek to make modified versions of those licenses should note the [explanation given in the GPL FAQ.](https://www.gnu.org/licenses/gpl-faq.html#ModifyGPL)

附录B--E包括由FSF发表的各种许可证的文本副本，它们都在许可证下许可，“每个人都被允许复制和分发本许可证文件的逐字副本，但不允许更改。”但是，那些试图制作修改版本的许可证的人应注意GPL FAQ中给出的解释。

As a public, collaborative project, this Guide is primarily composed of the many contributions received via its [public contribution process.](https://k.copyleft.org/guide/files/master/CONTRIBUTING.md) Please [review its Git logs](https://k.copyleft.org/guide/changelog/master/) for full documentation of all contributions, and Appendix [A](#_bookmark255) contains a list of third-party works from which some material herein was adapted.

作为公共协作项目，本指南主要由通过其公共贡献过程接收到的许多贡献组成。请查看其Git日志以获取所有贡献的完整文档，附录A包含了一些本文所述材料的第三方作品列表。

The most recent version is available online at <https://copyleft.org/guide/>. Patches are indeed welcome to this material. Sources can be found in the Git repository at <https://k.copyleft.org/guide/>.

最新版本可在线获取https://copyleft.org/guide/。欢迎为此材料提供补丁。源代码可以在Git存储库https://k.copyleft.org/guide/中找到。

CONTENTS

[Preface](#preface) vii

[I Detailed Analysis of the GNU GPL and Related Licenses](#_bookmark1) 1

1.  [What Is Software Freedom?](#_bookmark2) 3

    1.  [The Free Software Definition](#the-free-software-definition) 3

        1.  [The Freedom to Run](#the-freedom-to-run) 4

        2.  [The Freedom to Change and
            Modify](#the-freedom-to-change-and-modify) 4

        3.  [The Freedom to Copy and
            Share](#the-freedom-to-copy-and-share) 4

        4.  [The Freedom to Share
            Improvements](#the-freedom-to-share-improvements) 5

    2.  [How Does Software Become Free?](#how-does-software-become-free)
        5

        1.  [Public Domain Software](#public-domain-software) 6

        2.  [Why Copyright Free Software?](#why-copyright-free-software)
            7

        3.  [Software and Non-Copyright Legal
            Regimes](#software-and-non-copyright-legal-regimes) 8

        4.  [Non-USA Copyright Regimes](#non-usa-copyright-regimes) 8

    3.  [A Community of Equality](#a-community-of-equality) 9

        1.  [The Noncommercial Community](#the-noncommercial-community)
            9

        2.  [The Commercial Community](#the-commercial-community) 9

        3.  [Law Analogy](#law-analogy) 10

2.  [A Tale of Two Copyleft Licenses](#_bookmark27) 12

    1.  [Historical Motivations for the General Public
        License](#historical-motivations-for-the-general-public-license)
        12

    2.  [Proto-GPLs And Their Impact](#proto-gpls-and-their-impact) 12

    3.  [The GNU General Public License, Version
        1](#the-gnu-general-public-license-version-1) 13

    4.  [The GNU General Public License, Version
        2](#the-gnu-general-public-license-version-2) 13

    5.  [The GNU General Public License, Version
        3](#the-gnu-general-public-license-version-3) 14

    6.  [The Innovation of Optional "Or Any Later"
        Version](#the-innovation-of-optional-or-any-later-version) 14

    7.  [Complexities of Two Simultaneously Popular
        Copylefts](#complexities-of-two-simultaneously-popular-copylefts)
        15

3.  [Running Software and Verbatim Copying](#_bookmark42) 16

    1.  [GPLv2 *§*0: Freedom to Run](#gplv2-0-freedom-to-run) 16

    2.  [GPLv2 *§*1: Verbatim Copying](#gplv2-1-verbatim-copying) 17

4.  [Derivative Works: Statute and Case Law](#_bookmark45) 18

    1.  [The Copyright Act](#the-copyright-act) 19

    2.  [Abstraction, Filtration, Comparison
        Test](#abstraction-filtration-comparison-test) 19

        1.  [Abstraction](#abstraction) 20

        2.  [Filtration](#filtration) 20

        3.  [Comparison](#comparison) 21

    3.  [Analytic Dissection Test](#analytic-dissection-test) 21

    4.  [No Protection for "Methods of
        Operation"](#no-protection-for-methods-of-operation) 21

    5.  [No Test Yet Adopted](#no-test-yet-adopted) 22

    6.  [Cases Applying Software Derivative Work
        Analysis](#cases-applying-software-derivative-work-analysis) 22

    7.  [How Much Do Derivative Works
        Matter?](#how-much-do-derivative-works-matter) 22

5.  [Modified Source and Binary Distribution](#_bookmark56) 24

    1.  [GPLv2 2: Share and Share Alike](#gplv2-2-share-and-share-alike)
        24

        1.  [The Simpler Parts of GPLv2
            2](#the-simpler-parts-of-gplv2-2) 24

[5.1.2 GPLv2 2(b)](#gplv2-2b) 25

[5.1.3 Right to Private Modification](#right-to-private-modification) 26

2.  [GPLv2 3: Producing Binaries](#gplv2-3-producing-binaries) 27

    1.  [Complete, Corresponding Source
        (CCS)](#complete-corresponding-source-ccs) 27

    2.  [Additional Source Provision
        Options](#additional-source-provision-options) 28

```{=html}
<!-- -->
```
6.  [GPL's Implied Patent Grant](#_bookmark68) 30

7.  [Defending Freedom on Many Fronts](#_bookmark69) 32

    1.  [GPLv2 4: Termination on
        Violation](#gplv2-4-termination-on-violation) 32

    2.  [GPLv2 5: Acceptance, Copyright
        Style](#gplv2-5-acceptance-copyright-style) 33

    3.  [GPLv2 6: GPL, My One and Only](#gplv2-6-gpl-my-one-and-only) 33

    4.  [GPLv2 Irrevocability](#gplv2-irrevocability) 34

        1.  [The text of the GPLv2](#the-text-of-the-gplv2) 34

        2.  [Promissory estoppel](#promissory-estoppel) 35

        3.  [Conclusion](#conclusion) 35

    5.  [GPLv2 *§*7: "Give Software Liberty or Give It
        Death!"](#gplv2-7-give-software-liberty-or-give-it-death) 35

    6.  [GPLv2 *§*8: Excluding Problematic
        Jurisdictions](#gplv2-8-excluding-problematic-jurisdictions) 36

8.  [Odds, Ends, and Absolutely No Warranty](#_bookmark86) 37

    1.  [GPLv2 *§*9: FSF as Stewards of
        GPL](#gplv2-9-fsf-as-stewards-of-gpl) 37

    2.  [GPLv2 *§*10: Relicensing
        Permitted](#gplv2-10-relicensing-permitted) 37

    3.  [GPLv2 *§*11: No Warranty](#gplv2-11-no-warranty) 37

    4.  [GPLv2 *§*12: Limitation of
        Liability](#gplv2-12-limitation-of-liability) 38

9.  [GPL Version 3](#_bookmark93) 39

    1.  [Understanding GPLv3 As An Upgraded
        GPLv2](#understanding-gplv3-as-an-upgraded-gplv2) 39

    2.  [GPLv3 0: Giving In On "Defined
        Terms"](#gplv3-0-giving-in-on-defined-terms) 40

        1.  [Modify and the Work Based on the
            Program](#modify-and-the-work-based-on-the-program) 40

        2.  [The Covered Work](#the-covered-work) 40

        3.  [Propagate](#propagate) 41

        4.  [Convey](#convey) 41

        5.  [Appropriate Legal Notices](#appropriate-legal-notices) 41

        6.  [Other Defined Terms](#other-defined-terms) 41

    3.  [GPLv3 1: Understanding CCS](#gplv3-1-understanding-ccs) 42

        1.  [Source Code Definition](#source-code-definition) 42

        2.  [CCS Definition](#ccs-definition) 42

        3.  [The System Library
            Exception](#the-system-library-exception) 43

    4.  [GPLv3 2: Basic Permissions](#gplv3-2-basic-permissions) 43

    5.  [GPLv3's views on DRM and Device
        Lock-Down](#gplv3s-views-on-drm-and-device-lock-down) 44

    6.  [GPLv3 3: What Hath DMCA
        > Wrought](#gplv3-3-what-hath-dmca-wrought) 45

    7.  [GPLv3 4: Verbatim Copying](#gplv3-4-verbatim-copying) 45

    8.  [GPLv3 5: Modified Source](#gplv3-5-modified-source) 46

    9.  [GPLv3 6: Non-Source and Corresponding
        > Source](#gplv3-6-non-source-and-corresponding-source) 46

        1.  [GPLv3 6(e): Peer-to-Peer Sharing
            > Networks](#gplv3-6e-peer-to-peer-sharing-networks) 47

        2.  [User Products, Installation Information and Device
            > Lock-Down](#user-products-installation-information-and-device-lock-down)
            > 48

        3.  [GPLv3 7: Additional
            > Permissions](#gplv3-7-additional-permissions) 50

    10. [GPLv3 7: Understanding License
        > Compatibility](#gplv3-7-understanding-license-compatibility)
        > 50

    11. [GPLv3 8: A Lighter Termination](#gplv3-8-a-lighter-termination)
        > 52

    12. [GPLv3 9: Acceptance](#gplv3-9-acceptance) 52

    13. [GPLv3 10: Explicit Downstream
        > License](#gplv3-10-explicit-downstream-license) 52

    14. [GPLv3 11: Explicit Patent
        > Licensing](#gplv3-11-explicit-patent-licensing) 53

        1.  [The Contributor's Explicit Patent
            > License](#the-contributors-explicit-patent-license) 54

        2.  [Conveyors' Patent Licensing](#conveyors-patent-licensing)
            > 55

    15. [GPLv3 *§*12: Familiar as GPLv2
        > *§*7](#gplv3-12-familiar-as-gplv2-7) 56

    16. [GPLv3 *§*13: The Great Affero
        > Compromise](#gplv3-13-the-great-affero-compromise) 57

    17. [GPLv3 *§*14: So, When's GPLv4?](#gplv3-14-so-whens-gplv4) 57

    18. [GPLv3 *§*15--17: Warranty Disclaimers and Liability
        > Limitation](#gplv3-1517-warranty-disclaimers-and-liability-limita--tion)
        > 57

10. [**The Lesser GPL**](#_bookmark147) **58**

    1.  [The First LGPL'd Program](#the-first-lgpld-program) 58

    2.  [What's the Same?](#whats-the-same) 59

    3.  [Additions to the Preamble](#additions-to-the-preamble) 60

    4.  [An Application: A Work that Uses the
        > Library](#an-application-a-work-that-uses-the-library) 60

    5.  [The Library, and Works Based On
        > It](#the-library-and-works-based-on-it) 61

    6.  [Subtleties in Defining the
        > Application](#subtleties-in-defining-the-application) 62

    7.  [LGPLv2.1 6 & LGPLv2.1 5: Combining the
        > Works](#lgplv2.1-6-lgplv2.1-5-combining-the-works) 63

    8.  [Distributing Works Based On the
        > Library](#distributing-works-based-on-the-library) 64

    9.  [And the Rest](#and-the-rest) 64

11. [**LGPLv3**](#_bookmark158) **65**

    1.  [Section 0: Additional
        > Definitions](#section-0-additional-definitions) 65

    2.  [LGPLv3 *§*1: Exception to GPLv3
        > *§*3](#lgplv3-1-exception-to-gplv3-3) 65

    3.  [LGPLv3 *§*2: Conveying Modified
        > Versions](#lgplv3-2-conveying-modified-versions) 65

    4.  [LGPLv3 *§*3: Object Code Incorporating Material from Library
        > Header
        > Files](#lgplv3-3-object-code-incorporating-material-from-li--brary-header-files)
        > 65

    5.  [LGPLv3 *§*4: Combined Works](#lgplv3-4-combined-works) 66

12. [**Integrating the GPL into Business Practices**](#_bookmark164)
    **67**

    1.  [Using GPL'd Software In-House](#using-gpld-software-in-house)
        > 67

    2.  [Business Models](#business-models) 67

    3.  [Ongoing Compliance](#ongoing-compliance) 68

```{=html}
<!-- -->
```
II. [**A Practical Guide to GPL Compliance**](#_bookmark169) **69**

```{=html}
<!-- -->
```
13. [**Background**](#_bookmark170) **71**

    1.  [Who Has Compliance
        > Obligations?](#who-has-compliance-obligations) 72

    2.  [What Are The Risks of
        > Non-Compliance?](#what-are-the-risks-of-non-compliance) 72

    3.  [Understanding Who's Enforcing](#understanding-whos-enforcing)
        > 73

14. [**Best Practices to Avoid Common Violations**](#_bookmark176)
    **74**

    1.  [Evaluate License
        > Applicability](#evaluate-license-applicability) 74

    2.  [Monitor Software Acquisition](#monitor-software-acquisition) 75

    3.  [Track Your Changes and
        > Releases](#track-your-changes-and-releases) 76

    4.  [Avoid the "Build Guru"](#avoid-the-build-guru) 76

15. [**Details of Compliant Distribution**](#_bookmark186) **77**

    1.  [Binary Distribution
        > Permission](#binary-distribution-permission) 77

        1.  [Option (a): Source Alongside
            > Binary](#option-a-source-alongside-binary) 78

        2.  [Option (b): The Offer](#option-b-the-offer) 78

        3.  [Option (c): Noncommercial
            > Offers](#option-c-noncommercial-offers) 80

        4.  [Option 6(d) in GPLv3: Internet
            > Distribution](#option-6d-in-gplv3-internet-distribution)
            > 80

        5.  [Option 6(e) in GPLv3: Software
            > Torrents](#option-6e-in-gplv3-software-torrents) 80

    2.  [Preparing Corresponding
        > Source](#preparing-corresponding-source) 81

        1.  [Assemble the Sources](#assemble-the-sources) 81

        2.  [Building the Sources](#building-the-sources) 81

        3.  [What About the Compiler?](#what-about-the-compiler) 82

    3.  [Best Practices and Corresponding
        > Source](#best-practices-and-corresponding-source) 82

    4.  [Non-Technical Compliance
        > Issues](#non-technical-compliance-issues) 82

    5.  [Self-Assessment of Compliance](#self-assessment-of-compliance)
        > 83

16. [**When The Letter Comes**](#_bookmark205) **84**

    1.  [Communication Is Key](#communication-is-key) 84

    2.  [Termination](#termination) 85

17. [**Standard Requests**](#_bookmark209) **86**

18. [**Special Topics in Compliance**](#_bookmark210) **87**

    1.  [LGPL Compliance](#lgpl-compliance) 87

    2.  [Upstream Providers](#upstream-providers) 87

    3.  [Mergers and Acquisitions](#mergers-and-acquisitions) 88

    4.  [User Products and Installation
        > Information](#user-products-and-installation-information) 89

    5.  [Beware The Consultant in Enforcers'
        > Clothing](#beware-the-consultant-in-enforcers-clothing) 89

19. [**Conclusion**](#_bookmark218) **91**

```{=html}
<!-- -->
```
III. [**Case Studies in GPL Enforcement**](#_bookmark219) **92**

```{=html}
<!-- -->
```
20. [**Overview of Community Enforcement**](#_bookmark220) **94**

    1.  [Termination Begins
        > Enforcement](#termination-begins-enforcement) 94

    2.  [Ongoing Violations](#ongoing-violations) 94

    3.  [How are Violations Discovered?](#how-are-violations-discovered)
        > 95

    4.  [First Contact](#first-contact) 96

21. [**ThinkPenguin Wireless Router: Excellent CCS**](#_bookmark225)
    **97**

    1.  [Consumer Purchase and
        > Unboxing](#consumer-purchase-and-unboxing) 97

    2.  [Root Filesystem and Kernel
        > Compilation](#root-filesystem-and-kernel-compilation) 98

    3.  [U-Boot Compilation](#u-boot-compilation) 100

    4.  [Root Filesystem and Kernel
        > Installation](#root-filesystem-and-kernel-installation) 100

    5.  [U-Boot Installation](#u-boot-installation) 101

    6.  [Firmware Comparison](#firmware-comparison) 102

    7.  [Minor Annoyances](#minor-annoyances) 103

    8.  [Lessons Learned](#lessons-learned) 104

22. [**Bortez: Modified GCC SDK**](#_bookmark241) **105**

    1.  [Facts](#facts) 105

    2.  [Lessons](#lessons) 106

23. [**Bracken: a Minor Violation in a GNU/Linux
    Distribution**](#_bookmark244) **108**

    1.  [The Facts](#the-facts) 108

    2.  [Lessons Learned](#lessons-learned-1) 109

24. [**Vigorien: Security, Export Controls, and GPL
    Compliance**](#_bookmark248) **111**

    1.  [The Facts](#the-facts-1) 111

    2.  [Lessons Learned](#lessons-learned-2) 111

25. [**Haxil, Polgara, and Thesulac: Mergers, Upstream Providers and
    Radio Devices**](#_bookmark251) **113**

    1.  [The Facts](#the-facts-2) 113

    2.  [Lessons Learned](#lessons-learned-3) 114

```{=html}
<!-- -->
```
IV. [**Appendices**](#_bookmark254) **116**

[**A Citations of Incorporated Material from Other Published
Works**](#_bookmark255) **117**

B.  [**The GNU General Public License, version 2**](#_bookmark256)
    **119**

C.  [**The GNU Lesser General Public License, version
    2.1**](#_bookmark258) **125**

D.  [**The GNU General Public License, version 3**](#_bookmark259)
    **132**

E.  [**The Affero General Public License, version 3**](#_bookmark261)
    **141**

# PREFACE
# 前言

This tutorial is the culmination of nearly a decade of studying and writing about software freedom licensing and the GPL. Each part of this tutorial is a course unto itself, educating the reader on a myriad of topics from the deep details of the GPLv2 and GPLv3, common business models in the copyleft licensing area (both the friendly and unfriendly kind), best practices for compliance with the GPL, for engineers, managers, and lawyers, as well as real-world case studies of GPL enforcement matters.

这篇教程是近十年来关于自由软件许可和GPL的研究和写作的总结。本教程的每一部分都是一个独立的课程，向读者介绍了许多主题，包括GPLv2和GPLv3的深入细节、copyleft许可证领域常见的商业模式（友好和不友好的类型）、工程师、经理和律师遵守GPL的最佳实践，以及GPL执法事项的实际案例研究。

It is unlikely that all the information herein is necessary to learn all at once, and therefore this tutorial likely serves best as a reference book. The material herein has been used as the basis for numerous live tutorials and discussion groups since 2002, and the materials have been periodically updated. They likely stand on their own as excellent reference material.

一次性学习所有的信息是不太可能的，因此本教程最好作为参考书使用。自2002年以来，这些材料已经被用作许多现场教程和讨论小组的基础，并且这些材料定期更新。它们可能作为优秀的参考材料独立存在。

However, if you are reading these course materials without attending a live tutorial session, please note that this material is merely a summary of the highlights of the various CLE and other tutorial courses based on this material. Please be aware that during the actual courses, class discussion and presentation supplements this printed curriculum. Simply reading this material is **not equivalent** to attending a course.

但是，如果你在没有参加现场教程的情况下阅读这些课程材料，请注意，这些材料仅是基于这些材料的各种CLE和其他教程课程的亮点摘要。请注意，在实际课程中，课堂讨论和演示会补充这个印刷课程。仅仅阅读这些材料是**不能等同于**参加课程的。


# Part I： Detailed Analysis of the GNU GPL and Related Licenses

# 第一部分：GNU GPL 及相关许可证的详细分析

This part of the tutorial gives a comprehensive explanation of the most popular Free Software copyright license, the GNU General Public License ("GNU GPL", or sometimes just "GPL") -- both version 2 ("GPLv2") and version 3 ("GPLv3") -- and teaches lawyers, software developers, managers and business people how to use the GPL (and GPL'd software) successfully both as a community-building "Constitution" for a software project, and to incorporate copylefted software into a new Free Software business and in existing, successful enterprises.

本教程的这一部分对最流行的自由软件版权许可证，即GNU通用公共许可证（“GNU GPL”，有时简称为“GPL”）——第2版（“GPLv2”）和第3版（“GPLv3”）——进行了全面的解释，引导律师、软件开发人员、管理人员和业务人员如何成功地使用GPL（以及GPL软件），将其作为软件项目的社区建设“章程”，并将著佐权(copylefted)的软件合并到新的自由软件业务和现有的成功企业中。

To benefit from this part of the tutorial, readers should have a general familiarity with software development processes. A basic understanding of how copyright law applies to software is also helpful. The tutorial is of most interest to lawyers, software developers and managers who run or advise software businesses that modify and/or redistribute software under the terms of the GNU GPL (or who wish to do so in the future), and those who wish to make use of existing GPL'd software in their enterprise.

为了从教程的这一部分中受益，读者应该对软件开发过程有一个大致的了解。对版权法如何适用于软件的基本理解也很有帮助。本教程最感兴趣的是律师、软件开发人员和管理人员，他们经营软件业务，建议根据GNU GPL条款修改和/或重新分发软件（或希望在将来这样做），还有那些希望在他们的企业中使用已有的GPL软件的人。

Upon completion of this part of the tutorial, readers can expect to have learned the following:

看完本教程的这一部分后，读者可以期望学到以下内容：

- The freedom-defending purpose of various terms in the GNU GPLv2 and GPLv3.
- The differences between GPLv2 and GPLv3.
- The redistribution options under the GPLv2 and GPLv3.
- The obligations when modifying GPLv2'd or GPLv3'd software.
- How to build a plan for proper and successful compliance with the GPL.
- The business advantages that the GPL provides.
- The most common business models used in conjunction with the GPL.
- How existing GPL'd software can be used in existing enterprises.
- The basics of LGPLv2.1 and LGPLv3, and how they differ from the GPLv2 and GPLv3, respectively.
- The basics to begin understanding the complexities regarding derivative and combined works of software.

- GNU GPLv2和GPLv3中各种术语，目的是捍卫自由；
- GPLv2和GPLv3的区别；
- 基于GPLv2和GPLv3的再分发选项；
- 修改GPLv2或GPLv3软件时应遵循的义务；
- 如何制定计划以正确且成功地遵守GPL协议；
- GPL提供的业务优势；
- 与GPL结合使用的最常见的商业模式；
- 企业如何使用已有的GPL软件；
- LGPLv2.1和LGPLv3的基础知识，以及它们分别与GPLv2和GPLv3的区别；
- 开始了解有关软件的衍生和组合作品的复杂性的基础知识。

## CHAPTER 1 WHAT IS SOFTWARE FREEDOM?

## 第一章 什么是软件自由？

Study of the GNU General Public License (herein, abbreviated as *GNU GPL* or just *GPL*) must begin by first considering the broader world of software freedom. The GPL was not created in a vacuum. Rather, it was created to embody and defend a set of principles that were set forth at the founding of the GNU Project and the Free Software Foundation (FSF) -- the preeminent organization that upholds, defends and promotes the philosophy of software freedom. A prerequisite for understanding both of the popular versions of the GPL (GPLv2 and GPLv3) and their terms and conditions is a basic understanding of the principles behind them. The GPL family of licenses are unlike nearly all other software licenses in that they are designed to defend and uphold these principles.

研究GNU通用公共许可证（此处缩写为*GNU GPL*或简称*GPL*）必须首先考虑更广泛的软件自由世界。 GPL不是凭空产生的，它是为了体现和捍卫在GNU项目和自由软件基金会 (FSF) 成立时提出的一系列原则而创建的，FSF是一个维护、捍卫和促进软件自由哲学的卓越组织。 理解GPL的两个流行版本（GPLv2 和 GPLv3）及其条款和条件的先决条件是对它们背后的原则有基本的理解。GPL系列许可证与几乎所有其他的软件许可证不同，因为它们旨在捍卫和维护这些原则。

### 1.1 The Free Software Definition

### 1.1 自由软件的定义

The Free Software Definition is set forth in full on FSF's website at <http://fsf.org/philosophy/free-sw.html>. This section presents an abbreviated version that will focus on the parts that are most pertinent to the GPL.

自由软件定义在FSF的网站 <http://fsf.org/philosophy/free-sw.html> 上有完整的阐述。 本节提供一个缩略版，将重点放在与GPL最密切的部分。

A particular user has software freedom with respect to a particular program if that user has the following freedoms:

如果某个特定用户具有以下自由，则这个用户就具有与特定程序相关的软件自由：

- The freedom to run the program, for any purpose.

- The freedom to study how the program works, and modify it

- The freedom to redistribute copies.

- The freedom to distribute copies of modified versions to others.
  
- 出于任何目的执行程序的自由；

- 了解程序的运行机制，可以随意修改的自由；

- 随意分发软件副本的自由；

- 将修改后的软件副本分发给他人的自由。

The focus on "a particular user" is particularly pertinent here. It is not uncommon for a subset of a specific program's user base to have these freedoms, while other users of the same version the program have none or only some of these freedoms. Section [12.2](#business-models) talks in detail about how this can unfortunately happen even if a program is released under the GPL.

对“特定用户”的关注在这里尤为重要。某个特定程序的用户群的一部分人拥有这些自由的情况并不少见，而同一版本程序的其他用户则没有或只有其中的一部分自由。第 [12.2](#商业模式) 章节详细讨论了这种情况，即使程序是基于GPL发布的。

Many people refer to software with these freedoms as "Open Source." Besides having a different political focus from those who call such software by the name "Free Software"[^1], those who call the software "Open Source" are often focused on a side issue. Specifically, user access to the source code of a program is a prerequisite to make use of the freedom to modify. However, the important issue is what freedoms are granted in the license that applies to that source code.

许多人将具有这些自由的软件称为“开源”。除了与那些将此类软件称为“自由软件” [^1] 的人有着不同的政治关注点之外，将软件称为“开源”的人通常关注的是一个次要问题。具体来说，用户访问程序的源代码是实现修改自由的先决条件。然而，重要的问题是在适用于该源代码的许可证中授予了哪些自由。

[^1]: The political differences between the Free Software Movement and the Open Source Movement are documented on FSF's Web site at
<http://www.fsf.org/licensing/essays/free-software-for-freedom.html>.

[^1]: 自由软件运动和开源运动之间的政治分歧记录在FSF的网站上，网址为 <http://www.fsf.org/licensing/essays/free-software-for-freedom.html>.

Software freedom is only complete when no restrictions are imposed on how these freedoms are exercised. Specifically, users and programmers can exercise these freedoms noncommercially or commercially. Licenses that grant these freedoms for noncommercial activities but prohibit them for commercial activities are considered non-free. The Open Source Initiative (*OSI* ) (the arbiter of what is considered "Open Source") also regards such licenses as inconsistent with its "Open Source Definition".

只有当如何行使这些自由没有任何限制时，软件自由才是完整的。具体而言，用户和程序员可以非商业或商业的方式行使这些自由。那些仅限于非商业活动的一些自由，但禁止商业活动自由的许可，被认为是非自由的。开源促进会(*OSI*)（被认为是“开源”的仲裁者）也认为此类许可证与其“开源定义”不一致。

In general, software for which any of these freedoms are restricted in any way is called "nonfree" software. Some use the term "proprietary software" more or less interchangeably with "nonfree software". The FSF published a useful [explanation of various types of software and how they relate to one another.](http://www.gnu.org/philosophy/categories.html)

一般来说，以任何方式限制自由的软件被称为“非自由”软件。有些人或多或少地将“专有软件”一词与“非自由软件”互换使用。 FSF发布了一份有用的[对各种类型的软件以及它们之间的相互关系的解释](http://www.gnu.org/philosophy/categories.html)

Keep in mind that none of the terms "software freedom", "open source" and "free software" are known to be trademarked or otherwise legally restricted by any organization in any jurisdiction. As such, it's quite common that these terms are abused and misused by parties who wish to bank on the popularity of software freedom. When one considers using, modifying or redistributing a software package that purports to be Open Source or Free Software, one **must** verify that the license grants software freedom.

请记住，“软件自由”、“开源”和“免费软件”等术语均未被任何司法管辖区的任何组织注册商标，或以其他方式限制使用。这些术语被某些机构滥用和误用是很常见的现象，因为他们希望扩大软件自由的普及度。当考虑使用、修改或重新分发声称是开源或自由软件的软件包时，**必须**验证许可证是否授予软件自由。

Furthermore, throughout this text, we generally prefer the term "software freedom", as this is the least ambiguous term available to describe software that meets the Free Software Definition. For example, it is well known and often discussed that the adjective "free" has two unrelated meanings in English: "free as in freedom" and
"free as in price". Meanwhile, the term "open source" is even more confusing, because it appears to refer only to the "freedom to study", which is merely a subset of one of the four freedoms.

此外，在本文中，我们通常更喜欢“软件自由”一词，因为在那些描述符合自由软件定义的软件的一堆术语中，它的歧义最小。例如，大家经常讨论的英文中的形容词“自由”，它有两个不相关的含义：“使用的自由”和“价格的免费”。同时，“开源”一词更令人困惑，因为它似乎仅指“学习的自由”，这仅仅是四个自由中的一个。

The remainder of this section considers each of each component of software freedom in detail.

本节的其余部分将详细考虑软件自由的每个组成部分。

#### 1.1.1 The Freedom to Run

#### 1.1.1 执行程序的自由

The first tenet of software freedom is the user's fully unfettered right to run the program. The software's license must permit any conceivable use of the software. Perhaps, for example, the user has discovered an innovative use for a particular program, one that the programmer never could have predicted. Such a use must not be
restricted.

软件自由的首要原则是用户拥有完全不受限制地执行该程序的权利。该软件的许可证必须允许用户以任意方式使用软件。例如，也许用户发现了针对一个特定场景的创新用途，这个场景可能是程序员从未预料到的。不得限制此类用途。

It was once rare that this freedom was restricted by even proprietary software; but such is quite common today. Most End User License Agreements (EULAs) that cover most proprietary software typically restrict some types of uses. Such restrictions of any kind are an unacceptable restriction on software freedom.

曾经很少有使用软件的自由受到限制的情况，在专有软件中也很少见；但现在却很普遍。大多数基于最终用户许可协议（EULAs）的专有软件，通常限制某些类型的用途。任何这些形式的限制对软件自由来说，都是不可接受的。

#### 1.1.2 The Freedom to Change and Modify

#### 1.1.2 更改和修改程序的自由

Perhaps the most useful right of software freedom is the users' right to change, modify and adapt the software to suit their needs. Access to the source code and related build and installation scripts are an essential part of this freedom. Without the source code, and the ability to build and install the binary applications from that source, users cannot effectively exercise this freedom.

软件自由的最有用的权利也许是用户拥有根据自己的需求更改、修改和调整软件的权利。对源代码以及相关的构建和安装脚本的访问权限，是该自由的重要组成部分。如果没有源代码，以及基于该源码构建和安装二进制应用程序的脚本，用户就无法有效地行使这种自由。

Programmers directly benefit from this freedom. However, this freedom remains important to users who are not programmers. While it may seem counterintuitive at first, non-programmer users often exercise this freedom indirectly in both commercial and noncommercial settings. For example, users often seek noncommercial help with the software on email lists and in user groups. To make use of such help they must either have the freedom to recruit programmers who might altruistically assist them to modify their software, or to at least follow rote instructions to make basic modifications themselves.

程序员是这种自由的直接受益者。但是，这种自由对于非程序员的用户来说也很重要。虽然看起来似乎有点违反直觉，但非程序员用户通常在商业和非商业环境中，间接行使这种自由。例如，用户经常在电子邮件列表和用户群组中需求软件上的非商业性帮助。为了能够使用这种便利，必须允许他们自由地招募可能会免费帮助他们修改软件的程序员，或者允许他们按照使用说明可以自己进行基本的修改。

More commonly, users also exercise this freedom commercially. Each user, or group of users, may hire anyone they wish in a competitive free market to modify and change the software. This means that companies have a right to hire anyone they wish to modify their Free Software. Additionally, such companies may contract with other
companies to commission software modifications.

更常见的是，用户还可以在商业上行使这种自由。每个用户或一组用户都可以在竞争激烈的自由市场中，雇用他们希望的任何人来修改和更改软件。这意味着公司有权雇用任何愿意修改其免费软件的人。此外，公司可以与其他公司签订合同，委托进行软件修改。

#### 1.1.3 The Freedom to Copy and Share

#### 1.1.3 复制和分享软件的自由

Users share Free Software in a variety of ways. Software freedom advocates work to eliminate a fundamental ethical dilemma of the software age: choosing between obeying a software license and friendship (by giving away a copy of a program to your friend who likes the software you are using). Licenses that respect software
freedom, therefore, permit altruistic sharing of software among friends.

用户以多种方式分享自由软件。软件自由倡导者致力于消除软件时代的一个基本道德困境：在遵守软件许可和友谊之间做出选择（当你的朋友喜欢你正在使用的软件时，赠送一份程序副本给他）。 因此，尊重软件自由的许可证允许在朋友之间无私地分享软件。

The commercial environment also benefits from this freedom. Commercial sharing includes selling copies of Free Software: that is, Free Software can be distributed for any monetary price to anyone. Those who redistribute Free Software commercially also have the freedom to selectively distribute (i.e., you can pick your customers) and to set prices at any level that redistributor sees fit.

商业环境也得益于这种自由。商业共享包括出售自由软件的副本：也就是说，可以用任何货币价格将自由软件分发给其他人。那些以商业方式重新分发自由软件的人，也可以有选择地自由分发（如可以选择你自己的客户），并可以自行设置合适的价格水平。

Of course, most people get copies of Free Software very cheaply (and sometimes without charge). The competitive free market of Free Software tends to keep prices low and reasonable. However, if someone is willing to pay billions of dollars for one copy of the GNU Compiler Collection, such a sale is completely permitted.

当然，大多数人都可以非常便宜地获得自由软件的副本（有时甚至是免费的）。竞争激烈的自由软件市场倾向于保持低价和合理的价格。但是如果真有人愿意花费数十亿美元购买一份GNU编译集，这也是完全允许的。

Another common instance of commercial sharing is service-oriented distribution. For example, some distribution vendors provide immediate security and upgrade distribution via a special network service. Such distribution is not necessarily contradictory with software freedom.

商业共享的另一个常见方式是面向服务的分发。例如，一些分发供应商通过特殊的网络服务提供即时安全和升级服务。这种分发方式不一定与软件自由相矛盾。

(Section [12.2](#business-models) of this tutorial talks in detail about some common Free Software business models that take advantage of the freedom to share commercially.)

（本教程的[第12.2章](#商业模式)部分详细讨论了一些常见的利用商业实现自由软件的自由共享的业务模式。）

#### 1.1.4 The Freedom to Share Improvements

#### 1.1.4 分享改进的自由

The freedom to modify and improve is somewhat empty without the freedom to share those improvements. The software freedom community is built on the pillar of altruistic sharing of improved Free Software. Historically it was typical for a Free Software project to sprout a mailing list where improvements would be shared freely among members of the development community. [^2] Such noncommercial sharing is the primary reason that Free Software thrives.

如果没有分享改进的自由，修改和改进的自由多少有点空洞。软件自由社区建立在无私共享改进的自由软件的基础上。从历史上看，自由软件项目的典型做法是建立一个邮件列表，开发社区的成员可以在其中免费分享改进的内容。[^2] 这种非商业性质的共享方式是自由软件蓬勃发展的主要原因。

[^2]: This is still commonly the case, though today there are additional ways of sharing Free Software.

[^2]: 现在这仍然是常见的情况，尽管现在已经有其他共享自由软件的方法。

Commercial sharing of modified Free Software is equally important. For commercial support to exist in a competitive free market, all developers -- from single-person contractors to large software companies -- must have the freedom to market their services as augmenters of Free Software. All forms of such service marketing must
be equally available to all.

修改后的自由软件的商业共享同样重要。为了在竞争激烈的自由市场中提供商业支持，所有的开发人员——从个人承包商到大型软件公司——都应该可以自由地将他们的服务作为自由软件的补充进行销售。这种形式的服务营销必须对所有人一视同仁。

For example, selling support services for Free Software is fully permitted. Companies and individuals can offer themselves as "the place to call" when software fails or does not function properly. For such a service to be meaningful, the entity offering that service needs the right to modify and improve the software for the customer to correct any problems that are beyond mere user error.

例如，销售免费软件的支持服务是完全允许的。当软件出现故障或无法正常运行时，公司和个人可以将自己作为“呼叫客服”。为了使此类服务有意义，提供该服务的实体需要有权为客户修改和改进软件，以纠正任何超出用户错误的问题。

Software freedom licenses also permit any entity to distribute modified versions of Free Software. Most Free Software programs have a "standard version" that is made available from the primary developers of the software. However, all who have the software have the "freedom to fork" -- that is, make available nontrivial modified versions of the software on a permanent or semi-permanent basis. Such freedom is central to vibrant developer and user interaction.

软件自由许可证还允许任何实体分发自由软件的修改版本。大多数自由软件程序都有一个“标准版本”，可以从软件的主要开发人员那里获得。然而，所有拥有该软件的人都有“分叉自由”——也就是说，可以永久或半永久地提供软件的重要修订版本。这种自由是充满活力的开发人员和用户交互的核心。

Companies and individuals have the right to make true value-added versions of Free Software. They may use freedom to share improvements to distribute distinct versions of Free Software with different functionality and features. Furthermore, this freedom can be exercised to serve a disenfranchised subset of the user community. If the
developers of the standard version refuse to serve the needs of some of the software's users, other entities have the right to create a long- or short-lived fork to serve that sub-community.

公司和个人有权制作的自由软件的增值版本。他们可以自由地改进，并分享具有不同功能和特性的自由软件版本。此外，这种自由可以用来服务于被剥夺权力的用户群体。如果标准版本的开发人员拒绝满足某些软件用户的需求，则其他实体有权创建一个长期或短期的分支，提供服务满足于这些软件用户。

### 1.2 How Does Software Become Free?

### 1.2 软件是如何变得自由的？

The previous section set forth key freedoms and rights that are referred to as "software freedom". This section discusses the licensing mechanisms used to enable software freedom. These licensing mechanisms were ultimately created as a community-oriented "answer" to the existing proprietary software licensing mechanisms. Thus, first, consider carefully why proprietary software exists in the first place.

上一节阐述了被称为“软件自由”的一些关键自由和权利。本节讨论用于实现软件自由的许可机制。这些许可机制被看作是将现有专有软件许可机制转变为面向社区机制的“答案”所在。 因此，首先要仔细考虑为什么会有专有软件存在。

The primary legal regime that applies to software is copyright law. Proprietary software exists at all only because copyright law governs software.[^3] Copyright law, with respect to software, typically governs copying, modifying, and redistributing that software (For details of this in the USA, see [§106](http://www.copyright.gov/title17/92chap1.html#106) and [§117](http://www.copyright.gov/title17/92chap1.html#117) of [Title17](http://www.law.cornell.edu/uscode/text/17) of the *United States Code*).[^4] By law (in the USA and in most other jurisdictions), the copyright holder (most typically,the author) of the work controls how others may copy, modify and/or distribute the work. For proprietary software, these controls are used to prohibit these activities. In addition, proprietary software distributors further impede modification in a practical sense by distributing only binary code and keeping the source code of the software secret.

适用于软件的主要法律制度是版权法。专有软件的存在完全是因为版权法对软件的管理规定。[^3]关于软件的版权法，主要是对软件的复制、修改和再发行的管理规定（有关美国的详细信息，请参阅《美国法典》[第17篇](http://www.law.cornell.edu/uscode/text/17)的[§106](http://www.copyright.gov/title17/92chap1.html#106)和[§117](http://www.copyright.gov/title17/92chap1.html#117)）。[^4] 根据法律（在美国和大多数其他司法管辖区），作品的版权持有者（通常是作者本人） 可以控制其他人如何复制、修改和/或分发作品。专有软件的这些控制行为禁止了软件的相关操作。此外，专有软件分销商只发行二进制可执行代码，严格保密源代码，这也进一步阻碍了实际意义上的代码修改。

[^3]: This statement is admittedly an oversimplification. Patents and trade secrets can cover software and make it effectively non-Free, and one can contract away their rights and freedoms regarding software, or source code can be practically obscured in binary-only distribution without reliance on any legal system. However, the primary control mechanism for software is copyright, and therefore this section focuses on how copyright restrictions make software proprietary.

[^3]: 诚然，这种说法过于简单化了。专利和商业秘密可以要求软件保密，使其成为非自由软件，并且可以通过合同剥夺他们在软件方面的权利和自由，或者源代码实际上可以在不依赖于任何法律制度的情况下，以二进制形式分发。但是，软件的主要控制机制是版权，因此本节重点讨论版权限制如何使软件成为专有软件。

[^4]: Copyright law in general also governs "public performance" of copyrighted works. There is no generally agreed definition for public performance of software and both GPLv2 and GPLv3 do not restrict public performance.

[^4]: 版权法一般也适用于版权作品的“公开性能”。对于软件的公开性能没有普遍认可的定义，GPLv2和GPLv3都不限制公开性能。

Copyright is not a natural state, it is a legal construction. In the USA, the Constitution permits, but does not require, the creation of copyright law as federal legislation. Software, since it is an "original work of authorship fixed in any tangible medium of expression ... from which they can be perceived, reproduced, or otherwise communicated, either directly or with the aid of a machine or device" (as stated in [17 USC](http://www.law.cornell.edu/uscode/text/17/102) [§ 102)](http://www.law.cornell.edu/uscode/text/17/102), is thus covered by the statute, and is copyrighted by default.

版权不是一种自然状态，它是一种法律结构。在美国，宪法允许但不要求将版权法作为联邦立法。软件，因为它是“固定在任何有形表达媒介中的原创作品……可以直接或借助机器/设备从中感知、复制或以其他方式传播”（如 [《美国法典》第17篇](http://www.law.cornell.edu/uscode/text/17/102) [第§102章节](http://www.law.cornell.edu/uscode/text/17/102)所述)，因此受法规保护，默认情况下受版权保护。

However, software, in its natural state without copyright, is Free Software. In an imaginary world with no copyright, the rules would be different. In this world, when you received a copy of a program's source code, there would be no default legal system to restrict you from sharing it with others, making modifications, or redistributing those modified versions.[^5]

但是，在没有版权的自然状态下，软件是自由软件。在没有版权的虚拟世界中，规则会有所不同。在虚拟世界上，当你收到一个程序的源代码副本时，不会有默认的法律制度来限制你与他人共享、进行修改或重新分发这些修改后的版本。[^5]

[^5]: Note that this is again an oversimplification; the complexities with this argument are discussed in Section [1.2.3.](#software-and-non-copyright-legal-regimes)

[^5]: 注意，这里又将情况给简化处理了；关于这一争论的复杂情况的讨论详见[1.2.3 章节](#software-and-non-copyright-legal-regimes)

Software in the real world is copyrighted by default and is automatically covered by that legal system. However, it is possible to move software out of the domain of the copyright system. A copyright holder can often *disclaim* their copyright. (For example, under USA copyright law it is possible for a copyright holder to engage in
conduct resulting in abandonment of copyright.) If copyright is disclaimed, the software is effectively no longer restricted by copyright law. Software not restricted by copyright is in the "public domain."

现实世界中的软件默认受版权保护，并自动受该法律体系保护。但是，可以将软件移出版权系统的范围。版权所有者通常可以*放弃*他们的版权。（例如，根据美国版权法，版权所有者可以实施某些操作，放弃版权。）如果放弃版权，则该软件实际上不再受版权法的限制。不受版权限制的软件属于“公共领域软件”。

#### 1.2.1 Public Domain Software

#### 1.2.1 公共领域软件

In the USA and other countries that are parties to the Berne Convention on Copyright, software is copyrighted automatically by the author when she fixes the software in a tangible medium. In the software world, this usually means typing the source code of the software into a file.

在美国和其他加入《伯尔尼版权公约》的国家，当作者将软件固定在有形介质中时，软件自动受到版权保护。在软件世界中，这通常意味着将软件的源代码输入到文件中。

Imagine if authors could truly disclaim those default controls of copyright law. If so, the software is in the public domain --- no longer covered by copyright. Since copyright law is the construction allowing for most restrictions on software (i.e., prohibition of copying, modification, and redistribution), removing the software from the copyright system usually yields software freedom for its users.

想象一下，如果作者真的放弃了版权法的默认控制。如果是这样，该软件就属于公共领域 --- 不再受版权保护。由于版权法是允许对软件进行操作限制（如禁止复制、修改和重新分发）的结构定义，因此从版权系统中删除软件通常会为其用户带来软件自由。

Carefully note that software truly in the public domain is *not* licensed in any way. It is confusing to say software is "licensed for the public domain," or any phrase that implies the copyright holder gave express permission to take actions governed by copyright law.

请注意，真正属于公共领域的软件*未*以任何方式获得许可。关于软件“已获得公共领域许可”，或任何关于版权所有者明确允许采取受版权法管辖的行为的暗示说法，都是令人困惑的。

Copyright holders who state that they are releasing their code into the public domain are effectively renouncing copyright controls on the work. The law gave the copyright holders exclusive controls over the work, and they chose to waive those controls. Software that is, in this sense, in the public domain is conceptualized by the developer as having no copyright and thus no license. The software freedoms discussed in Section [1.1](#the-free-software-definition) are all
granted because there is no legal system in play to take them away.

如果版权所有者声明将其代码发布到公共领域，实际上他就放弃了对作品的版权控制。法律赋予版权所有者对作品的独占控制权，他们可以选择放弃这些控制权。从这个意义上说，处于公共领域的软件被开发人员认定为没有版权，因此也就没有许可证。第[1.1] 节（#the-free-software-definition）中讨论的软件自由都是被授予的，因为没有法律制度可以剥夺这些自由。

Admittedly, a discussion of public domain software is an oversimplified example. Because copyright controls are usually automatically granted and because, in some jurisdictions, some copyright controls cannot be waived (see Section [1.2.4](#non-usa-copyright-regimes) for further discussion), many copyright holders sometimes incorrectly believe a work has been placed in the public domain. Second, due to aggressive lobbying by the entertainment industry, the "exclusive Right" of copyright, that was supposed to only exist for "Limited Times" according to the USA Constitution, appears to be infinite: simply purchased on the installment plan rather than in whole. Thus, we must assume no works of software will fall into the public domain merely due to the passage of time.

诚然，对公共领域软件的讨论是一个过于简单化的例子。因为版权控制通常是自动授予的，并且在某些司法管辖区，某些版权控制不能被放弃（请参考第 [1.2.4] 节（#non-usa-copyright-regimes）以了解进一步的讨论），许多版权所有者有时会错误地认为作品已经发布到了公共领域。其次，由于娱乐业的积极游说，根据美国宪法规定，版权的“专有权”本应仅存在于“有限时间”，但看起来似乎是无限的：只是分期付款购买，而不是全部购买。因此，我们必须假设没有任何软件作品会因为时间的流逝而落入公共领域。

Nevertheless, under USA law it is likely that the typical disclaimers of copyright or public domain dedications we see in the Free Software world would be interpreted by courts as copyright abandonment, leading to a situation in which the user effectively receives a maximum grant of copyright freedoms, similar to a maximally-permissive Free Software license.

然而，根据美国法律，我们在自由软件世界中看到的典型的版权免责声明，或公共领域专有申明，可能会被法院解释为放弃版权，从而授予了用户实际上最大程度的版权自由，类似于最大程度的自由软件许可证。

The best example of software known to truly be in the public domain is software that is published by the USA government. Under [17 USC 101 105,](http://www.law.cornell.edu/uscode/text/17/105) all works published by the USA Government are not copyrightable in the USA.

目前所知的真正属于公共领域的软件最好的例子，是由美国政府发布的软件。根据《美国法典》[第17章101-105](http://www.law.cornell.edu/uscode/text/17/105)，在美国，美国政府出版的所有作品均不受版权保护。

#### 1.2.2 Why Copyright Free Software?

#### 1.2.2 为什么需要版权自由的软件？

If simply disclaiming copyright on software yields Free Software, then it stands to reason that putting software into the public domain is the easiest and most straightforward way to produce Free Software. Indeed, some major Free Software projects have chosen this method for making their software Free. However, most of the Free Software in existence *is* copyrighted. In most cases (particularly in those of FSF and the GNU Project), this was done due to very careful planning.

假如只是放弃了对软件的版权就产生了自由软件，那么将软件发布到公共领域是产生自由软件最简单和最直接的方式，这看起来是理所当然的。事实上，一些主要的自由软件项目已经选择了这种方法来使他们的软件成为自由软件。然而，现存的大多数自由软件*是*受版权保护的。在大多数情况下（特别是在FSF和GNU项目中），这些项目的规划都非常仔细。

Software released into the public domain does grant freedom to those users who receive the standard versions on which the original author disclaimed copyright. However, since the work is not copyrighted, any nontrivial modification made to the work is fully copyrightable.

当原作者将作品发布到公共领域以否认版权时，就将软件自由授予了那些已经收到标准版本的用户。虽然原作品不受版权保护，但对原作品所做的任何重要修改都是受版权保护的。

Free Software released into the public domain initially is Free, and perhaps some who modify the software choose to place their work into the public domain as well. However, over time, some entities will choose to proprietarize their modified versions. The public domain body of software feeds the proprietary software. The public commons disappears, because fewer and fewer entities have an incentive to contribute back to the commons. They know that any of their competitors can proprietarize their enhancements. Over time, almost no interesting work is left in the public domain, because nearly all new work is done by proprietarization.

起初，发布到公共领域的自由软件是自由的，一些修改软件的人也会选择将他们的作品发布到公共领域。然而，随着时间的推移，一些实体选择将其修改后的版本专有化。公共领域的软件主体为专有软件提供了支持。随着越来越少的实体有动力回馈公共领域，公共资源就消失了。他们知道，任何竞争对手都可以将自己的增强功能专有化。随着时间的推移，公共领域几乎不会留下任何有趣的项目，因为几乎所有的新项目都是由专有化的实体完成的。

A legal mechanism is needed to redress this problem. FSF was in fact originally created primarily as a legal entity to defend software freedom, and that work of defending software freedom is a substantial part of its work today. Specifically because of this "embrace, proprietarize and extend" cycle, FSF made a conscious choice to copyright its Free Software, and then license it under "copyleft" terms. Many, including the developers of the kernel named Linux, have chosen to follow this paradigm.

因此，需要一个法律机制来解决这个问题。事实上，FSF最初主要是作为一个捍卫软件自由的法律实体而创建的，而捍卫软件自由是其现在工作的重要组成部分。特别是由于这种“拥抱、专有化和扩展”的循环，FSF有意识地选择对其自由软件进行版权保护，然后根据“copyleft”条款对其进行许可。许多人，包括Linux内核的开发人员，都选择遵循这种模式。

Copyleft is a strategy of utilizing copyright law to pursue the policy goal of fostering and encouraging the equal and inalienable right to copy, share, modify and improve creative works of authorship. Copyleft (as a general term) describes any method that utilizes the copyright system to achieve the aforementioned goal. Copyleft as a concept is usually implemented in the details of a specific copyright license, such as the [GNU General Public License (GPL)](#_bookmark259) and the Creative Commons Attribution Share Alike License (the latter of which is the license of this work itself). Copyright holders of creative work can unilaterally implement these licenses for their own works to build communities that collaboratively share and improve those copylefted creative works.

Copyleft是一种利用版权法来实现政策目标的策略，意在促进和鼓励平等和不可剥夺的复制、共享、修改和改进原创作品的权利。Copyleft（作为一个通用术语）描述了利用版权系统实现上述目标的一些方法。Copyleft作为一个概念，通常在特定版权许可证的细节中体现，例如[GNU 通用公共许可 (GPL)](#_bookmark259) 和（Creative Commons Attribution Share Alike License）知识共享署名共享类似许可（后者是这个项目本身的许可证）。创意作品的版权持有者可以单方面为自己的作品实施这些许可，建立社区，共同分享和改进这些copyleft的创意作品。

Copyleft uses functional parts of the copyright system to achieve an unusual result (legal protection for free sharing). Copyleft modifies, or "hacks" copyright law, which is usually employed to strengthen the rights of authors or publishers, to strengthen instead the rights of users. Thus, Copyleft is a legal strategy and mechanism to defend, uphold and propagate software freedom. The basic technique of copyleft is as follows: copyright the software, license it under terms that give all the software freedoms, but use the copyright law controls to ensure that all who receive a copy of the software have equal rights and freedom. In essence, copyleft grants freedom, but forbids others to forbid that freedom to anyone else along the distribution and modification chains.

Copyleft使用版权系统的功能部分来实现一个不同寻常的结果（免费共享的法律保护）。Copyleft修改或“破解”版权法以加强用户的权利，而版权法通常用于加强作者或出版商的权利。因此，Copyleft是一种捍卫、支持和传播软件自由的法律策略和机制。Copyleft的基本原则为：对软件进行版权保护，在赋予所有软件自由的条款下颁发软件许可证，但使用版权法控制，以确保所有获得软件副本的人都享有平等的权利和自由。本质上，copyleft赋予用户自由，也禁止某些用户的垄断行为，即通过控制软件的分发和修改的后续链条限制其他人的软件自由。

Copyleft's "reciprocity" or "share and share alike" rule protects both developers, who avoid facing a "prioritized" competitor of their project, and users, who can be sure that they will have all four software freedoms --- not only in the present version of the program they use, but in all its future improved versions. Copyleft is a
general concept. Much like ideas for what a computer might do must be *implemented* by a program that actually does the job, so too must copyleft be implemented in some concrete legal structure. "Share and share alike" is a phrase that is used often enough to explain the concept behind copyleft, but to actually make it work in the real world, a true implementation in legal text must exist, written as a "copyright license". The GPL implements the concept of copyleft for software-oriented and other functional works of a technical nature. The "CC BY SA" license implements copyleft for works of textual, musical and visual authorship, such as this tutorial.

Copyleft的“互惠”或“共享和类似共享”的原则同时保护了开发者和用户，开发者可以避免面对他们项目的“优先”竞争对手，用户可以确保他们将拥有所有的四种软件自由——不仅限于当前他们使用的程序版本，也包括未来的所有改进版本中。Copyleft是一个笼统的概念。就像计算机可以做什么的想法必须由一个实际执行该任务的程序*实现*一样，copyleft也必须在某些具体的法律结构中实现。“共享和类似共享”这个短语经常被用来解释copyleft背后的概念，但要真正让它在现实世界中发挥作用，必须有一个真正的法律文本实现，即“版权许可”。GPL为面向软件和其他技术性质的功能性作品实现了copyleft的概念。 “CC BY SA”许可证为文本、音乐和视觉作者的作品提供了copyleft版权保护，例如本教程。

Copyleft advocates often distinguish between the concept of a "strong copyleft" or a "weak copyleft". However, "strong vs. weak" copyleft is not a dichotomy, it's a spectrum. The strongest copylefts strive to the exclusive rights that copyright grants to authors as extensively as possible to maximize software freedom.

Copyleft倡导者经常区分“强copyleft”或“弱copyleft”的概念。然而，“强与弱”copyleft并不是二分法原则，而是一个范围。最强的copyleft版权力图授予作者尽可能广泛的专有权，以最大限度地提高软件自由度。

As a copyleft gets "weaker", the copyleft license typically makes "trade offs" that might impede software freedom, but reach other tactic goals for the community of users and developers of the work.

随着copyleft变得“微弱”，copyleft许可证可能会做一些"权衡"，可能会阻碍软件自由，但会实现用户和项目开发者社区的其他策略目标。

In other words, strong copyleft licenses place the more requirements on how "the work" is licensed. The unit of copyright law is "the work". In that sense, the "work" referenced by the licenses is anything that can be copyrighted or will be subject to the terms of copyright law. Strong copyleft licenses exercise their scope fully.
Anything which is "a work" or a "work based on a work" licensed under a strong copyleft is subject to its requirements, including the requirement of complete, corresponding source code [^6]. Thus, copyleft licenses, particularly strong ones, seek to ensure the same license covers every version of "work based on the work", as recognized by local copyright law, and thereby achieve the specific strategic policy aim of ensuring software freedom for all users, developers, authors, and readers who encounter the copylefted work.

换句话说，较强的copyleft许可对“作品”的许可方式提出了更高的要求。是以“作品”为单位进行版权法认定的。从这个意义上说，许可证所指的“作品”是任何可以受版权保护或受版权法条款约束的东西。较强的copyleft许可证充分发挥了其作用。任何基于较强的copyleft许可的“作品”或“基于作品的作品”都必须遵守其要求，包括所有相应的源代码 [^6]。因此，copyleft许可证，特别是较强的许可证，旨在确保相同的许可证涵盖当地版权法认可的“基于作品的作品”的所有版本，从而确保实现与当前copyleft版权作品相关的所有用户、开发者、作者和读者的软件自由的特定战略目标。

[^6]: Copyleft communities' use of the term "strong copyleft" is undoubtedly imprecise. For example, most will call the GNU GPL a "strong copyleft" license, even though the GPL itself has various exceptions, such as the [GPLv3's system library exception](#the-system-library-exception) written into the text of the license itself. Furthermore, the copyleft community continues to debate where the a license cross the line from "strong copyleft" to "license that fails to respect software freedom", although ultimately these debates are actually regarding whether the license fits [Free Software definition](#the-free-software-definition) at all.

[^6]: Copyleft社区使用术语“强copyleft”无疑是不准确的。例如，大多数人会认为GNU GPL是“强copyleft”许可证，但其实GPL本身有多种例外情况，比如许可证文本中的[GPLv3的系统库例外情况](#the-system-library-exception)。此外，copyleft社区一直在争论许可证从“强copyleft”到“不尊重软件自由的许可证”之间的界限，尽管最终这些争论实际上是关于许可证是否符合 [自由软件的定义](#the-free-software-definition)

#### 1.2.3 Software and Non-Copyright Legal Regimes

#### 1.2.3 软件和非版权法律制度

The use, modification and distribution of software, like many endeavors, simultaneously interacts with multiple different legal regimes. As was noted early via footnotes, copyright is merely the *most common way* to restrict users' rights to copy, share, modify and/or redistribute software. However, proprietary software licenses typically use every mechanism available to subjugate users. For example:

与许多努力一样，软件的使用、修改和分发同时与多种不同的法律制度相互制约。正如早期通过脚注指出的那样，版权只是限制用户复制、共享、修改和/或重新分发软件的*最常见的方式*。但是专有软件许可证通常会使用所有各种机制来控制用户。例如：

- Unfortunately, despite much effort by many in the software freedom community to end patents that read on software (i.e., patents on computational ideas), they still exist. As such, a software program might otherwise seem to be unrestricted, but a patent might read on the software and ruin everything for its users.[^7]

- 软件自由社区中的人做了很多努力，希望能终止通过读取软件内容生成专利的行为（即跟软件思想相关的专利），但还是未能成功。因此，一个软件程序可能看起来不受限制，但有些人可能会读取该软件并生成专利，进而毁掉其他用户的一切。[^7]

[^7]: See [6,](#_bookmark68) [7.5,](#gplv2-7-give-software-liberty-or-give-it-death) [9.14](#gplv3-11-explicit-patent-licensing) for more discussion on how
the patent system interacts with copyleft, and read Richard M. Stallman's essay, [*Let's Limit the Effect of Software Patents, Since
We Can't Eliminate Them*](http://www.wired.com/opinion/2012/11/richard-stallman-software-patents/) for more information on the problems these patents present to society.

[^7]: 有关专利制度如何与copyleft交互的更多讨论，请参见[第6章](#_bookmark68)、[第7.5节](#gplv2-7-give-software-liberty-or-give-it-death)和[第9.14节](#gplv3-11-explicit-patent-licensing)，也请阅读Richard M. Stallman的文章 [*如果无法消除软件专利的影响就限制它吧*](http://www.wired.com/opinion/2012/11/richard-stallman-software-patents)，了解有关这些专利给社会带来的问题的更多信息。

Digital Restrictions Management (usually called *DRM* ) is often used to impose technological restrictions on users' ability to exercise software freedom that they might otherwise be granted.[^8] The simplest (and perhaps oldest) form of DRM, of course, is separating software source code (read by humans),
from their compiled binaries (read only by computers). Furthermore, [17 USC 1201](http://www.law.cornell.edu/uscode/text/17/1201) often prohibits users legally from circumventing some of these DRM systems.

虽然授予了软件自由，但数字限制管理（也被称为*DRM*）通常对用户行使软件自由的能力施加技术限制。[^8]最简单的（也是最古老的）DRM的形式，是将软件源代码（人类可阅读的）与编译的二进制文件（仅由计算机读取）分开。此外，[《美国法典》第17篇 第§102章节](http://www.law.cornell.edu/uscode/text/17/1201) 通常从法律层面禁止用户规避DRM系统中的一些。

[^8]: See [9.5](#gplv3s-views-on-drm-and-device-lock-down) for more information on how GPL deals with this issue.

[^8]: 想要了解GPL如何处理这类问题，可以查看[第9.5节](#gplv3s-views-on-drm-and-device-lock-down)

Most EULAs also include a contractual agreement that bind users further by forcing them to agree to a contractual, prohibitive software license before ever even using the software.

大多数EULA协议还包括一份用户合同，强制用户在使用软件之前同意合同性的、禁止性的软件许可来进一步约束用户。

Thus, most proprietary software restricts users via multiple interlocking legal and technological means. Any license that truly respect the software freedom of all users must not only grant appropriate copyright permissions, but also *prevent* restrictions from other legal and technological means like those listed above.

所以，大多数专有软件会通过多种相互关联的法律和技术手段来限制用户。任何真正尊重用户软件自由的许可证，不仅必须授予适当的版权许可，还必须*防止*上述其他法律和技术手段的限制。

#### 1.2.4 Non-USA Copyright Regimes

#### 1.2.4 美国之外的版权制度

Generally speaking, copyright law operates similarly enough in countries that have signed the Berne Convention on Copyright, and software freedom licenses have generally taken advantage of this international standardization of copyright law. However, copyright law does differ from country to country, and commonly, software freedom licenses like the GPL must be considered under the copyright law in the jurisdiction where any licensing dispute occurs.

一般来说，在签署了《伯尔尼版权公约》的国家中，版权法的运作非常相似，软件自由许可通常采用了国际标准化的版权法。然而，不同国家的版权法确实有所不同，通常像GPL这样的软件自由许可，必须在发生许可纠纷的司法管辖区，根据版权法予以考虑。

Those who are most familiar with the USA's system of copyright often are surprised to learn that there are certain copyright controls that cannot be waived nor disclaimed. Specifically, many copyright regimes outside the USA recognize a concept of moral rights of authors. Typically, moral rights are fully compatible with respecting software freedom, as they are usually centered around controls that software freedom licenses generally respect, such as the right of an authors to
require proper attribution for their work.

那些最熟悉美国版权制度的人通常会惊讶地发现，有些版权控制既不能放弃也不能否认。具体来说，美国以外的许多版权制度都承认作者的道德权利概念。通常，道德权利与尊重软件自由完全兼容，因为道德权利通常是以软件自由许可所允许的控制为中心，例如作者要求对其作品进行适当归属的权利。

### 1.3 A Community of Equality

### 1.3 平等的社区

The previous section described the principles of software freedom, a brief introduction to mechanisms that typically block these freedoms, and the simplest ways that copyright holders might grant those freedoms to their users for their copyrighted works of software. The previous section also introduced the idea of *copyleft* : a licensing mechanism to use copyright to not only grant software freedom to users, but also to uphold those rights against those who might seek to curtail them.

上一节描述了软件自由的原则，简要介绍了阻止这些自由的一些机制，以及版权所有者授予用户软件自由的最简单的方式，允许用户使用受版权保护的软件作品。同时还介绍了*copyleft* 的概念：一种使用版权的许可机制，不仅可以授予用户软件自由，还可以维护这些权利，防止试图限制这些权利的人。

Copyleft, as defined in [1.2.2,](#why-copyright-free-software) is a general term for this mechanism. The remainder of this text will discuss details of various real-world implementations of copyleft --most notably, the GPL.

如[第1.2.2节](#why-copyright-free-software)的Copyleft定义，它是该机制的一个通用术语。本书的其他章节将会讨论现实世界中copyleft的一些实现方式 -- 最值得注意的就是GPL。

This discussion begins first with some general explanation of what the GPL is able to do in software development communities. After that brief discussion in this section, deeper discussion of how GPL accomplishes this in practice follows in the next chapter.

讨论首先会解释GPL在软件开发社区中的作用。本节只进行简短讨论，下一章将深入讨论GPL如何在实践中实现这一点。

Simply put, though, the GPL ultimately creates a community of equality for both business and noncommercial users.

不过，简单来说，最终GPL为商业用户及非商业用户创建了一个平等的社区。

#### 1.3.1 The Noncommercial Community

#### 1.3.1 非商业社区

A GPL'd code base becomes a center of a vibrant development and user community. Traditionally, volunteers, operating noncommercially out of keen interest or "scratch an itch" motivations, produce initial versions of a GPL'd system. Because of the efficient distribution channels of the Internet, any useful GPL'd system is adopted quickly by noncommercial users.

GPL的代码库已经成为充满活力的开发者和用户社区的中心。一般来说，出于浓厚的兴趣爱好或“试一把”的动机，志愿者会以非商业的方式制作一个GPL系统的初始版本。由于互联网的高效分发渠道，任何有用的GPL系统都会很快被非商业用户所采用。

Fundamentally, the early release and quick distribution of the software gives birth to a thriving noncommercial community. Users and developers begin sharing bug reports and bug fixes across a shared intellectual commons. Users can trust the developers, because they know that if the developers fail to address their needs or abandon the project, the GPL ensures that someone else has the right to pick up development. Developers know that the users cannot redistribute their software without passing along the rights granted by the GPL, so they are assured that every one of their users is treated equally.

从根本上来说，软件的早期发布和快速分发催生了一个繁荣的非商业社区。用户和开发人员都在知识共享的社区中分享错误报告和修复补丁。用户非常信任开发人员，因为他们知道如果开发人员不能满足他们的需求或放弃项目，GPL协议能确保其他人有权接手并持续开发。开发人员知道，如果将GPL的权利授予用户，用户就没法二次分发他们的软件，因此他们需要确信每一位用户受到平等对待。

Because of the symmetry and fairness inherent in GPL'd distribution, nearly every GPL'd package in existence has a vibrant noncommercial user and developer base.

就是因为GPL分发协议的对称性和公平性，几乎每个GPL项目都拥有一个活跃的非商业用户和开发者群体。

#### 1.3.2 The Commercial Community

#### 1.3.2 商业群体

By the same token, nearly all established GPL'd software systems have a vibrant commercial community. Nearly every GPL'd system that has gained wide adoption from noncommercial users and developers eventually begins to fuel a commercial system around that software.

同样，几乎所有已建立的GPL软件系统都有一个充满活力的商业社区。每个获得非商业用户和开发人员拥护的GPL系统，最终几乎都开始围绕该软件为商业系统提供动力。

For example, consider the Samba file server system that allows Unix-like systems (including GNU/Linux) to serve files to Microsoft Windows systems. Two graduate students originally developed Samba in their spare time and it was deployed noncommercially in academic environments.[^9] However, very soon for-profit
companies discovered that the software could work for them as well, and their system administrators began to use it in place of Microsoft Windows NT file-servers. This served to lower the cost of running such servers by orders of magnitude. There was suddenly room in Windows file-server budgets to hire contractors to improve Samba. Some of the first people hired to do such work were those same two graduate students who originally developed the software.

例如，以Samba文件服务器系统为例，它允许类Unix系统（如GNU/Linux）向微软的Windows系统提供文件服务。Samb最初是由两名研究生在业余时间开发的，并在学术环境中部署，并未商业化。[^9] 之后很快商业公司就发现了该软件也适用于他们，公司的系统管理员开始使用它取代了微软的Windows NT文件服务器。这有助于将此类服务器的运行成本降低几个数量级。Windows文件服务器就有了多的预算空间，可以雇用承包商来改进Samba。最早受雇从事这项工作的正是最初开发该软件的两名研究生。

[^9]: See [Andrew Tridgell's "A bit of history and a bit of fun"](http://turtle.ee.ncku.edu.tw/docs/samba/history)

[^9]: 详情请看[Andrew Tridgell的《一点历史，一份趣味》](http://turtle.ee.ncku.edu.tw/docs/samba/history)

The noncommercial users, however, were not concerned when these two fellows began collecting paychecks off of their GPL'd work. They knew that because of the nature of the GPL that improvements that were distributed in the commercial environment could easily be folded back into the standard version. Companies are not permitted to
proprietarize Samba, so the noncommercial users, and even other commercial users are safe in the knowledge that the software freedom ensured by the GPL will remain protected.

当那两位学生开始从他们的GPL工作中获取报酬时，非商业用户也并不担心。他们知道，由于GPL的性质，在商业环境中实现的改进会很快地融入到标准版本。不允许任何公司将Samba私有化，非商业用户、其他商业用户都知道，GPL协议会确保软件自由将继续受到保护。

Commercial developers also work in concert with noncommercial developers. Those two now-long-since graduated students continue to contribute to Samba altruistically, but also get paid work doing it. Priorities change when a client is in the mix, but all the code is contributed back to the standard version. Meanwhile, many other
individuals have gotten involved noncommercially as developers, because they want to "cut their teeth on Free Software," or because the problems interest them. When
they get good at it, perhaps they will move on to another project, or perhaps they will become commercial developers of the software themselves.

商业开发商也会与非商业开发商合作。那两位已经毕业了的学生继续无私地为Samba做出贡献，但同时也获得了报酬。当有客户参与其中时，优先级会发生变化，但所有的代码都会回馈给标准版本。与此同时，许多其他人也作为开发者参与了非商业活动，因为他们想“在自由软件上小试牛刀”，或者是他们对这些问题感兴趣。当他们擅长编程时，也许会转向另一个项目，或者他们自己可能会成为软件的商业开发人员。

No party is a threat to another in the GPL software scenario because everyone is on equal ground. The GPL protects rights of the commercial and noncommercial contributors and users equally. The GPL creates trust, because it is a level playing field for all.

在GPL软件场景中，任何一方都不会对另外一方构成威胁，因为每个人都是平等的。GPL协议平等地保护了商业和非商业贡献者和用户的权利。GPL协议创造信任，因为它位所有人提供了公平的竞争环境。

#### 1.3.3 Law Analogy

#### 1.3.3 法律类比

In his introduction to Stallman's *Free Software, Free Society*, Lawrence Lessig draws an interesting analogy between the law and Free Software. He argues that the laws of a free society must be protected much like the GPL protects software. So that I might do true justice to Lessig's argument, I quote it verbatim:

在介绍Stellman的《自由软件、自由社会》时，Lawrence Lessig在法律和自由软件之间做了一个有趣的类比。他认为自由社会的法律也需要受到保护，就像GPL协议保护软件一样。为了能真正公正地对待Lessig的论点，我逐字引用了它：

A "free society" is regulated by law. But there are limits that any free society places on this regulation through law: No society that kept its laws secret could ever be called free. No government that hid its regulations from the regulated could ever stand in our tradition. Law controls. But it does so justly only when visibly. And law is visible only when its terms are knowable and controllable by those it regulates, or by the agents of those it regulates (lawyers, legislatures).

“自由社会”是受法律规范的。但是任何自由社会都通过法律对这种规定施加了限制：任何对法律保密的社会都不能被称为自由。任何向受监管者隐藏其法规的政府都无法立足于我们的传统。法律控制。但只有在显而易见的情况下，它才会这样做。法律只有在其条款可被监管者或监管者的代理人（律师、立法机关）知晓和控制时才是可见的。

This condition on law extends beyond the work of a legislature. Think about the practice of law in American courts. Lawyers are hired by their clients to advance their clients' interests. Sometimes that interest is advanced through litigation. In the course of this litigation, lawyers write briefs. These briefs in turn affect opinions written by judges. These opinions decide who wins a particular case, or whether a certain law can stand consistently with a constitution.

这种法律条件超出了立法机关的工作范围。想想美国法院的法律实践。律师受雇于他们的客户，目的是促进他们客户的利益。有时，这种利益是通过法律诉讼来推进的。在此诉讼过程中，律师撰写简报。这些简报反过来会影响法官撰写的意见。这些意见决定了在某一案件中谁会获胜，或者某项法律是否能够与宪法保持一致。

All the material in this process is free in the sense that Stallman means. Legal briefs are open and free for others to use. The arguments are transparent (which is different from saying they are good), and the reasoning can be taken without the permission of the original lawyers. The opinions they produce can be quoted in later briefs. They can be copied and integrated into another brief or opinion. The "source code" for American law is by design, and by principle, open and free for anyone to take. And take lawyers do---for it is a measure of a great brief that it achieves its creativity through the reuse of what happened before. The source is free; creativity and an economy is built upon it.

正如Stallman所说，这个过程中的所有材料都是免费的。法律简报是公开的，可供他人免费使用。论据透明（这不同于说它们是好的），无需原律师许可即可取证。他们提出的意见可以在以后的简报中引用。可以将它们复制并整合到另一份简报或意见中。美国法律的“源代码”在设计上和原则上都是开放的，任何人都可以免费使用。以律师的做法为例——因为这是一个伟大的简报的衡量标准，
它通过重用以前的案例来实现其创造力。来源是免费的；创造力和经济是建立在它之上的。

This economy of free code (and here I mean free legal code) doesn't starve lawyers. Law firms have enough incentive to produce great briefs even though the stuff they build can be taken and copied by anyone else. The lawyer is a craftsman; his or her product is public. Yet the crafting is not charity. Lawyers get paid; the public doesn't demand such work without price. Instead this economy flourishes, with later work added to the earlier.

这种免费代码经济（这里我指的是免费法律代码）不会让律师挨饿。律师事务所有足够的动力来制作出色的简报，即使他们制作的东西可以被其他任何人拿走和复制。律师是工匠；他或她的简报是公开的。然而，手工艺品不是慈善。律师得到报酬；公众不会要求律师无偿工作。取而代之的是，这种经济会蓬勃发展，后期的工作会逐渐添加到早期的工作中。

We could imagine a legal practice that was different --- briefs and arguments that were kept secret; rulings that announced a result but not the reasoning. Laws that were kept by the police but published to no one else. Regulation that operated without explaining its rule.

我们可以想象一种不同的法律实践——保持简报和论据的保密性；宣布结果但不宣布推理的裁决。警察遵守的法律，但不向其他人公开。没有解释规则的相关规定。

We could imagine this society, but we could not imagine calling it "free." Whether or not the incentives in such a society would be better or more efficiently allocated, such a society could not be known as free. The ideals of freedom, of life within a free society, demand more than efficient application. Instead, openness and transparency are the constraints within which a legal system gets built, not options to be added if convenient to the leaders. Life governed by software code should be no less.

我们可以想象这样的社会，但我们无法假装称它为“自由”。无论这个社会中的激励是否会得到更好或更有效的分配，这样的社会都不能被称为自由。自由的理想，自由社会中的生活，需要的不仅仅是有效的应用。相反，公开和透明是建立法律体系的约束条件，而不是领导者需要时可以随意添加的选项。由软件代码支配的生活应该不会少。

Code writing is not litigation. It is better, richer, more productive. But the law is an obvious instance of how creativity and incentives do not depend upon perfect control over the products created. Like jazz, or novels, or architecture, the law gets built upon the work that went before. This adding and changing is what creativity always is. And a free society is one that assures that its most important resources remain free in just this sense.[^10^](#_bookmark26)

代码编写不是法律诉讼。它更好、更丰富、更有生产力。但创造力和激励是不依赖于对所创造产品的完美与否的，法律就是一个明显的例子。就像爵士乐、小说或建筑一样，法律是建立在之前的作品之上的。这种添加和改变就是创造力的本质所在。一个自由的社会就是确保其最重要的资源在某种意义上保持免费。[^10]

[^10]: This quotation is Copyright c 2002, Lawrence Lessig. It is licensed under the terms of [the "Attribution License" version 1.0](http://creativecommons.org/licenses/by/1.0/) or any later version as published by Creative Commons.

[^10]: 此引文版权所有c 2002, Lawrence Lessig. 它根据[“署名许可”版本1.0](http://creativecommons.org/licenses/by/1.0/)或Createive Comments 发布的任何更新条款获得许可。

In essence, lawyers are paid to service the shared commons of legal infrastructure. Few citizens defend themselves in court or write their own briefs (even though they are legally permitted to do so) because everyone would prefer to have an expert do that job.

从本质上讲，律师是为法律基础设施的公共服务而工作的。很少有公民在法庭上为自己辩护或撰写自己的案情简报（即使法律允许他们这样做），每个人都更愿意让专家来做这项工作。

The Free Software economy is a market ripe for experts. It functions similarly to other well established professional fields like the law. The GPL, in turn, serves as the legal scaffolding that permits the creation of this vibrant commercial and noncommercial Free Software economy.

对于专家来说，自由软件经济是一个成熟的市场。它的功能类似于法律等其他成熟的专业领域。反过来，GPL协议又是一个法律脚手架，允许创建这个充满活力的商业和非商业的自由软件经济。


## CHAPTER 2 A TALE OF TWO COPYLEFT LICENSES

## 第2章 两个著佐权许可证的故事

While determining the proper methodology and criteria to yield an accurate count remains difficult, the GPL is generally considered one of the most widely used Free Software licenses. For most of its history --- for 16 years from June 1991 to June 2007 --- there was really only one version of the GPL, version 2.

尽管还没办法选择适当的方法和标准给出准确统计，但GPL是公认最广泛使用的自由软件许可证之一。在它大部分历史（从1991年6月到2007年6月的16年）中，GPL实际上只有一个版本，即第二版。

However, the GPL had both earlier versions before version 2, and, more well known, a revision to version

然而，GPL既有第二版之前的早期版本，也有更知名的第三版修订版。

### Historical Motivations for the General Public License

### 2.1 通用公共许可证的历史动因

The earliest license to grant software freedom was likely the Berkeley Software Distribution ("BSD") license. This license is typical of what are often called lax, highly permissive licenses. Not unlike software in the public domain, these non-copyleft licenses (usually) grant software freedom to users, but they do not go to any effort to uphold that software freedom for users. The so-called "downstream" (those who receive the software and then build new things based on that software) can restrict the software and distribute further.

最早的授予软件自由的许可证可能是伯克利软件分发（Berkeley Software Distribution，“BSD”）许可证。这个许可证是典型的、高度宽松的许可证，通常被称为“宽松许可证”。与公共领域的软件不一样，这些非著佐权许可证（通常）将软件自由授予用户，但它们并不为用户维护这种软件自由。所谓的 "下游"（那些收到软件后在该软件基础上添砖加瓦的人）可以限制该软件进一步分发。

The GNU's Not Unix ("GNU") project, which Richard M. Stallman ("RMS") founded in 1984 to make a complete Unix-compatible operating system implementation that assured software freedom for all. However, RMS saw that using a license that gave but did not assure software freedom would be counter to the goals of the GNU Project. RMS invented "copyleft" as an answer to that problem, and began using various copyleft licenses for the early GNU Project programs.[^1]

为了实现对完全兼容Unix的操作系统的应用、保证所有人的软件自由，Richard M. Stallman（RMS）于1984年创建“GUN Not Unix（GNU）”项目。然而，RMS发现使用许可证可以赋予却不能保证软件自由，这可能与GUN项目的目标背道而驰。于是RMS发明了“著佐权”来解决这个问题，并且开始在早期GNU项目程序中使用各种形式的著佐权许可证。[^1]

### Proto-GPLs And Their Impact

### 2.2 原始GPL及其影响

The earliest copyleft licenses were specific to various GNU programs. For example, The Emacs General Public License was likely the first copyleft license ever published. Interesting to note that even this earliest copyleft license contains a version of the well-known GPL copyleft clause:

最早的著佐权许可证是专门针对各种GNU程序的。例如，Emacs通用公共许可证可能是有史以来发布的第一个著佐权许可证。有趣的是，即使是这个最早的著佐权许可证也包含了著名的GPL著佐权条款的一个版本：

You may modify your copy or copies of GNU Emacs . . . provided that you also . . . cause the whole of any work that you distribute or publish, that in whole or in part contains or is a derivative of GNU Emacs or any part thereof, to be licensed at no charge to all third parties on terms identical to those contained in this License Agreement.

你可以修改你的GNU Emacs副本……如果你也……使你的任何全部或部分包含GNU Emacs或作为其衍生作品分发或发布的作品的整体，以与本许可协议中包含的条款相同的条款免费授权给所有第三方。

This simply stated clause is the fundamental innovation of copyleft. Specifically, copyleft *uses* the copy- right holders' controls on permission to modify the work to add a conditional requirement. Namely, downstream users may only have permission to modify the work if they pass along the same permissions on the modified version that came originally to them.

这个阐述简明的条款是著佐权的根本创新。具体来说，著佐权通过著作权所有者对修改作品的权限的控制，增加了一个条件，即：

[^1]: RMS writes more fully about this topic in his essay entitled simply [*The GNU Project*](http://www.gnu.org/gnu/thegnuproject.html) . For those who want to hear the story in his own voice, [speech recordings](http://audio-video.gnu.org/audio/) of his talk, *The Free Software Movement and the GNU/Linux Operating System* are also widely available


下游用户只有在将他们最初被赋予的修改版本的权限传递给他人时，才可能拥有修改作品的权限。

These original program-specific proto-GPLs give an interesting window into the central ideas and devel- opment of copyleft. In particular, reviewing them shows how the text of the GPL we know has evolved to address more of the issues discussed earlier in § [1.2.3.](#software-and-non-copyright-legal-regimes)

这些起初特定于程序的原始GPL提供了一个了解著佐权的中心思想和发展的有趣窗口。此外，仔细研究它们可以看到我们熟悉的GPL文本是如何逐步演变以解决前面 [1.2.3.] 节中讨论过的更多问题的。

### The GNU General Public License, Version 1

### 2.3 GNU通用公共许可证，第一版

In January 1989, the FSF announced that the GPL had been converted into a "subroutine" that could be reused not just for all FSF-copyrighted programs, but also by anyone else. As the FSF claimed in its announcement of the GPLv1:[^2]

1989年1月，FSF宣布GPL已经被转换成为一个“子例程”，不仅可以被所有受FSF著作权保护的程序重复使用，还可以被任何其他人重复使用。正如FSF在GPLv1的公告中所宣称的那样：[^2]

To make it easier to copyleft programs, we have been improving on the legalbol architecture of the General Public License to produce a new version that serves as a general-purpose subroutine: it can apply to any program without modification, no matter who is publishing it.

为了使著佐权程序更方便使用，我们一直在改进通用公共许可证的法律体系结构，以便产生一个可以作为通用子例程的新版本：无论由谁发布，它都适用于任何程序而无需修改。

This, like many inventive ideas, seems somewhat obvious in retrospect. But, the FSF had some bright people and access to good lawyers when it started. It took almost five years from the first copyleft licenses to get to a generalized, reusable GPLv1. In the context and mindset of the 1980s, this is not surprising. The idea of reusable licensing infrastructure was not only uncommon, it was virtually nonexistent! Even the early BSD licenses were simply copied and rewritten slightly for each new use.[^3] The GPLv1's innovation of reusable licensing infrastructure, an obvious fact today, was indeed a novel invention for its day.[^4]

这一点，就像许多具有创造性的想法一样，回想起来似乎是显而易见的。但是，FSF在成立之初拥有一些人才，也能接触到优秀的律师。从第一个著佐权许可证到形成通用的、可重复使用的GPLv1，花了将近五年的时间。在20世纪80年代的背景和思维模式下，这并不奇怪。可重复使用基础许可的想法不仅不常见，而且几乎不存在！即使是早期的BSD许可证也只是通过简单地复制和改写来适应每个新用途。[^3]GPLv1对可重复使用基础许可的创新，在今天是显而易见的事实，在当时确实是一项新颖的发明。[^4]

### The GNU General Public License, Version 2

### 2.4 GNU通用公共许可证，第二版

The GPLv2 was released two and a half years after GPLv1, and over the following sixteen years, it became the standard for copyleft licensing until the release of GPLv3 in 2007 (discussed in more detail in the next section).

GPLv2比GPLv1晚两年半发布，在接下来的16年里，它成为了著佐权许可的标准，直到2007年GPLv3发布(下一节将详细讨论)。

While this tutorial does not discuss the terms of GPLv1 in detail, it is worth noting below the three key changes that GPLv2 brought:

虽然本指南不详细讨论GPLv1的条款，但GPLv2带来的三个关键变化值得一提：

- Software patents and their danger are explicitly mentioned, inspiring (in part) the addition of GPLv2 §§5--7. (These sections are discussed in detail in §[7.2,](#gplv2-5-acceptance-copyright-style) §[7.3](#gplv2-6-gpl-my-one-and-only) and §[7.5](#gplv2-7-give-software-liberty-or-give-it-death) of this tutorial.) 软件专利及其风险被明确提及，(在一定程度上)激发了GPLv2 §§5-7的加入。(这些部分将在本指南的§[7.2](#gplv2-5-acceptance-copyright-style)、§[7.3](#gplv2-6-gpl-my-one-and-only)和§[7.5](#gplv2-7-give-software-liberty-or-give-it-death)中详细讨论。)

- GPLv2 §2's copyleft terms are expanded to more explicitly discuss the issue of combined works. (GPLv2 *§*2 is discussed in detail in *§* [5.1](#gplv2-2-share-and-share-alike) in this tutorial).
- GPLv2 §2的著佐权术语得到了扩展，可以更明确地讨论组合作品的问题。(GPLv2 §2将在本指南的§[5.1](#gplv2-2-share-and-share-alike)中详细讨论)。

- GPLv2 §3 includes more detailed requirements, including the phrase "the scripts used to control compi- lation and installation of the executable", which is a central component of current GPLv2 enforcement. (GPLv2 §3 is discussed in detail in §[5.2](#gplv2-3-producing-binaries) in this tutorial).
- GPLv2 §3包含了更详细的需求，包括短语“用于控制可执行文件的编译和安装的脚本”，这是当前GPLv2实施的核心组件。(GPLv2 §3将在本指南的§[5.2](#gplv2-3-producing-binaries)中详细讨论)。

The next chapter discusses GPLv2 in full detail, and readers who wish to dive into the section-by-section discussion of the GPL should jump ahead now to that chapter. However, the most interesting fact to note here is how GPLv2 was published with little fanfare and limited commentary. This contrasts greatly with the creation of GPLv3.

下一章将详细讨论GPLv2，希望深入了解GPL逐节讨论的读者现在可以跳到那一章。然而，这里要指出的最有趣的事实是，GPLv2是如何在没有大肆宣传和有限报道的情况下发布的。这与GPLv3的诞生形成了鲜明对比。

[^2]: The announcement of GPLv1 was published in the [GNU's Bulletin, vol 1, number 6 dated January 1989.](http://www.gnu.org/bulletins/bull6.html#SEC8) (Thanks very much to Andy Tai for his [consolidation of research on the history of the pre-v1 GPL's.)](http://www.free-soft.org/gpl_history/)

[^2]: GPLv1的公告发表在1989年1月的[GNU公报第1卷第6期](http://www.gnu.org/bulletins/bull6.html#SEC8)。(非常感谢Andy Tai[对GPL v1之前的历史进行的整合研究](http://www.free-soft.org/gpl_history/)。)

[^3]: It remains an interesting accident of history that the early BSD problematic "advertising clause" (discussion of which is somewhat beyond the scope of this tutorial) lives on into current day, simply because while the University of California at Berkeley gave unilateral permission to remove the clause from *its* copyrighted works, others who adapted the BSD license with their own names in place of UC-Berkeley's never have.

[^3]: 早期BSD有问题的“广告条款”(关于它的讨论在某种程度上超出了本指南的范围)直到今天依然存在，这一直是历史上一个有趣的偶然事件，仅仅是因为当加州大学伯克利分校单方面允许从其受著作权保护的作品中删除该条款时，那些修改BSD许可证时用自己的名字代替加州大学伯克利分校的其他组织却从来没有这样做。

[^4]: We're all just grateful that the FSF also opposes business method patents, since the FSF's patent on a "method for reusable licensing infrastructure" would have not expired until 2006!

[^4]: 我们都很感激FSF也反对商业方法专利，因为FSF的专利作为一种“可重复使用的基础许可模式”到2006年才失效！

### The GNU General Public License, Version 3

### 2.5 GNU通用公共许可证，第三版

RMS began drafting GPLv2.2 in mid-2002, and FSF ran a few discussion groups during that era about new text of that license. However, rampant violations of the GPL required more immediate attention of FSF's licensing staff, and as such, much of the early 2000's was spent doing GPL enforcement work.[^5] In 2006, FSF began in earnest drafting work for GPLv3.

RMS在2002年年中开始起草GPLv2.2, FSF在那个时期组织了一些讨论小组，讨论该许可证的新文本。然而，猖獗的GPL侵权行为需要FSF的授权人员更加及时的关注，因此，2000年早期的大部分时间都花在了GPL的实施工作上。5 2006年，FSF正式开始GPLv3的起草工作。

The GPLv3 process began in earnest in January 2006. It became clear that many provisions of the GPL could benefit from modification to fit new circumstances and to reflect what the entire community learned from experience with version 2. Given the scale of revision it seems proper to approach the work through public discussion in a transparent and accessible manner.

GPLv3的进程于2006年1月正式开始。很明显，GPL的许多条款可以从修改中完善，以适应新的情况并反映出整个社区从第二版的经验中得到的教训。考虑到修订的规模，似乎以透明和可访问的方式通过公开讨论来处理工作是合适的。

The GPLv3 process continued through June 2007, culminating in publication of GPLv3 and LGPLv3 on 29 June 2007, AGPLv3 on 19 November 2007, and the GCC Runtime Library Exception on 27 January 2009.

GPLv3进程一直持续到2007年6月，最终于2007年6月29日发布了GPLv3和LGPLv3，并于2007年11月19日发布了AGPLv3，以及于2009年1月27日发布了GCC运行时库异常。

All told, four discussion drafts of GPLv3, two discussion drafts of LGPLv3 and two discussion drafts of AGPLv3 were published and discussed. Ultimately, FSF remained the final arbiter and publisher of the licenses, and RMS himself their primary author, but input was sought from many parties, and these licenses do admittedly look and read more like legislation as a result. Nevertheless, all of the "v3" group are substantially better and improved licenses.

总共发布并讨论了四份GPLv3讨论草案、两份LGPLv3讨论草案和两份AGPLv3讨论草案。最终，FSF仍然是许可证的最终仲裁者和出版方，RMS自己是许可证的主要作者，但是征求了许多人士的意见，因此这些许可证确实看起来和读起来更像立法。尽管如此，整个“v3”组都有了很大的改进，成为了更好的许可证。

GPLv3 and its terms are discussed in detail in Chapter [9.]

GPLv3及其术语将在第[9]章中详细讨论。

### The Innovation of Optional "Or Any Later" Version

### 2.6 可选“或任何后来”版本的创新

An interesting fact of all GPL licenses is that there are ultimately multiple choices for use of the license. The FSF is the primary steward of GPL (as discussed later in *§*[8.1](#gplv2-9-fsf-as-stewards-of-gpl) and *§*[9.17).](#gplv3-14-so-whens-gplv4) However, those who wish to license works under GPL are not required to automatically accept changes made by the FSF for their own copyrighted works.

所有GPL许可证的一个有趣的事实是：最终有多种使用许可证的选择。FSF是GPL的主要管理者（稍后将在*§*[8.1](#gplv2-9-fsf-as-stewards-of-gpl) 和*§*[9.17).](#gplv3-14-so-whens-gplv4)中讨论）。然而，那些希望在GPL下授权作品的人不需要自动接受FSF对他们自己受著作权保护的作品所做的更改。

Each licensor may chose three different methods of licensing, as follows:

每个许可人可以选择以下三种不同的许可方式：

- explicitly name a single version of GPL for their work (usually indicated in shorthand by saying the license is "GPLv*X*-only"), or

- 为他们的作品明确指定一个GPL版本（一般用“仅限GPLvX”这样的简写来表示），或者

- name no version of the GPL, thus they allow their downstream recipients to select any version of the GPL they choose (usually indicated in shorthand by saying the license is simply "GPL"), or

- 不指定GPL的任何版本，这样他们允许下游接收者任意选择GPL的任何版本（一般只简称许可证是“GPL”），或者

- name a specific version of GPL and give downstream recipients the option to choose that version "or any later version as published by the FSF" (usually indicated by saying the license is "GPLv*X*-or-later")[^6]

- 指定一个特定的GPL版本，并让下游接收者选择该版本“或由FSF发布的任何更高版本”（一般会说许可证是“GPLv*X*或更高版本”）。[^6^]

Oddly, this flexibility has received (in the opinion of the authors, undue) criticism, primarily because of the complex and oft-debated notion of "license compatibility" (which is explained in detail in [9.10).](#gplv3-7-understanding-license-compatibility) Copyleft licenses are generally incompatible with each other, because the details of how they implement copyleft differs. Specifically, copyleft works only because of its requirement that downstream licensors use the *same* license for combined and modified works. As such, software licensed under the terms of "GPLv2- only" cannot be combined with works licensed "GPLv3-or-later". This is admittedly a frustrating outcome.

奇怪的是，这种灵活性受到了（在作者看来是不适当的）批评，主要是因为“许可证兼容性”（x 9.10中有详细解释）的复杂性以及对其概念的争论不断。著佐权许可证通常彼此不兼容，因为履行著佐权的细节不同。具体来说，著佐权生效的唯一条件是它要求下游许可方对合并和修改的作品使用相同许可。因此，在“仅限GPLv2”条款下授权的软件不能与使用“GPLv3或更高版本”许可的作品结合。诚然，这是一个令人沮丧的结果。

Other copyleft licenses that appeared after GPL, such as the Creative Commons "Attribution-Share Alike" licenses, the Eclipse Public License and the Mozilla Public License **require** all copyright holders choosing to use any version of those licenses to automatically allow use of their copyrighted works under new versions.[^7^] Of course, Creative Commons, the Eclipse Foundation, and the Mozilla Foundation (like the FSF) have generally served as excellent stewards of their licenses. Copyright holders using those licenses seems to find it acceptable to fully delegate all future licensing decisions for their copyrights to these organizations without a second thought.

在GPL之后出现的其他著佐权许可证，如知识共享“署名-相同方式共享”许可证、Eclipse公共许可证和Mozilla公共许可证要求所有选择使用这些许可证的任何版本的著作权所有者自动允许在新版本下使用其受著作权保护的作品。7 当然，知识共享组织、Eclipse基金会和Mozilla基金会（像FSF一样）通常都是他们自己的许可证的优秀管理员。使用这些许可证的著作权所有者似乎发现可以毫不犹豫地将其著作权的所有未来许可决策完全委托给这些组织。

[^5]: More on GPL enforcement is discussed in Part [II] of this tutorial.

[^5]: 关于GPL实施的更多内容将在本指南的第[二]部分中讨论.

[^6]: The shorthand of "GPL*X*+" is also popular for this situation. The authors of this tutorial prefer "-or-later" syntax, because it (a) mirrors the words "or" and "later from the licensing statement, (b) the *X*+ doesn't make it abundantly clear that *X* is clearly included as a license option and (c) the + symbol has other uses in computing (such as with regular expressions) that []: mean something different.

[^6]: “GPLX+”的简写在这种情况下也很流行。本指南的作者更倾向于使用“或更高版本”语法，因为它：(a)反映了许可陈述中的单词“or（或）”和“later（更高版本）”；(b) X+不能非常清楚地表明许可选项中包含X；(c) +符号在计算中有其他用途（例如正则表达式），其含义不同。

[^7]: CC-BY-SA-2.0 and greater only permit licensing of adaptations under future versions; 1.0 did not have any accomodation for future version compatibility.

[^7]: CC-BY-SA-2.0及更高版本只允许未来版本的改编许可；1.0没有为将来的版本兼容性做任何安排。

However, note that FSF gives herein the control of copyright holders to decide whether or not to implicitly trust the FSF in its work of drafting future GPL versions. The FSF, for its part, does encourage copyright holders to chose by default "GPLv*X*-or-later" (where *X* is the most recent version of the GPL published by the FSF). However, the FSF **does not mandate** that a choice to use any GPL requires a copyright holder ceding its authority for future licensing decisions to the FSF. In fact, the FSF considered this possibility for GPLv3 and chose not to do so, instead opting for the third-party steward designation clause discussed in Section [9.17.](#gplv3-14-so-whens-gplv4)

但是请注意，FSF在此赋予了著作权所有者决策权，他们可以决定是否在起草未来GPL版本的工作中绝对信任FSF。就FSF而言，它确实鼓励著作权所有者默认选择“GPLv*X*或更高版本”（其中*X*是FSF发布的GPL的最新版本）。然而，FSF并**没有强制**要求选择使用任何GPL需要著作权所有者将其未来许可决策的权力交给FSF。事实上，FSF考虑了GPLv3的这种可能性却选择不这样做，而是选择了[9.17.](#gplv3-14-so-whens-gplv4)节中讨论的第三方管理指定条款。

### Complexities of Two Simultaneously Popular Copylefts

### 2.7 两个著佐权同时普遍使用的复杂性

Obviously most GPL advocates would prefer widespread migration to GPLv3, and many newly formed projects who seek a copyleft license tend to choose a GPLv3-based license. However, many existing copylefted projects continue with GPLv2-only or GPLv2-or-later as their default license.

显然，大多数GPL倡导者更倾向于广泛迁移至GPLv3，而且许多新成立的项目在挑选著佐权许可证时倾向于选择基于GPLv3的许可证。然而，许多现有受著佐权保护的项目仍继续使用“仅限GPLv2”或“GPLv2或更高版本”作为默认许可证。

While GPLv3 introduces many improvements --- many of which were designed to increase adoption by for-profit companies --- GPLv2 remains a widely used and extremely popular license. The GPLv2 is, no doubt, a good and useful license.

虽然GPLv3引入了许多改进——其中许多改进旨在促进营利性公司的采用——GPLv2仍是一个被广泛使用和非常受欢迎的许可证。毫无疑问，GPLv2是一个优秀且实用的许可证。

However, unlike GPLv1 before it, GPLv2 remains an integral part of the copyleft licensing infrastructure. As such, those who seek to have expertise in current topics of copyleft licensing need to study both the GPLv2 and GPLv3 family of licenses.

然而，与之前的GPLv1不同的是，GPLv2仍然是著佐权基础许可中不可分割的一部分。因此，那些希望在当前著佐权许可相关的话题方面拥有专业知识的人需要同时研究GPLv2和GPLv3系列许可证。

Furthermore, GPLv3 is more easily understood by first studying GPLv2. This is not only because of their chronological order, but also because much of the discussion material available for GPLv3 tends to talk about GPLv3 in contrast to GPLv2. As such, a strong understanding of GPLv2 helps in understanding most of the third-party material found regarding GPLv3. Thus, the following chapter begins a deep discussion of GPLv2.

此外，先研究GPLv2会更容易理解GPLv3。这不仅是因为它们的时间顺序，还因为许多关于GPLv3的可用讨论材料倾向于将GPLv3与GPLv2进行对比。因此，对GPLv2的深刻理解有助于理解大多数关于GPLv3的第三方材料。因此，下一章开始深入讨论GPLv2。



## CHAPTER 3 RUNNING SOFTWARE AND VERBATIM COPYING

## 第3章 运行软件与逐字复制

This chapter begins the deep discussion of the details of the terms of GPLv2. In this chapter, we consider the first two sections: GPLv2 §§0--2. These are the straightforward sections of the GPL that define
the simplest rights that the user receives.

本章开始深入讨论GPLv2条款的细节。在本章中，我们将考虑前两个部分：GPLv2 第0-2条。这些是GPL中简单明了的部分，定义了用户获得的最单纯的权利。

### 3.1 GPLv2 §0: Freedom to Run

### 3.1 GPLv2 §0：自由运行

GPLv2 §0, the opening section of GPLv2, sets forth that copyright law governs the work. It specifically points out that it is the "copyright holder" who decides if a work is licensed under its terms and explains how the copyright holder might indicate this fact.

GPLv2 §0——GPLv2的开篇部分阐述了作品受著作权法管辖。该部分特别指出由“著作权所有者”决定作品是否根据其条款进行许可，并解释了著作权所有者如何表明这一事实。

A bit more subtly, GPLv2 §0 makes an inference that copyright law is the only system that can restrict the software. Specifically, it states:

更微妙的一点是，GPLv2 §0推断著作权法是唯一可以限制软件的系统。具体来说，它指出:

Activities other than copying, distribution and modification are not covered by this License; they are outside its scope.

本许可证对除复制、分发和修改外的其他活动无效；它们超出了其适用范围。

In essence, the license governs *only* those activities, and all other activities are unrestricted, provided that no other agreements trump GPLv2 (which they cannot; see Sections [7.3](#gplv2-6-gpl-my-one-and-only) and [7.5).](#gplv2-7-give-software-liberty-or-give-it-death) This is very important, because the Free Software community heavily supports users' rights to "fair use" and "unregulated use" of copyrighted material. GPLv2 asserts through this clause that it supports users' rights to fair and unregulated uses.

本质上，许可证*只*管理这些活动，所有其他活动都是不受限制的，如果没有其他协议限制GPLv2（这是不可能的；参见第[7.3](#gplv2-6-gpl-my-one-and-only)和[7.5).](#gplv2-7-give-software-liberty-or-give-it-death)节）。这是非常重要的，因为自由软件社区大力支持用户享有对受著作权保护的材料的“合理使用”和“不受管制的使用”的权利。GPLv2通过这一条款声明它支持用户公平和不受管制的使用权利。

Fair use (called "fair dealing" in some jurisdictions) of copyrighted material is an established legal doctrine that permits certain activities regardless of whether copyright law would otherwise restrict those activities. Discussion of the various types of fair use activity are beyond the scope of this tutorial. However, one important example of fair use is the right to quote portions of the text in a larger work so as to criticize or suggest changes. This fair use right is commonly used on mailing lists when discussing potential improvements or changes to Free Software.

对受著作权保护的材料的合理使用（在某些司法管辖区称为“公平交易”）是一种既定的法律原则，允许进行某些活动而不管著作权法是否会限制这些活动。关于各种类型的合理使用活动的讨论超出了本指南的范围。然而，合理使用的一个重要典型是有权在较大的作品中引用文本的部分内容，以便进行批评或提出修改建议。当讨论自由软件的潜在改进或变化时，这种合理使用权在邮件列表中会被经常使用。

Fair use is a doctrine established by the courts or by statute. By contrast, unregulated uses are those that are not covered by the statue nor determined by a court to be covered, but are common and enjoyed by many users. An example of unregulated use is reading a printout of the program's source code like an instruction book for the purpose of learning how to be a better programmer. The right to read something that you have access to is and should remain unregulated and unrestricted.

合理使用是由法院或法令确立的原则。相比之下，不受管制的使用是指那些不受法令保护也不在法院管辖范围内、但很常见且深受广大用户喜爱的使用方式。它的一个例子是：为了学习如何成为一个更好的程序员，像阅读说明书一样阅读程序源代码的打印资料。阅读你能读到的东西的权利是且应该保持不受监管和限制的。

Thus, the GPLv2 protects users' fair and unregulated use rights precisely by not attempting to cover them. Furthermore, the GPLv2 ensures the freedom to run specifically by stating the following:

因此，GPLv2正是通过不试图包含它们来保护用户的公平和不受监管的使用权。此外，GPLv2通过声明以下内容确保了运行的自由：

"The act of running the Program is not restricted."

“运行程序的行为不受限制。”

Thus, users are explicitly given the freedom to run by GPLv2 §0.

因此，用户明确地获得了使用GPLv2 §0运行的自由。

The bulk of GPLv2 §0 not yet discussed gives definitions for other terms used throughout. The only one worth discussing in detail is "work based on the Program". The reason this definition is particularly interesting is not for the definition itself, which is rather straightforward, but because it clears up a common misconception about the GPL.

尚未讨论的大部分GPLv2 §0给出了贯穿始终的其他术语的定义。唯一值得详细讨论的是“基于程序的作品”。这个定义之所以特别有趣不是因为这个相当简明的定义本身，而是因为它澄清了关于GPL的一个常见误解。

The GPL is often mistakenly criticized because it fails to give a definition of "derivative work" or "com- bined work". In fact, it would be incorrect and problematic if the GPL attempted to define these terms. A copyright license, in fact, has no control over the rules of copyright themselves. Such rules are the domain of copyright law and the courts --- not the licenses that utilize those systems.

GPL经常被错误地批评，因为它没有给出“衍生作品”或“组合作品”的定义。事实上，如果GPL试图定义这些术语，才是不正确且有问题的。著作权许可证实际上并不能控制著作权规则本身。这样的规则属于著作权法和法院（而不是使用这些系统的许可证）的管辖范围。

Copyright law as a whole does not propose clear and straightforward guidelines for identifying the deriva- tive and/or combined works of software. However, no copyright license --- not even the GNU GPL --- can be blamed for this. Legislators and court opinions must give us guidance in borderline cases. Meanwhile, lawyers will likely based their conclusions on the application of rules made in the context of literary or artistic copyright to the different context of computer programming and by analyzing the (somewhat limited) case law and guidance available from various sources. (Chapter [14.1](#evaluate-license-applicability) discusses this issue in depth.)

著作权法整体并没有就识别软件的衍生作品和/或组合作品提出明确而直接的指导方针。然而，没有著作权许可证——甚至GNU GPL——才应该对此负责。立法者和法院必须在边界模糊的案件中为我们提供指导。与此同时，律师们可能会根据文学或艺术著作权背景下制定的规则在计算机编程的不同背景下的应用情况，以及通过分析（有限的）案例法和各种渠道获得的指导来得出结论。（第[14.1](#evaluate-license-applicability)节深入讨论了这个问题。）

### 3.2 GPLv2 §1: Verbatim Copying

### 3.2 GPLv2 §1：逐字复制

GPLv2 §1 covers the matter of redistributing the source code of a program exactly as it was received. This section is quite straightforward. However, there are a few details worth noting here.

GPLv2 第1条涵盖了重新完整分发程序源代码的问题。这部分相当简单明了。但有一些细节值得一提。

The phrase "in any medium" is important. This, for example, gives the freedom to publish a book that is the printed copy of the program's source code. It also allows for changes in the medium of distribution. Some vendors may ship Free Software on a CD, but others may place it right on the hard drive of a pre-installed computer. Any such redistribution media is allowed.

“在任何媒介中”这句话很重要。举个例子，它交出了将程序源代码的打印副本作为一本书出版的自由。它还允许更改分发媒介。一些厂商可能以CD的形式推出自由软件，但其他厂商可能将其直接置入预装计算机的硬盘驱动器中。任何这样的重新分发媒体都是允许的。

Preservation of copyright notice and license notifications are mentioned specifically in GPLv2 *§*1. These are in some ways the most important part of the redistribution, which is why they are mentioned by name. GPL always strives to make it abundantly clear to anyone who receives the software what its license is. The goal is to make sure users know their rights and freedoms under GPL, and to leave no reason that users might be surprised the software is GPL'd. Thus throughout the GPL, there are specific references to the importance of notifying others down the distribution chain that they have rights under GPL.

GPLv2 §1中特别提到著作权通知和许可证通知的保存。在某种程度上，这些是重新分发作品中最重要的部分，这就是提及它们的原因。GPL一直在努力让收到软件的人都清楚地知道它的许可证是什么。我们的目标是确保用户知道他们在GPL限制下的权利和自由，没有理由让用户对软件使用GPL感到惊讶。因此，整个GPL中都有专门提到通知分发链下游的其他人他们拥有GPL限制下的权利的重要性。

GPL disclaims all warranties that legally can be disclaimed (which is discussed later in sections [8.3](#gplv2-11-no-warranty) and [8.4).](#gplv2-12-limitation-of-liability) Users generally rarely expect their software comes with any warranties, since typically all EULAs and other Free Software licenses disclaim warranties too. However, since many local laws require "consipi- cous" warranty disclaimers, GPLv2 1 explicitly mentions the importance of keeping warranty disclaimers in tact upon redistribution.

GPL放弃所有法律上可以放弃的担保（这将在后面的[8.3](#gplv2-11-no-warranty)节和[8.4).](#gplv2-12-limitation-of-liability)节中讨论）。用户通常很少期望他们的软件附带任何担保，因为通常所有的EULA和其他自由软件许可证也都放弃担保。然而，由于许多地方法律要求“明显的”免责声明，GPLv2 *§*1明确提到在重新分发时完整保留免责声明的重要性。

Note finally that GPLv2 §1 creates groundwork for the important defense of commercial freedom. GPLv2 §1 clearly states that in the case of verbatim copies, one may make money. Re-distributors are fully permitted to charge for the re-distribution of copies of Free Software. In addition, they may provide the warranty protection that the GPL disclaims as an additional service for a fee. (See Section [12.2](#business-models) for more discussion on making a profit from Free Software redistribution.)

最后请注意，GPLv2 §1为捍卫商业自由奠定了基础。GPLv2 §1明确指出在逐字复制的情况下可以赚钱。重新分发者对自由软件副本的重新分发版进行收费是完全允许的。此外，他们还可以提供GPL拒绝的担保，将其作为附加服务进行收费。（有关从自由软件重新分发中获利的更多讨论，请参见第[12.2](#business-models)节。）

## CHAPTER 4 DERIVATIVE WORKS: STATUTE AND CASE LAW

## 第四章 衍生作品：法规和案例法

As described in the [earlier general discussion of copylef](#why-copyright-free-software)t, strong copyleft licenses such as the GPL seek to uphold software freedom via the copyright system. This principle often causes theoretical or speculative dispute among lawyers, because "the work" --- the primary unit of consideration under most copyright rules -- is not a unit of computer programming. In order to determine whether a "routine" an "object", a "function", a "library" or any other unit of software is part of one "work" when combined with other GPL'd code, we must ask a question that copyright law will not directly answer in the same technical terms.

如前面关于copyleft的一般讨论所述，像GPL这样的强制copyleft许可证通过版权系统来维护软件自由。这一原则经常引起律师之间的理论或推测性争议，因为在大多数版权规则下，“作品”——最主要的考虑单位——并不是计算机编程的一个单位。为了确定一个“程序”，一个“对象”，一个“函数”，一个“库”或任何其他软件单位，当与其他GPL代码组合时是否是一个“作品”，我们必须提出一个版权法直接无法用同样的技术术语回答的问题。

Therefore, this chapter digresses from discussion of GPL's exact text to consider the matter of combined and/or derivative works --- a concept that we must understand fully before considering GPLv2 2--3. At least under USA copyright law, The GPL, and Free Software licensing in general, relies critically on the concept of "derivative work" since software that is "independent," (i.e., not "derivative") of Free Software need not abide by the terms of the applicable Free Software license. As much is required by 106 of the Copyright Act, 17 U.S.C. 106 (2002), and admitted by Free Software licenses, such as the GPL, which (as we have seen) states in GPLv2 0 that "a 'work based on the Program' means either the Program or any derivative work under copyright law." It is being a derivative work of Free Software that triggers the necessity to comply with the terms of the Free Software license under which the original work is distributed. Therefore, one is left to ask, just what is a "derivative work"? The answer to that question differs depending on which court is being asked.

因此，在考虑GPL的确切文本之前，本章偏离讨论合并和/或衍生作品的问题——这是一个我们必须完全理解的概念，才能考虑GPLv2 2-3。至少在美国版权法下，GPL和自由软件许可证的普遍使用，关键在于“衍生作品”的概念，因为独立于自由软件的软件（即不是“衍生”软件）不必遵守适用的自由软件许可证条款。这在版权法第106条、17 U.S.C. 106（2002）中被要求，并被自由软件许可证，如GPL所承认，GPLv2 0规定：“基于该程序的作品”指的是该程序或根据版权法的任何衍生作品。”只有成为自由软件的衍生作品才会触发需要遵守原始作品所分发的自由软件许可证条款的必要性。因此，人们不得不问，什么是“衍生作品”？这个问题的答案取决于被问的是哪个法院。

The analysis in this chapter sets forth the differing definitions of derivative work by the circuit courts. The broadest and most established definition of derivative work for software is the abstraction, filtration, and comparison test ("the AFC test") as created and developed by the Second Circuit. Some circuits, including the Ninth Circuit and the First Circuit, have either adopted narrower versions of the AFC test or have expressly rejected the AFC test in favor of a narrower standard. Further, several other circuits have yet to adopt any definition of derivative work for software.

本章分析了各个巡回法院对派生作品的不同定义。对于软件而言，最广泛和最成熟的派生作品定义是由第二巡回法院创造和发展的抽象、过滤和比较测试（“AFC测试”）。包括第九巡回法院和第一巡回法院在内的一些巡回法院已经采用了AFC测试的较窄版本，或明确拒绝了AFC测试，而采用了较窄的标准。此外，其他几个巡回法院还没有采用任何关于软件派生作品的定义。

As an introductory matter, it is important to note that literal copying of a significant portion of source code is not always sufficient to establish that a second work is a derivative work of an original program. Conversely, a second work can be a derivative work of an original program even though absolutely no copying of the literal source code of the original program has been made. This is the case because copyright protection does not always extend to all portions of a program's code, while, at the same time, it can extend beyond the literal code of a program to its non-literal aspects, such as its architecture, structure, sequence, organization, operational modules, and computer-user interface.

作为一个引言，需要注意的是，直接复制源代码的大部分并不总是足以证明第二个作品是原始程序的派生作品。相反，即使完全没有复制原始程序的字面源代码，第二个作品也可以是原始程序的派生作品。这是因为版权保护并不总是延伸到程序代码的所有部分，同时，它也可以超越程序的字面代码，涵盖程序的非字面方面，例如其结构、序列、组织、操作模块和计算机用户界面。

### The Copyright Act

### 4.1 版权法

The copyright act is of little, if any, help in determining the definition of a derivative work of software. However, the applicable provisions do provide some, albeit quite cursory, guidance. Section 101 of the Copyright Act sets forth the following definitions:

版权法在确定软件衍生作品的定义方面没有多少帮助，然而，适用的规定确实提供了一些相当肤浅的指导。版权法第101条规定了以下定义：

A "computer program" is a set of statements or instructions to be used directly or indirectly in a computer in order to bring about a certain result.

“计算机程序”是一组语句或指令，直接或间接用于计算机，以实现某种结果。

A "derivative work" is a work based upon one or more preexisting works, such as a translation, musical arrangement, dramatization, fictionalization, motion picture version, sound recording, art reproduction, abridgment, condensation, or any other form in which a work may be recast, transformed, or adapted. A work consisting of editorial revisions, annotations, elaborations, or other modifications which, as a whole, represent an original work of authorship, is a "derivative work."

“衍生作品”是基于一个或多个现有作品的作品，例如翻译、音乐编排、戏剧化、虚构化、电影版本、录音、艺术复制、缩写、概括或任何其他形式，在其中一个作品可以被重构、转化或改编。由编辑修订、注释、阐述或其他修改组成的作品，如果整体上代表了一部独创性作品，则为“衍生作品”。

These are the only provisions in the Copyright Act relevant to the determination of what constitutes a derivative work of a computer program. Another provision of the Copyright Act that is also relevant to the definition of derivative work is *§* 102(b), which reads as follows:

“衍生作品”是基于一个或多个现有作品的作品，例如翻译、音乐编排、戏剧化、虚构化、电影版本、录音、艺术复制、缩写、概括或任何其他形式，在其中一个作品可以被重构、转化或改编。由编辑修订、注释、阐述或其他修改组成的作品，如果整体上代表了一部独创性作品，则为“衍生作品”。

In no case does copyright protection for an original work of authorship extend to any idea, procedure, process, system, method of operation, concept, principle, or discovery, regardless of the form in which it is described, explained, illustrated, or embodied in such work.

在任何情况下，对于作者原创的作品，版权保护都不会扩展到其中包含的任何思想、程序、流程、系统、操作方法、概念、原理或发现，无论其以何种形式被描述、解释、说明或体现在该作品中。

Therefore, before a court can ask whether one program is a derivative work of another program, it must be careful not to extend copyright protection to any ideas, procedures, processes, systems, methods of operation, concepts, principles, or discoveries contained in the original program. It is the implementation of this requirement to "strip out" unprotectable elements that serves as the most frequent issue over which courts disagree.

因此，在法院可以询问一个程序是否是另一个程序的衍生作品之前，必须小心不要将原始程序中包含的任何思想、程序、流程、系统、操作方法、概念、原理或发现扩展到版权保护范围之内。解决“剥离”不受保护元素的问题，是法院之间最常见的争议问题。

### 4.2 Abstraction, Filtration, Comparison Test

### 4.2 抽象、筛选、比较测试

As mentioned above, the AFC test for determining whether a computer program is a derivative work of an earlier program was created by the Second Circuit and has since been adopted in the Fifth, Tenth, and Eleventh Circuits. Computer Associates Intl., Inc. v. Altai, Inc., 982 F.2d 693 (2nd Cir. 1992); Engineering Dynamics, Inc. v. Structural Software, Inc., 26 F.3d 1335 (5th Cir. 1994); Kepner-Tregoe, Inc. v. Leadership Software, Inc., 12 F.3d 527 (5th Cir. 1994); Gates Rubber Co. v. Bando Chem. Indust., Ltd., 9 F.3d 823 (10th Cir. 1993); Mitel, Inc. v. Iqtel, Inc., 124 F.3d 1366 (10th Cir. 1997); Bateman v. Mnemonics, Inc., 79 F.3d 1532 (11th Cir. 1996); and, Mitek Holdings, Inc. v. Arce Engineering Co., Inc., 89 F.3d 1548 (11th Cir. 1996).

如上所述，用于确定计算机程序是否是早期程序的派生作品的AFC测试是由第二巡回法院创建的，自那时以来已被第五、第十和第十一巡回法院采纳。具体案例包括：Computer Associates Intl.，Inc. v. Altai，Inc.，982 F.2d 693（第二巡回法院1992年）；Engineering Dynamics，Inc. v. Structural Software，Inc.，26 F.3d 1335（第五巡回法院1994年）；Kepner-Tregoe，Inc. v. Leadership Software，Inc.，12 F.3d 527（第五巡回法院1994年）；Gates Rubber Co. v. Bando Chem. Indust.，Ltd.，9 F.3d 823（第十巡回法院1993年）；Mitel，Inc. v. Iqtel，Inc.，124 F.3d 1366（第十巡回法院1997年）；Bateman v. Mnemonics，Inc.，79 F.3d 1532（第十一巡回法院1996年）；以及Mitek Holdings，Inc. v. Arce Engineering Co.，Inc.，89 F.3d 1548（第十一巡回法院1996年）。

Under the AFC test, a court first abstracts from the original program its constituent structural parts. Then, the court filters from those structural parts all unprotectable portions, including incorporated ideas, expression that is necessarily incidental to those ideas, and elements that are taken from the public domain. Finally, the court compares any and all remaining kernels of creative expression to the structure of the second program to determine whether the software programs at issue are substantially similar so as to warrant a finding that one is the derivative work of the other.

在AFC测试中，法院首先从原始程序中抽象出其组成结构部分。然后，法院从这些结构部分中筛选出所有不可保护的部分，包括融入的想法、与这些想法必然有关的表达和从公共领域中获取的元素。最后，法院比较任何和所有剩余的创造性表达核心与第二个程序的结构，以确定所涉及的软件程序是否存在实质相似，从而认定其中一个是另一个的派生作品。

Often, the courts that apply the AFC test will perform a quick initial comparison between the entirety of the two programs at issue in order to help determine whether one is a derivative work of the other. Such a holistic comparison, although not a substitute for the full application of the AFC test, sometimes reveals a pattern of copying that is not otherwise obvious from the application of the AFC test when, as discussed below, only certain components of the original program are compared to the second program. If such a pattern is revealed by the quick initial comparison, the court is more likely to conclude that the second work is indeed a derivative of the original.

通常，应用AFC测试的法院将对所涉及的两个程序的整体进行快速的初步比较，以帮助确定其中一个是否是另一个的派生作品。虽然这种整体比较并不能代替对AFC测试的全面应用，但有时它可以显示出从原始程序的某些组件与第二个程序进行比较时并不明显的复制模式。如果快速的初步比较揭示了这样的模式，法院更有可能得出结论，即第二个作品确实是原作的派生作品。

#### 4.2.1 Abstraction

#### 4.2.１ 抽象化

The first step courts perform under the AFC test is separation of the work's ideas from its expression. In a process akin to reverse engineering, the courts dissect the original program to isolate each level of abstraction contained within it. Courts have stated that the abstractions step is particularly well suited for computer programs because it breaks down software in a way that mirrors the way it is typically created. However, the courts have also indicated that this step of the AFC test requires substantial guidance from experts, because it is extremely fact and situation specific.

根据 AFC 测试，法院执行的第一步是将作品的想法与表达方式分开。类似于反向工程的过程，法院解剖原始程序以隔离其中包含的每个抽象级别。法院表示，由于它以与软件通常创建方式相似的方式将软件分解，因此抽象化步骤特别适用于计算机程序。然而，法院还指出，AFC 测试的这一步骤需要专家的大量指导，因为它具有极其事实和情况的特定性。

By way of example, one set of abstraction levels is, in descending order of generality, as follows: the main purpose, system architecture, abstract data types, algorithms and data structures, source code, and object code. As this set of abstraction levels shows, during the abstraction step of the AFC test, the literal elements of the computer program, namely the source and object code, are defined as particular levels of abstraction. Further, the source and object code elements of a program are not the only elements capable of forming the basis for a finding that a second work is a derivative of the program. In some cases, in order to avoid a lengthy factual inquiry by the court, the owner of the copyright in the original work will submit its own list of what it believes to be the protected elements of the original program. In those situations, the court will forgo performing its own abstraction, and proceed to the second step of the AFC test.

例如，一个抽象级别集合按照从一般到具体的顺序如下：主要目的、系统架构、抽象数据类型、算法和数据结构、源代码和目标代码。正如这组抽象级别所示，在 AFC 测试的抽象化步骤中，计算机程序的字面元素，即源代码和目标代码，被定义为特定的抽象级别。此外，程序的源代码和目标代码元素并不是形成发现第二个作品是原始程序的衍生作品的唯一元素。在某些情况下，为了避免法院进行冗长的事实调查，原始作品的版权所有人将提交其自己的保护元素列表。在这种情况下，法院将放弃执行自己的抽象化，直接进行 AFC 测试的第二步骤。

#### 4.2.2 Filtration

#### 4.2.2 过滤

The most difficult and controversial part of the AFC test is the second step, which entails the filtration of protectable expression contained in the original program from any unprotectable elements nestled therein. In determining which elements of a program are unprotectable, courts employ a myriad of rules and procedures to sift from a program all the portions that are not eligible for copyright protection.

AFC测试中最具争议和难度的部分是第二步，涉及从原始程序中筛选出包含保护性表达的部分，并从中滤除任何非保护性的元素。在确定程序中哪些元素是不受保护的时，法院采用各种规则和程序来筛选出所有不符合版权保护资格的部分。

First, as set forth in 102(b) of the Copyright Act, any and all ideas embodied in the program are to be denied copyright protection. However, implementing this rule is not as easy as it first appears. The courts readily recognize the intrinsic difficulty in distinguishing between ideas and expression and that, given the varying nature of computer programs, doing so will be done on an ad hoc basis. The first step of the AFC test, the abstraction, exists precisely to assist in this endeavor by helping the court separate out all the individual elements of the program so that they can be independently analyzed for their expressive nature. A second rule applied by the courts in performing the filtration step of the AFC test is the doctrine of merger, which denies copyright protection to expression necessarily incidental to the idea being expressed. The reasoning behind this doctrine is that when there is only one way to express an idea, the idea and the expression merge, meaning that the expression cannot receive copyright protection due to the bar on copyright protection extending to ideas. In applying this doctrine, a court will ask whether the program's use of particular code or structure is necessary for the efficient implementation of a certain function or process. If so, then that particular code or structure is not protected by copyright and, as a result, it is filtered away from the remaining protectable expression.

首先，根据版权法第102（b）条款，程序中包含的所有想法都将被否认版权保护。然而，执行此规则并不像它最初看起来那么容易。法院充分认识到区分思想和表达之间的内在困难，鉴于计算机程序的多样性，这样做将是一个临时性的基础。 AFC测试的第一步——抽象，恰恰是为了帮助法院将程序的所有单独元素分离出来，以便可以独立地分析它们的表现性质。法院在执行AFC测试的过程中应用的第二个规则是合并原则，该原则否认与表达所表达的思想必然相关的表达的版权保护。这个原则的理由是，当只有一种表达思想的方式时，思想和表达合并，意味着由于版权保护不扩展到思想，表达不能获得版权保护。在应用这个原则时，法院将询问程序是否使用特定的代码或结构对某个功能或流程的高效实现是必需的。如果是，那么该特定代码或结构不受版权保护，因此从其余可保护表达式中过滤掉。

A third rule applied by the courts in performing the filtration step of the AFC test is the doctrine of scenes a faire, which denies copyright protection to elements of a computer program that are dictated by external factors. Such external factors can include:

法院在执行AFC测试的筛选步骤中应用的第三个规则是通用场景原则，该原则否认由外部因素决定的计算机程序的元素的版权保护。这些外部因素可以包括：

- The mechanical specifications of the computer on which a particular program is intended to operate

- Compatibility requirements of other programs with which a program is designed to operate in conjunc- tion

- Computer manufacturers' design standards

- Demands of the industry being serviced, and widely accepted programming practices within the computer industry

- 特定程序的计算机的机械规格
- 与设计为一起运行的其他程序的兼容性要求
- 计算机制造商的设计标准
- 所服务的行业的需求以及计算机行业内广泛接受的编程实践

Any code or structure of a program that was shaped predominantly in response to these factors is filtered out and not protected by copyright. Lastly, elements of a computer program are also to be filtered out if they were taken from the public domain or fail to have sufficient originality to merit copyright protection.

如果程序的任何代码或结构主要是针对这些因素而形成的，则会被过滤掉，并且不受版权保护。最后，如果计算机程序的元素来自公共领域或缺乏足够的原创性，也应该被过滤掉。

Portions of the source or object code of a computer program are rarely filtered out as unprotectable elements. However, some distinct parts of source and object code have been found unprotectable. For example, constants, the invariable integers comprising part of formulas used to perform calculations in a program, are unprotectable. Further, although common errors found in two programs can provide strong evidence of copying, they are not afforded any copyright protection over and above the protection given to the expression containing them.

计算机程序的源代码或目标代码的部分很少被过滤为不可保护元素。然而，有些源代码和目标代码的独特部分被发现是不可保护的。例如，常量，即组成程序中用于执行计算的公式的不变整数，是不可保护的。此外，虽然在两个程序中发现的常见错误可以提供复制的强有力证据，但它们不享有任何超出包含它们的表达所享有的版权保护。

#### 4.2.3 Comparison

#### 4.2.3 比较

The third and final step of the AFC test entails a comparison of the original program's remaining protectable expression to a second program. The issue will be whether any of the protected expression is copied in the second program and, if so, what relative importance the copied portion has with respect to the original program overall. The ultimate inquiry is whether there is "substantial" similarity between the protected elements of the original program and the potentially derivative work. The courts admit that this process is primarily qualitative rather than quantitative and is performed on a case-by-case basis. In essence, the comparison is an ad hoc determination of whether the protectable elements of the original program that are contained in the second work are significant or important parts of the original program. If so, then the second work is a derivative work of the first. If, however, the amount of protectable elements copied in the second work are so small as to be de minimis, then the second work is not a derivative work of the original.

AFC测试的第三个也是最后一个步骤是将原始程序剩余的可保护表达式与第二个程序进行比较。问题在于第二个程序中是否复制了任何受保护的表达式，如果有，复制部分在整个原始程序中的相对重要性是什么。最终的问题是原始程序的受保护元素与潜在的衍生作品之间是否存在“实质性”相似性。法院承认这个过程主要是定性而非定量的，是根据具体情况进行的。实质上，比较是一种临时决定，用于确定第二个作品中包含的原始程序可保护元素是否是原始程序的重要组成部分。如果是，那么第二个作品就是第一个作品的衍生作品。然而，如果第二个作品中复制的可保护元素数量非常少，以至于可以视为微不足道，则第二个作品不是原始作品的衍生作品。

### 4.3 Analytic Dissection Test

### 4.3 分析解剖测试

The Ninth Circuit has adopted the analytic dissection test to determine whether one program is a derivative work of another. Apple Computer, Inc. v. Microsoft Corp., 35 F.3d 1435 (9th Cir. 1994). The analytic dissection test first considers whether there are substantial similarities in both the ideas and expressions of the two works at issue. Once the similar features are identified, analytic dissection is used to determine whether any of those similar features are protected by copyright. This step is the same as the filtration step in the AFC test. After identifying the copyrightable similar features of the works, the court then decides whether those features are entitled to "broad" or "thin" protection. "Thin" protection is given to non-copyrightable facts or ideas that are combined in a way that affords copyright protection only from their alignment and presentation, while "broad" protection is given to copyrightable expression itself. Depending on the degree of protection afforded, the court then sets the appropriate standard for a subjective comparison of the works to determine whether, as a whole, they are sufficiently similar to support a finding that one is a derivative work of the other. "Thin" protection requires the second work be virtually identical in order to be held a derivative work of an original, while "broad" protection requires only a "substantial similarity."

第九巡回上诉法院采用了分析解剖测试来确定一个程序是否是另一个程序的衍生作品。《苹果电脑公司诉微软公司》（Apple Computer, Inc. v. Microsoft Corp.）, 35 F.3d 1435 (9th Cir. 1994)。分析解剖测试首先考虑两个作品的观点和表达是否存在实质性的相似之处。一旦发现相似之处，就使用分析解剖来确定是否有任何受版权保护的相似之处。这一步与AFC测试中的过滤步骤相同。在确定了两个作品中受版权保护的相似之处后，法院将决定这些特征是否有“广泛”的或“薄弱”的保护。对于非版权保护的事实或观点，如果它们只是通过组合而获得版权保护，则只有其结构和表达方式才受到“薄弱”保护，而版权保护的表达方式本身则获得“广泛”保护。根据所享有的保护程度，法院随后确定了适当的标准来进行主观比较，以确定两个作品是否整体上足够相似，从而支持其中一个作品是另一个作品的衍生作品的结论。如果采用“薄弱”保护，第二个作品必须几乎完全相同才能被认为是原始作品的衍生作品；而如果采用“广泛”保护，则只需要存在“实质性相似性”。

### 4.4 No Protection for "Methods of Operation"

### 4.4 “操作方法”不受保护

The First Circuit has taken the position that the AFC test is inapplicable when the works in question relate to unprotectable elements set forth in 102(b). Their approach results in a much narrower definition of derivative work for software in comparison to other circuits. Specifically, the First Circuit holds that "method of operation," as used in 102(b) of the Copyright Act, refers to the means by which users operate computers. Lotus Development Corp. v. Borland Int'l., Inc., 49 F.3d 807 (1st Cir. 1995). In Lotus, the court held that a menu command hierarchy for a computer program was uncopyrightable because it did not merely explain and present the program's functional capabilities to the user, but also served as a method by which the program was operated and controlled. As a result, under the First Circuit's test, literal copying of a menu command hierarchy, or any other "method of operation," cannot form the basis for a determination that one work is a derivative of another. As a result, courts in the First Circuit that apply the AFC test do so only after applying a broad interpretation of 102(b) to filter out unprotected elements. E.g., Real View, LLC v. 20-20 Technologies, Inc., 683 F. Supp.2d 147, 154 (D. Mass. 2010).

第一巡回法院认为，当涉及到《版权法案》第102(b)条列出的不受保护元素时，AFC测试不适用于所讨论的作品。他们的方法相对于其他巡回法院的软件派生作品定义更为狭窄。具体来说，第一巡回法院认为，《版权法案》第102(b)条所使用的“操作方法”是指用户操作计算机的方式。在Lotus Development Corp. v. Borland Int'l., Inc.案中，法院认为，计算机程序的菜单命令层次结构是无法受版权保护的，因为它不仅仅是向用户解释和展示程序的功能能力，还作为控制程序操作的方法。因此，在第一巡回法院的测试中，菜单命令层次结构或其他“操作方法”的文字复制不能成为确定一部作品是否为另一部作品的派生作品的依据。因此，适用AFC测试的第一巡回法院在筛选出未受保护元素的广泛解释之后，才会适用该测试。例如，Real View, LLC v. 20-20 Technologies, Inc., 683 F. Supp.2d 147, 154 (D. Mass. 2010)案。

### 4.5 No Test Yet Adopted

### 4.5 尚未采用测试

Several circuits, most notably the Fourth and Seventh, have yet to declare their definition of derivative work and whether or not the AFC, Analytic Dissection, or some other test best fits their interpretation of copyright law. Therefore, uncertainty exists with respect to determining the extent to which a software program is a derivative work of another in those circuits. However, one may presume that they would give deference to the AFC test since it is by far the majority rule among those circuits that have a standard for defining a software derivative work.

几个巡回法院，尤其是第四和第七巡回法院，尚未宣布他们对派生作品的定义以及AFC测试、分析性解剖或其他测试是否最适合他们对版权法的解释。因此，在这些巡回法院中，仍然存在不确定性，无法确定软件程序在多大程度上是另一部作品的派生作品。然而，可以假定他们会尊重AFC测试，因为在那些已经有定义软件派生作品标准的巡回法院中，AFC测试明显占多数。

### 4.6 Cases Applying Software Derivative Work Analysis

### 4.6 应用于软件衍生作品分析的案例

In the preeminent case regarding the definition of a derivative work for software, Computer Associates v. Altai, the plaintiff alleged that its program, Adapter, which was used to handle the differences in operating system calls and services, was infringed by the defendant's competitive program, Oscar. About 30% of Oscar was literally the same code as that in Adapter. After the suit began, the defendant rewrote those portions of Oscar that contained Adapter code in order to produce a new version of Oscar that was functionally competitive with Adapter, without having any literal copies of its code. Feeling slighted still, the plaintiff alleged that even the second version of Oscar, despite having no literally copied code, also infringed its copyrights. In addressing that question, the Second Circuit promulgated the AFC test.

在关于软件衍生作品定义的权威案例Computer Associates v. Altai中，原告声称其用于处理操作系统调用和服务差异的程序Adapter被被告的竞争性程序Oscar侵犯了。 Oscar约30％的代码与Adapter的代码完全相同。诉讼开始后，被告重写了那些包含Adapter代码的Oscar部分，以产生一个新版本的Oscar，它在没有任何字面上的代码副本的情况下在功能上与Adapter竞争。尽管如此，原告声称，即使是Oscar的第二个版本，尽管没有任何文字上复制的代码，也侵犯了它的版权。在回答这个问题时，第二巡回法院颁布了AFC测试。

In abstracting the various levels of the program, the court noted a similarity between the two programs' parameter lists and macros. However, following the filtration step of the AFC test, only a handful of the lists and macros were protectable under copyright law because they were either in the public domain or required by functional demands on the program. With respect to the handful of parameter lists and macros that did qualify for copyright protection, after performing the comparison step of the AFC test, it was reasonable for the district court to conclude that they did not warrant a finding of infringement given their relatively minor contribution to the program as a whole. Likewise, the similarity between the organizational charts of the two programs was not substantial enough to support a finding of infringement because they were too simple and obvious to contain any original expression.

在抽象化程序的各个层面时，法院注意到两个程序的参数列表和宏之间的相似之处。然而，在AFC测试的过滤步骤之后，只有少数列表和宏受版权法保护，因为它们要么是公有领域的，要么是对程序的功能需求所必需的。对于少数符合版权保护的参数列表和宏，在执行AFC测试的比较步骤之后，地区法院认为它们并不值得被认定为侵犯，因为它们对整个程序的贡献相对较小。同样，两个程序组织图之间的相似之处也不足以支持侵权的发现，因为它们太简单和显而易见，不包含任何原创表达。

In the case of Oracle America v. Google, 872 F. Supp.2d 974 (N.D. Cal. 2012), the Northern District of California District Court examined the question of whether the application program interfaces (APIs) asso- ciated with the Java programming language are entitled to copyright protection. While the court expressly declined to rule whether all APIs are free to use without license (872 F. Supp.2d 974 at 1002), the court held that the command structure and taxonomy of the APIs were not protectable under copyright law. Specifi- cally, the court characterized the command structure and taxonomy as both a "method of operation" (using an approach not dissimilar to the First Circuit's analysis in Lotus) and a "functional requirement for com- patibility" (using Sega v. Accolade, 977 F.2d 1510 (9th Cir. 1992) and Sony Computer Ent. v. Connectix, 203 F.3d 596 (9th Cir. 2000) as analogies), and thus unprotectable subject matter under 102(b).

在Oracle America v. Google案中，北加利福尼亚地区法院审查了与Java编程语言相关的应用程序接口（API）是否享有版权保护的问题。虽然法院明确拒绝裁定所有API是否可在未获许可的情况下免费使用，但法院认为API的命令结构和分类法不受版权法保护。具体而言，法院将命令结构和分类法表述为“操作方法”（采用类似于Lotus中第一巡回法院分析的方法）和“兼容性的功能要求”（使用Sega v. Accolade，977 F.2d 1510（9th Cir. 1992）和Sony Computer Ent. v. Connectix，203 F.3d 596（9th Cir. 2000）作为类比），因此是根据102(b)不受保护的主题。

Perhaps not surprisingly, there have been few other cases involving a highly detailed software derivative work analysis. Most often, cases involve clearer basis for decision, including frequent bad faith on the part of the defendant or over-aggressiveness on the part of the plaintiff.

也许不令人意外的是，很少有其他案例涉及高度详细的软件衍生作品分析。大多数情况下，案例涉及更明显的决策基础，包括被告的频繁恶意行为或原告的过度侵权行为。

### 4.7 How Much Do Derivative Works Matter?

### 4.7 派生作品有多重要？

It is certainly true that GPL intends for any work that is determined a "derivative work" under copyright law must be licensed as a whole under GPL, as will be discussed in the following chapter. However, as we finish up our discussion derivative works, we must note that preparation of a derivative work is by far not the only way to create a new work covered by GPL.

毫无疑问，GPL旨在确保任何在版权法下被认定为“衍生作品”的作品必须作为整体在GPL下进行许可，这将在下一章中讨论。然而，当我们结束对衍生作品的讨论时，必须指出制作衍生作品远不是创建GPL覆盖的新作品的唯一方式。

In fact, while derivative work preparation is perhaps the most exciting area of legal issues to consider, the more mundane ways to create a new work covered by GPL are much more common. For example, copyright statutes generally require permission from the copyright holder to grant explicit permission to modify a work in any manner. As discussed in the next chapter, the GPL *does* grant such permission, but requires the modified work must also be licensed under the terms of the GPL (and only GPL: see*§* [7.3](#gplv2-6-gpl-my-one-and-only) in this tutorial). Determining whether software was modified is a substantially easier analysis than the derivative work discussions and considerations in this chapter.

事实上，尽管制作衍生作品可能是考虑法律问题最令人兴奋的领域，但通过更为平凡的方式创建GPL覆盖的新作品则更为常见。例如，版权法通常要求获得版权持有人的许可，以明确许可对作品进行任何方式的修改。如下一章所讨论的，GPL确实授予了这种许可，但要求修改后的作品也必须根据GPL的条款进行许可（而且只能是GPL：参见本教程中的§7.3）。确定软件是否被修改是一项相对容易的分析，与本章关于衍生作品的讨论和考虑相比要简单得多。

The question of derivative works, when and how they are made, is undoubtedly an essential discussion in the interpretation and consideration of copyleft. That is why this chapter was included in this tutorial. However, as we return from this digression and resume discussion of the detailed text of the GPLv2, we must gain a sense of perspective: most GPL questions center around questions of modification and distribution, not preparation of derivative works. Derivative work preparation is ultimately a small subset of the types of modified versions of the software a developer might create, thus, while an excessive focus on derivative works indulges us in the more exciting areas of copyleft, we must keep a sense of perspective regarding their relative importance.

衍生作品的问题、它们何时以及如何制作，无疑是在解释和考虑版权公用原则方面的必要讨论。这就是为什么本教程包含了这一章的原因。然而，当我们从这一跑题中回到对GPLv2详细文本的讨论并继续讨论时，我们必须有一个全局的认识：大多数GPL问题都集中在修改和分发问题上，而不是制作衍生作品。制作衍生作品最终只是开发人员可能创建的软件修改版本类型的一小部分，因此，虽然过分关注衍生作品能使我们沉浸在版权公用原则更激动人心的领域中，但我们必须保持相对重要性的观念。


## CHAPTER 5 MODIFIED SOURCE AND BINARY DISTRIBUTION

## 第5章 修改源代码和二进制分发

In this chapter, we discuss the two core sections that define the rights and obligations for those who modify, improve, and/or redistribute GPL'd software. These sections, GPLv2 2--3, define the central core rights and requirements of GPLv2.

本章中，我们讨论了修改、改进和/或重新分发GPL软件的权利和义务的两个核心部分。这些部分，即GPLv2 2-3，定义了GPLv2的核心权利和要求。

### 5.1 GPLv2 §2: Share and Share Alike

### 5.1 GPLv2 第2条：分享和分享相同

For many, this is where the "magic" happens that defends software freedom upon redistribution. GPLv2 2 is the only place in GPLv2 that governs the modification controls of copyright law. If users distribute modified versions a GPLv2'd program, they must follow the terms of GPLv2 2 in making those changes. Thus, this sections ensures that the body of GPL'd software, as it continues and develops, remains Free as in freedom. To achieve that goal, GPLv2 2 first sets forth that the rights of redistribution of modified versions are the same as those for verbatim copying, as presented in GPLv2 1. Therefore, the details of charging money, keeping copyright notices intact, and other GPLv2 1 provisions are intact here as well. However, there are three additional requirements.

对于许多人来说，这就是“魔法”发生的地方，它在重新分发时保护了软件自由。GPLv2 2是在GPLv2中仅控制版权法修改控制的地方。如果用户分发了GPLv2'd程序的修改版本，他们必须遵循GPLv2 2的条款进行更改。因此，这些部分确保了GPL'd软件库随着其不断发展和发展，仍然保持自由。为了实现这个目标，GPLv2 2首先规定修改版本的重新分发权与逐字复制的重新分发权相同，就像GPLv2 1中所述的那样。因此，收费细节、版权声明完整性和其他GPLv2 1规定也在这里得到保留。但是，还有三个额外的要求。

#### 5.1.1 The Simpler Parts of GPLv2 §2

### 5.1.1 GPLv2第2条简单部分

The first (GPLv2 2(a)) requires that modified files carry "prominent notices" explaining what changes were made and the date of such changes. This section does not prescribe some specific way of marking changes nor does it control the process of how changes are made. Primarily, GPLv2 2(a) seeks to ensure that those receiving modified versions know the history of changes to the software. For some users, it is important to know that they are using the standard version of program, because while there are many advantages to using a fork, there are a few disadvantages. Users should be informed about the historical context of the software version they use, so that they can make proper support choices. Finally, GPLv2 2(a) serves an academic purpose --- ensuring that future developers can use a diachronic approach to understand the software.

第一个（GPLv2 2（a））要求修改的文件要带有“重要通知”，解释了进行了哪些更改以及更改的日期。本节并未规定标记更改的某种特定方式，也不控制更改的过程。主要是为了确保接收修改版本的人知道软件的变更历史。对于某些用户，知道他们正在使用程序的标准版本很重要，因为虽然使用分支有很多优点，但也有一些缺点。用户应该了解他们使用的软件版本的历史背景，以便他们可以做出适当的支持选择。最后，GPLv2 2（a）具有学术目的 - 确保未来的开发人员可以使用历时的方法来理解软件。

GPLv2 2(c), a relatively simple section, requires that any program which (before modification) "normally reads commands interactively when run" and displays or prints legal information also display all copyright notices, warranty disclaimer, modification indications and a pointer to the license, even in modified versions. The requirement is relatively simple, and relates to an important policy goal of copyleft: downstream users should be informed of their rights. Its implications and details are straightforward and simple.

GPLv2 2（c）是一个相对简单的部分，要求在运行之前“通常会交互地读取命令”的任何程序，以及显示或打印法律信息的程序也必须在修改版本中显示所有版权声明、保证免责声明、修改指示和指向许可证的指针。这个要求相对简单，与copyleft的一个重要政策目标有关：下游用户应该知道他们的权利。它的影响和细节是简单明了的。

#### 5.1.2 GPLv2 §2(b)

#### 5.1.2 GPLv2 2(b)

Meanwhile, GPLv2 2(b) requires careful and extensive study. Its four short lines embody the some of the essential legal details of "share and share alike". These 46 words are considered by some to be the most worthy of careful scrutiny because they can be a source of great confusion when not properly understood. In considering GPLv2 2(b), first note the qualifier: it *only* applies to derivative, combined and/or modified works that "you distribute or publish". Despite years of education efforts on this matter, many still believe that modifiers of GPL'd software *must* publish or otherwise share their changes. On the contrary, GPLv2 2(b) **does not apply if** the changes are never distributed. Indeed, the freedom to make private, personal, unshared changes to software for personal use only should be protected and defended.[^5-1^]

与此同时，GPLv2第2条(b)要求仔细而广泛的研究。它的四行简短文字包含了“共享及共享同类”的一些基本法律细节。这46个单词被一些人认为是最值得仔细审查的，因为当它们没有被正确理解时，它们可以成为极大的混淆源。在考虑GPLv2第2条(b)时，首先要注意限定语：它仅适用于您分发或发布的派生、组合和/或修改作品。尽管在这个问题上已经进行了多年的教育工作，但许多人仍然认为GPL'd软件的修改者必须发布或以其他方式分享他们的修改。相反，GPLv2第2条(b)不适用于从未分发的更改。事实上，应该保护和维护仅用于个人使用的私人、个人、未共享软件的更改的自由。[^5-1^]

Next, we again encounter the same matter that appears in GPLv2 *§*0, in the following text:

接下来，我们再次遇到出现在GPLv2§0中的相同问题，如下所示：

>"\...that in whole or part contains or is derived from the Program or any part thereof."

>"...包含或源自程序或其任何部分的全部或部分内容。"

Again, the GPL relies here on copyright law. If, under copyright law, the modified version "contains or is derived from" the GPL'd software, then the requirements of GPLv2 2(b) apply. The GPL invokes its control as a copyright license over the modification of the work in combination with its control over distribution of the work.

同样，GPL在这里依赖于版权法。如果根据版权法，修改版本“包含或源自”GPL的软件，则适用GPLv2第2条(b)的要求。GPL通过其对作品修改和分发的版权许可证的控制来调用其控制。

The final clause of GPLv2 2(b) describes what the licensee must do if she distributes or publishes a modified version of the work --- namely, the following:

The final clause of GPLv2 2(b) describes what the licensee must do if she distributes or publishes a modified version of the work --- namely, the following:

GPLv2第2条(b)的最后一条款描述了许可证持有人在分发或发布作品的修改版本时必须执行的操作，即以下内容：

>\[The work must\] be licensed as a whole at no charge to all third parties under the terms of this License.

>作品必须作为一个整体在本许可证的条款下免费授权给所有第三方使用。

That is probably the most tightly-packed phrase in all of the GPL. Consider each subpart carefully.

这可能是GPL中最密集的短语。仔细考虑每个子部分。

The work "as a whole" is what is to be licensed. This is an important point that GPLv2 2 spends an entire paragraph explaining; thus this phrase is worthy of a lengthy discussion here. As a programmer modifies a software program, she generates new copyrighted material --- fixing expressions of ideas into the tangible medium of electronic file storage. That programmer is indeed the copyright holder of those new changes. However, those changes are part and parcel to the original work distributed to the programmer under GPL. Thus, the license of the original work affects the license of the new whole combined and/or derivative work.

"作为一个整体"的作品是需要被授权的。这是GPLv2 2节用整个段落解释的一个重要观点，因此这个短语在这里值得进行详细的讨论。当程序员修改一个软件程序时，她产生了新的版权材料——将思想的表达形式固定到电子文件存储的有形媒介中。那个程序员确实是这些新变化的版权持有人。然而，这些变化是与GPL下分发给程序员的原始作品紧密相关的。因此，原始作品的许可证影响新整个组合和/或派生作品的许可证。

It is certainly possible to take an existing independent work (called) and combine it with a GPL'd program (called ). The license of , when it is distributed as a separate and independent work, remains the prerogative of the copyright holder of . However, when is combined with , it produces a new work that is the combination of the two (called + ). The copyright of this combined work, + , is held by the original copyright holder of each of the two works.

当一个独立的作品（称为 ）与GPL的程序（称为 ）结合时，很可能出现的情况是：当 作为一个单独和独立的作品分发时，其许可证仍然是版权持有人的专属权利。然而，当与 一起组合时，它们产生了一个新的作品（称为 ），它是两个作品的组合。新作品 + 的版权由两个作品的原始版权持有人持有。

In this case, GPLv2 2 lays out the terms by which + may be distributed and copied. By default, under copyright law, the copyright holder of would not have been permitted to distribute + ; copyright law forbids it without the expressed permission of the copyright holder of . (Imagine, for a moment, if were a proprietary product --- would its copyright holders give you permission to create and distribute + without paying them a hefty sum?) The license of , the GPL, states the options for the copyright holder of who may want to create and distribute + . The GPL's pre-granted permission to create and distribute combined and/or derivative works, provided the terms of the GPL are upheld, goes far above and beyond the permissions that one would get with a typical work not covered by a copyleft license. Thus, to say that this condition is any way unreasonable is simply ludicrous.

在这种情况下，GPLv2 §2详细说明了可以分发和复制+的条款。根据版权法，默认情况下，不允许拥有者在未经许可的情况下分发+；版权法禁止这样做。 （想象一下，如果是一个专有产品，其版权持有者会允许您创建和分发+而不支付他们巨额费用吗？）GPL，即版权协议，规定了可能希望创建和分发+的版权所有者的选项。在遵守GPL条款的情况下，预先授予创建和分发组合和/或派生作品的权限远远超出了未受到版权通用许可证保护的作品所能获得的许可权限。因此，认为这个条件在任何方面都是不合理的纯属荒谬。

The GPL recognizes what is outside its scope. When a programmer's work is "separate and independent" from any GPL'd program code with which it could be combined, then the obligations of copyleft do not extend to the work separately distributed. Thus, Far from attempting to extend copyleft beyond the scope of copyright, the licenses explicitly recognize.

GPL认识到超出其范围的事情。当程序员的工作与任何可以与之结合的GPL程序代码“独立且独立”时，版权义务不适用于单独分发的工作。因此，远非试图将通用许可证超出版权范围，这些许可证明确承认了超出其范围的事情。

Thus, GPL recognizes what is outside its scope. When a programmer's work is "separate and inde- pendent" from any GPL'd program code with which it could be combined, then copyleft obligations do not extend to the independent work separately distributed. Thus, far from attempting to extend copyleft beyond the scope of copyright, GPL explicitly limits the scope of copyleft to the scope of copyright.

因此，GPL认识到超出其范围的事情。当程序员的工作与任何可以与之结合的GPL程序代码“独立且独立”时，版权义务不适用于单独分发的工作。因此，远非试图将通用许可证超出版权范围，这些许可证明确限制了通用许可证的范围，以符合版权的范围。

[^5-1^]: Most Free Software enthusiasts believe there is a **moral** obligation to redistribute changes that are generally useful, and they often encourage companies and individuals to do so. However, there is a clear distinction between what one **ought** to do and what one **must** do.

[^5-1^]: 大多数自由软件爱好者认为有一种道德义务重新分发通常有用的更改，他们经常鼓励公司和个人这样做。然而，有一个明确的区别，即人们应该做什么和人们必须做什么。

GPL does not, however (as is sometimes suggested) distinguish "dynamic" from "static" linking of pro- gram code. It is occasionally suggested that a subroutine "dynamically" linked to GPL'd code is, by virtue of the linking alone, inherently outside the scope of copyleft on the main work. This is a misunderstanding. When two software components are joined together to make one work (whether a main and some library subroutines, two objects with their respective methods, or a program and a "plugin") the combination infringes the copyright on the components if the combination required copyright permission from the com- ponent copyright holders, as such permission was either not available or was available on terms that were not observed.

GPL并不区分程序代码的“动态”链接和“静态”链接，尽管有时会有这种说法。有时会建议将一个“动态”链接到GPL代码的子例程视为单独存在于版权保护范畴之外，仅仅由于链接本身。这是一种误解。当两个软件组件被连接在一起形成一个整体（无论是主要程序和一些库子例程、两个具有各自方法的对象还是程序和“插件”）时，如果组合需要从组件版权持有人获得版权许可，而此类许可证要么不可用，要么是在未遵守条款的情况下可用，那么该组合就会侵犯这些组件的版权。

In other words, when combining other software with GPL'd components, the only available permission is GPL. The combiner must observe and respect the GPL observed on the combination as a whole. It matters not if that combination is made with a linker before distribution of the executable, is made by the operating system in order to share libraries for execution efficiency at runtime, or results from runtime references in the language at runtime (as in Java programs).

换句话说，当将其他软件与GPL组件结合使用时，唯一可用的许可是GPL。组合者必须尊重并遵守GPL作为整体所遵守的规定。无论这种组合是在链接器在可执行文件分发之前进行的，还是由操作系统在运行时为了共享库而进行的，或者是由语言在运行时的运行时引用所导致的（如Java程序）。

The next phrase of note in GPLv2 2(b) is "licensed . . . at no charge." This phrase confuses many. The sloppy reader points out this as "a contradiction in GPL" because (in their confused view) that clause of GPLv2 2 says that re-distributors cannot charge for modified versions of GPL'd software, but GPLv2 1 says that they can. Avoid this confusion: the "at no charge" **does not** prohibit re-distributors from charging when performing the acts governed by copyright law,[^5-2^] but rather that they cannot charge a fee for the *license itself*. In other words, redistributors of (modified and unmodified) GPL'd works may charge any amount they choose for performing the modifications on contract or the act of transferring the copy to the customer, but they may not charge a separate licensing fee for the software.

GPLv2 2(b)中需要注意的下一句话是“免费授权”。这句话让很多人感到困惑。粗心的读者会指出这是“GPL中的矛盾”，因为（在他们混淆的观点中）GPLv2 2中的这一条款说，重新发布者不能为GPL软件的修改版本收费，而GPLv2 1却说他们可以。避免这种混淆： “免费”不是禁止重新发布者在执行受版权法约束的行为时收费，[^5-2^] 而是他们不能为软件本身收取单独的许可费用。换句话说，（修改和未修改的）GPL作品的重新发布者可以为执行合同上的修改或向客户传递副本的行为收取任意金额，但他们不能为软件收取单独的许可费。

GPLv2 2(b) further states that the software must "be licensed . . . to all third parties." This too yields some confusion, and feeds the misconception mentioned earlier --- that all modified versions must be made available to the public at large. However, the text here does not say that. Instead, it says that the licensing under terms of the GPL must extend to anyone who might, through the distribution chain, receive a copy of the software. Distribution to all third parties is not mandated here, but GPLv2 2(b) does require re- distributors to license the whole work in a way that extends to all third parties who may ultimately receive a copy of the software.

GPLv2 2(b)进一步规定软件必须“授权……给所有第三方使用。”这也导致了一些困惑，并滋生了前面提到的误解，即所有修改版本都必须向公众公开。然而，这里的文字并没有说到这一点。相反，它说授权必须延伸到通过分发渠道可能获得软件副本的任何人。这里并没有强制要求向所有第三方分发，但GPLv2 2(b)要求再分发者以一种方式授权整个作品，使其适用于最终可能接收到软件副本的所有第三方。

In summary, GPLv2 2(b) says what terms under which the third parties must receive this no-charge license. Namely, they receive it "under the terms of this License", the GPLv2. When an entity *chooses* to redistribute a work based on GPL'd software, the license of that whole work must be GPL and only GPL. In this manner, GPLv2 *§*2(b) dovetails nicely with GPLv2 *§*6 (as discussed in Section [7.3](#gplv2-6-gpl-my-one-and-only) of this tutorial).

总之，GPLv2 2(b)规定了第三方必须获得此无费许可证的条款。换句话说，他们获得的是“本许可证”的条款，即GPLv2。当一个实体选择基于GPL软件再分发作品时，整个作品的许可证必须是GPL，只能是GPL。通过这种方式，GPLv2 2(b)与GPLv2 第6条（如本教程的7.3部分所讨论的）紧密结合。

The final paragraph of GPLv2 2 is worth special mention. It is possible and quite common to aggregate various software programs together on one distribution medium. Computer manufacturers do this when they ship a pre-installed hard drive, and GNU/Linux distribution vendors do this to give a one-stop CD or URL for a complete operating system with necessary applications. The GPL very clearly permits such "mere aggregation" with programs under any license. Despite what you hear from its critics, the GPL is nothing like a virus, not only because the GPL is good for you and a virus is bad for you, but also because simple contact with a GPL'd code-base does not impact the license of other programs. A programmer must expend actual effort to cause a work to fall under the terms of the GPL. Redistributors are always welcome to simply ship GPL'd software alongside proprietary software or other unrelated Free Software, as long as the terms of GPL are adhered to for those packages that are truly GPL'd.

GPLv2第2节的最后一段值得特别提及。在一个分发介质上聚合各种软件程序是可能且很常见的。计算机制造商在出货时这样做，GNU/Linux发行商则提供一站式CD或URL以获取具有必要应用程序的完整操作系统。GPL非常明确地允许这种“纯聚合”与任何许可证下的程序一起使用。尽管你从批评者那里听到的不是这样，GPL与病毒完全不同，不仅因为GPL对你有益而病毒对你有害，而且因为与GPL的代码库的简单接触不会影响其他程序的许可证。程序员必须实际努力才能使一个作品适用于GPL的条款。再分发者总是欢迎将GPL软件与专有软件或其他无关的自由软件一起分发，只要真正使用GPL的软件包的条款遵守GPL即可。

#### 5.1.3 Right to Private Modification

#### 5.1.3 私有修改权

The issue of private modifications of GPLv2'd works deserves special attention. While these rights are clearly explicit in GPLv3 2 2 (see [9.4](#gplv3-2-basic-permissions) of this tutorial for details), the permission to create private modifications is mostly implicit in GPLv2. Most notably, the requirements of GPLv2 2 (and GPLv2 3, which will be discussed next) are centered around two different copyright controls: both modification *and* distribution. As such, GPLv2 2's requirements need only be met when a modified version is distributed; one need not follow them for modified versions that are not distributed.[^5-3^]

对于 GPLv2 的作品进行私有修改的问题需要特别注意。虽然 GPLv3 2 2 中明确列出了这些权利（有关详情请参见本教程的 9.4 部分），但是在 GPLv2 中，创造私有修改的许可大多是暗含的。特别是，GPLv2 2（和将在下一节讨论的 GPLv2 3）的要求围绕两个不同的版权控制展开：修改和分发。因此，只有在分发修改版本时才需要遵守 GPLv2 2 的要求；对于未分发的修改版本，不需要遵守这些要求。[^5-3^]

[^5-2^]: Recall that you could by default charge for any acts not governed by copyright law, because the license controls are confined by copyright.

[^5-2^]: 请记住，您默认可以收取任何不受版权法约束的行为费用，因为许可控制受版权限制。

However, the careful reader of GPLv2 will notice that, unlike GPLv3, no other clauses of the license actually give explicit permission to make private modifications. Since modification of software is a control governed by copyright, a modifier needs permission from the copyright holder to engage in that activity.

然而，仔细阅读 GPLv2 的读者会注意到，与 GPLv3 不同，许可证的其他条款实际上没有明确允许进行私有修改的许可。由于软件修改是受版权控制的控制，因此修改者需要获得版权持有人的许可才能从事这项活动。

In practice, however, traditional GPLv2 interpretation has always assumed that blanket permission to create non-distributed modified versions was available, and the [FSF has long opined that distribution of](http://www.gnu.org/licenses/gpl-faq.html#GPLRequireSourcePostedPublic) [modified versions is never mandatory.](http://www.gnu.org/licenses/gpl-faq.html#GPLRequireSourcePostedPublic) This issue is one of many where GPLv3 clarifies in explicit text the implicit policy and intent that was solidified via long-standing interpretation of GPLv2.

然而，在实践中，传统的 GPLv2 解释一直假定拥有创造非分发修改版本的全面许可，而FSF 长期以来一直认为分发修改版本从来不是强制性的。这个问题是 GPLv3 明确文本阐明了长期解释 GPLv2 所确定的隐含政策和意图的众多问题之一。

### 5.2 GPLv2 §3: Producing Binaries

### 5.2 GPLv2 第3条：生成二进制文件

Software is a strange beast when compared to other copyrightable works. It is currently impossible to make a film or a book that can be truly obscured. Ultimately, the full text of a novel, even one written by William Faulkner, must be presented to the reader as words in some human-readable language so that they can enjoy the work. A film, even one directed by David Lynch, must be perceptible by human eyes and ears to have any value.

与其他可版权作品相比，软件是一种奇特的生物。目前还没有一种能真正被隐藏的电影或书籍。即使是威廉·福克纳写的小说全文也必须以某种人类可读的语言形式呈现给读者，以便他们能够享受这部作品。一部由大卫·林奇执导的电影也必须可被人类的眼睛和耳朵感知才有任何价值。

Software is not so. While the source code --- the human-readable representation of software --- is of keen interest to programmers, users and programmers alike cannot make the proper use of software in that human-readable form. Binary code --- the ones and zeros that the computer can understand --- must be predicable and attainable for the software to be fully useful. Without the binaries, be they in object or executable form, the software serves only the didactic purposes of computer science.

软件不同。尽管源代码是软件的人类可读表现形式，对程序员来说是非常重要的，但用户和程序员不能以这种人类可读的形式正确地使用软件。二进制代码，即计算机能够理解的一和零，必须是可预测且可获得的，才能充分发挥软件的作用。如果没有二进制文件，无论是目标文件还是可执行文件，该软件只能用于计算机科学的教学目的。

Under copyright law, binary representations of the software are simply modified versions (and/or deriva- tive works) of the source code. Applying a systematic process (i.e., "compilation"[^5-4^]) to a work of source code yields binary code. The binary code is now a new work of expression fixed in the tangible medium of electronic file storage.

根据版权法，软件的二进制表示只是源代码的修改版本（和/或派生作品）。将源代码作品应用一种系统的过程（即“编译”[^5-4^]）会产生二进制代码。现在，二进制代码是以电子文件存储为载体的新的表达形式。

Therefore, for GPL'd software to be useful, the GPL, since it governs the rules for creation of modified works, must grant permission for the generation of binaries. Furthermore, notwithstanding the relative popularity of source-based GNU/Linux distributions like Gentoo, users find it extremely convenient to receive distribution of binary software. Such distribution is the redistribution of modified works of the software's source code. GPLv2 3 addresses the matter of creation and distribution of binary versions.

因此，为了让GPL的软件有用，GPL必须授予生成二进制文件的许可，因为它管理修改作品的规则。此外，尽管基于源代码的GNU/Linux发行版（如Gentoo）相对受欢迎，用户发现接收二进制软件的分发非常方便。这种分发是软件源代码的修改作品的再分发。GPLv2 3解决了创建和分发二进制版本的问题。

Under GPLv2 3, binary versions may be created and distributed under the terms of GPLv2 1--2, so all the material previously discussed applies here. However, GPLv2 3 must go a bit further. Access to the software's source code is an incontestable prerequisite for the exercise of the fundamental freedoms to modify and improve the software. Making even the most trivial changes to a software program at the binary level is effectively impossible. GPLv2 3 must ensure that the binaries are never distributed without the source code, so that these freedoms are passed through the distribution chain.

根据GPLv2 3，可以在GPLv2 1-2的条款下创建和分发二进制版本，因此之前讨论的所有材料在这里都适用。但是，GPLv2 3必须更进一步。访问软件源代码是行使修改和改进软件的基本自由的必要条件。在二进制层面上进行最微小的更改实际上是不可能的。GPLv2 3必须确保二进制文件没有在未提供源代码的情况下进行分发，以便这些自由通过分发链传递。

GPLv2 3 permits distribution of binaries, and then offers three options for distribution of source code along with binaries. The most common and the least complicated is the option given under GPLv2 3(a).

GPLv2 3允许分发二进制文件，然后提供了三种选项，以便将源代码与二进制文件一起分发。最常见且最简单的选项是GPLv2 3(a)提供的选项。

GPLv2 3(a) offers the option to directly accompany the source code alongside the distribution of the binaries. This is by far the most convenient option for most distributors, because it means that the source- code provision obligations are fully completed at the time of binary distribution (more on that later).

GPLv2第3条(a)提供了在二进制文件分发的同时直接附带源代码的选择。这对于大多数分发者来说是最方便的选择，因为它意味着在二进制分发时完全完成了源代码提供义务（稍后将更详细地说明）。

#### 5.2.1 Complete, Corresponding Source (CCS)

#### 5.2.1 完整、对应的源代码（CCS）

Under GPLv2 3(a), the source code provided must be the "corresponding source code." Here "correspond- ing" primarily means that the source code provided must be that code used to produce the binaries being distributed. That source code must also be "complete". GPLv2 3's penultimate paragraph explains in de- tail what is meant by "complete". In essence, it is all the material that a programmer of average skill would need to actually use the source code to produce the binaries she has received. Complete source is required so that, if the licensee chooses, she should be able to exercise her freedoms to modify and redistribute changes. Without the complete source, it would not be possible to make changes that were actually directly derived from the version received.

在GPLv2 3(a)下，提供的源代码必须是“对应的源代码”。在这里，“对应的”主要意味着提供的源代码必须是用于生成所分发的二进制文件的代码。该源代码还必须是“完整的”。GPLv2 3的倒数第二段详细解释了“完整”的含义。实质上，它是程序员需要实际使用源代码来生成收到的二进制文件所需的所有材料。需要完整的源代码，以便许可证持有人选择时，可以行使修改和重新分发更改的自由。如果没有完整的源代码，就不可能制作实际上是直接源自所收到版本的更改。

[^5-3^]: As a matter of best practice, it's useful to assume that all software may eventually be distributed later, even if there no plans for distribution at this time. Too often, GPL violations occur because of a late distribution decision of software that was []{#_bookmark66 .anchor}otherwise never intended for distribution.

[^5-3^]: 作为最佳实践，有用的做法是假定所有软件最终都可能被分发，即使现在没有分发计划。由于本来没有意图进行分发的软件最终作出了分发决定，因此往往会出现GPL违规行为。

[^5-4^]: "Compilation" in this context refers to the automated computing process of converting source code into binaries. It has absolutely nothing to do with the term "compilation" in copyright statues.

[^5-4^]: 在此上下文中，“编译”是指将源代码自动转换为二进制文件的计算过程。它与版权法规中的“编译”一词完全无关。

Based on the appearance of those two words, GPL theorists will often refer to the source code required under the previsions of this section as "Complete, Corresponding Source", sometimes abbreviated as CCS. CCS is not a formal, defined term in GPLv2, but rather, GPL theorists coined the acronym CCS to embody not just the concepts of "complete" and "corresponding" as found in GPLv2, but the entirety of GPLv2's requirements for source code provisioning. In other words, GPL theorists might say: "the company provided some source, but it wasn't CCS", which would mean the source code failed in some ways to meet some term of GPLv2.

基于这两个词的出现，GPL理论家经常将此部分规定要求的源代码称为“完整、对应的源代码”，有时缩写为CCS。CCS不是GPLv2中的正式定义术语，而是GPL理论家创造出的缩写，它不仅代表了GPLv2中“完整”和“对应”的概念，而且代表了GPLv2对源代码提供的全部要求。换句话说，GPL理论家可能会说：“公司提供了一些源代码，但它不是CCS”，这意味着源代码在某些方面未能满足GPLv2的某些条款。

Indeed, CCS needs completely include not just that source which is directly translated by the compiler into object code, but other materials necessary to convert the source into equivalent binaries. Specifically, GPLv2 3 requires that the source code include "meta-material" like scripts, interface definitions, and other material that is used to "control compilation and installation" of the binaries. In this manner, those further down the distribution chain are assured that they have the unabated freedom to build their own modified works from the sources provided.

事实上，CCS必须完全包括不仅直接由编译器转换为目标代码的源代码，还包括将源代码转换为等效二进制文件所需的其他材料。具体而言，GPLv2 3要求源代码包括“元材料”，如脚本、接口定义和其他用于“控制编译和安装”二进制文件的材料。以这种方式，分销链中的下游用户可以确保他们可以从提供的源代码构建自己的修改作品，而没有受到任何限制。

This requirement is not merely of theoretical value. If you pay a high price for a copy of GPL'd binaries (which comes with CCS, of course), you have the freedom to redistribute that work at any fee you choose, or not at all. Sometimes, companies attempt a GPL-violating cozenage whereby they produce very specialized binaries (perhaps for an obscure architecture). They then give source code that does correspond, but withhold the "incantations" and build plans they used to make that source compile into the specialized binaries. Such distributions violate GPL, since the downstream users cannot effectively "control compilation and installation" of the binaries.

这个要求不仅仅具有理论价值。如果你花了高价购买了带有CCS的GPL二进制文件副本，你就有自由以任何你选择的费用重新分发该作品，或者根本不分发。有时，一些公司会尝试违反GPL的欺诈手段，他们会生产非常专业化的二进制文件（也许是针对某种不常见的架构），然后提供相应的源代码，但是却不提供他们用来将这个源代码编译成专业化二进制文件所需要的"咒语"和构建计划。这样的发行版违反了GPL，因为下游用户无法有效地"控制编译和安装"这些二进制文件。

#### 5.2.2 Additional Source Provision Options

#### 5.2.2 其他提供源代码的选项

Software distribution comes in many forms. Embedded manufacturers, for example, have the freedom to put GPL'd software into mobile devices with very tight memory and space constraints. In such cases, putting the source right alongside the binaries on the machine itself might not be an option. While it is recommended that this be the default way that people comply with GPL, the GPL does provide options when such distribution is unfeasible.

软件分发有多种形式。例如，嵌入式制造商可以自由地将GPL软件放入内存和空间非常有限的移动设备中。在这种情况下，将源代码放在机器上的二进制文件旁边可能不是一个选择。尽管建议这是人们遵守GPL的默认方式，但当这种分发不可行时，GPL确实提供了选项。

GPLv2 3, therefore, allows source code to be provided on any physical "medium customarily used for software interchange." By design, this phrase covers a broad spectrum --- the phrase seeks to pre-adapt to changes in technology. When GPLv2 was first published in June 1991, distribution on magnetic tape was still common, and CD was relatively new. By 2002, CD was the default. By 2007, DVD's were the default. Now, it's common to give software on USB drives and SD cards. This language in the license must adapt with changing technology.

因此，GPLv2 3允许在任何“用于软件交换的通常物理介质”上提供源代码。这个短语的设计旨在涵盖广泛的领域，它试图预先适应技术的变化。当GPLv2于1991年6月首次发布时，磁带分发仍然很常见，而CD则相对较新。到2002年，CD是默认选项。到2007年，DVD成为默认选项。现在，常见的做法是在USB驱动器和SD卡上提供软件。许可证中的这种语言必须随着技术的变化而适应。

Meanwhile, the binding created by the word "customarily" is key. Many incorrectly believe that dis- tributing binary on CD and source on the Internet is acceptable. In the corporate world in industrialized countries, it is indeed customary to simply download a CDs' worth of data quickly. However, even today in the USA, many computer users are not connected to the Internet, and most people connected to the Internet still have limited download speeds. Downloading CDs full of data is not customary for them in the least. In some cities in Africa, computers are becoming more common, but Internet connectivity is still available only at a few centralized locations. Thus, the "customs" here are normalized for a worldwide userbase. Simply providing source on the Internet --- while it is a kind, friendly and useful thing to do --- is not usually sufficient.

与此同时，“通常”一词所造成的约束是关键。许多人错误地认为在CD上分发二进制文件，在互联网上提供源代码是可以接受的。在工业化国家的公司世界中，只需快速下载一张CD的数据是很常见的。但是，即使是今天，在美国许多计算机用户仍未连接到互联网，大多数连接到互联网的人仍然具有有限的下载速度。对他们来说，下载充满数据的CD是一件非常不寻常的事情。在非洲的一些城市，计算机变得越来越普遍，但互联网连接仍然只在少数集中的位置可用。因此，这里的“惯例”是针对全球用户群的。仅仅在互联网上提供源代码——虽然这是一件善意和有用的事情——通常是不够的。

Note, however, a major exception to this rule, given by the last paragraph of GPLv2 3. *If* distribution of the binary files is made only on the Internet (i.e., "from a designated place"), *then* simply providing the source code right alongside the binaries in the same place is sufficient to comply with GPLv2 *§*3.

然而，GPLv2 3最后一段给出了一个主要例外。如果二进制文件的分发只是在互联网上进行（即“从指定的位置”），那么在同一位置直接提供源代码与二进制文件就足以符合GPLv2 §3的要求。

As is shown above, under GPLv2 3(a), embedded manufacturers can put the binaries on the device and ship the source code along on a CD. However, sometimes this turns out to be too costly. Including a CD with every device could prove too costly, and may practically (although not legally) prohibit using GPL'd software. For this situation and others like it, GPLv2*§* 3(b) is available.

如上所示，在GPLv2 3(a)下，嵌入式制造商可以将二进制文件放在设备上并将源代码放在CD上进行运输。然而，有时这种做法会被认为成本过高。为每个设备包含CD可能会过于昂贵，而且实际上可能（尽管法律上不允许）禁止使用GPL'd软件。对于这种情况和其他类似情况，GPLv2 § 3(b)是可用的。

GPLv2 3(b) allows a distributor of binaries to instead provide a written offer for source code alongside those binaries. This is useful in two specific ways. First, it may turn out that most users do not request the source, and thus the cost of producing the CDs is saved --- a financial and environmental windfall. In addition, along with a GPLv2 3(b) compliant offer for source, a binary distributor might choose to *also* give a URL for source code. Many who would otherwise need a CD with source might turn out to have those coveted high bandwidth connections, and are able to download the source instead --- again yielding environmental and financial windfalls.

GPLv2 3(b)允许二进制分发者提供书面源代码提供，而不是与这些二进制文件一起提供源代码。这有两个具体的用途。首先，可能大多数用户不请求源代码，因此节省了制作CD的成本 - 这是一笔财务和环境的收益。此外，与GPLv2 3(b)兼容的源代码提供书面提供，二进制分发者可能会选择为源代码也提供URL。许多其他需要源CD的人可能会发现拥有所需的高带宽连接，能够下载源代码，从而再次产生环境和财务收益。

However, note that regardless of how many users prefer to get the source online, GPLv2 3(b) does place lasting long-term obligations on the binary distributor. The binary distributor must be prepared to honor that offer for source for three years and ship it out (just as they would have had to do under GPLv2 3(a)) at a moment's notice when they receive such a request. There is real organizational cost here: support engineers must be trained how to route source requests, and source CD images for every release version for the last three years must be kept on hand to burn such CDs quickly. The requests might not even come from actual customers; the offer for source must be valid for "any third party".

但是，请注意，无论有多少用户喜欢在线获取源代码，GPLv2 3(b)都会对二进制分发者产生长期的持续义务。二进制分发者必须准备好在三年内执行源代码提供书面提供的义务，并在收到此类请求时立即运输（就像在GPLv2 3(a)下所必须做的那样）。这里确实存在实际的组织成本：支持工程师必须接受培训以了解如何路由源请求，并且必须保留过去三年每个发布版本的源CD映像以便快速刻录这些CD。这些请求甚至可能不是来自实际的客户；源代码提供书面提供必须对“任何第三方”有效。

That phrase is another place where some get confused --- thinking again that full public distribution of source is required. The offer for source must be valid for "any third party" because of the freedoms of redistribution granted by GPLv2 1--2. A company may ship a binary image and an offer for source to only one customer. However, under GPL, that customer has the right to redistribute that software to the world if she likes. When she does, that customer has an obligation to make sure that those who receive the software from her can exercise their freedoms under GPL --- including the freedom to modify, rebuild, and redistribute the source code.

这句话是另一个容易让人困惑的地方 —— 再次认为必须完全公开发布源代码。由于 GPLv2 1-2 授予的再分发自由，源代码的提供必须对“任何第三方”有效。一家公司可以向一个客户提供一个二进制映像和一个源代码的提供，但在 GPL 下，该客户有权将该软件重新分发给全世界，如果她愿意的话。当她这样做时，该客户有义务确保那些从她那里接收软件的人可以行使 GPL 下的自由权利，包括修改、重建和重新分发源代码。

GPLv2 3(c) is created to save her some trouble, because by itself GPLv2 3(b) would unfairly favor large companies. GPLv2 3(b) allows the separation of the binary software from the key tool that people can use to exercise their freedom. The GPL permits this separation because it is good for re-distributors, and those users who turn out not to need the source. However, to ensure equal rights for all software users, anyone along the distribution chain must have the right to get the source and exercise those freedoms that require it.

GPLv2 3(c) 的创建是为了节省她的一些麻烦，因为单独 GPLv2 3(b) 将不公平地偏向大公司。GPLv2 3(b) 允许将二进制软件与人们用于行使其自由的关键工具分离。GPL 允许这种分离，因为这对重新分发者和那些不需要源代码的用户是有益的。然而，为了确保所有软件用户的平等权利，沿着分发链的任何人都必须有权获取源代码并行使需要源代码的自由。

Meanwhile, GPLv2 3(b)'s compromise primarily benefits companies that distribute binary software commercially. Without GPLv2 3(c), that benefit would be at the detriment of the companies' customers; the burden of source code provision would be unfairly shifted to the companies' customers. A customer, who had received binaries with a GPLv2 3(b)-compliant offer, would be required under GPLv2 (sans GPLv2 3(c)) to acquire the source, merely to give a copy of the software to a friend who needed it. GPLv2 3(c) reshifts this burden to entity who benefits from GPLv2 3(b).

与此同时，GPLv2 3(b) 的妥协主要使得商业分发二进制软件的公司受益。如果没有 GPLv2 3(c)，这种利益将损害公司的客户；源代码提供的负担将不公平地转移到公司的客户身上。一个已收到 GPLv2 3(b)-兼容提供的二进制文件的客户，将根据 GPLv2 (不带 GPLv2 3(c)) 要求获取源代码，仅仅是为了将软件副本提供给需要的朋友。GPLv2 3(c) 将这个负担重新转移到从 GPLv2 3(b) 受益的实体身上。

GPLv2 3(c) allows those who undertake *noncommercial* distribution to simply pass along a GPLv2 3(b)- compliant source code offer. The customer who wishes to give a copy to her friend can now do so without provisioning the source, as long as she gives that offer to her friend. By contrast, if she wanted to go into business for herself selling CDs of that software, she would have to acquire the source and either comply via GPLv2 3(a), or write her own GPLv2 3(b)-compliant source offer.

GPLv2 3(c) 允许那些进行“非商业”分发的人简单地传递一个 GPLv2 3(b) —— 兼容的源代码提供。希望将副本交给她朋友的客户现在可以这样做，而无需提供源代码，只要她把这个提供转交给她的朋友即可。相比之下，如果她想自己开业，销售该软件的 CD，她将不得不获取源代码，并通过 GPLv2 3(a) 或编写自己的 GPLv2 3(b) —— 兼容的源代码提供来遵守 GPL。

This process is precisely the reason why a GPLv2 3(b) source offer must be valid for all third parties. At the time the offer is made, there is no way of knowing who might end up noncommercially receiving a copy of the software. Companies who choose to comply via GPLv2 3(b) must thus be prepared to honor all incoming source code requests. For this and the many other additional necessary complications under GPLv2 *§§*3(b--c), it is only rarely a better option than complying via GPLv2 *§*3(a).

这个过程正是 GPLv2 3(b) 源代码提供必须对所有第三方有效的原因。在提供源代码的时候，没有办法知道谁会非商业地获得软件的副本。因此，选择通过 GPLv2 3(b) 来遵守许可证的公司必须准备好满足所有源代码请求。因为在 GPLv2 §3(b-c) 下有许多其他必要的复杂程序，所以这种方式通常不如遵守 GPLv2 §3(a)。


## CHAPTER 6 GPL'S IMPLIED PATENT GRANT

## 第6章 GPL的暗示专利授权

We digress again briefly from our section-by-section consideration of GPLv2 to consider the interaction between the terms of GPL and patent law. The GPLv2, despite being silent with respect to patents, actually confers on its licensees more rights to a licensor's patents than those licenses that purport to address the issue. This is the case because patent law, under the doctrine of implied license, gives to each distributee of a patented article a license from the distributor to practice any patent claims owned or held by the distributor that cover the distributed article. The implied license also extends to any patent claims owned or held by the distributor that cover "reasonably contemplated uses" of the patented article. To quote the Federal Circuit Court of Appeals, the highest court for patent cases other than the Supreme Court:

我们再次暂时跳出对GPLv2的逐段审查，来考虑GPL条款和专利法之间的互动关系。尽管GPLv2在专利方面保持沉默，但它实际上向其许可证持有人授予了比那些声称处理此问题的许可证更多的许可证权利。这是因为根据暗示许可证原则，专利法规定，专利的分发者向每个分销专利物品的受让人授予许可证，该许可证覆盖分销的物品。暗示许可证也扩展到分销者拥有或持有的任何专利要求，该要求涵盖专利物品的“合理预期使用”。引用联邦巡回上诉法院（非最高法院）的话：

>Generally, when a seller sells a product without restriction, it in effect promises the purchaser that in exchange for the price paid, it will not interfere with the purchaser's full enjoyment of the product purchased. The buyer has an implied license under any patents of the seller that dominate the product or any uses of the product to which the parties might reasonably contemplate the product will be put.

>通常情况下，当卖家无限制地销售产品时，它实际上向购买者承诺，在支付的价格的交换条件下，不会干扰购买者对所购买产品的完全享用。买方在销售者拥有专利的任何专利下拥有隐含许可证，该专利主导产品或产品可能合理预期的任何用途。
 
Hewlett-Packard Co. v. Repeat-O-Type Stencil Mfg. Corp., Inc., 123 F.3d 1445, 1451 (Fed. Cir. 1997).

Hewlett-Packard Co. v. Repeat-O-Type Stencil Mfg. Corp.， Inc.，123 F.3d 1445, 1451（Fed. Cir. 1997）。

Of course, Free Software is licensed, not sold, and there are indeed restrictions placed on the licensee, but those differences are not likely to prevent the application of the implied license doctrine to Free Software, because software licensed under the GPL grants the licensee the right to make, use, and sell the software, each of which are exclusive rights of a patent holder. Therefore, although the GPLv2 does not expressly grant the licensee the right to do those things under any patents the licensor may have that cover the software or its reasonably contemplated uses, by licensing the software under the GPLv2, the distributor impliedly licenses those patents to the GPLv2 licensee with respect to the GPLv2'd software.

当然，自由软件是许可，而不是销售，并且的确对许可证持有人施加了限制，但是这些差异不太可能阻止暗示许可证原则适用于自由软件，因为根据GPLv2许可的软件授予许可证持有人行使专利所有者的专属权利，即制作、使用和销售该软件。因此，尽管GPLv2没有明确授予许可证持有人使用其可能涵盖软件或其合理预期使用的任何专利的权利，但通过在GPLv2下许可软件，分销商对于GPLv2许可证持有人在GPLv2下许可有关GPLv2软件的这些专利授予了暗示许可证。

An interesting issue regarding this implied patent license of GPLv2'd software is what would be considered "uses of the \[software\] to which the parties might reasonably contemplate the product will be put." A clever advocate may argue that the implied license granted by GPLv2 is larger in scope than the express license in other Free Software licenses with express patent grants, in that the patent license clause of many of those other Free Software licenses are specifically limited to the patent claims covered by the code as licensed by the patentee.

关于 GPLv2 软件的这个暗示专利许可的一个有趣问题是，“当事方可能合理地预期产品将被用于的软件用途”。一个聪明的辩护人可能会主张，GPLv2 授予的暗示许可比其他明示专利授权的自由软件许可证的范围更广，因为许多其他自由软件许可证的专利许可条款特别限制了专利权人许可的代码所涵盖的专利权主张。

In contrast, a GPLv2 licensee, under the doctrine of implied patent license, is free to practice any patent claims held by the licensor that cover "reasonably contemplated uses" of the GPL'd code, which may very well include creation and distribution of modified works since the GPL's terms, under which the patented code is distributed, expressly permits such activity.

相比之下，GPLv2 授权人根据暗示专利许可原则可以自由实践授权人拥有的涵盖“合理预期用途”的专利权主张，这很可能包括创建和分发修改后的作品，因为 GPL 的条款明确允许这种活动，而该专利权主张覆盖了GPL的代码所涵盖的内容。

Further supporting this result is the Federal Circuit's pronouncement that the recipient of a patented article has, not only an implied license to make, use, and sell the article, but also an implied patent license to repair the article to enable it to function properly, Bottom Line Mgmt., Inc. v. Pan Man, Inc., 228 F.3d 1352 (Fed. Cir. 2000). Additionally, the Federal Circuit extended that rule to include any future recipients of the patented article, not just the direct recipient from the distributor. This theory comports well with the idea of Free Software, whereby software is distributed among many entities within the community for the purpose of constant evolution and improvement. In this way, the law of implied patent license used by the GPLv2 ensures that the community mutually benefits from the licensing of patents to any single community member.

联邦巡回法院在 Bottom Line Mgmt.，Inc. v. Pan Man，Inc.，228 F.3d 1352（Fed. Cir. 2000）中进一步支持了这一结果，该法院宣称，专利物品的接收者不仅具有制造、使用和销售该物品的暗示许可，而且还具有修理该物品以使其正常运行的暗示专利许可，而这也适用于专利物品的任何未来接收者，而不仅仅是从分销商直接接收的接收者。这个理论与自由软件的思想相符，即将软件分发给社区中的许多实体，以实现不断的演进和改进。通过GPLv2使用的暗示专利许可法，确保社区从专利许可中共同受益。

Note that simply because GPLv2'd software has an implied patent license does not mean that any patents held by a distributor of GPLv2'd code become worthless. To the contrary, the patents are still valid and enforceable against either:

需要注意的是，仅因为 GPLv2 的软件具有暗示专利许可，并不意味着任何分发 GPLv2 软件的公司持有的专利就变得毫无价值。相反，这些专利仍然有效，并且可以针对以下任一方强制执行：

 a. any software other than that licensed under the GPLv2 by the patent holder, and

 b. any party that does not comply with the GPLv2 with respect to the licensed software.

a. 除了由专利持有人授权的GPLv2软件之外的任何软件；

b. 与许可软件有关的任何方不遵守GPLv2许可证。

For example, if Company has a patent on advanced Web browsing, but also licenses a Web browsing program under the GPLv2, then it cannot assert the patent against any party based on that party's use of Company 's GPL'd Web browsing software program, or on that party's creation and use of modified versions of that GPL'd program. However, if a party uses that program without complying with the GPLv2, then Company can assert both copyright infringement claims against the non-GPLv2-compliant party and infringement of the patent, because the implied patent license only extends to use of the software in accordance with the GPLv2. Further, if Company distributes a competitive advanced Web browsing program that is not a modified version of Company 's GPL'd Web browsing software program, Company is free to assert its patent against any user or distributor of that product. It is irrelevant whether Company 's program is also distributed under the GPLv2, as Company can not grant implied licenses to Company 's patent.

例如，如果一家公司拥有先进的Web浏览专利，但也根据GPLv2许可证授权了一个Web浏览程序，那么它就不能基于该方使用公司的GPLv2 Web浏览软件程序或者使用该程序的修改版本来主张专利权。然而，如果一方未遵守GPLv2使用了该程序，那么公司可以主张针对该非GPLv2兼容方的版权侵权索赔和专利侵权，因为暗示的专利许可仅限于按照GPLv2使用软件。此外，如果公司发布一款不是公司的GPLv2 Web浏览软件程序的改进版竞争性先进Web浏览程序，那么公司可以自由地针对该产品的任何用户或分销商主张其专利权。无论公司的程序是否也在GPLv2下发布，都是无关紧要的，因为公司不能授予对公司的专利的暗示许可证。

This result also reassures companies that they need not fear losing their proprietary value in patents to competitors through the GPLv2 implied patent license, as only those competitors who adopt and comply with the GPLv2's terms can benefit from the implied patent license. To continue the example above, Company does not receive a free ride on Company 's patent, as Company has not licensed-in and then redistributed Company A's advanced Web browser under the GPLv2. If Company does do that, however, Company still has not lost competitive advantage against Company , as Company must then, when it re-distributes Company 's program, grant an implied license to any of its patents that cover the program. Further, if Company relicenses an improved version of Company A's program, it must do so under the GPLv2, meaning that any patents it holds that cover the improved version are impliedly licensed to any licensee. As such, the only way Company can benefit from Company 's implied patent license, is if it, itself, distributes Company 's software program and grants an implied patent license to any of its patents that cover that program.

这个结果还让公司放心，它们不必担心通过GPLv2暗示专利许可证将专利的专有价值损失给竞争对手，因为只有那些采用并遵守GPLv2条款的竞争对手才能从暗示的专利许可证中受益。继续以上述例子，公司不会因为未将公司A的先进Web浏览器授权并再分发GPLv2而获得免费乘车。然而，如果公司这样做了，公司仍然没有失去对公司的竞争优势，因为当它重新分发公司的程序时，必须授予任何涵盖该程序的专利的暗示许可证。此外，如果公司重新授权改进版的公司A程序，那么它必须按照GPLv2这样做，这意味着它持有的覆盖改进版的任何专利都会被暗示地许可给任何许可证持有者。因此，公司获得公司的暗示专利许可证的唯一途径是，如果它本身分发公司的软件程序并向任何涵盖该程序的专利授予暗示专利许可证。


## CHAPTER 7 DEFENDING FREEDOM ON MANY FRONTS

## 第7章 在多个方面捍卫自由

Chapters [3] and [5] presented the core freedom-defending provisions of GPLv2, which are in GPLv2 0--3. GPLv2 4--7 of the GPLv2 are designed to ensure that GPLv2 0--3 are not infringed, are enforceable, are kept to the confines of copyright law but also not trumped by other copyright agreements or components of other entirely separate legal systems. In short, while GPLv2 *§§*0--3 are the parts of the license that defend the freedoms of users and programmers, GPLv2 *§§*4--7 are the parts of the license that keep the playing field clear so that *§§* 0--3 can do their jobs.

第3章和第5章介绍了 GPLv2 的核心捍卫自由条款，即 GPLv2 第0-3条。GPLv2 的 第4-7条旨在确保 GPLv2 第0-3条不被侵犯、可执行，并受到版权法的限制，但也不会被其他版权协议或完全独立的法律体系的组成部分所取代。简而言之，虽然 GPLv2 第0-3条是捍卫用户和程序员自由的许可证部分，但 GPLv2 第4-7条是保持竞争环境清晰的许可证部分，以便第0-3条可以发挥其作用。

### 7.1 GPLv2 §4: Termination on Violation

### 7.1 GPLv2 第4条：违规终止

GPLv2 4 is GPLv2's termination clause. Upon first examination, it seems strange that a license with the goal of defending users' and programmers' freedoms for perpetuity in an irrevocable way would have such a clause. However, upon further examination, the difference between irrevocability and this termination clause becomes clear. (See [7.4](#gplv2-irrevocability) for expanded discussion of GPLv2 irrevocability.)

GPLv2 4 是 GPLv2 的终止条款。初看起来，一个旨在永久且不可撤销地捍卫用户和程序员自由的许可证竟然有这样的条款，似乎有些奇怪。然而，进一步的研究表明，不可撤销和此终止条款之间的区别变得清晰了。（有关 GPLv2 不可撤销的更广泛讨论，请参见7.4。）

The GPL is irrevocable in the sense that once a copyright holder grants rights for someone to copy, modify and redistribute the software under terms of the GPL, they cannot later revoke that grant. Since the GPL has no provision allowing the copyright holder to take such a prerogative, the license is granted as long as the copyright remains in effect.[^7-1^] The copyright holders have the right to relicense the same work under different licenses (see Section [12.2](#business-models) of this tutorial), or to stop distributing the GPLv2'd version (assuming GPLv2 3(b) was never used), but they may not revoke the rights under GPLv2 already granted.

GPL是不可撤销的，因为一旦版权持有人授予他人在GPL条款下复制、修改和重新分发软件的权利，他们就不能撤回该授权。由于GPL没有允许版权持有人采取这种特权的规定，因此只要版权仍然有效，许可证就会被授予。[^7-1^] 版权持有人有权在不同的许可证下重新许可同一作品（请参见本教程的第12.2节），或停止分发GPLv2版本（假设从未使用GPLv2 3(b)），但他们不能撤销已授予的GPLv2下的权利。

In fact, when an entity loses their right to copy, modify and distribute GPL'd software, it is because of their *own actions*, not that of the copyright holder. The copyright holder does not decide when GPLv2 4 termination occurs (if ever); rather, the actions of the licensee determine that.

实际上，当一个实体失去复制、修改和分发GPL软件的权利时，是因为他们自己的行为，而不是版权持有人的行为。版权持有人不决定GPLv2 4终止的时间（如果有的话），而是许可证持有人的行为决定。

Under copyright law, the GPL has granted various rights and freedoms to the licensee to perform specific types of copying, modification, and redistribution. By default, all other types of copying, modification, and redistribution are prohibited. GPLv2 4 says that if you undertake any of those other types (e.g., redistributing binary-only in violation of GPLv2 3), then all rights under the license --- even those otherwise permitted for those who have not violated --- terminate automatically.

根据版权法，GPL已经授予许可证持有人执行特定类型的复制、修改和重新分发的各种权利和自由。默认情况下，所有其他类型的复制、修改和重新分发都是禁止的。GPLv2 4规定，如果您进行任何这些其他类型的活动（例如，在违反GPLv2 3的情况下重新分发仅限二进制文件），那么所有许可证下的权利，即使是对于没有违反许可证的人，也会自动终止。

GPLv2 4 makes GPLv2 enforceable. If licensees fail to adhere to the license, then they are stuck without any permission under to engage in activities covered by copyright law. They must completely cease and desist from all copying, modification and distribution of the GPL'd software.

GPLv2 4使GPLv2可强制执行。如果许可证持有人未能遵守许可证，那么他们就没有任何在版权法下从事活动的许可。他们必须完全停止所有对GPL软件的复制、修改和分发。

[^7-1^]: In the USA, due to unfortunate legislation, the length of copyright is nearly perpetual, even though the Constitution forbids perpetual copyright.

[^7-1^]: 在美国，由于不幸的立法，版权期限几乎是永久的，尽管宪法禁止永久版权。

At that point, violating licensees must gain the forgiveness of the copyright holders to have their rights restored. Alternatively, the violators could negotiate another agreement, separate from GPL, with the copyright holder. Both are common practice, although Chapter [13.3](#understanding-whos-enforcing) explains further key differences between these two very different uses of GPL.

在那时，违反许可证的人必须得到版权持有人的谅解，才能恢复他们的权利。或者，违规者可以与版权持有人另行协商一份与GPL无关的协议。尽管这两种做法都很常见，但第13.3章进一步解释了这两种非常不同的GPL用途之间的关键差异。

### 7.2 GPLv2 §5: Acceptance, Copyright Style

### 7.2 GPLv2 第5条：接受、版权风格

GPLv2 5 brings us to perhaps the most fundamental misconception and common confusion about GPLv2. Because of the prevalence of proprietary software, most users, programmers, and lawyers alike tend to be more familiar with EULAs. EULAs are believed by their authors to be contracts, requiring formal agreement between the licensee and the software distributor to be valid. This has led to mechanisms like "shrink-wrap" and "click-wrap" as mechanisms to perform acceptance ceremonies with EULAs.

GPLv2 5 可能是关于 GPLv2 最基本的误解和常见混淆。由于专有软件的普及，大多数用户、程序员和律师都更熟悉使用许可协议（EULA）。 EULA 的作者认为它们是合同，需要许可人和软件分发商之间的正式协议才能有效。这导致了"缩小包装"和"点击包装"等机制来执行 EULA 的接受仪式。

The GPL does not need contract law to "transfer rights." Usually, no rights are transferred between parties. By contrast, the GPL is primarily a permission slip to undertake activities that would otherwise have been prohibited by copyright law. As such, GPL needs no acceptance ceremony; the licensee is not even required to accept the license.

GPLv2 5 可能是关于 GPLv2 最基本的误解和常见混淆。由于专有软件的普及，大多数用户、程序员和律师都更熟悉使用许可协议（EULA）。 EULA 的作者认为它们是合同，需要许可人和软件分发商之间的正式协议才能有效。这导致了"缩小包装"和"点击包装"等机制来执行 EULA 的接受仪式。

However, without the GPL, the activities of copying, modifying and distributing the software would have otherwise been prohibited. So, the GPL says that you only accepted the license by undertaking activities that you would have otherwise been prohibited without your license under GPL. This is a certainly subtle point, and requires a mindset quite different from the contractual approach taken by EULA authors.

然而，如果没有 GPL，复制、修改和分发软件的活动本来是被禁止的。因此，GPL 表示，只有在进行原本在没有 GPL 许可下被禁止的活动时，你才接受了许可证。这是一个非常微妙的点，需要一种与 EULA 作者采取的合同方法截然不同的思维方式。

An interesting side benefit to GPLv2 5 is that the bulk of users of Free Software are not required to accept the license. Undertaking fair and unregulated use of the work, for example, does not bind you to the GPL, since you are not engaging in activity that is otherwise controlled by copyright law. Only when you engage in those activities that might have an impact on the freedom of others does license acceptance occur, and the terms begin to bind you to fair and equitable sharing of the software. In other words, the GPL only kicks in when it needs to for the sake of freedom.

GPLv2 5 的一个有趣的附带好处是，大部分自由软件的用户不需要接受许可证。例如，进行公正和不受限制的作品使用不会约束您使用 GPL，因为您并没有从事受版权法控制的活动。只有当您从事可能会影响他人自由的活动时，许可证才会生效，并开始将您与软件的公平和公正共享的条款绑定在一起。换句话说，GPL 只会在需要自由的情况下启动。

While GPL is by default a copyright license, it is certainly still possible to consider GPL as a contract as well. For example, some distributors chose to "wrap" their software in an acceptance ceremony to the GPL, and nothing in the GPL prohibits that use. Furthermore, the ruling in *Jacobsen v. Katzer, 535 F.3d 1373, 1380 (Fed.Cir.2008)* indicates that **both** copyright and contractual remedies may be sought by a copyright holder seeking to enforce a license designed to uphold software freedom.

虽然 GPL 默认是一个版权许可证，但当然仍然可以将 GPL 视为合同。例如，一些发行商选择在 GPL 接受仪式中"包装"他们的软件，而 GPL 中没有禁止这种用法。此外，在 Jacobsen v. Katzer, 535 F.3d 1373, 1380 (Fed.Cir.2008) 的裁决中表明，寻求执行旨在维护软件自由的许可证的版权持有人可以同时寻求版权和合同救济措施。

### 7.3 GPLv2 §6: GPL, My One and Only

### 7.3 GPLv2 第6条: GPL，唯一的版权许可证

A point that was glossed over in Section [7.1's](#gplv2-4-termination-on-violation) discussion of GPLv2 4 was the irrevocable nature of the GPL. The GPLv2 is indeed irrevocable, and it is made so formally by GPLv2 6.

在第7.1节讨论GPLv2 4时忽略了一个重要的问题，那就是GPLv2的不可撤销性。GPLv2确实是不可撤销的，GPLv2 6正式规定了这一点。

The first sentence in GPLv2 6 ensures that as software propagates down the distribution chain, that each licensor can pass along the license to each new licensee. Under GPLv2 6, the act of distributing automatically grants a license from the original licensor to the next recipient. This creates a chain of grants that ensure that everyone in the distribution has rights under the GPLv2. In a mathematical sense, this bounds the bottom --- making sure that future licensees get no fewer rights than the licensee before.

GPLv2 6的第一句确保了在软件沿着分发链传播时，每个许可人都可以将许可证传递给每个新的许可人。根据GPLv2 6，分发的行为自动授予原始许可人到下一个收件人的许可证。这创造了一系列的许可授权，确保分发中的每个人都在GPLv2下享有权利。从数学上讲，这将底部限制在一定范围内，确保未来的许可人得到的权利不少于前一个许可人。

The second sentence of GPLv2 6 does the opposite; it bounds from the top. It prohibits any licensor along the distribution chain from placing additional restrictions on the user. In other words, no additional requirements may trump the rights and freedoms given by GPLv2.

GPLv2 6的第二句则相反，它从顶部限制。它禁止沿着分发链的任何许可人对用户施加额外的限制。换句话说，没有额外的要求可以凌驾于GPLv2所赋予的权利和自由之上。

The final sentence of GPLv2 6 makes it abundantly clear that no individual entity in the distribution chain is responsible for the compliance of any other. This is particularly important for noncommercial users who have passed along a source offer under GPLv2 3(c), as they cannot be assured that the issuer of the offer will honor their GPLv2 3 obligations.

GPLv2 6的最后一句明确表示，在分发链中，没有任何个人实体对其他人的合规性负责。这对于已根据GPLv2 3(c)传递源代码的非商业用户尤其重要，因为他们无法确保发出源代码的人会履行他们GPLv2 3的义务。

In short, GPLv2 6 says that your license for the software is your one and only copyright license allowing you to copy, modify and distribute the software.

简而言之，GPLv2 6表示，该软件的许可证是您唯一的版权许可证，允许您复制、修改和分发该软件。

GPLv2 §6 is GPLv2's "automatic down stream licensing" provision[^7-2^]. Each time you redistribute a GPL'd program, the recipient automatically receives a license from each original licensor to copy, distribute or mod- ify the program subject to the conditions of the license. The redistributor need not take any to ensure the downstream recipient's acceptance of the license terms. This places every copyright holder in the chain of descent of the code in legal privity, or direct relationship, with every downstream redistributor. Two legal effects follow. First, downstream parties who remain in compliance have valid permissions for all actions (including modification and redistribution) even if their immediate upstream supplier of the software has been terminated for license violation[^7-3^]. Downstream's licensed rights are not dependent on compliance of their upstream, because their licenses issue directly from the copyright holder. Second, automatic termi- nation cannot be cured by obtaining additional copies from an alternate supplier: the license permissions emanate only from the original licensors, and if they have automatically terminated permission, no act by any intermediate license holder can restore those terminated rights[^7-4^].

GPLv2 §6是GPLv2的“自动下游许可证”条款[^7-2^]。每次您重新分发GPL授权的程序，接收方都会自动从每个原始许可证人那里获得许可证，以复制、分发或修改程序，但须遵守许可证的条件。再分发者无需采取任何措施来确保下游接收方接受许可证条款。这将每个代码下降链中的版权持有人置于法律特权或直接关系中，与每个下游再分发者有关。随之而来的是两个法律效果。首先，保持合规的下游方对于所有行为（包括修改和再分发），即使他们的软件直接上游供应商已因许可证违规而被终止，也具有有效的权限[^7-3^]。下游方的许可权不依赖于上游的合规性，因为他们的许可证直接来自版权持有人。其次，自动终止无法通过从备用供应商获取其他副本来解决：许可证权限仅来自原始许可证人，如果他们已自动终止许可证，则任何中间许可证持有人的行为都无法恢复已终止的权利[^7-4^]。

[^7-2^]: This section was substantially expanded for clarity and detail in [GPLv3 *§*10.](#gplv3-10-explicit-downstream-license)

[^7-2^]: 这个章节在 GPLv3 §10 中得到了大幅扩展，以增加其清晰度和详细程度。

### 7.4 GPLv2 Irrevocability

### 7.4 GPLv2的不可撤销性

This section digresses briefly to examine the manner in which GPLv2 4--6 interact together to assure that the license grant is irrevocable. There are two legal theories why a contributor cannot terminate their license grant. First is an argument that the text of the GPL prevents it; second is that a contributor would be estopped from succeeding on an infringement claim for continued use of the code even if it wasn't removed.

这个章节简要地讨论了GPLv2 4-6是如何相互作用以确保许可证授权是不可撤销的。有两种法律理论可以解释为什么贡献者不能终止他们的许可证授权。第一个是GPL的文本阻止了它的发生，第二个是即使代码没有被删除，贡献者也无法成功地主张侵权。

#### 7.4.1 The text of the GPLv2

#### 7.4.1 GPLv2的文本

The GPLv2 have several provisions that, when taken together, can be construed as an irrevocable license from each contributor. First, the GPLv2 says "by *modifying* or distributing the Program (or any work based on the Program), you indicate your acceptance of this License to do so, and all its terms and conditions for copying, distributing or modifying the Program or works based on it" (GPLv2 5, emphasis added). A contributor by definition is modifying the code and therefore has agreed to all the terms in the GPLv2, which includes the web of mechanisms in the GPLv2 that ensure the code can be used by all.

GPLv2有几个规定，当它们放在一起时，可以被解释为每个贡献者提供了一个不可撤销的许可证。首先，GPLv2说，“通过修改或分发程序（或任何基于程序的工作），您表明接受本许可证以进行此类操作，以及为复制，分发或修改程序或基于它的工作的所有条款和条件”（GPLv2 5，重点强调）。按照定义，贡献者正在修改代码，因此同意了GPLv2中的所有条款，包括GPLv2中保证代码可以被所有人使用的机制。

More specifically, the downstream license grant says "the recipient automatically receives a license from the original licensor to copy, distribute or modify the Program subject to these terms and conditions." (GPLv2 6). So in this step, the contributor has granted a license to the downstream, on the condition that the downstream complies with the license terms.

更具体地说，下游许可证授权说，“接收者自动从原始许可人那里获得许可证，以便根据这些条款和条件复制，分发或修改程序。”（GPLv2 6）。因此，在这一步中，贡献者已经授予了下游许可证，条件是下游用户遵守许可证条款。

That license granted to downstream is irrevocable, again provided that the downstream user complies with the license terms: "\[P\]arties who have received copies, or rights, from you under this License will not have their licenses terminated so long as such parties remain in full compliance" (GPLv2 4).

只要下游用户遵守许可证条款，向下游授予的许可证是不可撤销的：“只要这样的各方保持完全符合要求，从您处接收副本或权利的各方不会使其许可证终止”（GPLv2 4）。

Thus, anyone downstream of the contributor (which is anyone using the contributor's code), has an irrevocable license from the contributor. A contributor may claim to revoke their grant, and subsequently sue for copyright infringement, but a court would likely find the revocation was ineffective and the downstream user had a valid license defense to a claim of infringement.

因此，贡献者的任何下游方（也就是使用贡献者代码的任何人）都有一个不可撤销的许可证。贡献者可能声称撤回他们的授权，并随后对版权侵权提起诉讼，但法院很可能会发现撤销是无效的，下游用户有一个有效的许可证辩护权来反驳侵权指控。

Nevertheless, for purposes of argument, we will assume that for some reason the GPLv2 is not enforceable against the contributor[^7-5^], or that the irrevocable license can be revoked[^7-6^]. In that case, the application of promissory estoppel will likely mean that the contributor still cannot enforce their copyright against downstream users.

尽管如此，为了论证的目的，我们将假设某种原因导致 GPLv2 对贡献者不可执行[^7-5^]，或者可撤销的不可撤销许可证[^7-6^]。在这种情况下，承诺诱导可能意味着贡献者仍然无法对下游用户执行其版权。

[^7-3^]: While this is legally true, as a practical matter, a failure of "complete, corresponding source" (CCS) provisioning by an upstream could make it effectively impossible for a downstream party to engage in a commercial redistribution pursuant to []{#_bookmark78 .anchor}[GPLv2 3(a--b).](#gplv2-3-producing-binaries) ( [18.2](#upstream-providers) in the Compliance Guide portion of this tutorial discussed related details.)

[^7-3^]: 虽然这在法律上是正确的，但实际上，上游方未能完全提供“完整、对应的源代码”(CCS)可能会使下游方在遵循GPLv2 3(a-b)（本教程中合规指南部分的18.2部分讨论了相关细节）的商业再分发方面变得实际上不可能。

[^7-4^]: While nearly all attorneys and copyleft theorists are in agreement on this point, German copyleft legal expert [Till Jaeger](http://www.jbb.de/en/attorneys/till-jaeger/) vehemently disagrees. Jaeger's position is as follows: under German copyright law, a new copy of GPL'd software is a "fresh" license under GPL, and if compliance continues from that point further, the violator's permissions under copyright law are automatically restored, notwithstanding the strict termination provision in [GPLv2 4.](#gplv2-4-termination-on-violation) However, in practice, this issue is only salient with regard to [proprietary relicensing](#business-models) business models, since other copyright holders typically formally restore distributions rights once the only remaining compliance issue is "you lost copyright permission due to GPLv2 4". Therefore, the heated debates, which have raged between Jaeger and almost everyone else in the copyleft community for nearly a decade, []{#_bookmark79 .anchor}regard an almost moot and wholly esoteric legal detail.

[^7-4^]: 尽管几乎所有律师和共左派理论家都在这个观点上达成了一致，但德国共左派法律专家Till Jaeger强烈反对。Jaeger的观点如下：根据德国版权法，GPL软件的新副本是GPL下的“新”许可证，如果继续进行合规性，则侵权者根据版权法的许可将自动恢复，尽管在GPLv2 4。的严格终止规定下，这一观点在几乎所有共左派社区的Jaeger之间已经争论了将近十年的时间。然而，在实践中，这个问题只涉及专有重新许可业务模型，因为其他版权持有人通常会在唯一剩下的合规问题是“由于GPLv2 4而丧失版权许可”时正式恢复分发权利。因此，这些激烈的辩论几乎成为了一个不重要和完全偏僻的法律细节。

[^7-5^]: For example, the argument has been made that there may be a failure of consideration on the part of the contributor. While *Jacobsen v. Katzer*, 535 F.3d 1373 (Fed. Cir. 2008) is accepted as holding that there is consideration received by the contributor in a FOSS license, the posture of the case was one where the contributor advocated for the theory, not against it. The author is not aware of any other decisions that have analyzed the question in any depth, so it perhaps could be challenged in []{#_bookmark80 .anchor}the right factual situation.

[^7-5^]: 例如，人们曾经提出过这样的论点，即贡献者可能存在对价不足的问题。尽管Jacobsen v. Katzer，535 F.3d 1373（Fed。Cir.2008）被认为是支持FOSS许可证中的贡献者接受了对价的理论，但该案的状态是贡献者支持该理论，而不是反对该理论。作者不知道是否有其他决定对这个问题进行了深入的分析，因此在适当的情况下，它可能会受到挑战。

[^7-6^]: A contract without a definable duration can be terminated on reasonable notice. *Great W. Distillery Prod. v. John A.*

[^7-6^]: 没有明确定义的期限的合同可以在合理通知期内终止。Great W. Distillery Prod. v. John A.

#### 7.4.2 Promissory estoppel

#### 7.4.2 承诺阻止

"Promissory estoppel" is a legal theory that says, under some circumstances, a promise is enforceable against the promisee even after the promisee tries to renege on the promise. The test for how and when promissory estoppel applies differs from state to state, but generally where there is a "promise which the promisor should reasonably expect to induce action or forbearance on the part of the promisee or a third person and which does induce such action or forbearance is binding if injustice can be avoided only by enforcement of the promise."[^7-7^] Breaking it down, it is:

“承诺阻止”是一种法律理论，根据某些情况，即使承诺人试图食言，承诺也可以对承诺人生效。如何和何时应用承诺阻止的测试因州而异，但通常情况下，如果有“承诺能够合理预期促使承诺人或第三方采取行动或放弃采取行动的承诺，并且该承诺确实促使了这种行动或放弃采取行动，如果只有通过执行该承诺才能避免不公正，那么该承诺是具有约束力的。”[^7-7^] 将其分解为以下几点：

1. where there is a clear and definite promise;

2. where the promisor has a reasonable expectation that the offer will induce action or forbearance on the part of the promisee;

3. which does induce actual and reasonable action or forbearance by the promisee; and

4. which causes a detriment which can only be avoided by the enforcement of the promise.

1. 存在明确和明确的承诺；
2. 承诺人有合理的期望，即提供将促使承诺人采取行动或放弃采取行动；
3. 确实促使承诺人采取了实际和合理的行动或放弃采取行动；以及
4. 引起只有通过执行承诺才能避免的不利影响。

In this case, the promisor is the contributor. This should be an easy standard to meet in any widely used software.

在这种情况下，承诺人是贡献者。在任何广泛使用的软件中，这应该是一个容易实现的标准。

1. The promise is contained in the GPL, which is a promise that one can continue to use the licensed software as long as the terms of the license are met.

2. A contributor knows that there is a broad user base and users consume the software relying on the grant in the GPL as assuring their continued ability to use the software (one might even say it is the *sine qua non* of the intent of the GPL).

3. Users do, in fact, rely on the promises in the GPL, as they ingest the software and base their businesses on their continued ability to use the software.

4. Whether the user will suffer detriment is case-specific, but using Linux, a software program that is often fundamental to the operation of a business, as an example, the loss of its use would have a significantly detrimental, perhaps even fatal, effect on the continued operation of the business.

1. 承诺包含在GPL中，它承诺只要符合许可证条款，就可以继续使用许可的软件。
2. 贡献者知道有广泛的用户群，用户使用许可证中的授权来保证他们继续使用软件（可以说这是GPL意图的不可或缺的组成部分）。
3. 用户确实依赖GPL中的承诺，因为他们使用该软件，并基于其继续使用该软件来进行业务。
4. 用户是否会遭受损失是具体情况而定，但以Linux为例，这是一种通常对企业运作至关重要的软件程序，其使用的丧失将对企业的持续运营产生显着的，甚至是致命的影响。

#### 7.4.3 Conclusion

#### 7.4.3 结论

Whether as a matter of a straightforward contractual obligation, or as a matter of promissory estoppel, a contributor's attempt to revoke a copyright license grant and then enforce their copyright against a user is highly unlikely to succeed.

无论作为明确的合同义务，还是作为承诺阻止的事项，贡献者试图撤销版权许可授权，然后对用户执行其版权的行为极不可能成功。

### 7.5 GPLv2 §7: "Give Software Liberty or Give It Death!"

### 7.5 GPLv2 第7条：“给软件自由或给它死亡！”

In essence, GPLv2 7 is a verbosely worded way of saying for non-copyright systems what GPLv2 6 says for copyright. If there exists any reason that a distributor knows of that would prohibit later licensees from exercising their full rights under GPL, then distribution is prohibited.

实质上，GPLv2 7是一种措辞繁琐的表述方式，用于针对非版权系统，表达GPLv2 6对版权所说的意思。如果存在任何一个分发者知道会禁止后续许可人行使其在GPL下的全部权利的原因，那么就禁止分发。

Originally, this was designed as the title of this section suggests --- as a last ditch effort to make sure that freedom was upheld. However, in modern times, it has come to give much more. Now that the body of GPL'd software is so large, patent holders who would want to be distributors of GPL'd software have a tough choice. They must choose between avoiding distribution of GPL'd software that exercises the teachings of their patents, or grant a royalty-free, irrevocable, non-exclusive license to those patents. Many companies have chosen the latter.

最初，这是设计成本节标题所示的——作为确保自由得到维护的最后努力。然而，在现代，它给予了更多的意义。现在，由于GPL软件库如此庞大，想要成为GPL软件的分发者的专利持有人面临艰难的选择。他们必须在避免分发行使其专利教导的GPL软件和授予这些专利的免费，不可撤销，非独占许可之间做出选择。许多公司选择了后者。

*Wathen Distillery Co.*, 10 Cal. 2d 442, 447, 74 P.2d 745, 747 (1937). The term nevertheless can be a term of indefinite length []{#_bookmark84 .anchor}where its continuing effect is tied to the conduct of the parties. *Id*.

Wathen Distillery Co.，10 Cal. 2d 442, 447, 74 P.2d 745, 747 (1937)。然而，这个术语可以是一个无限期限的术语，其持续影响与各方的行为有关。Id。

[^7-7^]: *Kajima/Ray Wilson v. Los Angeles Cty. Metro. Transp. Auth.*, 23 Cal. 4th 305, 310, 1 P.3d 63, 66 (2000), *citing* Restatement (Second) of Contracts *§*90(1) (1979).

[^7-7^]: Kajima/Ray Wilson v. Los Angeles Cty. Metro. Transp. Auth.，23 Cal. 4th 305, 310, 1 P.3d 63, 66 (2000)，援引1979年《合同第二编》第90条第1款。

Thus, GPLv2 7 rarely gives software death by stopping its distribution. Instead, it is inspiring patent holders to share their patents in the same freedom-defending way that they share their copyrighted works.

因此，GPLv2 7很少会通过停止软件分发来导致软件的死亡。相反，它鼓励专利持有人以维护自由的方式分享他们的专利，就像他们分享版权作品一样。

### 7.6 GPLv2 §8: Excluding Problematic Jurisdictions

### 7.6 GPLv2 第8条: 排除问题管辖区

GPLv2 8 is rarely used by copyright holders. Its intention is that if a particular country, say Unfreedonia, grants particular patents or allows copyrighted interfaces (no country to our knowledge even permits those yet), that the GPLv2'd software can continue in free and unabated distribution in the countries where such controls do not exist.

GPLv2 8很少被版权持有人使用。它的意图是，如果某个国家，比如Unfreedonia，授予特定的专利或允许版权接口（目前没有任何国家允许这些），那么GPLv2软件可以在这些管辖区不存在这些控制的国家中自由、无障碍地分发。

As far as is currently known, GPLv2 8 has very rarely been formally used by copyright holders. Ad- mittedly, some have used GPLv2 8 to explain various odd special topics of distribution (usually related in some way to GPLv2 7). However, generally speaking, this section is not proven particularly useful in the more than two decades of GPLv2 history.

据目前所知，GPLv2 8很少被版权持有人正式使用。诚然，有些人使用GPLv2 8来解释分发的各种奇怪特殊话题（通常与GPLv2 7有关）。然而，一般来说，这个部分在GPLv2的二十多年历史中并没有被证明特别有用。

Meanwhile, despite many calls by the FSF (and others) for those licensors who explicitly use this section to come forward and explain their reasoning, no one ever did. Furthermore, research conducted during the GPLv3 drafting process found exactly one licensor who had invoked this section to add an explicit geographical distribution limitation, and the reasoning for that one invocation was not fitting with FSF's intended spirit of GPLv2 *§*8. As such, GPLv2 *§*8 was not included at all in GPLv3.

与此同时，尽管自由软件基金会（FSF）和其他人多次呼吁那些明确使用此部分的许可方来说明他们的理由，但没有人这样做。此外，在GPLv3起草过程中进行的研究发现，只有一个许可方曾引用此部分以添加明确的地理分布限制，而该引用的理由与FSF旨在实现的GPLv2 §8的精神不符。因此，GPLv2 §8在GPLv3中根本没有被包含进来。


## CHAPTER 8 ODDS, ENDS, AND ABSOLUTELY NO WARRANTY

## 第8章 杂项，保证和绝对无保证

GPLv2 0--7 constitute the freedom-defending terms of the GPLv2. The remainder of the GPLv2 handles administrivia and issues concerning warranties and liability.

GPLv2 0-7条款构成GPLv2的捍卫自由条款。GPLv2的其余部分处理行政事务和与保证和责任有关的问题。

### 8.1 GPLv2 §9: FSF as Stewards of GPL

### 8.1 GPLv2 第9条: FSF作为GPL的监管者

FSF reserves the exclusive right to publish future versions of the GPL; GPLv2 9 expresses this. While the stewardship of the copyrights on the body of GPL'd software around the world is shared among thousands of individuals and organizations, the license itself needs a single steward. Forking of the code is often regrettable but basically innocuous. Forking of licensing is disastrous.

FSF保留了发布GPL未来版本的独有权利; GPLv2 9表达了这一点。虽然全球GPL软件版权的管理权由数千个个人和组织共同分享，但许可证本身需要一个唯一的管理者。代码的分叉通常是令人遗憾但基本无害的。许可证的分叉是灾难性的。

(Chapter [2] discusses more about the various versions of GPL.)

（第2章更多地讨论了GPL的各个版本。）

### 8.2 GPLv2 §10: Relicensing Permitted

### 8.2 GPLv2 第10条: 允许重新许可

GPLv2 10 reminds the licensee of what is already implied by the nature of copyright law. Namely, the copyright holder of a particular software program has the prerogative to grant alternative agreements under separate copyright licenses.

GPLv2 10提醒许可证持有人，这已经隐含在版权法的性质中。即特定软件程序的版权持有人有权根据单独的版权许可证授予替代协议。

### 8.3 GPLv2 §11: No Warranty

### 8.3 GPLv2 第11条: 没有保证

Most warranty disclaimer language shouts at you. The [Uniform Commercial Code 2-316,](http://www.law.cornell.edu/ucc/2/2-316) which most of the USA's states and commonwealths have adopted as their local law, allows disclaimers of warranty, provided that the disclaimer is "conspicuous". There is apparently general acceptance that all caps is the preferred way to make something conspicuous, and that has over decades worked its way into the voodoo tradition of warranty disclaimer writing.

大多数保证免责声明语言都在大声喊叫。美国大部分州和自治领地采用的《统一商业法典》第2-316条款允许免责声明，前提是声明是“显著的”。显然有一般认同，全部字母大写是使某物显著的首选方式，这几十年已经成为保证免责声明书写的巫术传统。

That said, there is admittedly some authority under USA law suggesting that conspicuousness can be established by capitalization and is absent when a disclaimer has the same typeface as the terms surrounding it (see *Stevenson v. TRW, Inc.*, 987 F.2d 288, 296 (5th Cir. 1993)). While GPLv3's drafters doubted that such authority would apply to copyright licenses like the GPL, the FSF has nevertheless left warranty and related disclaimers in all caps throughout all versions of GPL.[^8-1^]

尽管如此，美国法律中确实存在一些权威机构认为，通过大写字母可以确定显著性，并且当免责声明与周围条款具有相同字体时，显著性就不存在（见Stevenson v. TRW, Inc.，987 F.2d 288, 296（第5巡回法庭，1993年））。虽然GPLv3的起草者怀疑此类权威将适用于像GPL这样的版权许可证，但FSF仍然在GPL的所有版本中将保证和相关免责声明保留为全部大写字母。[^8-1^]

[^8-1^]: One of the authors of this tutorial, Bradley M. Kuhn, has often suggested the aesthetically preferable compromise of a specifically designed "small caps" font, such as this one, as an alternative to WRITING IN ALL CAPS IN THE DEFAULT FONT (LIKE THIS), since the latter adds more ugliness than conspicuousness. Kuhn once engaged in reversion war with a lawyer who disagreed, but that lawyer never answered Kuhn's requests for case law that argues THIS IS INHERENTLY []{#_bookmark92 .anchor}MORE CONSPICUOUS Than this is.

[^8-1^]: 本教程的其中一位作者 Bradley M. Kuhn 经常建议使用专门设计的“小型大写字体”（例如此处所示的字体）作为使用默认字体中的全部大写（如此处）的替代方案，因为后者比前者更加丑陋而不显眼。Kuhn 曾与一位不同意他观点的律师进行过反转战，但该律师从未回应 Kuhn 要求提供证明“这种方式本质上更加显眼”的案例法律。

Critics have occasionally questioned GPL's enforceability in some jurisdictions because its disclaimer of warranties is impermissibly broad. However, critics have generally failed to articulate specific precedents in their jurisdictions that would directly indicate a problem with GPL's warranty disclaimer. Meanwhile, [Article](http://www.cisg.law.pace.edu/cisg/text/treaty.html#35) [35 of the United Nations Convention on Contracts for the International Sale of Goods](http://www.cisg.law.pace.edu/cisg/text/treaty.html#35) (often abbreviated "CISG", which [many countries have adopted)](https://treaties.un.org/Pages/ViewDetails.aspx?src=TREATY&id=228&chapter=10&lang=en) permits the disclaimer of warranties, so jurisdictions adopting this treaty allow some form of warranty disclaimer[^8-2^]. Nevertheless, to account for possible jurisdictional variances regarding this or any other issue, GPLv2 11 contains a jurisdictional savings provision, which states that it is to be interpreted only as broadly as allowed by applicable law. Such a provision ensures that both it, and the entire GPL, is enforceable in any jurisdiction, regardless of any particular law regarding the permissibility of certain warranty disclaimers.

批评者偶尔会质疑在某些司法管辖区内 GPL 的可执行性，因为其免责声明过于宽泛。然而，这些批评者通常未能明确阐述在其司法管辖区内存在直接指出 GPL 免责声明存在问题的具体先例。同时，联合国《国际货物销售合同公约》（常缩写为“CISG”）的第 35 条（许多国家已经采纳）允许免责声明，因此采用这个公约的司法管辖区允许某种形式的免责声明[^8-2^]。尽管如此，为了考虑到可能存在的司法管辖区异同，GPLv2 第 11 条包含了一个司法管辖区的节省规定，规定它只能按适用法律所允许的范围来解释。这样的规定确保了它及整个 GPL 在任何司法管辖区都是可执行的，而不受特定法律关于某些免责声明是否允许的影响。

Finally, one important point to remember when reading GPLv2 *§*11 is that GPLv2 *§*1 permits the sale of warranty as an additional service, which GPLv2 *§*11 affirms.

最后，在阅读 GPLv2 §11 时需要记住的一点是，GPLv2 §1 允许销售保修作为额外服务，而 GPLv2 §11 亦予以确认。

### 8.4 GPLv2 §12: Limitation of Liability

### 8.4 GPLv2 第12条：责任限制

There are many types of warranties, and in some jurisdictions some of them cannot be disclaimed. Therefore, usually agreements will have both a warranty disclaimer and a limitation of liability, as we have in GPLv2 12. GPLv2 11 thus gets rid of all implied warranties that can legally be disavowed. GPLv2 12, in turn, limits the liability of the actor for any warranties that cannot legally be disclaimed in a particular jurisdiction.

有许多类型的保证，在某些司法管辖区，其中一些保证可能无法否认。因此，通常协议会既有保证免责声明，也有责任限制，正如 GPLv2 12 所规定的那样。GPLv2 11 因此消除了可以在法律上否认的所有默示保证。而 GPLv2 12 则限制了在特定司法管辖区无法法律上否认的任何保证的责任。

Again, some have argued the GPL is unenforceable in some jurisdictions because its limitation of liability is impermissibly broad. However, 12, just like its sister, GPLv2 11, contains a jurisdictional savings provision, which states that it is to be interpreted only as broadly as allowed by applicable law. As stated above, such a provision ensures that both GPLv2 12, and the entire GPL, is enforceable in any jurisdiction, regardless of any particular law regarding the permissibility of limiting liability.

同样，一些人认为 GPL 在某些司法管辖区是不可执行的，因为其责任限制过于广泛。然而，GPLv2 12 就像其姐妹 GPLv2 11 一样，包含了司法管辖区救济条款，规定其只能按适用法律所允许的程度来解释。如上所述，这样的条款确保了 GPLv2 12 和整个 GPL 在任何司法管辖区都是可执行的，无论特定法律是否允许限制责任。

So end the terms and conditions of the GNU General Public License.

这就是 GNU 通用公共许可证的条款和条件。

[^8-2^]: Scholars continue to debate to what extent CISG applies to software licenses. For example, Diedrich concluded that "CISG is prima facie applicable to international transactions involving the transfer of computer software for a price", but Sono disagrees with this "prevailing view", presenting an "analysis \[that\] restricts the applicability of the CISG to software transactions by excluding 'license contracts"'. (See [Frank Diedrich, *The CISG and Computer Software Revisited*](http://www.cisg.law.pace.edu/cisg/biblio/diedrich1.html) , 6 Vindobona Journal of International Commercial Law and Arbitration, Supplement 55--75 (2002), and [Hiroo Sono, *The Applicability and*](http://www.cisg.law.pace.edu/cisg/biblio/sono6.html) [*Non-Applicability of the CISG to Software Transactions*](http://www.cisg.law.pace.edu/cisg/biblio/sono6.html), Camilla B. Andersen & Ulrich G. Schroeter eds., Sharing International Commercial Law across National Boundaries: Festschrift for Albert H. Kritzer on the Occasion of his Eightieth Birthday, Wildy, Simmonds & Hill Publishing (2008) 512--526.)

[^8-2^]: 学者们继续就 CISG 在软件许可证方面适用的程度进行辩论。例如，Diedrich 认为“CISG 明显适用于涉及计算机软件传输的国际交易，而且价格是其要素之一”，但 Sono 不同意这种“普遍观点”，提出了一种“分析，将 CISG 的适用范围限制在排除了许可合同的软件交易之外”（见 Frank Diedrich 的 The CISG and Computer Software Revisited，6 Vindobona Journal of International Commercial Law and Arbitration，Supplement 55--75（2002）和 Hiroo Sono 的 The Applicability and Non-Applicability of the CISG to Software Transactions，Camilla B. Andersen & Ulrich G. Schroeter eds.，Sharing International Commercial Law across National Boundaries: Festschrift for Albert H. Kritzer on the Occasion of his Eightieth Birthday，Wildy，Simmonds & Hill Publishing（2008）512--526）。

## CHAPTER 9 GPL VERSION 3

## 第9章 GPL 第3版

This chapter discusses the text of GPLv3. Much of this material herein includes text that was adapted (with permission) from text that FSF originally published as part of the so-called "rationale documents" for the various discussion drafts of GPLv3.

本章讨论GPLv3的文本。本文中的大部分材料是从FSF（经许可）最初作为各种讨论草案的所谓“基本原理文件”的部分文本编写。

The FSF ran a somewhat public process to develop GPLv3, and it was the first attempt of its kind to develop a Free Software license this way. Ultimately, RMS was the primary author of GPLv3, but he listened to feedback from all sorts of individuals and even for-profit companies. Nevertheless, in attempting to understand GPLv3 after the fact, the materials available from the GPLv3 process have a somewhat "drinking from the firehose" effect. This chapter seeks to explain GPLv3 to newcomers, who perhaps are familiar with GPLv2 and who did not participate in the GPLv3 process.

FSF运行了一个公开的开发GPLv3的流程，这是首次尝试开发自由软件许可证的方法。最终，RMS是GPLv3的主要作者，但是他听取了各种个人甚至是营利性公司的反馈。然而，试图在事后理解GPLv3，有点像“就着消防栓喝水”的感觉。本章旨在向可能熟悉GPLv2，而未参与过GPLv3流程的新手解释GPLv3。

Those who wish to drink from the firehose and take a diachronic approach to GPLv3 study by reading the step-by-step public drafting process of the GPLv3 (which occurred from Monday 16 January 2006 through Monday 19 November 2007) should visit <http://gplv3.fsf.org/>.

那些希望通过阅读GPLv3起草过程（从2006年1月16日星期一到2007年11月19日星期一）对GPLv3研究采取历时方法的人应该访问<http://gplv3.fsf.org>。

### Understanding GPLv3 As An Upgraded GPLv2

### 9.1 把GPLv3理解为GPLv2的升级版

Ultimately, GPLv2 and GPLv3 co-exist as active licenses in regular use. As discussed in Chapter [2](#_bookmark27) GPLv1 was never regularly used alongside GPLv2. However, given GPLv2's widespread popularity and existing longevity by the time GPLv3 was published, it is not surprising that some licensors still prefer GPLv2-only or GPLv2-or-later. GPLv3 gained major adoption by many projects, old and new, but many projects have not upgraded due to (in some cases) mere laziness and (in other cases) policy preference for some of GPLv2's terms and/or policy opposition to GPLv3's terms.

最终，GPLv2和GPLv3作为常规有效许可证共存。如第2章所述。GPL第1版从未与GPLv2一起常规使用。然而，鉴于GPLv2的广泛流行和GPLv3发布时的现有寿命，一些人许可人更喜欢采用仅GPLv2，或者，GPLv2或者后续版本就不足为奇了。

Given this "two GPLs world" is reality, it makes sense to consider GPLv3 in terms of how it differs from GPLv2. Also, most of the best GPL experts in the world must deal regularly with both licenses, and admittedly have decades of experience with GPLv2 while the most experience with GPLv3 that's possible is by definition less than a decade. These two factors usually cause even new students of GPL to start with GPLv2 and move on to GPLv3, and this tutorial follows that pattern.

鉴于这个“两个 GPL 世界”是现实，对 GPLv3 与 GPLv2 的区别来考虑它是有意义的。此外，世界上大多数最优秀的 GPL 专家必须定期处理这两个许可证，并且公认的是拥有数十年的 GPLv2 经验，理论上讲，最多的 GPLv3 经验可能不到10年。这两个因素通常甚至会导致 GPL 的新人不是从 GPLv2 开始，而是直接然后转向 GPLv3，本教程遵循这种模式。

Overall, the changes made in GPLv3 admittedly *increased* the complexity of the license. The FSF stated at the start of the GPLv3 process that they would have liked to oblige those who have asked for a simpler and shorter GPL. Ultimately, the FSF gave priority to making GPLv3 a better copyleft license in the spirit of past GPL's. Obsession for concision should never trump software freedom.

总的来说，GPLv3 中所做的更改无疑增加了许可证的复杂性。FSF 在 GPLv3 流程开始时表示，他们愿意帮助那些要求更简单、更短的 GPL 的人。最终，FSF 本着过去 GPL 的精神，优先考虑让 GPLv3 成为更好的 copyleft 许可证。对简洁的痴迷永远不应胜过软件自由。

The FSF had many different, important goals in seeking to upgrade to GPLv3. However, one important goal that is often lost in the discussion of policy minutia is a rather simple but important issue. Namely, FSF sought to assure that GPLv3 was more easily internationalized than GPLv2. In particular, the FSF sought to ease interpretation of GPL in other countries by replacement of USA-centric[^9-1] copyright phrases and wording with neutral terminology rooted in description of behavior rather than specific statute. As can be seen in the section-by-section discussion of GPLv3 that follows, nearly every section had changes related to issues of internationalization.

FSF 在寻求升级到 GPLv3 方面有许多不同的重要目标。然而，在讨论政策细枝末节时经常遗漏的一个重要目标是一个相当简单但重要的问题。那就是，FSF 试图确保 GPLv3 比 GPLv2 更容易国际化。特别是，FSF 试图通过替换以美国为中心的 [^9-1] 版权术语来简化其他国家/地区对 GPL 的解释。以及植根于行为描述而非特定法规的中性术语措辞。从接下来对 GPLv3 的逐节讨论中可以看出，几乎每一节都有与国际化问题相关的更改。

[^9-1]: See Section 1.2.4 of this tutorial for a brief discussion about non-USA copyright systems.

[^9-1]:有关非美国版权系统的简要讨论，请参阅本教程的第 1.2.4 节。

### GPLv3 §0: Giving In On "Defined Terms"

### 9.2 GPLv3 第0条：在“条款定义”上的让步

One of lawyers' most common complaints about GPLv2 is that defined terms in the document appear throughout. Most licenses define terms up-front. However, the GPL was always designed both as a document that should be easily understood both by lawyers and by software developers: it is a document designed to give freedom to software developers and users, and therefore it should be comprehensible to that constituency.

律师对 GPLv2 最常见的抱怨之一是文档中术语的定义贯穿始终。大多数许可证预先定义条款。然而，GPL 始终被设计成一个应该易于被律师和软件开发人员理解的文件：它是一个旨在为软件开发人员和用户提供自由的文件，因此它应该易于被这类用户所理解。

Interestingly enough, one coauthor of this tutorial who is both a lawyer and a developer pointed out that in law school, she understood defined terms more quickly than other law students precisely because of her programming background. For developers, having #define (in the C programming language) or other types of constants and/or macros that automatically expand in the place where they are used is second nature. As such, adding a defined terms section was not terribly problematic for developers, and thus GPLv3 adds one. Most of these defined terms are somewhat straightforward and bring forward better worded definitions from GPLv2. Herein, this tutorial discusses a few of the new ones.

有趣的是，本教程的一位合著者既是律师又是开发人员，她指出，在法学院，由于她的编程背景，她比其他法学院学生更快地理解术语的定义。对于开发人员来说，拥有 **#define** （在 C 编程语言中）或其他类型的常量和/或在使用它们的地方自动扩展的宏是第二天性。因此，添加一个术语的定义对开发人员来说并不是什么大问题，因此 GPLv3 也确实增加了新的定义。这些定义的术语中的大多数都有些直截了当，并从 GPLv2 中提出了更好的措辞定义。在此，本教程讨论的那些新增加的。

GPLv3 0 includes definitions of five new terms not found in any form in GPLv2: "modify" "covered work", "propagate", "convey", and "Appropriate Legal Notices".

GPLv3 第0条包括 GPLv2 中没有以任何形式出现的五个新术语的定义：“修改”、“涵盖的作品”、“传播”、“传达”和“适当的法律声明”。

#### Modify and the Work Based on the Program

#### 9.2.1 基于程序的修改和工作

GPLv2 included a defined term, "work based on the Program", but also used the term "modify" and "based on" throughout the license. GPLv2's "work based on the Program" definition made use of a legal term of art, "derivative work", which is peculiar to USA copyright law.[^9-2] GPLv2 always sought to cover all rights governed by relevant copyright law, in the USA and elsewhere. Even though differently-labeled concepts corresponding to the derivative work are recognized in all copyright law systems, these counterpart concepts might differ to some degree in scope and breadth from the USA derivative work. GPLv3 therefore internationalizes on this issue by removing GPLv2's references to derivative works and by providing a more globally useful definition. GPLv3 drops all reference to USA "derivative works" and returns to the base concept only: GPL covers the licensed work and all works where copyright permission from the licensed work's copyright holder.

GPLv2 包括一个术语“基于程序的作品”的定义，但在整个许可证中也使用了术语“修改”和“基于”。GPLv2 的“基于程序的作品”定义使用了美国版权法特有的艺术术语“衍生作品”[^9-2]。GPLv2 始终寻求涵盖美国相关版权法管辖的所有权利和其他地方。尽管与衍生作品相对应的不同标签概念在所有版权法体系中都得到认可，但这些对应概念可能在范围和广度上与美国衍生作品存在一定程度的差异。因此，GPLv3 通过删除 GPLv2 对衍生作品的引用并提供更具全球实用性的定义，使这个问题国际化。GPLv3 删除了所有对美国“衍生作品”的引用，并仅返回基本概念：GPL 涵盖许可作品和所有获得许可作品版权所有者版权许可的作品。

[^9-2]: Ironically, most criticism of USA-specific legal terminology in GPLv2’s “work based on the Program” definition historically came not primarily from readers outside the USA, but from those within it. The FSF noted in that it did not generally agree with these views, and expressed puzzlement by the energy with which they were expressed, given the existence of many other, more difficult legal issues implicated by the GPL. Nevertheless, the FSF argued that it made sense to eliminate usage of local copyright terminology to good effect.

[^9-2]:具有讽刺意味的是，在 GPLv2 的“基于程序的作品”定义中，对美国特定法律术语的大多数批评历史上主要不是来自美国以外的读者，而是来自美国境内的读者。FSF 指出，它一般不同意这些观点，并对表达这些观点的精力表示困惑，因为 GPL 涉及许多其他更困难的法律问题。尽管如此，FSF 认为，消除对本地版权术语的使用是有道理的。

The new definitions returns to the common elements of copyright law. Copyright holders of works of software have the exclusive right to form new works by modification of the original --- a right that may be expressed in various ways in different legal systems. GPLv3 operates to grant this right to successive generations of users (particularly through the copyleft conditions set forth in GPLv3 5, as described later in this tutorial in its [9.8).](#gplv3-5-modified-source) Here in GPLv3 0, "modify" refers to basic copyright rights, and then this definition of "modify" is used to define "modified version of" and "work based on" as synonyms.

新定义回归版权法的共同要素。软件作品的版权持有者拥有通过修改原件形成新作品的专有权——这种权利在不同的法律体系中可能以不同的方式表达。GPLv3 将此权利授予连续几代用户（特别是通过 GPLv3 第5条中规定的 copyleft 条件，如本教程后面的 9.8 中所述）。这里在 GPLv3 第0条中，“修改”指的是基本版权，然后这个“修改”的定义用来定义“修改版本”和“基于”的同义词。

#### The Covered Work

#### 9.2.2 涵盖的工作

GPLv3 uses a common license drafting technique of building upon simpler definitions to make complex ones. The Program is a defined term found throughout GPLv2, and the word "covered" and the phrase "covered by this license" are used in tandem with the Program in GPLv2, but not as part of a definition. GPLv3 offers a single term "covered work", which enables some of the wording in GPLv3 to be simpler and clearer than its GPLv2 counterparts.

GPLv3 使用一种通用的许可证起草技术，即在更简单的定义基础上构建复杂的定义。“本程序”是贯穿 GPLv2 的一个定义术语，“涵盖”一词和短语“受本许可证涵盖”在 GPLv2 中与“本程序”一起使用，但不作为定义的一部分。GPLv3 提供了一个单一的术语“涵盖的作品”，这使得 GPLv3 中的一些措辞比 GPLv2 对应的措辞更简单、更清晰。

Next, to avoid locking GPLv3 into specific copyright statues, the GPLv3 defines two terms that are otherwise exotic to the language of international copyright.

接下来，为了避免将 GPLv3 锁定在特定的版权法规中，GPLv3 定义了两个对国际版权语言来说陌生的术语。

#### Propagate

#### 9.2.3 传播

To "propagate" a work covered by the license means any activity in a locale that requires permission of copyright holders in that locale's legal system. However, personal use or modification for personal use are activities explicitly excluded from "propagation" *regardless* of domestic copyright law.

“传播”许可证涵盖的作品是指在该地区的法律体系中需要版权所有者许可的地区的任何活动。然而，无论国内版权法如何，个人使用或为个人使用而修改是明确排除在“传播”之外的活动。

The term "propagate" serves two purposes. First, "propagate" provides a simple and convenient means for distinguishing between the kinds of uses of a work that GPL imposes conditions on and the kinds of uses that GPL does not (for the most part) impose conditions on.

“传播”一词有两个目的。首先，“传播”提供了一种简单方便的方式来区分 GPL 施加条件的作品的使用类型和 GPL 不（在大多数情况下）施加条件的使用类型。

Second, "propagate" helps globalize GPL in its wording and effect: "derivative work" was in fact not the only term commonly used by local copyright statutes. A term like "distribute" (or its equivalent in languages other than English) is also used in several national copyright statutes. Practical experience with GPLv2 revealed the awkwardness of using the term "distribution" in a license intended for global use: the scope of "distribution" in the copyright context can differ from country to country. The GPL never necessarily intended the specific meaning of "distribution" that exists under USA (or any other country's) copyright law.

其次，“传播”有助于 GPL 在措辞和效果上的全球化：“衍生作品”实际上并不是当地版权法规常用的唯一术语。一些国家的版权法规中也使用了诸如“分发”（或英语以外的其他语言中的等效词）之类的术语。GPLv2 的实践经验揭示了在全球使用的许可证中使用术语“分发”的尴尬：版权上下文中的“分发”范围可能因国家/地区而异。GPL 未必意指美国（或任何其他国家/地区）版权法下存在的“分发”的特定含义。

Indeed, even within a single country and language, the term distribution may be ambiguous; as a legal term of art, distribution varies significantly in meaning among those countries that recognize it. For example, comments during GPLv3's drafting process indicated that in at least one country, distribution may not include network transfers of software but may include interdepartmental transfers of physical copies within an organization. Meanwhile, the copyright laws of many countries, as well as certain international copyright treaties, recognize "making available to the public" or "communication to the public" as one of the exclusive rights of copyright holders.

事实上，即使在单一的国家和语言中，术语分布也可能是模棱两可的； 作为一个法律术语，分配在承认它的国家之间的含义差异很大。例如，GPLv3 起草过程中的评论表明，至少在一个国家/地区，分发可能不包括软件的网络传输，但可能包括组织内物理副本的部门间传输。同时，许多国家的版权法以及某些国际版权条约都承认“向公众提供”或“向公众传播”是版权人的专有权利之一。

Therefore, the GPLv3 defines the term "propagate" by reference to activities that require permission un- der "applicable copyright law", but excludes execution and private modification from the definition. GPLv3's definition also gives examples of activities that may be included within "propagation" but it also makes clear that, under the copyright laws of a given country, "propagation" may include other activities as well.

因此，GPLv3 通过引用根据“适用版权法”需要许可的活动来定义术语“传播”，但从定义中排除了执行和私人修改。GPLv3 的定义还给出了可能包含在“传播”范围内的活动示例，但它也明确指出，根据特定国家/地区的版权法，“传播”也可能包括其他活动。

Thus, propagation is defined by behavior, and not by categories drawn from some particular national copyright statute. This helps not only with internationalization, but also factually-based terminology aids in developers' and users' understanding of the GPL.

因此，传播是由行为定义的，而不是由某些特定国家版权法规中的类别定义的。这不仅有助于国际化，而且基于事实的术语有助于开发人员和用户理解 GPL。

As a further benefit, because "propagation" includes all exclusive rights granted under any particular copyright regime, the term automatically accounts for all exclusive rights under that regime.

作为进一步的好处，因为“传播”包括任何特定版权制度下授予的所有专有权，该术语自动说明该制度下的所有专有权。

#### Convey

#### 9.2.4 传达

Next, GPLv3 defines a subset of propagate --- "convey". Conveying includes activities that constitute propagation of copies to others. As with the definition of propagate, GPLv3 thus addresses transfers of copies of software in behavioral rather than statutory terms. Any propagation that enables other parties to receive or make copies of the work, is called "conveying". Usually, conveying is the activity that triggers most of the other obligations of GPLv3.

接下来，GPLv3 定义了传播的一个子集——“传达”（convey）。传送包括构成向他人传播副本的活动。与传播的定义一样，GPLv3 因此以行为而非法定条款处理软件副本的传输。使其他方能够接收或复制作品的任何传播都称为“传送”。通常，传送是触发 GPLv3 的大部分其他义务的活动。

#### Appropriate Legal Notices

#### 9.2.5 适当的法律声明

GPLv2 used the term "appropriate copyright notice and disclaimer of warranty" in two places, which is a rather bulky term. Also, experience with GPLv2 and other licenses that grant software freedom showed throughout the 1990s that the scope of types of notices that need preservation upon conveyance were more broad that merely the copyright notices. The Appropriate Legal Notice definition consolidates the material that GPLv2 traditionally required preserved into one definition.

GPLv2 在两处使用了术语“适当的版权声明和免责声明”，这是一个相当庞大的术语。此外，GPLv2 和其他授予软件自由的许可的经验表明，在整个 1990 年代，需要在传输时保存的通知类型的范围比仅版权通知更广泛。适当的法律声明定义将 GPLv2 传统上要求保留的材料整合到一个定义中。

#### Other Defined Terms

#### 9.2.6 其他术语的定义

Note finally that not all defined terms in GPLv3 appear in GPLv3 0. Specifically, those defined terms that are confined in use to a single section are defined in the section in which they are used, and GPLv3 1 contains those definitions focused on source code. In this tutorial, those defined terms are discussed in the section where they are defined and/or used.

最后请注意，并不是所有 GPLv3 中定义的术语都出现在 GPLv3 第0条中。具体来说，那些被限制在单个部分中使用的定义术语在使用它们的部分中定义，而 GPLv3 条款一包含那些专注于源代码的定义。在本教程中，这些定义的术语将在定义和/或使用它们的部分进行讨论。

### GPLv3 §1: Understanding CCS

### 9.3 GPLv3 第1条：理解CCS

Ensuring that users have the source code to the software they receive and the freedom to modify remains the paramount right embodied in the Free Software Definition (found in [1.1](#the-free-software-definition) of this tutorial). As such, GPLv3 1 is likely one of the most important sections of GPLv3, as it contains all the defined terms related to this important software freedom.

确保用户拥有他们收到的软件的源代码和修改的自由仍然是自由软件定义（参见本教程的 1.1 ）中体现的首要权利。因此，GPLv3 条款一可能是 GPLv3 最重要的部分之一，因为它包含与这一重要软件自由相关的所有定义条款。

#### 9.3.1 Source Code Definition

#### 9.3.1 源代码的定义

First, GPLv3 1 retains GPLv2's definition of "source code" and adds an explicit definition of "object code" as "any non-source version of a work". Object code is not restricted to a narrow technical meaning and is understood broadly to include any form of the work other than the preferred form for making modifications to it. Object code therefore includes any kind of transformed version of source code, such as bytecode or minified Javascript. The definition of object code also ensures that licensees cannot escape their obligations under the GPL by resorting to shrouded source or obfuscated programming.

首先，GPLv3 条款一保留了 GPLv2 对“源代码”的定义，并将“目标代码”明确定义为“作品的任何非源版本”。目标代码并不局限于狭义的技术含义，而是广义地理解为包括除对其进行修改的首选形式之外的任何形式的作品。因此，目标代码包括任何类型的源代码转换版本，例如字节码或缩小的 Javascript。目标代码的定义还确保被许可人无法通过诉诸隐藏源代码或混淆编程来逃避 GPL 规定的义务。

#### 9.3.2 CCS Definition

#### 9.3.2 CCS的定义

The definition of CCS,[^9-3](#_bookmark107) or, as GPLv3 officially calls it, "Corresponding Source" in GPLv3 1 4 is possibly the most complex definition in the license.

CCS 的定义[^9-3]，或 GPLv3 官方称之为 GPLv3 条款一 4 中的“对应源”可能是许可证中最复杂的定义。

[^9-3]:Note that the preferred term for those who work regularly with both GPLv2 and GPLv3 is “Complete Corresponding Source”, abbreviated to “CCS”. Admittedly, the word “complete” no longer appears in GPLv3 (which uses the word “all” instead). However, both GPLv2 and the early drafts of GPLv3 itself used the word “complete”, and early GPLv3 drafts even called this defined term “Complete Corresponding Source”. Meanwhile, use of the acronym “CCS” (sometimes, “C&CS”) was so widespread among GPL enforcers that its use continues even though GPLv3-focused experts tend to say just the defined term of “Corresponding Source”.

[^9-3]: 请注意，经常使用 GPLv2 和 GPLv3 的人的首选术语是“Complete Corresponding Source”，缩写为“CCS”。诚然，“完整”一词不再出现在 GPLv3 中（它使用“全部”一词代替）。然而，GPLv2 和 GPLv3 的早期草案本身都使用了“完整”一词，而早期的 GPLv3 草案甚至将这一定义术语称为“完整对应源”。同时，首字母缩略词“CCS”（有时称为“C&CS”）在 GPL 执法者中的使用如此广泛，以至于即使专注于 GPLv3 的专家倾向于只说定义的术语“对应源”，它的使用仍在继续。

The CCS definition is broad so as to protect users' exercise of their rights under the GPL. The definition includes particular examples to remove any doubt that they are to be considered CCS. GPLv3 seeks to make it completely clear that a licensee cannot avoid complying with the requirements of the GPL by dynamically linking a subprogram component to the original version of a program. The examples also clarify that the shared libraries and dynamically linked subprograms that are included in Corresponding Source are those that the work is "specifically" designed to require, which clarifies that they do not include libraries invoked by the work that can be readily substituted by other existing implementations. While copyleft advocates never doubted this was required under GPLv2's definition of CCS, GPLv3 makes it abundantly clear with an extra example.

CCS 的定义很宽泛，以保护用户行使其在 GPL 下的权利。该定义包括特定示例，以消除对它们被视为 CCS 的任何疑问。GPLv3 力求完全清楚地表明，被许可人无法通过将子程序组件动态链接到程序的原始版本来避免遵守 GPL 的要求。这些示例还阐明了相应源代码中包含的共享库和动态链接的子程序是作品“专门”设计需要的那些，这阐明了它们不包括作品调用的库，这些库可以很容易地被其他人替换现有的实施。虽然 Copyleft 倡导者从不怀疑这是 GPLv2 对 CCS 的定义所要求的，但 GPLv3 通过一个额外的例子使其非常清楚。

The GPL, as always, seeks to ensure users are truly in a position to install and run their modified versions of the program; the CCS definition is designed to be expansive to ensure this software freedom. However, although the definition of CCS is expansive, it is not sufficient to protect users' freedoms in many circumstances. For example, a GPL'd program, or a modified version of such a program, might be locked- down and restricted. The requirements in GPLv3 6 (discussed in Section [9.9](#gplv3-6-non-source-and-corresponding-source) of this tutorial) handle that issue. (Early drafts of GPLv3 included those requirements in the definition of CCS; however, given that the lock-down issue only comes up in distribution of object code, it is more logical to place those requirements with the parts of GPLv3 dealing directly with object code distribution).

GPL 一如既往地寻求确保用户真正能够安装和运行他们修改后的程序版本； CCS 定义旨在扩展以确保这种软件自由。然而，尽管 CCS 的定义很广泛，但在许多情况下不足以保护用户的自由。例如，GPL 程序或此类程序的修改版本可能会被锁定和限制。GPLv3 条款六中的要求（在本教程的第 9.9 节中讨论）解决了这个问题。（GPLv3 的早期草案在 CCS 的定义中包含了这些要求；然而，鉴于锁定问题只出现在目标代码的分发中，将这些要求放在 GPLv3 直接处理目标代码的部分中更为合乎逻辑分配）。

The penultimate paragraph in GPLv3 2 notes that GPLv3's CCS definition does not require source that can be automatically generated. Many code generators, preprocessors and take source code as input and sometimes even have output that is still source code. Source code should always be whatever the original programmer preferred to modify.

GPLv3 第2条中的倒数第二段指出 GPLv3 的 CCS 定义不需要可以自动生成的源。许多代码生成器、预处理器和将源代码作为输入，有时甚至输出仍然是源代码。源代码应该始终是原始程序员喜欢修改的任何内容。

GPLv3 1's final paragraph removes any ambiguity about what should be done on source-only distribu- tions. Specifically, the right to convey source code that does not compile, does not work, or otherwise is experimental in-progress work is fully permitted, *provided that* no object code form is conveyed as well. Indeed, when combined with the permissions in GPLv3 5, it is clear that if one conveys *only* source code, one can never be required to provide more than that. One always has the right to modify a source code work by deleting any part of it, and there can be no requirement that free software source code be a whole functioning program.

GPLv3 条款一的最后一段消除了关于应该在纯源代码发行版上做什么的任何歧义。具体而言，完全允许传输未编译、无法运行或处于实验性进行中工作的源代码的权利，前提是不传输任何目标代码形式。事实上，当结合 GPLv3 第5条中的许可时，很明显，如果一个人只传达源代码，就永远不会被要求提供更多。人们始终有权通过删除源代码作品的任何部分来修改源代码作品，并且可以不要求自由软件源代码是一个完整的功能程序。

#### 9.3.3 The System Library Exception

#### 9.3.3 系统库例外

The previous section skipped over one part of the CCS definition, the so-called system library exception. The "System Libraries" definition (and the "Standard Interface" and "Major Component" definitions, which it includes) are designed to permit certain distribution arrangements that are considered reasonable by copyleft advocates. The system library exception is designed to allow copylefted software to link with these libraries when prohibition of that linking would hurt software freedom more than it would hurt proprietary software. The system library exception has two parts. Part (a) rewords the GPLv2 exception for clarity replacing GPLv2's words "unless that component itself accompanies the executable" with "which is not part of the Major Component". The goal here is to not require disclosure of source code of certain libraries, such as necessary Microsoft Windows DLLs (which aren't part of Windows' kernel but accompany it) that are required for functioning of copylefted programs compiled for Windows.

上一节跳过了 CCS 定义的一部分，即所谓的系统库异常。“系统库”定义（以及其中包含的“标准接口”和“主要组件”定义）旨在允许 copyleft 倡导者认为合理的某些分发安排。系统库例外旨在允许 copylefted 软件与这些库链接，而禁止该链接对软件自由的伤害大于对专有软件的伤害。系统库异常有两部分。(a) 部分重写了 GPLv2 例外，以清楚地将 GPLv2 的措辞“除非该组件本身伴随可执行文件”替换为“它不是主要组件的一部分”。这里的目标是不要求公开某些库的源代码，例如必要的 Microsoft Windows DLL（它们不是 Windows 内核的一部分，但伴随它）是为 Windows 编译的 copylefted 程序运行所必需的。

However, in isolation, (a) would be too permissive, as it would sometimes allow distributors to evade important GPL requirements. Part (b) reigns in (a). Specifically, (b) specifies only a few functionalities that a system library may provide and still qualify for the exception. The goal is to ensure system libraries are truly adjunct to a major essential operating system component, compiler, or interpreter. The more low-level the functionality provided by the library, the more likely it is to be qualified for this exception.

但是，单独来看，(a) 过于宽容，因为它有时会允许发行商规避重要的 GPL 要求。(b) 部分优先于 (a) 部分。具体来说，(b) 仅指定了系统库可能提供的少数功能，并且仍然符合例外条件。目标是确保系统库真正附属于主要的基本操作系统组件、编译器或解释器。库提供的功能越低级，越有可能符合此异常。

Admittedly, the system library exception is a frequently discussed topic of obsessed GPL theorists. The amount that has been written on the system library exception (both the GPLv2 and GPLv3 versions of it), if included herein, could easily increase this section of the tutorial to a length greater than all the others.

诚然，系统库异常是痴迷于 GPL 的理论家经常讨论的话题。如果包含在系统库异常（它的 GPLv2 和 GPLv3 版本）上的数量，很容易将本教程的这一部分增加到比其他所有部分都长的长度。

Like any exception to the copyleft requirements of GPL, would-be GPL violators frequently look to the system library exception as a potential software freedom circumvention technique. When considering whether or not a library qualifies for the system library exception, here is a pragmatic thesis to consider, based on the combined decades of experience in GPL interpretation of this tutorial's authors: the harder and more strained the reader must study and read the system library exception, the more likely it is that the library in question does not qualify for it.

与 GPL 的 copyleft 要求的任何例外一样，潜在的 GPL 违反者经常将系统库例外视为潜在的软件自由规避技术。在考虑一个库是否符合系统库例外条件时，根据本教程作者数十年的 GPL 解释经验，这里有一个实用的论点需要考虑：读者必须越努力、越紧张地学习和阅读系统 library exception，有问题的图书馆越有可能不符合条件。

### GPLv3 §2: Basic Permissions

### 9.4 GPLv3 第2条：基本权利

GPLv3 2 can roughly be considered as an equivalent to GPLv2 0 (discussed in [3.1](#gplv2-0-freedom-to-run) of this tutorial). However, the usual style of improvements found in GPLv3 are found here as well. For example, the first sentence of GPLv3 2 furthers the goal internationalization. Under the copyright laws of some countries, it may be necessary for a copyright license to include an explicit provision setting forth the duration of the rights being granted. In other countries, including the USA, such a provision is unnecessary but permissible. GPLv3 2 1 also acknowledges that licensees under the GPL enjoy rights of copyright fair use, or the equivalent under applicable law. These rights are compatible with, and not in conflict with, the freedoms that the GPL seeks to protect, and the GPL cannot and should not restrict them.

GPLv3 条款可以粗略地视为等同于 GPLv2 第0条（在本教程的 3.1 中讨论）。但是，这里也可以找到 GPLv3 中常见的改进方式。例如，GPLv3 条款二的第一句进一步推进了目标国际化。根据某些国家/地区的版权法，版权许可可能需要包括明确规定授予权利的期限。在包括美国在内的其他国家，这样的规定是不必要的，但却是允许的。GPLv3 条款二第1项还承认 GPL 下的被许可人享有版权合理使用权或适用法律下的同等权利。这些权利与自由相容而不冲突GPL 寻求保护的内容，而 GPL 不能也不应该限制它们。

However, note that (sadly to some copyleft advocates) the unlimited freedom to run is confined to the *unmodified* Program. This confinement is unfortunately necessary since Programs that do not qualify as a User Product in GPLv3 6 (see [9.9.2](#user-products) in this tutorial) might have certain unfortunate restrictions on the freedom to run.[^9-4]

然而，请注意（对某些 copyleft 拥护者而言令人遗憾的是）无限的运行自由仅限于未修改的程序。不幸的是，这种限制是必要的，因为在 GPLv3 条款六中不符合用户产品资格的程序（请参阅本教程中的 9.9.2）可能对运行自由有某些不幸的限制[^9-4]。

[^9-4]:See § 1.1.1 of this tutorial for the details on “the freedom to run”.

[^9-4]: 详见本教程的§1.1.1“运行的自由”。

GPLv3 2 2 distinguishes between activities of a licensee that are permitted without limitation and activities that trigger additional requirements. Specifically, GPLv3 2 2 guarantees the basic freedoms of privately modifying and running the program. While these basic freedoms were generally considered a standard part of users' rights under GPLv2 as well, the GPLv3 states them herein more explicitly. In other words, there is no direct analog to the first sentence of GPLv3 2 2 in GPLv2 (See [5.1.3](#right-to-private-modification) of this tutorial for more on this issue.)

GPLv3 第2条第2款区分被许可人允许但不限于的活动和触发额外要求的活动。具体来说，GPLv3 第2条第2款保证了私下修改和运行程序的基本自由。虽然这些基本自由通常也被视为 GPLv2 下用户权利的标准部分，但 GPLv3 在此更明确地说明了它们。换句话说，在 GPLv2 中没有直接模拟 GPLv3 条款二第2项的第一句（有关此问题的更多信息，请参见本教程的 5.1.3。）

Also, GPLv3 2 2 gives an explicit permission for a client to provide a copy of its modified software to a contractor exclusively for that contractor to modify it further, or run it, on behalf of the client. However, the client can *only* exercise this control over its own copyrighted changes to the GPL-covered program. The parts of the program it obtained from other contributors must be provided to the contractor with the usual GPL freedoms. Thus, GPLv3 permits users to convey covered works to contractors operating exclusively on the users' behalf, under the users' direction and control, and to require the contractors to keep the users' copyrighted changes confidential, but *only if* the contractor is limited to acting on the users' behalf (just as the users' employees would have to act).

此外，GPLv3 第2条第2款明确允许客户向承包商提供其修改后软件的副本，专供承包商代表客户进一步修改或运行。但是，客户只能对其自己对受 GPL 保护的程序的版权更改行使此控制权。它从其他贡献者那里获得的程序部分必须以通常的 GPL 自由提供给承包商。因此，GPLv3 允许用户将涵盖的作品传送给专门在代表用户，在用户的指导和控制下，并要求承包商对用户的受版权保护的更改保密，但前提是承包商仅限于代表用户行事（就像用户的员工会行动）。

The strict conditions in this "contractors provision" are needed so that it cannot be twisted to fit other activities, such as making a program available to downstream users or customers. By making the limits on this provision very narrow, GPLv3 ensures that, in all other cases, contractor gets the full freedoms of the GPL that they deserve.

需要此“承包商条款”中的严格条件，以使其不能被扭曲以适应其他活动，例如向下游用户或客户提供程序。GPLv3 使这一条款的限制非常狭窄，确保在所有其他情况下，承包商获得他们应得的 GPL 的全部自由。

The FSF was specifically asked to add this "contractors provisions" by large enterprise users of Free Software, who often contract with non-employee developers, working offsite, to make modifications intended for the user's private or internal use, and often arrange with other companies to operate their data centers. Whether GPLv2 permits these activities is not clear and may depend on variations in copyright law in different jurisdictions. The practices seem basically harmless, so FSF decided to make it clear they are permitted.

FSF 被自由软件的大型企业用户特别要求添加这个“承包商规定”，他们经常与非雇员开发人员签订合同，在异地工作，进行修改供用户私人或内部使用，并经常与其他公司安排运营他们的数据中心。GPLv2 是否允许这些活动尚不清楚，可能取决于不同司法管辖区版权法的变化。这些做法基本上看起来是无害的，因此 FSF 决定明确表示它们是允许的。

GPLv3 2's final paragraph includes an explicit prohibition of sublicensing. This provision ensures that GPL enforcement is always by the copyright holder. Usually, sublicensing is regarded as a practical convenience or necessity for the licensee, to avoid having to negotiate a license with each licensor in a chain of distribution. The GPL solves this problem in another way --- through its automatic licensing provision found in GPLv3 *§*10 (which is discussed in more detail in *§* [9.13](#gplv3-10-explicit-downstream-license) of this tutorial).

GPLv3 第2条的最后一段明确禁止再许可。此条确保 GPL 强制执行始终由版权所有者执行。通常，再许可被认为是被许可人的实际便利或必要，以避免必须与分销链中的每个许可人协商许可。GPL 以另一种方式解决了这个问题——通过 GPLv3 第10条中的自动许可条款（在本教程的第 9.13 节中有更详细的讨论）。

### GPLv3's views on DRM and Device Lock-Down

### 9.5 GPLv3 对 DRM 和设备锁定的看法

The issues of DRM, device lock-down and encryption key disclosure were the most hotly debated during the GPLv3 process. FSF's views on this were sadly frequently misunderstood and, comparing the provisions related to these issues in the earliest drafts of GPLv3 to the final version of GPLv3 shows the FSF's willingness to compromise on tactical issues to reach the larger goal of software freedom.

DRM、设备锁定和加密密钥泄露等问题是 GPLv3 过程中争论最激烈的问题。遗憾的是，FSF 对此的看法经常被误解，将 GPLv3 最早草案中与这些问题相关的条款与 GPLv3 的最终版本进行比较，表明 FSF 愿意在战术问题上做出妥协，以实现更大的软件自由目标。

Specifically, GPLv3 introduced provisions that respond to the growing practice of distributing GPL- covered programs in devices that employ technical means to restrict users from installing and running modified versions. This practice thwarts the expectations of developers and users alike, because the right to modify is one of the core freedoms the GPL is designed to secure.

具体来说，GPLv3 引入了一些条款，以应对越来越多的在设备中分发 GPL 覆盖程序的做法，这些设备采用技术手段来限制用户安装和运行修改版本。这种做法违背了开发人员和用户的期望，因为修改权是 GPL 旨在保护的核心自由之一。

Technological measures to defeat users' rights. These measures are often described by such Orwellian phrases, such as "digital rights management," which actually means limitation or outright destruction of users' legal rights, or "trusted computing," which actually means selling people computers they cannot trust. However, these measures are alike in one basic respect. They all employ technical means to turn the system of copyright law (where the powers of the copyright holder are limited exceptions to general freedom) into a virtual prison, where everything not specifically permitted is utterly forbidden. This system of "para- copyright" was created well after GPLv2 was written --- initially through legislation in the USA and the EU, and later in other jurisdictions as well. This legislation creates serious civil or even criminal penalties to escape from these restrictions (commonly and aptly called "jail-breaking a device"), even where the purpose in doing so is to restore the users' legal rights that the technology wrongfully prevents them from exercising. GPLv2 did not address the use of technical measures to take back the rights that the GPL granted, because such measures did not exist in 1991, and would have been irrelevant to the forms in which software was then delivered to users. GPLv3 addresses these issues, particularly because copylefted software is ever more widely embedded in devices that impose technical limitations on the user's freedom to change it.

破坏用户权利的技术措施。这些措施通常用这样的奥威尔式短语来描述，例如“数字版权管理”实际上意味着限制或彻底破坏用户的合法权利，或者“可信计算”实际上意味着向人们出售他们不信任的计算机。然而，这些措施在一个基本方面是相似的。他们都采用技术手段将版权法体系（版权持有者的权力是一般自由的有限例外）变成虚拟监狱，凡是未明确允许的事情都被完全禁止。这种“副版权”系统是在编写 GPLv2 之后很久就创建的——最初是通过美国和欧盟的立法，后来也通过其他司法管辖区的立法。该立法规定了严重的民事甚至刑事处罚以逃避这些限制（通常被恰当地称为“越狱设备”），即使这样做的目的是恢复用户的合法权利，而该技术错误地阻止了他们使用。GPLv2 没有解决使用技术措施收回 GPL 授予的权利的问题，因为这些措施在 1991 年不存在，并且与当时向用户交付软件的形式无关。GPLv3 解决了这些问题，特别是因为 copylefted 软件永远是更广泛地嵌入到对用户更改它的自由施加技术限制的设备中。

However, FSF always made a clear distinction to avoid conflating these "lock-down" measures with legitimate applications that give users control, as by enabling them to choose higher levels of system or data security within their networks, or by allowing them to protect the security of their communications using keys they can generate or copy to other devices for sending or receiving messages. Such technologies present no obstacles to software freedom and the goals of copyleft.

然而，FSF 始终明确区分以避免将这些“锁定”措施与赋予用户控制权的合法应用程序混为一谈，例如通过使他们能够在其网络中选择更高级别的系统或数据安全，或通过允许他们保护使用他们可以生成或复制到其他设备以发送或接收消息的密钥来确保他们的通信安全。这些技术对软件自由和 copyleft 的目标没有任何障碍。

The public GPLv3 drafting process sought to balance these positions of copyleft advocates with various disparate views of the larger Free-Software-using community. Ultimately, FSF compromised to the GPLv3 3 and GPLv3 6 provisions that, taken together, are a minimalist set of terms sufficient to protect the software freedom against the threat of invasive para-copyright.

公共 GPLv3 起草过程试图平衡 copyleft 倡导者的这些立场与更大的自由软件使用社区的各种不同观点。最终，FSF 妥协于 GPLv3 第3条和第6条，这些条款合在一起是一组足以保护软件自由免受侵犯性准版权威胁的极简主义条款。

The compromises made were ultimately quite reasonable. The primary one is embodied in GPLv3*§*6's "User Product" definition (see [9.9.2](#user-products) in this tutorial for details). Additionally, some readers of early GPLv3 drafts seem to have assumed GPLv3 contained a blanket prohibition on DRM; but it does not. In fact, no part of GPLv3 forbids DRM regarding non-GPL'd works; rather, GPLv3 forbids the use of DRM specifically to lock-down restrictions on users' ability to install modified versions of the GPL'd software itself, but again, *only* with regard to User Products.

做出的妥协最终是相当合理的。第一个体现在 GPLv3 第6条的“用户产品”定义（详见本教程9.9.2）。此外，一些早期 GPLv3 草案的读者似乎认为 GPLv3 包含对 DRM 的全面禁止； 但事实并非如此。事实上，GPLv3 的任何部分都没有禁止对非 GPL 作品进行 DRM； 相反，GPLv3 禁止使用 DRM，专门用于锁定限制用户安装 GPL 软件本身的修改版本的能力，但同样仅限于用户产品。

### GPLv3 §3: What Hath DMCA Wrought

### 9.6 GPLv3 第三款：DMCA做了什么

As discussed in [1.2.3](#software-and-non-copyright-legal-regimes) of this tutorial, [17 USC 1201](http://www.law.cornell.edu/uscode/text/17/1201) and related sections[^9-5] prohibits users from circumventing technological measures that implement DRM. Since this is part of copyright law and the GPL is primarily a copyright license, and since what the DMCA calls "circumvention" is simply "modifying the software" under the GPL, GPLv3 must disclaim that such anti-circumvention provisions are not applicable to the GPLv3'd software. GPLv3 3 shields users from being subjected to liability under anti-circumvention law for exercising their rights under the GPL, so far as the GPL can do so.

如本教程 1.2.3 中所述，17 USC 1201 和相关部[^9-5]禁止用户规避实施 DRM 的技术措施。由于这是版权法的一部分，而 GPL 主要是版权许可，而 DMCA 所说的“规避”只是 GPL 下的“修改软件”，因此 GPLv3 必须否认此类反规避条款不适用于 GPLv3 的软件。GPLv3 第三款保护用户在 GPL 允许的范围内行使他们在 GPL 项下的权利时免于承担反规避法规定的责任。

[^9-5]: These sections of the USC are often referred to as the “Digital Millennium Copyright Act”, or “DMCA”, as that was the name of the bill that so-modified these sections of the USC.

[^9-5]: USC 的这些部分通常被称为“数字千年版权法”或“DMCA”，因为这是对 USC 这些部分进行如此修改的法案的名称。

First, GPLv3 3 1 declares that no GPL'd program is part of an effective technological protection measure, regardless of what the program does. Early drafts of GPLv3 3 1 referred directly to the DMCA, but the final version instead includes instead an international legal reference to anticircumvention laws enacted pursuant to the 1996 WIPO treaty and any similar laws. Lawyers outside the USA worried that a USA statutory reference could be read as indicating a choice for application of USA law to the license as a whole. While the FSF did not necessarily agree with that view, the FSF decided anyway to refer to the WIPO treaty rather than DMCA, since several national anticircumvention laws were (or will likely be) structured more similarly to the anticircumvention provisions of the DMCA in their implementation of WIPO. Furthermore, the addition of "or similar laws" provides an appropriate catch-all.

首先，GPLv3 第3条第1款声明任何 GPL 程序都不是有效技术保护措施的一部分，无论该程序做什么。GPLv3 第3条第1款的早期草案直接引用了 DMCA，但最终版本反而包含了对根据 1996 年 WIPO 条约和任何类似法律颁布的反规避法的国际法律引用。美国境外的律师担心，美国法定参考可能被解读为表明选择将美国法律应用于整个许可。尽管 FSF 不一定同意该观点，但 FSF 还是决定参考 WIPO 条约而不是 DMCA，因为一些国家的反规避法律在实施中已经（或可能）在结构上更类似于 DMCA 的反规避条款 产权组织。此外，添加“或类似法律”提供了适当的包罗万象。

GPLv3 3 2 states precisely that a conveying party waives the power to forbid circumvention of techno- logical measures only to the extent that such circumvention is accomplished through the exercise of GPL rights in the conveyed work. GPLv3 3 2 makes clear that the referenced "legal rights" are specifically rights arising under anticircumvention law. and refers to both the conveying party's rights and to third party rights, as in some cases the conveying party will also be the party legally empowered to enforce or invoke rights arising under anticircumvention law.

GPLv3 第3条第2款明确指出，仅当这种规避是通过在所传送的作品中行使 GPL 权利来实现时，传送方才放弃禁止规避技术措施的权力。GPLv3 第3条第2款明确指出，所引用的“合法权利”是根据反规避法产生的具体权利。并且指的是转让方的权利和第三方的权利，因为在某些情况下，转让方也将是依法有权执行或援引反规避法规定的权利的一方。

These disclaimers by each licensor of any intention to use GPL'd software to stringently control access to other copyrighted works should effectively prevent any private or public parties from invoking DMCA-like laws against users who escape technical restriction measures implemented by GPL'd software.

每个许可方的这些关于使用 GPL 软件严格控制对其他受版权保护作品的访问的意图的免责声明应该有效地防止任何私人或公共团体援引类似 DMCA 的法律来对付那些逃避 GPL 软件实施的技术限制措施的用户。

### GPLv3 §4: Verbatim Copying

### 9.7 GPLv3 第4条：逐字复制

GPLv3 4 is a revision of GPLv2 1 (as discussed in [3.2](#gplv2-1-verbatim-copying) of this tutorial). There are almost no changes to this section from the GPLv2 1, other than to use the new defined terms.

GPLv3 第4条是 GPLv2 第1条的修订版（如本教程 3.2 中所述）。除了使用新定义的术语外，GPLv2 第1条的这一部分几乎没有变化。

The only notable change, of "a fee" to "any price or no price", is in the first sentence of GPLv3 4 2. The GPLv2 1 1 means that the GPL permits one to charge money for the distribution of software. Despite efforts by copyleft advocates to explain this in GPLv2 itself and in other documents, there are evidently some people who still believe that GPLv2 allows charging for services but not for selling copies of software and/or that the GPL requires downloads to be gratis. Perhaps this is because GPLv2 referred to charging a "fee"; the term "fee" is generally used in connection with services.

唯一值得注意的变化是 GPLv3 第4条第2款的第一句中将“收费”改为“任何价格或无价格”。GPLv2 第1条第1款表示 GPL 允许对软件分发收费。尽管 copyleft 拥护者努力在 GPLv2 本身和其他文档中解释这一点，但显然仍有一些人认为 GPLv2 允许对服务收费但不允许销售软件副本和/或 GPL 要求免费下载。也许这是因为 GPLv2 提到了收取“费用”； “费用”一词通常与服务相关。

GPLv2's wording also referred to "the physical act of transferring." The intention was to distinguish charging for transfers from attempts to impose licensing fees on all third parties. "Physical" might be read, however, as suggesting "distribution in a physical medium only".

GPLv2 的措辞还提到了“传输的物理行为”。目的是将转让收费与向所有第三方征收许可费的尝试区分开来。然而，“物理”可能被解读为暗示“仅在物理介质中分发”。

To address these two issues, GPLv3 says "price" in place of "fee," and removes the term "physical." GPLv3 *§*4 has also been revised from its corresponding section in GPLv2 in light of the GPLv3 *§*7 (see *§* [9.9.3](#gplv3-7-additional-permissions) in this tutorial for more). Specifically, a distributor of verbatim copies of the program's source code must obey any existing additional terms that apply to parts of the program pursuant to GPLv3 []{#_bookmark114 .anchor}*§*7. In addition, the distributor is required to keep intact all license notices, including notices of such additional terms.

为了解决这两个问题，GPLv3 用“价格”代替“费用”，并删除了“物理”一词。GPLv3 第4条也根据 GPLv3 第7条对 GPLv2 中的相应部分进行了修订（有关更多信息，请参见本教程的第 9.9.3 节）。具体来说，程序源代码的逐字副本的分发者必须遵守根据 GPLv3 适用于程序部分的任何现有附加条款。此外，经销商必须完整保留所有许可通知，包括此类附加条款的通知。

Finally, there is no harm in explicitly pointing out what ought to be obvious: that those who convey GPL-covered software may offer commercial services for the support of that software.

最后，明确指出应该显而易见的事情并没有什么害处：那些传送 GPL 软件的人可能会提供商业服务来支持该软件。

### GPLv3 §5: Modified Source

### 9.8 GPLv3 第5条：修改源代码

GPLv3 5 is the rewrite of GPLv2 2, which was discussed in [5.1](#gplv2-2-share-and-share-alike) of this tutorial. This section discusses the changes found in GPLv3 5 compared to GPLv2 2.

GPLv3 第5条是 GPLv2 第5条的重写，在本教程的 5.1 中讨论过。本节讨论 GPLv3 第5条与 GPLv2 第2条相比的变化。

GPLv3 5(a) still requires modified versions be marked with "relevant date", but no longer says "the date of any change". The best practice is to include the date of the latest and/or most significant changes and who made those. Of course, compared to its GPLv2 2(a), GPLv3 5(a) slightly relaxes the requirements regarding notice of changes to the program. In particular, the modified files themselves need no longer be marked. This reduces administrative burdens for developers of modified versions of GPL'd software.

GPLv3 5(a) 仍然要求修改版本标明“relevant date”，但不再写“date of any change”。最佳做法是包括最新和/或最重要更改的日期以及进行这些更改的人员。当然，与其 GPLv2 2(a) 相比，GPLv3 5(a) 稍微放宽了对程序变更通知的要求。特别是，修改后的文件本身不再需要标记。这减轻了 GPL 软件修改版本开发人员的管理负担。

GPLv3 5(b) is a new but simple provision. GPLv3 5(b) requires that the license text itself must be unmodified (except as permitted by GPLv3 7; see [9.9.3](#gplv3-7-additional-permissions) in this tutorial). Furthermore, it removes any perceived conflict between the words "keep intact all notices" in GPLv3 4, since operating under GPLv3 5 still includes all the requirements of GPLv3 4 by reference.

GPLv3 5(b) 是一项新的但简单的规定。GPLv3 5(b) 要求许可证文本本身必须未经修改（除非 GPLv3 7 允许；请参阅本教程中的 9.9.3）。此外，它消除了 GPLv3 第4条中“保持所有通知完整”一词之间的任何明显冲突，因为在 GPLv3 第5条下运行仍然通过引用包含 GPLv3 第4条的所有要求。

GPLv3 5(c) is the primary source-code-related copyleft provision of GPL. (The object-code-related copy- left provisions are in GPLv3 6, discussed in [9.9](#gplv3-6-non-source-and-corresponding-source) of this tutorial). Compared to GPLv2 2(b), GPLv3 5(c) states that the GPL applies to the whole of the work. Such was stated already in GPLv2 2(b), in "in whole or in part", but this simplified wording makes it clear it applies to the entire covered work.

GPLv3 第5条 c 项是 GPL 中与源代码相关的主要 copyleft 条款。（与目标代码相关的版权条款在 GPLv3 第六款中，在本教程的 9.9 中讨论）。与 GPLv2 2(b) 相比，GPLv3 第5条 c 项声明 GPL 适用于整个作品。GPLv2 2(b) 中已经以“全部或部分”的形式说明了这一点，但这种简化的措辞清楚地表明它适用于整个涵盖的作品。

Another change in GPLv3 5(c) is the removal of the words "at no charge," which was often is misunder- stood upon na¨ıve reading of in GPLv2 (b) (as discussed in [5.1.2](#gplv2-2b) of this tutorial).

GPLv3 第5条 c 项的另一个变化是删除了“免费”一词，这在天真阅读 GPLv2 (b) 时经常被误解（如本教程的 5.1.2 中所述）。

Note that of GPLv2 2's penultimate and ante-penultimate paragraphs are now handled adequately by the definitions in GPLv3 0 and as such, have no direct analogs in GPLv3.

请注意，GPLv2 第2条的倒数第二个和倒数第二个段落现在已由 GPLv3 第0条中的定义充分处理，因此，在 GPLv3 中没有直接类似物。

GPLv2 2's final paragraph, however, is reworded and expanded into the final paragraph of GPLv3 5, which now also covers issues related to copyright compilations (but not compilations into object code --- that's in the next section!). The intent and scope is the same as was intended in GPLv2.

然而，GPLv2 第2条的最后一段被改写并扩展到 GPLv3 第5条的最后一段，现在还涵盖了与版权编译相关的问题（但不包括编译成目标代码——那是在下一节！）。意图和范围与 GPLv2 中的意图和范围相同。

### GPLv3 §6: Non-Source and Corresponding Source

### 9.9 GPLv3 第6条：非源代码和对应源代码

GPLv3 6 states the compliance obligations for distributing "non-source forms" of a program (which means any form other than CCS). As noted in [9.2,](#gplv3-0-giving-in-on-defined-terms) "object code" in GPLv3 is defined broadly to mean any non-source version of a work, and thus includes not only binaries or executables, but also obfuscated, mini- mized, compressed or otherwise non-preferred forms for modification. Thus, GPLv3 6 clarifies and revises GPLv2 3. Indeed, GPLv3 6's CCS requirement under closely parallels the provisions of [GPLv2 3,](#gplv2-3-producing-binaries) with changes designed to make compliant provisioning easier under contemporary technological conditions. Dis- tributors of GPLv3'd object code must provide access to the corresponding source code, in one of four specified ways.

GPLv3 第6条规定了分发程序“非源代码形式”（即 CCS 以外的任何形式）的合规义务。如 9.2 中所述，GPLv3 中的“目标代码”被广泛定义为作品的任何非源版本，因此不仅包括二进制文件或可执行文件，还包括混淆、最小化、压缩或其他非首选形式修改。因此，GPLv3 第六款澄清并修订了 GPLv2 第三款。事实上，GPLv3 第六款的 CCS 要求与 GPLv2 第三款的规定非常相似，其变化旨在使合规供应在当代技术条件下更容易。GPLv3 目标代码的分发者必须以四种指定方式之一提供对相应源代码的访问。

GPLv3 6(a--b) now apply specifically to distribution of object code in a physical product. Physical products include embedded systems, as well as physical software distribution media such as CDs. As in GPLv2 3 (discussed in [5.2](#gplv2-3-producing-binaries) of this tutorial), the distribution of object code may either be accompanied by the machine-readable source code, or it may be accompanied by a valid written offer to provide the machine-readable source code. However, unlike in GPLv2, that offer cannot be exercised by any third party; rather, only those "who possess the object code" can exercise the offer. (Note that this is a substantial narrowing of requirements of offer fulfillment, and is a wonderful counterexample to dispute claims that the GPLv3 has more requirements than GPLv2.)

GPLv3 6(a–b) 现在专门适用于在物理产品中分发目标代码。物理产品包括嵌入式系统，以及物理软件分发介质，例如 CD。与 GPLv2 第3条（在本教程的 5.2 中讨论）一样，目标代码的分发可能伴随着机器可读的源代码，或者它可能伴随着提供机器可读源代码的有效书面报价。但是，与 GPLv2 不同的是，任何第三方都不能行使该要约； 相反，只有那些“拥有目标代码”的人才能行使要约。（请注意，这是对要约履行要求的实质性缩小，并且是对 GPLv3 比 GPLv2 有更多要求的说法提出异议的一个很好的反例。）

GPLv3 6(b) further revises the requirements for the written offer to provide source code. As before, the offer must remain valid for at least three years. In addition, even after three years, a distributor of a product containing GPL'd object code must offer to provide source code for as long as the distributor also continues to offer spare parts or customer support for the product model. This is a reasonable and appropriate requirement; a distributor should be prepared to provide source code if he or she is prepared to provide support for other aspects of a physical product.

GPLv3 第六款(b) 进一步修改了对书面报价提供源代码的要求。和以前一样，要约必须至少保持3年有效。此外，即使在3年后，包含 GPL 目标代码的产品的分销商也必须提供源代码，只要该分销商还继续为该产品模型提供备件或客户支持。这是一个合理且适当的要求； 如果分销商准备为物理产品的其他方面提供支持，则他或她应该准备好提供源代码。

GPLv3 6(a--b) clarifies that the medium for software interchange on which the machine-readable source code is provided must be a durable physical medium. GPLv3 6(b)(2), however, permits a distributor to instead offer to provide source code from a network server instead, which is yet another example GPLv3 looser in its requirements than GPLv2 (see [5.2.2](#additional-source-provision-options) for details).

GPLv3 第6条(a–b) 阐明了提供机器可读源代码的软件交换介质必须是耐用的物理介质。然而，GPLv3 第6条(b)(2) 允许发行商转而提议从网络服务器提供源代码，这是 GPLv3 的要求比 GPLv2 宽松的另一个例子（详见 5.2.2）。

GPLv3 6(c) gives narrower permission than GPLv2 3(c). The "pass along" option for GPLv3 6(c)(1) offers is now available only for individual distribution of object code; moreover, such individual distribution can occur only "occasionally and noncommercially." A distributor cannot comply with the GPL merely by making object code available on a publicly-accessible network server accompanied by a copy of the written offer to provide source code received from an upstream distributor.

GPLv3 第6条（c）提供比 GPLv2 第3条（c）更窄的许可。GPLv3 第6条（c）(1) 所述的“传递”选项现在仅适用于目标代码的单独分发； 此外，这种个人分发只能“偶尔且非商业性地”发生。分销商不能仅通过在可公开访问的网络服务器上提供目标代码并附上书面报价的副本以提供从上游分销商收到的源代码来遵守 GPL。

GPLv3 6(d) revises and improves GPLv2 3's final paragraph. When object code is provided by offering access to copy the code from a designated place (such as by enabling electronic access to a network server), the distributor must merely offer equivalent access to copy the source code "in the same way through the same place". This wording also permits a distributor to offer a third party access to both object code and source code on a single network portal or web page, even though the access may include links to different physical servers. For example, a downstream distributor may provide a link to an upstream distributor's server and arrange with the operator of that server to keep the source code available for copying for as long as the downstream distributor enables access to the object code. Thus, the obligation remains on the party distributing object code to point prominently ("next to" the object code download) to the third-party source code provisioning server, and to ensure that this third-party server remains in operation for required period. This codifies formally the typical historical interpretation of GPLv2.

GPLv3 第6条(d) 修改并改进了 GPLv2 第3条的最后一段。当通过提供从指定位置复制代码的访问权限（例如通过启用对网络服务器的电子访问权限）来提供目标代码时，分销商必须仅提供等效的访问权限以“以相同方式通过相同位置”复制源代码 ”。该措辞还允许分销商在单个网络门户或网页上向第三方提供对目标代码和源代码的访问权限，即使该访问权限可能包含指向不同物理服务器的链接。例如，下游分销商可以提供到上游分销商服务器的链接，并与该服务器的运营商安排，只要下游分销商能够访问目标代码，就可以保持源代码可供复制。因此，分发目标代码的一方仍有义务在显着位置（“目标代码下载旁边”）指向第三方源代码供应服务器，并确保该第三方服务器在规定的时间内保持运行。这正式编纂了 GPLv2 的典型历史解释。

Furthermore, under GPLv3 6(d), distributors may charge for the conveyed object code; however, those who pay to obtain the object code must be given equivalent and gratis access to obtain the CCS. (If distributors convey the object code gratis, distributors must likewise make CCS available without charge.) Those who do not obtain the object code from that distributors (perhaps because they choose not to pay the fee for object code) are outside the scope of the provision; distributors are under no specific obligation to give CCS to someone who has not purchased an object code download under GPLv3 *§*6(d). (Note: this does not change nor impact any obligations under GPLv3 *§*6(b)(2); GPLv3 *§*6(d) is a wholly different provision.)

此外，根据 GPLv3 第6条(d)，分销商可以对传送的目标代码收费； 但是，那些为获得目标代码而付费的人必须获得同等的免费访问权限才能获得 CCS。（如果分销商免费提供目标代码，分销商必须同样免费提供 CCS。）那些没有从分销商那里获得目标代码的人（可能是因为他们选择不支付目标代码的费用）不在范围之内。条款; 分销商没有特定义务向未根据 GPLv3 第六款(d) 购买目标代码下载的人提供 CCS。（注意：这不会改变或影响 GPLv3 第6条(b)(2) 下的任何义务；GPLv3 第6条(d) 是完全不同的规定。）

#### 9.9.1 GPLv3 §6(e): Peer-to-Peer Sharing Networks

#### 9.9.1 GPLv3 第6条e款：点对点共享网络

GPLv3 6(e) allows provision of CCS via another server when the binary or other non-source form is dis- tributed by peer-to-peer protocols such as BitTorrent. Here the requirement is only that each peer be effectively informed of the location of the source code on a server as above.

当二进制或其他非源代码形式通过对等协议（如 BitTorrent）分发时，GPLv3 第6条(e) 允许通过另一台服务器提供 CCS。这里的要求只是像上面那样有效地通知每个对等方源代码在服务器上的位置。

GPLv3 really did require this addition, even though it adds complexity to a key section of GPL. In particular, Decentralized peer-to-peer file sharing present a challenge to the unidirectional view of distribution that is implicit in GPLv2 and initial drafts of GPLv3. Identification of an upstream/downstream link in BitTorrent distribution is neither straightforward nor reasonable; such distribution is multidirectional, cooperative and (somewhat) anonymous. In peer-to-peer distribution systems, participants act both as transmitters and recipients of blocks of a particular file, but they perceive the experience merely as users and receivers, and not as distributors in any conventional sense. At any given moment of time, most peers will not have the complete file.

GPLv3 确实需要添加这一内容，尽管它增加了 GPL 关键部分的复杂性。特别是，去中心化点对点文件共享对 GPLv2 和 GPLv3 初始草案中隐含的单向分发视图提出了挑战。在 BitTorrent 分发中识别上游/下游链接既不简单也不合理； 这种分布是多向的、合作的和（有点）匿名的。在点对点分发系统中，参与者既充当特定文件块的发送者又充当接收者，但他们仅将体验视为用户和接收者，而不是任何传统意义上的分发者。在任何给定的时刻，大多数同行都不会拥有完整的文件。

Meanwhile, GPLv3 6(d) permits distribution of a work in object code form over a network, provided that the distributor offers equivalent access to copy the Corresponding Source Code "in the same way through the same place". This wording might be interpreted to permit peer-to-peer distribution of binaries *if* they are packaged together with the CCS, but such packaging is impractical, for at least three reasons. First, even if the CCS is packaged with the object code, it will only be available to a non-seeding peer at the end of the distribution process, but the peer will already have been providing parts of the binary to others in the network. Second, in practice, peer-to-peer forms of transmission are poorly suited means for distributing CCS. In large distributions, packaging CCS with the object code may result in a substantial increase in file size and transmission time. Third, in current practice, CCS packages themselves tend *not* to be transmitted through BitTorrent --- owing to reduced demand -- thus, there generally will be too few participants downloading the same source package at the same time to enable effective seeding and distribution.

同时，GPLv3 第6条(d) 允许通过网络以目标代码形式分发作品，前提是分发者提供同等访问权限以“以相同方式通过相同位置”复制相应的源代码。如果二进制文件与 CCS 打包在一起，则该措辞可能被解释为允许二进制文件的点对点分发，但至少出于三个原因，这种打包是不切实际的。首先，即使 CCS 与目标代码打包在一起，它也只能在分发过程结束时供非播种对等方使用，但对等方已经向网络中的其他人提供了部分二进制文件。其次，在实践中，点对点传输形式不太适合分发 CCS。在大型发行版中，将 CCS 与目标代码打包在一起可能会导致文件大小和传输时间大幅增加。第三，在目前的实践中，CCS 包本身往往不通过 BitTorrent 传输——由于需求减少——因此，通常同时下载相同源包的参与者太少，无法实现有效的播种和分配。

GPLv3 6(e) addresses these issues. If a licensee conveys such a work of object code using peer-to-peer transmission, that licensee is in compliance with GPLv3 6 if the licensee informs other peers where the object code and its CCS are publicly available at no charge under subsection GPLv3 6(d). The CCS therefore need not be provided through the peer-to-peer system that was used for providing the binary.

GPLv3 第6条(e) 解决了这些问题。如果被许可人使用点对点传输传送此类目标代码作品，如果被许可人根据 GPLv3 第6条通知其他同行目标代码及其 CCS 是免费公开可用的，则该被许可人符合 GPLv3 第6条（ d). 因此，不需要通过用于提供二进制文件的对等系统来提供 CCS。

Second, GPLv3 9 also clarifies that ancillary propagation of a covered work that occurs as part of the process of peer-to-peer file transmission does not require acceptance, just as mere receipt and execution of the Program does not require acceptance. Such ancillary propagation is permitted without limitation or further obligation.

其次，GPLv3 第9条还阐明了作为点对点文件传输过程的一部分发生的涵盖作品的辅助传播不需要接受，就像仅仅接收和执行程序不需要接受一样。这种辅助传播是允许的，没有限制或进一步的义务。

#### 9.9.2 User Products, Installation Information and Device Lock-Down

#### 9.9.2 用户产品、安装信息和设备锁定

As discussed in [9.5](#gplv3s-views-on-drm-and-device-lock-down) of this tutorial, GPLv3 seeks to thwart technical measures such as signature checks in hardware to prevent modification of GPL'd software on a device.

正如本教程 9.5 中所讨论的，GPLv3 试图阻止技术措施，例如硬件中的签名检查，以防止在设备上修改 GPL 软件。

To address this issue, GPLv3 6 requires that parties distributing object code provide recipients with the source code through certain means. When those distributors pass on the CCS, they are also required to pass on any information or data necessary to install modified software on the particular device that included it. (This strategy is not unlike that used in LGPLv2.1 to enable users to link proprietary programs to modified libraries.)

为了解决这个问题，GPLv3 第6条要求分发目标代码的各方通过某种方式向接收者提供源代码。当这些分销商传递 CCS 时，他们还需要传递在包含它的特定设备上安装修改后的软件所需的任何信息或数据。（此策略与 LGPLv2.1 中使用的策略没有什么不同，使用户能够将专有程序链接到修改后的库。）

##### User Products

##### 用户产品

The scope of these requirements is narrow. GPLv3 6 introduces the concept of a "User Product", which includes devices that are sold for personal, family, or household use. Distributors are only required to provide Installation Information when they convey object code in a User Product.

这些要求的范围很窄。GPLv3 第6条引入了“用户产品”的概念，其中包括为个人、家庭或家庭使用而销售的设备。当经销商在用户产品中传送目标代码时，他们只需要提供安装信息。

In brief, the right to convey object code in a defined class of "User Products," under certain circumstances, depends on providing whatever information is required to enable a recipient to replace the object code with a functioning modified version.

简而言之，在某些情况下，在定义的“用户产品”类别中传送目标代码的权利取决于提供使接收者能够使用功能修改版本替换目标代码所需的任何信息。

This was a compromise that was difficult for the FSF to agree to during the GPLv3 drafting process. However, companies and governments that use specialized or enterprise-level computer facilities reported that they actually *want* their systems not to be under their own control. Rather than agreeing to this as a concession, or bowing to pressure, they ask for this as a *preference*. It is not clear that the GPL should interfere here, since the main problem lies elsewhere.

这是 FSF 在 GPLv3 起草过程中难以同意的妥协。然而，使用专业或企业级计算机设施的公司和政府报告称，他们实际上希望自己的系统不受自己的控制。他们没有将此作为让步或屈服于压力而同意，而是将此视为一种偏好。不清楚 GPL 是否应该干预这里，因为主要问题在别处。尽管在任何情况下对修改施加技术障碍都是错误的，但受限设备在当今最实际关注的领域属于用户产品定义。大多数（如果不是全部）运行受 GPL 保护的程序的技术限制设备都是消费电子设备。此外，制造商和这些用户之间的影响力悬殊，使得用户很难以其微弱和无组织的市场力量拒绝技术限制。即使仅限于用户产品，该条款也解决了根本问题。

While imposing technical barriers to modification is wrong regardless of circumstances, the areas where restricted devices are of the greatest practical concern today fall within the User Product definition. Most, if not all, technically-restricted devices running GPL-covered programs are consumer electronics devices. Moreover, the disparity in clout between the manufacturers and these users makes it difficult for the users to reject technical restrictions through their weak and unorganized market power. Even limited to User Products, this provision addresses the fundamental problem.

无论情况如何，施加技术障碍都是错误的，但是当今，限制设备的实际关注的领域属于用户产品定义。 大多数（如果不是全部）运行GPL程序的技术限制设备是消费电子设备。 此外，制造商和这些用户之间的影响力差异使用户难以通过薄弱且无组织的市场能力拒绝技术限制。 即使仅限于用户产品，此规定也解决了基本问题。

The core of the User Product definition is a subdefinition of "consumer product" adapted from the Magnuson-Moss Warranty Act, a federal consumer protection law in the USA found in 15 USC 2301: "any tangible personal property which is normally used for personal, family, or household purposes." The USA has had three decades of experience of liberal judicial and administrative interpretation of this definition in a manner favorable to consumer rights.[^6^](#_bookmark120) Ideally, this body of interpretation[^7^](#_bookmark121) will guide interpretation of the consumer product subdefinition in GPLv3 6, and this will hopefully provide a degree of legal certainty advantageous to device manufacturers and downstream licensees alike.

用户产品定义的核心是根据美国联邦消费者保护法 Magnuson-Moss 保修法改编的“消费品”的子定义，该法案载于 15 USC 2301：“任何通常用于个人、 家庭或家庭目的。” 美国在以有利于消费者权利的方式对此定义进行自由司法和行政解释已有 30 年的经验[^9-6]。理想情况下，该解释体系[^9-7]将指导对 GPLv3 6 中消费品子定义的解释，并且这有望为设备制造商和下游被许可人提供一定程度的法律确定性。

[^9-6]:Magnuson-Moss 消费品定义本身在美国和加拿大具有影响力，已被多个州和省的消费者保护法采纳。

[^9-7]:然而，FSF 非常清楚，纳入此类法律解释绝不是为了作为美国法律对 GPLv3 的一般选择。

One well-established interpretive principle under Magnuson-Moss is that ambiguities are resolved in favor of coverage. That is, in cases where it is not clear whether a product falls under the definition of consumer product, the product will be treated as a consumer product.[^9-8^] Moreover, for a given product, "normally used" is understood to refer to the typical use of that type of product, rather than a particular use by a particular buyer. Products that are commonly used for personal as well as commercial purposes are consumer products, even if the person invoking rights is a commercial entity intending to use the product for commercial purposes.[^9-9^] Even a small amount of "normal" personal use is enough to cause an entire product line to be treated as a consumer product under Magnuson-Moss.[^9-10^]

Magnuson-Moss 下的一个公认的解释原则是解决歧义以支持覆盖。也就是说，在不清楚产品是否属于消费品定义的情况下，该产品将被视为消费品[^9-8^]。此外，对于给定的产品，“通常使用”被理解为是指 该类型产品的典型用途，而不是特定用途一个特定的买家。通常用于个人和商业目的的产品是消费品，即使调用权利的人是打算将产品用于商业目的的商业实体[^9-9^]。即使是少量的“正常”个人使用也足够了 使整个产品线在 Magnuson-Moss 下被视为消费品[^9-10^]。

[^9-8^]: 16 CFR § 700.1(a); McFadden v. Dryvit Systems, Inc., 54 UCC Rep. Serv.2d 934 (D. Ore. 2004).

[^9-8^]: 16 CFR § 700.1(a)； McFadden 诉 Dryvit Systems, Inc., 54 UCC Rep. Serv.2d 934 (D. Ore. 2004)。

[^9-9^]: 16 CFR § 700.1(a). Numerous court decisions interpreting Magnuson-Moss are in accord; see, e.g., Stroebner Motors, Inc. v. Automobili Lamborghini S.p.A., 459 F. Supp.2d 1028, 1033 (D. Hawaii 2006).

[^9-9^]: 16 美国联邦法规 700.1(a)。许多解释 Magnuson-Moss 的法院判决是一致的； 参见，例如，Stroebner Motors, Inc. 诉 Automobili Lamborghini S.p.A.，459 F. Supp.2d 1028, 1033（D. Hawaii 2006）。

[^9-10^]: *Tandy Corp. v. Marymac Industries, Inc.*, 213 U.S.P.Q. 702 (S.D. Tex. 1981). In this case, the court concluded that TRS-80 microcomputers were consumer products, where such computers were designed and advertised for a variety of users, []{#_bookmark126 .anchor}including small businesses and schools, and had only recently been promoted for use in the home.

[^9-10^]: Tandy Corp. 诉 Marymac Industries, Inc.，213 U.S.P.Q. 702（S.D. Tex. 1981）。在本案中，法院得出结论认为 TRS-80 微型计算机是消费品，此类计算机是为各种用户设计和宣传的，包括小型企业和学校，并且最近才被推广用于 在家里使用。

However, Magnuson-Moss is not a perfect fit because in the area of components of dwellings, the settled interpretation under Magnuson-Moss is under-inclusive. Depending on how such components are manufac- tured or sold, they may or may not be considered Magnuson-Moss consumer products.[^9-11^]Therefore, GPLv3 defines User Products as a superset of consumer products that also includes "anything designed or sold for incorporation into a dwelling."

然而，Magnuson-Moss 并不是一个完美的选择，因为在住宅的组成部分，Magnuson-Moss 下的固定解释是包容性不足的。根据此类组件的制造或销售方式，它们可能被视为也可能不被视为 Magnuson-Moss 消费产品[^9-11^]。因此，GPLv3 将用户产品定义为消费产品的超集，其中还包括“任何为公司设计或销售的产品” 住处。”

[^9-11^]: Building materials that are purchased directly by a consumer from a retailer, for improving or modifying an existing dwelling, are consumer products under Magnuson-Moss, but building materials that are integral component parts of the structure of a dwelling at the time that the consumer buys the dwelling are not consumer products. 16 C.F.R. 700.1(c)--(f); Federal Trade Commission, Final Action Concerning Review of Interpretations of Magnuson-Moss Warranty Act, 64 Fed. Reg. 19,700 (April 22, 1999); see also, e.g., *McFadden*, 54 U.C.C. Rep. Serv.2d at 934.

[^9-11^]: 消费者直接从零售商处购买的建筑材料，用于改善或改造现有住宅，属于 Magnuson-Moss 下的消费品，但在 消费者购买住宅的时间不属于消费品。16 C.F.R. 700.1©–(f)； 联邦贸易委员会，关于审查 Magnuson-Moss 保证法案解释的最终行动，64 Fed。注册。19,700（1999 年 4 月 22 日）； 另见，例如，McFadden, 54 U.C.C. Rep. Serv.2d 在 934。

Thus, the three sentences in the center of GPLv3's User Product definition encapsulate the judicial and administrative principles established over the past three decades in the USA concerning the Magnuson-Moss consumer product definition. First, it states that doubtful cases are resolved in favor of coverage under the definition. Second, it indicates that the words "normally used" in the consumer product definition refer to a typical or common use of a class of product, and not the status of a particular user or expected or actual uses by a particular user. Third, it clearly states that the existence of substantial non-consumer uses of a product does not negate a determination that it is a consumer product, unless such non-consumer uses represent the only significant mode of use of that product.

因此，GPLv3 用户产品定义中心的三句话概括了美国过去三十年建立的关于 Magnuson-Moss 消费产品定义的司法和行政原则。首先，它声明疑似案件的解决有利于定义下的覆盖范围。其次，它表明消费品定义中的“通常使用”一词是指一类产品的典型或普遍使用，而不是特定用户的状态或特定用户的预期或实际使用。第三，它明确指出，产品的大量非消费者使用的存在并不能否定它是消费品的决定，除非这种非消费者使用代表了该产品的唯一重要使用方式。

It should be clear from these added sentences that it is the general mode of use of a product that determines objectively whether or not it is a consumer product. One could not escape the effects of the User Products provisions by labeling what is demonstrably a consumer product in ways that suggest it is "for professionals", for example.

从这些增加的句子中应该清楚，是产品的一般使用方式客观地决定了它是否是消费品。例如，通过以表明它是“专业人士”的方式标记明显是消费品的东西，无法逃避用户产品条款的影响。

##### Installation Information

##### 安装信息

With the User Products definition complete, the "Installation Information" definition uses that to define what those receiving object code inside a User Product must receive.

随着用户产品定义的完成，“安装信息”定义使用它来定义用户产品中那些接收目标代码必须接收的内容。

Installation Information is information that is "required to install and execute modified versions of a covered work . . . from a modified version of its" CCS, in the same User Product for which the covered work is conveyed. GPLv3 provides guidance concerning how much information must be provided: it "must suffice to ensure that the continued functioning of the modified object code is in no case prevented or interfered with solely because modification has been made." For example, the information provided would be insufficient if it enabled a modified version to run only in a disabled fashion, solely because of the fact of modification (regardless of the actual nature of the modification). The information need not consist of cryptographic keys; Installation Information may be "any methods, procedures, authorization keys, or other information". Note that GPLv3 does not define "continued functioning" further. However, GPLv3 does provide some additional guidance concerning the scope of GPLv3-compliant action or inaction that distributors of technically-restricted User Products can take with respect to a downstream recipient who replaces the conveyed object code with a modified version. First of all, GPLv3 makes clear that GPLv3 implies no obligation "to continue to provide support service, warranty, or updates" for such a work.

安装信息是“安装和执行涵盖作品的修改版本所需的信息。……来自其修改版本”。CSS，在传达涵盖工作的同一用户产品中。GPLv3 提供了关于必须提供多少信息的指南：它“必须足以确保修改后的目标代码的继续运行在任何情况下都不会仅仅因为进行了修改而受到阻止或干扰。” 例如，如果仅仅因为修改的事实（不管修改的实际性质）使修改后的版本仅以禁用方式运行，那么所提供的信息将是不充分的。信息不需要包含密钥； 安装信息可以是“任何方法、程序、授权密钥或其他信息”。请注意，GPLv3 没有进一步定义“持续运行”。但是，GPLv3 确实提供了一些额外的指导，涉及技术受限用户产品的分销商可以针对下游接收者采取的符合 GPLv3 的行动或不行动的范围，后者将所传送的目标代码替换为修改后的版本。首先，GPLv3 明确了 GPLv3 意味着不为此类作品“继续提供支持服务、保证或更新”的义务。

Second, most technically-restricted User Products are designed to communicate across networks. It is important for both users and network providers to know when denial of network access to devices running modified versions becomes a GPL violation. GPLv3 permits denial of access in two cases: "when the modification itself materially and adversely affects the operation of the network," and when the modification itself "violates the rules and protocols for communication across the network". The second case is deliberately drawn in general terms, and it serves as a foundation for reasonable enforcement policies that respect recipients' right to modify while recognizing the legitimate interests of network providers.

其次，大多数受技术限制的用户产品旨在跨网络通信。对于用户和网络提供商来说，了解拒绝对运行修改版本的设备进行网络访问何时会违反 GPL 非常重要。GPLv3 允许在两种情况下拒绝访问：“当修改本身对网络的运行产生重大不利影响时”，以及当修改本身“违反了网络通信的规则和协议时”。第二种情况是故意用笼统的术语来描述的，它是合理执行政策的基础，这些政策尊重接收者的修改权，同时承认网络提供者的合法利益。

Note that GPLv3 permits the practice of conveying object code in a mode not practically susceptible to modification by any party, such as code burned in ROM or embedded in silicon. The goal of the Installation Information requirement is to ensure the downstream licensee receives the real right to modify when the device manufacturer or some other party retains that right. Accordingly, GPLv3 6's ante-penultimate paragraph states that the requirement to provide Installation Information "does not apply if neither you nor any third party retains the ability to install modified object code on the User Product".

请注意，GPLv3 允许以一种实际上不易被任何一方修改的模式传送目标代码，例如在 ROM 中烧录或嵌入硅中的代码。安装信息要求的目标是确保下游被许可人在设备制造商或某些其他方保留修改权时获得真正的修改权。因此，GPLv3 第六款的倒数第二段规定，提供安装信息的要求“不适用，如果您或任何第三方都没有保留在用户产品上安装修改后的目标代码的能力”。

Finally, GPLv3 第六款makes it clear that there is also no requirement to provide warranty or support for the User Product itself.

请注意，GPLv3 允许以一种实际上不易被任何一方修改的模式传送目标代码，例如在 ROM 中烧录或嵌入硅中的代码。安装信息要求的目标是确保下游被许可人在设备制造商或某些其他方保留修改权时获得真正的修改权。因此，GPLv3 第六款的倒数第二段规定，提供安装信息的要求“不适用，如果您或任何第三方都没有保留在用户产品上安装修改后的目标代码的能力”。

#### 9.9.3 GPLv3 §7: Additional Permissions

#### 9.9.3 GPLv3 第7条：附加权限

The GPL is a statement of permissions, some of which have conditions. Additional terms --- terms that supplement those of the GPL --- may come to be placed on, or removed from, GPL-covered code in certain common ways. Copyleft licensing theorists have generally called those added terms "additional permissions" if they grant exceptions from the conditions of the GPL, and "additional requirements" if they add conditions to the basic permissions of the GPL. The treatment of additional permissions and additional requirements under GPLv3 is necessarily asymmetrical, because they do not raise the same interpretive issues; in particular, additional requirements, if allowed without careful limitation, could transform a GPL'd program into a non- free one.

GPL 是一种权限声明，其中一些是有条件的。附加条款——补充 GPL 条款的条款——可能会以某些常见的方式添加到 GPL 代码中，或从中删除。Copyleft 许可理论家通常将这些添加的条款称为“附加许可”，如果他们授予 GPL 条件的例外，如果他们将条件添加到 GPL 的基本许可，则称为“附加要求”。GPLv3 下对额外许可和额外要求的处理必然是不对称的，因为它们不会引发相同的解释问题； 特别是，如果在没有仔细限制的情况下允许附加要求，可能会将 GPL 程序转换为非自由程序。

Due to the latter fear, historically, GPLv2 did not permit any additional requirements. However, over time, many copyright holders generally tolerated certain types of benign additional requirements merely through a "failure to enforce" estoppel-esque scenario. Therefore, GPLv3 allows for some specific limited requirement variations that GPLv2 technically prohibits.

由于后一种恐惧，从历史上看，GPLv2 不允许任何额外的要求。然而，随着时间的推移，许多版权持有者通常仅仅通过“未能执行”禁止反言式的场景来容忍某些类型的良性附加要求。因此，GPLv3 允许 GPLv2 在技术上禁止的一些特定的有限要求变化。

With these principles in the background, GPLv3 *§*7 answers the following questions:

在这些原则的背景下，GPLv3 第7条回答了以下问题：

1. How does the presence of additional terms on all or part of a GPL'd program affect users' rights?

1. GPL 程序的全部或部分附加条款的存在如何影响用户的权利？

2. When and how may a licensee add terms to code being distributed under the GPL?

2. 被许可人何时以及如何向根据 GPL 分发的代码添加条款？

3. When may a licensee remove additional terms?

3. 被许可人何时可以删除附加条款？

Additional permissions present the easier case. Since the mid-1990s, permissive exceptions often appeared alongside GPLv2 to allow combination with certain non-free code. Typically, downstream stream recipients could remove those exceptions and operate under pure GPLv2. Similarly, LGPLv2.1 is in essence a permissive variant of GPLv2, and it permits relicensing under the GPL.

附加权限呈现更简单的情况。自 20 世纪 90 年代中期以来，宽容例外经常与 GPLv2 一起出现，以允许与某些非自由代码结合。通常，下游流接收者可以删除这些例外并在纯 GPLv2 下运行。同样，LGPLv2.1 本质上是 GPLv2 的许可变体，它允许在 GPL 下重新授权。

These practices are now generalized via GPLv3 7. A licensee may remove any additional permission from a covered work, whether it was placed by the original author or by an upstream distributor. A licensee may also add any kind of additional permission to any part of a work for which the licensee has, or can give, appropriate copyright permission. For example, if the licensee has written that part, the licensee is the copyright holder for that part and can therefore give additional permissions that are applicable to it. Alternatively, the part may have been written by someone else and licensed, with the additional permissions, to that licensee. Any additional permissions on that part are, in turn, removable by downstream recipients. As GPLv3 7 1 explains, the effect of an additional permission depends on whether the permission applies to the whole work or a part.

这些做法现在通过 GPLv3 第7条得到推广。被许可人可以从涵盖的作品中删除任何额外的许可，无论它是由原作者还是由上游分发者引入的。被许可人还可以对作品的任何部分添加任何类型的额外许可，而被许可人已对其拥有或可以给予适当的版权许可。例如，如果被许可人编写了该部分，则被许可人是该部分的版权所有者，因此可以授予适用于该部分的额外许可。或者，该部分可能是由其他人编写的，并以附加许可的形式许可给该被许可人。反过来，下游接收者可以删除该部分的任何其他权限。正如 GPLv3 第7条第1款所解释的那样，附加许可的效果取决于该许可是适用于整个作品还是部分作品。

Indeed, LGPLv3 is itself simply a list of additional permissions supplementing the terms of GPLv3. GPLv3 7 has thus provided the basis for recasting a formally complex license as an elegant set of added terms, without changing any of the fundamental features of the existing LGPL. LGPLv3 is thus a model for developers wishing to license their works under the GPL with permissive exceptions. The removability of additional permissions under GPLv3 7 does not alter any existing behavior of the LGPL since the LGPL has always allowed relicensing under the ordinary GPL.

事实上，LGPLv3 本身只是一个补充 GPLv3 条款的附加许可列表。因此，GPLv3 第7条为将形式上复杂的许可证重铸为一组优雅的附加条款提供了基础，而无需改变现有 LGPL 的任何基本特征。因此，LGPLv3 是希望根据 GPL 许可其作品的开发人员的模型，但有例外。GPLv3 第7条下附加许可的可移除性不会改变 LGPL 的任何现有行为，因为 LGPL 始终允许在普通 GPL 下重新许可。

### GPLv3 §7: Understanding License Compatibility

### 9.10 GPLv3 第7条：理解许可证兼容性

A challenge that faced the Free Software community heavily through out the early 2000s was the proliferation of incompatible Free Software licenses. Of course, the GPL cannot possibly be compatible with all such licenses. However, GPLv3 contains provisions that are designed to reduce license incompatibility by making it easier for developers to combine code carrying non-GPL terms with GPL'd code.

在 2000 年代初期，自由软件社区面临的一个严峻挑战是不兼容的自由软件许可证的激增。当然，GPL 不可能兼容所有这些许可证。但是，GPLv3 包含旨在通过使开发人员更容易将带有非 GPL 条款的代码与 GPL 代码结合起来来减少许可证不兼容性的条款。

This license compatibility issue arises for three reasons. First, the GPL is a strong copyleft license, requiring modified versions to be distributed under the GPL. Second, the GPL states that no further restrictions may be placed on the rights of recipients. Third, all other software freedom respecting licenses in common use contain certain requirements, many of which are not conditions made by the GPL. Thus, when GPL'd code is modified by combination with code covered by another formal license that specifies other requirements, and that modified code is then distributed to others, the freedom of recipients may be burdened by additional requirements in violation of the GPL. It can be seen that additional permissions in other licenses do not raise any problems of license compatibility.

出现此许可证兼容性问题的原因有以下三个。首先，GPL 是一个强大的 copyleft 许可证，要求在 GPL 下分发修改后的版本。其次，GPL 声明不能对接收者的权利施加进一步的限制。第三，所有其他尊重通用许可证的软件自由都包含某些要求，其中许多不是 GPL 规定的条件。因此，当 GPL 代码与另一个指定其他要求的正式许可证所涵盖的代码相结合进行修改，然后将修改后的代码分发给其他人时，接收者的自由可能会受到违反 GPL 的额外要求的负担。可以看出，其他许可证中的附加权限不会引起任何许可证兼容性问题。

GPLv3 took a new approach to the issue of combining GPL'd code with code governed by the terms of other software freedom licenses. Traditional GPLv2 license compatibility theory (which was not explicitly stated in GPLv2 itself, but treated as a license interpretation matter by the FSF) held that GPLv2 allowed such combinations only if the non-GPL licensing terms permitted distribution under the GPL and imposed no restrictions on the code that were not also imposed by the GPL. In practice, the FSF historically supplemented that policy with a structure of exceptions for certain kinds of combinations.

GPLv3 采取了一种新方法来解决将 GPL 代码与受其他软件自由许可条款约束的代码相结合的问题。传统的 GPLv2 许可兼容性理论（GPLv2 本身并未明确说明，但被 FSF 视为许可解释事项）认为 GPLv2 仅在非 GPL 许可条款允许在 GPL 下分发并且不对任何限制施加限制的情况下才允许此类组合 GPL 也没有强加的代码。在实践中，FSF 历来为该政策补充了针对某些类型组合的例外结构。

GPLv3 7 implements a more explicit policy on license compatibility. It formalizes the circumstances under which a licensee may release a covered work that includes an added part carrying non-GPL terms. GPLv3 7 distinguish between terms that provide additional permissions, and terms that place additional requirements on the code, relative to the permissions and requirements established by applying the GPL to the code.

GPLv3 第7条在许可证兼容性方面实施了更明确的政策。它正式规定了被许可人可以发布包含带有非 GPL 条款的附加部分的涵盖作品的情况。GPLv3 第7条区分提供额外权限的条款和对代码提出额外要求的条款，相对于通过将 GPL 应用于代码而建立的权限和要求。

As discussed in the previous section of this tutorial, GPLv3 7 first and foremost explicitly allows added parts covered by terms with additional permissions to be combined with GPL'd code. This codifies the existing practice of regarding such licensing terms as compatible with the GPL. A downstream user of a combined GPL'd work who modifies such an added part may remove the additional permissions, in which case the broader permissions no longer apply to the modified version, and only the terms of the GPL apply to it.

正如本教程上一节中所讨论的，GPLv3 第7条首先明确允许将具有附加权限的条款所涵盖的附加部分与 GPL 代码相结合。这规范了将此类许可条款视为与 GPL 兼容的现有做法。修改此类添加部分的组合 GPL 作品的下游用户可以删除额外的权限，在这种情况下，更广泛的权限不再适用于修改后的版本，只有 GPL 的条款适用于它。

In its treatment of terms that impose additional requirements, GPLv3 7 extends the range of licensing terms with which the GPL is compatible. An added part carrying additional requirements may be combined with GPL'd code, but only if those requirements belong to a set enumerated in GPLv3 7. There are, of course, limits on the acceptable additional requirements, which ensures that enhanced license compatibility does not defeat the broader software-freedom-defending terms of the GPL. Unlike terms that grant additional permissions, terms that impose additional requirements cannot be removed by a downstream user of the combined GPL'd work, because only in the pathological case [^9-12^] would a user have the right to do so.

在处理附加要求的条款时，GPLv3 第7条扩展了与 GPL 兼容的许可条款范围。带有附加要求的附加部分可以与 GPL 代码组合，但前提是这些要求属于 GPLv3 第7条中列举的集合。当然，可接受的附加要求是有限制的，这确保增强的许可证兼容性不会击败 GPL 更广泛的软件自由捍卫条款。与授予额外权限的条款不同，施加额外要求的条款不能被组合 GPL 作品的下游用户删除，因为只有在病态情况下 [^9-12^] 用户才有权这样做。

[^9-12^]: Theoretically, a user could collect copyright assignment from all known contributors and then do this, but this would indeed be the pathological case. 7(e): This provision clarifies that refusal to grant trademark rights for a GPLv3'd covered work remains compatible with GPLv3. Again, some non-copyleft permissive licenses include such clauses.

[^9-12^]: 理论上，用户可以从所有已知的贡献者那里收集版权转让，然后这样做，但这确实是病态的情况。7(e)：该条款阐明拒绝授予 GPLv3 涵盖作品的商标权仍然与 GPLv3 兼容。同样，一些非 copyleft 许可包含此类条款。

In general, the types of additional requirements were those terms in regular use by other non-copyleft Free Software licenses that the FSF found unobjectionable. The specific details GPLv3's permitted additional requirements hat GPLv3 are as follows:

一般来说，附加要求的类型是 FSF 认为无异议的其他非 copyleft 自由软件许可证经常使用的条款。GPLv3允许的附加要求 GPLv3的具体细节如下：

7(a): This provision allows alternative "disclaimer of warranty" forms. Copyright holders can disclaim warranty or limit liability differently from the terms as provided under GPLv3 15--16. Drafters included this permission to advance the internationalization goals of GPLv3; international treaties lack adequate harmonization for laws regarding warranty and disclaimer.

7(a)：该条款允许使用替代的“保证免责声明”形式。版权所有者可以放弃保证或限制与 GPLv3 第15-16条下提供的条款不同的责任。起草者包括此许可以推进 GPLv3 的国际化目标； 国际条约缺乏关于保证和免责声明的法律的充分协调。

7(b): This provision allows alternative requirements for preservation of appropriate legal notices. GPLv3 permits additional requirements regarding preservation of legal notices, including on output from exe- cution of covered works. Preserved information can include information about the origins of the code or alterations of the code.

7(b)：本条款允许对适当的法律声明进行保存的替代要求。GPLv3 允许关于保存法律声明的额外要求，包括关于执行涵盖作品的输出。保留的信息可以包括有关代码来源或代码更改的信息。

7(c): This provision allows prohibition of misrepresentation of original material. The provision yields com- patibility with non-copyleft Free Software licenses that require marking of modified versions in "rea- sonable"ways which differ from GPL's own precise marking requirements.

7(c)：该条款允许禁止对原始材料进行虚假陈述。该条款与非 copyleft 自由软件许可证兼容，这些许可证要求以“合理”的方式标记修改版本，这与 GPL 自己的精确标记要求不同。

7(d): This provision allows limitations on the use of names of licensor for publicity purposes. This provision also yields additional compatibility with non-copyleft Free Software licenses that prohibit the use of the licensor's name on unmodified versions (or other prohibitions on advertising rights). The third clause of the [3-Clause BSD License,](http://opensource.org/licenses/BSD-3-Clause) for example, long considered de-facto compatible with GPLv2 anyway, is via this clause unequivocally compatible with GPLv3. However, [this clause *does not* make](https://www.gnu.org/licenses/license-list.html#OriginalBSD) [GPL compatible with the old BSD advertising clause](https://www.gnu.org/licenses/license-list.html#OriginalBSD) that the FSF [long ago identified as problematic.](https://www.gnu.org/philosophy/bsd.html)

7(d)：该条款允许限制出于宣传目的使用许可方名称。该规定还与非 copyleft 自由软件许可证产生了额外的兼容性，这些许可证禁止在未修改的版本上使用许可方的名称（或其他广告权禁令）。例如，3 条款 BSD 许可证的第3条，长期以来一直被认为事实上与 GPLv2 兼容，通过该条款明确兼容 GPLv3。然而，该条款并没有使 GPL 与 FSF 很久以前认为有问题的旧 BSD 广告条款兼容。

7(f): This provision allows indemnification requirements of authors and licensors. The FSF specifically designed this clause to achieve GPLv3 compatibility for the [Apache Software License, Version 2.0.](http://www.apache.org/licenses/LICENSE-2.0.html)

7(f)：该条款允许作者和许可人提出赔偿要求。FSF 专门设计了此条款以实现 Apache 软件许可证版本 2.0 的 GPLv3 兼容性。

During the GPLv3 drafting process, some questioned the necessity of GPLv3 7; those critics suggested that it creates complexity that did not previously exist. However, by the time of GPLv3's drafting, many existing GPLv2'd software packages already combined with various non-copylefted Free Software licensed code that carried such additional terms. Therefore, GPLv3 7 is rationalized existing practices of those package authors and modifiers, since it sets clear guidelines regarding the removal and addition of these additional terms. With its carefully limited list of allowed additional requirements, GPLv3 7 accomplishes additional objectives as well, since it permits the expansion of the base of code available for GPL developers, while also encouraging useful experimentation with requirements the GPLv3 does not include by default.

在 GPLv3 起草过程中，有人质疑 GPLv3 第7条的必要性； 这些批评者认为，它造成了以前不存在的复杂性。然而，在 GPLv3 起草之时，许多现有的 GPLv2 软件包已经与各种非 copyleft 自由软件许可代码相结合，这些代码带有此类附加条款。因此，GPLv3 第7条合理化了这些软件包作者和修改者的现有做法，因为它为删除和添加这些附加条款设定了明确的指导方针。GPLv3 第7条仔细限制了允许的附加要求列表，还实现了其他目标，因为它允许扩展 GPL 开发人员可用的代码基础，同时还鼓励对 GPLv3 默认不包含的要求进行有用的实验。

However, any other non-permissive additional terms apart from those stated above are considered "fur- ther" restrictions which [GPLv3 10](#gplv3-10-explicit-downstream-license) prohibits. Furthermore, as a compliance matter, if you add additional terms in accordance with GPLv3 7, you must ensure that the terms are placed in the relevant source files or provide a conspicuous notice about where to find the additional terms.

但是，除上述条款之外的任何其他非许可附加条款均被视为 GPLv3 第10条禁止的“进一步”限制。此外，作为合规性事项，如果您根据 GPLv3 第7条添加附加条款，您必须确保将这些条款放在相关源文件中或提供关于在哪里可以找到附加条款的显着通知。

### GPLv3 §8: A Lighter Termination

### 9.11 GPLv3 第8条：更轻松的终止

GPLv2 provided for automatic termination of the rights of a person who copied, modified, sublicensed, or distributed a work in violation of the license. Automatic termination can be too harsh for those who have committed an inadvertent violation, particularly in cases involving distribution of large collections of software having numerous copyright holders. A violator who resumes compliance with GPLv2 technically needs to obtain forgiveness from all copyright holders, and even contacting them all might be impossible.

GPLv2 规定自动终止违反许可证复制、修改、再许可或分发作品的人的权利。自动终止对于那些无意中违规的人来说可能过于严厉，尤其是在涉及分发拥有众多版权所有者的大量软件的情况下。恢复遵守 GPLv2 的违规者在技术上需要获得所有版权所有者的原谅，甚至连联系他们都可能是不可能的。

GPLv3 8 now grants opportunities for provisional and permanent reinstatement of rights. The termi- nation procedure provides a limited opportunity to cure license violations. If a licensee has committed a first-time violation of the GPL with respect to a given copyright holder, but the licensee cures the violation within 30 days following receipt of notice of the violation, then any of the licensee's GPL rights that have been terminated by the copyright holder are "automatically reinstated".

GPLv3 第8条现在授予临时和永久恢复权利的机会。终止程序提供了有限的机会来解决许可证违规问题。如果被许可人首次违反与给定版权所有者有关的 GPL，但被许可人在收到违规通知后 30 天内纠正了违规行为，则被许可人的任何已被终止的 GPL 权利 版权所有者“自动恢复原状”。

Finally, if a licensee violates the GPL, a contributor may terminate any patent licenses that it granted under GPLv3 *§*11, in addition to any copyright permissions the contributor granted to the licensee.

最后，如果被许可人违反 GPL，贡献者可以终止其根据 GPLv3 第11条授予的任何专利许可，以及贡献者授予被许可人的任何版权许可。

### GPLv3 §9: Acceptance

### 9.12 GPLv3 第9条：接受

GPLv3 9 means what it says: mere receipt or execution of code neither requires nor signifies contractual acceptance under the GPL. Speaking more broadly, GPLv3 is intentionally structured as a unilateral grant of copyright permissions, the basic operation of which exists outside of any law of contract. Whether and when a contractual relationship is formed between licensor and licensee under local law do not necessarily matter to the working of the license.

代码既不需要也不表示 GPL 下的合同接受。更广泛地说，GPLv3 被有意构建为单方面授予版权许可，其基本操作存在于任何合同法之外。根据当地法律，许可人和被许可人之间是否以及何时形成合同关系不一定对许可的运作有影响。

### GPLv3 §10: Explicit Downstream License

### 9.13 GPLv3 第10条：显式下游许可

GPLv3 10 is a generally straightforward section that ensures that everyone downstream receives licenses from all copyright holders. Each time you redistribute a GPL'd program, the recipient automatically receives a license, under the terms of GPL, from every upstream licensor whose copyrighted material is present in the work you redistribute. You could think of this as creating a three-dimensional rather than linear flow of license rights. Every recipient of the work is "in privity," or is directly receiving a license from every licensor. This mechanism of automatic downstream licensing is central to copyleft's function. Every licensor in- dependently grants licenses, and every licensor independently terminates the license on violation. Parties further downstream from the infringing party remain licensed, so long as they don't themselves commit infringing actions. Their licenses come directly from all the upstream copyright holders, and are not depen- dent on the license of the breaching party who distributed to them. For the same reason, an infringer who acquires another copy of the program has not thereby acquired any new license rights: once any upstream licensor of that program has terminated the license for breach of its terms, no new automatic license will issue to the recipient just by acquiring another copy[^9-13^]

GPLv3 第10条通常是一个简单明了的部分，可确保下游的每个人都从所有版权所有者那里获得许可。每次您重新分发 GPL 程序时，接收者都会根据 GPL 的条款自动从每个上游许可人那里收到一份许可，其受版权保护的材料出现在您重新分配的工作。您可以将其视为创建三维而非线性的许可权流。作品的每个接收者都是“私密的”，或者直接从每个许可人那里获得许可。这种自动下游许可机制是 Copyleft 功能的核心。每个许可人独立地授予许可，并且每个许可人在违反时独立地终止许可。侵权方下游的各方仍然获得许可，只要他们自己不实施侵权行为。他们的许可直接来自所有上游版权所有者，不依赖于向他们分发的违约方的许可。出于同样的原因，获得该程序的另一个副本的侵权者并没有因此获得任何新的许可权：一旦该程序的任何上游许可人因违反其条款而终止许可，则不会有新的自动许可只需获取另一份副本即可发送给收件人[^9-13^]。

[^9-13^]: Footnote 3 also applies here in discussion of GPLv3 just as it did in discussion of GPLv2.

[^9-13^]: 脚注 3 也适用于 GPLv3 的讨论，就像它在 GPLv2 的讨论中一样。

Meanwhile, one specific addition in GPLv3 here in GPLv3 10 deserves special mention. Specifically, GPLv3 removed the words "at no charge" from GPLv2 2(b) (which, BTW, became GPLv3 5(b)) because it contributed to a misconception that the GPL did not permit charging for distribution of copies. The purpose of the "at no charge" wording was to prevent attempts to collect royalties from third parties. The removal of these words created the danger that the imposition of licensing fees would no longer be seen as a license violation. Therefore, GPLv3 10 adds a new explicit prohibition on imposition of licensing fees or royalties. This section is an appropriate place for such a clause, since it is a specific consequence of the general requirement that no further restrictions be imposed on downstream recipients of GPL-covered code.

同时，GPLv3 第10条中 GPLv3 中的一个特定添加值得特别提及。具体来说，GPLv3 从 GPLv2 2(b)（顺便说一句，后来变成了 GPLv3 5(b)）中删除了“免费”一词，因为它造成了一种误解，即 GPL 不允许对副本的分发收费。“不收费”措辞的目的是防止试图从第三方收取版税。删除这些词会产生危险，即征收许可费将不再被视为违反许可。因此，GPLv3 第10条新增了一项明确禁止征收许可费或版税的规定。本节是此类条款的适当位置，因为它是一般要求的特定结果，即不对 GPL 代码的下游接收者施加进一步的限制。

### GPLv3 §11: Explicit Patent Licensing

### 9.14 GPLv3 第11条：显式专利许可

Software patenting is a harmful and unjust policy, and should be abolished; recent experience makes this all the more evident. Since many countries grant patents that can apply to and prohibit software packages, in various guises and to varying degrees, GPLv3 seeks to protect the users of GPL-covered programs from those patents, while at the same time making it feasible for patent holders to contribute to and distribute GPL-covered programs as long as they do not attack the users of those programs.

软件专利是一种有害和不公正的政策，应该废除；最近的经验使这一点更加明显。由于许多国家/地区以各种形式和不同程度授予可以应用于和禁止软件包的专利，因此 GPLv3 旨在保护受 GPL 保护的程序的用户免受这些专利的影响，同时使专利持有人能够贡献自己的力量 分发 GPL 程序，只要它们不攻击这些程序的用户。

It is generally understood that GPLv2 implies some limits on a licensee's power to assert patent claims against the use of GPL-covered works. However, the patent licensing practice that GPLv2 7 (corresponding to GPLv3 12) is designed to prevent is only one of several ways in which software patents threaten to make free programs non-free and to prevent users from exercising their rights under the GPL. GPLv3 takes a more comprehensive approach to combating the danger of patents.

人们普遍认为，GPLv2 意味着对被许可人针对 GPL 保护作品的使用提出专利索赔的权力的一些限制。然而，GPLv2 第7条（对应于 GPLv3 第12条）旨在防止的专利许可实践只是软件专利威胁使免费程序成为非自由软件并阻止用户行使 GPL 下的权利的几种方式之一。GPLv3 采用更全面的方法来对抗专利的危险。

GPLv2 7 has seen some success in deterring conduct that would otherwise result in denial of full downstream enjoyment of GPL rights, and thus it is preserved in GPLv3 12. Experience has shown that more is necessary, however, to ensure adequate community safety where companies act in concert to heighten the anticompetitive use of patents that they hold or license.

GPLv2 第7条在阻止可能导致下游无法完全享受 GPL 权利的行为方面取得了一些成功，因此它在 GPLv3 第12条中得到了保留。然而，经验表明，在公司采取行动的地方，还需要做更多的工作来确保充分的社区安全 共同加强对他们持有或许可的专利的反竞争使用。

Therefore, GPLv3 is designed to reduce the patent risks that distort and threaten the activities of users who make, run, modify and share Free Software. At the same time, GPLv3 gives favorable consideration to practical goals such as certainty and administrability for patent holders that participate in distribution and development of GPL-covered software. GPLv3's policy requires each such patent holder to provide appropriate levels of patent assurance to users, according to the nature of the patent holder's relationship to the program.

因此，GPLv3 旨在降低扭曲和威胁制作、运行、修改和共享自由软件的用户的活动的专利风险。同时，GPLv3 对参与 GPL 软件分发和开发的专利持有人的确定性和可管理性等实际目标给予了有利的考虑。GPLv3 的政策要求每个此类专利持有人根据专利持有人与程序的关系性质，向用户提供适当级别的专利保证。

In general, GPLv3 provides for two classes of patent commitments:

Grant of license to claims in contributor versions: GPLv3 11 introduces an affirmative grant of rights to patent claims by those who contribute code to GPL'd programs. The intent is to prevent parties from aggressively asserting patents against users of code those parties have themselves modified --- in theory preventing betrayal by "insiders" of the copyleft community. A contributor's patent claims necessarily infringed by the version of the program created by the incorporation of its modifications are licensed to all subsequent users and modifiers of the program, or programs based on the program. No patent claims only infringed by subsequent modifications by other parties are thus licensed. Patent claims acquired after the making of the "contributor version" necessarily infringed by that version are also licensed by this provision at the time of their acquisition or perfection.

一般来说，GPLv3 提供两类专利承诺：

授予贡献者版本中声明的许可：GPLv3 第11条引入了对那些为 GPL 程序贡献代码的人的专利声明的肯定性授予权利。这样做的目的是防止各方针对他们自己修改的代码的用户积极主张专利——理论上防止 copyleft 社区的“内部人士”背叛。贡献者的专利声明必然会受到其修改的合并所创建的程序版本的侵犯，该版本将许可给该程序或基于该程序的程序的所有后续用户和修改者。仅因其他方的后续修改而侵犯的专利权利要求不会因此获得许可。在制作“贡献者版本”后获得的专利权利要求必然受到该版本的侵犯，在其获得或完善时也根据本条款获得许可。

Prohibition of enforcement of patent claims against those to whom you distribute: GPLv3 10 makes explicit that licensees who directly distribute may not make demands for acceptance of patent licenses or payment of patent royalties from distribution recipients. This provision establishes a uniform rule of patent exhaustion with respect to GPL'd programs regardless of the domestic patent law in any particular system or locale.

禁止对您分发的人执行专利索赔：GPLv3 第10条明确规定直接分发的被许可人不得要求接受专利许可或支付分发接收者的专利使用费。无论任何特定系统或地区的国内专利法如何，该条款都针对 GPL 程序建立了统一的专利用尽规则。

The following two subsections discuss in order each of the above mentioned classes of patent commitments.

以下两小节按顺序讨论上述每一类专利承诺。

#### 9.14.1 The Contributor's Explicit Patent License

#### 9.14.1 贡献者的显示专利许可

Specifically, the ideal might have been for GPLv3 to feature a patent license grant triggered by all acts of distribution of GPLv3-covered works. The FSF considered it during the GPLv3 drafting process, but many patent-holding companies objected to this policy. They have made two objections: (1) the far-reaching impact of the patent license grant on the patent holder is disproportionate to the act of merely distributing code without modification or transformation, and (2) it is unreasonable to expect an owner of vast patent assets to exercise requisite diligence in reviewing all the GPL-covered software that it provides to others. Some expressed particular concern about the consequences of "inadvertent" distribution.

具体来说，理想的情况可能是 GPLv3 具有由 GPLv3 涵盖作品的所有分发行为触发的专利许可授予。FSF 在 GPLv3 起草过程中考虑过这一点，但许多专利持有公司反对这一政策。他们提出了两个反对意见：（1）授予专利许可对专利持有人的深远影响与仅分发代码而不进行修改或改造的行为不相称，（2）期望拥有大量专利的所有者是不合理的专利资产，以尽必要的努力审查其提供给他人的所有 GPL 软件。一些人对“无意”分发的后果表示特别关注。

The argument that the impact of the patent license grant would be "disproportionate", that is to say unfair, is not valid. Since software patents are weapons that no one should have, and using them for aggression against free software developers is an egregious act (thus preventing that act cannot be unfair).

专利许可授予的影响将“不成比例”，即不公平的论点是无效的。由于软件专利是任何人都不应该拥有的武器，使用它们来攻击自由软件开发者是一种恶劣的行为（因此阻止这种行为是不公平的）。

However, the second argument seems valid in a practical sense. A typical GNU/Linux distribution includes thousands of programs. It would be quite difficult for a re-distributor with a large patent portfolio to review all those programs against that portfolio every time it receives and passes on a new version of the distribution. Moreover, this question raises a strategic issue. If the GPLv3 patent license requirements convince patent-holding companies to remain outside the distribution path of all GPL-covered software, then these requirements, no matter how strong, will cover few patents.

然而，第二个论点在实际意义上似乎是有效的。典型的 GNU/Linux 发行版包括数千个程序。对于拥有大量专利组合的再分发者来说，每次收到并传递新版本的分发时，都很难根据该组合审查所有这些程序。此外，这个问题提出了一个战略问题。如果 GPLv3 专利许可要求说服专利持有公司置身于所有受 GPL 保护的软件的分发路径之外，那么这些要求，无论多么强烈，都将覆盖很少的专利。

GPLv3 therefore makes a partial concession which would lead these companies to feel secure in doing the distribution themselves. GPLv3 11 applies only to those distributors that have modified the program. The other changes we have made in sections 10 and 11 provide strengthened defenses against patent assertion and compensate partly for this concession.

因此，GPLv3 做出了部分让步，这将使这些公司在自己进行分发时感到安全。GPLv3 第11条仅适用于修改了程序的发行商。我们在第10条和第11条中所做的其他更改提供了针对专利主张的强化抗辩，并部分补偿了这种让步。

Therefore, GPLv3 11 introduces the terms "contributor", "contributor version", and "essential patent claims", which are used in the GPLv3 11 3. Viewed from the perspective of a recipient of the Program, contributors include all the copyright holders for the Program, other than copyright holders of material originally licensed under non-GPL terms and later incorporated into a GPL-covered work. The contributors are therefore the initial GPLv3 licensors of the Program and all subsequent upstream licensors who convey, under the terms of GPLv3 5, modified covered works. Thus, the "contributor version" includes the material the contributor has copied from the upstream version that the contributor has modified. GPLv3 11 3 does not apply to those that redistribute the program without change.[^9-14^] In other words, the "contributor version" includes not just the material added or altered by the contributor, but also the pre-existing material the contributor copied from the upstream version and retained in the modified version. (GPLv3's usage of "contributor" and "contribution" should not be confused with the various other ways in which those terms are used in certain other free software licenses.[^9-15^])

因此，GPLv3 第11条第3款引入了 GPLv3 第11条中使用的术语“贡献者”、“贡献者版本”和“必要的专利权利要求”。从程序接收者的角度来看，贡献者包括程序所有版权持有者，最初根据非 GPL 条款许可并后来合并到 GPL 作品中的材料的版权所有者除外。因此，贡献者是本程序的初始 GPLv3 许可人，以及根据 GPLv3 第5条传送修改后的涵盖作品的所有后续上游许可人。因此，“贡献者版本”包括贡献者从贡献者已修改的上游版本复制的材料。GPLv3 第11条第3款不适用于那些不加改动地重新发布程序的人[^9-14^]。换句话说，“贡献者版本”不仅包括贡献者添加或更改的材料，还包括贡献者从中复制的现有材料上游版本并保留在修改版本中。（GPLv3 对“贡献者”和“贡献”的使用不应与这些术语在某些其他自由软件许可中的各种其他使用方式相混淆[^9-15^]。）

Some details of the "essential patent claims" definition deserve special mention. "Essential patent claims", for a given party, are a subset of the claims "owned or controlled" by the party. They do include sublicensable claims that have been licensed to the contributor by a third party.[^9-16^] Most commercial patent license agreements that permit sublicensing do so under restrictive terms that are inconsistent with the requirements of the GPL. For example, some patent licenses allow the patent licensee to sublicense but require collection of royalties from any sublicensees. The patent licensee could not distribute a GPL-covered program and grant the recipient a patent sublicense for the program without violating section 12 of GPLv3.[^9-17^] In rare cases, however, a conveying party can freely grant patent sublicenses to downstream recipients without violating the GPL.

“必要专利权利要求”定义的一些细节值得特别提及。对于给定的一方，“必要专利权利要求”是该方“拥有或控制”的权利要求的子集。它们确实包括已由第三方许可给贡献者的可再许可声明。[^9-16^] 大多数允许再许可的商业专利许可协议都是在与 GPL 要求不一致的限制性条款下进行的。例如，一些专利许可允许专利被许可人进行再许可，但要求从任何被再许可人处收取使用费。专利被许可人不能在不违反 GPLv3 第12条的情况下分发受 GPL 保护的程序并向接收者授予该程序的专利从属许可[^9-17^] 然而，在极少数情况下，传送方可以在不违反 GPLv3 的情况下自由向下游接收者授予专利从属许可 GPL。

[^9-14^]: An implied patent license from the distributor, however, often arises. See [6]in this tutorial

[^9-15^]: Cf., e.g., Apache License, version 2.0, section 1; Eclipse Public License, version 1.0, section 1; Mozilla Public License, v[]{#_bookmark138 .anchor}ersion 1.1, section 1.1.

[^9-16^]: This issue is typically handled in other software freedom licenses having patent licensing provisions by use of the unhelpful []{#_bookmark139 .anchor}term "licensable," which is either left undefined or is given an ambiguous definition.

[^9-17^]: GPLv3 also provides an example in section 12 that makes this point clear.

[^9-14^]: 但是，经常会出现来自分销商的默示专利许可。参见本教程中的 6

[^9-15^]: Cf.，例如，Apache 许可证，版本 2.0，第 1 节； Eclipse 公共许可证，版本 1.0，第 1 节； Mozilla 公共许可证，v[]{#_bookmark138 .anchor}版本 1.1，第 1.1 节。

[^9-16^]: 该问题通常在其他软件自由许可中处理，该许可通过使用无用的术语“可授权”，该术语“可授权”，该术语要么不定义，要么给出了模棱两可的定义。

[^9-17^]: GPLv3 在12条也提供了一个例子明确这一点。

Additionally, "essential patent claims" are those patents "that would be infringed by some manner, permitted by this License, of making, using, or selling the work". This intends to make clear that a patent claim is "essential" if some mode of usage would infringe that claim, even if there are other modes of usage that would not infringe.

此外，“基本专利权利要求”是那些“在本许可证允许的情况下，以某种方式侵犯制作、使用或销售作品的专利”。这旨在表明，如果某种使用方式会侵犯专利权利要求，则该专利权利要求是“必要的”，即使存在其他不会侵权的使用方式也是如此。

Finally, "essential patent claims . . . do not include claims that would be infringed only as a consequence of further modification of the work." The set of essential patent claims licensed is fixed by the particular version of the work that was contributed. The claim set cannot expand as a work is further modified downstream. (If it could, then any software patent claim would be included, since any software patent claim can be infringed by some further modification of the work.)[^9-18^]

最后，“必要的专利声明……不包括仅因进一步修改作品而被侵权的索赔。” 许可的基本专利权利要求集由所贡献作品的特定版本确定。随着作品在下游进一步修改，声明集无法扩展。（如果可以，那么将包括任何软件专利声明，因为任何软件专利声明都可能因对作品的进一步修改而受到侵犯。）[^9-18^]

[^9-18^]:　However, “the work” should not be understood to be restricted to a particular mechanical affixation of, or medium for　distributing, a program, where the same program might be provided in other forms or in other ways that may be captured by　other patent claims held by the contributor．

[^9-18^]: 然而，“作品”不应理解为仅限于分发程序的特定机械粘连或介质，在该程序中，可以由贡献者以其他形式或其他专利索赔捕获的其他形式或其他方式提供相同的程序。

Ideally, this contributor patent policy will result in fairly frequent licensing of patent claims by contrib- utors. A contributor is charged with awareness of the fact that it has modified a work and provided it to others; no act of contribution should be treated as inadvertent. GPLv3's rule also requires no more work, for a contributor, than the weaker rule proposed by the patent holders. Under their rule, the contributor must always compare the entire work against its patent portfolio to determine whether the combination of the modifications with the remainder of the work cause it to read on any of the contributor's patent claims.

理想情况下，这种贡献者专利政策将导致贡献者相当频繁地许可专利权利要求。贡献者有责任意识到自己修改了作品并将其提供给他人；任何捐助行为都不应被视为无意。对于贡献者来说，GPLv3 的规则也不需要比专利持有人提出的较弱的规则更多的工作。根据他们的规定，贡献者必须始终将整个作品与其专利组合进行比较，以确定修改与作品其余部分的组合是否会导致其阅读贡献者的任何专利声明。

Finally, GPLv3's explicit patent license for contributors has an interesting and useful side effect. When a company with a large number of such claims acquires the program's modifier, all claims held or thereafter acquired by the purchaser are automatically licensed under this provision. For example, Microsoft's acqui- sition of Nokia resulted in the automatic licensing of all Microsoft patent claims now or hereafter acquired which read on any contributor version of any GPLv3 program ever modified by Nokia.

最后，GPLv3 对贡献者的明确专利许可有一个有趣且有用的副作用。当拥有大量此类权利要求的公司获得该程序的修改器时，购买者持有或之后获得的所有权利要求将根据本条款自动获得许可。例如，微软对诺基亚的收购导致微软现在或以后获得的所有专利权利要求的自动许可，这些权利要求阅读诺基亚曾经修改过的任何 GPLv3 程序的任何贡献者版本。

#### 9.14.2 Conveyors' Patent Licensing

#### 9.14.2 专利许可的传递

The remaining patent licensing in GPLv3 deals with patent licenses that are granted by conveyance. The licensing is not as complete or far reaching as the contributor patent licenses discussed in the preceding section.

GPLv3 中剩余的专利许可涉及通过转让授予的专利许可。许可不像上一节中讨论的贡献者专利许可那样完整或广泛。

The term "patent license," as used in GPLv3 11 4--6, is not meant to be confined to agreements formally identified or classified as patent licenses. GPLv3 11 3 makes this clear by defining "patent license," for purposes of the subsequent three paragraphs, as "any express agreement or commitment, however denomi- nated, not to enforce a patent (such as an express permission to practice a patent or covenant not to sue for patent infringement)"

GPLv3 第11条第4-6款中使用的术语“专利许可”并不意味着仅限于正式确定或归类为专利许可的协议。GPLv3 第11条第3款通过为后续三段的目的将“专利许可”定义为“任何明确的协议或承诺，无论名称如何，不强制执行专利（例如明确许可实施专利或 承诺不起诉专利侵权）”

GPLv3 11 5 is commonly called GPLv3's downstream shielding provision. It responds particularly to the problem of exclusive deals between patent holders and distributors, which threaten to distort the free software distribution system in a manner adverse to developers and users. The fundamental idea is to make a trade-off between assuring a patent license for downstream and making (possibly patent-encumbered) CCS publicly available.

GPLv3 第11条第5款通常称为 GPLv3 的下游屏蔽条款。它特别针对专利持有人和分销商之间的排他性交易问题作出回应，这些交易有可能以对开发者和用户不利的方式扭曲自由软件分发系统。基本思想是在确保下游专利许可和公开提供（可能受专利保护的）CCS 之间做出权衡。

Simply put, in nearly all cases in which the "knowingly relying" test is met, the patent license will indeed not be sublicensable or generally available to all on free terms. If, on the other hand, the patent license is generally available under terms consistent with the requirements of the GPL, the distributor is automatically in compliance, because the patent license has already been extended to all downstream recipients. Finally, if the patent license is sublicensable on GPL-consistent terms, the distributor may choose to grant sublicenses to downstream recipients instead of causing the CCS to be publicly available. (In such a case, if the distributor is also a contributor, it will already have granted a patent sublicense anyway, and so it need not do anything further to comply with the third paragraph.)

简而言之，在几乎所有满足“故意依赖”测试的情况下，专利许可确实不可再许可或普遍免费提供给所有人。另一方面，如果专利许可在符合 GPL 要求的条款下普遍可用，则分销商自动遵守，因为专利许可已经扩展到所有下游接收者。最后，如果专利许可可以按照与 GPL 一致的条款进行再许可，则分发者可以选择向下游接收者授予再许可，而不是让 CCS 公开可用。（在这种情况下，如果分销商也是贡献者，那么无论如何它已经授予了专利从属许可，因此它不需要做任何进一步的事情来遵守第三段。）

Admittedly, public disclosure of CCS is not necessarily required by other sections of the GPL, and the FSF in drafting GPLv3 did not necessarily wish to impose a general requirement to make source code available to all, which has never been a GPL condition. However, many vendors who produce products that include copylefted software, and who are most likely to be affected by the downstream shielding provision, lobbied for the addition of the source code availability option, so it remains.

诚然，CCS 的公开披露不一定是 GPL 的其他部分所要求的，并且 FSF 在起草 GPLv3 时并不一定希望强加一个通用的要求，即向所有人提供源代码，这从来都不是 GPL 的条件。然而，许多生产包含 copylefted 软件的产品的供应商，以及最有可能受到下游屏蔽条款影响的供应商，游说添加源代码可用性选项，因此它仍然存在。

^18^[]{#_bookmark141 .anchor}However, "the work" should not be understood to be restricted to a particular mechanical affixation of, or medium for distributing, a program, where the same program might be provided in other forms or in other ways that may be captured by other patent claims held by the contributor.

Meanwhile, two specific alternatives to the source code availability option are also available. The dis- tributor may comply by disclaiming the patent license it has been granted for the conveyed work, or by arranging to extend the patent license to downstream recipients.[^9-19^] The GPL is intended to permit private distribution as well as public distribution, and the addition of these options ensures that this remains the case, even though it remains likely that distributors in this situation will usually choose the source code availability option.

同时，还提供了源代码可用性选项的两个特定替代方案。发行商可以通过放弃已授予其所传送作品的专利许可，或通过安排将专利许可扩展到下游接收者来遵守。[^9-19^] GPL 旨在允许私人发行和公共发行，并且这些选项的添加确保了这种情况仍然存在，即使在这种情况下分销商仍然可能通常会选择源代码可用性选项。

Note that GPLv3 11 5 is activated only if the CCS is not already otherwise publicly available. (Most often it will, in fact, already be available on some network server operated by a third party.) Even if it is not already available, the option to "cause the Corresponding Source to be so available" can then be satisfied by verifying that a third party has acted to make it available. That is to say, the affected distributor need not itself host the CCS to take advantage of the source code availability option. This subtlety may help the distributor avoid certain peculiar assumptions of liability.

请注意，仅当 CCS 尚未以其他方式公开可用时，GPLv3 第11条第5款才会被激活。（事实上，大多数情况下，它已经在第三方运营的某些网络服务器上可用。）即使它还不可用，“使相应的源如此可用”的选项也可以通过验证来满足第三方已采取行动使其可用。也就是说，受影响的分销商不需要自己托管 CCS 来利用源代码可用性选项。这种微妙之处可能有助于分销商避免某些特殊的责任假设。

Note that GPLv3 11 6--7 are designed to stop distributors from colluding with third parties to offer selective patent protection. GPLv3 is designed to ensure that all users receive the same rights; arrangements that circumvent this make a mockery of free software, and we must do everything in our power to stop them. First, GPLv3 11 6 states that any license that protects some recipients of GPL'd software must be extended to all recipients of the software. If conveyors arrange to provide patent protection to some of the people who get the software from you, that protection is automatically extended to everyone who receives the software, no matter how they get it.

请注意，GPLv3 第11条第6–7款旨在阻止分销商与第三方串通以提供选择性专利保护。GPLv3 旨在确保所有用户获得相同的权利； 规避这一点的安排是对自由软件的嘲弄，我们必须竭尽全力阻止它们。首先，GPLv3 第11条第6款声明任何保护 GPL 软件的某些接收者的许可证必须扩展到该软件的所有接收者。如果传送者安排向从您那里获得软件的某些人提供专利保护，则该保护会自动扩展到接收到软件的每个人，无论他们如何获得它。

Second, GPLv3 11 7 prohibits anyone who made such an agreement from distributing software released under GPLv3. Conveyors are prohibited from distributing software under GPLv3 if the conveyor makes an agreement of that nature in the future.

其次，GPLv3 第11条第7款禁止任何签订此类协议的人分发根据 GPLv3 发布的软件。如果传送者将来达成此类性质的协议，则禁止传送者分发 GPLv3 下的软件。

The date in GPLv3 11 7 likely seems arbitrary to those who did not follow the GPLv3 drafting process. This issue was hotly debated during the drafting of GPLv3, but ultimately one specific deal of this type --- a deal between Microsoft and Novell for Microsoft to provide so-called "coupons" to Microsoft customers to redeem for copies of Novell's GNU/Linux distribution with a Microsoft patent license -- was designed to be excluded.

对于那些不遵循 GPLv3 起草过程的人来说，GPLv3 第11条第7款中的日期可能看起来很武断。这个问题在 GPLv3 的起草过程中引起了激烈的争论，但最终达成了一项此类具体交易——微软和 Novell 之间的一项交易，微软向微软客户提供所谓的“优惠券”，以兑换 Novell 的 GNU/Linux 发行版副本 微软专利许可——被设计为被排除在外。

The main reason for this was a tactical decision by the FSF. FSF believed they can do more to protect the community by allowing Novell to use software under GPLv3 than by forbidding it to do so. This is because of paragraph 6 of section 11 (corresponding to paragraph 4 in Draft 3). It will apply, under the Microsoft/Novell deal, because of the coupons that Microsoft has acquired that essentially commit it to participate in the distribution of the Novell SLES GNU/Linux system.

主要原因是 FSF 的战术决定。FSF 认为，与禁止 Novell 使用 GPLv3 软件相比，他们可以通过允许 Novell 使用 GPLv3 软件来保护社区。这是因为第11条第6款（对应草案3中的第4款）。根据 Microsoft/Novell 协议，它将适用，因为 Microsoft 获得的优惠券实质上承诺参与 Novell SLES GNU/Linux 系统的分发。

The FSF also gave a secondary reason: to avoid affecting other kinds of agreements for other kinds of activities. While GPLv3 sought to distinguish pernicious deals of the Microsoft/Novell type from business conduct that is not particularly harmful, the FSF also did not assume success in that drafting, and thus there remained some risk that other unchangeable past agreements could fall within the scope of GPLv3 11 7. In future deals, distributors engaging in ordinary business practices can structure the agreements so that they do not fall under GPLv3 *§*11*¶*7.

FSF 还给出了一个次要原因：避免影响其他类型活动的其他类型协议。虽然 GPLv3 试图将 Microsoft/Novell 类型的有害交易与不是特别有害的商业行为区分开来，但 FSF 也没有假设在该起草中取得成功，因此仍然存在一些风险，即其他不可更改的过去协议可能属于 GPLv3 的范围 GPLv3 第11条第7款。在未来的交易中，从事普通商业行为的分销商可以构建协议，使其不属于 GPLv3 第11条第7款。

### GPLv3 §12: Familiar as GPLv2 §7

### 9.15 GPLv3 第12条：与GPLv2 第7条相似

GPLv2 12 remains almost completely unchanged from the text that appears in GPLv2 7. This is an important provision that ensures a catch-all to ensure that nothing "surprising" interferes with the continued conveyance safely under copyleft.

GPLv3 第12条 与 GPLv2 第7条中出现的文本几乎完全保持不变。这是一项重要的规定，确保包罗万象，确保没有任何“意外”干扰 copyleft 下的安全继续传输。

The wording in the first sentence of GPLv3 12 has been revised slightly to clarify that an agreement -- such as a litigation settlement agreement or a patent license agreement -- is one of the ways in which conditions may be "imposed" on a GPL licensee that may contradict the conditions of the GPL, but which do not excuse the licensee from compliance with those conditions. This change codifies the historical interpretation of GPLv2.

GPLv3 第12条第一句的措辞略有修改，以阐明协议（例如诉讼和解协议或专利许可协议）是可以对 GPL 被许可人“施加”条件的方式之一 与 GPL 的条件相矛盾，但不能成为被许可人不遵守这些条件的借口。此更改整理了 GPLv2 的历史解释。

GPLv3 removed the limited severability clause of GPLv2 7 as a matter of tactical judgment, believing that this is the best way to ensure that all provisions of the GPL will be upheld in court. GPLv3 also removed the final sentence of GPLv2 section 7, which the FSF consider to be unnecessary.

[^9-19^]: The latter option, if chosen, must be done "in a manner consistent with the requirements of this License"; for example, it is unavailable if extension of the patent license would result in a violation of GPLv3 *§*12.

[^9-19^]: 对于后者，如果选择了，必须符合“以符合本许可证的要求一致”；例如，如果延长专利许可导致违反 GPLv3 第12条。

GPLv3 作为战术判断删除了 GPLv2 第7条的有限可分割性条款，认为这是确保 GPL 所有条款在法庭上得到维护的最佳方式。GPLv3 还删除了 GPLv2 第 7 条的最后一句，FSF 认为这是不必要的。

### GPLv3 §13: The Great Affero Compromise

### 9.16 GPLv3 第13条：伟大的Affero妥协

The Affero GPL was written with the expectation that its additional requirement would be incorporated into the terms of GPLv3 itself. Many software freedom advocates, including some authors of this tutorial, advocated heavily for that, and fully expected it to happen.

Affero GPL 的编写期望将其附加要求纳入 GPLv3 本身的条款中。许多软件自由倡导者，包括本教程的一些作者，大力倡导这一点，并完全期待它的发生。

The FSF, however, chose not to include the Affero clause in GPLv3, due to what it called "irreconcilable views from different parts of the community". Many commercial users of Free Software were opposed to the inclusion of a mandatory Affero-like requirement in the body of GPLv3 itself. In fact, some wealthier companies even threatened to permanently fund forks of many FSF copyrighted-programs under GPLv2 if the Affero clause appeared in GPLv3.

然而，由于所谓的“来自社区不同部分的不可调和的观点”，FSF 选择不将 Affero 条款包含在 GPLv3 中。许多自由软件的商业用户反对在 GPLv3 本身的主体中包含强制性的类似 Affero 的要求。事实上，如果 Affero 条款出现在 GPLv3 中，一些更富有的公司甚至威胁要永久资助许多 GPLv2 下的 FSF 版权程序的分支。

Meanwhile, there was disagreement even among copyleft enthusiasts about the importance of the pro- vision. A coalition never formed, and ultimately the more powerful interests implicitly allied with the companies who deeply opposed the Affero clause such that the FSF felt the Affero clause would need its own license, but one compatible with GPLv3.

与此同时，甚至在 copyleft 爱好者中也对该条款的重要性存在分歧。一个联盟从未形成，最终更强大的利益集团与那些强烈反对 Affero 条款的公司暗中结盟，以至于 FSF 认为 Affero 条款需要自己的许可，但要与 GPLv3 兼容。

GPLv3 13 makes GPLv3 compatible with the AGPLv3, so that at least code can be shared between AGPLv3'd and GPLv3'd projects, even if the Affero clause does not automatically apply to all GPLv3'd works.

GPLv3 第13条使 GPLv3 与 AGPLv3 兼容，因此至少可以在 AGPLv3 和 GPLv3 项目之间共享代码，即使 Affero 条款不会自动适用于所有 GPLv3 作品。

Meanwhile, those who criticize the permission to link with code under the Affero GPL should recognize that most other free software licenses also permit such linking. In particular, when a combined work is made by linking GPLv3-covered code with AGPLv3-covered code, the copyleft on one part will not extend to the other part. In such combinations, the Affero requirement will apply only to the part originally brought into the combination under the Affero license. In theory, those who receive such a combination and do not wish to use code under the Affero requirement may remove the Affero-covered portion of the combination. (Admittedly, in practice, de-mingling of combined code can be technically difficult.)

人应该认识到，大多数其他自由软件许可证也允许此类链接。特别是，当通过将 GPLv3 覆盖的代码与 AGPLv3 覆盖的代码链接起来制作组合作品时，一部分的 copyleft 不会扩展到另一部分。在此类组合中，Affero 要求将仅适用于最初根据 Affero 许可引入组合的部分。理论上，那些收到此类组合并且不想根据 Affero 要求使用代码的人可以删除组合中 Affero 覆盖的部分。（诚然，在实践中，组合代码的去混合在技术上可能很困难。）

### GPLv3 §14: So, When's GPLv4?

### 9.17 GPLv3 第14条：那么GPLv4什么时候会出？

No substantive change has been made in section 14. The wording of the section has been revised slightly to make it clearer.

第 14 条未作实质性更改。该节的措辞已略作修改，以使其更加清晰。

It's unclear when the FSF might consider publishing GPLv4. However, this section makes it clear that the FSF is the sole authority who can decide such.

目前尚不清楚 FSF 何时会考虑发布 GPLv4。但是，本节明确表示 FSF 是唯一可以做出此类决定的机构。

The main addition to this section allows a third-party proxy to be appointed by contributors who wish someone else to make relicensing to new versions of GPL when they are released. This is a "halfway" point between using "-only" or "-or-later" by consolidating the decision-making on that issue to a single authority.

本节的主要新增内容允许贡献者指定第三方代理，这些贡献者希望其他人在发布新版本的 GPL 时重新授权。通过将该问题的决策整合到一个单一的权威机构，这是使用“仅”或“及后续”之间的“中间”点。

### GPLv3 §15--17: Warranty Disclaimers and Liability Limita- tion

### 9.18 GPLv3 第15——17条：免责声明与有限责任

No substantive changes have been made in sections 15 and 16.

第 15 和 16 条未作实质性修改。

Finally, the FSF shortened the section on "How to Apply These Terms to Your New Programs" to just the bare essentials.

最后，FSF 将“如何将这些条款应用于您的新程序”部分缩短为仅保留基本要素。

## CHAPTER 10 THE LESSER GPL

## 第10章 宽松GPL

As we have seen in our consideration of the GPL, its text is specifically designed to cover all possible derivative, modified and/or combined works under copyright law. Our goal in designing the GPL was to maximize its use of the controls of copyright law to maximize the number of works that were covered by GPL.

正如我们在考虑 GPL 时所看到的，它的文本是专门设计用于涵盖所有可能的衍生作品，修改和/或版权法下的组合作品。我们设计 GPL 的目标是为了最大限度地利用版权法来最大化地控制涵盖的作品数量。

However, while the strategic goal of software freedom is to bring as much Free Software into the world as possible, particular tactical considerations regarding software freedom dictate different means. Extending the copyleft effect as far as copyright law allows is not always the most prudent course in reaching the goal. In particular situations, even those of us with the goal of building a world where all published software is Free Software realize that full copyleft does not best serve us. The GNU Lesser General Public License ("GNU LGPL") was designed as a solution for such situations. The Lesser General Public License is sometimes described as a "weak copyleft" license, because code licensed under LGPL's terms can be combined with code under non-free licenses, and is sometimes used in that fashion.

然而，虽然软件自由的战略目标是尽可能多的把自由软件带给世界，特别是关于软件自由的战术考虑决定了不同的方式。在版权法允许的范围内扩大 copyleft 的效果并不始终是实现目标最谨慎的做法。 特殊情况下，甚至我们当中有些人的目标是建立一个世界所有发布的软件都是自由软件，实现完全的 copyleft 并不能最好地为我们服务。 GNU 宽松通用公共许可证(“GNU LGPL") 被设计为针对此类情况的解决方案。LGPL 有时被描述为“弱 copyleft” 许可，因为根据 LGPL 条款许可的代码可以与非自由许可下的代码，有时确实以这种方式使用。

### 10.1 The First LGPL'd Program

### 10.1 第一个采用LGPL许可的程序

The first example that FSF encountered where such altered tactics were needed was when work began on the GNU C Library. The GNU C Library would become (and today, now is) a drop-in replacement for existing C libraries. On a Unix-like operating system, C is the lingua franca and the C library is an essential component for all programs. It is extremely difficult to construct a program that will run with ease on a Unix-like operating system without making use of services provided by the C library --- even if the program is written in a language other than C. Effectively, all user application programs that run on any modern Unix-like system must make use of the C library.

FSF 遇到的第一个需要改变策略的例子是从 GNU C 库的工作开始时。 GNU C 库将成为（现在已经是）现有 C 的直接替代品库。 在类 Unix 操作系统上，C 是通用语言，C 库是所有程序的重要组成部分。 在类 Unix 操作系统上，不使用 C 库构建一个可以轻松运行的程序是非常困难的 —— 即使程序是用一种 C 语言之外的语言编写的。实际上，所有运行在任何现代类 Unix 系统上的程序都必须使用 C 库。

By the time work began on the GNU implementation of the C libraries, there were already many C libraries in existence from a variety of vendors. Every proprietary Unix vendor had one, and many third parties produced smaller versions for special purpose use. However, our goal was to create a C library that would provide equivalent functionality to these other C libraries on a Free Software operating system (which in fact happens today on modern GNU/Linux systems, which all use the GNU C Library).

当 C 库的 GNU 实现工作开始时，已经有来自各种供应商的许多 C 库。 每个专有的 Unix 供应商都有一个，还有许多第三方为特殊用途生产了较小的版本。 然而，我们的目标是在自由软件操作系统上创建一个于这些其他 C 库提供等效功能的 C 库（事实上如今在现代 GNU/Linux 系统上，它们都使用GNU C 库）。

Unlike existing GNU application software, however, the licensing implications of releasing the GNU C Library ("glibc") under the GPL were somewhat different. Applications released under the GPL would never themselves become part of proprietary software. However, if glibc were released under the GPL, it would require that any application distributed for the GNU/Linux platform be released under the GPL.

然而，与现有的 GNU 应用软件不同的是，在 GPL 许可证下发布 GNU C 库（“glibc”）的影响有些不同。 在 GPL 下发布的应用程序将永远不会自己成为专有软件的一部分。 然而，如果 glibc 是在 GPL 下发布的，它要求任何为 GNU/Linux 平台分发的应用程序在 GPL 下发布。

Since all applications on a Unix-like system depend on the C library, it means that they must link with that library to function on the system. In other words, all applications running on a Unix-like system must be combined with the C library to form a new whole work that is composed of the original application and the C library. Thus, if glibc were GPL'd, each and every application distributed for use on GNU/Linux would also need to be GPL'd, since to even function, such applications would need to be combined into larger works by linking with glibc.

由于 Unix 系统上的所有应用程序都依赖于 C 库，这意味着它们必须链接到该库才能在系统上运行。换句话说，运行在 Unix 系统上的所有应用程序必须与 C 库结合在一起，形成一个新的整体作品，由原始应用程序和 C 库组成。因此，如果 glibc 被授权为 GPL，那么每个在 GNU/Linux 上使用的应用程序也需要遵循 GPL，因为为了使这些应用程序能够运行，它们需要通过与 glibc 链接而被组合成更大的作品。

At first glance, such an outcome seems like a windfall for Free Software advocates, since it stops all proprietary software development on GNU/Linux systems. However, the outcome is a bit more subtle. In a world where many C libraries already exist, many of which could easily be ported to GNU/Linux, a GPL'd glibc would be unlikely to succeed. Proprietary vendors would see the excellent opportunity to license their C libraries to anyone who wished to write proprietary software for GNU/Linux systems. The de-facto standard for the C library on GNU/Linux would likely be not glibc, but the most popular proprietary one.

乍一看，这样的结果似乎对自由软件倡导者来说是一笔意外之财，因为它停止了所有在 GNU/Linux 系统上的专有软件开发。然而，结果却更加微妙。在已经存在许多C库的世界中，其中许多都可以很容易地移植到 GNU/Linux 上，一个 GPL 的 glibc 很难成功。专有供应商将会看到优秀的机会，可以向希望为 GNU/Linux 系统编写专有软件的任何人授权其 C 库。在GNU/Linux 上，C 库的事实标准可能不会是 glibc，而是最受欢迎的专有C库。

Meanwhile, the actual goal of releasing glibc under the GPL --- to ensure no proprietary applications on GNU/Linux --- would be unattainable in this scenario. Furthermore, users of those proprietary applications would also be users of a proprietary C library, not the Free glibc.

同时，在 GPL 下发布 glibc 的实际目标 —— 确保 GNU/Linux 上没有专有应用程序 —— 将是在这种情况下无法实现。 此外，那些专有的用户应用程序也将是专有 C 库的用户，而不是免费的 glibc。

The Lesser GPL was initially conceived to handle this scenario. It was clear that the existence of proprietary applications for GNU/Linux was inevitable. Since there were so many C libraries already in existence, a new one under the GPL would not stop that tide. However, if the new C library were released under a license that permitted proprietary applications to link with it, but made sure that the library itself remained Free, an ancillary goal could be met. Users of proprietary applications, while they would not have the freedom to copy, share, modify and redistribute the application itself, would have the freedom to do so with respect to the C library.

宽松 GPL 最初是为处理这种情况而设计的。 很明显，GNU/Linux 的专有应用程序的存在是不可避免的。 由于已经存在这么多 C 库，GPL 下的新库不会阻止这种趋势。 但是，如果新 C 库是根据允许专有的许可证发布的应用程序与它链接，又能确保库本身保持自由，那么就可以实现附属目标。专有应用程序的用户虽然不能复制、共享、修改和重新分发应用程序本身，但可以分享 C 库的这些自由。

There was no way the license of glibc could stop or even slow the creation of proprietary applications on GNU/Linux. However, loosening the restrictions on the licensing of glibc ensured that nearly all proprietary applications at least used a Free C library rather than a proprietary one. This trade-off is central to the reasoning behind the LGPL.

glibc 的许可证无法阻止甚至减慢在 GNU/Linux 上创建专有应用程序。 然而，对 glibc 许可的宽松限制确保几乎所有专有应用程序至少使用自由软件 C 库而不是专有的。这种权衡是 LGPL 背后的核心理由。

Of course, many people who use the LGPL today are not thinking in these terms. In fact, they are often choosing the LGPL because they are looking for a "compromise" between the GPL and the X11-style liberal licensing. However, understanding FSF's reasoning behind the creation of the LGPL is helpful when studying the license.

当然，今天许多使用 LGPL 的人并没有考虑这些条款。 事实上，他们经常选择 LGPL，因为他们正在寻找 GPL 和 X11 风格之间的“妥协”自由许可。 然而，了解 FSF 创建 LGPL 背后的原因有助于学习许可证。

### 10.2 What's the Same?

### 10.2 相同的是什么？

Much of the text of the LGPL is identical to the GPL. As we begin our discussion of the LGPL, we will first eliminate the sections that are identical, or that have the minor modification changing the word "Program" to "Library."

LGPL 的大部分文本与 GPL 相同。当我们开始讨论 LGPL 时，我们将首先删除以下相同的部分，或者将“程序”改成“库”有微小的修改。

First, LGPLv2.1 1, the rules for verbatim copying of source, are equivalent to those in GPLv2 1.

首先，LGPLv2.1 第1条，逐字复制源码的规则，等同于 GPLv2 第1条中的规则。

Second, LGPLv2.1 8 is equivalent GPLv2 4. In both licenses, this section handles termination in precisely the same manner.

其次，LGPLv2.1 第8条等同于 GPLv2 第4条。在这两个许可证中，这部分以完全相同的方式处理许可终止。

LGPLv2.1 9 is equivalent to GPLv2 5. Both sections assert that the license is a copyright license, and handle the acceptance of those copyright terms.

LGPLv2.1 第9条等同于 GPLv2 第5条。这两部分都声明许可是版权许可，并处理接受版权的条款。

LGPLv2.1 10 is equivalent to GPLv2 6. They both protect the distribution system of Free Software under these licenses, to ensure that up, down, and throughout the distribution chain, each recipient of the software receives identical rights under the license and no other restrictions are imposed.

LGPLv2.1 第10条等同于 GPLv2 第6条。它们都保护这些许可证下的自由软件分发系统，以确保在整个分发链上、下游和整个分发链中，每个收件人的软件根据许可证获得相同的权利，并且没有施加了其他限制。

LGPLv2.1 11 is GPLv2 7. As discussed, it is used to ensure that other claims and legal realities, such as patent licenses and court judgments, do not trump the rights and permissions granted by these licenses, and requires that distribution be halted if such a trump is known to exist.

LGPLv2.1的第11条是GPLv2的第7条。如前所述，它用于确保其他主张和法律现实，例如专利许可和法庭判决，不会否定这些许可证授予的权利和权限，并要求如果已知存在这样的否定情况，则必须停止分发。

LGPLv2.1 12 adds the same features as GPLv2 8. These sections are used to allow original copyright holders to forbid distribution in countries with draconian laws that would otherwise contradict these licenses. LGPLv2.1 13 sets up the FSF as the steward of the LGPL, just as GPLv2 9 does for GPL. Meanwhile, LGPLv2.1 14 reminds licensees that copyright holders can grant exceptions to the terms of LGPL, just as GPLv2 10 reminds licensees of the same thing.

LGPLv2.1 第12条款增加了与 GPLv2 第8条相同的功能。这些条款用于允许原始版权持有人禁止在拥有极其严苛法律的国家进行分发，否则将与这些许可证相矛盾。LGPLv2.1 第13条设立了 FSF 作为 LGPL 的管理者，就像 GPLv2 第9条为 GPL 所做的那样。同时，LGPLv2.1 第14条提醒许可证持有人版权持有人可以授予对 LGPL 条款的例外，就像 GPLv2 第10条提醒许可证持有人一样。

Finally, the assertions of no warranty and limitations of liability are identical; thus LGPLv2.1 15 and LGPLv2.1 16 are the same as GPLv2 11 and 12.

最后，无保证和责任限制的声明是相同； 因此 LGPLv2.1 第15条 和 LGPLv2.1 第16条 与 GPLv2 第11条和第12条相同。

As we see, the entire latter half of the license is identical. The parts which set up the legal boundaries and meta-rules for the license are the same. It is our intent that the two licenses operate under the same legal mechanisms and are enforced precisely the same way.

如我们所见，许可证的整个后半部分是相同的。 这为许可证设置法律边界和元规则的部分是相同的。我们的意图是这两个许可证在相同的法律机制，并以完全相同的方式执行。

We strike a difference only in the early portions of the license. Namely, in the LGPL we go into deeper detail of granting various permissions to create certain types of combinations, modifications and derivations. The LGPL does not stretch the requirements as far as copyright law does regarding what works must be relicensed under the same terms. Therefore, LGPL must in detail explain which works can be proprietary. Thus, we'll see that the front matter of the LGPL is a bit more wordy and detailed with regards to the permissions granted to those who modify or redistribute the software.

我们只在许可证的早期部分进行了一些不同。也就是说，在 LGPL 中，我们更详细地授予各种权限，以创建某些类型的组合、修改和派生作品。LGPL 并不像版权法那样要求作品必须按相同条款重新许可，因此，LGPL 必须详细说明哪些作品可以是专有的。因此，我们将看到 LGPL 的前言部分在授予修改或重新分发软件的人所获得的权限方面更加冗长和详细。

### 10.3 Additions to the Preamble

### 10.3 序言的补充

Most of the LGPL's Preamble is identical, but the last seven paragraphs introduce the concepts and reasoning behind creation of the license, presenting a more generalized and briefer version of the story with which we began our consideration of the LGPL.

LGPL 的前言大部分内容相同，但最后7段介绍了创造该许可证的概念和理由，提供了一个更加普遍和简短的版本，这个版本与我们开始考虑 LGPL 时所讲述的故事相似。

In short, FSF designed the LGPL for those edge cases where the freedom of the public can better be served by a more lax licensing system. FSF doesn't encourage use of the LGPL automatically for any software that happens to be a library; rather, FSF suggests that it only be used in specific cases, such as the following:

简而言之，自由软件基金会设计LGPL是为了那些边缘情况，这些情况中公众的自由可以通过更宽松的许可系统更好地得到保障。自由软件基金会并不会自动鼓励对任何恰好是库的软件使用LGPL；相反，自由软件基金会建议只在以下特定情况下使用LGPL：

To encourage the widest possible use of a Free Software library, so it becomes a de-facto standard over similar, although not interface-identical, proprietary alternatives

为了鼓励尽可能广泛地使用自由软件库，使其成为类似专有替代品之间的事实标准，尽管它们的接口并不完全相同。

To encourage use of a Free Software library that already has interface-identical proprietary competitors that are more developed

为了鼓励使用已经有更成熟的专有竞争对手存在的自由软件库，而这些竞争对手的接口是相同的。

To allow a greater number of users to get freedom, by encouraging proprietary companies to pick a Free alternative for its otherwise proprietary products

为了让更多的用户获得自由，通过鼓励专有公司在其原本专有的产品中选择自由的替代方案。

The LGPL's preamble sets forth the limits to which the license seeks to go in chasing these goals. The LGPL is designed to ensure that users who happen to acquire software linked with such libraries have full freedoms with respect to that library. They should have the ability to upgrade to a newer or modified Free version or to make their own modifications, even if they cannot modify the primary software program that links to that library.

LGPL的前言阐述了许可证在追求这些目标时的限制。LGPL的设计旨在确保那些获取与这些库链接的软件的用户对该库拥有完全的自由。他们应该有能力升级到一个更新或修改后的自由版本，或者进行自己的修改，即使他们不能修改链接到该库的主要软件程序。

Finally, the preamble introduces two terms used throughout the license to clarify between the different types of combined works: "works that use the library," and "works based on the library." Unlike the GPL, the LGPL must draw some lines regarding permissibly proprietary combined works. We do this here in this license because we specifically seek to liberalize the rights afforded to those who make combined works. In the GPL, we reach as far as copyright law allows. In the LGPL, we want to draw a line that allows some derivative works copyright law would otherwise prohibit if the copyright holder exercised his full permitted controls over the work.

最后，前言引入了两个术语，这些术语贯穿整个许可证，以澄清不同类型的组合作品之间的区别：“使用该库的作品”和“基于该库的作品”。与GPL不同，LGPL必须在允许专有组合作品方面划分一些界限。我们在这个许可证中这样做，因为我们特别寻求放宽对那些制作组合作品的人所享有的权利。在GPL中，我们尽可能地延伸到版权法所允许的范围。在LGPL中，我们想划定一条线，如果版权持有人行使其对作品的全部允许控制权，那么版权法本来会禁止一些衍生作品的产生。

### 10.4 An Application: A Work that Uses the Library

### 10.4 应用：使用该库的作品

In the effort to allow certain proprietary works and prohibit others, the LGPL distinguishes between two classes of works: "works based on the library," and "works that use the library." The distinction is drawn on the bright line of binary (or runtime) combined works and modified versions of source code. We will first consider the definition of a "work that uses the library," which is set forth in LGPLv2.1 5.

为了允许某些专有作品并禁止其他作品，LGPL 区分了两类作品：“基于该库的作品”和“使用该库的作品”。这个区分是基于二进制（或运行时）组合作品和源代码的修改版本的明显界限。我们首先考虑“使用该库的作品”的定义，这在LGPLv2.1 第5条中规定。

We noted in our discussion of GPLv2 3 (discussed in Section [5.2](#gplv2-3-producing-binaries) of this document) that binary programs when compiled and linked with GPL'd software are covered as a whole by GPL. This includes both linking that happens at compile-time (when the binary is created) or at runtime (when the binary -- including library and main program both -- is loaded into memory by the user). In GPL, binary works are controlled by the terms of the license (in GPLv2 3), and distributors of such binary works must release full corresponding source.

我们在讨论GPLv2 第3条时指出（在本文档的第5.2节中讨论），当二进制程序在编译时与GPL软件链接时，整个程序都受GPL的覆盖范围。这包括在编译时发生的链接（创建二进制文件时）或在运行时发生的链接（当用户将包括库和主程序的二进制文件加载到内存中时）。在GPL中，二进制作品受许可证条款（GPLv2 第3条）的控制，这些二进制作品的分发者必须发布相应的全部源代码。

The LGPL, by contrast, allows partial proprietarization of such binary works. This scenario, defined in LGPL as "a work that uses the library," works as follows:

相比之下，LGPL 允许对这种二进制文件进行部分专有化作品。这种场景在 LGPL 中定义为“使用库”的工作原理如下：

- A new copyright holder creates a separate and independent work, *I*, that makes interface calls (e.g., function calls) to the LGPL'd work, called *L*, whose copyright is held by some other party. Note that since *I* and *L* are separate and independent works, there is no copyright obligation on this new copyright holder with regard to the licensing of *I*, at least with regard to the source code.

- 一个新的版权持有者创建了一个名为 **I** 的独立作品，它进行接口调用（例如函数调用）到由其他方持有版权的 LGPL 作品 **L**。请注意，由于 **I** 和 **L** 是独立的作品，因此对于 **I** 的许可证至少在源代码方面，新的版权持有者没有版权义务。

- The new copyright holder, for her software to be useful, realizes that it cannot run without combining *I* and *L*. Specifically, when she creates a running binary program, that running binary must be a combined work, called *L*+*I*, that the user can run.

- 新的版权持有者，为了让她的软件有用，意识到如果不结合 *I* 和 *L*，它就无法运行。具体来说，当她创建一个可执行的二进制程序时，那个可执行的二进制程序 必须是用户可以运行的组合作品，称为 *L*+*I*。

- Since *L*+*I* is a based on both *I* and *L*, the license of *L* (the LGPL) can put restrictions on the license of *L*+*I*. In fact, this is what the LGPL does.

- 由于 *L*+*I* 是基于 *I* 和 *L* 的，*L* 的许可证 （LGPL）可以对 *L*+*I* 的许可施加限制。事实上，LGPL 就是这么做的。

We will talk about the specific restrictions LGPLv2.1 places on "works that use the library" in detail in Section [10.7.](#lgplv2.1-6-lgplv2.1-5-combining-the-works) For now, focus on the logic related to how the LGPLv2.1 places requirements on the license of

下面我们就来说说 [10.7](#lgplv2.1-6-lgplv2.1-5-combining-the-works) 节中 LGPLv2.1 对使用库的“作品”的具体限制部分中的详细信息。现在，关注 LGPLv2.1 中如何添加条件的现在

\+ . Note, first of all, the similarity between this explanation and that in Section [5.1.2,](#gplv2-2b) which discussed the combination of otherwise separate and independent works with GPL'd code. Effectively, what LGPLv2.1 does is say that when a new work is otherwise separate and independent, but has interface calls out to an LGPL'd library, then it is considered a "work that uses the library."

\+ 首先注意到这个解释和5.1.2节中讨论的将GPL代码与本来是独立的代码组合起来的相似之处。实际上，LGPLv2.1的作用是指出，当一个新的作品本来是独立的，但是它与LGPL库存在接口调用时，那么它被认为是“使用该库的作品”。

In addition, the only reason that LGPLv2.1 has any control over the licensing of a "work that uses the library" is for the same reason that GPL has some say over separate and independent works. Namely, such controls exist because the *binary combination* ( + ) that must be created to make the separate work ( ) at all useful is a work based on the LGPLv2.1'd software ( ).

此外，LGPLv2.1对“使用该库的作品”的许可控制之所以存在，唯一的原因与GPL对于本来是独立的作品有一定程度的控制权是相同的。也就是说，这些控制权存在是因为必须通过二进制组合(+)来使本来是独立的作品( )有用，而这个二进制组合是基于LGPLv2.1的软件( )创建的作品。

Thus, a two-question test that will help indicate if a particular work is a "work that uses the library" under LGPLv2.1 is as follows:

因此，一个包含两个问题的测试将有助于表明一个特定的工作是否是LGPLv2.1下的“使用库的作品”如下：

1. Is the source code of the new copyrighted work, *I*, a completely independent work that stands by itself, and includes no source code from *L*?

2. When the source code is compiled, does it combine into a single work with *L*, either by static (compile- time) or dynamic (runtime) linking, to create a new binary work, *L*+*I*?

<br />

1. 新的被版权保护的作品 **I** 的源代码是完全独立的吗？它能够单独存在并且不包括来自 **L** 的任何源代码吗？

2. 当源代码被编译时，它是否通过静态（编译时）或动态（运行时）链接与L组合成一个单一的工作，以创建一个新的二进制工作，即 **L+I**？

If the answers to both questions are "yes," then is most likely a "work that uses the library." If the answer to the first question "yes," but the answer to the second question is "no," then most likely is neither a "work that uses the library" nor a "work based on the library." If the answer to the first question is "no," but the answer to the second question is "yes," then an investigation into whether or not is in fact a "work based on the library" is warranted.

如果两个问题的答案都是“是”，那么这很可能是一个“使用库的作品”。如果第一个问题的答案是“是”，但第二个问题的答案是“否”，那么很可能既不是“使用库的作品”，也不是“基于库的作品”。如果第一个问题的答案是“否”，但第二个问题的答案是“是”，那么需要调查是否实际上是一个“基于库的作品”。

### 10.5 The Library, and Works Based On It

### 10.5 库，基于它的衍生作品

In short, a "work based on the library" could be defined as any work based on the LGPL'd software that cannot otherwise fit the definition of a "work that uses the library." A "work based on the library" extends the full width and depth of derivative, combined and/or modified works under copyright law, in the same sense that the GPL does.

简而言之，“基于库的作品”可以被定义为任何基于LGPL 许可的软件的作品，否则不能符合“使用库的作品”的定义。在版权法的范围内，“基于库的作品”扩展了派生、组合和/或修改作品的全部范围，与 GPL 的作用相同。

Most typically, one creates a "work based on the library" by directly modifying the source of the library. Such a work could also be created by tightly integrating new software with the library. The lines are no doubt fuzzy, just as they are with GPL'd works, since copyright law gives us no litmus test for determining if a given work is a derivative or otherwise a modified version of another software program.

最常见的情况是通过直接修改库的源代码创建一个“基于库的作品”。这样的作品也可以通过与库紧密集成新软件来创建。这些界限无疑是模糊的，就像 GPL 的作品一样，因为版权法没有给我们一个检验标准来确定一个给定的作品是否是另一个软件程序的派生或修改版本。

Thus, the test to use when considering whether something is a "work based on the library" is as follows:

因此，在考虑是否是一个“基于库的作品”时，可以使用以下测试：

1. Is the new work, when in source form, a derivative and/or modified work of, and/or a combined work with the LGPL'd work under copyright law?

2. Is there no way in which the new work fits the definition of a "work that uses the library"?

<br />

1. 在源代码形式下，新的作品是否在版权法下是一个派生和/或修改的作品，和/或一个与 LGPL 许可作品组合的作品？

2. 新的作品是否没有符合“使用库的作品”的定义的方式？

If the answer is "yes" to both these questions, then you most likely have a "work based on the library." If the answer is "no" to the first but "yes" to the second, you are in a gray area between "work based on the library" and a "work that uses the library."

如果两个问题的答案都是“是”，那么你很可能有一个“基于库的作品”。如果第一个问题的答案是否定的，但第二个问题的答案是肯定的，你就处于“基于库的作品”和“使用库的作品”之间的灰色地带。

You can also perform a similar same analysis through careful consideration of the license text itself. LGPLv2 2(a) states that if a licensed work is a software library (defined in LGPLv2 0 as "a collection of software functions and/or data prepared so as to be conveniently linked with application programs (which use some of those functions and data) to form executables"), you have permission to distribute modified versions only if those versions are themselves libraries. LGPLv2.1 code can therefore not be compliantly taken from its context in a library and placed in a non-library modified version or work based on the work. For its part, LGPLv2 6 does not provide an exception for this rule: a combination may be made of a modified version of an LGPL'd library with other code, but the LGPL'd code must continue to be structured as a library, and to that library the terms of the license continue to apply.

你还可以通过仔细考虑许可证文本本身来进行类似的分析。LGPLv2 2(a)规定，如果一个许可工作是软件库（在LGPLv2 第0条中定义为“一组软件函数和/或数据，为了方便地与应用程序（使用其中一些函数和数据）链接形成可执行文件而准备的”），你只有在这些版本本身是库时才有权限分发修改版本。因此，LGPLv2.1 代码不能从其上下文中以合规的方式作为库被拿出来并放置在非库修改版本或基于该工作的工作中。对于其部分，LGPLv2 第6条并没有为此规则提供例外：可以将 LGPL 许可的库的修改版本与其他代码组合，但 LGPL 许可的代码必须继续作为库结构化，并且该库的条款仍然适用于该库。

Either way you view the rules, these issues are admittedly complicated. Nevertheless, In our years of work with the LGPLv2.1, however, we have never seen a work of software that was not clearly one or the other; the line is quite bright. At times, though, we have seen cases where a particularly large work in some ways seemed to be both to both a work that used the library and a work based on the library. We overcame this problem by dividing the work into smaller subunits. It was soon discovered that what we actually had were three distinct components: the original LGPL'd work, a specific set of works that used that library, and a specific set of works that were based on the library. Once such distinctions are established, the licensing for each component can be considered independently and the LGPLv2.1 applied to each work as prescribed. Finally, note though that, since the LGPLv2.1 can be easily upgraded to GPLv2-or-later, in the worst case you simply need to comply as if the software was licensed under GPLv2. The only reason you must consider the question of whether you have a "work that uses the library" or a "work based on the library" is when you wish to take advantage of the "weak copyleft" effect of the Lesser GPL. If GPLv2-or-later is an acceptable license (i.e., if you plan to copyleft the entire work anyway), you may find this an easier option.

无论您如何看待这些规则，这些问题都可以说是相当复杂的。然而，在我们多年 LGPLv2.1 工作的经验中，我们从未见过一个软件作品不明确属于其中之一的情况；界限非常明显。不过，有时我们会遇到一些特别大的作品，在某些方面似乎既是使用库的作品，又是基于库的作品。我们通过将作品分成较小的子单元来解决这个问题。很快就发现我们实际上有三个不同的组成部分：原始的LGPL作品、使用该库的一组具体作品以及基于该库的一组具体作品。一旦建立了这样的区分，每个组件的许可证可以独立考虑，而且可以按照规定为每个作品应用 LGPLv2.1。最后，请注意，由于 LGPLv2.1 可以很容易地升级为 GPLv2 或更高版本，因此在最坏的情况下，您只需要遵守好像软件已经根据GPLv2许可的规定即可。您必须考虑是否拥有“使用库的作品”或“基于库的作品”的问题，唯一的原因是当您想要利用较弱的版权保护（“weak copyleft”）效果时。如果 GPLv2 或更高版本是可接受的许可证（即如果您计划无论如何都使用copyleft保护整个作品），那么您可能会发现这是一个更容易的选择。

### 10.6 Subtleties in Defining the Application

### 10.6 定义应用程序的微妙之处

In our discussion of the definition of "works that use the library," we left out a few more complex details that relate to lower-level programming details. The fourth paragraph of LGPLv2.1 5 covers these complexities, and it has been a source of great confusion. Part of the confusion comes because a deep understanding of how compiler programs work is nearly mandatory to grasp the subtle nature of what LGPLv2.1 5, 4 seeks to cover. It helps some to note that this is a border case that we cover in the license only so that when such a border case is hit, the implications of using the LGPL continue in the expected way.

在我们讨论“使用库的作品”的定义时，我们忽略了一些与较低级编程细节相关的更复杂的细节。LGPLv2.1 第5条的第4项涵盖了这些复杂性，它已经成为了一个极大的困惑来源。部分的困惑来自于深入理解编译器程序工作方式几乎是必需的，以理解LGPLv2.1 第5条第4项试图涵盖的微妙性质。需要注意的是，这是一个边界情况，我们仅在许可证中涵盖它，以便当出现这样的边界情况时，LGPL的使用后果将以预期的方式继续产生影响。

To understand this subtle point, we must recall the way that a compiler operates. The compiler first generates object code, which are the binary representations of various programming modules. Each of those modules is usually not useful by itself; it becomes useful to a user of a full program when those modules are *linked* into a full binary executable.

要理解这个微妙的点，我们必须回顾编译器的工作方式。编译器首先生成目标代码，这些是各种编程模块的二进制表示。这些模块通常本身并不有用；只有当这些模块被链接到一个完整的二进制可执行文件中时，它们才对完整程序的用户有用。

As we have discussed, the assembly of modules can happen at compile-time or at runtime. Legally, there is no distinction between the two --- both create a modified version of the work by copying and combining portions of one work and mixing them with another. However, under LGPL, there is a case in the compilation process where the legal implications are different. To understand this phenomenon, we consider that a "work that uses the library" is typically one whose final binary is a work based on the Program, but whose source is not. However, sometimes, there are cases where the object code --- that intermediate step between source and final binary --- is a work created by copying and modifying code from the LGPL'd software.

正如我们所讨论的，模块的组合可以在编译时或运行时发生。从法律上讲，这两者之间没有区别——都通过复制和组合一个作品的部分并将它们与另一个混合来创建一个修改版本的作品。然而，在LGPL下，编译过程中存在一种情况，其法律影响是不同的。为了理解这种现象，我们考虑“使用库的作品”通常是指其最终二进制文件是基于程序的作品，但其源代码不是。然而，有时候，在目标代码——源代码和最终二进制文件之间的中间步骤中——存在一种情况，即通过复制和修改LGPL软件中的代码创建了一个作品。

For efficiency, when a compiler turns source code into object code, it sometimes places literal portions of the copyrighted library code into the object code for an otherwise separate independent work. In the normal scenario, the final combined work would not be created until final assembly and linking of the executable occurred. However, when the compiler does this efficiency optimization, at the intermediate object code step, a combined work is created.

为了提高效率，编译器将源代码转换为目标代码时，有时会将受版权保护的库代码的文字部分放入目标代码中，以便于另一个独立的作品。在正常情况下，直到最终的汇编和可执行文件链接发生时，才会创建最终的组合作品。但是，当编译器进行这种效率优化时，在中间的目标代码步骤中，就创建了一个组合作品。

LGPLv2.1 5 4 is designed to handle this specific case. The intent of the license is clearly that simply compiling software to "make use" of the library does not in itself cause the compiled work to be a "work based on the library." However, since the compiler copies verbatim, copyrighted portions of the library into the object code for the otherwise separate and independent work, it would actually cause that object file to be a "work based on the library." It is not FSF's intent that a mere compilation idiosyncrasy would change the requirements on the users of the LGPLv2.1'd software. This paragraph removes that restriction, allowing the implications of the license to be the same regardless of the specific mechanisms the compiler uses underneath to create the "work that uses the library."

LGPLv2.1 第5条第4项的设计目的是处理这种特定情况。许可证的意图显然是，仅仅编译软件以“使用”库本身并不会导致编译后的作品成为“基于库的作品”。然而，由于编译器将受版权保护的库的文字部分复制到了另一个独立的作品的目标代码中，实际上会使得该目标文件成为“基于库的作品”。FSF并不希望仅仅是编译的怪癖会改变LGPLv2.1软件的用户的要求。该段落移除了这个限制，允许许可证的影响在不考虑编译器在创建“使用库的作品”时使用的具体机制的情况下是相同的。

As it turns out, we have only once had anyone worry about this specific idiosyncrasy, because that particular vendor wanted to ship object code (rather than final binaries) to their customers and was worried about this edge condition. The intent of clarifying this edge condition is primarily to quell the worries of software engineers who understand the level of verbatim code copying that a compiler often does, and to help them understand that the full implications of LGPLv2.1 are the same regardless of the details of the compilation progress.

事实证明，我们只有一次有人担心这个特定的怪癖，因为那个特定的供应商想要向他们的客户提供目标代码（而不是最终的二进制代码），并担心这种边缘情况。澄清这种边缘情况的目的主要是为了平息那些了解编译器常常进行逐字复制的软件工程师的担忧，并帮助他们理解LGPLv2.1的全部含义，而不管编译过程的细节如何。

### 10.7 LGPLv2.1 §6 & LGPLv2.1 §5: Combining the Works

### 10.7 LGPLv2.1 第6条和第5条：组合作品

Now that we have established a good working definition of works that "use" and works that "are based on" the library, we will consider the rules for distributing these two different works.

既然我们已经建立了一个关于“使用”和“基于”该库的作品的良好工作定义，我们将考虑分发这两种不同作品的规则。

The rules for distributing "works that use the library" are covered in LGPLv2.1 6. LGPLv2.1 6 is much like GPLv2 3, as it requires the release of source when a binary version of the LGPL'd software is released. Of course, it only requires that source code for the library itself be made available. The work that "uses" the library need not be provided in source form. However, there are also conditions in LGPLv2.1 6 to make sure that a user who wishes to modify or update the library can do so.

分发“使用该库的作品”的规则在LGPLv2.1 第6条中有所涉及。LGPLv2.1 第6条类似于GPLv2 第3条，因为它要求在发布LGPL 许可的软件的二进制版本时发布源代码。当然，它只需要该库本身的源代码可用。使用该库的作品不必以源代码形式提供。但是，LGPLv2.1 第6条也有条件，以确保希望修改或更新库的用户可以这样做。

LGPLv2.1 6 lists five choices with regard to supplying library source and granting the freedom to modify that library source to users. We will first consider the option given by 6(b), which describes the most common way currently used for LGPLv2.1 compliance on a "work that uses the library."

LGPLv2.1 6列出了五个选项，关于提供库源代码和向用户授予修改该库源代码的自由。我们将首先考虑6(b)提供的选项，这是目前在“使用该库的作品”上遵守LGPLv2.1的最常见方式。

LGPLv2.1 6(b) allows the distributor of a "work that uses the library" to simply use a dynamically linked, shared library mechanism to link with the library. This is by far the easiest and most straightforward option for distribution. In this case, the executable of the work that uses the library will contain only the "stub code" that is put in place by the shared library mechanism, and at runtime the executable will combine with the shared version of the library already resident on the user's computer. If such a mechanism is used, it must allow the user to upgrade and replace the library with interface-compatible versions and still be able to use the "work that uses the library." However, all modern shared library mechanisms function as such, and thus LGPLv2.1 6(b) is the simplest option, since it does not even require that the distributor of the "work based on the library" ship copies of the library itself.

LGPLv2.1 6(b)允许“使用该库的作品”的分发者简单地使用动态链接共享库机制与该库链接。这是分发的最简单和最直接的选择。在这种情况下，“使用该库的作品”的可执行文件将只包含由共享库机制放置的“存根代码”，在运行时可执行文件将与已经驻留在用户计算机上的共享库的共享版本合并。如果使用这种机制，它必须允许用户升级和替换库并仍然能够使用“使用该库的作品”，前提是它们具有界面兼容版本。然而，所有现代共享库机制都是这样工作的，因此LGPLv2.1 6(b)是最简单的选择，因为它甚至不需要“基于该库的作品”的分发者提供该库本身的副本。

LGPLv2.1 6(a) is the option to use when, for some reason, a shared library mechanism cannot be used. It requires that the source for the library be included, in the typical GPL fashion, but it also has a requirement beyond that. The user must be able to exercise her freedom to modify the library to its fullest extent, and that means recombining it with the "work based on the library." If the full binary is linked without a shared library mechanism, the user must have available the object code for the "work based on the library," so that the user can relink the application and build a new binary.

LGPLv2.1 6(a)是当某些原因无法使用共享库机制时使用的选项。它要求以典型的GPL方式包含该库的源代码，但它还有一个额外的要求。用户必须能够充分行使其修改该库的自由，这意味着将其与“基于该库的作品”重新组合。如果完整的二进制文件没有使用共享库机制进行链接，则用户必须可用“基于该库的作品”的目标代码，以便用户可以重新链接应用程序并构建一个新的二进制文件。

Almost all known LGPL'd distributions exercise either LGPLv2.1 6(a) or LGPLv2.1 6(b). However, LGPLv2.1 6 provides three other options. LGPLv2.1 6(c) allows for a written offer for CCS (akin to [GPLv2 3(b)).](#additional-source-provision-options) CCS may also be distributed by network under the terms of LGPLv2.1 6(c). Furthermore, under LGPLv2.1 6(e) the distributor may "verify" that the user has already received, or at least that the distributor has already sent to this particular user, the relevant source[^1^](#_bookmark155).

几乎所有已知的LGPL发行版都使用LGPLv2.1 6(a)或LGPLv2.1 6(b)。但是，LGPLv2.1 6还提供了另外三个选项。LGPLv2.1 6(c)允许书面提供CCS的选择（类似于GPLv2 3(b)）。CCS也可以按照LGPLv2.1 6(c)的条款通过网络分发。此外，在LGPLv2.1 6(e)下，分发者可以“验证”用户已经收到了相关的源代码，或者至少已经向该特定用户发送了相关源代码 [^1^]。

Finally, LGPLv3 *§*6 also requires that:

最后，LGPLv3 第6条还要求：

You must give prominent notice with each copy of the work that the Library is used in it and that the Library and its use are covered by this License. You must supply a copy of this License. If the work during execution displays copyright notices, you must include the copyright notice for the Library among them, as well as a reference directing the user to the copy of this License.

每份作品的副本中必须显著说明其中使用了该库，并且该库及其使用受到本许可证的覆盖。您必须提供本许可证的副本。如果作品在执行过程中显示版权声明，您必须在其中包括该库的版权声明，以及一个引用，指向本许可证的副本。

^1^[]{#_bookmark155 .anchor}Policy motivations for LGPLv2.1 6(d) are unclear, but it presumably intended to prevent requiring duplicate deliveries in "whole distribution" situations.

^1^[]{#_bookmark155 .anchor}LGPLv2.1 6(d) 的政策动机尚不清楚，但它可能旨在防止在“整个分发”情况下要求重复交付。

This is not identical to the roughly parallel requirements of GPLv2 and GPLv3. Compliance requires slightly different measures with respect to the "credits" or "licenses" or "about" screens in interactive programs.

是的，这与GPLv2和GPLv3的大致类似要求不完全相同。在交互式程序中，符合要求需要采取稍微不同的措施来处理“信用”、“许可”或“关于”屏幕。

### 10.8  Distributing Works Based On the Library

### 10.8  分发基于该库的作品

Essentially, "works based on the library" must be distributed under the same conditions as works under full GPL. In fact, we note that LGPLv2.1 2 is nearly identical in its terms and requirements to GPLv2 2.

本质上，“基于库的作品”必须按照完整版GPL下作品的相同条件分发。事实上，我们注意到LGPLv2.1的条款和要求与GPLv2 2几乎完全相同。

There are, however, subtle differences and additions. For example not only is CCS required (as would be with normal versions of GPL), but also the CCS provided must enable a developer to regenerate the modified version of the entire combined work, using with a modified version of the LGPL'd work (as a replacement for the version a distributor provided). For example, LGPL'd code is statically linked to a non-copyleft executable, the required source code must also include sufficient material to split the distributed executable and relink with a modified version of the library.

然而，存在一些细微的差异和添加。例如，不仅需要使用通用公共许可证（CCS）（与普通GPL版本一样），还需要提供的CCS必须使开发人员能够使用LGPL作品的修改版本（作为替换分发者提供的版本），重新生成整个组合作品的修改版本。例如，如果LGPL的代码被静态链接到一个非版权的可执行文件中，所需的源代码还必须包括足够的材料来拆分分发的可执行文件，并与库的修改版本重新链接。

### 10.9 And the Rest

### 10.9 其余部分

The remaining variations between the LGPL and the GPL cover the following conditions:

LGPL 和 GPL 之间的其余差异涵盖了以下条件：

Allowing a licensing "upgrade" from the LGPL to the GPL (in LGPLv2.1 3). Note, however, LGPLv2.1 3 allows relicensing of works under its terms instead under the terms of GPLv2-or-later. This provides, for example, a pathway for those who do not want to use code under the requirements of LGPLv2.1 to do so under GPLv2 or GPLv3 at their discretion.

允许从LGPL升级到GPL进行许可证“升级”（在LGPLv2.1 第3条中）。但是请注意，LGPLv2.1 第3条允许将作品重新许可为其条款下的作品，而不是 GPLv2 或更高版本的条款下的作品。例如，这为那些不想按照 LGPLv2.1 要求使用代码的人提供了一条路径，让他们可以根据自己的意愿在 GPLv2 或 GPLv3 下使用该代码。

- Binary distribution of the library only, covered in LGPLv2.1 *§*4, which is effectively equivalent to LGPLv2.1 *§*3

- LGPLv2.1的第4条涵盖的是仅对库进行二进制分发，其实质上相当于LGPLv2.1的第3条。

- Creating aggregates of libraries that are separate and independent works from each other, and dis- tributing them as a unit (in LGPLv2.1 *§*7)

- LGPLv2.1的第7条涵盖的是创建库的集合，这些库彼此独立且相互独立，作为一个单元进行分发。

Due to time constraints, we cannot cover these additional terms in detail, but they are mostly straight- forward. The key to understanding LGPLv2.1 is understanding the difference between a "work based on the library" and a "work that uses the library." Once that distinction is clear, the remainder of LGPLv2.1 is close enough to GPL that the concepts discussed in our more extensive GPL unit can be directly applied.

由于时间限制，我们无法详细讨论这些额外条款，但它们大多数都很简单。理解 LGPLv2.1 的关键在于理解“基于库的作品”和“使用库的作品”之间的区别。一旦这种区别清晰明了，LGPLv2.1 的其余部分就足够接近 GPL，以至于我们在更广泛的 GPL 单元中讨论的概念可以直接应用。


## CHAPTER 11 LGPLv3

## 第11章 LGPLv3

LGPLv3 was designed to rectify architectural flaws in the GNU family of licenses. Historically , LGPLv2.1 was a textual modification of GPLv2. Reconciliation of licensing terms upon combination of LGPLv2.1'd and GPLv2'd works is cumbersome, from a licensing bookkeeping perspective.

LGPLv3旨在纠正GNU许可证系列中的结构缺陷。历史上，LGPLv2.1是GPLv2的文本修改。从许可证记账的角度来看，当LGPLv2.1的作品与GPLv2的作品结合时，许可证条款的协调是麻烦的。

LGPLv3 redresses this historical problem through extensive use of [GPLv3](#gplv3-7-additional-permissions) 7's exception architecture.

LGPLv3通过广泛使用GPLv3第7条的例外结构来纠正这个历史性问题。

LGPLv3 is therefore a set of additional permission to GPLv3.

因此，LGPLv3 是 GPLv3 的一组附加许可。

### 11.1 Section 0: Additional Definitions

### 11.1 第 0 条：附加定义

LGPLv3 0 defines the "Library" -- a work that presents one or more interfaces at which a "use" can be made by an "Application." Class inheritance is "deemed" a use of an interface. An "Application," which is other program code using one or more "Library" interfaces can be combined with the code on the other side of the interfaces it uses to form a "Combined Work."

LGPLv3 第0条定义了“库”，这是一种提供一个或多个接口，可以被“应用程序”使用的作品。类继承被视为对接口的使用。“应用程序”是指使用一个或多个“库”接口的其他程序代码，可以与其使用的接口对面的代码结合起来形成“组合作品”。

### 11.2 LGPLv3 §1: Exception to GPLv3 §3

### 11.2 LGPLv3 第1条：GPLv3 第3条的例外情况

LGPLv3 *§*1 excepts away the interference with use of LGPLv3 code as part of "effective technological measures" of access limitation for other copyrighted works provided otherwise by GPLv3 *§*3.

LGPLv3 第1条中规定，使用LGPLv3代码作为“有效技术措施”限制其他受版权保护作品的访问的一部分，不能排除GPLv3 第3条的规定。

### 11.3  LGPLv3 §2: Conveying Modified Versions

### 11.3 LGPLv3 §2：传送修改后的版本

LGPLv3 2 continues to require, as LGPLv2.1 2(d) requires, that the Library not be modified to require keys, tokens, tables, or other global non-argument data unrelated to function. This is again stated as a "good faith effort" requirement, but failure to cure on notice is strong evidence of the absence of good faith. LGPLv3 *§*2(b) permits removal of the permissions entirely (as prescribed by GPLv3 *§*7); however, such removal reduces the license of the entire covered work back to pure GPLv3. Thus, exercising LGPLv3 *§*2(b) as a compliance alternative to LGPLv3 *§*2(a) likely creates more compliance obligations than it removes.

LGPLv3 第2条继续要求，与LGPLv2.1 2(d)类似，库不能被修改以需要与函数无关的密钥、令牌、表格或其他全局非参数数据。这再次被规定为“诚信努力”的要求，但是在通知后未能纠正的情况是缺乏诚信的强有力证据。LGPLv3 2(b)允许完全删除权限（如GPLv3 第7条所规定的），但是这种删除会将整个被覆盖作品的许可证还原为纯GPLv3。因此，将LGPLv3 2(b)作为符合要求的替代方案，用于替代LGPLv3 2(a)，可能会创建比它所消除的符合要求的义务更多的符合要求的义务。

### 11.4 LGPLv3 §3: Object Code Incorporating Material from Li- brary Header Files

### 11.4 LGPLv3 第3条：目标代码包含来自库头文件的材料

LGPLv3 3's front matter assures incorporation of smaller header files into non-copylefted object code can proceed unimpeded. More complex header files (those that do not meet the limitations provided in the section), can still be incorporated into object code, a copy of appropriate licensing information must accompany distribution (per LGPLv3 *§*3(a--b).

LGPLv3 第3条的前言确保较小的头文件可以无障碍地合并到非版权对象代码中。更复杂的头文件（不符合该部分提供的限制的头文件）仍然可以合并到对象代码中，但必须附带适当的许可证信息副本进行分发（根据LGPLv3 3(a--b)）。

### 11.5 LGPLv3 §4: Combined Works

### 11.5 LGPLv3 第4条：组合作品

LGPLv3 4 is the combination permission at the heart of LGPLv3. It restates the license limitation provision of LGPLv2.1 2 to clarify that the terms on the Combined Work may not prohibit user modification of the Library code, or the debugging of such modifications to the Library code by means of whatever reverse engineering is necessary.

LGPLv3 第4条是LGPLv3的核心组合授权。它重新表述了LGPLv2.1 第2条的许可限制规定，以澄清组合作品的条款不能禁止用户修改库代码，或通过必要的逆向工程手段对库代码的这些修改进行调试。

LGPLv3 4(d)(0) contains the source provision requirement, for the Minimal Corresponding Source, which "means the Corresponding Source for the Combined Work, excluding any source code for portions of the Combined Work that, considered in isolation, are based on the Application, and not on the Linked Version \[of the Library\]". The alternative to the provision of source code is distribution by way of the "shared library" mechanism under LGPLv3 4(d)(1), described with respect to LGPLv2.1 6.

LGPLv3 4(d)(0)包含源代码条款要求，即“最小对应源码”，这意味着组合作品的对应源码，不包括在分离状态下基于应用程序而不是基于（库的）链接版本的任何部分的源代码。提供源代码的替代方案是通过LGPLv3 4(d)(1)中描述的“共享库”机制进行分发，该机制与LGPLv2.1 第6条有关。

In addition, LGPLv3 4(e) requires the delivery of "installation information" required to install the modified version of the Library in "user products" under GPLv3 6. Where Library Minimal Corresponding Source is not made available under LGPLv3 4(d)(1), LGPLv3 4(e) reaffirms that "installation information" must still be compliantly delivered under the terms of GPLv3 6.

此外，LGPLv3 4(e)要求提供“安装信息”，以便根据 GPLv3 第6条在“用户产品”中安装修改版本的库。如果库的最小对应源代码未在LGPLv3 4(d)(1)下提供，LGPLv3 4(e)重申必须按照 GPLv3 第6条合规地提供“安装信息”。

All other provisions of GPLv3 are in force as previously described, and are not excepted by the additional permission granted in LGPLv3.

除了LGPLv3授予的附加权限之外，GPLv3的所有其他规定均如先前所述生效，并没有任何例外。

If the distributor of the combined work intends not to distribute or offer the source code of the LGPL'd components, the LGPL'd work must be separately distributed (subject to source code delivery requirements as part of that separate distribution) and packaged in a "shared library" mechanism, which means that it:

如果组合作品的分发者不打算分发或提供 LGPL 组件的源代码，LGPL 作品必须单独分发（以源代码交付为准 要求作为该单独分发的一部分）并打包在 “共享库”机制，这意味着它：

4(d)(1): uses at run time a copy of the library already present on the user's computer system, rather than copying library functions into the executable, and

如果组合作品的分发者不打算分发或提供LGPL组件的源代码，则必须单独分发LGPL作品（作为该单独分发的一部分，需满足源代码交付要求），并将其打包在“共享库”机制中，这意味着：

4(d)(2): will operate properly with a modified version of the library, if the user installs one, as long as the modified version is interface-compatible with the version that the work was made with.

LGPLv3 4(d)(2)：如果用户安装了与创建该作品的版本兼容的修改版本的库，那么作品将能够与该修改版本正确地运行。

Taken all together, LGPLv3 *§*4's primary implications for redistributors are two-fold, as follows:

综合而言，LGPLv3 第4条对于再分发者的主要影响有以下两个方面：

If you create a program that links through a shared library mechanism to a work that is separately distributed under LGPLv3, then you can distribute the resultant program under a license of your choice and you need not convey the LGPLv3'd work's source code. If you distribute the library along with your program, or are the separate distributor of the work in another context or as another product, you must distribute its corresponding source under the terms of LGPLv3 or GPLv3-or-later.

如果你创建一个通过共享库机制链接到在LGPLv3下单独分发的作品的程序，那么你可以将生成的程序在你选择的许可下分发，而且你不需要传达LGPLv3下的作品源代码。如果你将库与你的程序一起分发，或者在另一个上下文或另一个产品中作为独立分发者分发作品，那么你必须根据LGPLv3或GPLv3或后续版本的条款分发相应的源代码。

If you choose to statically link or otherwise combine your program with an LGPLv3'd work via mech- anisms other than a shared library, you may choose your own license for the work provided the license terms limitations for user modification, reverse engineering and debugging are met, and given that the LGPL'd components are still governed by LGPL's terms. You must offer or provide CCS for the LGPL'd components. The source code material provided must be sufficient to regenerate the combined work with a user-modified version of the LGPL'd components.

如果您选择通过除共享库以外的机制静态链接或以其他方式组合您的程序与LGPLv3的作品，则可以选择自己的许可证，前提是符合用户修改、反向工程和调试的许可条款限制，并且LGPL的组件仍受LGPL的条款约束。您必须提供或提供LGPL组件的CCS。提供的源代码材料必须足以使用LGPL的组件的用户修改版本重新生成组合工作。


## CHAPTER 12　INTEGRATING THE GPL INTO BUSINESS PRACTICES

## 第12章 将 GPL 整合到商业实践中

Since GPL'd software is now extremely prevalent through the industry, it is useful to have some basic knowledge about using GPL'd software in business and how to build business models around GPL'd software.

由于 GPL 授权的软件现在在行业中非常普遍，因此了解在商业中使用GPL授权的软件以及如何围绕GPL授权的软件构建商业模型是非常有用的。

### 12.1 Using GPL'd Software In-House

### 12.1 在企业内部使用 GP L授权的软件

As discussed in Sections [3.1](#gplv2-0-freedom-to-run) and [7.2](#gplv2-5-acceptance-copyright-style) of this tutorial, the GPL only governs the activities of copying, modifying and distributing software programs that are not governed by the license. Thus, in FSF's view, simply installing the software on a machine and using it is not controlled or limited in any way by the GPL. Using Free Software in general requires substantially fewer agreements and less license compliance activity than any known proprietary software.

正如本教程第3.1节和7.2节中所讨论的，GPL仅控制未受许可证管辖的软件程序的复制、修改和分发活动。因此，根据FSF的观点，简单地在机器上安装软件并使用它并不受GPL的任何控制或限制。总的来说，使用自由软件所需的协议和许可证合规活动比任何已知的专有软件都要少得多。

Even if a company engages heavily in copying the software throughout the enterprise, such copying is not only permitted by GPLv2 1 and 3, but it is encouraged! If the company simply deploys unmodified (or even modified) Free Software throughout the organization for its employees to use, the obligations under the license are very minimal. Using Free Software has a substantially lower cost of ownership --- both in licensing fees and in licensing checking and handling -- than the proprietary software equivalents.

即使公司大量复制软件到企业中，这种复制不仅在GPLv2的第1条和第3条中是允许的，而且还被鼓励！如果公司只是部署未经修改（甚至经过修改的）自由软件供员工使用，则许可证下的义务非常少。使用自由软件的拥有成本（包括许可证费用以及许可证检查和处理方面）要比专有软件的等效物低得多。

### 12.2 Business Models

### 12.2 商业模式

Using Free Software in house is certainly helpful, but a thriving market for Free Software-oriented business models also exists. There is the traditional model of selling copies of Free Software distributions. Many companies make substantial revenue from this model. Some choose this model because they have found that for higher-end hardware, the profit made from proprietary software licensing fees is negligible. The real profit is in the hardware, but it is essential that software be stable, reliable and dependable, and the users be allowed to have unfettered access to it. Free Software, and GPL'd software in particular, is the right choice. For instance IBM can be assured that proprietary versions of the their software will not exist to compete on their hardware.

在公司内部使用自由软件确实是有帮助的，但也存在一个以自由软件为导向的商业模式兴旺的市场。有传统的模式是销售自由软件发行版的副本。许多公司从这个模式中获得了大量的收入。一些公司选择这种模式，因为他们发现对于高端硬件来说，从专有软件许可费中获得的利润微不足道。真正的利润在于硬件，但是软件必须是稳定、可靠和可信赖的，并且用户可以自由获取它。自由软件，特别是GPL软件，是正确的选择。例如，IBM可以确信，他们的软件的专有版本不会存在以与他们的硬件竞争。

For example, charging a "convenience fee" for Free Software, when set at a reasonable price (around \$60 or so), can produce some profit. Even though Red Hat's system is fully downloadable on their Web site, people still go to local computer stores and buy copies of their box set, which is simply a printed version of the manual (available under a Free license as well) and the Free Software system it documents.

例如，对于自由软件收取“便利费”，如果价格合理（大约为60美元左右），可以产生一些利润。尽管Red Hat的系统可以在他们的网站上完全下载，但人们仍然会去当地的计算机商店购买他们的盒装套装，这只是手册的打印版本（同样可在自由许可下获得）和所记录的自由软件系统。

Custom support, service, and software improvement contracts are the most widely used models for GPL'd software. The GPL is central to their success, because it ensures that the code base remains common, and that large and small companies are on equal footing for access to the technology. Consider, for example, the GNU Compiler Collection (GCC). Cygnus Solutions, a company started in the early 1990s, was able to grow steadily simply by providing services for GCC --- mostly consisting of new ports of GCC to different or new, embedded targets. Eventually, Cygnus was so successful that it was purchased by Red Hat
where it remains a profitable division.

定制支持、服务和软件改进合同是GPL软件最广泛使用的模式。GPL对于它们的成功至关重要，因为它确保代码库保持共同，并且大大小小的公司在访问技术方面处于平等地位。例如，考虑GNU编译器集合（GCC）。上世纪90年代初创立的Cygnus Solutions公司，仅通过为GCC提供服务（主要包括将GCC移植到不同的或新的嵌入式目标）就能够稳步增长。最终，Cygnus取得了如此成功，以至于被Red Hat收购，现在它仍然是一个有利可图的部门。

However, there are very small companies that compete in this space. Modern industry demands the trust created by GPL protected code-bases. Companies can cooperate on the software and improve it for everyone. Meanwhile, companies who rely on GCC for their work are happy to pay for improvements, and for ports to new target platforms. Nearly all the changes fold back into the standard versions, and those forks that exist remain freely available.

然而，在这个领域中也有一些非常小的公司在竞争。现代产业需要由GPL保护的代码库所创造的信任。公司可以合作开发软件，并为每个人都进行改进。与此同时，那些依赖GCC进行工作的公司很乐意为改进和移植到新的目标平台付费。几乎所有的变化都会被折叠回标准版本中，而那些存在的分支仍然可以自由获取。

A final common business model that is perhaps the most controversial is proprietary relicensing of a GPL'd code base. This is only an option for software in which a particular entity holds exclusive rights to relicense.[^12-1^] As discussed earlier in this tutorial, a copyright holder is permitted under copyright law to license a software system under her copyright as many different ways as she likes to as many different parties as she wishes.

最后一个常见的商业模式可能是最具争议的，那就是专有软件重新许可一个GPL的代码库。这只是适用于那些拥有重新许可排他性权利的软件。[^12-1^] 如本教程前面所讨论的，根据版权法，版权持有人可以根据自己的意愿以任何不同的方式将软件系统许可给尽可能多的不同方。

Some companies use this to their financial advantage with regard to a GPL'd code base. The standard version is available from the company under the terms of the GPL. However, parties can purchase separate proprietary software licensing for a fee.

一些公司利用这一点在财务上获得了利益，与GPL许可的代码库相关。 标准版本可以在公司按照GPL条款的条件下获取。 但是，各方可以通过付费购买单独的专有软件许可证。

This business model is at best problematic and at worst predatory because it means that the GPL'd code base must be developed in a somewhat monolithic way, because volunteer Free Software developers may be reluctant to assign their copyrights to the company because it will not promise to always and forever license the software as Free Software. Indeed, the company will surely use such code contributions in proprietary versions licensed for fees.

这种商业模式充其量是有问题的，最坏的情况下是掠夺性的，因为它意味着GPL许可的代码库必须以某种集中的方式进行开发，因为志愿的自由软件开发人员可能不愿将其版权分配给公司，因为公司不会承诺永远将软件许可为自由软件。事实上，该公司肯定会将这样的代码贡献用于收费许可的专有版本中。

### 12.3 Ongoing Compliance

### 12.3 持续合规

GPL compliance is in fact a very simple matter --- much simpler than typical proprietary software agreements and EULAs. Usually, the most difficult hurdle is changing from a proprietary software mindset to one that seeks to foster a community of sharing and mutual support. Certainly complying with the GPL from a users' perspective gives substantially fewer headaches than proprietary license compliance.

事实上，GPL合规实际上是一个非常简单的问题 —— 比典型的专有软件协议和最终用户许可协议(EULAs)简单得多。通常，最困难的障碍是从专有软件的心态转变为寻求培育共享和相互支持社区的心态。从用户的角度来看，遵守GPL比遵守专有许可证要简单得多，减少了很多麻烦。

For those who go into the business of distributing *modified* versions of GPL'd software, the burden is a bit higher, but not by much. The glib answer is that by releasing the whole product as Free Software, it is always easy to comply with the GPL. However, admittedly to the dismay of FSF, many modern and complex software systems are built using both proprietary and GPL'd components that are clearly and legally separate and independent works, merely aggregated together on the same device.

对于那些从事分发修改版GPL软件的业务的人来说，负担略微增加，但并不多。简单的答案是，通过将整个产品作为自由软件发布，始终很容易遵守GPL。然而，诚然让自由软件基金会(FSF)失望的是，许多现代复杂的软件系统是使用既有专有又有GPL组件构建的，这些组件在法律上明显独立并独立存在，仅仅是聚合在同一设备上。

However, it sometimes is easier, quicker, and cheaper to simply improve an existing GPL'd application than to start from scratch. In exchange for this amazing benefit, the license requires that the modifier gives back to the commons that made the work easier in the first place. It is a reasonable trade-off and a way to help build a better world while also making a profit.

然而，有时候，与其从头开始，改进现有的GPL软件可能会更容易、更快捷、更便宜。为了换取这一惊人的好处，许可证要求修改者将工作的成果回馈给共同体，因为共同体在第一时间让这项工作变得更容易。这是一个合理的权衡和一种帮助建设更美好世界同时也获得利润的方式。

Note that FSF does provide services to assist companies who need assistance in complying with the GPL. You can contact FSF's GPL Compliance Labs at *\<*<licensing@fsf.org>*\>*.

请注意，自由软件基金会(FSF)提供帮助企业遵守GPL的服务。您可以联系FSF的GPL合规实验室，电子邮件地址为*<licensing@fsf.org>*。

If you are particularly interested in matters of GPL compliance, we recommend the next two parts, which include both recommendations on good compliance and compliance case studies.

如果您特别关心GPL合规问题，我们建议阅读接下来的两个部分，其中包括有关良好合规的建议和合规案例研究。

[^12-1^]: Entities typically hold exclusive relicensing rights either by writing all the software under their own copyrights, collect- ing copyright assignments from all contributors, or by otherwise demanding unconditional relicensing permissions from all contributors via some legal agreement

[^12-1^]: 通常，实体持有独家重新许可权，方法可以是通过在其自己的版权下编写所有软件、从所有贡献者收集版权分配，或者通过某些法律协议以其他方式要求所有贡献者无条件重新许可。


# Part II A Practical Guide to GPL Compliance

# 第2部分 GPL 合规实用指南

## EXECUTIVE SUMMARY

## 概要

This is a guide to effective compliance with the GNU General Public License (GPL) and related licenses. Copyleft advocates usually seek to assist the community with GPL compliance cooperatively. This guide focuses on complying from the start, so that readers can learn to avoid enforcement actions entirely, or, at least, minimize the negative impact when enforcement actions occur. This guide introduces and explains basic legal concepts related to the GPL and its enforcement by copyright holders. It also outlines business practices and methods that lead to better GPL compliance. Finally, it recommends proper post-violation responses to the concerns of copyright holders.

这是一份有关有效遵守GNU通用公共许可证(GPL)和相关许可证的指南。Copyleft倡导者通常希望通过合作来协助社区进行GPL合规。本指南侧重于从一开始就合规，以便读者可以学习避免完全执行行动，或者至少在执行行动发生时将负面影响最小化。本指南介绍并解释与GPL及其版权持有者的执行相关的基本法律概念。它还概述了导致更好的GPL合规的业务实践和方法。最后，它建议适当的违规后应对版权持有者的关切的措施。

## CHAPTER 13 BACKGROUND

## 第13章 背景

Copyright law grants exclusive rights to authors. Authors who chose copyleft seek to protect the freedom of users and developers to copy, share, modify and redistribute the software. However, copyleft is ultimately implemented through copyright, and the GPL is primarily and by default a copyright license. (See [1.2](#how-does-software-become-free) for more about the interaction between copyright and copyleft.) Copyright law grants an unnatural exclusive control to copyright holders regarding copyright-controlled permissions related to the work. Therefore, copyright holders (or their agents) are the ultimately the sole authorities to enforce copyleft and protect the rights of users. Actions for copyright infringement are the ultimate legal mechanism for enforcement. Therefore, copyright holders, or collaborative groups of copyright holders, have historically been the actors in GPL enforcement.

版权法授予作者独占权利。选择使用copyleft的作者试图保护用户和开发人员复制、分享、修改和重新分发软件的自由。然而，copyleft最终是通过版权实施的，而GPL主要且默认是一种版权许可证。（有关版权和copyleft之间相互作用的更多信息，请参见[1.2](＃how-does-software-become-free)。）版权法在涉及作品的版权受控权限方面授予版权持有人不自然的独占控制。因此，版权持有人（或其代理人）最终是唯一的权力机构，用于执行copyleft并保护用户的权利。版权侵权行为是执行的最终法律机制。因此，版权持有人或版权持有人的协作团体在GPL执行中一直是行动者。

The earliest of these efforts began soon after the GPL was written by Richard M. Stallman (RMS) in 1989, and consisted of informal community efforts, often in public Usenet discussions.[^13-1^] Over the next decade, the Free Software Foundation (FSF), which holds copyrights in many GNU programs, was the only visible entity actively enforcing its GPL'd copyrights on behalf of the software freedom community. FSF's enforcement was generally a private process; the FSF contacted violators confidentially and helped them to comply with the license. Most violations were pursued this way until the early 2000's.

最早的这些努力始于1989年Richard M. Stallman（RMS）撰写的GPL之后不久，这些努力由非正式的社区努力组成，通常在公共的Usenet讨论中进行。[^13-1^] 在接下来的十年中，自由软件基金会（FSF）在为软件自由社区代表其GPL版权方面是唯一一个可见的实体。FSF的执行通常是一个私人流程；FSF会与侵权者进行保密联系，并帮助他们遵守许可证。大多数侵权行为都是通过这种方式来处理的，直到2000年代初期。

By that time, Linux-based systems such as GNU/Linux and BusyBox/Linux had become very common, particularly in embedded devices such as wireless routers. During this period, public ridicule of violators in the press and on Internet fora supplemented ongoing private enforcement and increased pressure on businesses to comply. In 2003, the FSF formalized its efforts into the GPL Compliance Lab, increased the volume of enforcement, and built community coalitions to encourage copyright holders to together settle amicably with violators. Beginning in 2004, Harald Welte took a more organized public enforcement approach and launched [gpl-violations.org,](http://gpl-violations.org/) a website and mailing list for collecting reports of GPL violations. On the basis of these reports, Welte successfully pursued many enforcement actions in Europe, including formal legal action. Harald earns the permanent fame as the first copyright holder to bring legal action in a court regarding GPL compliance.

到那个时候，基于Linux的系统，例如GNU/Linux和BusyBox/Linux已经非常普遍，特别是在无线路由器等嵌入式设备中。在这段时间内，对违规者的公开嘲笑在新闻媒体和互联网论坛上进行，补充了正在进行的私人执法，并增加了对企业遵守许可证的压力。2003年，FSF将其努力正式组织成GPL合规实验室，增加了执行量，并建立社区联盟，鼓励版权持有者与侵权者友好地共同解决问题。从2004年开始，Harald Welte采取了更有组织的公开执行方法，并推出了 gpl-violations.org，这是一个收集GPL侵权报告的网站和邮件列表。在这些报告的基础上，Welte成功地在欧洲追究了许多执行行动，包括正式的法律行动。Harald因成为第一个在GPL合规方面在法院提起法律诉讼的版权持有人而永久获得了名声。

In 2007, two copyright holders in BusyBox, in conjunction with the Software Freedom Conservancy ("Conservancy"), filed the first copyright infringement lawsuit based on a violation of the GPL in the USA. While lawsuits are of course quite public, the vast majority of Conservancy's enforcement actions are resolved privately via cooperative communications with violators. As both FSF and Conservancy have worked to bring individual companies into compliance, both organizations have encountered numerous violations resulting from preventable problems such as inadequate attention to licensing of upstream software, misconceptions about the GPL's terms, and poor communication between software developers and their management. This document highlights these problems and describe best practices to encourage corporate Free Software users to reevaluate their approach to GPL'd software and avoid future violations.

2007年，BusyBox的两个版权持有人与软件自由保护协会（“协会”）一起，根据违反GPL的行为在美国提起了第一起版权侵权诉讼。虽然诉讼当然是相当公开的，但绝大多数协会的执法行动都是通过与侵权者的合作沟通私下解决的。由于FSF和协会都致力于使各个公司符合许可证，因此两个组织都遇到了许多违规问题，这些问题可以通过避免诸如不充分关注上游软件的许可证、对GPL条款的误解以及软件开发人员和他们的管理之间的沟通不良等问题而防止。本文强调了这些问题，并描述了最佳实践，以鼓励企业自由软件用户重新评估其对GPL软件的处理方式并避免未来的违规行为。

[^13-1^]: One example is the public outcry over NeXT's attempt to make the Objective-C front-end to GCC proprietary. RMS, in fact, handled this enforcement action personally and the Objective-C front-end is still part of upstream GCC today.

[^13-1^]: 其中一个例子是公众对NeXT试图使GCC的Objective-C前端专有化的强烈抗议。实际上，RMS亲自处理了这个执行行动，而Objective-C前端仍然是GCC上游的一部分至今。

Both FSF and Conservancy continue GPL enforcement and compliance efforts for software under the GPL, the GNU Lesser Public License (LGPL) and other copyleft licenses. In doing so, both organizations have found that most violations stem from a few common, avoidable mistakes. All copyleft advocates hope to educate the community of commercial distributors, redistributors, and resellers on how to avoid violations in the first place, and to respond adequately and appropriately when a violation occurs.

FSF和协会都继续对使用GPL、GNU Lesser Public License (LGPL)和其他copyleft许可证的软件进行执行和合规工作。在执行过程中，两个组织发现大多数违规行为都源于一些常见的可避免错误。所有copyleft的支持者都希望教育商业分发者、再分发者和转售商社区如何避免首次违规，并在发生违规时做出足够和适当的回应。

### 13.1 Who Has Compliance Obligations?

### 13.1 谁有合规义务？

All distributors of modified or unmodified versions of copylefted works unmodified versions of the works have compliance obligations. Common methods of modifying the works include innumerable common acts, such as:

所有分销修改或未修改的copyleft作品的分发者都有合规义务。修改作品的常见方法包括无数常见的行为，例如：

- embedding those works as executable copies into a device,

- 将这些作品作为可执行副本嵌入到设备中，

- transferring a digital copy of executable copies to someone else,

- 将可执行副本的数字副本转移给其他人，

- posting a patch to the copylefted software to a public mailing list.

- 将著佐权软件的补丁发布到公共邮件列表。

Such distributors have obligations to (at least) the users to whom they (or intermediary parties) distribute those copies. In some cases, distributors have obligations to third parties not directly receiving their distribution of the works (depending on the distributors chosen licensing options, as described later in [15.1).](#binary-distribution-permission) In addition, distributors have compliance obligations to upstream parties, such as preservation of reasonable legal notices embedded in the code, and appropriate labeling of modified versions.

这些分发者有义务向他们（或中间方）分发这些副本的用户（至少）承担责任。在某些情况下，分发者对未直接接收其作品分发的第三方也有义务（取决于分发者选择的许可选项，如稍后在15.1中所述）。此外，分发者还有向上游方的合规义务，例如保留代码中嵌入的合理法律声明，并适当标记修改版本。

Online service providers and distributors alike have other compliance obligations. In general, they must refrain from imposing any additional restrictions on downstream parties. Most typically, such compliance problems arise from "umbrella licenses:" EULAs, or sublicenses that restrict downstream users' rights under copyleft. (See [7.3](#gplv2-6-gpl-my-one-and-only) and [9.13).](#gplv3-10-explicit-downstream-license)

在线服务提供商和分发商都有其他的合规义务。通常来说，他们必须避免对下游方施加任何额外的限制。这种合规问题最常见的来源是“伞形许可证”：即限制下游用户在copyleft下享有的权利的最终用户许可协议（EULA）或子许可证。（详见7.3和9.13）。

Patent holders having claims reading on GPL'd works they distribute must refrain from enforcing those claims against parties to whom they distribute. Furthermore, patent holders holding copyrights on GPLv3'd works must further grant an explicit patent license for any patent claims reading on the version they dis- tributed, and therefore cannot enforce those specific patent claims against anyone making, using or selling a work based on their distributed version. All parties must refrain from acting as a provider of services or distributor of licensed works if they have accepted, or had imposed on them by judicial action, any legal conditions that would prevent them from meeting any obligation under GPL. (See *§* [7.5,](#gplv2-7-give-software-liberty-or-give-it-death) *§* [9.14](#gplv3-11-explicit-patent-licensing) and *§* [9.15.](#gplv3-12-familiar-as-gplv2-7)

在分发 GPL 的作品时具有专利权的人必须避免对他们分发的任何一方强制执行其专利权声明。此外，持有 GPLv3 的版权者还必须为其分发版本中与专利有关的任何专利声明明确授予专利许可，因此不能对任何基于其分发版本进行制作、使用或销售的人执行这些特定的专利声明。如果任何一方接受或由司法行为强制执行任何法律条件以阻止其履行 GPL 下的任何义务，则所有各方都必须避免充当服务提供者或许可作品的分发者。 (参见 7.5, 9.14 和 9.15.)

### 13.2 What Are The Risks of Non-Compliance?

### 13.2 不合规的风险是什么？

Copyleft experts have for decades observed a significant mismatch between the assumptions most businesses make about copyleft compliance and the realities. Possibly due to excessive marketing of proprietary tools and services from the for-profit compliance industry, businesses perennially focus on the wrong concerns. This tutorial seeks to educate those businesses about what actually goes wrong, what causes disputes, and how to resolve those disputes.

多年来，知识产权专家一直观察到，大多数企业对于版权许可合规性的假设与实际情况存在显著的不匹配。可能是由于盈利合规行业过度营销专有工具和服务，企业经常关注错误的问题。本教程旨在教育这些企业关注实际出现的问题、引发争议的原因以及如何解决这些争议。

Many businesses currently invest undue resources to avoid unlikely risks that have low historical incidence of occurrence and low cost of remediation, while leaving unmanaged the risks that have historically resulted in all the litigation and other adverse outcomes. For example, some "compliance industry"[^13-2^] vendors insist that great effort must be expended to carefully list, in the menus or manuals of embedded electronics products, copyright notices for every last copyright holder that contributed to the Free Software included in the product. While nearly all Free Software licenses, including copylefts like GPL, require preservation and display of copyright notices, failure to meet this specific requirement is trivially remedied. Therefore, businesses should spend just reasonable efforts to properly display copyright notices, and note that failure to do so is simply remedied: add the missing copyright notice!

许多企业目前投入过多的资源来避免那些历史上发生率低、补救成本低的不太可能发生的风险，而忽略了那些历史上导致所有诉讼和其他不利后果的风险。例如，一些“合规产业”[^13-2^] 的供应商坚持认为，必须付出极大努力，在嵌入式电子产品的菜单或手册中仔细列出每个为产品中的自由软件做出贡献的版权持有者的版权声明。虽然几乎所有的自由软件许可证，包括类似GPL的Copyleft，都要求保存和显示版权声明，但未能满足这一具体要求是很容易纠正的。因此，企业应该花费合理的努力来正确显示版权声明，并注意未能这样做的问题是很容易解决的：只需添加缺少的版权声明即可！

[^13-2^]: “Compliance industry” refers to third-party for-profit companies that market proprietary software tools and/or consulting services that purport to aid businesses with their Free Software license compliance obligations, such as those found in GPL and other copyleft licenses. This tutorial leaves the term in quotes throughout, primarily to communicate the skepticism most of this tutorial’s authors feel regarding the mere existence of this industry. Not only do copyleft advocates object on principle to proprietary software tools in general, and to their ironic use specifically to comply with copyleft, but also to the “compliance industry” vendors’ marketing messaging, which some copyleft advocates claim as a cause in the risk misassessments discussed herein. Bradley M. Kuhn, specifically, regularly uses the term “compliance industrial complex” to analogize the types of problems in this industry to those warned against in the phrase of origin.

[^13-2^]: “合规产业”是指营利性第三方公司，它们市场推广专有软件工具和/或咨询服务，声称能够帮助企业满足其自由软件许可证合规义务，例如 GPL 和其他 Copyleft 许可证中规定的义务。本教程在整个过程中都用带引号的方式使用了这个术语，主要是为了传达本教程的大部分作者对这个产业存在的怀疑。Copyleft 支持者不仅基于原则反对专有软件工具，特别是用来遵守 Copyleft 的，而且反对“合规产业”供应商的市场营销信息，一些 Copyleft 支持者认为这些信息是导致本教程中讨论的风险错误评估的原因之一。具体来说，Bradley M. Kuhn 经常使用“合规产业复合体”这个术语来类比这个产业中存在的问题与起源短语中所警告的问题类型。

### 13.3 Understanding Who's Enforcing

### 13.3 了解谁在执法

The mismatch between actual compliance risk and compliance risk management typically results from a misunderstanding of licensor intentions. For-profit businesses often err by assuming other actors have kindred motivations. The primary enforcers of the GPL, however, have goals that for-profit businesses will find strange and perhaps downright alien.

实际合规风险与合规风险管理之间的不匹配通常是由于对许可方意图的误解而导致的。营利性企业经常错误地假设其他参与者有类似的动机。然而，GPL的主要执行者的目标可能对营利性企业来说会感到奇怪，甚至完全陌生。

Specifically, community-oriented GPL enforcement organizations (called "COGEOs" throughout the re- mainder of this tutorial) are typically non-profit charities (such as the FSF and Software Freedom Conser- vancy) who declare, as part of their charitable mission, advancement of software freedom for all users. In the USA, these COGEOs are all classified as charitable under the IRS's 501(c)(3) designation, which is reserved for organizations that have a mission to enhance the public good.

具体来说，在这个教程的剩余部分中称为“COGEOs”的社区导向的GPL执法组织通常是非营利性慈善机构（例如FSF和软件自由保护协会），它们宣布作为其慈善使命，推进所有用户的软件自由。在美国，这些COGEOs都被归类为非营利性慈善机构，根据IRS的501(c)(3)规定，这种分类是为了那些旨在增进公共福利的组织而保留的。

As such, these COGEOs enforce GPL primarily to pursue the policy goals and motivations discussed throughout this tutorial: to spread software freedom further. As such, COGEOs are unified in their primary goal to bring the violator back into compliance as quickly as possible, and redress the damage caused by the violation. COGEOs are steadfast in their position in a violation negotiation: comply with the license and respect freedom.

因此，这些COGEOs主要通过执行GPL来追求本教程中讨论的政策目标和动机：进一步推广软件自由。因此，COGEOs在其主要目标上是一致的，即尽快将违规者带回遵守许可证的轨道，并补救违规造成的损害。在违规协商中，COGEOs坚定地主张：遵守许可证并尊重自由。

Certainly, other entities do not share the full ethos of software freedom as institutionalized by COGEOs, and those entities pursue GPL violations differently. Oracle, a company that produces the GPL'd MySQL database, upon discovering GPL violations typically negotiates a proprietary software license separately for a fee. While this practice is not one a COGEO would undertake nor endorse, a copyleft license technically permits this behavior. To put a finer point on this practice already discussed in [12.2,](#business-models) copyleft advocates usually find copyleft enforcement efforts focused on extract alternative proprietary licenses distasteful at best, and a corrupt manipulation of copyleft at worst. Much to the advocates' chagrin, such for-profit enforcement efforts seem to increase rather than decrease.

当然，其他机构并不完全分享COGEO所制定的软件自由理念，这些机构以不同的方式追究GPL违规行为。甲骨文公司是一个提供GPL的MySQL数据库的公司，发现GPL违规行为后通常会单独协商收费的专有软件许可证。虽然这种做法不是COGEO会采取或支持的做法，但著佐权许可证从技术上允许这种行为。更进一步地，正如在12.2中已经讨论过的这种做法，著佐权的倡导者通常认为，着重提取替代专有许可证的著佐权执法行动充其量令人不快，最坏的情况是对著佐权的腐败操纵。令倡导者感到烦恼的是，这样的营利性执法行动似乎越来越多，而不是减少。

Thus, unsurprisingly, for-profit adopters of GPL'd software often incorrectly assume that all copyright holders seek royalties. Businesses therefore focus on the risk of so-called "accidental" (typically as the result of unsupervised activity by individual programmers) infringe copyright by incorporating "snippets" of copylefted code into their own proprietary computer program. "Compliance industry" flagship products, therefore, focus on "code scanning" services that purport to detect accidental inclusions. Such effort focuses on proprietary software development and view Free Software as a foreign interloper. Such approach not only ignores current reality that many companies build their products directly on major copylefted projects (e.g., Android vendor's use of the kernel named Linux), but also creates a culture of fear among developers, leading them into a downward spiral of further hiding their necessary reliance on copylefted software in the company's products.

因此，毫不奇怪，采用GPL授权软件的营利企业通常会错误地认为所有版权持有人都寻求版税。因此，企业关注所谓的“意外”侵犯版权的风险（通常是由个人程序员的监管不足导致），他们将“片段”的通用公共授权代码合并到自己的专有计算机程序中。因此，“合规产业”的旗舰产品便集中于声称能够检测到这些意外合并的“代码扫描”服务。这种做法关注的是专有软件开发，并将自由软件视为一个外来者。这种方法不仅忽略了当前的现实情况，即许多公司直接在重要的通用公共授权项目（例如，Android供应商使用名为Linux的内核）上构建他们的产品，而且还在开发人员之间创造了一种恐惧文化，导致他们在公司产品中进一步隐藏其对通用公共授权软件的必要依赖。

Fortunately, COGEOs regard GPL compliance failures as an opportunity to improve compliance. Every compliance failure downstream represents a loss of rights by their users. The COGEOs are the guardian of its users' and developers' rights. Their activity seeks to restore those rights, and to protect the project's contributors' intentions in the making of their software.

幸运的是，COGEO（社区导向的GPL执行组织）将GPL合规失败视为提高合规性的机会。每一次合规失败都代表着用户失去了权利。COGEO是其用户和开发人员权利的守护者。他们的活动旨在恢复这些权利，并保护项目贡献者在制作软件时的意图。


## CHAPTER 14 BEST PRACTICES TO AVOID COMMON VIOLATIONS

## 第14章 避免常见违规的最佳实践

Unlike highly permissive licenses (such as the ISC license), which typically only require preservation of copy- right notices, licensees face many important requirements from the GPL. These requirements are carefully designed to uphold certain values and standards of the software freedom community. While the GPL's re- quirements may initially appear counter-intuitive to those more familiar with proprietary software licenses, by comparison, its terms are in fact clear and quite favorable to licensees. Indeed, the GPL's terms actually simplify compliance when violations occur.

与高度宽容的许可证（如ISC许可证）通常只需要保留版权声明的要求不同，许可证持有人面临许多来自GPL的重要要求。这些要求被精心设计来维护软件自由社区的某些价值观和标准。虽然对于那些更熟悉专有软件许可证的人而言，GPL的要求可能最初似乎有些违反直觉，但与之相比，它的条款实际上是明确的并且对许可证持有人非常有利的。事实上，当出现违规时，GPL的条款实际上简化了合规性。

GPL violations occur (or, are compounded) most often when companies lack sound practices for the incorporation of GPL'd components into their internal development environment. This section introduces some best practices for software tool selection, integration and distribution, inspired by and congruent with software freedom methodologies. Companies should establish such practices before building a product based on GPL'd software.[^14-1^]

当公司在其内部开发环境中整合GPL组件时，GPL违规（或加剧）的情况最常见于公司缺乏可靠的实践。本节介绍了一些基于软件自由方法的软件工具选择、集成和分发的最佳实践。公司应在基于GPL软件构建产品之前建立这些实践。[^14-1^]

### 14.1 Evaluate License Applicability

### 14.1 评估许可证适用性

Political discussion about the GPL often centers around determining the "work" that must be licensed under GPL, or in other words, "what is the derivative and/or combined work that was created". Nearly ever esoteric question asked by lawyers seek to consider that question [^14-2^] (perhaps because that question explores exciting legal issues while the majority of the GPL deals with much more mundane ones). Of course, GPL was designed primarily to embody the licensing feature of copyleft.

关于GPL的政治讨论通常集中于确定必须在GPL下许可的“作品”，换句话说，“创作了什么派生和/或组合作品”。律师们几乎询问了每一个奇怪的问题，以考虑这个问题[^14-2^]（也许是因为这个问题探讨了令人兴奋的法律问题，而GPL的大多数内容都涉及更为平凡的问题）。当然，GPL的设计主要是体现copyleft的许可特性。

However, most companies who add complex features to and make combinations with GPL'd software are already well aware of their more complex obligations under the license that require complex legal analysis. And, there are few companies overall that engage in such activities. Thus, in practical reality, this issue is not relevant to the vast majority of companies distributing GPL'd software.

然而，大多数向GPL软件添加复杂功能并与之组合的公司已经充分了解许可证下更复杂的义务，这些义务需要进行复杂的法律分析。而且，总体上从事此类活动的公司很少。因此，在实际情况下，这个问题对于分发GPL软件的绝大多数公司来说并不相关。

Thus, experienced GPL enforcers find that few redistributors' compliance challenges relate directly to combined work issues in copyleft. Instead, the distributions of GPL'd systems most often encountered typically consist of a full operating system including components under the GPL (e.g., Linux, BusyBox) and components under the LGPL (e.g., the GNU C Library). Sometimes, these programs have been patched or slightly improved by direct modification of their sources, and thus the result is unequivocally a modified version. Alongside these programs, companies often distribute fully independent, proprietary programs, developed from scratch, which are designed to run on the Free Software operating system but do not combine with, link to, modify, derive from, or otherwise create a combined work with the GPL'd components.[^14-3^] In the latter case, where the work is unquestionably a separate work of creative expression, no copyleft provisions are invoked. The core compliance issue faced, thus, in such a situation, is not an discussion of what is or is not a combined, derivative, and/or modified version of the work, but rather, issues related to distribution and conveyance of binary works based on GPL'd
source, but without Complete, Corresponding Source.

因此，有经验的GPL执法者发现，很少有再分发者的合规挑战直接涉及到在Copyleft中的组合工作问题。相反，最常遇到的是包含GPL组件（例如Linux，BusyBox）和LGPL组件（例如GNU C库）的完整操作系统的分发。有时，这些程序通过直接修改其源代码进行修补或略微改进，因此结果是明确的修改版本。除了这些程序外，公司通常还会分发完全独立的专有程序。即那些独立开发的软件，旨在运行在自由软件操作系统上，但不与GPL的组件组合，链接，修改，派生或以其他方式创建一个结合作品。[^14-3^] 在后一种情况下，如果作品毫无疑问是一份独立的创意表达作品，则不会引用版权保护规定。因此，在这种情况下，所面临的核心合规问题不是讨论作品是否为组合，派生或修改版本，而是涉及基于GPL源代码的二进制作品的分发和传递问题，但没有提供完整的对应源代码。

[^14-1^]: This document addresses compliance with GPLv2, GPLv3, LGPLv2, and LGPLv3. Advice on avoiding the most common errors differs little for compliance with these four licenses. [18.1](#lgpl-compliance) discusses the key differences between GPL and LGPL compliance.


[^14-2^]: This tutorial in fact also addresses the issue at length in *§* [14.1.](#evaluate-license-applicability)


As such, issues of software delivery are the primary frustration for GPL enforcers. In particular, the following short list accounts for at least 95% of the GPL violations ever encountered:

因此，软件交付问题是GPL执行者主要遇到的挫折。特别是以下简短清单中至少占了95%的GPL违规行为：

The violator fails to provide required information about the presence of copylefted programs and their applicable license terms in the product they have purchased.

违规者未能提供关于他们购买的产品中存在的版权保护程序及其适用的许可证条款的所需信息。

The violator fails to reliably deliver [complete, corresponding source](#ccs-definition) (CCS) for copylefted programs the violator knew were included (i.e., the CCS is either delivered but incomplete, or is not delivered at all).

违规者未能可靠地交付违规者知道已包含的版权保护程序的完整对应源代码 (CCS)（即，CCS被交付但不完整，或者根本没有被交付）。

Requestors are ignored when they communicate with violator's published addresses requesting fulfill- ment of businesses' obligations.

当请求者通过违规者公布的地址联系请求履行义务时，被忽视。

This tutorial therefore focuses primarily on these issue. Admittedly, a tiny minority of compliance situations relate to question of derivative, combined, or modified versions of the work. Those situations are so rare, and the details from situation to situation differ greatly. Thus, such situations require a highly fact-dependent analysis and cannot be addressed in a general-purpose document such as this one.

因此，本教程主要关注这些问题。不可否认，极少数的合规情况涉及到作品的派生、合并或修改版本的问题。这些情况非常罕见，并且各种情况之间的细节差异很大。因此，这些情况需要进行高度依赖事实的分析，不能在这样一个通用性的文档中解决。

Most companies accused of violations lack a basic understanding of how to comply even in the straight- forward scenario. This document provides those companies with the fundamental and generally applicable prerequisite knowledge. For answers to rarer and more complicated legal questions, such as whether your software is a derivative or combined work of some copylefted software, consult with an
attorney.[^4^](#_bookmark182)

大多数被指控违规的公司甚至缺乏基本的理解如何在简单的情况下进行合规性操作。本文档提供了这些公司所需的基本和普遍适用的先决知识。对于更罕见和更复杂的法律问题，例如您的软件是否是某些版权保护软件的派生或合并作品，请咨询律师^4^。

This discussion thus assumes that you have already identified the "work" covered by the license, and that any components not under the GPL (e.g., applications written entirely by your developers that merely happen to run on a Linux-based operating system) distributed in conjunction with those works are separate works within the meaning of copyright law and the GPL. In such a case, the GPL requires you to provide complete corresponding source (CCS)[^5^](#_bookmark183) for the GPL'd components and your modifications thereto, but not for independent proprietary applications. The procedures described in this
document address this typical scenario.

因此，本讨论假定您已经确定了受许可证保护的“作品”，并且在与这些作品一起分发的任何未受GPL保护的组件（例如，完全由您的开发人员编写的仅恰好在基于Linux的操作系统上运行的应用程序）中，根据版权法和GPL的意义，它们是独立的作品。在这种情况下，GPL要求您提供GPL保护的组件及其修改的完整对应源代码(CCS)[^5^](#_bookmark183]，但不包括独立的专有应用程序。本文档中描述的程序解决了这种典型情况。

### 14.2 Monitor Software Acquisition

### 14.2 监控软件采购

Software engineers deserve the freedom to innovate and import useful software components to improve products. However, along with that freedom should come rules and reporting procedures to make sure that you are aware of what software that you include with your product.

软件工程师应该拥有创新和引入有用软件组件来改进产品的自由。然而，与此自由相应的应该是规则和报告程序，以确保您知道您所包含产品中的哪些软件。

The most typical response to an initial enforcement action is: "We didn't know there was GPL'd stuff in there". This answer indicates failure in the software acquisition and procurement process. Integration of third-party proprietary software typically requires a formal arrangement and management/legal oversight before the developers incorporate the software. By contrast, developers often obtain and integrate Free Software without intervention nor oversight. That ease of acquisition, however, does not mean the oversight is any less necessary. Just as your legal and/or management team negotiates terms for inclusion of any proprietary software, they should gently facilitate all decisions to bring Free Software into your product.

最典型的初步执行行动的回应是：“我们不知道里面有GPL的东西。”这个答案表明软件采购和采购流程的失败。第三方专有软件的集成通常需要正式的安排和管理/法律监督，然后开发人员才能将该软件纳入产品中。相比之下，开发人员通常无需干预或监督即可获得和集成自由软件。但是，这种获取的便利性并不意味着监督就不再必要了。正如您的法律和/或管理团队为纳入任何专有软件而协商条款一样，他们应该慢慢促进所有决定将自由软件引入您的产品。

Simple, engineering-oriented rules help provide a stable foundation for Free Software integration. For example, simply ask your software developers to send an email to a standard place describing each new Free Software component they add to the system, and have them include a brief description of how they will incorporate it into the product. Further, make sure developers use a revision control system (such as Git or Mercurial), and store the upstream versions of all software in a "vendor branch" or similar mechanism, whereby they can easily track and find the main version of the software and, separately, any local changes. Such procedures are best instituted at your project's launch. Once chaotic and poorly-sourced development processes begin, cataloging the presence of GPL'd components becomes challenging.

简单的工程规则有助于为自由软件集成提供稳定的基础。例如，只需要求您的软件开发人员将每个新的自由软件组件添加到系统中的标准位置发送电子邮件，并包括他们将如何将其集成到产品中的简要描述。此外，确保开发人员使用修订控制系统（如Git或Mercurial），并将所有软件的上游版本存储在“供应商分支”或类似机制中，从而可以轻松地跟踪和查找软件的主版本以及任何本地更改。这些程序最好在项目启动时实施。一旦混乱和低质量的开发过程开始，就会变得很难记录GPL的组件的存在。

[^14-3^]: However, these programs do often combine with LGPL'd libraries. This is discussed in detail in [18.1.](#lgpl-compliance)




*§* [9.3](#gplv3-1-understanding-ccs) of this tutorial.


Such a situation often requires use of a tool to "catch up" your knowledge about what software your product includes. Most commonly, companies choose some software licensing scanning tool to inspect the codebase. However, there are few tools that are themselves Free Software. Thus, GPL enforcers usually recommend the GPL'd [FOSSology system,](http://fossology.org/) which analyzes a source code base and produces a list of Free Software licenses that may apply to the code. FOSSology can help you build a catalog of the sources you have already used to build your product. You can then expand that into a more structured inventory and process.

这种情况通常需要使用一种工具来“跟进”了解产品包含的软件。最常见的做法是选择一些软件许可扫描工具来检查代码库。然而，很少有工具本身是自由软件。因此，GPL 执法者通常推荐 GPL 的 FOSSology 系统，它可以分析源代码库，并生成可能适用于代码的自由软件许可证列表。FOSSology 可以帮助您建立一个您已经使用的源代码的目录，然后将其扩展为更结构化的清单和流程。

### 14.3 Track Your Changes and Releases

### 14.3 跟踪你的变更与发布

As explained in further detail below, the most important component of GPL compliance is the one most often ignored: proper inclusion of CCS in all distributions of GPL'd software. To comply with GPL's CCS requirements, the distributor *must* always know precisely what sources generated a given binary distribution. In an unfortunately large number of our enforcement cases, the violating company's engineering team had difficulty reconstructing the CCS for binaries distributed by the company. Here are three simple rules to follow to decrease the likelihood of this occurrence:

如下所述，GPL合规的最重要组成部分是最常被忽略的：在所有GPL软件的发布中正确包含CCS。为了遵守GPL的CCS要求，分发者必须始终精确地知道哪些源代码生成了特定的二进制分发。在我们的许多执法案件中，违规公司的工程团队通常难以重建公司分发的二进制文件的CCS。以下是三个简单的规则，可以降低这种情况发生的可能性：

- Ensure that your developers are using revision control systems properly.

- 确保您的开发人员正确使用版本控制系统。
- Have developers mark or "tag" the full source tree corresponding to builds distributed to customers.
- 确保您的开发人员正确使用版本控制系统。

Check that your developers store all parts of the software development
in the revision control system, including readmes, build scripts,
engineers' notes, and documentation.

检查开发人员是否将软件开发的所有部分存储在版本控制系统中，包括readme、构建脚本、工程师的笔记和文档。

Your developers will benefit anyway from these rules. Developers will
be happier in their jobs if their tools already track the precise
version of source that corresponds to any deployed binary.

无论如何，您的开发人员都会受益于这些规则。如果他们的工具已经跟踪与部署的二进制文件相对应的精确源代码版本，开发人员将更加愉快地工作。

### 14.4 Avoid the "Build Guru"

### 14.4 避免“构建大师”

Too many software projects rely on only one or a very few team members
who know how to build and assemble the final released product. Such
knowledge centralization not only creates engineering redundancy
issues, but also thwarts GPL compliance. Specifically, CCS does not
just require source code, but scripts and other material that explain
how to control compilation and installation of the executable and
object code.

太多的软件项目仅依赖于一个或非常少数的团队成员，他们知道如何构建和组装最终发布的产品。这种知识集中不仅会创建工程冗余问题，还会阻碍GPL合规。具体而言，CCS不仅需要源代码，还需要脚本和其他材料，以说明如何控制可执行和目标代码的编译和安装。

Thus, avoid relying on a "build guru", a single developer who is the
only one who knows how to produce your final product. Make sure the
build process is well defined. Train every developer on the build
process for the final binary distribution, including (in the case of
embedded software) generating a final firmware image suitable for
distribution to the customer. Require developers to use revision
control for build processes. Make a rule that adding new components to
the system without adequate build instructions (or better yet,
scripts) is unacceptable engineering practice.

因此，避免依赖“构建大师”，即只有一个开发人员知道如何生成您的最终产品。确保构建过程被明确定义。对最终二进制分发的构建过程对每个开发人员进行培训，包括（在嵌入式软件的情况下）生成适合分发给客户的最终固件映像。要求开发人员在构建过程中使用版本控制。制定规则，即添加新组件到系统中，如果没有足够的构建说明（或更好的是脚本），则是不可接受的工程实践。


## CHAPTER 15 DETAILS OF COMPLIANT DISTRIBUTION

## 第15章 符合要求的发行

Distribution of GPL'd works has requirements; copyleft will not function without placing requirements on redistribution. However, some requirements are more likely to cause compliance difficult than others. This chapter[^15-1^] explains some the specific requirements placed upon distributors of GPL'd software that redistributors are most likely to overlook, yielding compliance problems.

分发GPL作品有要求；没有对再分发提出要求，共享版权也无法发挥作用。然而，有些要求比其他要求更容易导致符合要求的困难。本章[^15-1^]解释了针对GPL软件的分发商放置的一些具体要求，这些要求往往被再分发者忽视，从而导致符合要求的问题。

First, [GPLv2 1](#gplv2-1-verbatim-copying) and [GPLv2 4](#gplv2-4-termination-on-violation) require that the full license text must accompany every distribution (either in source or binary form) of each licensed work. Strangely, this requirement is responsible for a surprisingly significant fraction of compliance errors; too often, physical products lack required information about the presence of GPL'd programs and the applicable license terms. Automated build processes can and should carry a copy of the license from the the source distribution into the final binary firmware package for embedded products. Such automation usually achieves compliance regarding license inclusion requirements[^15-2^]

首先，GPLv2 1和GPLv2 4要求每个受许可作品的每个分发（无论是源代码还是二进制形式）必须附带完整的许可证文本。奇怪的是，这一要求导致了相当大比例的符合要求错误；太多的物理产品缺乏关于GPL程序的存在和适用许可证条款的必要信息。自动化的构建过程可以并且应该将许可证副本从源代码分发中携带到嵌入式产品的最终二进制固件包中。这种自动化通常可以达到符合许可证包含的要求[^15-2^]。

### 15.1 Binary Distribution Permission

### 15.1 二进制分发许可

The various versions of the GPL are copyright licenses that grant permission to make certain uses of software that are otherwise restricted by copyright law. This permission is conditioned upon compliance with the GPL's requirements.

GPL的各个版本都是版权许可证，授权在版权法限制下进行某些软件使用。这个许可是有条件的，需要遵守GPL的要求。

This section walks through the requirements (of both GPLv2 and GPLv3) that apply when you distribute GPL'd programs in binary (i.e., executable or object code) form, which is typical for embedded applications. Because a binary application derives from a program's original sources, you need permission from the copy- right holder to distribute it. 3 of GPLv2 and 6 of GPLv3 contain the permissions and conditions related to binary distributions of GPL'd programs.[^15-3^] Failure to provide or offer CCS is the single largest failure mode leading to compliance disputes.

本节介绍了适用于以二进制形式（即可执行或目标代码）分发GPL程序时（这在嵌入式应用中很常见）的要求（适用于GPLv2和GPLv3）。因为二进制应用程序是从程序的原始源代码中派生出来的，因此你需要版权持有人的许可才能分发它。GPLv2的第3条和GPLv3的第6条包含了与GPL程序的二进制分发相关的许可和条件。[^15-3^]未能提供或提供CCS是导致合规争议的最大失败模式。

GPL's binary distribution sections offer a choice of compliance methods, each of which we consider in turn. Each option refers to the "Corresponding Source" code for the binary distribution, which includes the source code from which the binary was produced. This abbreviated and simplified definition is sufficient for the binary distribution discussion in this section, but you may wish to refer back to this section after reading the thorough discussion of "Corresponding Source" that appears in []{#_bookmark188 .anchor}*§* [15.2.](#preparing-corresponding-source)

GPL的二进制分发部分提供了几种合规方法选择，我们依次考虑每种选项。每个选项都涉及二进制分发的“相应源代码”，其中包括生成二进制代码的源代码。这个缩写和简化的定义足以在本节的二进制分发讨论中使用，但是你可能希望在阅读了出现在§15.2中的“相应源代码”的详细讨论后再参考本节。

[^15-1^]: Note that this chapter refers heavily to specific provisions and language in [GPLv2 3](#_bookmark257) and [GPLv3 6.](#_bookmark260) It may be helpful to []{#_bookmark189 .anchor}review [5.2](#gplv2-3-producing-binaries) and [9.9](#gplv3-6-non-source-and-corresponding-source) first, and then have a copy of each license open while reading this section.

[^15-1^]: 注意，本章节大量涉及GPLv2 第3条和GPLv3 第6条中的特定条款和语言。在阅读本节之前，先回顾5.2和9.9，然后在阅读本节时同时查看每个许可证的内容会很有帮助。

[^15-2^]: At least one COGEO recommends the [Yocto Project,](https://www.yoctoproject.org/) since its engineers have designed such features into it build process.

[^15-2^]: 至少有一个 COGEO 建议使用 Yocto Project，因为其工程师已经将这些特性设计到了其构建过程中。

[^15-3^]: These sections cannot be fully understood in isolation; read the entire license thoroughly before focusing on any particular provision. However, once you have read and understood the entire license, look to these sections to guide compliance for binary distributions.

[^15-3^]: 这些部分不能单独完全理解；在关注任何特定条款之前，请仔细阅读整个许可证。然而，一旦你已经阅读并理解了整个许可证，请查看这些部分以指导二进制分发的合规性。

#### 15.1.1 Option (a): Source Alongside Binary

#### 15.1.1 选项（a）：与二进制文件同时提供源代码

GPLv2 3(a) and v3 6(a) embody the easiest option for providing source code: including Corresponding Source with every binary distribution. While other options appear initially less onerous, this option invari- ably minimizes potential compliance problems, because when you distribute Corresponding Source with the binary, *your GPL obligations are satisfied at the time of distribution*. This is not true of other options, and for this reason, we urge you to seriously consider this option. If you do not, you may extend the duration of your obligations far beyond your last binary distribution.

GPLv2 3(a)和GPLv3 6(a)体现了提供源代码最简单的选项：在每个二进制发布中包含相应的源代码。虽然其他选项最初似乎不那么麻烦，但这个选项不可避免地最大限度地减少了潜在的合规问题，因为当你将相应的源代码与二进制文件一起分发时，你的GPL义务在分发时就得到了满足。其他选项并非如此，因此我们敦促你认真考虑此选项。如果你不这样做，你可能会将你的义务延长到最后一个二进制分发之后。

Compliance under this option is straightforward. If you ship a product that includes binary copies of GPL'd software (e.g., in firmware, or on a hard drive, CD, or other permanent storage medium), you can store the Corresponding Source alongside the binaries. Alternatively, you can include the source on a CD or other removable storage medium in the box containing the product.

按照此选项的合规性很简单。如果你发布的产品包含GPL软件的二进制副本（例如在固件中或存储在硬盘驱动器、CD或其他永久存储介质上），则可以将相应的源代码与二进制文件一起存储。或者，你可以在产品所在的盒子里包含一个 CD 或其他可移动存储介质，上面包含源代码。

GPLv2 refers to the various storage mechanisms as "medi\[a\] customarily used for software interchange". While the Internet has attained primacy as a means of software distribution where super-fast Internet connections are available, GPLv2 was written at a time when downloading software was not practical (and was often impossible). For much of the world, this condition has not changed since GPLv2's publication, and the Internet still cannot be considered "a medium customary for software interchange". GPLv3 clarifies this matter, requiring that source be "fixed on a durable physical medium customarily used for software interchange". This language affirms that option (a) requires binary redistributors to provide source on a physical medium.

GPLv2将各种存储机制称为“软件交换习惯上使用的介质”。虽然在超快速互联网连接可用的情况下，互联网已经成为软件分发的主要手段，但GPLv2是在下载软件不可行（并且经常是不可能的）的时代编写的。对于世界上大部分地区而言，自GPLv2出版以来，这种情况并没有改变，因此互联网仍不能被视为“软件交换的常规介质”。GPLv3澄清了这一点，要求源代码“固定在常规用于软件交换的耐用物理介质上”。这种语言确认了选项（a）要求二进制再分发者在物理介质上提供源代码。

Please note that while selection of option (a) requires distribution on a physical medium, voluntary distribution via the Internet is very useful. This is discussed in detail in *§* [15.1.2.](#option-b-the-offer)

请注意，虽然选择选项（a）需要通过物理介质分发，但自愿通过互联网分发非常有用。这在15.1.2.中详细讨论。

#### 15.1.2 Option (b): The Offer

#### 15.1.2 选项（b）：提供源代码

Many distributors prefer to ship only an offer for source with the binary distribution, rather than the complete source package. This option has value when the cost of source distribution is a true per-unit cost. For example, this option might be a good choice for embedded products with permanent storage too small to fit the source, and which are not otherwise shipped with a CD but *are* shipped with a manual or other printed material.

许多分发者更喜欢仅随二进制分发提供源代码，而不是完整的源代码包。当源代码分发成本是真正的单位成本时，这个选项是有价值的。例如，当嵌入式产品的永久存储空间太小无法容纳源代码，并且没有随盘（CD）或其他印刷材料一起发送时，这个选项可能是一个好的选择。

However, this option increases the duration of your obligations dramatically. An offer for source must be good for three full years from your last binary distribution (under GPLv2), or your last binary or spare part distribution (under GPLv3). Your source code request and provisioning system must be designed to last much longer than your product life cycle. Thus, it also increases your compliance costs in the long run. In addition, if you are required to comply with the terms of GPLv2, you **cannot** use a network service to provide the source code. For GPLv2, the source code offer is fulfilled only with physical media. This usually means that you must continue to produce an up-to-date "source code CD" for years after the product's end-of-life.

然而，这个选项会显著增加你的义务期限。根据GPLv2，源代码邀请必须在你的最后一个二进制分发之后保持三年有效期，或在GPLv3下，你的最后一个二进制或备件分发之后保持三年有效期。你的源代码请求和提供系统必须设计得比你的产品生命周期长得多。因此，它也会增加你长期的合规成本。此外，如果你需要遵守GPLv2的条款，则不能使用网络服务提供源代码。对于GPLv2，只有在实体媒介上提供源代码邀请才能履行义务。这通常意味着你必须在产品的生命周期结束后多年继续生产最新的“源代码CD”。

Under GPLv2, it is acceptable and advisable for your offer for source code to include an Internet link for downloadable source *in addition* to offering source on a physical medium. This practice enables those with fast network connections to get the source more quickly, and typically decreases the number of physical media fulfillment requests. (GPLv3 6(b) permits provision of source with a public network-accessible distribution only and no physical media. We discuss this in detail at the end of this section.)

根据GPLv2，你的源代码邀请可以包括可下载源代码的Internet链接，并且建议这么做，除了提供实体媒介的源代码。这种做法可以使那些拥有快速网络连接的人更快地获取源代码，并且通常会减少实体媒介履行请求的数量。（GPLv3 6(b)仅允许在公共网络可访问分发源代码，不提供实体媒介。我们在本节末尾详细讨论此问题。）

The following is a suggested compliant offer for source under GPLv2 (and is also acceptable for GPLv3) that you would include in your printed materials accompanying each binary distribution:

以下是在每个二进制分发品附带的印刷材料中建议的符合GPLv2（也适用于GPLv3）的源代码提供方案：

>The software included in this product contains copyrighted software that is licensed under the GPL. A copy of that license is included in this document on page *X*. You may obtain the complete Corresponding Source code from us for a period of three years after our last shipment of this product, which will be no earlier than 2011-08-01, by sending a money order or check for \$5 to:
>
>GPL Compliance Division
>
>Our Company
>
>Any Town, US 99999
>
>Please write "source for product *Y* " in the memo line of your payment.
>
>You may also find a copy of the source at <http://www.example.com/sources/Y/>. This offer is valid to anyone in receipt of this information.

>此产品中包含根据GPL许可的受版权保护的软件。该许可证的副本已包含在本文档的第X页中。你可以通过发送5美元的汇票或支票到以下地址，获得我们提供的该产品最后一次装运后三年内的完整的对应源代码：
>
>GPL合规部门
>
>我们公司
>
>Any Town, US 99999
>
>请在付款单的备忘录栏中写上“产品Y的源代码”。
>
>你还可以在 <http://www.example.com/sources/Y/> 找到源代码的副本。此提供方案适用于所有收到此信息的人。

There are a few important details about this offer. First, it requires a copying fee. GPLv2 permits "a charge no more than your cost of physically performing source distribution". This fee must be reasonable. If your cost of copying and mailing a CD is more than around \$10, you should perhaps find a cheaper CD stock and shipment method. It is simply not in your interest to try to overcharge the community. Abuse of this provision in order to make a for-profit enterprise of source code provision will likely trigger enforcement action.

提供源代码有几个重要的细节。首先，要求授权费。GPLv2 授权你“收取不超过你实际分发源代码成本的费用”。收费必须合理。如果你复制和邮寄一张 CD 的费用超过10美元，你可能需要找更便宜的 CD 店和邮寄方式。简单来说，从社区盈利不是你的目的。滥用此条款建立靠源代码盈利的企业可能会引发执行行动。

Second, note that the last line makes the offer valid to anyone who requests the source. This is because v2 3(b) requires that offers be "to give any third party" a copy of the Corresponding Source. GPLv3 has a similar requirement, stating that an offer must be valid for "anyone who possesses the object code". These requirements indicated in v2 3(c) and v3 6(c) are so that noncommercial redistributors may pass these offers along with their distributions. Therefore, the offers must be valid not only to your customers, but also to anyone who received a copy of the binaries from them. Many distributors overlook this requirement and assume that they are only required to fulfill a request from their direct customers.

其次，注意最后一行规定了向任何要求源代码的人提供源代码都是有效的。这是因为第2版3(b)要求了向“任何第三方”提供相应源代码的副本。GPLv3 有相似的要求，声明了提供源代码必须是向“任何拥有目标代码的人”都是有效的。第2版 3(c) 和第3版 6(c) 中指出的这些要求是为了让非商业再分发者可以与他们的分发一起传递。 因此，提供源代码必须不仅对你的客户有效，而且对从他们那里收到二进制文件副本的任何人都必须有效。 许多分销商忽视了这一要求，并认为他们只需要满足直接客户的要求。

The option to provide an offer for source rather than direct source distribution is a special benefit to companies equipped to handle a fulfillment process. GPLv2 3(c) and GPLv3 6(c) avoid burdening noncommercial, occasional redistributors with fulfillment request obligations by allowing them to pass along the offer for source as they received it.

提供源代码而不是直接分发源代码对有能力履行流程的公司来说是特殊的好处。GPLv2 3(c)和GPLv3 6(c)允许非商业性、偶尔地再分发者在收到请求时提供源代码，从而避免履行请求义务的负担。

Note that commercial redistributors cannot avail themselves of the option (c) exception, and so while your offer for source must be good to anyone who receives the offer (under v2) or the object code (under v3), it *cannot* extinguish the obligations of anyone who commercially redistributes your product. The license terms apply to anyone who distributes GPL'd software, regardless of whether they are the original distributor. Take the example of Vendor *V* , who develops a software platform from GPL'd sources for use in embedded devices. Manufacturer *M* contracts with *V* to install the software as firmware in *M* 's device. *V* provides the software to *M* , along with a compliant offer for source. In this situation, *M* cannot simply pass *V* 's offer for source along to its customers. *M* also distributes the GPL'd software commercially, so *M* too must comply with the GPL and provide source (or *M* 's *own* offer for source) to *M* 's customers.

请注意，商业再分发者无法利用选项(c)的例外情况，因此，尽管你的源代码提供必须对任何接收到提供（在v2下）或目标代码（在v3下）的人有效，但它不能免除任何商业再分发你产品的人的义务。许可条款适用于任何分发GPL软件的人，无论他们是否是最初的分发者。以供应商 V 为例，该厂商从GPL源代码开发软件平台用于嵌入式设备。制造商M与V签订合同，在M的设备中安装该软件作为固件。V提供该软件给M，以及符合规定的源代码提供。在这种情况下，M不能简单地将V的源代码提供转交给其客户。因为M也在商业上分发GPL软件，所以M也必须遵守GPL并向M的客户提供源代码（或M自己的源代码提供）。

This situation illustrates that the offer for source is often a poor choice for products that your customers will likely redistribute. If you include the source itself with the products, then your distribution to your customers is compliant, and their (unmodified) distribution to their customers is likewise compliant, because both include source. If you include only an offer for source, your distribution is compliant but your customer's distribution does not "inherit" that compliance, because they have not made their own offer to accompany their distribution.

这种情况说明，对于你的客户很可能会重新分发的产品，提供源代码的选择通常不是一个好选择。如果你将源代码本身与产品一起提供，那么你向客户的分发是合规的，他们（未修改的）向他们的客户的分发同样合规，因为两者都包含源代码。如果你只提供源代码的提供，你的分发是合规的，但你的客户的分发不会“继承”这种合规性，因为他们没有提供自己的提供来伴随他们的分发。

The terms related to the offer for source are quite different if you distribute under GPLv3. Under v3, you may make source available only over a network server, as long as it is available to the general public and remains active for three years from the last distribution of your product or related spare part. Accordingly, you may satisfy your fulfillment obligations via Internet-only distribution. This makes the "offer for source" option less troublesome for v3-only distributions, easing compliance for commercial redistributors. However, before you switch to a purely Internet-based fulfillment process, you must first confirm that you can actually distribute *all* of the software under GPLv3. Some programs are indeed licensed under "GPLv2, *or any later version*" (often abbreviated "GPLv2-or-later"). Such licensing gives you the option to redistribute under GPLv3. However, a few popular programs are only licensed under GPLv2 and not "or any later version" ("GPLv2-only"). You cannot provide only Internet-based source request fulfillment for the latter programs. If you determine that all GPL'd works in your whole product allow upgrade to GPLv3 (or were already GPLv3'd to start), your offer for source may be as simple as this:

与提供源代码相关的条款在 GPLv3 下有很大不同。根据 v3，你可以仅通过网络服务器提供源代码，只要它对一般公众可用并且从你的产品或相关备件的最后分发开始保持活动状态三年。因此，你可以通过仅通过互联网分发来满足你的履行义务。这使得“提供源代码”选项对仅适用于 v3 的分发来说不那么麻烦，为商业再分发者简化了合规性。但是，在切换到纯粹基于互联网的履行流程之前，你必须首先确认你实际上可以在 GPLv3 下分发所有软件。一些程序确实是根据“GPLv2，或任何以后版本”（通常缩写为“GPLv2-或更高版本”）许可的。这种许可给了你在 GPLv3 下重新分发的选择。然而，一些流行的程序仅根据 GPLv2 许可，而不是“或任何以后版本”（“GPLv2-only”）。你不能为后者的程序提供仅基于互联网的源代码请求履行。如果你确定整个产品中的所有 GPL 软件都允许升级到 GPLv3（或已经从 GPLv3 开始），那么你的源代码提供可能像这样简单：

The software included in this product contains copyrighted software that is licensed under the GPLv3. A copy of that license is included in this document on page *X*. You may obtain the complete Corresponding Source code from us for a period of three years after our last shipment of this product and/or spare parts therefor, which will be no earlier than 2011-08-01, on our website at <http://www.example.com/sources/productnum/>.

本产品中包含受 GPLv3 许可的版权软件。该许可证的副本在本文档的第 X 页中包含。你可以在我们的网站 http://www.example.com/sources/productnum/ 上在最后一次发货和/或备件发货之后三年的时间内获取完整的相应源代码。

Under both GPLv2 and GPLv3, source offers must be accompanied by a copy of the license itself, either electronically or in print, with every distribution.

在 GPLv2 和 GPLv3 下，每次分发源代码提供必须附带许可证本身的副本，可以是电子版或印刷版。

Finally, it is unacceptable to use option (b) merely because you do not have Corresponding Source ready. We find that some companies choose this option because writing an offer is easy, but producing a source distribution as an afterthought to a hasty development process is difficult. The offer for source does not exist as a stop-gap solution for companies rushing to market with an out-of-compliance product. If you ship an offer for source with your product but cannot actually deliver *immediately* on that offer when your customers request it, you should expect an enforcement action.

最后，仅仅因为没有准备好相关源代码，就使用选项（b）是不可接受的。我们发现，有些公司选择这个选项只是因为编写提供书面源代码的声明很容易，但在匆忙的开发过程中，生产源代码分发却很困难。提供源代码的声明不是一种临时的解决方案，用于公司匆忙推出不合规产品的情况。如果你向产品中附上了提供源代码的声明，但在客户要求时无法立即履行该声明，那么你应该预期会受到执法行动。

#### 15.1.3 Option (c): Noncommercial Offers

#### 15.1.3 选项（c）：非商业提供

As discussed in the last section, GPLv2 3(c) and GPLv3 6(c) apply only to noncommercial use. These options are not available to businesses distributing GPL'd software. Consequently, companies that redis- tribute software packaged for them by an upstream vendor cannot merely pass along the offer they received from the vendor; they must provide their own offer or corresponding source to their distributees. We talk in detail about upstream software providers in *§* [18.2.](#upstream-providers)

正如上一节所述，GPLv2 3(c)和GPLv3 6(c)仅适用于非商业用途。这些选项对于分发GPL软件的企业不可用。因此，通过上游供应商打包软件的公司不能仅仅转交他们从供应商获得的提供，他们必须向他们的分发对象提供自己的提供或对应源代码。我们在18.2.小节中详细讨论了上游软件提供商的问题。

#### 15.1.4 Option 6(d) in GPLv3: Internet Distribution

#### 15.1.4 GPLv3中的选项6(d)：互联网分发

Under GPLv2, your formal provisioning options for Corresponding Source ended with 3(c). But even under GPLv2, pure Internet source distribution was a common practice and generally considered to be compliant. GPLv2 mentions Internet-only distribution almost as aside in the language, in text at the end of the section after the three provisioning options are listed. To quote that part of GPLv2 *§* 3:

根据GPLv2，与对应源代码的正式供应选项在3(c)结束。但即使在GPLv2下，纯互联网源分发也是一种常见做法，通常被认为是符合规定的。GPLv2在语言上几乎只是提到互联网分发，是在列出三个供应选项后的章节末尾的一段文字。引用GPLv2 第3条的部分内容如下：

>If distribution of executable or object code is made by offering access to copy from a designated place, then offering equivalent access to copy the source code from the same place counts as distribution of the source code, even though third parties are not compelled to copy the source along with the object code.

>如果通过提供从指定位置复制的访问来进行可执行或对象代码的分发，则提供从同一位置复制源代码的等效访问计为源代码的分发，即使第三方不必与对象代码一起复制源代码。

When that was written in 1991, Internet distribution of software was the exception, not the rule. Some FTP sites existed, but generally software was sent on magnetic tape or CDs. GPLv2 therefore mostly assumed that binary distribution happened on some physical media. By contrast, GPLv3 6(d) explicitly gives an option for this practice that the community has historically considered GPLv2-compliant.

当这段话在1991年写出来时，软件的互联网分发是例外，而不是规则。一些FTP站点存在，但通常软件是通过磁带或CD发送的。因此，GPLv2主要假定二进制分发是在某些物理媒体上发生的。相比之下，GPLv3 6(d)明确给出了这种做法的一个选项，社区历来认为这是符合GPLv2的。

Thus, you may fulfill your source-provision obligations by providing the source code in the same way and from the same location. When exercising this option, you are not obligated to ensure that users download the source when they download the binary, and you may use separate servers as needed to fulfill the requests as long as you make the source as accessible as the binary. However, you must ensure that users can easily find the source code at the time they download the binary. GPLv3 6(d) thus clarifies a point that has caused confusion about source provision in v2. Indeed, many such important clarifications are included in v3 which together provide a compelling reason for authors and redistributors alike to adopt GPLv3.

因此，你可以通过以相同的方式和从相同的位置提供源代码来履行你的源代码供应义务。在行使此选项时，你不需要确保用户在下载二进制文件时也下载源代码，并且你可以使用所需的单独服务器来满足请求，只要你使源代码与二进制文件同样易于获取即可。但是，在用户下载二进制文件时，你必须确保用户可以轻松找到源代码。因此，GPLv3 6(d)澄清了有关v2中源代码供应的一个引起混淆的问题。实际上，许多这样的重要澄清都包含在v3中，这些澄清共同为作者和再分发者采用GPLv3提供了一个有力的理由。

#### 15.1.5 Option 6(e) in GPLv3: Software Torrents

#### 15.1.5 GPLv3的选项6(e)：软件种子

Peer-to-peer file sharing arose well after GPLv2 was written, and does not easily fit any of the v2 source provision options. GPLv3 6(e) addresses this issue, explicitly allowing for distribution of source and binary together on a peer-to-peer file sharing network. If you distribute solely via peer-to-peer networks, you can exercise this option. However, peer-to-peer source distribution *cannot* fulfill your source provision obligations for non-peer-to-peer binary distributions. Finally, you should ensure that binaries and source are equally seeded upon initial peer-to-peer distribution.

对等文件共享出现在 GPLv2 之后，不容易符合任何 v2 源代码供应选项。GPLv3 6(e) 解决了这个问题，明确允许在P2P文件共享网络上同时分发源代码和二进制文件。如果你仅通过对等文件共享网络进行分发，你可以行使此选项。但是，对等文件共享的源代码分发无法满足非对等文件共享二进制分发的源代码供应义务。最后，你应确保二进制文件和源代码在初始P2P文件共享分发时被平等分布。

### 15.2 Preparing Corresponding Source

### 15.2 准备相应源代码

Most enforcement cases involve companies that have unfortunately not implemented procedures like our [14](#_bookmark176) recommendations and have no source distribution arranged at all. These companies must work backwards from a binary distribution to come into compliance. Our recommendations in [14](#_bookmark176) are designed to make it easy to construct a complete and Corresponding Source release from the outset. If you have followed those principles in your development, you can meet the following requirements with ease. If you have not, you may have substantial reconstruction work to do.

大多数执行案例涉及那些不幸没有实施像我们建议的14那样的程序，也没有安排任何源代码分发的公司。这些公司必须从二进制分发开始向后工作，以达到合规。我们在14中的建议旨在使从一开始就构建完整的相应源代码发布变得容易。如果你在开发过程中遵循了这些原则，你可以轻松满足以下要求。如果没有，你可能需要进行大量的重建工作。

#### 15.2.1 Assemble the Sources

#### 15.2.1 收集源代码

For every binary that you produce, you should collect and maintain a copy of the sources from which it was built. A large system, such as an embedded firmware, will probably contain many GPL'd and LGPL'd components for which you will have to provide source. The binary distribution may also contain proprietary components which are separate and independent works that are covered by neither the GPL nor LGPL.

对于你生成的每个二进制文件，都应该收集和维护一个从中构建出来的源代码副本。一个大型的系统，例如嵌入式固件，可能包含许多 GPL 和 LGPL 组件，你需要为其提供源代码。二进制分发还可能包含专有组件，这些组件是独立的作品，既不受 GPL 也不受 LGPL 的覆盖。

The best way to separate out your sources is to have a subdirectory for each component in your system. You can then easily mark some of them as required for your Corresponding Source releases. Collecting subdirectories of GPL'd and LGPL'd components is the first step toward preparing your release.

分离源代码的最佳方式是为系统中的每个组件都创建一个子目录。然后，你可以轻松地将其中一些标记为所需的相应源代码发布。收集 GPL 和 LGPL 组件的子目录是准备发布的第一步。

#### 15.2.2 Building the Sources

#### 15.2.2  构建源代码

Few distributors, particularly of embedded systems, take care to read the actual definition of Corresponding Source in the GPL. Consider carefully the definition, from GPLv3:

很少有分发者，特别是嵌入式系统的分发者，会注意到GPL中"对应源代码"的实际定义。仔细考虑GPLv3中的定义：

>The "Corresponding Source" for a work in object code form means all the source code needed to generate, install, and (for an executable work) run the object code and to modify the work, including scripts to control those activities.

>对于以目标代码形式提供的作品，"对应源代码"是指生成、安装和（对于可执行作品）运行目标代码以及修改该作品所需的所有源代码，包括控制这些活动的脚本。

and the definition from GPLv2:

和GPLv2中的定义：

>The source code for a work means the preferred form of the work for making modifications to it. For an executable work, complete source code means all the source code for all modules it contains, plus any associated interface definition files, plus the scripts used to control compilation and installation of the executable.

>作品的源代码是指进行修改所需的首选形式。对于可执行作品，完整的源代码是指其中包含的所有模块的源代码，以及任何相关的接口定义文件和用于控制可执行文件编译和安装的脚本。

Note that you must include "scripts used to control compilation and installation of the executable" and/or anything "needed to generate, install, and (for an executable work) run the object code and to modify the work, including scripts to control those activities". These phrases are written to cover different types of build environments and systems. Therefore, the details of what you need to provide with regard to scripts and installation instructions vary depending on the software details. You must provide all information necessary such that someone generally skilled with computer systems could produce a binary similar to the one provided.

请注意，你必须包括"用于控制编译和安装可执行文件的脚本"和/或任何"生成、安装和（对于可执行作品）运行目标代码以及修改该作品所需的所有源代码，包括控制这些活动的脚本"。这些短语被编写成覆盖不同类型的构建环境和系统的情况。因此，关于脚本和安装说明的提供细节取决于软件的细节。你必须提供所有必要的信息，以便一般熟练掌握计算机系统的人可以生成与提供的二进制文件类似的二进制文件。

Take as an example an embedded wireless device. Usually, a company distributes a firmware, which includes a binary copy of Linux[^15-4^] and a filesystem. That filesystem contains various binary programs, including some GPL'd binaries, alongside some proprietary binaries that are separate works (i.e., not derived from, nor based on freely-licensed sources). Consider what, in this case, constitutes adequate "scripts to control compilation and installation" or items "needed to generate, install and run" the GPL'd programs.

以嵌入式无线设备为例。通常，一家公司会分发一个固件，其中包括Linux[^15-4^]的二进制副本和一个文件系统。该文件系统包含各种二进制程序，包括一些GPL的二进制程序，以及一些专有的二进制程序，它们是独立的作品（即不是基于自由许可证源代码派生的或基于自由许可证源代码的）。在这种情况下，考虑什么构成足够的"用于控制编译和安装的脚本"或"生成、安装和运行"GPL的程序所需的内容。

Most importantly, you must provide some sort of roadmap that allows technically sophisticated users to build your software. This can be complicated in an embedded environment. If your developers use scripts to control the entire compilation and installation procedure, then you can simply provide those scripts to users along with the sources they act upon. Sometimes, however, scripts were never written (e.g., the information on how to build the binaries is locked up in the mind of your "build guru"). In that case, we recommend that you write out build instructions in a natural language as a detailed, step-by-step readme.

最重要的是，你必须提供某种路线图，让技术复杂的用户能够构建你的软件。在嵌入式环境中，这可能很复杂。如果你的开发人员使用脚本来控制整个编译和安装过程，那么你可以简单地将这些脚本与它们所处理的源代码一起提供给用户。然而，有时候脚本从未编写过（例如，如何构建二进制文件的信息被锁在你的“构建专家”的头脑中）。在这种情况下，我们建议你用自然语言编写详细的、逐步的构建说明。

No matter what you offer, you need to give those who receive source a clear path from your sources to binaries similar to the ones you ship. If you ship a firmware (kernel plus filesystem), and the filesystem contains binaries of GPL'd programs, then you should provide whatever is necessary to enable a reasonably skilled user to build any given GPL'd source program (and modified versions thereof), and replace the given binary in your filesystem. If the kernel is Linux, then the users must have the instructions to do the same with the kernel. The best way to achieve this is to make available to your users whatever scripts or process your engineers would use to do the same.

无论你提供什么，你都需要为那些收到源代码的人提供一个明确的路径，让他们能够从你的源代码到类似于你提供的二进制文件的文件。如果你提供了固件（内核加文件系统），并且文件系统中包含了GPL的程序二进制文件，那么你应该提供一切必要的东西，以使合理熟练的用户能够构建任何给定的GPL源代码程序（及其修改版本），并替换文件系统中的给定二进制文件。如果内核是Linux，那么用户必须有相同的指令来执行相同的操作。实现这个的最好方法是向你的用户提供你的工程师将使用的任何脚本或过程。

[^15-4^]: "Linux" refers only to the kernel, not the larger system as a whole.

[^15-4^]: “Linux” 只指内核，而不是整个系统。

These are the general details for how installation instructions work. Details about what differs when the work is licensed under LGPL is discussed in *§* [18.1,](#lgpl-compliance) and specific details that are unique to GPLv3's installation instructions are in *§* [18.4.](#user-products-and-installation-information)

这些是安装说明的一般细节。关于在作品采用LGPL许可下安装说明有何不同之处，可以参考18.1节。另外，GPLv3安装说明所特有的细节可以参考18.4节。

#### 15.2.3 What About the Compiler?

#### 15.2.3 关于编译器呢？

The GPL contains no provision that requires distribution of the compiler used to build the software. While companies are encouraged to make it as easy as possible for their users to build the sources, inclusion of the compiler itself is not normally considered mandatory. The Corresponding Source definition -- both in GPLv2 and GPLv3 -- has not been typically read to include the compiler itself, but rather things like makefiles, build scripts, and packaging scripts.

GPL中没有规定要求分发用于构建软件的编译器。虽然我们鼓励公司尽可能地让用户容易地构建源代码，但通常情况下不认为包含编译器本身是强制性的。无论是在GPLv2还是GPLv3中，“相应源代码”的定义通常不包括编译器本身，而是像makefile、构建脚本和打包脚本这样的东西。

Nonetheless, in the interest of goodwill and the spirit of the GPL, most companies do provide the compiler itself when they are able, particularly when the compiler is based on GCC or another copylefted compiler. If you have a GCC-based system, it is your prerogative to redistribute that GCC version (binaries plus sources) to your customers. We in the software freedom community encourage you to do this, since it often makes it easier for users to exercise their software freedom. However, if you chose to take this recommendation, ensure that your GCC distribution is itself compliant.

尽管如此，在善意和GPL精神的基础上，大多数公司在可能的情况下会提供编译器本身，特别是当编译器基于GCC或其他使用Copyleft协议的编译器时。如果你有一个基于GCC的系统，你有权将该GCC版本（二进制和源代码）重新分发给你的客户。我们在自由软件社区鼓励你这样做，因为这通常使用户更容易行使其软件自由。但是，如果你选择采取这个建议，请确保你的GCC发行版本身符合要求。

If you have used a proprietary, third-party compiler to build the software, then you probably cannot ship it to your customers. We consider the name of the compiler, its exact version number, and where it can be acquired as information that *must* be provided as part of the Corresponding Source. This information is essential to anyone who wishes to produce a binary. It is not the intent of the GPL to require you to distribute third-party software tools to your customer (provided the tools themselves are not based on the GPL'd software shipped), but we do believe it requires that you give the user all the essential non-proprietary facts that you had at your disposal to build the software. Therefore, if you choose not to distribute the compiler, you should include a readme about where you got it, what version it was, and who to contact to acquire it, regardless of whether your compiler is Free Software, proprietary, or internally developed.

如果你使用专有的第三方编译器构建软件，则可能无法将其发送给客户。我们认为编译器的名称、确切版本号以及其获取方式是必须作为“相应源代码”的一部分提供的信息。这些信息对于希望生成二进制文件的任何人都是必不可少的。GPL的意图不是要求你向客户分发第三方软件工具（前提是这些工具本身不是基于已分发的GPL软件），但我们确实认为它要求你向用户提供你用于构建软件的所有基本非专有信息。因此，如果你选择不分发编译器，无论你的编译器是自由软件、专有软件还是内部开发的，请在README文件中说明你获取编译器的来源、版本以及联系方式。

### 15.3 Best Practices and Corresponding Source

### 15.3 最佳实践和对应源代码

[14](#_bookmark176) and [15.2](#preparing-corresponding-source) above are closely related. If you follow the best practices outlined above, you will find that preparing your Corresponding Source release is an easier task, perhaps even a trivial one.

上面的 14 和 15.2 密切相关。如果你按照上面概述的最佳实践，你会发现准备相应源代码的发布将是一个更容易的任务，甚至可能是一个微不足道的任务。

Indeed, the enforcement process itself has historically been useful to software development teams. Devel- opment on a deadline can lead organizations to cut corners in a way that negatively impacts its development processes. We have frequently been told by violators that they experience difficulty when determining the exact source for a binary in production (in some cases because their "build guru" quit during the release cycle). When management rushes a development team to ship a release, they are less likely to keep release sources tagged and build systems well documented.

事实上，执法过程本身对软件开发团队历史上一直是有益的。在期限紧迫的开发中，组织可能会在某种程度上走捷径，从而对其开发过程产生负面影响。我们经常被侵权者告知，他们在确定正在生产的二进制文件的确切源代码时遇到了困难（在某些情况下，因为他们的“构建专家”在发布周期内离开了）。当管理层迫使开发团队发布一个版本时，他们更不可能保持发布源代码标记和构建系统记录的良好状态。

We suggest that, if contacted about a violation, product builders use GPL enforcement as an opportunity to improve their development practices. No developer would argue that their system is better for having a mysterious build system and no source tracking. Address these issues by installing a revision system, telling your developers to use it, and requiring your build guru to document his or her work!

如果你收到关于侵权的通知，我们建议产品构建者将GPL执行视为改进其开发实践的机会。没有开发人员会认为他们的系统因拥有神秘的构建系统和没有源代码跟踪而变得更好。通过安装修订系统，告诉你的开发人员使用它，并要求你的构建专家记录他或她的工作来解决这些问题！

### 15.4 Non-Technical Compliance Issues

### 15.4 非技术合规问题

Certainly, the overwhelming majority of compliance issues are, in fact, either procedural or technical. Thus, the primary material in this chapter so far has covered those issues. However, a few compliance issues do require more direct consideration of a legal situation. This portion guide does not consider those in detail, as a careful reading of the earlier chapters of Part [I](#_bookmark1) shows various places where legal considerations are necessary for considering compliance activity.

当然，绝大多数合规问题实际上都是程序上的或技术上的问题。因此，本章的主要内容到目前为止都涵盖了这些问题。然而，少数合规问题确实需要更直接地考虑法律情况。本指南的这一部分不会详细介绍这些问题，因为仔细阅读第 I 部分早期章节就可以看到，在考虑合规性活动时需要考虑法律问题的各个方面。

For example, specific compliance issues related to [GPLv2 7,](#gplv2-7-give-software-liberty-or-give-it-death) [GPLv3 7,](#gplv3-7-additional-permissions) and [GPLv3 11](#gplv3-7-additional-permissions) demand a more traditional approach to legal license compliance. Of course, such analysis and consideration can be com- plicated, and some are considered in the enforcement case studies that follow in the next part. However, compliance issues related to such sections are not rare, and, as is typical, no specific training is available for dealing with extremely rare occurrences.

例如，与 GPLv2 7、GPLv3 7 和 GPLv3 11 相关的具体合规问题需要更传统的法律许可证合规方法。当然，这样的分析和考虑可能会很复杂，并且在下一部分的执行案例研究中会涉及其中一些问题。然而，与这些部分相关的合规问题并不罕见，正如通常情况下，对于处理极为罕见的情况没有特定的培训。

### 15.5 Self-Assessment of Compliance

### 15.5 合规自我评估

Most companies that adopt copylefted software believe they have complied. Humans usually have difficult admitting their own mistakes, particularly systematic ones. Therefore, perhaps the most important necessary step to stay in compliance is a company's regular evaluation of their own compliance.

大多数采用Copyleft软件的公司都认为自己已经合规了。人们通常很难承认自己的错误，特别是系统性的错误。因此，保持合规性的最重要的必要步骤可能是公司定期评估自己的合规性。

First, exercise a request CCS for all copylefted works from all your upstream providers of software and of components embedding software. Then, perform your own CCS check on this material first, and verify that it meets the requirements. This tutorial presents later a case study of a COGEO's CCS check in [21,](#_bookmark225) which you can emulate when examining their own CCS.

首先，向所有软件和嵌入软件组件的上游提供商请求所有Copyleft作品的CCS。然后，首先对这些材料进行自己的CCS检查，并验证其是否符合要求。本教程随后将在21中提供COGEO的CCS检查案例，你可以在检查自己的CCS时进行仿效。

Second, measure all copyleft compliance from the position of the users[^15-5^] downstream from you exercising their rights under GPL. Have those users received notice of the copylefted software included in your product? Is CCS available to the users easily (preferably by automated means)? Ask yourself these questions frequently. If you cannot answer these questions with certainty in the positive, dig deeper and modify your process.

其次，从使用GPL下游用户[^15-5^]的角度度量所有Copyleft合规性。这些用户是否收到了你产品中包含的Copyleft软件的通知？用户是否能够轻松获取CCS（最好通过自动化手段）？经常问自己这些问题。如果你无法确定地回答这些问题，请深入挖掘并修改你的流程。

Avoid "compliance industry" marketing distractions and concentrate on the copylefted software you already know is in your product. Historically, the risk from a copylefted code snippet that some programmer dropped in your proprietary product careless of the consequences is a problem far more infrequent and less difficult to resolve. Efficient management of the risks of higher concern lies in making sure you can provide, for example, precisely CCS for a copy of Coreboot, the kernel named Linux, BusyBox, or GNU tar that you included in a product your company shipped two years ago than in the risk of 10 lines of GPL'd Java code an engineer accidentally pasted into the source of your ERP system.

避免“合规产业”营销分散注意力，集中精力处理你已经知道存在于你的产品中的Copyleft软件。历史上，某些程序员在你的专有产品中随意添加的Copyleft代码片段带来的风险问题远不如解决起来容易。更高关注度的风险的有效管理在于确保你可以提供例如Coreboot的副本、命名为Linux的内核、BusyBox或GNU tar的精确CCS，这些软件两年前包含在你公司发货的某个产品中，而不是在你的ERP系统源代码中无意贴入10行GPL的Java代码的风险。

Thus, reject the "compliance industry" suggestions that code scanners find and help solve fundamental compliance problems. Consider how COGEO's tend to use code scanners. FOSSology is indeed an important part of a violation investigation, but such is the last step and catches only some (usually minor) licensing notice problems. Thus, code scanners can help solve minor compliance problems once you have resolved the major ones. Code scanners do not manage risk.

因此，请拒绝“合规产业”建议，即代码扫描器可以找到和帮助解决基本的合规性问题。考虑一下COGEO的使用代码扫描器的方式。FOSSology确实是违规调查的重要组成部分，但它是最后一步，仅能发现一些（通常是较小的）许可通知问题。因此，一旦你解决了重大问题，代码扫描器可以帮助解决较小的合规问题。代码扫描器不能管理风险。

[^15-5^]: Realizing of course that user very well may not be your own customer.

[^15-5^]: 当然要意识到，用户很可能并不是你自己的客户。


## CHAPTER 16 WHEN THE LETTER COMES

## 第16章 当信来的时候

Unfortunately, many GPL violators ignore their obligations until they are contacted by a copyright holder or the lawyer of a copyright holder. You should certainly contact your own lawyer if you have received a letter alleging that you have infringed copyrights that were licensed to you under the GPL. This section outlines a typical enforcement case and provides some guidelines for response. These discussions are generalizations and do not all apply to every alleged violation. However, COGEO's in particular universally follow the processes described herein.

不幸的是，许多GPL违规者忽略了他们的义务，直到他们由版权所有者或版权律师联系持有者。如果你有，你当然应该联系你自己的律师收到一封信，声称您侵犯了版权已根据GPL授权给您。本节概述了一个典型的执法案例，并提供一些应对指南。这些讨论是概括性的，并不都适用于每一个所谓的违反。然而，COGEO特别普遍遵循此处描述的过程。

### 16.1 Communication Is Key

### 16.1 沟通是关键

GPL violations are typically only escalated when a company ignores the copyright holder's initial commu- nication or fails to work toward timely compliance. Accused violators should respond very promptly to the initial request. As the process continues, violators should follow up weekly with the copyright holders to make sure everyone agrees on targets and deadlines for resolving the situation.

GPL违规通常只会在公司忽略GPL时升级版权所有者的初步沟通或未能努力实现及时合规。被指控的违规者应非常迅速地回应最初的要求。随着过程的继续，违规者应遵循每周与版权所有者联系，以确保每个人都同意解决问题的目标和期限。

Ensure that any staff who might receive communications regarding alleged GPL violations understands how to channel the communication appropriately within your organization. Often, initial contact is addressed for general correspondence (e.g., by mail to corporate headquarters or by e-mail to general informational or support-related addresses). Train the staff that processes such communications to escalate them to someone with authority to take action. An uninformed response to such an inquiry (e.g., from a first-level technical support person) can cause negotiations to fail prematurely.

确保任何可能收到关于涉嫌违反GPL了解如何引导沟通适当地在您的组织内。通常，初次接触是用于一般通信（例如，通过邮寄给公司总部或通过电子邮件发送给一般信息或支持相关的地址）。培训处理此类通信的员工以将他们上报给有权采取行动的人。一个不知情的对此类询问的回应（例如，来自一级技术支持者）可能导致谈判过早失败。

Answer promptly by multiple means (paper letter, telephone call, and email), even if your response merely notifies the sender that you are investigating the situation and will respond by a certain date. Do not let the conversation lapse until the situation is fully resolved. Proactively follow up with synchronous communication means to be sure communications sent by non-reliable means (such as email) were received. Remember that the software freedom community generally values open communication and cooperation, and these values extend to GPL enforcement. You will generally find that software freedom developers and their lawyers are willing to have a reasonable dialogue and will work with you to resolve a violation once you open the channels of communication in a friendly way.

通过多种方式（纸质信函、电话、电子邮件），即使您的回复只是通知发件人您是调查情况，并将在特定日期前做出回应。不要让谈话停止，直到情况完全解决。以同步沟通方式主动跟进以确保通过不可靠的方式（例如电子邮件）发送的通信被已收到。请记住，软件自由社区通常重视开放的交流与合作，这些价值观延伸到GPL强制执行。您通常会发现软件自由开发商和他们的律师愿意进行合理的对话一旦您以友好的方式打开沟通渠道，我们将与您一起解决违规问题。

Furthermore, if the complaint comes from a COGEO, assume they are well-prepared. COGEO's fully investigate compliance issues before raising the issue. The claims and concerns will be substantiated, and immediate denials will likely lead the COGEO to suspect malice rather than honest mistake.

此外，如果投诉来自COGEO，假设他们是早有准备。COGEO之前全面调查合规问题提出问题。索赔和担忧将得到证实，并且立即否认可能会导致COGEO怀疑恶意而不是而不是诚实的错误。

However, the biggest and most perennial mistake that all COGEOs see during enforcement is this: failure to include the violators' software development teams in the enforcement discussions and negotiations. As described above, CCS verification and approval is the most time-consuming and difficult part of resolving most compliance matters. Without direct contact between software developers on both sides, the resolution of the technical issues involved in demonstrating that the binary distributed was built from the source provided is likely to be tortuous, expensive, and tense. Your lawyers will certainly be understandably reluctant to expose your employees to direct inquiry from potentially adverse parties. However, facilitated exchanges of information among software engineers communicating on technical subjects shortens the time to resolution, substantially reduces the cost of reaching resolution, and prevents unnecessary escalation due to mutual misunderstanding. Furthermore, such frank technical discussion will often be the only way to avoid compliance litigation once a violation has occurred.

然而，所有COGEO都看到的最大和最常犯的错误执法期间是这样的：未能包括违规者的软件执行讨论和谈判中的开发团队。作为综上所述，CCS验证认可是最解决大多数合规性的耗时且困难的部分事项。软件开发人员之间没有直接联系双方，解决涉及的技术问题证明二进制分发是从源代码构建的provided很可能是曲折的、昂贵的和紧张的。你的律师可以理解的是，您肯定不愿意让您的员工暴露在来自潜在不利方的直接询问。然而，促进软件工程师之间的信息交换技术主题大大缩短了解决问题的时间降低达成决议的成本，并防止不必要的因相互误会而升级。此外，这种坦率的技术讨论往往是避免合规的唯一途径一旦发生侵权行为。

Fortunately, these frank discussions will improve your company's relationships. Free Software develop- ment communities improve software to benefit everyone, which includes you and your company. When you use copylefted community software in your products, you are part of that community. Therefore, resolv- ing a compliance matter is an occasion to strengthen your relationship to the community, by increasing communication between your developers and the project whose work you use for business benefit.

幸运的是，这些坦率的讨论将提高贵公司的关系。自由软件开发社区得到改善使所有人受益的软件，包括您和您的公司。当您在您的产品中使用copylefted社区软件时，您那个社区的一部分。因此，解决合规问题是一个加强你与社区关系的机会，通过增加开发人员与项目之间的沟通您用于商业利益的工作。

### 16.2 Termination

### 16.2 终止

Many redistributors overlook the GPL's termination provision (GPLv2 4 and GPLv3 8). Under v2, violators forfeit their rights to redistribute and modify the GPL'd software until those rights are explicitly reinstated by the copyright holder. In contrast, v3 allows violators to rapidly resolve some violations without consequence.

许多再分发者忽略了GPL的终止条款（GPLv24和GPLv38)。在v2下，违规者将失去重新分配的权利并修改GPL软件，直到明确这些权利由版权所有者恢复。相反，v3允许违规者迅速解决一些违规行为而不承担任何后果。

If you have redistributed an application under GPLv2[^16-1^], but have violated the terms of GPLv2, you must request a reinstatement of rights from the copyright holders before making further distributions, or else cease distribution and modification of the software forever. Different copyright holders condition reinstatement upon different requirements, and these requirements can be (and often are) wholly independent of the GPL. The terms of your reinstatement will depend upon what you negotiate with the copyright holder of the GPL'd program.

如果您重新分发了一个应用程序GPLv2[^16-1^]，但是违反了GPLv2的条款，你必须要求版权所有者恢复权利在进行进一步分发之前，或者停止分发和永远修改软件。不同的版权所有者根据不同的要求条件恢复，这些要求可以（而且经常）完全独立于GPL。这您的恢复条款将取决于您与什么人谈判GPL程序的版权所有者。

Since your rights under GPLv2 terminate automatically upon your initial violation, *all your subsequent distributions* are violations and infringements of copyright. Therefore, even if you resolve a violation on your own, you must still seek a reinstatement of rights from the copyright holders whose licenses you violated, lest you remain liable for infringement for even compliant distributions made subsequent to the initial violation.

由于您在GPLv2下的权利在您的最初的违规行为，*您随后的所有分配*都是违规行为和侵犯版权。因此，即使您解决了一个自行侵权，仍须寻求恢复权利来自您违反其许可的版权所有者，以免您即使是合规分发，仍需承担侵权责任在最初的违规之后。

GPLv3 is more lenient. If you have distributed only v3-licensed programs, you may be eligible under v3 *§* 8 for automatic reinstatement of rights. You are eligible for automatic reinstatement when:

GPLv3更宽松。如果您只分发了v3许可程序，您可能有资格根据v3*§*8获得自动恢复权利。您有资格获得自动恢复什么时候：

you correct the violation and are not contacted by a copyright holder about the violation within sixty days after the correction, or you receive, from a copyright holder, your first-ever contact regarding a GPL violation, and you correct that violation within thirty days of receipt of copyright holder's notice.

您更正了违规行为并且版权所有者未与您联系在更正后六十天内通知违规行为，或您从版权所有者那里收到您的第一次联系关于违反GPL的行为，并且您在收到版权所有者的通知后三十天。

In addition to these permanent reinstatements provided under v3, violators who voluntarily correct their violation also receive provisional permission to continue distributing until they receive contact from the copyright holder. If sixty days pass without contact, that reinstatement becomes permanent. Nonetheless, you should be prepared to cease distribution during those initial sixty days should you receive a termination notice from the copyright holder.

除了v3下提供的这些永久恢复之外，自愿改正违规行为的违规者还会收到临时许可继续分发，直到他们收到来自版权所有者的联系方式。如果六十天过去了没有联系，该恢复成为永久性的。尽管如此，你应该准备在最初的六十天内停止分发应该您收到版权所有者的终止通知。

Given that much discussion of v3 has focused on its so-called more complicated requirements, it should be noted that v3 is, in this regard, more favorable to violators than v2.

鉴于对v3的大量讨论都集中在其所谓的更多复杂的要求，需要注意的是v3是，在这个考虑到，比v2对违规者更有利。

However, note that most Linux-based systems typically include some software licensed under GPLv2-only, and thus the copyright holders have withheld permission to redistribute under terms of GPLv3. In larger aggregate distributions which include GPLv2-only works (such as the kernel named Linux), redistributors must operate as if termination is immediate and permanent, since the technological remove of GPLv2-only works from the larger distribution requires much more engineering work than the negotiation required to seek restoration of rights for distribution under GPLv2-only after permanent termination.

但是，请注意大多数基于Linux的系统通常包括一些仅在GPLv2下许可的软件，以及版权所有者已拒绝根据GPLv3条款重新分发的许可。在更大的聚合发行版，其中包括GPLv2-only作品（例如名为Linux的内核），重新分配器必须像终止一样运行是直接和永久的，因为技术移除GPLv2-only适用于更大的发行版需要更多工程工作超过寻求恢复所需的谈判永久终止后仅在GPLv2下分发的权利。

[^16-1^]: This applies to all programs licensed to you under only GPLv2 ("GPLv2-only"). However, most so-called GPLv2 programs are actually distributed with permission to redistribute under GPLv2 *or any later version of the GPL* ("GPLv2-or-later"). In the latter cases, the redistributor can choose to redistribute under GPLv2, GPLv3, GPLv2-or-later or even GPLv3-or-later. Where the redistributor has chosen v2 explicitly, the v2 termination provision will always apply. If the redistributor has chosen v3, the v3 termination provision will always apply. If the redistributor has chosen GPLv2-or-later, then the redistributor may want to narrow to GPLv3-only upon violation, to take advantage of the termination provisions in v3.

[^16-1^]: 这适用于所有授权给您仅在GPLv2下（“GPLv2-only”）。然而，大多数所谓的GPLv2程序实际上是在允许重新分发的情况下分发的在GPLv2*或GPL*的任何更高版本（“GPLv2或更高版本”）下。在在后一种情况下，重新分配器可以选择重新分配GPLv2、GPLv3、GPLv2或更高版本甚至GPLv3或更高版本。在哪里再发行商明确选择了v2，即v2终止条款将永远适用。如果再分发者选择了v3，则v3终止条款将始终适用。如果再分配器有选择GPLv2或更高版本，则再分发者可能希望缩小范围GPLv3-only在违反时，利用终止v3中的规定。


## CHAPTER 17 STANDARD REQUESTS

## 第17章 标准要求

As we noted above, different copyright holders have different requirements for reinstating a violator's distri- bution rights. Upon violation, you no longer have a license under the GPL. Copyright holders can therefore set their own requirements outside the license before reinstatement of rights. We have collected below a list of reinstatement demands that copyright holders often require.

如上所述，不同的版权所有者有不同的恢复违规者发行权的要求。之上违规，您将不再拥有GPL下的许可证。版权因此，持有人可以在许可证之外设定自己的要求在恢复权利之前。我们在下面收集了一份清单版权所有者经常要求的恢复原状要求。

- **Compliance on all Free Software copyrights**. Copyright holders of Free Software often want a company to demonstrate compliance for all GPL'd software in a distribution, not just their own. A copyright holder may refuse to reinstate your right to distribute one program unless and until you comply with the licenses of all Free Software in your distribution.

- **遵守所有自由软件版权**。的版权持有人自由软件通常希望公司证明所有人的合规性发行版中的GPL软件，而不仅仅是他们自己的。版权持有人可以拒绝恢复您分发一个程序的权利除非并直到您遵守所有自由软件的许可你的分布。

- **Notification to past recipients**. Users to whom you previously distributed non-compliant software should receive a communication (email, letter, bill insert, etc.) indicating the violation, describing their rights under the GPL, and informing them how to obtain a gratis source distribution. If a customer list does not exist (such as in reseller situations), an alternative form of notice may be required (such as a magazine advertisement).

- **通知过去的收件人**。您之前联系过的用户分布式不合规软件应收到通信（电子邮件、信件、账单插页等）表明违规行为，描述他们在GPL下的权利，并告知他们如何获得免费的源代码分发。如果客户名单不存在（例如在转销商的情况下），另一种形式的通知可能是必需的（例如杂志广告）。

- **Appointment of a GPL Compliance Officer.** The software freedom community values personal accountability when things go wrong. Copyright holders often require that you name someone within the violating company officially responsible for Free Software license compliance, and that this indi- vidual serve as the key public contact for the community when compliance concerns arise.

- **任命GPL合规官。**软件自由当出现问题时，社区重视个人责任。版权所有者通常要求您在违反公司正式负责自由软件许可证合规性，并且此人是关键的公众联系人在出现合规性问题时为社区提供服务。

- **Periodic Compliance Reports.** Many copyright holders wish to monitor future compliance for some period of time after the violation. For some period, your company may be required to send regular reports on how many distributions of binary and source have occurred.

- **定期合规报告。**许多版权所有者希望在违规发生后的一段时间内监控未来的合规性。在一段时间内，您的公司可能需要定期发送报告关于发生了多少次二进制和源代码分发。

These are just a few possible requirements for reinstatement. In the context of a GPL violation, and particularly under v2's termination provision, the copyright holder may have a range of requests in exchange for reinstatement of rights. These software developers are talented professionals from whose work your company has benefited. Indeed, you are unlikely to find a better value or more generous license terms for similar software elsewhere. Treat the copyright holders with the same respect you treat your corporate partners and collaborators.

这些只是恢复的一些可能要求。在里面违反GPL的上下文，尤其是在v2终止的情况下规定，版权持有人可能有一系列的要求换取权利的恢复。这些软件开发商是有才华的专业人士，他们的工作使贵公司受益。事实上，您不太可能找到更好的价值或更慷慨的别处类似软件的许可条款。对待版权持有人与您对待您的公司合作伙伴一样尊重，并且合作者。


## CHAPTER 18 SPECIAL TOPICS IN COMPLIANCE

## 第18章 合规的特别话题

There are several other issues that are less common, but also relevant in a GPL compliance situation. To those who face them, they tend to be of particular interest.

在GPL合规情况下，还有一些不太常见但也相关的问题。对于那些面临这些问题的人，它们往往具有特别的兴趣。

### 18.1 LGPL Compliance

### 18.1 GPL 合规

GPL compliance and LGPL compliance mostly involve the same issues. As we discussed in [14.1,](#evaluate-license-applicability) questions of modified versions of software are highly fact-dependent and cannot be easily addressed in any overview document. The LGPL adds some additional complexity to the analysis. Namely, the various LGPL versions permit proprietary licensing of certain types of modified versions. These issues are discussed in greater detail in Chapter [10](#_bookmark147) and [11.](#_bookmark158) However, as a rule of thumb, once you have determined (in accordance with LGPLv3) what part of the work is the "Application" and what portions of the source are "Minimal Corresponding Source", then you can usually proceed to follow the GPL compliance rules that discussed above, replacing our discussion of "Corresponding Source" with "Minimal Corresponding Source".

GPL合规性和LGPL合规性大多涉及相同的问题。正如我们在14.1中讨论的那样，关于软件修改版本的问题高度依赖于事实，并且无法在任何概述性文件中轻易解决。LGPL在分析中增加了一些额外的复杂性。即，各种LGPL版本允许某些类型的修改版本使用专有许可证。这些问题在第10章和第11章中进行了更详细的讨论。然而，作为一个经验法则，一旦你已经确定了（按照LGPLv3的规定）工作的哪个部分是“应用程序”，源代码的哪些部分是“最小对应源代码”，那么你通常可以继续遵循上面讨论的GPL合规规则，将我们对“对应源代码”的讨论替换为“最小对应源代码”。

LGPL also requires that you provide a mechanism to combine the Application with a modified version of the library, and outlines some options for this. Also, the license of the whole work must permit "reverse engineering for debugging such modifications" to the library. Therefore, you should take care that the EULA used for the Application does not contradict this permission.

LGPL还要求你提供一种将应用程序与库的修改版本结合的机制，并概述了一些选项。此外，整个工作的许可证必须允许“反向工程调试此类修改”到库中。因此，你应该注意，应用程序使用的EULA不应违反此许可。

Thus, under the terms of LGPL, you must refrain from license terms on works based on the licensed work that prohibit replacement of the licensed components of the larger non-LGPL'd work, or prohibit decompilation or reverse engineering in order to enhance or fix bugs in the LGPL'd components.

因此，在LGPL的条款下，你必须避免授权作品的许可条款，这些作品禁止替换较大的非LGPL作品的授权组件，或禁止反汇编或反向工程以增强或修复LGPL组件。

LGPLv3 is not surprisingly easier to understand and examine from a compliance lens, since the FSF was influenced in LGPLv3's drafting by questions and comments on LGPLv2.1 over a period of years. Admittedly, LGPLv2.1 is still in wide use, and thus compliance with LGPLv2.1 remains a frequent topic you may encounter. The best advice there is careful study of Chapter [10.](#_bookmark147)

LGPLv3自然更易于从合规角度理解和审查，因为FSF在起草LGPLv3时受到了多年来关于LGPLv2.1的问题和评论的影响。值得注意的是，LGPLv2.1仍在广泛使用，因此遵守LGPLv2.1仍然是你可能遇到的频繁话题。最好的建议是仔细研究第10章。

However, to repeat a key point here made within that chapter: Note though that, since the LGPLv2.1 can be easily upgraded to GPLv2-or-later, in the worst case you simply need to comply as if the software was licensed under GPLv2. The only reason you must consider the question of whether you have a "work that uses the library" or a "work based on the library" is when you wish to take advantage of the "weak copyleft" effect of the Lesser GPL. If GPLv2-or-later is an acceptable license (i.e., if you plan to copyleft the entire work anyway), you may find this an easier option.

然而，重复一下该章节中的一个关键观点：请注意，由于LGPLv2.1可以轻松升级为GPLv2或更高版本，在最坏的情况下，你只需要按照软件受GPLv2许可证的规定来遵守。你必须考虑是否有一个“使用该库的工作”或者“基于该库的工作”的问题的

### 18.2 Upstream Providers

### 18.2 上游供应商

With ever-increasing frequency, software development (particularly for embedded devices) is outsourced to third parties. If you rely on an upstream provider for your software, note that you *cannot ignore your GPL* *compliance requirements* simply because someone else packaged the software that you distribute. If you redistribute GPL'd software (which you do, whenever you ship a device with your upstream's software in it), you are bound by the terms of the GPL. No distribution (including redistribution) is permissible absent adherence to the license terms.

越来越多的情况下，软件开发（尤其是嵌入式设备）被外包给第三方。如果你依赖上游供应商提供的软件，请注意，你不能仅因为别人打包了你分发的软件，就忽略你的GPL合规要求。如果你重新分发GPL的软件（每当你将设备带着上游提供的软件发货时，你就在重新分发），你就必须遵守GPL的条款。在未遵守许可证条款的情况下，没有任何分发（包括重新分发）是可行的。

Therefore, you should introduce a due diligence process into your software acquisition plans. This is much like the software-oriented recommendations we make in [14.](#_bookmark176) Implementing practices to ensure that you are aware of what software is in your devices can only improve your general business processes. You should ask a clear list of questions of all your upstream providers and make sure the answers are complete and accurate. The following are examples of questions you should ask:

因此，你应该在你的软件获取计划中引入尽职调查流程。这很像我们在14章中提出的面向软件的建议。采取实践来确保你了解设备中的软件内容，只能提高你的一般业务流程。你应该向所有的上游供应商提出一系列明确的问题，并确保回答完整准确。以下是你应该问的问题示例：

- What are all the licenses that cover the software in this device?

- From which upstream vendors, be they companies or individuals, did *you* receive your software before distributing it to us?

- What are your GPL compliance procedures?

- If there is GPL'd software in your distribution, we will be redistributors of this GPL'd software. What mechanisms do you have in place to aid us with compliance?

- If we follow your recommended compliance procedures, will you formally indemnify us in case we are nonetheless found to be in violation of the GPL?

- 该设备中涵盖的软件的所有许可证是什么？

- 你在将软件分发给我们之前从哪些上游供应商（无论是公司还是个人）处获得了你的软件？

- 你的GPL合规程序是什么？

- 如果你的分发中有GPL的软件，我们将成为这个GPL的软件的重新分发者。你有哪些机制来帮助我们合规？

- 如果我们遵循你推荐的合规程序，你是否会正式赔偿我们，以防我们仍然被发现违反GPL？

This last point is particularly important. Many GPL enforcement actions are escalated because of petty finger-pointing between the distributor and its upstream. In our experience, agreements regarding GPL compliance issues and procedures are rarely negotiated up front. However, when they are, violations are resolved much more smoothly (at least from the point of view of the redistributor).

最后一个问题尤其重要。许多GPL执法行动由于分销商和其上游供应商之间的琐碎指责而升级。根据我们的经验，在GPL合规问题和程序方面达成协议是很少提前谈判的。然而，当这样做时，违规处理更加顺畅（至少从再分销商的角度来看）。

Consider the cost of potential violations in your acquisition process. Using Free Software allows software vendors to reduce costs significantly, but be wary of vendors who have done so without regard for the licenses. If your vendor's costs seem "too good to be true," you may ultimately bear the burden of the vendor's inattention to GPL compliance. Ask the right questions, demand an account of your vendors' compliance procedures, and seek indemnity from them.

在你的采购过程中考虑潜在违规的成本。使用自由软件可以显著降低软件供应商的成本，但要警惕那些没有考虑许可证的供应商。如果你的供应商成本看起来“太好了”，最终你可能会承担供应商对GPL合规的忽视的负担。问对问题，要求供应商说明其合规程序，并向他们索取赔偿。

In particular, any time your vendor incorporates copylefted software, you *must* exercise your own rights as a user to request CCS for all the copylefted programs that your suppliers provided to you. Furthermore, you must ensure that CCS is correct and adequate yourself. Good vendors should help you do this, and make it easy. If those vendors cannot, pick a different vendor before proceeding with the product.

特别是当你的供应商使用具有版权保护的自由软件时，你必须行使自己作为用户的权利，要求所有供应商提供给你的受版权保护的程序的完整、正确的源代码。此外，你必须自己确保源代码是正确的和充分的。好的供应商应该帮助你做到这一点，并使其变得简单。如果供应商无法提供这样的帮助，请在继续使用该产品之前选择另一个供应商。

### 18.3 Mergers and Acquisitions

### 18.3 合并与收购

Often, larger companies often encounter copyleft licensing during a Mergers and Acquisitions (M&A) process. Ultimately, a merger or acquisition causes all of the other company's problems to become yours. Therefore, for most concerns, the acquirer "simply" must apply the compliance analysis and methodologies discussed earlier across the acquired company's entire product line. Of course, this is not so simple, as such effort may be substantial, but a well-defined process for compliance investigation means the required work, while voluminous, is likely rote.

在合并和收购（M&A）过程中，大公司通常会遇到知识共享许可证。最终，合并或收购会导致所有其他公司的问题成为你的问题。因此，对于大多数问题，收购者“只需”在收购公司的整个产品线上应用先前讨论的合规分析和方法。当然，这并不是那么简单，因为这样的努力可能是重大的，但是明确定义的合规调查流程意味着所需的工作虽然繁重，但很可能是例行公事。

A few sections of GPL require careful attention and legal analysis to determine the risk of acquisitions. Those handling M&A issues should pay particular attention to the requirements of GPLv2 7 and GPLv3 10-- 12 --- focusing on how they relate to the acquired assets may be of particular importance.

GPL的几个部分需要仔细关注和法律分析，以确定收购的风险。处理M&A问题的人员应特别注意GPLv2 第7条和GPLv3 第10 - 12条的要求——重点关注它们与所收购资产的关系可能是特别重要的。

For example, GPLv3 10 clarifies that in business acquisitions, whether by sale of assets or transfers of control, the acquiring party is downstream from the party acquired. This results in new automatic downstream licenses from upstream copyright holders, licenses to all modifications made by the acquired business, and rights to source code provisioning for the now-downstream purchaser. However, despite this aid given by explicit language in GPLv3, acquirers must still confirm compliance by the acquired (even if GPLv3 10 does assert the the acquirers rights under GPL, that does not help if the acquired is out of compliance altogether). Furthermore, for fear of later reprisal by the acquirer if a GPL violation is later discovered in the acquired's product line, the acquired may need to seek a waiver and release of from additional damages beyond a requirement to comply fully (and a promise of rights restoration) if a GPL violation by the acquired is later uncovered during completion of the acquisition or thereafter.

例如，GPLv3 第10条澄清，在商业收购中，无论是通过资产销售还是控制权转移，收购方都位于被收购方的下游。这导致上游版权持有人向下游自动授予新的下游许可证，授予所有被收购企业所做的修改的许可证，并为现在的下游购买者提供源代码供应的权利。然而，尽管GPLv3明确语言为收购者提供了帮助，但收购者仍必须确认被收购方的合规性（即使GPLv3 第10条确实声明了收购者在GPL下的权利，如果被收购方完全不合规，则这并不能帮助到收购者）。此外，由于担心被收购方的产品线中以后发现GPL违规行为会导致收购者以后受到报复，被收购方可能需要寻求豁免并免除额外的损害赔偿要求，除了完全遵守（并承诺恢复权利）的要求外，如果收购方的GPL违规行为在完成收购或之后被发现，就需要这样做。

Finally, other advice available regarding handling of GPL compliance in an M&A situation tends to ignore the most important issue: most essential copylefted software is not wholly copyrighted by the entities involved in the M&A transaction. Therefore, copyleft obligations likely reach out to the customers of all entities involved, as well as to the original copyright holders of the copylefted work. As such, notwithstanding the two paragraphs in GPLv3 10, the entities involved in M&A should read the copyleft licenses through the lens of third parties whose software freedom rights under those licenses are of equal importance to then entities inside the transaction.

在 M&A 情况下处理 GPL 合规的其他可用建议往往忽略了最重要的问题：大多数重要的共享软件并非完全由 M&A 交易涉及的实体拥有版权。因此，共享义务可能会延伸到所有实体客户，以及共享作品的原始版权持有人。因此，尽管 GPLv3 第10条中有两段话，但 M&A 中涉及的实体应该通过第三方的视角阅读共享许可证，这些第三方的软件自由权利在这些许可证下与交易内部实体的权利同等重要。

### 18.4 User Products and Installation Information

### 18.4 用户产品和安装信息

GPLv3 requires you to provide "Installation Information" when v3 software is distributed in a "User Product." During the drafting of v3, the debate over this requirement was contentious. However, the provision as it appears in the final license is reasonable and easy to understand.

GPLv3要求在分发“用户产品”中的v3软件时提供“安装信息”。在v3起草期间，对此要求的争论很激烈。然而，在最终许可证中出现的规定是合理且易于理解的。

If you put GPLv3'd software into a User Product (as defined by the license) and *you* have the ability to install modified versions onto that device, you must provide information that makes it possible for the user to install functioning, modified versions of the software. Note that if no one, including you, can install a modified version, this provision does not apply. For example, if the software is burned onto an non-field- upgradable ROM chip, and the only way that chip can be upgraded is by producing a new one via a hardware factory process, then it is acceptable that the users cannot electronically upgrade the software themselves.

如果你将GPLv3的软件放入用户产品中（根据许可证的定义），并且你有能力将修改版安装到该设备上，你必须提供信息，使用户能够安装功能齐全的修改版软件。请注意，如果没有人（包括你在内）能够安装修改版，这项规定就不适用。例如，如果软件被烧录到不可升级的ROM芯片上，唯一的升级方式是通过硬件工厂流程制造新芯片，那么用户无法电子升级软件本身是可以接受的。

Furthermore, you are permitted to refuse support service, warranties, and software updates to a user who has installed a modified version. You may even forbid network access to devices that behave out of speci- fication due to such modifications. Indeed, this permission fits clearly with usual industry practice. While it is impossible to provide a device that is completely unmodifiable[^18-1^], users are generally on notice that they risk voiding their warranties and losing their update and support services when they make modifications.[^18-1^]

此外，你被允许拒绝向安装修改版的用户提供支持服务、保修和软件更新。你甚至可以禁止因此类修改而出现规格不符的设备访问网络。事实上，这个许可与通常的行业惯例完全相符。虽然无法提供完全不可修改的设备[^18-1^]，但用户通常会注意到，当他们进行修改时，他们冒着使保修失效和失去更新和支持服务的风险。[^18-2^]

GPLv3 is in many ways better for distributors who seek some degree of device lock-down. Technical processes are always found for subverting any lock-down; pursuing it is a losing battle regardless. With GPLv3, unlike with GPLv2, the license gives you clear provisions that you can rely on when you are forced to cut off support, service or warranty for a customer who has chosen to modify.

GPLv3在许多方面对寻求某种程度的设备锁定的分发商更为有利。技术过程总是被发现用于颠覆任何锁定；追求这一点总是徒劳无功的。与GPLv2不同，GPLv3许可证在你被迫切断为已选择修改的客户提供支持、服务或保修时，为你提供了清晰的规定。

### 18.5 Beware The Consultant in Enforcers' Clothing

### 18.5 注意扮成执法者的顾问

There are admittedly portions of the GPL enforcement community that function somewhat like the [computer](http://en.wikipedia.org/wiki/Hacker_%28computer_security%29#Classifications) [security and network penetration testing hacker community.](http://en.wikipedia.org/wiki/Hacker_%28computer_security%29#Classifications) By analogy, most COGEO's consider themselves [white hats,](http://en.wikipedia.org/wiki/White_hat_%28computer_security%29) while some might appropriately call [proprietary relicensing](#business-models) by the name ["black](http://en.wikipedia.org/wiki/Hacker_%28computer_security%29#Black_hat) hats". And, to finalize the analogy, there are indeed few [grey hat](http://en.wikipedia.org/wiki/Grey_hat) GPL enforcers.

公开执法GPL的社区中，有一部分确实像计算机安全和网络渗透测试黑客社区一样运作。类比地，大多数COGEO认为自己是“白帽子”，而一些人可能恰当地将“专有重新许可”称为“黑帽子”。此外，确实有一些灰帽GPL执法者。

Grey hat GPL enforcers usually have done some community-oriented GPL enforcement themselves, typ- ically working as a volunteer for a COGEO, but make their living as a "hired gun" consultant to find GPL violations and offer to "fix them" for companies. Other such operators hold copyrights in some key piece of copylefted software and enforce as a mechanism to find out who is most likely to fund improvements on the software.

灰帽GPL执法者通常已经自己进行过一些面向社区的GPL执行，通常作为COGEO的志愿者工作，但他们通过作为“聘用枪手”顾问为公司寻找GPL违规行为并提供“修复”服务谋生。其他类似的运营商拥有某些关键的copylefted软件的版权，并强制执行以了解谁最有可能为软件改进提供资金。

A few companies report that they have formed beneficial consulting or employment relationships with developers they first encountered through enforcement. In some such cases, companies have worked with such consultants to alter the mode of use of the project's code in the company's products. More often in these cases, the communication channels opened in the course of the inquiry served other consulting purposes later.

一些公司报告称，他们已经与通过执行遇到的开发人员建立了有益的咨询或雇佣关系。在某些这样的情况下，公司已经与这些顾问合作，以改变项目代码在公司产品中的使用方式。在这些情况下，更多的是，在调查过程中开放的通信渠道后来为其他咨询目的服务。

[^18-1^]: Consider that the iPhone, a device designed primarily to restrict users' freedom to modify it, was unlocked and modified within 48 hours of its release.

[^18-1^]: 考虑到iPhone是一个旨在限制用户修改的设备，但是它在发布后的48小时内被解锁和修改。

[^18-2^]: A popular t-shirt in the software freedom community reads: "I void warranties.". Our community is well-known for modifying products with full knowledge of the consequences. GPLv3's "Installation Instructions" section merely confirms that reality, and makes sure GPL rights can be fully exercised, even if users exercise those rights at their own peril.

[^18-2^]: 软件自由社区流行的一款 T 恤衫上写着：“我无视保修条款”。我们的社区以全面了解后果的方式来修改产品而闻名。GPLv3 的“安装说明”部分仅仅确认了这一事实，并确保即使用户冒着自己的风险行使这些权利，GPL 的权利也能够被充分行使。

Feelings and opinions about this behavior are mixed within the larger copyleft community. Some see it as a reasonable business model and others renounce it as corrupt behavior. Regardless, a GPL violator should always immediately determine the motivations of the enforcer via documented, verifiable facts. For example, COGEOs such as the FSF and Conservancy have made substantial public commitments to enforce in a way that is uniform, transparent, and publicly documented. Furthermore, since these specific organizations are public charities in the USA, they are accountable to the IRS (and the public at large) in their annual Form 990 filings. Everyone may examine their revenue models and scrutinize their work.

在更广泛的copyleft社区中，人们对这种行为的感受和意见是各不相同的。有些人认为这是一个合理的商业模式，而另一些人则谴责它是腐败行为。无论如何，GPL违规者应该始终通过有文件记录的可验证事实来确定执法者的动机。例如，像自由软件基金会（FSF）和保护协会这样的COGEO已经做出了重大的公开承诺，以一种统一、透明和公开记录的方式进行执法。此外，由于这些特定组织是美国的公共慈善机构，它们在年度990表申报中对IRS（以及公众）负责。每个人都可以审查它们的收入模型和审查它们的工作。

However, entities and individuals who do GPL enforcement centered primarily around a profit motive are likely the most dangerous enforcement entities for one simple reason: an agreement to comply fully with the GPL for past and future products --- always the paramount goal to COGEOs --- may not suffice as adequate resolution for a proprietary relicensing company or grey hat GPL enforcer. Therefore, violators must consider carefully who has made the enforcement inquiry and ask when and where the enforcer made public commitments and reports regarding their enforcement work and perhaps even ask the enforcer to directly mimic CEOGEO's detailed public disclosures and follow the [standard requests for resolution](#_bookmark209) found in this document.

然而，以盈利为中心的GPL执法实体和个人可能是最危险的执法实体，原因很简单：对于一个专门进行专有再许可的公司或灰帽GPL执法者而言，完全遵守过去和未来产品的GPL协议可能不足以作为充分的解决方案。因此，违规者必须仔细考虑谁进行了执法调查，并询问执法者何时何地作出公开承诺和报告其执法工作，甚至可以要求执法者直接模仿COGEO的详细公开披露并遵循本文档中找到的标准解决请求。
\

## CHAPTER 19 CONCLUSION

## 第十九章 结论

GPL compliance need not be an onerous process. Historically, struggles have been the result of poor de- velopment methodologies and communications, rather than any unexpected application of the GPL's source code disclosure requirements.

遵循GPL并不一定需要特别复杂的流程。根据历史经验，糟糕的开发方法和沟通所导致的结果往往是争议，而非任何GPL源代码公开要求的不经意应用。

Compliance is straightforward when the entirety of your enterprise is well-informed and well-coordinated. The receptionists should know how to route a GPL source request or accusation of infringement. The lawyers should know the basic provisions of Free Software licenses and your source disclosure requirements, and should explain those details to the software developers. The software developers should use a version control system that allows them to associate versions of source with distributed binaries, have a well-documented build process that anyone skilled in the art can understand, and inform the lawyers when they bring in new software. Managers should build systems and procedures that keep everyone on target. With these practices in place, any organization can comply with the GPL without serious effort, and receive the substantial benefits of good citizenship in the software freedom community, and lots of great code ready-made for their products.

当您所在的企业可以得到充足的信息和良好的协作时，是很容易做到合规的。接洽人员应该熟悉如何发送GPL源请求或侵权指控。法务人员应该了解自由软件许可的基本条款和自有源代码的披露要求，并有义务向软件开发人员解释这些细节问题。软件开发人员应使用版本控制系统，通过该系统将源代码版本与分布式二进制文件相关联，使用一个良好的文档编辑流程，方便任何熟悉技术的人员快速理解，并可以在法务引入新软件时通知他们及时收悉。管理者应该建立一套能够让每个人都能达到目标的制度和程序。通过这些实践，任何组织都能轻而易举地遵守GPL，并在自由软件社区中获得良好公民身份的资格与福利，同时为他们的产品收获大量现成的优质代码。


# Part III Case Studies in GPL Enforcement

# 第2部分 GPL 执行案例研究

## PREFACE

## 前言

This one-day course presents the details of five different GPL compliance cases handled by FSF's GPL Compliance Laboratory. Each case offers unique insights into problems that can arise when the terms of the GPL are not properly followed, and how diplomatic negotiation between the violator and the copyright holder can yield positive results for both parties.

这个为期一天的课程详细介绍了五种不同的GPL课程。 合规案例由 FSF 的 GPL 合规实验室处理。每个案例 提供对以下条款可能出现的问题的独特见解 GPL没有得到适当的遵守，外交谈判如何 在侵权者和版权所有者之间可以产生积极的结果 双方的结果。

Attendees should have successfully completely the course, a "Detailed Study and Analysis of the GPL and LGPL," as the material from that course forms the building blocks for this material.

与会者应已成功完成课程，“详细 GPL和LGPL的研究和分析“，作为其中的材料 课程构成了该材料的基石。

This course is of most interest to lawyers who have clients or employers that deal with Free Software on a regular basis. However, technical managers and executives whose businesses use or distribute Free Software will also find the course very helpful.

本课程对有客户或 定期与自由软件打交道的雇主。然而 其业务使用或分发的技术经理和高管 自由软件也会发现这门课程非常有帮助。

These course materials are merely a summary of the highlights of the course presented. Please be aware that during the actual GPL course, class discussion supplements this printed curriculum. Simply reading it is not equivalent to attending the course.

这些课程材料只是对 课程介绍。请注意，在实际的 GPL 课程中， 课堂讨论是对这一印刷课程的补充。简单阅读 它不等同于参加课程。

## CHAPTER 20 OVERVIEW OF COMMUNITY ENFORCEMENT

## 第20章 社区执法概述

The GPL is a Free Software license with legal teeth. Unlike licenses like the X11-style or various BSD licenses, the GPL (and by extension, the LGPL) is designed to defend as well as grant freedom. We saw in the last course that the GPL uses copyright law as a mechanism to grant all the key freedoms essential in Free Software, but also to ensure that those freedoms propagate throughout the distribution chain of the software.

GPL 是一个具有法律效力的自由软件许可证。与许可证不同 像 X11 风格或各种 BSD 许可证一样，GPL（以及扩展， LGPL）旨在捍卫和给予自由。我们在 GPL使用版权法作为机制的最后一门课程 授予自由软件中必不可少的所有关键自由，但也授予 确保这些自由在整个分销链中传播 的软件。

### 20.1 Termination Begins Enforcement

### 20.1 终止开始强制执行

As we have learned, the assurance that Free Software under the GPL remains Free Software is accomplished through various terms of the GPL: 3 ensures that binaries are always accompanied with source; 2 ensures that the sources are adequate, complete and usable; 6 and 7 ensure that the license of the software is always the GPL for everyone, and that no other legal agreements or licenses trump the GPL. It is 4, however, that ensures that the GPL can be enforced.

正如我们所了解到的，保证GPL下的自由软件 仍然自由软件是通过各种条款完成的 GPL：3 确保二进制文件始终与源代码一起提供;2 确保来源充足、完整和可用;6 和 7 确保软件的许可证始终是 GPL 每个人，并且没有其他法律协议或许可证胜过 GPL。然而，正是 4 确保了 GPL 的执行。

Thus, 4 is where we begin our discussion of GPL enforcement. This clause is where the legal teeth of the license are rooted. As a copyright license, the GPL governs only the activities governed by copyright law --- copying, modifying and redistributing computer software. Unlike most copyright licenses, the GPL gives wide grants of permission for engaging with these activities. Such permissions continue, and all parties may exercise them until such time as one party violates the terms of the GPL. At the moment of such a violation (i.e., the engaging of copying, modifying or redistributing in ways not permitted by the GPL) 4 is invoked. While other parties may continue to operate under the GPL, the violating party loses their rights.

因此，4 是我们开始讨论 GPL 执行的地方。这 条款是许可证的法律牙齿扎根的地方。作为一个 版权许可，GPL 仅管辖受 版权法 ---复制、修改和重新分发计算机软件。与 大多数版权许可证，GPL给予广泛的许可 参与这些活动。此类权限将继续，并且所有 当事人可以行使这些权利，直到一方违反 GPL 的条款。在发生此类违规行为时（即 以不允许的方式进行复制、修改或重新分发 通过 GPL） 4 被调用。而其他各方可能继续运营 根据 GPL，违规方将失去其权利。

Specifically, 4 terminates the violators' rights to continue engaging in the permissions that are otherwise granted by the GPL. Effectively, their rights revert to the copyright defaults --- no permission is granted to copy, modify, nor redistribute the work. Meanwhile, 5 points out that if the violator has no rights under the GPL, they are prohibited by copyright law from engaging in the activities of copying, modifying and distributing. They have lost these rights because they have violated the GPL, and no other license gives them permission to engage in these activities governed by copyright law.

具体来说，4终止了违规者继续参与的权利 在 GPL 以其他方式授予的权限中。有效 他们的权利恢复为版权默认值---没有权限 授予复制、修改或重新分发作品的权限。同时，5 指出，如果违反者在GPL下没有权利，他们是 版权法禁止从事以下活动 复制、修改和分发。他们失去了这些权利 因为他们违反了GPL，并且没有其他许可证给他们 允许从事受版权法管辖的这些活动。

### 20.2 Ongoing Violations

### 20.2 持续的违规行为

In conjunction with 4's termination of violators' rights, there is one final industry fact added to the mix: rarely does one engage in a single, solitary act of copying, distributing or modifying software. Almost always, a violator will have legitimately acquired a copy of a GPL'd program, either making modifications or not,

结合4的终止侵权者权利，有一个 最后的行业事实补充：很少有人参与 复制、分发或修改软件的单一、单独行为。 几乎总是，违规者会合法地获得一份副本 GPL 程序，无论是否进行修改，

and then begun distributing that work. For example, the violator may have put the software in boxes and sold them at stores. Or perhaps the software was put up for download on the Internet. Regardless of the delivery mechanism, violators almost always are engaged in *ongoing* violation of the GPL.

然后开始分发该作品。例如，违规者可能 已将软件放在盒子中并在商店出售。或者也许 软件在互联网上可供下载。无论 交付机制，违反者几乎总是在持续违反GPL。

In fact, when we discover a GPL violation that occurred only once --- for example, a user group who distributed copies of a GNU/Linux system without source at one meeting --- we rarely pursue it with a high degree of tenacity. In our minds, such a violation is an educational problem, and unless the user group becomes a repeat offender (as it turns out, they never do), we simply forward along a FAQ entry that best explains how user groups can most easily comply with the GPL, and send them on their merry way.

事实上，当我们发现只发生过一次 GPL 违规时--- 例如，分发 GNU/Linux 系统副本的用户组 在一次会议上没有来源---我们很少以高 坚韧程度。在我们看来，这种侵犯是一种教育 问题，除非用户组成为累犯者（因为它 事实证明，他们从不这样做），我们只是沿着常见问题解答条目转发 最好地解释用户组如何最容易地遵守 GPL，以及 送他们快乐的路。

It is only the cases of *ongoing* GPL violation that warrant our active attention. We vehemently pursue those cases where dozens, hundreds or thousands of customers are receiving software that is out of compliance, and where the company continually offers for sale (or distributes gratis as a demo) software distributions that include GPL'd components out of compliance. Our goal is to maximize the impact of enforcement and educate industries who are making such a mistake on a large scale.

只有持续违反 GPL 的情况才值得我们 积极关注。我们强烈追查那些案件，其中数十， 成百上千的客户正在接收已淘汰的软件 合规性，以及公司持续提供销售（或 免费分发作为演示）软件分发，包括 GPL 组件不合规。我们的目标是最大限度地发挥影响力 执法和教育犯了这种错误的行业规模大。

In addition, such ongoing violation shows that a particular company is committed to a GPL'd product line. We are thrilled to learn that someone is benefiting from Free Software, and we understand that sometimes they become confused about the rules of the road. Rather than merely giving us a postmortem to perform on a past mistake, an ongoing violation gives us an active opportunity to educate a new contributor to the GPL'd commons about proper procedures to contribute to the community.

此外，这种持续的违规行为表明，特定公司是 致力于GPL产品线。我们很高兴得知 有人从自由软件中受益，我们理解这一点 有时他们对道路规则感到困惑。而 不仅仅是给我们一个事后分析来执行过去的错误，一个 持续的违规行为为我们提供了一个积极的机会来教育新的 GPL 共享资源的贡献者关于贡献的正确程序到社区。

Our central goal is not, in fact, to merely clear up a particular violation. In fact, over time, we hope that our compliance lab will be out of business. We seek to educate the businesses that engage in commerce related to GPL'd software to obey the rules of the road and allow them to operate freely under them. Just as a traffic officer would not revel in reminding people which side of the road to drive on, so we do not revel in violations. By contrast, we revel in the successes of educating an ongoing violator about the GPL so that GPL compliance becomes a second-nature matter, allowing that company to join the GPL ecosystem as a contributor.

事实上，我们的中心目标不仅仅是澄清一个特定的问题。 违反。事实上，随着时间的推移，我们希望我们的合规实验室将是 停业。我们寻求教育从事以下业务的企业 与GPL软件相关的商业，以遵守道路规则和 允许他们在他们之下自由运作。就像交通官员一样 不会陶醉于提醒人们在马路的哪一边开车 上，所以我们不陶醉于违规行为。相比之下，我们陶醉在 成功教育持续违反 GPL 的人，以便 GPL 合规成为第二天性问题，允许该公司 作为贡献者加入 GPL 生态系统。

### 20.3 How are Violations Discovered?

### 20.3 如何发现违规行为？

Our enforcement of the GPL is not a fund-raising effort; in fact, FSF's GPL Compliance Lab runs at a loss (in other words, it is subsided by our donors). Our violation reports come from volunteers, who have encountered, in their business or personal life, a device or software product that appears to contain GPL'd software. These reports are almost always sent via email to *\<*<license-violation@fsf.org>*\>*.

我们对 GPL 的执行不是筹款工作;事实上 FSF 的 GPL 合规性实验室亏本运行（换句话说，它是 由我们的捐助者补贴）。我们的违规报告来自志愿者， 在业务或个人生活中遇到设备或 似乎包含 GPL 软件的软件产品。这些报告 几乎总是通过电子邮件发送到 <license-violation@fsf.org>。

Our first order of business, upon receiving such a report, is to seek independent confirmation. When possible, we get a copy of the software product. For example, if it is an offering that is downloadable from a Web site, we download it and investigate ourselves. When it is not possible for us to actually get a copy of the software, we ask the reporter to go through the same process we would use in examining the software.

在收到这样的报告后，我们的首要任务是寻求 独立确认。如果可能，我们会获得软件的副本 产品。例如，如果它是可从 网站，我们下载它并自己调查。当它不是 我们可能实际获得该软件的副本，我们要求 报告者经历我们在检查 软件。

By rough estimation, about 95% of violations at this stage can be confirmed by simple commands. Almost all violators have merely made an error and have no nefarious intentions. They have made no attempt to remove our copyright notices from the software. Thus, given the third-party binary, tpb, usually, a simple command (on a GNU/Linux system) such as the following will find a Free Software copyright notice and GPL reference:

粗略估计，现阶段大约95%的违规行为可以 通过简单的命令确认。几乎所有违规者都只是做出了一个 错误，没有恶意。他们没有试图 从软件中删除我们的版权声明。因此，鉴于 第三方二进制文件，tpb，通常是一个简单的命令（在GNU/Linux上） 系统）如以下将找到自由软件版权 通知和 GPL 参考：

```bash
    strings tpb \| grep Copyright
```

In other words, it is usually more than trivial to confirm that GPL'd software is included.

换句话说，确认 GPL 通常不是微不足道的 包括软件。

Once we have confirmed that a violation has indeed occurred, we must then determine whose copyright has been violated. Contrary to popular belief, FSF does not have the power to enforce the GPL in all cases. Since the GPL operates under copyright law, the powers of enforcement --- to seek redress once 4 has been invoked --- lie with the copyright holder of the software. FSF is one of the largest copyright holders in the world of GPL'd software, but we are by no means the only one. Thus, we sometimes discover that while GPL'd code is present in the software, there is no software copyrighted by FSF present.

一旦我们确认确实发生了违规行为，我们必须 然后确定谁的版权被侵犯了。与流行相反 相信，FSF 无权在所有情况下执行 GPL。 由于GPL在版权法下运作，因此执行权 ---在援引4后寻求补救---与版权有关 软件持有人。FSF是最大的版权所有者之一 GPL软件的世界，但我们绝不是唯一的。 因此，我们有时会发现，虽然 GPL 代码存在于 软件，目前没有受 FSF 版权保护的软件。

In cases where FSF does not hold copyright interest in the software, but we have confirmed a violation, we contact the copyright holders of the software, and encourage them to enforce the GPL. We offer our good offices to help negotiate compliance on their behalf, and many times, we help as a third party to settle

如果 FSF 对软件不拥有版权权益， 但我们已经确认违规，我们联系了版权所有者 该软件，并鼓励他们执行GPL。我们提供我们的好 办公室代表他们帮助谈判合规性，并且很多时候， 我们作为第三方帮助解决

such GPL violations. However, what we will describe primarily in this course is FSF's first-hand experience enforcing its own copyrights and the GPL.

此类违反 GPL 的行为。但是，我们将在此主要描述的内容 课程是 FSF 执行自己的版权和GPL的第一手经验。

### 20.4 First Contact

### 20.4 第一次接触

The Free Software community is built on a structure of voluntary cooperation and mutual help. Our community has learned that cooperation works best when you assume the best of others, and only change policy, procedures and attitudes when some specific event or occurrence indicates that a change is necessary. We treat the process of GPL enforcement in the same way. Our goal is to encourage violators to join the cooperative community of software sharing, so we want to open our hand in friendship.

自由软件社区建立在自愿的结构之上 合作互助。我们的社区已经了解到 当你假设别人最好的时，合作效果最好，而且只有 在某些特定事件或 发生表示需要更改。我们对待过程 以同样的方式执行 GPL。我们的目标是鼓励违规者 加入软件共享的合作社区，所以我们想 在友谊中张开我们的手。

Therefore, once we have confirmed a violation, our first assumption is that the violation is an oversight or otherwise a mistake due to confusion about the terms of the license. We reach out to the violator and ask them to work with us in a collaborative way to bring the product into compliance. We have received the gamut of possible reactions to such requests, and in this course, we examine four specific examples of such compliance work.

因此，一旦我们确认了违规行为，我们的第一个假设是 违规行为是疏忽或其他错误，原因是 对许可条款的混淆。我们联系违规者 并要求他们以协作的方式与我们合作，以带来 产品合规。我们已经收到了可能的所有范围 对此类请求的反应，在本课程中，我们将研究四个 此类合规工作的具体示例。


## CHAPTER 21 THINKPENGUIN WIRELESS ROUTER: EXCELLENT CCS

## 第21章 THINKPENGUIN 无线路由器：优秀的 CCS

Too often, case studies examine failure and mistakes. Indeed, most of the chapters that follow herein will consider the myriad difficulties discovered in community-oriented GPL enforcement for the last two decades. However, to begin, this is a case study in how copyleft compliance can indeed be done correctly.

往往情况下，案例研究都是关于失败和错误的。事实上，下面的大多数章节将考虑过去二十年中在面向社区的 GPL 执行方面所发现的无数困难。然而，首先，这是一个关于如何正确执行版权合规性的案例研究。

This example is, in fact, more than ten years in the making. Since almost the inception of for-profit corporate adoption of Free Software, companies have requested a clear example of a model citizen to emulate. Sadly, while community-oriented enforcers have vetted uncounted thousands of "Complete, Corresponding Source" (CCS) candidates from hundreds of companies, this particular CCS release described herein is the first ever declared a "pristine example".

事实上，这个例子已经经过了十年以上的时间。自从营利性企业采用自由软件的几乎开始以来，公司们一直在要求一个明确的示范公民的清晰案例来仿效。遗憾的是，尽管面向社区的执行者们从数百家公司中审核了无数个"完整的、相应的源代码"(CCS) 候选者，但这个在此描述的 CCS 版本是第一个被宣布为"纯净样例"的。

Of course, most CCS examined for the last decade has (eventually) complied with the GPL, perhaps after many iterations of review by the enforcer. However, in the experience of the two primary community-oriented enforcers (Conservancy and the FSF), such CCS results routinely "barely comply with GPL's requirements". To use an academic analogy: while a "C" is certainly a passing grade, any instructor prefers to disseminate to the class an exemplar sample that earned an "A".

当然，过去十年中大多数 CCS 最终都符合了 GPL，可能经过了执行者的多次审核。然而，在面向社区的两个主要执行者（Conservancy 和 FSF）的经验中，这样的 CCS 结果通常只是"勉强符合 GPL 的要求"。用一个学术类比：虽然"C"当然是及格的，但是任何教师都更喜欢向班上展示一个获得"A"的样例。

Fortunately, thanks in large part to the FSF's "Respects Your Freedom" (RYF) certification campaign[^1^](#_bookmark227), a few electronics products on the market meet a higher standard of copyleft compliance. As such, for the first time in the history of copyleft, CCS experts have pristine examples to study and present as exemplars worthy of emulation.

幸运的是，由于大部分得益于 FSF 的"尊重你的自由"(RYF) 认证运动，市场上有几款电子产品符合了更高的版权合规标准。因此，对于版权合规的历史来说，CCS 专家们有了可供研究和展示的纯净样例，值得仿效。

This case study therefore examines the entire life-cycle of a GPL compliance investigation: from product purchase, to source request, to CCS review, and concluding in a final compliance determination. Specifically, this chapter discusses the purchase, CCS provision, and a step-by-step build and installation analysis of a specific, physical, embedded electronics product: [the "TPE-NWIFIROUTER" wireless router by ThinkPenguin.](https://www.thinkpenguin.com/gnu-linux/free-software-wireless-n-broadband-router-gnu-linux-tpe-nwifirouter2)[^2^](#_bookmark228)

因此，这个案例研究考察了 GPL 合规调查的整个生命周期：从购买产品到请求源代码，到 CCS 审查，以及最终的合规性决定。具体而言，本章讨论了购买、CCS 提供以及特定的物理嵌入式电子产品（ThinkPenguin 的"TPE-NWIFIROUTER"无线路由器）[^2^](#_bookmark228)的逐步构建和安装分析。

### 21.1 Consumer Purchase and Unboxing

### 21.1 消费者购买和开箱

The process for copyleft compliance investigation, when properly conducted, determines whether users in- clined to exercise their rights under a copyleft license will be successful in their attempt. Therefore, at every stage, the investigator seeks to take actions that reasonably technically knowledgeable users would during the ordinary course of their acquisition and use of copyleft-covered products. As such, the investigator typ- ically purchases the device on the open market to verify that distribution of the copylefted software therein complies with binary distribution requirements (such as those discussed earlier in [5.2](#gplv2-3-producing-binaries) and [9.9).](#gplv3-6-non-source-and-corresponding-source)

如果正确进行，copyleft 合规调查的过程将确定倾向于行使 copyleft 许可下权利的用户是否能够成功实现他们的尝试。因此，在每个阶段，调查人员都会寻求采取合理的技术知识，通常是在获取和使用 copyleft 覆盖产品的普通过程中普通用户会采取的行动。因此，调查人员通常会在开放市场上购买设备，以验证其中 copylefted 软件的分发是否符合二进制分发要求（例如 5.2 和 9.9 中讨论的那些要求）。

[^21-1^]: [RYF is a campaign by FSF to certify products that truly meet the principles of software freedom.](http://www.fsf.org/resources/hw/endorsement/respects-your-freedom) Products must meet []{#_bookmark228 .anchor}[strict standards for RYF certification,](http://www.fsf.org/resources/hw/endorsement/criteria) and among them is a pristine example of CCS.

[^21-1^]: RYF 是 FSF 的一项运动，旨在认证真正符合软件自由原则的产品。产品必须符合 RYF 认证的严格标准，其中包括 CCS 的一个纯净示例。具体的 RYF 认证标准可以在 http://www.fsf.org/resources/hw/endorsement/criteria 上查看。

[^21-2^]: The FSF of course performed a thorough CCS check as part of its certification process. The analysis discussed herein was independently performed by Software Freedom Conservancy without reviewing the FSF's findings. Thus, this analysis is "true to form", and explains the typical procedures Conservancy uses when investigating a potential GPL violation. In this case, obviously, no violation was uncovered.

[^21-2^]: 自由软件基金会在其认证过程中当然进行了彻底的代码清理检查。本文讨论的分析是由自由软件协会独立进行的，而没有查看自由软件基金会的结果。因此，这个分析是“切合实际的”，并解释了自由软件协会在调查潜在的GPL违规行为时使用的典型程序。在这种情况下，显然没有发现任何违规行为。

Therefore, the investigator first purchased the TPE-NWIFIROUTER through an online order, and when the package arrived, examined the contents of the box. The investigator immediately discovered that ThinkPenguin had taken advice from [15.1.2,](#option-b-the-offer) and exercised [GPLv2 3(a)](#gplv2-3-producing-binaries) and [GPLv3 6,](#gplv3-6-non-source-and-corresponding-source) rather than us- ing the [problematic offer for source provisions.](#option-b-the-offer) This choice not only accelerated the investigation (since there was no CCS offer to "test"), but also simplified the compliance requirements for ThinkPenguin.

因此，调查人员首先通过在线订购购买了TPE-NWIFIROUTER，并在包裹到达后检查了盒子的内容。调查人员立即发现，ThinkPenguin已经遵循了15.1.2节的建议，并执行了GPLv2 3(a)和GPLv3 6节，而不是使用问题来源提供条款。 这种选择不仅加速了调查过程（因为没有CCS来源提供要“测试”），还简化了ThinkPenguin的合规要求。

### 21.2 Root Filesystem and Kernel Compilation

### 21.2 Root文件系统和内核合规

The CD found in the box was labeled "libreCMC v1.2.1 source code", and contained 407 megabytes of data. The investigator copied this ISO to a desktop GNU/Linux system and examined its contents. Upon doing so, the investigator immediately found a file called "README" at the top-level directory:

盒子里发现的CD标签上写着“libreCMC v1.2.1源代码”，里面包含407兆字节的数据。调查员将这个ISO文件复制到一个桌面GNU/Linux系统并检查了它的内容。在这样做的过程中，调查员立即在顶级目录下发现了一个名为“README”的文件。

```bash
$ dd if=/dev/cdrom of=libreCMC_v1.2.1_SRC.iso 
$ mkdir libCMC 
$ sudo mount -o loop ./libreCMC_v1.2.1_SRC.iso libCMC 
mount: block device /path/to/libreCMC_v1.2.1_SRC.iso 
       is write-protected, mounting read-only 
$ ls -1 libCMC 
bin 
librecmc-u-boot.tar.bz2 
librecmc-v1.2.1.tar.bz2 
README 
u-boot_reflash 
$ cat libCMC/README 
...
```

The investigator therefore knew immediately to begin the CCS check should begin with a study of the contents of "README". Indeed, that file contained the appropriate details to start the build:

The investigator therefore knew immediately to begin the CCS check should begin with a study of the contents of "README". Indeed, that file contained the appropriate details to start the build:

>In order to build firmware images for your router, the following needs to be installed:
>
>gcc, binutils, bzip2, flex, python, perl, make, find, grep, diff, unzip, gawk, getopt, libz-dev and libc headers.
>
>Please use "make menuconfig" to configure your appreciated configuration for the toolchain and firmware. Please note that the default configuration is what was used to build the firmware image for your router. It is advised that you use this configuration.
>
>Simply running "make" will build your firmware. The build system will download all sources, build the cross-compile toolchain, the kernel and all chosen applications.
>
>To build your own firmware you need to have access to a GNU/Linux system (case-sensitive filesystem required).

    为了为您的路由器构建固件映像，需要安装以下内容：

    gcc、binutils、bzip2、flex、python、perl、make、find、grep、diff、unzip、gawk、getopt、libz-dev和libc头文件。

    请使用“make menuconfig”配置您欣赏的工具链和固件的配置。请注意，默认配置是用于构建路由器固件映像的配置。建议您使用此配置。

    只需运行“make”即可构建您的固件。构建系统将下载所有源代码，构建交叉编译工具链、内核和所有已选择的应用程序。

    要构建自己的固件，您需要访问一个GNU/Linux系统（需要区分大小写的文件系统）。

In other words, the first "script" that investigator "ran" was the above. This was not a software script, rather the processor for the script was the investigator's own brain - like a script of a play. Less glibly stated: instructions written in English are usually necessary for the build and installation operations that demand actual intelligence. In this case, the investigator ascertained the host system requirements for construction of this embedded firmware.

换句话说，调查员“运行”的第一个“脚本”就是上述内容。这不是软件脚本，而是调查员自己的大脑充当脚本的处理器——就像一部戏剧的剧本。更严谨地说：通常需要使用英语编写的说明来进行构建和安装操作，这些操作需要实际智能。在这种情况下，调查员确定了构建这个嵌入式固件所需的主机系统要求。

GPL does not give specific guidance on the form or location of "scripts used to control compilation and installation of the executable" and/or "Installation Information". Community-oriented GPL enforcers apply a "reasonableness standard" to evaluate such instructions. If an investigator of average skill in embedded firmware construction can surmise the proper procedures to build and install a replacement firmware, the instructions are likely sufficient to meet GPL's requirements. Fortunately, in this case, the instructions are more abundant and give extra detail.

GPL并没有对“用于控制可执行文件编译和安装的脚本”和/或“安装信息”的形式或位置提供具体指导，社区导向的GPL执行者采用“合理性标准”来评估此类说明。如果嵌入式固件构建方面的一般技能的调查员可以推测出正确的构建和安装程序，则说明足以满足GPL的要求。幸运的是，在这种情况下，说明更加详尽，提供了额外的细节。

Nevertheless, these instructions offer more options than the reader typically sees in other CCS candidates. More typically, top-level build instructions name an exact host distribution to use, such as "Debian 7 installed on an amd64 system with the following packages installed". Of course, if the build will fail on any other system, instructions *should* include such details. However, this CCS builds on a wide range of distributions, and thus it was appropriate (and preferred) that the build instructions do not specify a specific distribution. In this specific case, the developers of the libreCMC project (a Free Software project that forms the base system for the TPE-NWIFIROUTER) have clearly made an effort to ensure the CCS builds on a variety of host systems. The investigator was in fact dubious upon seeing these instructions, since finicky embedded build processes usually require a very specific host system. Fortunately, it seems such doubts were generally unfounded (although the investigator did find [a minor annoyance that could be resolved with more detailed](#u-boot-compilation) [instructions).](#u-boot-compilation)

然而，这些说明提供的选项比读者通常在其他CCS候选项中看到的要多。更典型的情况是，顶级构建说明指定要使用的确切主机分发版本，例如“在安装有以下软件包的amd64系统上安装了Debian 7”。当然，如果在任何其他系统上构建失败，说明应该包括这些详细信息。然而，这个CCS可以在各种发行版上构建，因此不指定特定的发行版是合适的（也是首选的）。在这个特定情况下，libreCMC项目的开发人员（一个自由软件项目，形成TPE-NWIFIROUTER的基础系统）已经明确努力确保CCS在各种主机系统上构建。实际上，调查员对这些说明持怀疑态度，因为挑剔的嵌入式构建过程通常需要非常具体的主机系统。幸运的是，似乎这种怀疑通常是没有根据的（尽管调查员确实发现了一些可以通过更详细的说明解决的小问题（参见＃u-boot-compilation））。

Anyway, since these instructions did not specify a specific host system, the investigator simply used his own amd64 Debian GNU/Linux 6 desktop system. Before beginning, the investigator used the following command:

无论如何，由于这些说明没有指定特定的主机系统，调查员只是使用了自己的amd64 Debian GNU / Linux 6桌面系统。在开始之前，调查员使用了以下命令：

```bash
$ dpkg --list | egrep ’ˆiii’ | less

```

>to verify that the required packages listed in the README were installed[^21-3^].
>
>Next, the investigator then extracted the primary source package with the following command:

    为了确认 README 中列出的所需软件包已安装，调查员使用了该命令。[^21-3^]
    接下来，调查员使用以下命令提取主要源代码包：

```bash
$ dpkg --list | egrep ’ˆiii’ | less
```

The investigator did notice an additional source release, entitled "librecmc-u-boot.tar.bz2". The in- vestigator concluded upon simple inspection that the instructions found in "u-boot_reflash" were specific instructions for that part of the CCS. This was a minor annoyance, and ideally the "README" would so-state, but the CCS filesystem layout met the reasonableness standard; the skilled investigator determine the correct course of action with a few moments of study.

The investigator then noted the additional step offered by the "README", which read:

    Please use "make menuconfig" to configure your appreciated configuration for the toolchain and firmware. Please note that the default configuration is what was used to build the firmware image for your router. It is advised that you use this configuration.

This instruction actually exceeds GPL's requirements. Specifically, the instruction guides users in their first step toward exercising the freedom to modify the software. While the GPL does contain requirements that facilitate the freedom to modify (such as ensuring the CCS is in the "preferred form . . . for making modifications to it"), GPL does not require specific instructions explaining how to undertake modifications. This specific instruction therefore exemplifies the exceptional quality of this particular CCS.

调查员注意到还有一个名为“librecmc-u-boot.tar.bz2”的源代码发布包。经过简单的检查，调查员得出结论，"u-boot_reflash" 中的说明是针对 CCS 的那一部分的具体说明。这是一个小小的烦恼，理想情况下，"README" 应该说明清楚，但是 CCS 文件系统布局符合合理性标准；经验丰富的调查员在短短几分钟的学习之后便能确定正确的操作步骤。

However, for purposes of the CCS verification process, typically the investigator avoids any unnecessary changes to the source code during the build process, lest the investigator err and cause the build to fail through his own modification, and thus incorrectly identify the CCS as inadequate. Therefore, the investigator proceeded to simply run:

然而，在CCS验证过程中，为了避免不必要的更改，调查人员通常在构建过程中避免对源代码进行任何更改，以免因其自己的修改而导致构建失败，并因此错误地确定CCS不足。因此，调查人员只是简单地运行了以下命令：

```bash
$ cd libCMC 
$ make
```

and waited approximately 40 minutes for the build to complete[^21-4^]. The investigator kept a [full log of the](https://k.copyleft.org/guide/files/master/enforcement-case-studies_log-output/thinkpenguin_librecmc-complete.log) [build,](https://k.copyleft.org/guide/files/master/enforcement-case-studies_log-output/thinkpenguin_librecmc-complete.log) which is not included herein due its size (approximately 7.2K of text).

调查员运行了上述命令，并等待大约40分钟，直到构建完成[^21-4^]。调查员记录了完整的构建日志，此处不包含日志，由于其大小（约7.2K的文本）。

Upon completion of the "make" process, the investigator immediately found (almost to his surprise) several large firmware files in the "bin/ar71xx" directory. Typically, this step in the CCS verification process is harrowing. In most cases, the "make" step will fail due to a missing package or because toolchain paths are not setup correctly.

当“make”过程完成后，调查员立即在“bin/ar71xx”目录下找到了几个大型固件文件，这几乎让他感到惊讶。在大多数情况下，这个CCS验证过程是困难的。通常，由于缺少软件包或工具链路径设置不正确，"make"步骤会失败。

In light of such experiences, the investigator speculated that ThinkPenguin's engineers did the most important step in self-CCS verification: test one's own instructions on a clean system. Ideally, an employee with similar skills but unfamiliar with the specific product can most easily verify CCS and identify problems before a violation occurs.

考虑到这样的经历，调查员推测ThinkPenguin的工程师们在自我CCS验证中完成了最重要的一步：在一个干净的系统上测试自己的说明。理想情况下，一位具有相似技能但不熟悉特定产品的员工可以最轻松地验证CCS并在违规发生之前识别问题。

However, upon completing the "make", the investigator was unclear which filesystem and kernel images to install on the TPE-NWIFIROUTER hardware. Ideally, the original "README" would indicate which image is appropriate for the included hardware. However, this was ultimately an annoyance rather than a compliance issue. Fortunately, the web UI (see next section) on the TPE-NWIFIROUTER performs firmware image installation. Additionally, the router's version number was specified on the bottom of the device, which indicated which of the differently-versioned images we should install. The investigator would prefer instruc- tions such as those found at [http://librecmc.org/librecmc/wiki?name=Tp+MR3020](http://librecmc.org/librecmc/wiki?name=Tp%2BMR3020)instructions similar to these in the README itself; however, application of the reasonableness standard here again indicates compliance, since a knowledgeable user can easily determine the proper course of action.

然而，在完成“make”后，调查员不清楚哪个文件系统和内核镜像适合TPE-NWIFIROUTER硬件。理想情况下，原始的“README”应该指出适用于所包含硬件的映像。然而，这最终只是一个烦恼而不是合规问题。幸运的是，TPE-NWIFIROUTER上的Web UI（见下一节）执行固件映像安装。此外，路由器的版本号被指定在设备底部，表明我们应该安装哪个不同版本的映像。调查员希望在README中找到类似于http://librecmc.org/librecmc/wiki?name=Tp+MR3020这样的说明，但是这里再次适用合理性标准表明符合合规要求，因为有知识的用户可以轻松确定正确的操作。

### 21.3 U-Boot Compilation

### 21.3 U-Boot编译

The investigator then turned his attention to the file, "u-boot_reflash". These instructions explained how to build and install the bootloader for the device.

然后，调查人员将注意力转向了文件“u-boot_reflash”。这些说明解释了如何构建和安装设备的引导加载程序。

The investigator followed the instructions for compiling U-Boot, and found them quite straight-forward. The investigator discovered two minor annoyances, however, while building U-Boot:

调查人员按照编译U-Boot的说明进行操作，发现它们非常简单。然而，在构建U-Boot时，调查人员发现了两个小问题：

- The variable \$U-BOOT_SRC was used as a placeholder for the name of the extracted source directory. This was easy to surmise and was not a compliance issue (per the reasonableness standard), but explicitly stating that fact at the top of the instructions would be helpful.

- Toolchain binaries were included and used by default by the build process. These binaries were not the appropriate ones for the investigator's host system, and the build failed with the following error:

- 变量$U-BOOT_SRC被用作提取的源目录名称的占位符。这很容易推断出来，并且不是一个合规问题（按照合理性标准），但在说明书的顶部明确说明这一点会更有帮助。

- 编译过程中默认使用了包含的工具链二进制文件。这些二进制文件不适用于调查人员的主机系统，并且编译失败，出现以下错误：

```bash
mips-librecmc-linux-uclibc-gcc.bin: /lib/libc.so.6: 
   version ‘GLIBC‘_2.14’ not found 
   (required by mips-librecmc-linux-uclibc-gcc.bin)
```

>(The [complete log output from the failure](https://k.copyleft.org/guide/files/master/enforcement-case-studies_log-output/thinkpenguin_u-boot-build_fail.log) is too lengthy to include herein.) 
>This issue is an annoyance, not a compliance problem. It was clear from context that these binaries were simply for a different host architecture, and the investigator simply removed "toolchain/bin" and created a symlink to utilize the toolchain already built earlier (during the compilation discussed in *§* [21.2):](#_bookmark231)

    完整的故障日志输出太长，无法在此包含。此问题只是一个烦恼，而不是合规问题。从上下文中可以清楚地看出，这些二进制文件只是针对不同的主机架构，调查人员只需删除 "toolchain/bin" 并创建符号链接以利用之前已构建的工具链（在第21.2节中讨论的编译期间）。

```bash
$ ln -s \ 
  ../../staging_dir/toolchain-mips_34kc_gcc-4.6-linaro_uClibc-0.9.33.2/bin \ 
  toolchain/bin
```

>After this change, the U-Boot build completed successfully.
    
    经过这个更改，U-Boot 构建成功了。

The [full log of the build](https://k.copyleft.org/guide/files/master/enforcement-case-studies_log-output/thinkpenguin_u-boot-finish_build.log) is not included herein due its size (approximately 3.8K of text). After that, the investigator found a new U-Boot image in the "bin" directory.

由于体积太大（约3.8K文字），此构建的完整日志未在此处包含。之后，调查人员在 "bin" 目录中找到了一个新的 U-Boot 映像。

### 21.4 Root Filesystem and Kernel Installation

### 21.4 根文件系统和内核安装

The investigator next tested installation of the firmware. In particular, the investigator connected the TPE- NWIFIROUTER to a local network, and visited <http://192.168.10.1/>, logged in, and chose the option sequence: "System Backup / Flash Firmware".

接下来，调查人员测试了固件的安装。特别地，调查人员将 TPE-NWIFIROUTER 连接到本地网络，并访问 http://192.168.10.1/，登录并选择选项序列："System Backup / Flash Firmware"。

From there, the investigator chose the "Flash new firmware image" section and selected the "librecmc- ar71xx-generic-tl-wr841n-v8-squashfs-sysupgrade.bin" image from the "bin/ar71xx" directory. The investi- gator chose the "v8" image upon verifying the physical router read "v8.2" on its bottom. The investigator chose the "sysupgrade" version of the image because this was clearly a system upgrade (as a firmware already came preinstalled on the TPE-NWIFIROUTER).

从那里，调查人员选择了 "Flash new firmware image" 部分，并从 "bin/ar71xx" 目录中选择了 "librecmc-ar71xx-generic-tl-wr841n-v8-squashfs-sysupgrade.bin" 映像。在验证物理路由器底部显示 "v8.2" 后，调查人员选择了 "v8" 映像。调查人员选择了 "sysupgrade" 映像版本，因为这显然是系统升级（因为 TPE-NWIFIROUTER 上已经预装了固件）。

Upon clicking "Flash image. . . ", the web interface prompted the investigator to confirm the MD5 hash of the image to flash. The investigator did so, and then clicked "Proceed" to flash the image. The process took about one minute, at which point the web page refreshed to the login screen. Upon logging in, the investigator was able to confirm in the "Kernel Log" section of the web interface that the newly built copy of Linux had indeed been installed.

单击 "Flash image. . . " 后，Web 接口提示调查人员确认要刷写的映像的 MD5 哈希值。调查人员确认后，点击 "Proceed" 来刷写映像。该过程大约需要一分钟，此时网页会刷新到登录界面。登录后，调查人员能够在 Web 接口的 "Kernel Log" 部分确认新构建的 Linux 副本确实已安装。

The investigator confirmed that a new version of "busybox" had also been installed by using SSH to connect to the router and ran the command "busybox", which showed the newly-compiled version (via its date of compilation).

通过使用 SSH 连接到路由器并运行 "busybox" 命令，调查人员确认已安装了新版本的 "busybox"。该命令显示了新编译版本（通过其编译日期）。

### 21.5 U-Boot Installation

The U-Boot installation process is substantially more complicated than the firmware update. The investigator purchased the optional serial cable along with the TPE-NWIFIROUTER, in order to complete the U-Boot installation per the instructions in "u-boot_reflash" in its section "Installing u-boot to your router", which reads:

    1. Install and configure any TFTP server on your PC (tftp-hpa). Set a fixed IP address on your PC . . . and connect it to the router, using RJ45 network cable . . .
    2. Connect USB to UART adapter to the router and start any application to communicate with it, like PuTTY. . . .
    3. Power on the router, wait for a line like one of the following and interrupt the process of loading a kernel:

    Autobooting in 1 seconds

    (for most TP-Link routers, you should enter tpl at this point) Hit ESC key to stop autoboot: 1 (for 8devices Carambola 2, use ESC key) Hit any key to stop autoboot: 1 (for D-Link DIR-505, use any key)

    4. Set ipaddr and serverip environment variables:

```bash
        hornet> setenv ipaddr 192.168.1.1 
        hornet> setenv serverip 192.168.1.2
```

    在您的PC上安装和配置任何TFTP服务器（tftp-hpa）。在您的PC上设置一个固定的IP地址，并使用RJ45网络电缆将其连接到路由器上。
    将USB转UART适配器连接到路由器上，并启动任何通信应用程序，例如PuTTY。
    打开路由器电源，等待类似以下内容的提示，并中断加载内核的过程：
    Autobooting in 1 seconds

    （对于大多数TP-Link路由器，此时您应该输入tpl）按ESC键停止自动引导：1（对于8devices Carambola 2，请使用ESC键）按任意键停止自动引导：1（对于D-Link DIR-505，请使用任意键）

    设置ipaddr和serverip环境变量：

The investigator used the purchased serial cable, which was a USB serial adapter with a male USB type A connector to 4 female jumper wires. The female jumper wires were red, black, white, and green.

调查员使用了购买的串行电缆，这是一个USB串行适配器，带有一个雄性USB Type A连接器和4个母式跳线。这些母式跳线的颜色分别为红色、黑色、白色和绿色。

The instructions here were slightly incomplete, since they did not specify how to connect the wires to the router. However, the investigator found general information available online at [http://wiki.openwrt.org/](http://wiki.openwrt.org/toh/tp-link/tl-wr841nd#serial.console) [toh/tp-link/tl-wr841nd#serial.console](http://wiki.openwrt.org/toh/tp-link/tl-wr841nd#serial.console) which described the proper procedure. While the "power" and "ground" cables were obvious, some trial and error was necessary to find the RX and TX cables, but this was easily determined since miswiring TX and RX yields no I/O and proper wiring yields the output as expected. Using the pin gender changer included with the adapter, the investigator was able to stably wire the pins for use once the proper RX and TX connections were determined.

这里的说明略微不完整，因为它们没有说明如何将电缆连接到路由器。然而，调查员在http://wiki.openwrt.org/toh/tp-link/tl-wr841nd#serial.console上找到了通用的在线信息，描述了正确的过程。虽然“电源”和“地”电缆很明显，但需要一些尝试才能找到RX和TX电缆，但这很容易确定，因为错连接TX和RX不会产生I/O，正确连接会产生预期的输出。使用适配器附带的针脚转换器，一旦确定了正确的RX和TX连接，调查员就能够稳定地连接针脚以供使用。

The investigator then used the recommended 115200 8N1 for serial console settings, leaving all flow control off, and tested both with the minicom and screen commands. The investigator found that if all 4 wires were connected on the USB serial adapter that the router would start without additional power and the console would receive the startup messages. The investigator could replicate the same behavior by omitting the power cable from the USB serial adapter (red wire) and connecting the main power adapter to the router instead.

然后，调查员使用推荐的115200 8N1串行控制台设置，关闭所有流控制，并使用minicom和screen命令进行测试。调查员发现，如果将USB串行适配器上的所有4根电线连接起来，路由器就会开始启动，而控制台会收到启动消息。调查员可以通过省略USB串行适配器上的电源电缆(红线)并将主电源适配器连接到路由器上来复制相同的行为。

At this point, the on-screen messages as described in the installation instructions appeared, but the investigator found that no key events sent via the serial port appeared to reach the U-Boot console. In other words, while the investigator saw both U-Boot and kernel boot messages in the serial console, the investigator was unable to interrupt the boot process as instructed by "u-boot_reflash". Hitting a key simply did *not* interrupt the boot process and yield the hornet\> prompt.

此时，安装说明中描述的屏幕上的消息出现了，但是调查员发现，通过串口发送的任何按键事件似乎都无法到达U-Boot控制台。换句话说，尽管调查员在串行控制台中看到了U-Boot和内核引导消息，但是调查员无法按照“u-boot_reflash”的指示打断引导过程。按键根本没有打断引导过程并显示 **hornet>** 提示符。

After additional trial and error over a period of hours, the investigator had finally to consider this question for the first time during the process: "Has ThinkPenguin violated the GPL?" More specifically, the immediate question was: "Given this failure, has the distributor met [the requirements for 'scripts used to](#complete-corresponding-source-ccs) [control installation of the executable' (GPLv2)](#complete-corresponding-source-ccs) and [necessary 'Installation Information' (GPLv3)?"](#installation-information)

经过数小时的额外试验和错误，调查人员最终在过程中第一次考虑了这个问题：“ThinkPenguin是否违反了GPL？”更具体地说，立即的问题是：“鉴于这个失败，发行者是否符合了“用于控制可执行文件安装的脚本”（GPLv2）和“必要的安装信息”（GPLv3）的要求？”

The appropriate answer to the question (at this specific stage) is "possibly, but more information is needed". Embedded installation and configuration is a tricky and complex technical process. While the GPL requires documentation and clear instructions for this process, the investigator did not immediately blame the distributor for what may be an honest, correctable mistake, or an issue legitimately explained by feasible alternative theories.

在这个特定阶段，这个问题的适当答案是“可能，但需要更多信息”。嵌入式安装和配置是一个棘手和复杂的技术过程。虽然GPL要求对此过程进行文档记录和清晰的说明，但调查人员并没有立即指责分发者，因为这可能是一个诚实的、可以纠正的错误，或者是一个可以通过可行的替代理论合理解释的问题。

In this case, upon remembering the issues of wiring, the investigator wonder if perhaps the power pin was accidentally connected for a moment to the RX pin while live. Such action could easily fry the RX pin, and yield the observed behavior. Since the investigator could not rule out the possibility of accidental connection of power to the RX pin mentioned, the investigator had to assume the instructions would work properly if he had not made that error.

在这种情况下，调查人员在想起接线问题后，想知道是否有可能在通电时将电源引脚误连接到了RX引脚。这样的行为可能会轻易地烧掉RX引脚，导致观察到的行为。由于调查人员不能排除提到的意外将电源连接到RX引脚的可能性，因此调查人员不得不假设如果他没有犯下这个错误，指令将正常工作。

That conclusion, while correct, also left the investigator with only two option to complete the final verification of the CCS:

这个结论虽然正确，但也让调查人员只剩下两个选项来完成CCS的最终验证：

- Purchase a new router and cable anew, and reattempt the installation process while taking extra care not to miswire any cables.

- Seek assistance from the libreCMC community to find an alternative method of installation.

- 购买新的路由器和电缆，重新尝试安装过程，并特别注意不要误接任何电缆。

- 寻求libreCMC社区的帮助，找到一种替代的安装方法。

The investigator chose the latter and then contacted a libreCMC developer familiar with the product. That developer, who agreed the the RX pin was likely ruined, described an alternative method for console access using the netcat. The libreCMC developer described the process as follows:

调查人员选择了后者，然后联系了一个熟悉该产品的libreCMC开发者。这位开发者同意RX引脚很可能被毁坏，并描述了一种使用netcat进行控制台访问的替代方法。该libreCMC开发者描述了如下过程：

- Change the IP address of the router to 192.168.1.1.

- Change the IP address of a desktop GNU/Linux system to 192.168.1.2.

- Power on the router while holding the reset button for 7 seconds.

- Use the netcat command (as below) on the desktop, and press enter to receive U-Boot's prompt:

    - 将路由器的IP地址更改为192.168.1.1。

    - 将桌面GNU/Linux系统的IP地址更改为192.168.1.2。

    - 按住重置按钮7秒钟，开启路由器。

    - 在桌面上使用netcat命令（如下），并按Enter键接收U-Boot的提示：

```bash
$ nc -u -p 6666 192.168.1.1 6666 
uboot>
```

Upon following this procedure, the investigator was able to confirm the (original) shipped version of U-Boot was still installed:

按照这个步骤，调查员确认了原始发货版本的 U-Boot 仍然安装在系统中：

```bash
$ nc -u -p 6666 192.168.1.1 6666 
uboot> version 
U-Boot 1.1.4 (Jul 28 2014)
```

Thereafter, the investigator followed the instructions from "u-boot_reflash". Specifically, the investigator configured a TFTP server and placed the newly built firmware into /srv/tftp. The investigator also followed the remaining instructions in "u-boot_reflash", but used the netcat console rather than the serial console, and used U-Boot's reset command to reboot the router.

此后，调查员按照“u-boot_reflash”中的说明进行操作。具体来说，调查员配置了一个 TFTP 服务器，并将新构建的固件放置在 /srv/tftp 中。调查员还按照“u-boot_reflash”中的其余说明进行操作，但是使用了 netcat 控制台而不是串行控制台，并使用了 U-Boot 的重置命令来重新启动路由器。

Upon reboot, the serial console (still connect with working output) showed the message U-Boot 1.1.4 (Oct 17 2014), and thus confirmed a successful reflash of the U-Boot image built by the investigator.

重新启动后，串行控制台（仍然连接并输出正常）显示了消息“U-Boot 1.1.4（2014 年 10 月 17 日）”，从而确认了调查员构建的 U-Boot 映像的成功重新烧写。

### 21.6 Firmware Comparison

### 21.6 固件比较

Next, to ensure the CCS did indeed correspond to the firmware original installed on the TPE-NWIFIROUTER, the investigator compared the built firmware image with the filesystem originally found on the device itself. The comparison steps were as follows:

接下来，为确保 CCS 确实与安装在 TPE-NWIFIROUTER 上的原始固件相对应，调查员将构建的固件映像与设备本身上原始的文件系统进行比较。比较步骤如下：

1. Extract the filesystem from the image we built by running > [find-firmware.pl](https://k.copyleft.org/gpl-compliance-scripts/files/master/find-firmware.pl) on "bin/ar71xx/librecmc- ar71xx-generic-tl-wr841n-v8-squashfs-factory.bin" and then running [bat-extratools'](http://www.binaryanalysis.org/en/content/show/download) "squashfs4.2/squashfs- tools/bat-unsquashfs42" on the resulting morx0.squash, using the filesystem in the new squashfs-root directory for comparison.

2. Login to the router's web interface (at <http://192.168.10.1/>) from  a computer connected to the router.

3. Set a password using the provided link at the top (since the router's UI warns that no password is set and asks the user to change it).

4. Logged into the router via SSH, using the root user with the aforementioned password.

5. Compared representative directory listings and binaries to ensure the set of included files (on the router) is similar to those found in the firmware image that the investigator created (whose contents are now in the local squashfs-root directory). In particular, the investigator did the following comparisons:

1. 运行 > find-firmware.pl 命令从 "bin/ar71xx/librecmc- ar71xx-generic-tl-wr841n-v8-squashfs-factory.bin" 中提取我们构建的文件系统，然后使用 bat-extratools' 中的 "squashfs4.2/squashfs- tools/bat-unsquashfs42" 命令解压 morx0.squash，将结果中的文件系统保存到新的 squashfs-root 目录中，用于比较。

2. 使用连接到路由器的计算机从路由器的 Web 界面（位于 http://192.168.10.1/）登录。

3. 使用顶部提供的链接设置密码（因为路由器的用户界面会警告用户未设置密码并要求用户更改密码）。

4. 使用具有上述密码的 root 用户通过 SSH 登录到路由器。

5. 比较代表性的目录列表和二进制文件，以确保在路由器上包含的文件集与调查员创建的固件映像中找到的文件集（其内容现在保存在本地的 squashfs-root 目录中）相似。特别是，调查员进行了以下比较：

    a.  Listed the /bin folder ("ls -l /bin") and confirm the list of files is the same and that the file sizes are similar.

    b.  Checked the "strings" output of "/bin/busybox" to confirm it is similar in both places (similar number of lines and content of lines). (One cannot directly compare the binaries because the slight compilation variations will cause some bits to be different.)

    c.  Repeated the above two steps for "/lib/modules", "/usr/bin", and other directories with a signif- icant number of binaries.

    d.  Checked that the kernel was sufficiently similar. The investigator compared the "dmesg" output both before and after flashing the new firmware. As the investigator expected, the kernel version string was similar, but had a different build date and user@host indicator. (The kernel binary itself is not easily accessible from an SSH login, but was retrievable using the U-Boot console (the start address of the kernel in flash appears to be 0x9F020000, based on the boot messages seen in the serial console).

    a. 列出 /bin 文件夹（"ls -l /bin"）并确认文件列表相同，文件大小相似。

    b. 检查 "/bin/busybox" 的 "strings" 输出，以确认两个位置的输出相似（行数和内容）。 （不能直接比较二进制文件，因为轻微的编译差异会导致某些位不同。）

    c. 对 "/lib/modules"、"/usr/bin" 和其他具有大量二进制文件的目录重复上述两个步骤。

    d. 检查内核是否足够相似。调查员比较了刷写新固件前后的 "dmesg" 输出。如调查员所预期的，内核版本字符串相似，但具有不同的构建日期和 user@host 指示器。 （内核二进制文件本身无法从 SSH 登录轻松访问，但可以使用 U-Boot 控制台检索（基于在串行控制台中看到的启动消息，内核在闪存中的起始地址似乎是0x9F020000）。）

### 21.7 Minor Annoyances

### 21.7 小问题

As discussed in detail above, there were a few minor annoyances, none of which were GPL violations. Rather, the annoyances briefly impeded the build and installation. However, the investigator, as a reasonably skilled build engineer for embedded devices, was able to complete the process with the instructions provided.

正如上面详细讨论的那样，存在一些小问题，但没有违反 GPL 许可证。这些问题稍微阻碍了构建和安装过程。但是，作为一个技能较强的嵌入式设备构建工程师，调查员能够按照提供的说明完成整个过程。

To summarize, no GPL compliance issues were found, and the CCS release was one of the best ever reviewed by any investigator at any community-oriented enforcement organization. However, the following annoyances were discovered:

总结一下，没有发现任何 GPL 合规性问题，而且 ThinkPenguin 发布的 CCS 版本是任何一个社区导向执法组织评审过的最好的版本之一。但是，还发现了以下问题：

- Failure to explain how to extract the source tarball and then where to run the "make" command.

Failure to explain how to install the kernel and root filesystem on the device; the user must assume the web UI must be used.

Including pre-built toolchain binaries that don't work on all systems, and failure to copy and/or symlink built toolchain binaries in the right location.

- Failure to include information in the U-Boot installation instructions for wiring the serial cable.

- Ideally, the U-Boot installation instructions would also include the netcat method of installation. Finally, the instructions should note that the new U-Boot firmware should be placed into /srv/tftp when using TFTP on most GNU/Linux desktops.

- 没有说明如何提取源码 tarball，以及在哪里运行“make”命令。

- 没有说明如何在设备上安装内核和根文件系统；用户必须假设必须使用 Web UI 进行操作。

- 包括不适用于所有系统的预编译工具链二进制文件，并且没有在正确的位置复制和/或创建工具链二进制文件的符号链接。

- 在 U-Boot 安装说明中没有包括有关连接串行电缆的信息。

- 理想情况下，U-Boot 安装说明还应包括 netcat 安装方法。最后，说明应指出，在大多数 GNU/Linux 桌面系统上使用 TFTP 时，新的 U-Boot 固件应放置在 /srv/tftp 中。

Thus, no CCS is absolutely perfect, but GPL violation investigators always give the distributors the benefit of any doubts and seek to work with the vendors and improve their CCS for the betterment of their users, customers, and the entire software freedom community.

因此，没有绝对完美的 CCS，但是 GPL 违规调查员始终会给予发行商任何怀疑的权利，并寻求与供应商合作，改进他们的 CCS，以造福他们的用户、客户和整个软件自由社区。

### 21.8 Lessons Learned

### 21.8 总结与教训

Companies that seek to redistribute copylefted software can benefit greatly from ThinkPenguin's example. Here are just a few of the many lessons that can be learned here:

试图重新分发共享软件的公司可以从 ThinkPenguin 的例子中受益。这里只是可以学到的许多教训中的几个：

1. Even though copyleft licenses have them, [**avoid the  offer-for-source provisions**](#consumer-purchase-and-unboxing). Not only does including the CCS alongside binary distribution make violation investigation and compliance confir- mation substantially easier, but also (and more importantly) doing so [completes the distributor's CCS](#option-b-the-offer) [compliance obligations at the time of distribution](#option-b-the-offer) (provided, of course, that the distributor is otherwise in compliance with the relevant copyleft license).

2. **Include top-level build instructions in a natural language (such  as English) in a [clear and](#_bookmark230) [conspicuous place.](#_bookmark230)** Copyleft licenses require that someone reasonably skilled in the art can reproduce the build and installation. Typically, instructions written in English are necessary, and often easier than writing programmed scripts. The "script" included can certainly be more like the script of a play and less like a Bash script.
3. **Write build/install instructions to the appropriate level of  specificity**. The upstream engi- neers in this case study [clearly did additional work to ensure functionality on a wide variety of host](#_bookmark230) [build systems;](#_bookmark230) this is quite rare. When in doubt, include the maximum level of detail build engi- neers can provide with the CCS instructions, but also double-check to investigate if a more generalized solution (such as other host systems) work just as well for the build.

4. **Seek to adhere to the spirit of copyleft, not just the letter of  the license**. Encouragement of users to improve and make their devices better is one of ThinkPenguin's commercial differentiators. Copyleft advocates that other companies have undervalued the large and lucrative market of users who seek hackable devices. By going beyond the mere minimal requirements of GPL, companies can immediately reap the benefits in that target market.

5. Community-oriented enforcement organizations do not play  "gotcha"[^21-5^] with distributors regarding GPL violations. The goal in the GPL enforcement process is to achieve compliance and correct mistakes and annoyances. Such organizations therefore take an "innocent until proven guilty assume guilty due to honest error rather than malicious action " approach. The goal is compliance (in direct contrast with the [discussion in *§* 12.2 about the proprietary relicensing](#business-models) business model).

1. 即使共享许可证包括它们，尽量避免提供源代码条款。将 CCS 与二进制分发一起包含不仅使违规调查和合规确认变得更加容易，而且（更重要的是）在分发时**（前提是分发商符合相关共享许可证）完成了分发商的 CCS 合规义务**。

2. **在明显的位置用自然语言（如英语）包含顶层构建说明。**共享许可证要求合理熟练的人可以重现构建和安装过程。通常需要使用英语编写的说明，并且往往比编写脚本更容易。包含的“脚本”当然可以更像戏剧脚本，而不是 Bash 脚本。

3. 编写适当级别的构建/安装说明。在这个案例研究中，上游工程师们显然做了额外的工作，以确保在各种主机构建系统上的功能正常，这是非常罕见的。当存在疑虑时，将构建工程师可以提供的最详细的构建说明包括进 CCS 指令中，但同时要仔细检查是否有更普适的解决方案（如其他主机系统）同样适用于构建。

4. 力求遵守 Copyleft 精神，而非仅遵守许可证条款。鼓励用户改进和使其设备更好是 ThinkPenguin 的商业差异化之一。Copyleft 倡导其他公司低估了寻求可黑客化设备的大型和有利可图的用户市场。通过超越 GPL 的最低要求，公司可以立即在这个目标市场中获得好处。

5. 面向社区的执法组织在 GPL 违规问题上不与分销商玩“抓到你了”[^21-5^]的游戏。在 GPL 执法过程中，目标是实现合规并纠正错误和恼人之处。因此，这样的组织采取“假定无罪，由于诚实的错误而不是恶意行为而被认定有罪”的方法。目标是遵守（与商业模型章节中关于专有再许可的讨论形成鲜明对比）。

[^21-1^]: RYF is a campaign by FSF to certify products that truly meet the principles of software freedom. Products must meet strict standards for RYF certification, and among them is a pristine example of CCS.

[^21-2^]: The FSF of course performed a thorough CCS check as part of its certification process. The analysis discussed herein was independently performed by Software Freedom Conservancy without reviewing the FSF’s findings. Thus, this analysis is “true to form”, and explains the typical procedures Conservancy uses when investigating a potential GPL violation. In this case, obviously, no violation was uncovered.

[^21-3^]: The “dpkg” command is a Debian-specific way of finding installed packages.

[^21-4^]: Build times will likely vary widely on various host systems.

[^21-5^]: For lack of a better phrase.

[^21-1^]: RYF 是 FSF 的一个活动，旨在认证真正符合软件自由原则的产品。产品必须符合 RYF 认证的严格标准，其中包括纯粹的 CCS 的典范示例。

[^21-2^]: 在认证过程中，FSF 当然会进行彻底的 CCS 检查。本文讨论的分析是由软件自由保护协会独立进行的，未经过查看 FSF 的发现。因此，这个分析是“真实的”，并解释了 Conservancy 调查潜在的 GPL 违规时使用的典型程序。在这种情况下，显然没有发现任何违规行为。

[^21-3^]: “dpkg” 命令是 Debian 特有的一种查找已安装软件包的方式。

[^21-4^]: 在不同的主机系统上，构建时间可能会有很大的差异。

[^21-5^]: 没有更好的说法。


## CHAPTER 22 BORTEZ: MODIFIED GCC SDK

## 第22章 Bortez:修改版的GCC SDK

In our first case study, we will consider Bortez, a company that produces software and hardware toolkits to assist OEM vendors, makers of consumer electronic devices.

在第一个案例研究中，我们把目光投到Bortez，这是一家生产软件和硬件工具包用来服务于OEM供应商和消费电子设备制造商的公司。

### 22.1 Facts

### 22.1 事情经过

One of Bortez's key products is a Software Development Kit ("SDK") designed to assist developers building software for a specific class of consumer electronics devices.

Bortez的主打产品是一款软件开发工具包(“SDK”)，用途是帮助开发人员为特定类型的消费电子设备进行软件架构。

FSF received a report that the SDK may be based on the GNU Compiler Collection (which is an FSF- copyrighted collection of tools for software development in C, C++ and other popular languages). FSF investigated the claim, but was unable to confirm the violation. The violation reporter was unresponsive to follow-up requests for more information.

FSF收到的一份举报，称SDK似乎是基于GNU编译器套件（GNU Compiler Collection，这是FSF拥有版权的C、C++和其他流行语言软件开发工具箱）。FSF就这个反映进行了调查，但无法证实这一违规行为。举报人没有对后续提供更多信息的请求做出回应。

Since FSF was unable to confirm the violation, we did not pursue it any further. Bogus reports do happen, and we do not want to burden companies with specious GPL violation complaints. FSF shelved the matter until more evidence was discovered.

由于FSF无法证实这一违规行为，我们没有做进一步追究。鉴于可能存在不实举报，我们不愿让公司背负莫须有的GPL违规投诉。FSF将此事搁置，直到发现更多证据。

FSF was later able to confirm the violation when two additional reports surfaced from other violation reporters, both of whom had used the SDK professionally and noticed clear similarities to FSF's GNU GCC. FSF's Compliance Engineer asked the reporters to run standard tests to confirm the violation, and it was confirmed that Bortez's SDK was indeed a modified version of GCC. Bortez had ported to Windows and added a number of features, including support for a specific consumer device chipset and additional features to aid in the linking process ("LP") for those specific devices. FSF explained the rights that the GPL afforded these customers and pointed out, for example, that Bortez only needed to provide source to those in possession of the binaries, and that the users may need to request that source (if 3(b) was exercised). The violators confirmed that such requests were not answered.

一段时间以后，当来自其他举报人的另外两份报告浮出水面时，FSF终于对这一违规行为予以确认。这两人都曾专业地使用过SDK，并注意到与FSF的GNU GCC有明显的相似之处。FSF的合规工程师要求报告人通过运行标准测试来确认违规，并证实Bortez的SDK确实是GCC的修改版本。Bortez已经将其移植到Windows，并添加了许多功能，包括对特定消费设备芯片组的支持，并在这些设备的连接过程(“LP”)中提供一些额外支持功能。FSF对GPL赋予客户的权利做出说明，例如，Bortez只可以向那些拥有二进制文件的人提供源代码，并且用户只能对该源代码提出请求(在遵循3(b)的情况下)。违规者证实，这些请求没有得到回应。

FSF brought the matter to the attention of Bortez, who immediately escalated the matter to their attorneys. After a long negotiation, Bortez acknowledged that their SDK was indeed a modified version of GCC. Bortez released most of the source, but some disagreement occurred over whether LP was also derivative of GCC. After repeated FSF inquiries, Bortez reaudited the source to discover that FSF's analysis was correct. Bortez determined that LP included a number of source files copied from the GCC code-base. Once the full software release was made available, FSF asked the violation reporters if it addressed the problem. Reports came back that the source did not properly build. FSF asked Bortez to provide better build instructions with the software, and such build instructions were incorporated into the next software release.

FSF向Bortez发出警告函，后者立即将此事通知他们的律师。经过长时间的谈判，Bortez承认他们的SDK确实是GCC的修改版本。Bortez公布了大部分来源，但在LP是否也属于GCC的衍生产品的问题上出现了一些分歧。经过FSF的反复质询，Bortez重新对出处进行溯源，发现FSF的分析是正确的。Bortez确定LP包含了许多从GCC代码库复制的源文件。当完整版软件发行后，FSF询问举报人该问题是否得到解决。回信说，该来源并没有被正确构建。FSF要求Bortez为软件做出更适当的构建说明，并将其合并到下一个软件版本中。

At FSF's request as well, Bortez informed customers who had previously purchased the product that the source was now available by announcing the availability on its Web site and via a customer newsletter.

在FSF的要求下，Bortez通过其网站以及客户通讯录发布消息，通知以前购买过该产品的客户，已经可以正常使用该来源。

Bortez did have some concerns regarding patents. They wished to include a statement with the software release that made sure they were not granting any patent permission other than what was absolutely required by the GPL. They understood that their patent assertions could not trump any rights granted by the GPL. The following language was negotiated into the release:

Bortez对专利问题有一些顾虑。他们希望在软件发行时包含一份声明，以确保他们没有授予除GPL基础条款以外的任何专利许可。他们清楚，自己的专利主张无法凌驾于GPL授予的权利之上。以下内容是通过谈判达成的结果：

Subject to the qualifications stated below, Bortez, on behalf of itself and its Subsidiaries, agrees not to assert the Claims against you for your making, use, offer for sale, sale, or importation of the Bortez's GNU Utilities or derivative works of the Bortez's GNU Utilities ("Derivatives"), but only to the extent that any such Derivatives are licensed by you under the terms of the GNU General Public License. The Claims are the claims of patents that Bortez or its Subsidiaries have standing to enforce that are directly infringed by the making, use, or sale of an Bortez Distributed GNU Utilities in the form it was distributed by Bortez and that do not include any limitation that reads on hardware; the Claims do not include any additional patent claims held by Bortez that cover any modifications of, derivative works based on or combinations with the Bortez's GNU Utilities, even if such a claim is disclosed in the same patent as a Claim. Subsidiaries are entities that are wholly owned by Bortez.

根据下述的条款，Bortez代表自身及其子公司，同意不对他人制作、使用、出售、销售或进口Bortez GNU工具组或Bortez GNU工具组的派生产品(“衍生品”)的行为主张权利，但仅限于在GNU通用公共许可证的条款许可下的任何此类衍生品。这是Bortez及其子公司有权强制执行的专利声明，一旦出现利用Bortez发行的版本制作、使用或销售Bortez分布式GNU实用程序的行为则属于直接侵权，并且不包括任何对硬件的限制；权利要求不包括由Bortez持有的那部分额外的专利要求，这涵盖了任何基于Bortez GNU工具组的修改、衍生或组合产品，即使此类权利要求已经在相关专利中予以披露。所谓子公司，是指Bortez全资控股的实体。

This statement does not negate, limit or restrict any rights you already have under the GNU General Public License version 2.

本声明并不否认、限制或禁止您在GNU通用公共许可证第2版框架下已经拥有的任何权利。

This quelled Bortez's concerns about other patent licensing they sought to do outside of the GPL'd software, and satisfied FSF's concerns that Bortez give proper permissions to exercise teachings of patents that were exercised in their GPL'd software release.

至此Bortez免除了在GPL版软件之外出现其他专利许可的担忧。为了让FSF放心，Bortez还给予了适当的许可，以行使在GPL版软件中行使的教学的权利。

Finally, a GPL Compliance Officer inside Bortez was appointed to take responsibility for all matters of GPL compliance inside the company. Bortez is responsible for informing FSF if the position is given to someone else inside the company, and making sure that FSF has direct contact with Bortez's Compliance Officer.

最后，Bortez任命了一名GPL合规官，负责公司内所有GPL合规事宜。如果该职位出现人员调整，Bortez负责通知FSF，并确保FSF与Bortez的合规官保持直接对话。

### 22.2 Lessons

### 22.2 经验教训

This case introduces a number of concepts regarding GPL enforcement.

本案例涉及了一些关于GPL实施的概念。

1. **Enforcement should not begin until the evidence is confirmed.** Most companies that distribute GPL'd software do so in compliance, and at times, violation reports are mistaken. Even with extensive efforts in GPL education, many users do not fully understand their rights and the obligations that companies have. By working through the investigation with reporters, the violation can be properly confirmed, and **the user of the software can be educated about what to expect with GPL'd software**. When users and customers of GPL'd products know their rights, what to expect, and how to properly exercise their rights (particularly under 3(b)), it reduces the chances for user frustration and inappropriate community outcry about an alleged GPL violation.

1. **除非证据确凿，否则不应执行。** 大多数GPL软件的发行公司都是遵守规定的，违规举报有时是错误的。即使在GPL宣贯方面做了大量的努力，许多用户也不完全理解他们企业的权利和义务。通过与报告人一起联合调查，可以正确地确认违规行为，并且**可以引导用户如何使用GPL软件**。当GPL产品的用户和客户知道他们的权利、期望，并了解如何正确行使他们的权利（尤其是在3(b)框架下）时，这可以减少用户的不满和社区中抗议违反GPL侵权的机会。

2. **GPL compliance requires friendly negotiation and cooperation.** Often, attorneys and man- agers are legitimately surprised to find out GPL'd software is included in their company's products. Engineers sometimes include GPL'd software without understanding the requirements. This does not excuse companies from their obligations under the license, but it does mean that care and patience are essential for reaching GPL compliance. We want companies to understand that participating and benefiting from a collaborative Free Software community is not a burden, so we strive to make the process of coming into compliance as smooth as possible.

2. **GPL的合规需要友好协商和合作。** 通常情况下，法务人员和管理层在发现公司产品中包含GPL软件时，理所当然地会感到惊讶。工程师有时会在不了解需求的情况下使用GPL软件。而这并不能作为免除企业在许可证框架下相关义务的借口，但这也确实意味着实现GPL合规必须具备严谨和耐心。我们希望企业能够理解，参与并受益于一个自由软件社区的协作并非会成为负担，因此我们努力促使合规过程尽量顺利。

3. **Confirming compliance is a community effort.** The whole point of making sure that software distributors respect the terms of the GPL is to allow a thriving software sharing community to benefit and improve the work. FSF is not the expert on how a compiler for consumer electronic devices should work. We therefore inform the community who originally brought the violation to our attention and ask them to assist in evaluation and confirmation of the product's compliance. Of course, FSF coordinates and oversees the process, but we do not want compliance for compliance's sake; rather, we wish to foster a cooperating community of development around the Free Software in question, and encourage the once-violator to begin participating in that community.

3. **合规确认是社区整体共同努力的结果。** 确保软件发行者尊重GPL条款的全部意义在于允许一个蓬勃发展的软件共享社区从中受益并完善。FSF对消费类电子设备编译器并不擅长。因此，我们通知了最初报告违规问题的社区，并请他们协助评估和确认产品的合规性。当然，FSF对这个过程进行了协调和监督，但我们并不希望大家为了合规而合规；相反，我们更愿意围绕所讨论的自由软件来建立一个合作开发的社区，并鼓励曾经的违反者也参与到这个社区中来。

4. **Informing the harmed community is part of compliance.** FSF asks violators to make some attempt --- such as via newsletters and the company's Web site --- to inform those who already have the products as to their rights under the GPL. One of the key thrusts of the GPL's 1 and 3 is to *make sure the user knows she has these rights*. If a product was received out of compliance by a customer, she may never actually discover that she has such rights. Informing customers, in a way that is not burdensome but has a high probability of successfully reaching those who would seek to exercise their freedoms, is essential to properly remedy the mistake.

4. **通知受害社区也是合规的工作之一。** FSF要求违规者做出一些尝试——比如通过新闻媒体和公司网站——把GPL权益告诉那些已经成为产品用户的人们。GPL第1条和第3条的重点之一便是确保用户了解自己拥有这些权利。如果客户收到的产品不符合规范，他可能永远不会清晰的知道自己享有这样的权利。要正确地纠正错误，必须采用一种不折腾、又最可能成功地联系到的方式通知那些想要行使自由权利的客户。

5. **Lines between various copyright, patent, and other legal > mechanisms must be precisely de- fined and considered.** The most difficult negotiation point of the Bortez case was drafting language that simultaneously protected Bortez's patent rights outside of the GPL'd source, but was consistent with the implicit patent grant in the GPL. As we discussed in the first course of this series, there is indeed an implicit patent grant with the GPL, thanks to 6 and 7. However, many companies become nervous and wish to make the grant explicit to assure themselves that the grant is sufficiently narrow for their needs. We understand that there is no reasonable way to determine what patent claims read on a company's GPL holdings and which do not, so we do not object to general language that explicitly narrows the patent grant to only those patents that were, in fact, exercised by the GPL'd software as released by the company.

5. **必须精确地定义和考虑各种版权、专利和其他法律机制之间的界限。** Bortez案最困难的谈判环节是起草文本，需要保护Bortez在GPL来源之外的专利权，并兼顾GPL隐性专利授权的一致性。正如我们在本系列的第一节课中所讨论的，依照第6条和第7条规定，GPL确实存在隐性专利授权。然而，许多企业开始关切，希望对补偿加以明确，以确保范围足以满足他们的需要。我们知道并没有科学的方法来确定哪些专利声明是或者不是基于企业GPL所有权，因此我们不反对将专利授予范围明确缩小到那些实际上由企业发布的GPL软件行使的专利上。


## CHAPTER 23 BRACKEN: A MINOR VIOLATION IN A GNU/LINUX DISTRIBUTION

## 第23章 BRACKEN：GNU/LINUX发行版中的一次小违规

In this case study, we consider a minor violation made by a company
whose knowledge of the Free Software community and its functions is
deep.

在这个案例的研究过程中，我们来讨论一个轻微的违规行为，该企业对自由软件社区及其功能有着很透彻的了解。

### The Facts

### 23.1 事情经过

Bracken produces a GNU/Linux operating system product that is sold
primarily to OEM vendors to be placed in appliance devices used for a
single purpose, such as an Internet-browsing-only device. The product
is almost 100% Free Software, mostly licensed under the GPL and
related Free Software licenses.

Bracken研发了一款GNU/Linux操作系统产品，主要客户是OEM供应商，可应用于单一用途的电器设备中，例如仅用于互联网浏览的设备。该产品几乎100%使用了自由软件，大部分是在GPL和相关的自由软件许可证下授权的。

FSF found out about this violation through a report first posted on a
Slashdot[^1^](#_bookmark246) comment, and then it was brought to our
attention again by another Free Software copyright holder who had
discovered the same violation.

FSF通过Slashdot[^1^](#_bookmark246) 上的一篇评论报告发现了这一违规行为，之后另一名自由软件版权所有者发现了同样的违规行为，这再次引起了我们的注意。

Bracken's GNU/Linux product is delivered directly from their Web site.
This allowed FSF engineers to directly download and confirm the
violation quickly. Two primary problems were discovered with the
online distribution:

Bracken的GNU/Linux产品直接通过他们的网站发行。因此FSF工程师可以直接下载并快速确认违规。我们发现了在线分发的两个主要问题:

No source code nor offer for source code was provided for a number of
components for the distributed GNU/Linux system; only binaries were
available

- 没有为分布式GNU/Linux系统的诸多组件提供源代码或源代码报价；只有二进制文件可用；

An End User License Agreement ("EULA") was included that contradicted
the permissions granted by the GPL

- 包含了与GPL授予的权限相矛盾的最终用户许可协议(“EULA”) ；

FSF contacted Bracken and gave them the details of the violation.
Bracken immediately ceased distri- bution of the product temporarily
and set forth a plan to bring themselves back into compliance. This
plan included the following steps:

FSF与Bracken取得联系，告知他们违规的细节。Bracken立即叫停了该产品的分销，并制定了一项计划，使自己重新合规。该计划包括以下步骤:

Bracken attorneys would rewrite the EULA to comply with the GPL and
would vet the new EULA through FSF before use

- Bracken律师将重写符合GPL的EULA，并在使用前交由FSF对新EULA进行审查。

Bracken engineers would provide source side-by-side with the binaries
for the GNU/Linux distribution on the site (and on CD's, if ever they
distributed that way)

- Bracken工程师将在线为GNU/Linux发行版提供源代码和二进制文件（如以CD方式发行，同样也会提供）

Bracken attorneys would run an internal seminar for its engineers
regarding proper GPL compliance to help ensure that such oversights
regarding source releases would not occur in the future

- Bracken的律师将为其工程师举办一场关于正确遵循GPL的内部研讨会，以帮助确保此类关于源代码发布的疏忽在未来不会再发生。

^1^[]{#_bookmark246 .anchor}Slashdot is a popular news and discussion
site for technical readers.

^1^[]{#_bookmark246 .anchor}Slashdot是一个受技术读者欢迎的新闻和讨论平台。

Bracken would resume distribution of the product only after FSF
formally restored Bracken's distri- bution rights

- 只有在FSF正式恢复Bracken的分销权后，Bracken才可以恢复该产品的分销。

This case was completed in about a month. FSF approved the new EULA
text. The key portion in the EULA relating to the GPL read as follows:

这个案件大约一个月就办理完毕了。FSF批准了新的EULA文本。EULA中与GPL相关的关键部分如下:

Many of the Software Programs included in Bracken Software are
distributed under the terms of agreements with Third Parties ("Third
Party Agreements") which may expand or limit the Licensee's rights to
use certain Software Programs as set forth in \[this EULA\]. Certain
Software Programs may be licensed (or sublicensed) to Licensee under
the GNU General Public License and other similar license agreements
listed in part in this section which, among other rights, permit the
Licensee to copy, modify and redistribute certain Software Programs,
or portions thereof, and have access to the source code of certain
Software Programs, or portions thereof. In addition, certain Software
Programs, or portions thereof, may be licensed (or sublicensed) to
Licensee under terms stricter than those set forth in \[this EULA\].
The Licensee must review the electronic documentation that accompanies
certain Software Programs, or portions thereof, for the applicable
Third Party Agreements. To the extent any Third Party Agreements
require that Bracken provide rights to use, copy or modify a Software
Program that are broader than the rights granted to the Licensee in
\[this EULA\], then such rights shall take precedence over the rights
and restrictions granted in this Agreement solely for such Software
Programs.

Bracken产品中的许多软件程序都是根据与第三方签署的协议条款(“第三方协议”)来分发的，这些协议条款可能在被许可方使用[本EULA]中规定的某些软件程序的权利时扩展或限制。一些软件程序可以根据GNU通用公共许可证和本章列出的其他相似许可协议授权(或二次授权)给被许可方，在其他权利中，允许被许可方复制、修改和重新发布某些软件或其中一部分程序，并有权访问某些软件或其部分程序的源代码。另外，某些软件或其部分程序可按照比[本EULA]更严格的条款授权(或二次授权)给被许可方。被许可方必须审阅这些软件或其部分程序的电子文档附件，以了解适用的第三方协议。如果任何第三方协议要求Bracken提供比[本EULA]向被许可方授予的更广泛的使用、复制或修改软件程序的权利，则该权利的级别应优先于本协议中授予该软件程序的权利和限制的等级。

FSF restored Bracken's distribution rights shortly after the work was
completed as described.

在工作完成后不久，FSF恢复了Bracken的分销权。

### 23.2 Lessons Learned

### 23.2 经验教训

This case was probably the most quickly and easily resolved of all GPL
violations in the history of FSF's Compliance Lab. The ease with which
the problem was resolved shows a number of cultural factors that play
a role in GPL compliance.

这个案例可能是FSF合规实验室历史上最快速、最容易解决的GPL违规事件。相关问题的轻松解决表明了许多文化因素在GPL合规中发挥了作用。

1. **Companies that understand Free Software culture better have an
    > easier time with compli- ance.** Bracken's products were designed
    > and built around the GNU/Linux system and Free Software
    > components. Their engineers were deeply familiar with the Free
    > Software ecosystem, and their lawyers had seen and reviewed the
    > GPL before. The violation was completely an honest mistake. Since
    > the culture inside the company had already adapted to the
    > cooperative style of resolution in the Free Software world, there
    > was very little work for either party to bring the product into
    > compliance.

1. **了解自由软件文化的企业更容易做到合规。**
    > Bracken的产品是基于GNU/Linux系统和自由软件组件而设计和构建的。他们的工程师非常熟悉自由软件生态系统，他们的律师之前阅读并审查过GPL。这次违规完全是无心之过。由于企业内部的文化已经适应了自由软件世界的协作解决方式，各方所需开展的工作很少，即可使产品重新合规。

2. **When people in key positions understand the Free Software nature
    > of their software products, compliance concerns are as mundane as
    > minor software bugs.** Even the most functional system or
    > structure has its problems, and successful business often depends
    > on agile response to the problems that do come up; avoiding
    > problems altogether is a pipe dream. Minor GPL violations can and
    > do happen even with well-informed redistributors. However,
    > resolution is reached quickly when the company --- and in
    > particular, the lawyers, managers, and engineers working on the
    > Free Software product lines --- have adapted to Free Software
    > culture that the lower-level engineer already understood

2. **当处于关键位置的人理解其软件产品的自由软件本质时，合规问题就像软件的小错误一样普通了。**
    > 即使是功能最强大的系统或结构也有它的问题，成功的业务往往取决于对出现问题的敏捷反应；完全避免问题是一个白日做梦。即使是经验丰富的再发布者也会发生轻微违反GPL的情况。然而，当企业——特别是律师、经理和在自由软件产品一线工作的工程师——就连基层工程师也已经理解并适应自由软件文化时，解决方案很快就会落实。

3. **Legally, distribution must stop when a violation is identified.**
    > In our opinion, Bracken went above and beyond the call of duty by
    > ceasing distribution while the violation was being resolved. Under
    > GPL 4, the redistributor loses the right to distribute the
    > software, and thus they are in ongoing violation of copyright law
    > if they distribute before rights are restored. It is FSF's policy
    > to temporarily allow distribution while compliance negotiations
    > are ongoing and only in the most extreme cases (where the other
    > party appears to be negotiating in bad faith) does FSF even
    > threaten an injunction on copyright grounds. However, Bracken ---
    > as a good Free Software citizen --- chose to be on the safe side
    > and do the legally correct thing while the violation case was
    > pending. From start to finish, it took less than a month to
    > resolve. This lapse in distribution did not, to FSF's knowledge,
    > impact Bracken's business in any way.

3. **依照法律要求，分发任务在确认违规行为时必须立刻中止。**
    > 从我们的角度来看，Bracken在解决违规问题时停止分发，属于超出责任范围之外。根据GPL 4，再发布者不继续享有分发软件的权利，因此，如果他们在恢复权利之前分发软件，就违反了版权法。FSF的政策是在合规谈判进行期间暂时允许发行，只有在最极端的情况下(当另一方疑似恶意谈判时)，FSF才会以版权为由发出禁止警告。然而，Bracken——作为一个优秀的自由软件公民——选择了稳妥的做法，在违规案件悬而未决的时候做了法律上正确的事情。从开始到结束，用时不到一个月就解决了。据FSF所知，这次分销上的失误并没有以任何方式影响到Bracken的业务。

4. **EULAs are a common area for GPL problems.** Often, EULAs are
    > drafted from boilerplate text that a company uses for all its
    > products. Even the most diligent attorneys forget or simply do not
    > know that a product contains software licensed under the GPL and
    > other Free Software licenses. Drafting a EULA that accounts for
    > such licenses is straightforward; the text quoted above works just
    > fine. The EULA must be designed so that it does not trump rights
    > and permissions already granted by the GPL. The EULA must clearly
    > state that if there is a conflict between it and the GPL, with
    > regard to GPL'd code, the GPL is the overriding license.

4. **EULA是GPL问题的一个常见领域。**
    > 通常情况下，EULA的策划是以企业的产品样板文本为基础的。即使是最认真的律师也会忘记或不清楚某个产品是否包含基于GPL和其他自由软件许可证的软件。起草一份对此类许可做出规范的EULA并不难，前面引用的这篇文章就是个很好的参照。EULA在设计时必须确保它不会超出GPL已经授予的权利和权限。EULA必须明确声明，如果与GPL之间存在冲突，GPL对于GPL代码具有上位覆盖许可权力。

5. **Compliance Officers are rarely necessary when companies are
    > educated about GPL com- pliance.** As we saw in the Bortez case,
    > FSF asks that a formal "GPL Compliance Officer" be appointed
    > inside a previously violating organization to shepherd the
    > organization to a cooperative approach to GPL compliance. However,
    > when FSF sees that an organization already has such an approach,
    > there is no need to request that such an officer be appointed.

5. **当企业具有GPL合规培养环境时，合规官的作用并不明显。**
    > 正如我们在Bortez案例中所看到的，FSF要求在先前违反GPL的企业内部任命一个正式的“GPL合规官”，以指导企业采取合作的方法来遵守GPL。然而，当FSF看到一个组织已经有这样的态度时，便没有必要再强制要求这类人事任命。


## CHAPTER 24 VIGORIEN: SECURITY, EXPORT CONTROLS, AND GPL COMPLIANCE

## 第24章 Vigorien：安全、出口管制和GPL合规性

This case study introduces how concerns of "security through obscurity" and regulatory problems can impact GPL compliance matters.

本案例研究介绍了"安全通过混淆"和法规问题如何影响GPL合规问题。

### 24.1 The Facts

### 24.1 事实

Vigorien distributes a back-up solution product that allows system administrators to create encrypted back- ups of file-systems on Unix-like computers. The product is based on GNU tar, a backup utility that replaces the standard Unix utility simply called tar, but has additional features.

Vigorien分发一款备份解决方案产品，使系统管理员能够在类Unix计算机上创建加密备份文件系统。该产品基于GNU tar，这是一种备份实用程序，可以替换称为tar的标准Unix实用程序，并具有其他功能。

Vigorien's backup solution added cryptographic features to GNU tar, and included a suite of utilities and graphical user interfaces surrounding GNU tar to make backups convenient.

Vigorien分发一款备份解决方案产品，使系统管理员能够在类Unix计算机上创建加密备份文件系统。该产品基于GNU tar，这是一种备份实用程序，可以替换称为tar的标准Unix实用程序，并具有其他功能。

FSF discovered the violation from a user report, and determined that the cryptographic features were the only part of the product that constituted a derivative work of GNU tar; the extraneous utilities merely made shell calls out to GNU tar. FSF requested that Vigorien come into compliance with the GPL by releasing the source of GNU tar, with the cryptographic modifications, to its customers.

FSF从用户报告中发现了这一违规行为，并确定加密功能是该产品中唯一构成GNU tar衍生作品的部分；多余的实用程序只是向GNU tar发出shell调用。FSF要求Vigorien通过向其客户发布带有加密修改的GNU tar源代码来符合GPL。

Vigorien released the original GNU tar sources, but kept the cryptographic modifications proprietary. They argued that the security of their system depending on keeping the software proprietary and that regardless, USA export restrictions on cryptographic software prohibited such a release. FSF disputed the first claim, pointing out that Vigorien had only one option if they did not want to release the source: they would have to remove GNU tar from the software and not distribute it further. Vigorien rejected this suggestion, since GNU tar was an integral part of the product, and the security changes were useless without GNU tar.

Vigorien发布了原始的GNU tar源代码，但保留了加密修改的专有权利。他们认为，系统的安全性取决于保持软件的专有性，并且无论如何，美国对加密软件的出口限制禁止这样的发布。FSF对第一项声明表示异议，指出如果他们不想发布源代码，只有一个选择：他们必须从软件中删除GNU tar，并不再分发它。Vigorien拒绝了这个建议，因为GNU tar是产品的一个重要组成部分，而没有GNU tar，安全更改是无用的。

Regarding the export control claims, FSF proposed a number of options, including release of the source from one of Vigorien's divisions overseas where no such restrictions occurred, but Vigorien argued that the problem was insoluble because they operated primarily in the USA.

关于出口控制的说法，FSF提出了许多选项，包括从Vigorien在没有此类限制的海外分支之一发布源代码，但Vigorien认为问题是无法解决的，因为他们主要在美国运营。

The deadlock on the second issue was resolved when those cryptographic export restrictions were lifted shortly thereafter, and FSF again raised the matter with Vigorien. At that point, they dropped the first claim and agreed to release the remaining source module to their customers. They did so, and the violation was resolved.

第二个问题的僵局在加密出口限制不久后解决，此后FSF再次向Vigorien提出了这个问题。此时，他们放弃了第一个声明，并同意向其客户发布剩余的源代码模块。他们这样做了，违规行为得到了解决。

### 24.2 Lessons Learned

### 24.2 教训

1. **Removing the GPL'd portion of the product is always an option.** Many violators' first response is to simply refuse to release the source code as the GPL requires. FSF offers the option to simply remove the GPL'd portions from the product and continue along without them. Every case where this has been suggested has led to the same conclusion. Like Vigorien, the violator argues that the product cannot function without the GPL'd components, and they cannot effectively replace them.

Such an outcome is simply further evidence that the combined work in question is indeed a modified version of the original GPL'd component. If the other components cannot stand on their own and be useful without the GPL'd portions, then one cannot effectively argue that the work as a whole is not a based on the GPL'd portions.

2. **The whole product is not always covered.** In this case, Vigorien had additional works aggregated. The backup system was a suite of utilities, some of which were the GPL and some of which were not. While the cryptographic routines were tightly coupled with GNU tar and clearly made a whole new combined work of both components, the various GUI utilities were separate and independent works merely aggregated with the distribution of the GNU-tar-based product.

3. **"Security" concerns do not exonerate a distributor from GPL obligations, and "security through obscurity" does not work anyway.** The argument that "this is security software, so it cannot be released in source form" is not a valid defense for explaining why the terms of the GPL are ignored. If companies do not want to release source code for some reason, then they should not base the work on GPL'd software. No external argument for noncompliance can hold weight if the work as a whole is indeed a modified version of a GPL'd program.

The "security concerns" argument is often floated as a reason to keep software proprietary, but the computer security community has on numerous occasions confirmed that such arguments are entirely specious. Security experts have found --- since the beginnings of the field of cryptography in the ancient world --- that sharing results about systems and having such systems withstand peer review and scrutiny builds the most secure systems. While full disclosure may help some who wish to compromise security, it helps those who want to fix problems even more by identifying them early.

4. **External regulatory problems can be difficult to resolve.** The GPL, though grounded in copyright law, does not have the power to trump regulations like export controls. While Vigorien's "security concerns" were specious, their export control concerns were not. It is indeed a difficult problem that FSF acknowledges. We want compliance with the GPL and respect for users' freedoms, but we certainly do not expect companies to commit criminal offenses for the sake of compliance. We will see more about this issue in our next case study.

<br/>

1. **移除产品中受GPL保护的部分始终是一种选择。** 许多违规者的第一反应是拒绝按照GPL要求发布源代码。FSF提供了一种简单的解决方案，即从产品中简单地移除受GPL保护的部分，然后继续使用其他部分。每个这样建议的案例都导致了相同的结论。就像Vigorien一样，违规者辩称，如果没有GPL保护的组件，产品无法正常运行，并且他们无法有效地替换它们。

这样的结果仅仅进一步证明，涉及的组合作品确实是原始GPL组件的修改版本。如果其他组件不能独立运行且没有GPL的部分有用，则不能有效地主张整个作品不是基于GPL组件的。

2. **整个产品并不总是被覆盖。** 在这种情况下，Vigorien还有其他聚合的作品。备份系统是一套实用工具，其中一些是GPL，一些不是。虽然加密例程与GNU tar紧密耦合，并明显形成了GNU-tar-based产品的全新组合作品，但各种GUI实用程序是单独和独立的作品，仅仅是与分发GNU-tar-based产品的聚合。

3. **“安全”问题不能使分发者免除GPL义务。**“通过模糊来保护安全性”也行不通。“这是安全软件，因此不能以源代码形式发布”这种论点不是一个有效的辩护理由，解释为什么忽略了GPL的条款。如果公司出于某种原因不想发布源代码，那么他们就不应该以GPL软件为基础进行开发。如果整个作品确实是GPL软件的修改版本，那么任何非遵守的外部论点都没有说服力。

“安全问题”论点经常被提出作为保持软件专有的理由，但是计算机安全社区在许多场合证实，这种论点完全是无稽之谈。自古代密码学领域以来，安全专家们已经发现，共享关于系统的结果，并让这些系统经受同行评审和审查，构建最安全的系统。虽然完全披露可能有助于一些想要破坏安全的人，但它更有助于那些想要尽早识别问题并修复它们的人。

4. **外部监管问题可能难以解决。**尽管GPL是基于版权法的，但它无法取代出口管制等法规。尽管Vigorien的“安全担忧”是牵强的，但他们的出口管制担忧并非如此。这确实是一个FSF承认的难题。我们希望遵守GPL并尊重用户的自由，但我们肯定不希望公司为了遵守GPL而犯罪。我们将在下一个案例研究中详细了解这个问题。


## CHAPTER 25 HAXIL, POLGARA, AND THESULAC: MERGERS, UPSTREAM PROVIDERS AND RADIO DEVICES

## 第25章 HAXIL，POLGARA和THESULAC：合并，上游供应商和无线电设备

This case study considers an ongoing (at the time of writing) violation that has occurred. By the end of the investigation period, three companies were involved and many complex issues arose.

本案例研究考虑了一起正在发生（在撰写本文时）的侵犯行为。调查期结束时，三家公司参与其中，出现了许多复杂的问题。

### 25.1 The Facts

### 25.1 事实

Haxil produced a consumer electronics device which included a mini GNU/Linux distribution to control the device. The device was of interest to many technically-minded consumers, who purchased the device and very quickly discovered that Free Software was included without source. Mailing lists throughout the Free Software community erupted with complaints about the problem, and FSF quickly investigated.

Haxil生产了一种消费电子设备，其中包括一个迷你GNU / Linux发行版来控制设备。该设备引起了许多技术爱好者的兴趣，他们购买了该设备，并很快发现其中包含未附源代码的自由软件。整个自由软件社区的邮件列表都在抱怨这个问题，FSF迅速展开调查。

FSF confirmed that FSF-copyrighted GPL'd software was included. In addition, the whole distribution included GPL'd works from hundreds of individual copyright holders, many of whom were, at this point, up in arms about the violation.

FSF确认包含了FSF版权的GPL软件。此外，整个发行版包括来自数百个个人版权持有者的GPL作品，其中许多人此时都对侵犯行为感到愤怒。

Meanwhile, Haxil was in the midst of being acquired by Polgara. Polgara was as surprised as everyone else to discover the product was based on GPL'd software; this fact had not been part of the disclosures made during acquisition. FSF contacted Haxil, Polgara, and the product managers who had transitioned into the "Haxil division" of the newly-merged Polgara company. Polgara's General Counsel's office worked with FSF on the matter.

同时，Haxil正在被Polgara收购。Polgara像其他人一样惊讶地发现该产品是基于GPL软件构建的；这个事实在收购过程中没有被披露。FSF联系了Haxil，Polgara和已经转入新合并的Polgara公司的“Haxil部门”的产品经理。Polgara的总法律顾问办公室与FSF一起处理此事。

FSF formed a coalition with the other primary copyright holders to pursue the enforcement effort on their behalf. FSF communicated directly with Polgara's representatives to begin working through the issues on behalf of itself and the Free Software community at large.

FSF与其他主要版权持有者组成了联盟，代表他们追求执行行动。FSF直接与Polgara的代表沟通，开始代表自己和整个自由软件社区处理问题。

Polgara pointed out that the software distribution they used was mostly contributed by an upstream provider, Thesulac, and Haxil's changes to that code base were minimal. Polgara negotiated with Thesulac to obtain the source, although the issue moved very slowly in the channels between Polgara and Thesulac.

Polgara指出，他们使用的软件发行版大部分是由上游供应商Thesulac提供的，并且Haxil对该代码库的更改很少。Polgara与Thesulac协商以获得源代码，尽管问题在Polgara和Thesulac之间的渠道中进展缓慢。

FSF encouraged a round-table meeting so that high bandwidth communication could occur between FSF, Polgara and Thesulac. Polgara and Thesulac agreed, and that discussion began. Thesulac provided nearly complete sources to Polgara, and Polgara made a full software release on their Web site. At the time of writing, that software still has some build problems (similar to those that occurred with Bortez, as described in Section [22.1).](#facts) FSF continues to negotiate with Polgara and Thesulac to resolve these problems, which have a clear path to a solution and are expected to resolve.

FSF鼓励进行圆桌会议，以便FSF，Polgara和Thesulac之间进行高带宽通信。Polgara和Thesulac同意，并开始讨论。Thesulac几乎完整地提供了源代码给Polgara，Polgara在其网站上发布了完整的软件版本。撰写本文时，该软件仍然存在一些构建问题（与第22.1节中描述的Bortez类似）。FSF继续与Polgara和Thesulac协商解决这些问题，这些问题有一个明确的解决路径，预计会解决。

Similar to the Vigorien case, Thesulac has regulatory concerns. In this case, it is not export controls - an issue that has since been resolved - but radio spectrum regulation. Since this consumer electronic device contains a software-programmable radio transmitter, regulations in (at least) the USA and Japan prohibit release of those portions of the code that operate the device. Since this is a low-level programming issue, the changes to operate the device form a single combined work with the kernel named Linux. A decade later, this situation remains largely unresolved.

与 Vigorien 案类似，Thesulac 也存在监管问题。在这种情况下，不是出口管制问题-该问题已经解决，而是无线电频谱监管问题。由于这种消费电子设备包含软件可编程无线电发射器，美国和日本的法规禁止发布操作该设备的代码部分。由于这是一个低级编程问题，操作设备的更改与名为 Linux 的内核形成一个单独的组合作品。十年后，这种情况仍然没有得到解决。

### 25.2 Lessons Learned

### 25.2 教训

1. **Community outrage, while justified, can often make negotiation more difficult.** FSF has a strong policy never to publicize names of GPL violators if they are negotiating in a friendly way and operating in good faith toward compliance. Most violations are honest mistakes, and FSF sees no reason to publicly admonish violators who genuinely want to come into compliance with the GPL and to work hard staying in compliance.

This case was so public in the Free Software community that both Haxil's and Polgara's representatives were nearly shell-shocked by the time FSF began negotiations. There was much work required to diffuse the situation. We empathize with our community and their outrage about GPL violations, but we also want to follow a path that leads expediently to compliance. In our experience, public outcry works best as a last resort, not the first.

2. **For software companies, GPL compliance belongs on a corporate acquisition checklist.** Polgara was truly amazed that Haxil had used GPL'd software in a major new product line but never informed Polgara during the acquisition process. While GPL compliance is not a particularly difficult matter, it is an additional obligation that comes along with the product line. When planning mergers and joint ventures, one should include lists of GPL'd components contained in the products discussed.

3. **Compliance problems of upstream providers do not excuse a violation for the downstream distributor.** To paraphrase 6, upstream providers are not responsible for enforcing compliance of their downstream, nor are downstream distributors responsible for compliance problems of upstream providers. However, engaging in distribution of GPL'd works out of compliance is still just that: a compliance problem. When FSF carries out enforcement, we are patient and sympathetic when the problem appears to be upstream. In fact, we urge the violator to point us to the upstream provider so we may talk to them directly. In this case, we were happy to begin negotiations with Thesulac. However, Polgara still has an obligation to bring their product into compliance, regardless of Thesulac's response.

4. **It behooves upstream providers to advise downstream distributors about compliance matters.** FSF has encouraged Thesulac to distribute a "good practices for GPL compliance" document with their product. Polgara added various software components to Thesulac's product, and it is conceivable that such additions can introduce compliance. In FSF's opinion, Thesulac is in no way legally responsible for such a violation introduced by their customer, but it behooves them from a marketing standpoint to educate their customers about using the product. We can argue whether or not it is your coffee vendor's fault if you burn yourself with their product, but (likely) no one on either side would dispute the prudence of placing a "caution: hot" label on the cup.

5. **FSF enforcement often avoids redundant enforcement cases from many parties.** Most Free Software systems have hundreds of copyright holders. Some have thousands. FSF is in a unique position as one of the largest single copyright holders on GPL'd software and as a respected umpire in the community, neutrally enforcing the rules of the GPL road. FSF works hard in the community to convince copyright holders that consolidating GPL claims through FSF is better for them, and more likely to yield positive compliance results.

<br/>

1. **社区的公愤，虽然有道理，但通常会使谈判变得更加困难。**自由软件基金会(FSF)有一个强有力的政策，即如果GPL违规者以友好的方式进行谈判并以诚信的态度遵守，FSF将永远不公开GPL违规者的名称。大多数违规都是诚实的错误，FSF认为没有理由公开责备那些真正想遵守GPL并努力保持合规的违规者。

这个案件在自由软件社区是如此公开，以至于 Haxil 和 Polgara 的代表在 FSF 开始谈判时几乎被打击了。需要做很多工作才能化解局势。我们理解我们的社区及其对GPL违规的愤怒，但我们也希望走一条通向合规的捷径。根据我们的经验，公众的抗议最好作为最后一招，而不是第一招。

2. **对于软件公司来说，GPL合规应该列在企业收购清单上。** Polgara 真的很惊讶 Haxil 在一个重要的新产品线中使用了GPL软件，但在收购过程中从未告知 Polgara。虽然GPL合规并不是一个特别困难的问题，但它是随着产品线而来的一个额外义务。在规划合并和合资企业时，应该列出所讨论产品中包含的GPL组件清单。

3. **上游提供商的合规问题并不能为下游分销商的违规行为开脱责任。**换句话说，上游提供商没有责任强制执行下游分销商的合规性，下游分销商也没有责任对上游提供商的合规问题负责。然而，未合规地分发 GPL 作品仍然是一个合规性问题。当 FSF 进行执法时，如果问题似乎出在上游，我们会耐心并且同情。事实上，我们敦促违规者指出上游供应商，以便我们可以直接与他们交流。在这种情况下，我们很高兴开始与 Thesulac 进行谈判。然而，Polgara 仍然有义务使他们的产品符合规定，而不管 Thesulac 的回应如何。

4. **上游提供商应该告知下游分销商合规事宜。**FSF 鼓励 Thesulac 在他们的产品中分发“GPL 合规的良好实践”文档。Polgara 将各种软件组件添加到 Thesulac 的产品中，这可能会引入合规性问题。在 FSF 的看法中，Thesulac 对于客户引入的违规行为没有任何法律责任，但从市场的角度来看，向他们的客户宣传产品的使用方式是值得的。我们可以争论是否应该归咎于您的咖啡供应商，如果您用他们的产品烫伤了自己，但（可能）双方都不会争议在杯子上贴上“注意：热”的标签的明智性。

5. **FSF 的执法通常避免了许多各方的重复执法案件。**大多数自由软件系统有数百个版权持有人。有些有数千个。作为 GPL 软件最大的单一版权持有人之一，以及社区中备受尊重的裁判员，FSF 处于独特的地位，中立地执行 GPL 路线规则。FSF 在社区中努力说服版权持有人通过 FSF 整合 GPL 索赔，这对他们更好，并且更有可能产生积极的合规结果。

A few copyright holders engage in the "proprietary relicensing" business, so they use GPL enforcement as a sales channel for that business. FSF, as a community-oriented, not-for-profit organization, seeks only to preserve the freedom of Free Software in its enforcement efforts. As it turns out, most of the community of copyright holders of Free Software want the same thing. Share and share alike is a simple rule to follow, and following that rule to FSF's satisfaction usually means you are following it to the satisfaction of the entire Free Software community.

几个版权持有者从事“专有重新许可”业务，因此他们将GPL执法用作该业务的销售渠道。作为一个面向社区的非营利组织，FSF仅在其执法工作中寻求保护自由软件的自由。事实证明，大多数自由软件版权持有者社区也希望实现同样的目标。共享并分享是一个简单的规则，遵循这个规则通常意味着你已经达到了整个自由软件社区的满意度。

Generally, from the experience of GPL enforcement, we glean the following general practices that can help in GPL compliance for organizations that distribute products based on GPL'd software:

通常从GPL执法的经验中，我们得出以下对于基于GPL软件的产品进行分发的组织来说可以帮助实现GPL合规的一些通用做法：

- Talk to your software engineers and ask them where they got the components they use in the products they build. Find out if GPL'd components are present.

- Teach your engineering staff to pay attention to license documents. Give them easy-to-follow policies to get approval for using a Free Software component.

- Build a "Free Software Licensing" committee that handles requests and questions about the GPL and other Free Software licenses.

- Add "What parts of your products are under the GPL or other Free Software licenses?" to your checklist of questions to ask when you consider mergers, acquisitions, or joint ventures.

- Encourage your engineers to participate collaboratively with GPL'd software development. The more knowledge about the Free Software world your organization has, the better equipped it is to deal with this rapidly changing field.

- When someone points out a potential GPL violation in one of your products, do not assume the product line is doomed. The GPL is not a virus; merely having GPL'd code in one part of a product does not necessarily mean that every related product must also be GPL'd. And, even if some software needs to be released that was not before, the product will surely survive. In FSF's enforcement efforts, we have not yet seen a product line die because source was released to customers in compliance with the GPL.

- 与你的软件工程师交谈并问问他们从哪里获得他们在构建产品中使用的组件。了解是否存在GPL组件。

- 教育你的工程人员注意许可文件。为他们提供易于遵循的政策，以获取使用自由软件组件的批准。

- 建立一个“自由软件许可”委员会，负责处理GPL和其他自由软件许可的请求和问题。

- 在考虑合并、收购或联合企业时，将“你的产品的哪些部分受GPL或其他自由软件许可证的保护？”添加到你的问题清单中。

- 鼓励你的工程师参与GPL软件开发的协作。你的组织对自由软件世界的了解越多，就越能应对这个快速变化的领域。

- 当有人指出你的产品可能存在GPL违规行为时，不要认为整个产品线都会毁掉。GPL不是病毒；仅仅在产品的某个部分存在GPL代码并不一定意味着每个相关产品都必须成为GPL。即使需要发布一些以前没有发布的软件，该产品也一定会生存。在FSF的执法工作中，我们还没有看到因为向客户发布了符合GPL的源代码而使得产品线死亡的情况。

## Appendices

## 附录

### APPENDIX A** CITATIONS OF INCORPORATED MATERIAL FROM OTHER PUBLISHED WORKS

### 从其他已发表作品中引用的材料的引证

As a public, collaborative project, this Guide is primarily composed of the many contributions received via its [public contribution process.](https://k.copyleft.org/guide/files/master/CONTRIBUTING.md) Please [review its Git logs](https://k.copyleft.org/guide/changelog) for full documentation of all contributions.

作为一项公开的协作项目，本指南主要由通过其公共贡献流程收到的许多贡献组成。请查看Git日志以获取所有贡献的完整文档记录。

Below is a list of CC-By-SA-licensed works, with specific titles and publication dates, from which any material was incorporated into this Guide. The specific methods and details of incorporation are fully documented in the [Git logs](https://k.copyleft.org/guide/changelog) of the project.

以下是CC-By-SA许可的作品列表，包括特定的标题和出版日期，这些作品中的任何材料都被纳入了本指南中。具体的纳入方法和细节在项目的Git日志中得到了充分的记录。

- [*GPLv3 First Discussion Draft Rationale*](http://gplv3.fsf.org/gpl-rationale-2006-01-16.html), published by the Free Software Foundation on 2006-01-16.

- [*GPLv3 Second Discussion Draft Rationale*](http://gplv3.fsf.org/opinions-draft-2.html), published by the Free Software Foundation circa 2006-07.

- [*GPLv3 Third Discussion Draft Rationale*](http://gplv3.fsf.org/gpl3-dd3-guide), published by the Free Software Foundation on 2007-03-28.

- [*GPLv3 Discussion Draft 3 FAQ*](http://gplv3.fsf.org/dd3-faq) , published by the Free Software Foundation on 2007-03-28.

- [*GPLv3 Final Discussion Draft Rationale*](http://gplv3.fsf.org/gpl3-dd4-guide.html), published by the Free Software Foundation on 2007-05-31.

- [*GPLv3 Final Rationale*](http://www.gnu.org/licences/gpl3-final-rationale.pdf), written and published by the Free Software Foundation on 2007-06-29.

- [GPLv3第一次讨论草案理由](http://gplv3.fsf.org/gpl-rationale-2006-01-16.html)，由自由软件基金会于2006年1月16日发布。

- [GPLv3第二次讨论草案理由](http://gplv3.fsf.org/opinions-draft-2.html)，由自由软件基金会于2006年7月左右发布。

- [GPLv3第三次讨论草案理由](http://gplv3.fsf.org/gpl3-dd3-guide)，由自由软件基金会于2007年3月28日发布。

- [GPLv3第三次讨论草案常见问题解答](http://gplv3.fsf.org/dd3-faq)，由自由软件基金会于2007年3月28日发布。

- [GPLv3最终讨论草案理由](http://gplv3.fsf.org/gpl3-dd4-guide.html)，由自由软件基金会于2007年5月31日发布。

- [GPLv3最终理由](http://www.gnu.org/licences/gpl3-final-rationale.pdf)，由自由软件基金会于2007年6月29日撰写并发布。

[*A Practical Guide GPL Compliance*](http://www.softwarefreedom.org/resources/2008/compliance-guide.html), written by Bradley M. Kuhn, Aaron Williamson and Karen Sandler and published by the Software Freedom Law Center on 2008-08-20.

[GPL合规实践指南](http://www.softwarefreedom.org/resources/2008/compliance-guide.html)，由Bradley M. Kuhn、Aaron Williamson和Karen Sandler撰写，并于2008年8月20日由软件自由法律中心出版。

[*Software Freedom Law Center Guide to GPL Compliance, 2nd Edition*](http://www.softwarefreedom.org/resources/2014/SFLC-Guide_to_GPL_Compliance_2d_ed.html), written by Eben Moglen and Mishi Choudhary and published by the Software Freedom Law Center on 2014-10-31.

[软件自由法律中心GPL合规指南第2版](http://www.softwarefreedom.org/resources/2014/SFLC-Guide_to_GPL_Compliance_2d_ed.html)，由Eben Moglen和Mishi Choudhary撰写，并于2014年10月31日由软件自由法律中心出版。

*Detailed Analysis of the GNU GPL and Related Licenses*, written by Bradley M. Kuhn, Daniel B. Ravicher, and John Sullivan and published by the Free Software Foundation for its CLE courses on 2004-01-20, 2004-08-24, and 2014-03-24.

《GNU GPL及相关许可证的详细分析》是由Bradley M. Kuhn、Daniel B. Ravicher和John Sullivan所著，由自由软件基金会于2004年1月20日、2004年8月24日和2014年3月24日发表于其CLE课程中的一篇文章。

*Enforcement Case Studies*, written by Bradley M. Kuhn and published by the Free Software Foundation for its CLE courses on 2004-01-20, 2004-08-24, and 2014-03-24.

《执行案例研究》是Bradley M. Kuhn撰写的，由自由软件基金会于2004年1月20日、2004年8月24日和2014年3月24日为其CLE课程出版。

Please note, however, that this list above does not include nor adequately represent the substantial contributions from those who directly contributed to this Guide using its Git (and formerly, CVS) repository. Rather, this is a list of third-party published works from which any text was herein included under their CC-By-SA licensing. Thus, as the reader might expect, the [version control logs](https://k.copyleft.org/guide/changelog) contain the only true and accurate view available of who has contributed which portions of this project.

请注意，上述列表不包括也无法充分代表那些直接通过Git（以前是CVS）代码库对本指南做出实质性贡献的人。相反，这是一个第三方已发布作品的列表，其中任何文本都是根据它们的CC-By-SA许可证在此处包含的。因此，正如读者所期望的那样，版本控制日志 包含了对谁在此项目的哪些部分做出了贡献的唯一真实和准确的视图。

The remaining appendices include a full copy of GPLv2, GPLv3, LGPLv2.1, LGPLv3, and AGPLv3.

其余的附录包括 GPLv2、GPLv3、LGPLv2.1、LGPLv3 和 AGPLv3 的完整副本。

These are the most commonly used licenses in the GPL family of licenses.

这些是GPL许可证家族中最常用的许可证。

## APPENDIX B GNU通用公共许可证

第二版，1991年6月

版权所有(C) 1989，1991自由软件基金会

51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA

任何人都可以复制和发布本许可证完整副本，但不允许修改。

## 译者声明

This is an unofficial translation of the GNU General Public License into Chinese. It was not published by the Free Software Foundation, and does not legally state the distribution terms for software that uses the GNU GPL--only the original English text of the GNU GPL does that. However, we hope that this translation will help Chinese speakers understand the GNU GPL better.

本译文是GNU通用公共许可证的一份非官方中文翻译，并非自由软件基金会所发表，不适用于使用GNU通用公共许可证发布的软件的法律声明——只有GNU通用公共许可证英文原版才具有法律效力。不过我希望本翻译能够帮助中文读者更好地理解GNU通用公共许可证。

You may publish this translation, modified or unmodified, only under the terms at <https://www.gnu.org/licenses/translations.html>.

仅在遵循 <https://www.gnu.org/licenses/translations.html> 中的条款时，你才可以经过修改地或者不经过修改地发布本译文。

## 序言

大部分软件的许可证都是被设计为剥夺你分享和修改的自由。相反，GNU通用公共许可证的目的是保护你分享和修改自由软件的自由——确保软件对所有用户都是自由的。本通用公共许可证适用于自由软件基金会的大部分软件以及任何作者承诺使用该许可证的软件（自由软件基金会的其他一些软件受GNU宽松通用许可证的保护）。你也可以将本许可证用于你的程序。

自由软件，强调的是自由，而不是免费。本通用公共许可证的目的是保证你拥有分发自由软件的自由（如果你愿意还可以为此收费），确保你有收到源代码或者想要获得时拥有获得源代码的自由，确保你想要修改或者在新的自由软件中使用其中代码的自由，并且确保你有知情权。

为了保护你的权利，我们设置了一些限制以防止其他人否定你的权利或者要求你放弃你的权利。这些限制在你分发或者修改这些软件时会成为你的责任。

例如，你分发这类软件的副本，无论是免费的或者收费的，你必须授予接收者你拥有的所有权利。你必须保证他们也能收到或者能够获得源代码。并且你也要确保他们也知道他们的权利。

我们通过两步保护你的权利：(1) 授予软件著作权；(2) 赋予你合法复制、分发和修改软件的权利。

此外，为了保护每一位作者和我们自己，我们向每个人声明：自由软件是没有任何品质保证的。如果被其他人修改或者转发，我们希望接收者知道他们收到的不是原始版本，因此其他人引入的任何问题不会影响原作者的声誉。

最后，自由软件还不停地收到软件专利的威胁。我们希望避免自由软件分发者以个人名义获取专利，从而导致自由软件成为私有软件。为了避免这种事情发生，我们明确声明：任何专利必须许可给任何人自由使用或者完全不进行许可。

以下是复制、分发和修改的具体条款和条件。

## 复制、分发与修改条款和条件

0、本许可适用于任何版权持有人在他的程序或作品中声明以通用许可证条款发布的程序或作品。“程序”在下文中是指，任何程序或者作品，“程序的衍生作品”是指程序或者衍生作品包含该程序的全部或者部分，无论是逐字复制地或者经过修改的，或者是翻译成其他语言的。（下文中，翻译属于但不限于修改的范围）。每个被许可人均指“你”。

除复制、分发、修改之外的其他行为不在本许可范围内。运行软件的行为是不受约束的，软件的输出一般不在本许可范围内，除非它构成了本程序的衍生作品（单独通过运行本软件产生）。具体情况依程序用途而定。

1、如果你发布每个副本时，在明显的位置包含适当的版权声明和免责声明，包含本许可证的全部声明和免责声明，你就可以在任何介质上复制和原文分发你收到的软件的源代码。

你可以为你实际发送副本的实际行为收取费用，你也可以提供品质保证收取费用。

2、你可以通过修改本程序副本或者其中任意部分，从而构成衍生作品，并在满足条款1以及下列3点要求的前提下复制或者分发修改的作品。

  a）你必须在修改后的文件带有明显的声明，说明你修改的任何文件和日期。

  b）你必须将你发布或者发表的整个或者部分，或者基于本程序或者任意部分衍生的作品，全部免费地按照本许可证许可给所有第三方。

  c）如果修改后的软件在运行时通常以交互的方式读取命令，你必须在让程序进入交互模式时打印或者显示合适的版权声明和免责声明（或者，你也可以提供品质保证），并且告诉用户可以在本约束下分发本软件，告知用户如何查阅本许可证（例外：如果程序本来就是交互方式的但不打印声明，你的衍生作品也不需要打印声明）。

上述要求对修改后作品的整体有效。如果作品可以独立的部分不是从本软件衍生的，可以合理地将它们作为独立或者单独的作品，进行单独分发，本许可及其条款不适应于它们。但是，当你将它们与本程序的衍生作品一同发布时，分发的作品必须作为一个整体按照本许可证许可，本许可证的授权延伸到全部作品，而无论其任何部分是谁写的。

因此，本条款的目的不是声明或者争辩你创造的作品的全部权利，而是行使控制本程序衍生作品或者集体作品的分发权利。

另外，仅仅与本程序或者衍生作品一同存储或者通过同一个介质上分发的其他非本程序的衍生作品不在本许可证范围内。

3、在上述第1条和第2条约束下，你可以复制或者分发本程序（或根据第2条的衍生作品）的目标代码或者可执行格式分发本程序时，你必须满足下列要求：

a）根据上述第1条和第2条要求，附上完整的、机器可读的源代码，按照常用的软件交换媒介分发。或者

  b）附上至少3年有效期的书面报价，向任何第三方，收取不高于你因分发源代码的实际花费的费用。源代码是根据上述第1条和第2条要求机器可读的完整的源代码，通过常用的软件交换介质分发。或者

  c）附上你所收到的源代码的信息（该要求仅适用于非商业性分发，并且仅当你收到程序是目标代码或者可执行格式，同时还要满足本条款b项要求）。

  作品的源代码是修改作品的首选格式。对于一个可执行的作品，完整的源代码是指其所有模块的所有源代码、相关接口定义文件、编译和安装所需的脚本。然而，作为例外，分发的源代码不必包括任何通常随运行本软件的目标操作系统的主要组件（编译器、内核等）一同分发的（源代码或者二进制）文件，除非它们是本软件的一部分。

如果是通过指定访问位置的形式分发可执行文件或者目标代码，那么提供获取源代码副本相同地址也算分发源代码，即使不要求第三方在复制目标代码时复制源代码。

4、除本许可证许可之外，你不能复制、修改、再许可或者分发本程序。试图进行任何其他形式的复制、修改、再许可或者分发本程序都是无效的，并且本许可证授予你的权利自动终止。然而，只要符合本许可证条款，从你获得副本的其他人的权利仍然有效。

5、你没有签署本许可证，你也不必接受本许可证。而且，此外无人可以授权你修改本程序及其衍生作品。除非你接受本许可证，否则这些行为是被法律禁止的。然而，修改或者分发本软件（或基于本软件的任何作品），表明你接受本许可证复制、分发或者修改本软件或者基于本软件的条款和条件。

6、你每次再分发本程序（或本程序的衍生作品）时，接收者自动从原始权利人获得本许可，以复制、分发或者修改本软件。你不能对他们获得的权利引入任何限制。你也没有要求第三方遵循本许可的责任。

7、如果由于法庭裁决或者专利侵权或者其他原因（不限于专利），使得你面临与本许可证冲突的情况（无论由于法庭裁决、协议或者其他），这也不能成为你不遵守本许可证的理由。如果你不分发本程序，就能满足本许可证条款和其他相关要求，你就不要分发本软件。例如，某专利许可不允许直接或者间接从你获得副本的接受者免费再分发本软件，为了同时满足本许可证和它的要求，你的唯一做法就是不再分发本软件。

如果在特定情况下本条款的任何部分无效或者无法实施，本条款的其余部分仍然适用，并且本条款作为整体适用于其他情况。

本条款的目的不是怂恿你违反任何专利或者其他权利要求，或者与它们抗辩。本条款的目的纯粹是保护自由软件分发系统的完整性，即通过公共许可证来实现。通过一致地应用该分发系统，很多人已经向通过该系统分发的大量软件做出了慷慨的贡献；作者/贡献者也可以决定是否愿意通过其他渠道分发，被授权人无权干涉该决定。

本条款旨在彻底阐明本许可其他条款所带来的当然后果。

8、如果本程序的分发和/或使用收到一些国家专利或者著作权的限制，权利人可以在通过本许可证授权的软件中明确添加受限的地理范围，以排除那些受限的国家，因此分发仍然可以在其他国家进行。这种情况下，本许可将这些限制纳入许可范围内。

9、自由软件基金会可能不时发布通用公共许可证的修订版和/或新版本。此类新版本与当前版本精神上相似，但在描述细节上可能不同，以解决新问题或情况。

每个版本都有一个唯一的版本号。如果软件指定了具体的版本号和“任何后续版本”，你可以选择遵守该版本或者后续版本。如果软件没有指定具体的许可证版本号，你可以选择自由软件基金会发布的任何版本。

10、如果你希望将本软件的部分并于分发条件不同的其他自由软件，应对书面请求作者的许可。对于自由软件基金会拥有著作权的软件，写信给自由软件基金会。我们有时会例外处理。我们的处理此类事情是有两个目标：保持所有自由软件衍生作品的自由属性以及促进软件共享和重用。

## 免责声明

11、本软件免费许可，因此在适用法律范围内不提供品质保证。除非另有书面声明，本软件著作权人和/或其他作者按“原样”提供本软件，不提供任何形式的显示的或隐式的品质保证，包括但不限于经济价值和适合特定用途的保证。本软件的全部品质和性能风险均由你承担。如果本软件出现缺陷、你将承担所有必要服务、修复和更正的成本。

12、在任何情况下，除非适用的法律要求或者书面协议，任何版权方和/或任何按照上述条款修改或/和分发本软件的第三方都不对你的损失负责，包括任何一般的、特殊的、偶发的或者重大损失（包括但不限于因你或者第三方，或操作不当、或无法与其他软件错误协同造成的数据丢失，数据失真、失效），即使那些持有方或者其他人已被告知此类损失的可能性。

**条款和条件结束**

## 如何将上述条款应用于你的新程序

如果你开发了一个新程序，并且希望它最大限度地被公众所使用，最好的办法就是将其作为自由软件，使得每个人都可以按照本许可证分发和修改。

为此，最安全、最有效的办法是将如下的声明附在每个文件开头，以明确传达免责声明。每个文件应当最少包含一个“版权声明”和一个本许可证的完整声明。

    用一行标明程序的名称和作用。

    版权所有（C） 年份  作者姓名

    本程序是自由软件，你可以根据自由软件基金会发布的GNU通用许可证自由地再分发或者修改。本程序适用第2版或者后续版本（具体随你）。

    我们希望本程序有用，但是不提供任何保证，甚至不保证它的经济价值或者适合特定目的。具体细节参加GNU通过公共许可证。

    你应当随本程序收到了GNU通用公共许可证的副本，如果没有请致信自由软件基金会：51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA

同时提供你的电子邮件或者纸质邮件地址。

如果本程序是交互的，让它在交互模式启动前输出如下的简短声明：

    Gnomovision 第69版，版权所有（C）年份 作者姓名

    Gnomovision不提供任何品质保证，输入“show w”查看详情。本软件是自由软件，欢迎你根据许可条件再分发，输入“show c”查看详情。

假设的命令`show w`和`show c`用于显示通用公共许可证相应的内容。当然，你也可以使用`show w`和`show c`之外的其他命，甚至点击鼠标或者菜单项等——任何适合你程序的方式。

如有必要，你还应该得到你的雇主（如果你是一名程序员）或者学校（如果有的话）签署该本程序的放弃版权声明。如下例所示：

    Yoyodyne有限公司声明放弃James Hacker所写的“Gnomovision”（编译通过的程序）的版权权益。

    Ty Coon的签名 1989年4月1日

    副总裁 Ty Coon

本通用公共许可证不允许将你的程序合并到私有程序。如果你的程序是子程序库，而你可以考虑让私有程序链接它，使其更有用。如果你希望这么做，你可以使用GUN宽松通用许可证。

## APPENDIX C GNU通用公共许可证

第二版，1991年6月

版权所有(C) 1989，1991自由软件基金会

51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA

任何人都可以复制和发布本许可证完整副本，但不允许修改。

## 译者声明

This is an unofficial translation of the GNU General Public License into Chinese. It was not published by the Free Software Foundation, and does not legally state the distribution terms for software that uses the GNU GPL--only the original English text of the GNU GPL does that. However, we hope that this translation will help Chinese speakers understand the GNU GPL better.

本译文是GNU通用公共许可证的一份非官方中文翻译，并非自由软件基金会所发表，不适用于使用GNU通用公共许可证发布的软件的法律声明——只有GNU通用公共许可证英文原版才具有法律效力。不过我希望本翻译能够帮助中文读者更好地理解GNU通用公共许可证。

You may publish this translation, modified or unmodified, only under the terms at <https://www.gnu.org/licenses/translations.html>.

仅在遵循 <https://www.gnu.org/licenses/translations.html> 中的条款时，你才可以经过修改地或者不经过修改地发布本译文。

## 序言

大部分软件的许可证都是被设计为剥夺你分享和修改的自由。相反，GNU通用公共许可证的目的是保护你分享和修改自由软件的自由——确保软件对所有用户都是自由的。本通用公共许可证适用于自由软件基金会的大部分软件以及任何作者承诺使用该许可证的软件（自由软件基金会的其他一些软件受GNU宽松通用许可证的保护）。你也可以将本许可证用于你的程序。

自由软件，强调的是自由，而不是免费。本通用公共许可证的目的是保证你拥有分发自由软件的自由（如果你愿意还可以为此收费），确保你有收到源代码或者想要获得时拥有获得源代码的自由，确保你想要修改或者在新的自由软件中使用其中代码的自由，并且确保你有知情权。

为了保护你的权利，我们设置了一些限制以防止其他人否定你的权利或者要求你放弃你的权利。这些限制在你分发或者修改这些软件时会成为你的责任。

例如，你分发这类软件的副本，无论是免费的或者收费的，你必须授予接收者你拥有的所有权利。你必须保证他们也能收到或者能够获得源代码。并且你也要确保他们也知道他们的权利。

我们通过两步保护你的权利：(1) 授予软件著作权；(2) 赋予你合法复制、分发和修改软件的权利。

此外，为了保护每一位作者和我们自己，我们向每个人声明：自由软件是没有任何品质保证的。如果被其他人修改或者转发，我们希望接收者知道他们收到的不是原始版本，因此其他人引入的任何问题不会影响原作者的声誉。

最后，自由软件还不停地收到软件专利的威胁。我们希望避免自由软件分发者以个人名义获取专利，从而导致自由软件成为私有软件。为了避免这种事情发生，我们明确声明：任何专利必须许可给任何人自由使用或者完全不进行许可。

以下是复制、分发和修改的具体条款和条件。

## 复制、分发与修改条款和条件

0、本许可适用于任何版权持有人在他的程序或作品中声明以通用许可证条款发布的程序或作品。“程序”在下文中是指，任何程序或者作品，“程序的衍生作品”是指程序或者衍生作品包含该程序的全部或者部分，无论是逐字复制地或者经过修改的，或者是翻译成其他语言的。（下文中，翻译属于但不限于修改的范围）。每个被许可人均指“你”。

除复制、分发、修改之外的其他行为不在本许可范围内。运行软件的行为是不受约束的，软件的输出一般不在本许可范围内，除非它构成了本程序的衍生作品（单独通过运行本软件产生）。具体情况依程序用途而定。

1、如果你发布每个副本时，在明显的位置包含适当的版权声明和免责声明，包含本许可证的全部声明和免责声明，你就可以在任何介质上复制和原文分发你收到的软件的源代码。

你可以为你实际发送副本的实际行为收取费用，你也可以提供品质保证收取费用。

2、你可以通过修改本程序副本或者其中任意部分，从而构成衍生作品，并在满足条款1以及下列3点要求的前提下复制或者分发修改的作品。

  a）你必须在修改后的文件带有明显的声明，说明你修改的任何文件和日期。

  b）你必须将你发布或者发表的整个或者部分，或者基于本程序或者任意部分衍生的作品，全部免费地按照本许可证许可给所有第三方。

  c）如果修改后的软件在运行时通常以交互的方式读取命令，你必须在让程序进入交互模式时打印或者显示合适的版权声明和免责声明（或者，你也可以提供品质保证），并且告诉用户可以在本约束下分发本软件，告知用户如何查阅本许可证（例外：如果程序本来就是交互方式的但不打印声明，你的衍生作品也不需要打印声明）。

上述要求对修改后作品的整体有效。如果作品可以独立的部分不是从本软件衍生的，可以合理地将它们作为独立或者单独的作品，进行单独分发，本许可及其条款不适应于它们。但是，当你将它们与本程序的衍生作品一同发布时，分发的作品必须作为一个整体按照本许可证许可，本许可证的授权延伸到全部作品，而无论其任何部分是谁写的。

因此，本条款的目的不是声明或者争辩你创造的作品的全部权利，而是行使控制本程序衍生作品或者集体作品的分发权利。

另外，仅仅与本程序或者衍生作品一同存储或者通过同一个介质上分发的其他非本程序的衍生作品不在本许可证范围内。

3、在上述第1条和第2条约束下，你可以复制或者分发本程序（或根据第2条的衍生作品）的目标代码或者可执行格式分发本程序时，你必须满足下列要求：

a）根据上述第1条和第2条要求，附上完整的、机器可读的源代码，按照常用的软件交换媒介分发。或者

  b）附上至少3年有效期的书面报价，向任何第三方，收取不高于你因分发源代码的实际花费的费用。源代码是根据上述第1条和第2条要求机器可读的完整的源代码，通过常用的软件交换介质分发。或者

  c）附上你所收到的源代码的信息（该要求仅适用于非商业性分发，并且仅当你收到程序是目标代码或者可执行格式，同时还要满足本条款b项要求）。

  作品的源代码是修改作品的首选格式。对于一个可执行的作品，完整的源代码是指其所有模块的所有源代码、相关接口定义文件、编译和安装所需的脚本。然而，作为例外，分发的源代码不必包括任何通常随运行本软件的目标操作系统的主要组件（编译器、内核等）一同分发的（源代码或者二进制）文件，除非它们是本软件的一部分。

如果是通过指定访问位置的形式分发可执行文件或者目标代码，那么提供获取源代码副本相同地址也算分发源代码，即使不要求第三方在复制目标代码时复制源代码。

4、除本许可证许可之外，你不能复制、修改、再许可或者分发本程序。试图进行任何其他形式的复制、修改、再许可或者分发本程序都是无效的，并且本许可证授予你的权利自动终止。然而，只要符合本许可证条款，从你获得副本的其他人的权利仍然有效。

5、你没有签署本许可证，你也不必接受本许可证。而且，此外无人可以授权你修改本程序及其衍生作品。除非你接受本许可证，否则这些行为是被法律禁止的。然而，修改或者分发本软件（或基于本软件的任何作品），表明你接受本许可证复制、分发或者修改本软件或者基于本软件的条款和条件。

6、你每次再分发本程序（或本程序的衍生作品）时，接收者自动从原始权利人获得本许可，以复制、分发或者修改本软件。你不能对他们获得的权利引入任何限制。你也没有要求第三方遵循本许可的责任。

7、如果由于法庭裁决或者专利侵权或者其他原因（不限于专利），使得你面临与本许可证冲突的情况（无论由于法庭裁决、协议或者其他），这也不能成为你不遵守本许可证的理由。如果你不分发本程序，就能满足本许可证条款和其他相关要求，你就不要分发本软件。例如，某专利许可不允许直接或者间接从你获得副本的接受者免费再分发本软件，为了同时满足本许可证和它的要求，你的唯一做法就是不再分发本软件。

如果在特定情况下本条款的任何部分无效或者无法实施，本条款的其余部分仍然适用，并且本条款作为整体适用于其他情况。

本条款的目的不是怂恿你违反任何专利或者其他权利要求，或者与它们抗辩。本条款的目的纯粹是保护自由软件分发系统的完整性，即通过公共许可证来实现。通过一致地应用该分发系统，很多人已经向通过该系统分发的大量软件做出了慷慨的贡献；作者/贡献者也可以决定是否愿意通过其他渠道分发，被授权人无权干涉该决定。

本条款旨在彻底阐明本许可其他条款所带来的当然后果。

8、如果本程序的分发和/或使用收到一些国家专利或者著作权的限制，权利人可以在通过本许可证授权的软件中明确添加受限的地理范围，以排除那些受限的国家，因此分发仍然可以在其他国家进行。这种情况下，本许可将这些限制纳入许可范围内。

9、自由软件基金会可能不时发布通用公共许可证的修订版和/或新版本。此类新版本与当前版本精神上相似，但在描述细节上可能不同，以解决新问题或情况。

每个版本都有一个唯一的版本号。如果软件指定了具体的版本号和“任何后续版本”，你可以选择遵守该版本或者后续版本。如果软件没有指定具体的许可证版本号，你可以选择自由软件基金会发布的任何版本。

10、如果你希望将本软件的部分并于分发条件不同的其他自由软件，应对书面请求作者的许可。对于自由软件基金会拥有著作权的软件，写信给自由软件基金会。我们有时会例外处理。我们的处理此类事情是有两个目标：保持所有自由软件衍生作品的自由属性以及促进软件共享和重用。

## 免责声明

11、本软件免费许可，因此在适用法律范围内不提供品质保证。除非另有书面声明，本软件著作权人和/或其他作者按“原样”提供本软件，不提供任何形式的显示的或隐式的品质保证，包括但不限于经济价值和适合特定用途的保证。本软件的全部品质和性能风险均由你承担。如果本软件出现缺陷、你将承担所有必要服务、修复和更正的成本。

12、在任何情况下，除非适用的法律要求或者书面协议，任何版权方和/或任何按照上述条款修改或/和分发本软件的第三方都不对你的损失负责，包括任何一般的、特殊的、偶发的或者重大损失（包括但不限于因你或者第三方，或操作不当、或无法与其他软件错误协同造成的数据丢失，数据失真、失效），即使那些持有方或者其他人已被告知此类损失的可能性。

**条款和条件结束**

## 如何将上述条款应用于你的新程序

如果你开发了一个新程序，并且希望它最大限度地被公众所使用，最好的办法就是将其作为自由软件，使得每个人都可以按照本许可证分发和修改。

为此，最安全、最有效的办法是将如下的声明附在每个文件开头，以明确传达免责声明。每个文件应当最少包含一个“版权声明”和一个本许可证的完整声明。

    用一行标明程序的名称和作用。

    版权所有（C） 年份  作者姓名

    本程序是自由软件，你可以根据自由软件基金会发布的GNU通用许可证自由地再分发或者修改。本程序适用第2版或者后续版本（具体随你）。

    我们希望本程序有用，但是不提供任何保证，甚至不保证它的经济价值或者适合特定目的。具体细节参加GNU通过公共许可证。

    你应当随本程序收到了GNU通用公共许可证的副本，如果没有请致信自由软件基金会：51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA

同时提供你的电子邮件或者纸质邮件地址。

如果本程序是交互的，让它在交互模式启动前输出如下的简短声明：

    Gnomovision 第69版，版权所有（C）年份 作者姓名

    Gnomovision不提供任何品质保证，输入“show w”查看详情。本软件是自由软件，欢迎你根据许可条件再分发，输入“show c”查看详情。

假设的命令`show w`和`show c`用于显示通用公共许可证相应的内容。当然，你也可以使用`show w`和`show c`之外的其他命，甚至点击鼠标或者菜单项等——任何适合你程序的方式。

如有必要，你还应该得到你的雇主（如果你是一名程序员）或者学校（如果有的话）签署该本程序的放弃版权声明。如下例所示（你需要修改名字）：

    Yoyodyne有限公司声明放弃James Hacker所写的“Gnomovision”（编译通过的程序）的版权权益。

    Ty Coon的签名 1989年4月1日

    副总裁 Ty Coon

本通用公共许可证不允许将你的程序合并到私有程序。如果你的程序是子程序库，而你可以考虑让私有程序链接它，使其更有用。如果你希望这么做，你可以使用GUN宽松通用许可证。

- - -

翻译：赵振华 <zhao.zhenhua@gmail.com>

发布日期：2022年12月28日

地址：<https://github.com/zRich/gpl/blob/main/gplv2/gplv2.pdf>

如有修改建议欢迎发邮件或者到<https://github.com/zRich/gpl>讨论。

参考：

[简体中文译本] <https://www.gnu.org/licenses/old-licenses/gpl-2.0-translations.html>

## APPENDIX D GNU通用公共许可证

第3版，2007年6月29日

版权所有 (C) 2007年 自由软件基金会 <https://fsf.org/>。

任何人都可以复制和发布本许可证的完整副本，但不允许修改。

## 引言

GNU通用公共许可证是一份面向软件及其他类型作品的、著佐权许可证。

就多数软件而言，许可证被设计用于剥夺你分享和修改软件的自由。相反，GNU通用公共许可证力图保障你分享和修改某程序全部版本的权利——确保自由软件对其用户来说是自由的。我们——自由软件基金会——将GNU通用公共许可证用于我们的大多数软件，并为一些其他作品的作者效仿。你也可以将本许可证用于你的程序。

所谓自由软件，强调自由，而非免费。设计GNU通用公共许可证的目的在于确保你享有分发自由软件的自由（你可以为此服务收费），确保你可以在需要的时候获得cd这些软件的源代码，确保你可以修改这些软件或者在新的自由软件中复用其中某些片段，并且确保你在这方面享有知情权。

为了保护你的权利，我们设置了一些限制以防止其他人否定你的权利或者要求你放弃你的权利。这些限制在你分发或者修改这些软件时会成为你的责任。

例如，你分发这类软件的副本，无论是收费或者免费，你必须授予接收者你拥有的所有权利。你必须保证他们也能收到或者能够获得源代码。并且你也要确保他们也知道他们的权利。

采用GNU通用公共许可证的开发者通过两步保障你的权利：（1）声明软件的版权；（2）通过本许可证授予你合法地复制、分发和修改该软件的权利。

为了保护作者和开发者，GPL明确声明：自由软件并没有品质担保。为用户和作者双方着想，GPL要求修改版必须有修改标记，以免其问题被错误地归到先前版本的作者身上。

某些设备设计成拒绝用户安装、运行修改过的软件，但设备生产商不受此限制。这和我们保护用户享有修改软件的自由的宗旨存在根本性矛盾。这种系统化地滥用模式常常出现于个人用品领域，这恰恰是最不可接受的。因此，我们设计了这版GPL来禁止这类做法的产品。如果此类问题在其他领域大量出现，我们随时在GPL的后续版本中把规定扩展到相应领域，以保护用户的自由。

最后，每个程序都持续受到软件专利的威胁。政府不应该允许专利限制通用计算机软件的开发和应用，在做不到这点时，我们希望避免因专利的应用而使自由软件私有化的危险。就此，GPL保证专利不能使程序非自由化。

下文是关于复制、分发和修改的详细条款和条件。

## 条款和条件

### 0. 定义

“本许可证”指GNU通用公共许可证第3版。

“版权”也指适用于其他类型作品的类似版权的法律，如半导体掩模。

“本程序”指任何受本许可证保护的任何有版权的作品。每位被授权人称作“你”。“被授权人”和“接收者”可以是个人或组织。

“修改”一个作品指需要版权授权才能复制该作品以及对作品全部或部分的改编行为，不同于制作完全相同的副本。所产生的作品称作上一作品的“修改版”，或“基于”上一作品衍生作品。

“涵盖的作品”指未修改的程序或其衍生作品。

“传播”作品指那些未经授权就会在适用版权法律下构成直接或间接侵权的任何行为，但在计算机上运行和修改私有副本除外。传播包括复制、分发（无论修改与否）、向公众公开，以及在某些国家的其他行为。

“传递”作品指让他方能够制作或者接收副本的行为。仅仅通过计算机网络与用户交互，但没有传输副本，则不算传递。

显示“适当的法律声明”的交互式用户界面应包括一个方便和醒目的可视化方式显示：（1）适当的版权声明；（2）告知用户没有品质担保（提供了品质担保的情况除外），被授权人可以在本许可证约束下传递该作品，及查看本许可证副本的途径。如果该界面是以命令列表或者选项方式显示，如菜单，在列表项显示上述法律声明，也是符合本要求。

### 1. 源代码

作品的“源代码”指其可修改的首选形式，目标代码指所有其他形式。

“标准接口”指标准化组织定义的官方标准中的接口，或针为某种编程语言设定的为开发者广泛使用的接口。

可执行作品中的“系统库”不是指整个程序，而是包含任何这类内容的部分：（a）以通常形式和主要组件打包到一起却并非后者的一部分，且（b）仅为和主要组件一起使该作品可用或实现某些已有公开实现源代码的接口。“主要组件”在这里指可执行该作品运行依赖的操作系统（如果存在）的必要组件（内核、窗口系统等），或者生成该作品的编译器，或运行所需的目标代码解释器。

目标代码作品的“相应源代码”指所有修改该作品及生成、安装、运行（对可执行作品而言）目标代码所需的所有源代码，或者修改作品的所有源代码，包括控制上述行为的脚本。可是，其中不包括系统库、通用工具、不需要修改就可以直接用于支持上述行为但不是该作品一部分的、通常可得的自由软件。例如，相应的源代码包含与作品源文件相关的接口定义，以及共享库和该作品专门依赖的动态链接子程序的源代码。这里的依赖体现为密切的数据交换或者该子程序和作品其他部分的控制流切换。

相应的源代码不必包含那些用户可以通过源代码其他部分自动生成的内容。

源代码形式作品的相应源代码即该作品本身。

### 2. 基本授权

本许可证的所有授权都是对本程序的版权而言的，并且当所述条件都满足时不可撤销。本许可证明确授权你不受限制地运行本程序的未修改版本。运行涵盖的作品的输出结果，仅当其内容构成一个涵盖的作品时，才受本许可证约束。如版权法授权一样，本许可证承认你合理使用权或其他同等权利。

只要你获得的许可仍有效，你就可以制作、运行和传播不是你传递的涵盖的作品。在你遵守本许可证中关于转发你拥有版权的材料的条款时，你可以向他人传递涵盖的的作品，以让对方单独为你定制修改，或者向你提供运行这些作品的工具。那些为你制作或运行这些涵盖的作品的人，必须在你的指引和控制下，仅代表你工作，即禁止他们在双方关系之外制作任何你提供的受版权保护材料的副本。

仅当满足后文所述条件时，其他各种情况下的传递才是被允许的。不允许再授权，而第10条的存在也使再授权变得没有必要。

### 3. 保护用户的合法权益免受反破解法限制

为了履行1996年12月20日通过的WIPO版权条约第11章规定的义务，法律规定了禁止或规避措施的条款，所有涵盖的作品不应该被视为规避这些法律条款的技术手段的一部分。

如果你传递一个涵盖的作品，即表明你放弃禁止技术规避措施的法律权利，行使本许可证所授予权利可以实现规避，同时，你也放弃禁止技术规避措施相关的法律赋予你或者第三方限制运行或者修改本作品的权利。

### 4. 传递原始副本

你可以通过任何媒介传递你接收到的本程序的完整源代码副本，但必须做到：为每一个副本明显而恰当地发布版权声明；完整地保留关于本许可及按第7条加入的非许可性条款；完整地保留所有免责声明；给接收者附上一份本许可证的副本。

你可以免费或收任何费用传递，也可以选择提供技术支持或品质担保以收取费用。

### 5. 传递经过修改的源代码

你可以以第4条规定的源代码形式传递基于本程序的作品或修改的内容，但必须满足以下要求：

- a）该作品必须带有明显的修改声明及相应的日期。

- b）该作品必须带有明显的声明，指明其在本许可证及任何符合第7条的附加条款下发布。这个要求修正了第4条关于“完整保留所有声明”的内容。

- c）你必须按照本许可证将该作品整体许可给任何得到副本的人。本许可证与符合第7条的附加条款共同适用于整个作品，以及作品的任何一部分，不管它们是如何组建的。本许可证不允许以其他形式许可本作品，但不会使你已经单独收到的其他授权无效。

- d) 如果该作品有交互式用户界面，则其必须显示适当的法律声明。然而，当该程序有交互式用户界面却不显示适当的法律声明时，你的作品也无需使其显示。

一个涵盖的作品与其他单独且独立的作品组成一个组合，其中的单独作品既不是涵盖的作品的自然延伸，也不是为了与涵盖的作品组成更大程序而与被保护作品存储或者分发介质上，并且这种组合和组合后的版权不会限制单独作品的授权，则这种组合称为“组合体”。

### 6. 以非源代码形式传递

你可以以第4条和第5条所述那样以目标代码形式传递涵盖的作品，同时在本许证可规范下以如下方式之一传递机器可读的对应源代码：

- a) 通过物理产品（包括物理分发媒介）传递或者嵌入目标代码时，通过常用于软件交换的耐用型物理媒介传递相应的源代码。

- b) 通过物理产品（包括物理分发媒介）时，附随具有至少3年有效期的书面承诺，并且有效期涵盖提供的备件或客户支持，以授予任何目标代码的持有者：（1）获得产品中全部涵盖的软件的相应源代码的副本，副本通过常用于软件交换的耐用型物理媒介提供，且收费不超过其合理的传递成本；或者（2）通过网络免费获得相应源代码的途径。

- c) 单独传递目标代码的副本时，伴以提供源代码的书面承诺。本选项仅在偶尔并且非商业情况下，同时你收到也是第6条b项所述的目标代码的情况下可用。

- d) 通过在指定地址获取目标代码（无论是否收费）的形式传递目标代码时，对同一地址以同样的方式提供相应源代码同等访问权限，并不得额外收费。你不必要求接收者在复制目标代码的同时复制源代码。如果提供获取目标代码的地址为网络服务器，相应的源代码可以提供在另一个支持相同复制功能的服务器上（由你或者第三方运营），不过你要在目标代码处指出相应源代码的确切路径。不管你用什么源代码服务器，你有义务要确保持续可用以满足这些要求。

- e) 通过点对点传输传递目标代码时，告知其他节点目标代码和源代码在何处，并以第6条d项形式向大众免费提供。

如果目标代码的可分离部分，其源代码作为系统库在相应的源代码之外，则不需要被包括在传送目标代码作品中。

“用户产品”指（1）“消费品”，即个人、家庭或日常用途的个人的有形财产；或者（2）面向家庭设计或销售的物品。在判断一款产品是否消费品时，对于有争议的案例，应尽量扩大覆盖范围。就特定用户接收到特定产品而言，“正常使用”指对此类产品的典型的或一般使用，与该用户的身份，该用户对该产品的实际用法，以及该产品的预期用法无关。无论产品是否实质上具有商业上的，工业上的，及非面向消费者的用法，它都视为消费品，除非以上用法代表了它唯一的重要使用模式。

用户产品的“安装信息”，指基于修改过的源代码来安装运行该产品中的涵盖的作品的修改版所需的方法、流程、授权秘钥及其他信息。这些信息必须足以保证修改过的目标代码不会仅仅因为被修改过而不能继续工作。

如果你根据本条规定，传递一个目标代码作品到用户产品中或与用户产品一起，或专门用于特定用户产品，并且传送行为成为交易的一部分，使得用户产品永久或在特定期限内暂时转移给接收者（无论交易的特征如何），必须通过安装信息附上根据本条传递的相应来源。但如果你和第三方都没有在用户产品中保留安装修改目标代码的能力时，可以不遵守该要求（例如，作品有已安装在 ROM 中）。

提供安装信息的要求不包括对接受者修改或者安装、或者已经被修改或者安装的用户产品继续提供支持服务、品质担保或者升级。当修改本身对网络运行有重大负面影响，或违反网络通信规则和协议时，可能会被拒绝访问网络。

根据本条规定发布的源代码及安装信息，必须以公共的文档格式（并且以源代码形式实现对公众可用）存在，同时不得对解压、阅读和复制设置任何密码或秘钥。

### 7. 附加条款

“附加许可”用于补充本许可证的条款，以允许一或者多个例外情况。如果附加许可适用于整个程序且在适用的法律范围内有效，就应该视为本许可证的一部分。如果附加许可只适用于程序的某部分，则该部分受此附加许可约束，而其他部分受不适用附加许可之外的条款约束。

当你传递本程序的副本时，你可以选择性从副本中删除任何附加许可。（在某些情况下，当你修改作品时，附加许可可能已经写明要求你删除该附加许可。）对于你传递的作品，如果你拥有或者可以适当地授权，你也可以在作品的材料中添加附加许可。

尽管本许可证还有的其他条款，对于你添加到涵盖的作品中的材料，你可以对本许可证（如果你获得该材料版权持有人的授权）添加如下补充条款：

- a) 以第15条、第16条之外的方式，拒绝提供品质担保或缩小责任范围。或者

- b) 要求在此材料中或在法律声明中包含特定的合理法律声明或作者信息。或者

- c) 禁止对该原始材料不当描述，或要求用不同与原始版本的方式对该材料修改版本合理标示。或者

- d) 限制公开使用授权人或者该材料作者姓名。或者

- e) 拒绝使用在商标法下使用商号、商标及服务标识。

- f) 任何传递该材料（或其修改版）者，如果对接收者提供契约性责任许诺，需要为授权人或者该材料作者承担赔偿责任，因为任何契约假设责任都造成授权人或者作者承担。

此外的非授权附加条款都被视作第10条所说的“进一步的限制”。如果你接收到的程序或程序的任何部分，包含受本许可约束的声明，却补充了这种进一步的限制条款，你可以删除它们。如果某许可文件包含进一步的限制条款，但允许通过本许可证再授权或传递，你可以添加受该许可文件保护的材料，同时提供其他的再许可或者传递的进一步限制条款。

如果你根据本条规定向涵盖的作品添加了新的条款，你必须在相关的源文件中加入附加条款的对应的声明，或者指明在哪里可以找到适用的条款。

附加条款，不管是授权的还是非授权的，可以以独立的书面许可出现，也可以声明为例外情况，两种做法都可以实现上述要求。

### 8. 终止

除非在本许可证明确授权下，你不得传播或修改涵盖的作品。其他任何传播或修改涵盖的作品的做法都是无效的，你通过本许可证获得的权利（包括第11条第3段中授予的专利权限）也自动终止。

然而，当你不再违反本许可证时，你从特定版权持有人处获得的许可可以：（1）暂时恢复，直到版权持有人明确终止；（2）永久恢复，如果版权持有人没能在60天内以合理的方式指出你的侵权行为。

再者，如果你第一次收到了特定版权持有人关于你违反本许可证（对任意作品）的通知，且在收到通知后30天内改正，那你可以继续享此有许可。

当你享有的权利如本条所述被中止时，根据本许可证从你这里获得许可的第三方的权利不会因此中止。在你的权利恢复之前，你没有资格凭第10条获得同一材料的许可。

### 9. 持有副本不需要接受

你不必为接收或运行本程序而接受本许可。类似地，仅仅因点对点传输接收到副本引发的对涵盖的作品的辅助性传播，并不要求接受本许可证。但是，除本许可证外没有什么可以授权你传播或修改任何涵盖的作品。如果你不接受本许可证，这些行为就侵犯了著作权。因此，一旦修改和传播一个涵盖的作品，就表明你接受了本许可证。

### 10. 对下游接收者的自动授权

每当你传递一个涵盖的作品，其接收者自动获得来自原始授权人的许可，依照本许可证可以运行、修改和传播此作品。你没有要求第三方遵守本许可证的责任。

“实体交易”指转移一个组织的控制权或全部资产、或拆分或合并组织的交易。如果实体交易导致一个涵盖的作品的传播，则交易中各收到作品副本方，都有获得前利益相关者享有或可以如前段所述提供的对该作品的任何授权，以及从前利益相关者处获得并拥有相应的源代码的权利，如果前利益相关者享有或可以通过合理的努力获得此源代码。

你不可以对本许可证所授权利的行使施以进一步的限制。例如，你不可以索要许可费或版税，或就行使本许可证所授予的权利征收其他费用；你也不能发起诉讼（包括交互诉讼和反诉），宣称制作、使用、零售、批发、引进本程序或其部分的行为侵犯了任何专利声明。

### 11. 专利

“贡献者”指通过本许可证对本程序或其衍生作品进行许可的版权持有人。贡献者许可的作品称为“贡献者版本”。

贡献者的“必要专利声明”是由贡献者拥有或控制所有专利声明，无论是已经获得还是将要获得的，通过本许可证授权本来侵犯行为，例如制作、使用或销售其贡献者版本，但不包括仅对贡献者版本进一步修改的行为。根据本定义，“控制”包括符合本许可证要求的专利再许可的权利。

每位贡献者皆其就拥有的实际专利权限，授予你一份全球有效的免版费的非独占专利许可，以制作、使用、零售、批发、引进，及运行、修改、传播其贡献者版的内容。

在以下3段中，“专利授权”指通过任何方式明确表达的不行使专利权（如对使用专利的明确许可和不起诉专利侵权的契约）的协议或承诺。对某方“授予”专利权限，指这种不对其强制行使专利权的协议或承诺。

如果你传递的涵盖的作品时，明知需要某专利授权，而其相应的源代码并不是任何人都能根据本许可从网上或其他地方免费获得，那你必须（1）提供相应的源代码；或者（2）放弃从该程序的专利授权中的权益；或者（3）以某种和本许可相一致的方式将专利许可扩展到下游接收者。“明知需要”指你实际上知道若没有专利授权，你在某国家传递涵盖的作品的行为，或者接收者在某国家使用涵盖的作品的行为，会侵犯一项或多项该国认定的专利，而这些专利你有理由相信它们的有效性。

如果根据单一交易或安排，抑或与之相关，你传递某涵盖的作品，或通过促成其转手以实现传播，并且该作品的接收方被授予专利权限，以使其可以使用、传播、修改或转发该作品的特定副本，则此等专利授权将自动延伸及每一个收到该作品或其衍生作品的接受者。

如果某专利在其涵盖范围内，不包含本许可证专门授予的一项或多项权利，禁止行使它们或以不行使它们为前提，则该专利是“歧视性”的。如果你和软件发布行业的第三方有合作，合作要求你就转发涵盖的作品的情况向其付费，并授予作品接收方歧视性专利，而且该专利（a）与你转发的副本（或在此基础上制作的副本）有关，或针对包含该涵盖的作品的产品或联合作品，你不得转发本程序，除非参加此项合作或取得该专利授权早于2007年3月28日。

本许可证的任何部分不应被解释成在排斥或限制任何暗含的许可，或者其他在适用专利法下对抗侵权的措施。

### 12. 不得牺牲他人的自由

即便你面临与本许可证条款冲突的条件（来自于法庭要求、协议或其他），也不能成为你违反本许可证的理由。倘若你不能在传递涵盖的作品时同时满足本许可证和其他相关文件的要求，那么你就不要传递本程序。例如，你为了遵循某些要求，你必须向传递对象的接收者收取版税，唯一能同时满足它和本许可证要求的做法便是不传递本程序。

### 13. 与GNU Affero通用公共许可证一起使用

尽管本许可证中已存在其他条款，你可以将任何涵盖的作品与以GNU Affero通用公共许可证保护的作品关联或组合成一个联合作品，并转发。本许可证对其中的涵盖的作品部分仍然有效，但GNU Affero通用公共许可证第13条的关于网络交互的特别要求适用于整个联合作品。

### 14. 本许可证的修订版

自由软件基金会可能会不定时发布GNU通用公共许可证的修订版或新版。新版将秉承当前版本的精神，但在细节上描述不尽相同，以解决新的问题或事项。

每一版都会有不同的版本号，如果本程序指定其使用的是某个GNU通用公共许可证的版本“或后续版本”，你可以选择遵守该版本或者任何后续版本的条款。如果本程序没有指定许可证的版本，你可以选用自由软件基金会发布的GNU通用公共许可证任何版本。

如果本程序指明代理可以决定使用GNU通用公共许可证哪个版本，则该代理的公开声明的版本为授权你永久使用的版本。

后续版本可能会给予你额外或不同的许可。但是，任何作者或版权持有人的义务，不会因为你选择新后续版本而增加。

### 15. 免责声明

本程序在适用法律范围内不提供品质担保。除非另作书面声明，版权持有人及其他程序提供者“概”不提供任何显式或隐式的品质担保，品质担保所指包括而不仅限于有经济价值和适合特定用途的保证。全部风险，如程序的质量和性能问题，皆由你承担。若程序出现缺陷，你将承担所有必要的修复和更正服务的费用。

### 16. 责任限制

除非适用法律或书面协议要求，任何版权持有人或本程序按本许可证可能存在的第三方修改和再发布者，都不对你的损失负有责任，包括由于使用或者不能使用本程序造成的任何一般的、特殊的、偶发的或重大的损失（包括而不限于数据丢失、数据失真、你或第三方的后续损失、其他程序无法与本程序协同运作），即使有人声称会对此负责。

### 17. 第15条和第16条的解释

如果上述免责声明和责任限制不为地方法律所支持，上诉法庭应采用与之最接近的关于放弃本程序相关民事责任的地方法律，除非本程序附带收费的品质担保或责任许诺。

条款和适用条件结束

## 如何将上述条款应用到你的程序

如果你开发了一个新程序，并且希望它最大限度地被公众所使用，最好的办法就是将其作为自由软件，使得每个人都可以按照本许可证分发和修改。

为此，最安全、最有效的办法是将如下的声明附在每个文件开头，以明确传达免责声明。每个文件应当最少包含一个“版权声明”和一个本许可证的完整声明。

    <用一行标明程序的名称和作用。 >

    版权所有 (C) <年份>  <作者姓名>

    本程序是自由软件，你可以根据自由软件基金会发布的GNU通用许可证自由地再分发或者修改。本程序适用第3版或者后续版本（具体随你）。

    我们希望本程序有用，但是不提供任何保证，甚至不保证它的经济价值或者适合特定目的。具体细节参加GNU通过公共许可证。

    你应当随本程序收到了GNU通用公共许可证的副本，如果没有，请参阅<https://www.gnu.org/licenses/>。

同时提供你的电子邮件或者纸质邮件地址。

如果本程序是交互的，使其在交互模式启动前输出如下的简短声明：

    <程序> 版权所有 (C) <年份>  <作者姓名>

    本程序不提供任何品质保证，输入“show w”查看详情。
    本软件是自由软件，欢迎你根据许可条件再分发，输入“show c”查看详情。

假设的命令`show w` 和 `show c` 用于显示通用公共许可证相应的内容。当然，你也可以使用`show w` 和 `show c` 之外的其他命令，对于图形界面程序，你可以使用“关于”对话框。

如果需要，你还应该得到你的雇主（如果你是一名程序员）或者学校（如果有的话）签署该本程序的放弃版权声明。关于如何应用及遵循GNU通用公共授权许可证的详细信息，请查看  <https://www.gnu.org/licenses/>。

本通用公共许可证不允许将你的程序合并到私有程序。如果你的程序是子程序库，而你可以考虑让私有程序链接它，使其更有用。如果你希望这么做，你可以使用GUN宽松通用许可证，但是首先，请阅读 <https://www.gnu.org/licenses/why-not-lgpl.html>。

## APPENDIX E: GNU AFFERO GENERAL PUBLIC LICENSE

## 附录#： GNU Affero 通用公共许可证

Version 3, 19 November 2007

第3版, 2017年11月19日

Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>

版权所有 (C) 2007年 自由软件基金会 <https://fsf.org/>。

任何人都可以复制和发布本许可证的完整副本，但不允许修改。

## Preamble

## 引言

The GNU Affero General Public License is a free, copyleft license
for software and other kinds of works, specifically designed to ensure
cooperation with the community in the case of network server software.

GNU Affero通用公共许可证是一个面向软件和其他类型作品自由的、著佐权许可证，专门针对网络服务软件，确保社区合作而设计。

The licenses for most software and other practical works are
designed to take away your freedom to share and change the works.  By
contrast, our General Public Licenses are intended to guarantee your
freedom to share and change all versions of a program--to make sure it
remains free software for all its users.

就多数软件而言，许可证被设计用于剥夺你分享和修改软件的自由。相反，通用公共许可证力图保障你分享和修改某程序全部版本的权利——确保自由软件对其用户来说是自由的。我们——自由软件基金会——将GNU通用公共许可证用于我们的大多数软件，并为一些其他作品的作者效仿。你也可以将本许可证用于你的程序。

When we speak of free software, we are referring to freedom, not
price.  Our General Public Licenses are designed to make sure that you
have the freedom to distribute copies of free software (and charge for
them if you wish), that you receive source code or can get it if you
want it, that you can change the software or use pieces of it in new
free programs, and that you know you can do these things.

所谓自由软件，强调自由，而非免费。设计通用公共许可证的目的在于确保你享有分发自由软件的自由（你可以为此服务收费），确保你可以在需要的时候获得这些软件的源代码，确保你可以修改这些软件或者在新的自由软件中复用其中某些片段，并且确保你在这方面享有知情权。

Developers that use our General Public Licenses protect your rights
with two steps: (1) assert copyright on the software, and (2) offer
you this License which gives you legal permission to copy, distribute
and/or modify the software.

采用我们通用公共许可证的开发者通过两步保障你的权利：（1）声明软件的版权；（2）通过本许可证授予你合法地复制、分发和修改该软件的权利。

A secondary benefit of defending all users' freedom is that
improvements made in alternate versions of the program, if they
receive widespread use, become available for other developers to
incorporate.  Many developers of free software are heartened and
encouraged by the resulting cooperation.  However, in the case of
software used on network servers, this result may fail to come about.
The GNU General Public License permits making a modified version and
letting the public access it on a server without ever releasing its
source code to the public.

捍卫所有用户自由的次要好处是如果在软件替代版本在的改进被广泛实用，其他开发者也可以采用它们。很多自由软件的开发者对产生的合作感到振奋和受到鼓舞。然而，对于网络服务器上使用的软件，这种结果可能不会出现。GNU通用公共许可证允许在服务器上提供一个公众可以访问的修改版，而不需要向公众提供修改版的源代码。

The GNU Affero General Public License is designed specifically to
ensure that, in such cases, the modified source code becomes available
to the community.  It requires the operator of a network server to
provide the source code of the modified version running there to the
users of that server.  Therefore, public use of a modified version, on
a publicly accessible server, gives the public access to the source
code of the modified version.

GNU Affero通用公共许可证针对这种情况设计，让修改后的代码仍然能被社区使用。这要求网络服务器的运营商提供在服务器上为用户运行的修改版的源代码。
因此，公众使用的修补版，在一个公众可以访问的服务器上，公众可以获得修改版的源代码。

An older license, called the Affero General Public License and
published by Affero, was designed to accomplish similar goals.  This is
a different license, not a version of the Affero GPL, but Affero has
released a new version of the Affero GPL which permits relicensing under
this license.

Affero发布的一个称为Affero通用公共许可证的旧许可证，也为实现类似的目的。那个许可证不是GNU Affero通用公共许可证的版本，但是Affero已经发布了新版本，允许在该许可证下重新许可。

The precise terms and conditions for copying, distribution and
modification follow.

下文是关于复制、分发和修改的详细条款和条件。

## Terms and Conditions

## 条款和条件

### 0. Definitions

### 0. 定义

``This License`` refers to version 3 of the GNU Affero General Public License.

“本许可证”指GNU Affero通用公共许可证第3版。

``Copyright`` also means copyright-like laws that apply to other kinds of
works, such as semiconductor masks.

“版权”也指适用于其他类型作品的类似版权的法律，如半导体掩模。

``The Program`` refers to any copyrightable work licensed under this
License.  Each licensee is addressed as ``you``.  ``Licensees`` and
``recipients`` may be individuals or organizations.

“本程序”指任何受本许可证保护的任何有版权的作品。每位被授权人称作“你”。“被授权人”和“接收者”可以是个人或组织。

To ``modify`` a work means to copy from or adapt all or part of the work
in a fashion requiring copyright permission, other than the making of an
exact copy.  The resulting work is called a ``modified version`` of the
earlier work or a work ``based on`` the earlier work.

“修改”一个作品指需要版权授权才能复制该作品以及对作品全部或部分的改编行为，不同于制作完全相同的副本。所产生的作品称作上一作品的“修改版”，或“基于”上一作品衍生作品。

A ``covered work`` means either the unmodified Program or a work based
on the Program.

“涵盖的作品”指未修改的程序或其衍生作品。

To ``propagate`` a work means to do anything with it that, without
permission, would make you directly or secondarily liable for
infringement under applicable copyright law, except executing it on a
computer or modifying a private copy.  Propagation includes copying,
distribution (with or without modification), making available to the
public, and in some countries other activities as well.

“传播”作品指那些未经授权就会在适用版权法律下构成直接或间接侵权的任何行为，但在计算机上运行和修改私有副本除外。传播包括复制、分发（无论修改与否）、向公众公开，以及在某些国家的其他行为。

To ``convey`` a work means any kind of propagation that enables other
parties to make or receive copies.  Mere interaction with a user through
a computer network, with no transfer of a copy, is not conveying.

“传递”作品指让他方能够制作或者接收副本的行为。仅仅通过计算机网络与用户交互，但没有传输副本，则不算传递。

An interactive user interface displays ``Appropriate Legal Notices``
to the extent that it includes a convenient and prominently visible
feature that (1) displays an appropriate copyright notice, and (2)
tells the user that there is no warranty for the work (except to the
extent that warranties are provided), that licensees may convey the
work under this License, and how to view a copy of this License.  If
the interface presents a list of user commands or options, such as a
menu, a prominent item in the list meets this criterion.

显示“适当的法律声明”的交互式用户界面应包括一个方便和醒目的可视化方式显示：（1）适当的版权声明；（2）告知用户没有品质担保（提供了品质担保的情况除外），被授权人可以在本许可证约束下传递该作品，及查看本许可证副本的途径。如果该界面是以命令列表或者选项方式显示，如菜单，在列表项显示上述法律声明，也是符合本要求。

### 1. Source Code

### 1. 源代码

The ``source code`` for a work means the preferred form of the work
for making modifications to it.  ``Object code`` means any non-source
form of a work.

作品的“源代码”指其可修改的首选形式，目标代码指所有其他形式。

A ``Standard Interface`` means an interface that either is an official
standard defined by a recognized standards body, or, in the case of
interfaces specified for a particular programming language, one that
is widely used among developers working in that language.

“标准接口”指标准化组织定义的官方标准中的接口，或针为某种编程语言设定的为开发者广泛使用的接口。

The ``System Libraries`` of an executable work include anything, other
than the work as a whole, that (a) is included in the normal form of
packaging a Major Component, but which is not part of that Major
Component, and (b) serves only to enable use of the work with that
Major Component, or to implement a Standard Interface for which an
implementation is available to the public in source code form.  A
``Major Component``, in this context, means a major essential component
(kernel, window system, and so on) of the specific operating system
(if any) on which the executable work runs, or a compiler used to
produce the work, or an object code interpreter used to run it.

可执行作品中的“系统库”不是指整个程序，而是包含任何这类内容的部分：（a）以通常形式和主要组件打包到一起却并非后者的一部分，且（b）仅为和主要组件一起使该作品可用或实现某些已有公开实现源代码的接口。“主要组件”在这里指可执行该作品运行依赖的操作系统（如果存在）的必要组件（内核、窗口系统等），或者生成该作品的编译器，或运行所需的目标代码解释器。

The ``Corresponding Source`` for a work in object code form means all
the source code needed to generate, install, and (for an executable
work) run the object code and to modify the work, including scripts to
control those activities.  However, it does not include the work's
System Libraries, or general-purpose tools or generally available free
programs which are used unmodified in performing those activities but
which are not part of the work.  For example, Corresponding Source
includes interface definition files associated with source files for
the work, and the source code for shared libraries and dynamically
linked subprograms that the work is specifically designed to require,
such as by intimate data communication or control flow between those
subprograms and other parts of the work.

目标代码作品的“相应源代码”指所有修改该作品及生成、安装、运行（对可执行作品而言）目标代码所需的所有源代码，或者修改作品的所有源代码，包括控制上述行为的脚本。可是，其中不包括系统库、通用工具、不需要修改就可以直接用于支持上述行为但不是该作品一部分的、通常可得的自由软件。例如，相应的源代码包含与作品源文件相关的接口定义，以及共享库和该作品专门依赖的动态链接子程序的源代码。这里的依赖体现为密切的数据交换或者该子程序和作品其他部分的控制流切换。

The Corresponding Source need not include anything that users
can regenerate automatically from other parts of the Corresponding
Source.

相应的源代码不必包含那些用户可以通过源代码其他部分自动生成的内容。

The Corresponding Source for a work in source code form is that
same work.

源代码形式作品的相应源代码即该作品本身。

### 2. Basic Permissions

### 2. 基本授权

All rights granted under this License are granted for the term of
copyright on the Program, and are irrevocable provided the stated
conditions are met.  This License explicitly affirms your unlimited
permission to run the unmodified Program.  The output from running a
covered work is covered by this License only if the output, given its
content, constitutes a covered work.  This License acknowledges your
rights of fair use or other equivalent, as provided by copyright law.

本许可证的所有授权都是对本程序的版权而言的，并且当所述条件都满足时不可撤销。本许可证明确授权你不受限制地运行本程序的未修改版本。运行涵盖的作品的输出结果，仅当其内容构成一个涵盖的作品时，才受本许可证约束。如版权法授权一样，本许可证承认你合理使用权或其他同等权利。

You may make, run and propagate covered works that you do not
convey, without conditions so long as your license otherwise remains
in force.  You may convey covered works to others for the sole purpose
of having them make modifications exclusively for you, or provide you
with facilities for running those works, provided that you comply with
the terms of this License in conveying all material for which you do
not control copyright.  Those thus making or running the covered works
for you must do so exclusively on your behalf, under your direction
and control, on terms that prohibit them from making any copies of
your copyrighted material outside their relationship with you.

只要你获得的许可仍有效，你就可以制作、运行和传播不是你传递的涵盖的作品。在你遵守本许可证中关于转发你拥有版权的材料的条款时，你可以向他人传递涵盖的的作品，以让对方单独为你定制修改，或者向你提供运行这些作品的工具。那些为你制作或运行这些涵盖的作品的人，必须在你的指引和控制下，仅代表你工作，即禁止他们在双方关系之外制作任何你提供的受版权保护材料的副本。

Conveying under any other circumstances is permitted solely under
the conditions stated below.  Sublicensing is not allowed; section 10
makes it unnecessary.

仅当满足后文所述条件时，其他各种情况下的传递才是被允许的。不允许再授权，而第10条的存在也使再授权变得没有必要。

### 3. Protecting Users' Legal Rights From Anti-Circumvention Law

### 3. 保护用户的合法权益免受反破解法限制

No covered work shall be deemed part of an effective technological
measure under any applicable law fulfilling obligations under article
11 of the WIPO copyright treaty adopted on 20 December 1996, or
similar laws prohibiting or restricting circumvention of such
measures.

为了履行1996年12月20日通过的WIPO版权条约第11章规定的义务，法律规定了禁止或规避措施的条款，所有涵盖的作品不应该被视为规避这些法律条款的技术手段的一部分。

When you convey a covered work, you waive any legal power to forbid
circumvention of technological measures to the extent such circumvention
is effected by exercising rights under this License with respect to
the covered work, and you disclaim any intention to limit operation or
modification of the work as a means of enforcing, against the work's
users, your or third parties' legal rights to forbid circumvention of
technological measures.

如果你传递一个涵盖的作品，即表明你放弃禁止技术规避措施的法律权利，行使本许可证所授予权利可以实现规避，同时，你也放弃禁止技术规避措施相关的法律赋予你或者第三方限制运行或者修改本作品的权利。

### 4. Conveying Verbatim Copies

### 4. 传递原始副本

You may convey verbatim copies of the Program's source code as you
receive it, in any medium, provided that you conspicuously and
appropriately publish on each copy an appropriate copyright notice;
keep intact all notices stating that this License and any
non-permissive terms added in accord with section 7 apply to the code;
keep intact all notices of the absence of any warranty; and give all
recipients a copy of this License along with the Program.

你可以通过任何媒介传递你接收到的本程序的完整源代码副本，但必须做到：为每一个副本明显而恰当地发布版权声明；完整地保留关于本许可及按第7条加入的非许可性条款；完整地保留所有免责声明；给接收者附上一份本许可证的副本。

You may charge any price or no price for each copy that you convey,
and you may offer support or warranty protection for a fee.

你可以免费或收任何费用传递，也可以选择提供技术支持或品质担保以收取费用。

### 5. Conveying Modified Source Versions

### 5. 传递经过修改的源代码

You may convey a work based on the Program, or the modifications to
produce it from the Program, in the form of source code under the
terms of section 4, provided that you also meet all of these conditions:

你可以以第4条规定的源代码形式传递基于本程序的作品或修改的内容，但必须满足以下要求：
  
- a) The work must carry prominent notices stating that you modified it, and giving a relevant date.

- a) 该作品必须带有明显的修改声明及相应的日期。
  
- b)  The work must carry prominent notices stating that it is released under this License and any conditions added under section 7.  This requirement modifies the requirement in section 4 to ``keep intact all notices``.

- b) 该作品必须带有明显的声明，指明其在本许可证及任何符合第7条的附加条款下发布。这个要求修正了第4条关于“完整保留所有声明”的内容。
  
- c) You must license the entire work, as a whole, under this
  License to anyone who comes into possession of a copy.  This
  License will therefore apply, along with any applicable section 7
  additional terms, to the whole of the work, and all its parts,
  regardless of how they are packaged.  This License gives no
  permission to license the work in any other way, but it does not
  invalidate such permission if you have separately received it.

- c) 你必须按照本许可证将该作品整体许可给任何得到副本的人。本许可证与符合第7条的附加条款共同适用于整个作品，以及作品的任何一部分，不管它们是如何组建的。本许可证不允许以其他形式许可本作品，但不会使你已经单独收到的其他授权无效。

- d) If the work has interactive user interfaces, each must display
  Appropriate Legal Notices; however, if the Program has interactive
  interfaces that do not display Appropriate Legal Notices, your
  work need not make them do so.

- d) 如果该作品有交互式用户界面，则其必须显示适当的法律声明。然而，当该程序有交互式用户界面却不显示适当的法律声明时，你的作品也无需使其显示。

A compilation of a covered work with other separate and independent
works, which are not by their nature extensions of the covered work,
and which are not combined with it such as to form a larger program,
in or on a volume of a storage or distribution medium, is called an
``aggregate`` if the compilation and its resulting copyright are not
used to limit the access or legal rights of the compilation's users
beyond what the individual works permit.  Inclusion of a covered work
in an aggregate does not cause this License to apply to the other
parts of the aggregate.

一个涵盖的作品与其他单独且独立的作品组成一个组合，其中的单独作品既不是涵盖的作品的自然延伸，也不是为了与涵盖的作品组成更大程序而与被保护作品存储或者分发介质上，并且这种组合和组合后的版权不会限制单独作品的授权，则这种组合称为“组合体”。

### 6. Conveying Non-Source Forms

### 6. 以非源代码形式传递

You may convey a covered work in object code form under the terms
of sections 4 and 5, provided that you also convey the
machine-readable Corresponding Source under the terms of this License,
in one of these ways:

你可以以第4条和第5条所述那样以目标代码形式传递涵盖的作品，同时在本许证可规范下以如下方式之一传递机器可读的对应源代码：
  
- a) Convey the object code in, or embodied in, a physical product
  (including a physical distribution medium), accompanied by the
  Corresponding Source fixed on a durable physical medium
  customarily used for software interchange.

- a) 通过物理产品（包括物理分发媒介）传递或者嵌入目标代码时，通过常用于软件交换的耐用型物理媒介传递相应的源代码。
  
- b) Convey the object code in, or embodied in, a physical product
  (including a physical distribution medium), accompanied by a
  written offer, valid for at least three years and valid for as
  long as you offer spare parts or customer support for that product
  model, to give anyone who possesses the object code either (1) a
  copy of the Corresponding Source for all the software in the
  product that is covered by this License, on a durable physical
  medium customarily used for software interchange, for a price no
  more than your reasonable cost of physically performing this
  conveying of source, or (2) access to copy the
  Corresponding Source from a network server at no charge.

- b) 通过物理产品（包括物理分发媒介）时，附随具有至少3年有效期的书面承诺，并且有效期涵盖提供的备件或客户支持，以授予任何目标代码的持有者：（1）获得产品中全部涵盖的软件的相应源代码的副本，副本通过常用于软件交换的耐用型物理媒介提供，且收费不超过其合理的传递成本；或者（2）通过网络免费获得相应源代码的途径。

- c) Convey individual copies of the object code with a copy of the
  written offer to provide the Corresponding Source.  This
  alternative is allowed only occasionally and noncommercially, and
  only if you received the object code with such an offer, in accord
  with subsection 6b.

- c) 单独传递目标代码的副本时，伴以提供源代码的书面承诺。本选项仅在偶尔并且非商业情况下，同时你收到也是第6条b项所述的目标代码的情况下可用。
  
- d) Convey the object code by offering access from a designated
  place (gratis or for a charge), and offer equivalent access to the
  Corresponding Source in the same way through the same place at no
  further charge.  You need not require recipients to copy the
  Corresponding Source along with the object code.  If the place to
  copy the object code is a network server, the Corresponding Source
  may be on a different server (operated by you or a third party)
  that supports equivalent copying facilities, provided you maintain
  clear directions next to the object code saying where to find the
  Corresponding Source.  Regardless of what server hosts the
  Corresponding Source, you remain obligated to ensure that it is
  available for as long as needed to satisfy these requirements.

- d) 通过在指定地址获取目标代码（无论是否收费）的形式传递目标代码时，对同一地址以同样的方式提供相应源代码同等访问权限，并不得额外收费。你不必要求接收者在复制目标代码的同时复制源代码。如果提供获取目标代码的地址为网络服务器，相应的源代码可以提供在另一个支持相同复制功能的服务器上（由你或者第三方运营），不过你要在目标代码处指出相应源代码的确切路径。不管你用什么源代码服务器，你有义务要确保持续可用以满足这些要求。

- e) Convey the object code using peer-to-peer transmission, provided
  you inform other peers where the object code and Corresponding
  Source of the work are being offered to the general public at no
  charge under subsection 6d.

- 3) 通过点对点传输传递目标代码时，告知其他节点目标代码和源代码在何处，并以第6条d项形式向大众免费提供。
  
A separable portion of the object code, whose source code is excluded
from the Corresponding Source as a System Library, need not be
included in conveying the object code work.

如果目标代码的可分离部分，其源代码作为系统库在相应的源代码之外，则不需要被包括在传送目标代码作品中。

A ``User Product`` is either (1) a ``consumer product``, which means any
tangible personal property which is normally used for personal, family,
or household purposes, or (2) anything designed or sold for incorporation
into a dwelling.  In determining whether a product is a consumer product,
doubtful cases shall be resolved in favor of coverage.  For a particular
product received by a particular user, ``normally used`` refers to a
typical or common use of that class of product, regardless of the status
of the particular user or of the way in which the particular user
actually uses, or expects or is expected to use, the product.  A product
is a consumer product regardless of whether the product has substantial
commercial, industrial or non-consumer uses, unless such uses represent
the only significant mode of use of the product.

“用户产品”指（1）“消费品”，即个人、家庭或日常用途的个人的有形财产；或者（2）面向家庭设计或销售的物品。在判断一款产品是否消费品时，对于有争议的案例，应尽量扩大覆盖范围。就特定用户接收到特定产品而言，“正常使用”指对此类产品的典型的或一般使用，与该用户的身份，该用户对该产品的实际用法，以及该产品的预期用法无关。无论产品是否实质上具有商业上的，工业上的，及非面向消费者的用法，它都视为消费品，除非以上用法代表了它唯一的重要使用模式。

``Installation Information`` for a User Product means any methods,
procedures, authorization keys, or other information required to install
and execute modified versions of a covered work in that User Product from
a modified version of its Corresponding Source.  The information must
suffice to ensure that the continued functioning of the modified object
code is in no case prevented or interfered with solely because
modification has been made.

用户产品的“安装信息”，指基于修改过的源代码来安装运行该产品中的涵盖的作品的修改版所需的方法、流程、授权秘钥及其他信息。这些信息必须足以保证修改过的目标代码不会仅仅因为被修改过而不能继续工作。

If you convey an object code work under this section in, or with, or
specifically for use in, a User Product, and the conveying occurs as
part of a transaction in which the right of possession and use of the
User Product is transferred to the recipient in perpetuity or for a
fixed term (regardless of how the transaction is characterized), the
Corresponding Source conveyed under this section must be accompanied
by the Installation Information.  But this requirement does not apply
if neither you nor any third party retains the ability to install
modified object code on the User Product (for example, the work has
been installed in ROM).

如果你根据本条规定，传递一个目标代码作品到用户产品中或与用户产品一起，或专门用于特定用户产品，并且传送行为成为交易的一部分，使得用户产品永久或在特定期限内暂时转移给接收者（无论交易的特征如何），必须通过安装信息附上根据本条传递的相应来源。但如果你和第三方都没有在用户产品中保留安装修改目标代码的能力时，可以不遵守该要求（例如，作品有已安装在 ROM 中）。

The requirement to provide Installation Information does not include a
requirement to continue to provide support service, warranty, or updates
for a work that has been modified or installed by the recipient, or for
the User Product in which it has been modified or installed.  Access to a
network may be denied when the modification itself materially and
adversely affects the operation of the network or violates the rules and
protocols for communication across the network.

提供安装信息的要求不包括对接受者修改或者安装、或者已经被修改或者安装的用户产品继续提供支持服务、品质担保或者升级。当修改本身对网络运行有重大负面影响，或违反网络通信规则和协议时，可能会被拒绝访问网络。

Corresponding Source conveyed, and Installation Information provided,
in accord with this section must be in a format that is publicly
documented (and with an implementation available to the public in
source code form), and must require no special password or key for
unpacking, reading or copying.

根据本条规定，所专递相应源代码和所提供的安装信息必须以公开的文档格式（并且以源代码形式实现对公众可用）存在，同时不得对解包、阅读和复制设置任何密码或秘钥。

### 7. Additional Terms

### 7. 附加条款

``Additional permissions`` are terms that supplement the terms of this
License by making exceptions from one or more of its conditions.
Additional permissions that are applicable to the entire Program shall
be treated as though they were included in this License, to the extent
that they are valid under applicable law.  If additional permissions
apply only to part of the Program, that part may be used separately
under those permissions, but the entire Program remains governed by
this License without regard to the additional permissions.

“附加许可”用于补充本许可证的条款，以允许一或者多个例外情况。如果附加许可适用于整个程序且在适用的法律范围内有效，就应该视为本许可证的一部分。如果附加许可只适用于程序的某部分，则该部分受此附加许可约束，而其他部分受不适用附加许可之外的条款约束。

When you convey a copy of a covered work, you may at your option
remove any additional permissions from that copy, or from any part of
it.  (Additional permissions may be written to require their own
removal in certain cases when you modify the work.)  You may place
additional permissions on material, added by you to a covered work,
for which you have or can give appropriate copyright permission.

当你传递本程序的副本时，你可以选择性从副本中删除任何附加许可。（在某些情况下，当你修改作品时，附加许可可能已经写明要求你删除该附加许可。）对于你传递的作品，如果你拥有或者可以适当地授权，你也可以在作品的材料中添加附加许可。

Notwithstanding any other provision of this License, for material you
add to a covered work, you may (if authorized by the copyright holders of
that material) supplement the terms of this License with terms:

尽管本许可证还有的其他条款，对于你添加到涵盖的作品中的材料，你可以对本许可证（如果你获得该材料版权持有人的授权）添加如下补充条款：

- a) Disclaiming warranty or limiting liability differently from the
  terms of sections 15 and 16 of this License; or

- a) 以第15条、第16条之外的方式，拒绝提供品质担保或缩小责任范围。或者

- b) Requiring preservation of specified reasonable legal notices or
  author attributions in that material or in the Appropriate Legal
  Notices displayed by works containing it; or

- b) 要求在此材料中或在法律声明中包含特定的合理法律声明或作者信息。或者
  
- c) Prohibiting misrepresentation of the origin of that material, or
  requiring that modified versions of such material be marked in
  reasonable ways as different from the original version; or

- c) 禁止对该原始材料不当描述，或要求用不同与原始版本的方式对该材料修改版本合理标示。或者
  
- d) Limiting the use for publicity purposes of names of licensors or
  authors of the material; or

- d) 限制公开使用授权人或者该材料作者姓名。或者

- e) Declining to grant rights under trademark law for use of some
  trade names, trademarks, or service marks; or

- e) 拒绝使用在商标法下使用商号、商标及服务标识。

- f) Requiring indemnification of licensors and authors of that
  material by anyone who conveys the material (or modified versions of
  it) with contractual assumptions of liability to the recipient, for
  any liability that these contractual assumptions directly impose on
  those licensors and authors.

- f) 任何传递该材料（或其修改版）者，如果对接收者提供契约性责任许诺，需要为授权人或者该材料作者承担赔偿责任，因为任何契约假设责任都造成授权人或者作者承担。

All other non-permissive additional terms are considered ``further
restrictions`` within the meaning of section 10.  If the Program as you
received it, or any part of it, contains a notice stating that it is
governed by this License along with a term that is a further
restriction, you may remove that term.  If a license document contains
a further restriction but permits relicensing or conveying under this
License, you may add to a covered work material governed by the terms
of that license document, provided that the further restriction does
not survive such relicensing or conveying.

此外的非授权附加条款都被视作第10条所说的“进一步的限制”。如果你接收到的程序或程序的任何部分，包含受本许可约束的声明，却补充了这种进一步的限制条款，你可以删除它们。如果某许可文件包含进一步的限制条款，但允许通过本许可证再授权或传递，你可以添加受该许可文件保护的材料，同时提供其他的再许可或者传递的进一步限制条款。

If you add terms to a covered work in accord with this section, you
must place, in the relevant source files, a statement of the
additional terms that apply to those files, or a notice indicating
where to find the applicable terms.

如果你根据本条规定向涵盖的作品添加了新的条款，你必须在相关的源文件中加入附加条款的对应的声明，或者指明在哪里可以找到适用的条款。

Additional terms, permissive or non-permissive, may be stated in the
form of a separately written license, or stated as exceptions;
the above requirements apply either way.

附加条款，不管是授权的还是非授权的，可以以独立的书面许可出现，也可以声明为例外情况，两种做法都可以实现上述要求。

### 8. Termination

### 8. 终止

You may not propagate or modify a covered work except as expressly
provided under this License.  Any attempt otherwise to propagate or
modify it is void, and will automatically terminate your rights under
this License (including any patent licenses granted under the third
paragraph of section 11).

除非在本许可证明确授权下，你不得传播或修改涵盖的作品。其他任何传播或修改涵盖的作品的做法都是无效的，你通过本许可证获得的权利（包括第11条第3段中授予的专利权限）也自动终止。

However, if you cease all violation of this License, then your
license from a particular copyright holder is reinstated (a)
provisionally, unless and until the copyright holder explicitly and
finally terminates your license, and (b) permanently, if the copyright
holder fails to notify you of the violation by some reasonable means
prior to 60 days after the cessation.

然而，当你不再违反本许可证时，你从特定版权持有人处获得的许可可以：（1）暂时恢复，直到版权持有人明确终止；（2）永久恢复，如果版权持有人没能在60天内以合理的方式指出你的侵权行为。

Moreover, your license from a particular copyright holder is
reinstated permanently if the copyright holder notifies you of the
violation by some reasonable means, this is the first time you have
received notice of violation of this License (for any work) from that
copyright holder, and you cure the violation prior to 30 days after
your receipt of the notice.

再者，如果你第一次收到了特定版权持有人关于你违反本许可证（对任意作品）的通知，且在收到通知后30天内改正，那你可以继续享此有许可。

Termination of your rights under this section does not terminate the
licenses of parties who have received copies or rights from you under
this License.  If your rights have been terminated and not permanently
reinstated, you do not qualify to receive new licenses for the same
material under section 10.

当你享有的权利如本条所述被中止时，根据本许可证从你这里获得许可的第三方的权利不会因此中止。在你的权利恢复之前，你没有资格凭第10条获得同一材料的许可。

### 9. Acceptance Not Required for Having Copies

### 9. 持有副本不需要接受

You are not required to accept this License in order to receive or
run a copy of the Program.  Ancillary propagation of a covered work
occurring solely as a consequence of using peer-to-peer transmission
to receive a copy likewise does not require acceptance.  However,
nothing other than this License grants you permission to propagate or
modify any covered work.  These actions infringe copyright if you do
not accept this License.  Therefore, by modifying or propagating a
covered work, you indicate your acceptance of this License to do so.

你不必为接收或运行本程序而接受本许可。类似地，仅仅因点对点传输接收到副本引发的对涵盖的作品的辅助性传播，并不要求接受本许可证。但是，除本许可证外没有什么可以授权你传播或修改任何涵盖的作品。如果你不接受本许可证，这些行为就侵犯了著作权。因此，一旦修改和传播一个涵盖的作品，就表明你接受了本许可证。

### 10. Automatic Licensing of Downstream Recipients

### 10. 对下游接收者的自动授权

Each time you convey a covered work, the recipient automatically
receives a license from the original licensors, to run, modify and
propagate that work, subject to this License.  You are not responsible
for enforcing compliance by third parties with this License.

每当你传递一个涵盖的作品，其接收者自动获得来自原始授权人的许可，依照本许可证可以运行、修改和传播此作品。你没有要求第三方遵守本许可证的责任。

An ``entity transaction`` is a transaction transferring control of an
organization, or substantially all assets of one, or subdividing an
organization, or merging organizations.  If propagation of a covered
work results from an entity transaction, each party to that
transaction who receives a copy of the work also receives whatever
licenses to the work the party's predecessor in interest had or could
give under the previous paragraph, plus a right to possession of the
Corresponding Source of the work from the predecessor in interest, if
the predecessor has it or can get it with reasonable efforts.

“实体交易”指转移一个组织的控制权或全部资产、或拆分或合并组织的交易。如果实体交易导致一个涵盖的作品的传播，则交易中各收到作品副本方，都有获得前利益相关者享有或可以如前段所述提供的对该作品的任何授权，以及从前利益相关者处获得并拥有相应的源代码的权利，如果前利益相关者享有或可以通过合理的努力获得此源代码。

You may not impose any further restrictions on the exercise of the
rights granted or affirmed under this License.  For example, you may
not impose a license fee, royalty, or other charge for exercise of
rights granted under this License, and you may not initiate litigation
(including a cross-claim or counterclaim in a lawsuit) alleging that
any patent claim is infringed by making, using, selling, offering for
sale, or importing the Program or any portion of it.

你不可以对本许可证所授权利的行使施以进一步的限制。例如，你不可以索要许可费或版税，或就行使本许可证所授予的权利征收其他费用；你也不能发起诉讼（包括交互诉讼和反诉），宣称制作、使用、零售、批发、引进本程序或其部分的行为侵犯了任何专利声明。

### 11. Patents

### 11. 专利

A ``contributor`` is a copyright holder who authorizes use under this
License of the Program or a work on which the Program is based.  The
work thus licensed is called the contributor's ``contributor version``.

“贡献者”指通过本许可证对本程序或其衍生作品进行许可的版权持有人。贡献者许可的作品称为“贡献者版本”。

A contributor's ``essential patent claims`` are all patent claims
owned or controlled by the contributor, whether already acquired or
hereafter acquired, that would be infringed by some manner, permitted
by this License, of making, using, or selling its contributor version,
but do not include claims that would be infringed only as a
consequence of further modification of the contributor version.  For
purposes of this definition, ``control`` includes the right to grant
patent sublicenses in a manner consistent with the requirements of
this License.

贡献者的“必要专利声明”是由贡献者拥有或控制所有专利声明，无论是已经获得还是将要获得的，通过本许可证授权本来侵犯行为，例如制作、使用或销售其贡献者版本，但不包括仅对贡献者版本进一步修改的行为。根据本定义，“控制”包括符合本许可证要求的专利再许可的权利。

Each contributor grants you a non-exclusive, worldwide, royalty-free
patent license under the contributor's essential patent claims, to
make, use, sell, offer for sale, import and otherwise run, modify and
propagate the contents of its contributor version.

每位贡献者皆其就拥有的实际专利权限，授予你一份全球有效的免版费的非独占专利许可，以制作、使用、零售、批发、引进，及运行、修改、传播其贡献者版的内容。

In the following three paragraphs, a ``patent license`` is any express
agreement or commitment, however denominated, not to enforce a patent
(such as an express permission to practice a patent or covenant not to
sue for patent infringement).  To ``grant`` such a patent license to a
party means to make such an agreement or commitment not to enforce a
patent against the party.

在以下3段中，“专利授权”指通过任何方式明确表达的不行使专利权（如对使用专利的明确许可和不起诉专利侵权的契约）的协议或承诺。对某方“授予”专利权限，指这种不对其强制行使专利权的协议或承诺。

If you convey a covered work, knowingly relying on a patent license,
and the Corresponding Source of the work is not available for anyone
to copy, free of charge and under the terms of this License, through a
publicly available network server or other readily accessible means,
then you must either (1) cause the Corresponding Source to be so
available, or (2) arrange to deprive yourself of the benefit of the
patent license for this particular work, or (3) arrange, in a manner
consistent with the requirements of this License, to extend the patent
license to downstream recipients.  ``Knowingly relying`` means you have
actual knowledge that, but for the patent license, your conveying the
covered work in a country, or your recipient's use of the covered work
in a country, would infringe one or more identifiable patents in that
country that you have reason to believe are valid.

如果你传递的涵盖的作品时，明知需要某专利授权，而其相应的源代码并不是任何人都能根据本许可从网上或其他地方免费获得，那你必须（1）提供相应的源代码；或者（2）放弃从该程序的专利授权中的权益；或者（3）以某种和本许可相一致的方式将专利许可扩展到下游接收者。“明知需要”指你实际上知道若没有专利授权，你在某国家传递涵盖的作品的行为，或者接收者在某国家使用涵盖的作品的行为，会侵犯一项或多项该国认定的专利，而这些专利你有理由相信它们的有效性。

If, pursuant to or in connection with a single transaction or
arrangement, you convey, or propagate by procuring conveyance of, a
covered work, and grant a patent license to some of the parties
receiving the covered work authorizing them to use, propagate, modify
or convey a specific copy of the covered work, then the patent license
you grant is automatically extended to all recipients of the covered
work and works based on it.

如果根据单一交易或安排，抑或与之相关，你传递某涵盖的作品，或通过促成其转手以实现传播，并且该作品的接收方被授予专利权限，以使其可以使用、传播、修改或转发该作品的特定副本，则此等专利授权将自动延伸及每一个收到该作品或其衍生作品的接受者。

A patent license is ``discriminatory`` if it does not include within
the scope of its coverage, prohibits the exercise of, or is
conditioned on the non-exercise of one or more of the rights that are
specifically granted under this License.  You may not convey a covered
work if you are a party to an arrangement with a third party that is
in the business of distributing software, under which you make payment
to the third party based on the extent of your activity of conveying
the work, and under which the third party grants, to any of the
parties who would receive the covered work from you, a discriminatory
patent license (a) in connection with copies of the covered work
conveyed by you (or copies made from those copies), or (b) primarily
for and in connection with specific products or compilations that
contain the covered work, unless you entered into that arrangement,
or that patent license was granted, prior to 28 March 2007.

如果某专利在其涵盖范围内，不包含本许可证专门授予的一项或多项权利，禁止行使它们或以不行使它们为前提，则该专利是“歧视性”的。如果你和软件发布行业的第三方有合作，合作要求你就转发涵盖的作品的情况向其付费，并授予作品接收方歧视性专利，而且该专利（a）与你转发的副本（或在此基础上制作的副本）有关，或针对包含该涵盖的作品的产品或联合作品，你不得转发本程序，除非参加此项合作或取得该专利授权早于2007年3月28日。

Nothing in this License shall be construed as excluding or limiting
any implied license or other defenses to infringement that may
otherwise be available to you under applicable patent law.

本许可证的任何部分不应被解释成在排斥或限制任何暗含的许可，或者其他在适用专利法下对抗侵权的措施。

### 12. No Surrender of Others' Freedom

### 12. 不得牺牲他人的自由

If conditions are imposed on you (whether by court order, agreement or
otherwise) that contradict the conditions of this License, they do not
excuse you from the conditions of this License.  If you cannot convey a
covered work so as to satisfy simultaneously your obligations under this
License and any other pertinent obligations, then as a consequence you may
not convey it at all.  For example, if you agree to terms that obligate you
to collect a royalty for further conveying from those to whom you convey
the Program, the only way you could satisfy both those terms and this
License would be to refrain entirely from conveying the Program.

即便你面临与本许可证条款冲突的条件（来自于法庭要求、协议或其他），也不能成为你违反本许可证的理由。倘若你不能在传递涵盖的作品时同时满足本许可证和其他相关文件的要求，那么你就不要传递本程序。例如，你为了遵循某些要求，你必须向传递对象的接收者收取版税，唯一能同时满足它和本许可证要求的做法便是不传递本程序。

### 13. Remote Network Interaction; Use with the GNU General Public License

### 13. 远程网络交互；与GNU GPL通用公共许可证一起使用

Notwithstanding any other provision of this License, if you modify the
Program, your modified version must prominently offer all users interacting
with it remotely through a computer network (if your version supports such
interaction) an opportunity to receive the Corresponding Source of your
version by providing access to the Corresponding Source from a network
server at no charge, through some standard or customary means of
facilitating copying of software.  This Corresponding Source shall include
the Corresponding Source for any work covered by version 3 of the GNU
General Public License that is incorporated pursuant to the following
paragraph.

尽管本许可证中已存在其他条款，如果你修改了本程序，你的修改版必须在明显位置向所有通过计算机网络（如果你的版本支持此类交互）交互的用户在网络服务器上提供标准的或者符合用户习惯的、免费地获取你的版本的相应的源代码的方式。

Notwithstanding any other provision of this License, you have permission to
link or combine any covered work with a work licensed under version 3 of
the GNU General Public License into a single combined work, and to convey
the resulting work.  The terms of this License will continue to apply to
the part which is the covered work, but the work with which it is combined
will remain governed by version 3 of the GNU General Public License.

尽管本许可证有其他规定，你有权将任何涵盖的作品与根据 GNU 通用公共许可证第 3 版许可的作品链接或组合成一个单一的组合作品，并传递由此产生的作品。 本许可证的条款将继续适用于包含作品的部分，但与之结合的作品将继续受 GNU 通用公共许可证第 3 版的约束。

### 14. Revised Versions of this License

### 14. 本许可证的修订版

The Free Software Foundation may publish revised and/or new versions of
the GNU Affero General Public License from time to time.  Such new versions will
be similar in spirit to the present version, but may differ in detail to
address new problems or concerns.

自由软件基金会可能会不定时发布GNU通用公共许可证的修订版或新版。新版将秉承当前版本的精神，但在细节上描述不尽相同，以解决新的问题或事项。

Each version is given a distinguishing version number.  If the
Program specifies that a certain numbered version of the GNU Affero General
Public License ``or any later version`` applies to it, you have the
option of following the terms and conditions either of that numbered
version or of any later version published by the Free Software
Foundation.  If the Program does not specify a version number of the
GNU Affero General Public License, you may choose any version ever published
by the Free Software Foundation.

每一版都会有不同的版本号，如果本程序指定其使用的是某个GNU通用公共许可证的版本“或后续版本”，你可以选择遵守该版本或者任何后续版本的条款。如果本程序没有指定许可证的版本，你可以选用自由软件基金会发布的GNU通用公共许可证任何版本。

If the Program specifies that a proxy can decide which future
versions of the GNU Affero General Public License can be used, that proxy's
public statement of acceptance of a version permanently authorizes you
to choose that version for the Program.

如果本程序指明代理可以决定使用GNU通用公共许可证哪个版本，则该代理的公开声明的版本为授权你永久使用的版本。

Later license versions may give you additional or different
permissions.  However, no additional obligations are imposed on any
author or copyright holder as a result of your choosing to follow a
later version.

后续版本可能会给予你额外或不同的许可。但是，任何作者或版权持有人的义务，不会因为你选择新后续版本而增加。

### 15. Disclaimer of Warranty

### 15. 免责声明

THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY
APPLICABLE LAW.  EXCEPT WHEN OTHERWISE STATED IN WRITING THE
COPYRIGHT HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM ``AS IS``
WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED,
INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE.  THE ENTIRE
RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM IS WITH YOU.
SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL
NECESSARY SERVICING, REPAIR OR CORRECTION.

本程序在适用法律范围内不提供品质担保。除非另作书面声明，版权持有人及其他程序提供者“概”不提供任何显式或隐式的品质担保，品质担保所指包括而不仅限于有经济价值和适合特定用途的保证。全部风险，如程序的质量和性能问题，皆由你承担。若程序出现缺陷，你将承担所有必要的修复和更正服务的费用。

### 16. Limitation of Liability

### 16. 责任限制

IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN
WRITING WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES
AND/OR CONVEYS THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR
DAMAGES, INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL
DAMAGES ARISING OUT OF THE USE OR INABILITY TO USE THE PROGRAM
(INCLUDING BUT NOT LIMITED TO LOSS OF DATA OR DATA BEING RENDERED
INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD PARTIES OR A FAILURE
OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS), EVEN IF SUCH
HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH
DAMAGES.

除非适用法律或书面协议要求，任何版权持有人或本程序按本许可证可能存在的第三方修改和再发布者，都不对你的损失负有责任，包括由于使用或者不能使用本程序造成的任何一般的、特殊的、偶发的或重大的损失（包括而不限于数据丢失、数据失真、你或第三方的后续损失、其他程序无法与本程序协同运作），即使有人声称会对此负责。

### 17. Interpretation of Sections 15 and 16

### 17. 第15条和第16条的解释

If the disclaimer of warranty and limitation of liability provided
above cannot be given local legal effect according to their terms,
reviewing courts shall apply local law that most closely approximates
an absolute waiver of all civil liability in connection with the
Program, unless a warranty or assumption of liability accompanies a
copy of the Program in return for a fee.

如果上述免责声明和责任限制不为地方法律所支持，上诉法庭应采用与之最接近的关于放弃本程序相关民事责任的地方法律，除非本程序附带收费的品质担保或责任许诺。

End of Terms and Conditions

条款和适用条件结束

## How to Apply These Terms to Your New Programs

## 如何将上述条款应用到你的程序

If you develop a new program, and you want it to be of the greatest
possible use to the public, the best way to achieve this is to make it
free software which everyone can redistribute and change under these terms.

如果你开发了一个新程序，并且希望它最大限度地被公众所使用，最好的办法就是将其作为自由软件，使得每个人都可以按照本许可证分发和修改。

To do so, attach the following notices to the program.  It is safest
to attach them to the start of each source file to most effectively
state the exclusion of warranty; and each file should have at least
the ``copyright`` line and a pointer to where the full notice is found.

为此，最安全、最有效的办法是将如下的声明附在每个文件开头，以明确传达免责声明。每个文件应当最少包含一个“版权声明”和一个本许可证的完整声明。

<one line to give the program's name and a brief idea of what it does.>

    <用一行标明程序的名称和作用。 >

    Copyright (C) <textyear>  <name of author>

    版权所有 (C) <年份>  <作者姓名>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    本程序是自由软件，你可以根据自由软件基金会发布的GNU通用许可证自由地再分发或者修改。本程序适用第3版或者后续版本（具体随你）。

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

我们希望本程序有用，但是不提供任何保证，甚至不保证它的经济价值或者适合特定目的。具体细节参加GNU通过公共许可证。

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>..
你应当随本程序收到了GNU通用公共许可证的副本，如果没有，请参阅<https://www.gnu.org/licenses/>。

Also add information on how to contact you by electronic and paper mail.

同时提供你的电子邮件或者纸质邮件地址。

If your software can interact with users remotely through a computer
network, you should also make sure that it provides a way for users to
get its source.  For example, if your program is a web application, its
interface could display a ``Source`` link that leads users to an archive
of the code.  There are many ways you could offer source, and different
solutions will be better for different programs; see section 13 for the
specific requirements.

如果你的软件可以通过计算机网络远程与用户交互，你应该确保它提供了让用户获得源代码的方式。例如，你的程序是一个Web应用程序，
它应该显示“源代码”链接，以让用户访问代码存档。提供源代码的方式有多种，不同的程序适合不同的方式；具体参考第13条。

You should also get your employer (if you work as a programmer) or
school, if any, to sign a ``copyright disclaimer`` for the program, if
necessary.  For more information on this, and how to apply and follow
the GNU AGPL, see \texttt{<https://www.gnu.org/licenses/>}.

如果需要，你还应该得到你的雇主（如果你是一名程序员）或者学校（如果有的话）签署该本程序的放弃版权声明。关于如何应用及遵循GNU通用公共授权许可证的详细信息，请查看 <https://www.gnu.org/licenses/>。
