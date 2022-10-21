
Copyleft and the

GNU General Public License:

A Comprehensive Tutorial and Guide

Copyright c Copyright c Copyright c Copyright c Copyright c Copyright
c

2018 Chestek Legal.

2003--2005, 2008, 2014--2015, 2018 Bradley M. Kuhn.

2014--2015 Anthony K. Sebro, Jr.

2014 Denver Gingerich.

2003--2007, 2014 Free Software Foundation, Inc.

2008, 2014 Software Freedom Law Center.

The copyright holders grant the freedom to copy, modify, convey,
adapt, and/or redistribute this work (except Appendices
[B](#_bookmark256)[--E](#_bookmark261)) under the terms of the
Creative Commons Attribution Share Alike 4.0 International License. A
copy of that license is available at
<https://creativecommons.org/licenses/by-sa/4.0/legalcode>.

Appendices [B--E](#_bookmark261) include copies of the texts of
various licenses published by the FSF, and they are all licensed under
the license, "Everyone is permitted to copy and distribute verbatim
copies of this license document, but changing it is not allowed.".
However, those who seek to make modified versions of those licenses
should note the [explanation given in the GPL
FAQ.](https://www.gnu.org/licenses/gpl-faq.html#ModifyGPL)

As a public, collaborative project, this Guide is primarily composed
of the many contributions received via its [public contribution
process.](https://k.copyleft.org/guide/files/master/CONTRIBUTING.md)
Please [review its Git
logs](https://k.copyleft.org/guide/changelog/master/) for full
documentation of all contributions, and Appendix [A](#_bookmark255)
contains a list of third-party works from which some material herein
was adapted.

The most recent version is available online at
<https://copyleft.org/guide/>. Patches are indeed welcome to this
material. Sources can be found in the Git repository at
<https://k.copyleft.org/guide/>.

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

This tutorial is the culmination of nearly a decade of studying and
writing about software freedom licensing and the GPL. Each part of
this tutorial is a course unto itself, educating the reader on a
myriad of topics from the deep details of the GPLv2 and GPLv3, common
business models in the copyleft licensing area (both the friendly and
unfriendly kind), best practices for compliance with the GPL, for
engineers, managers, and lawyers, as well as real-world case studies
of GPL enforcement matters.

It is unlikely that all the information herein is necessary to learn
all at once, and therefore this tutorial likely serves best as a
reference book. The material herein has been used as the basis for
numerous live tutorials and discussion groups since 2002, and the
materials have been periodically updated. They likely stand on their
own as excellent reference material.

However, if you are reading these course materials without attending a
live tutorial session, please note that this material is merely a
summary of the highlights of the various CLE and other tutorial
courses based on this material. Please be aware that during the actual
courses, class discussion and presentation supplements this printed
curriculum. Simply reading this material is **not equivalent** to
attending a course.

