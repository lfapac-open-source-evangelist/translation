
[]{#_bookmark1 .anchor}

**Part I**

**第一部分**

**Detailed Analysis of the GNU GPL and Related Licenses**

**GNU GPL 及相关许可证的详细分析**

This part of the tutorial gives a comprehensive explanation of the most popular Free Software copy- right license, the GNU General Public License ("GNU GPL", or sometimes just "GPL") -- both version 2 ("GPLv2") and version 3 ("GPLv3") -- and teaches lawyers, software developers, managers and business people how to use the GPL (and GPL'd software) successfully both as a community-building "Constitution" for a software project, and to incorporate copylefted software into a new Free Software business and in existing, successful enterprises.

本教程的这一部分对最流行的开源软件版权许可证，即GNU通用公共许可证（“GNU GPL”，有时简称为“GPL”）——版本 2（“GPLv2”）和版本 GPLv3（“GPLv3”）——进行了全面的解释，引导律师、软件开发人员、管理人员和业务人员如何成功地使用GPL（以及GPL的软件），将其作为软件项目的社区建设“章程”，并将版权不标准(copylefted)的软件合并到新的自由软件业务和现有的成功企业中。

To benefit from this part of the tutorial, readers should have a general familiarity with software development processes. A basic understanding of how copyright law applies to software is also helpful. The tutorial is of most interest to lawyers, software developers and managers who run or advise software businesses that modify and/or redistribute software under the terms of the GNU GPL (or who wish to do so in the future), and those who wish to make use of existing GPL'd software in their enterprise.

为了从教程的这一部分中受益，读者应该对软件开发过程有一个大致的了解。对版权法如何适用于软件的基本理解也很有帮助。本教程最感兴趣的是律师、软件开发人员和管理人员，他们经营软件业务，建议根据GNU GPL条款修改和/或重新分发软件（或希望在将来这样做），还有那些希望在他们的企业中使用已有的GPL软件的人。

Upon completion of this part of the tutorial, readers can expect to have learned the following:

看完本教程的这一部分后，读者可以期望学到以下内容：

-   The freedom-defending purpose of various terms in the GNU GPLv2 and GPLv3.
-   GNU GPLv2和GPLv3中各种术语，目的是捍卫自由；

-   The differences between GPLv2 and GPLv3.
-   GPLv2和GPLv3的区别；

-   The redistribution options under the GPLv2 and GPLv3.
-   基于GPLv2和GPLv3的再分发选项；

-   The obligations when modifying GPLv2'd or GPLv3'd software.
-   修改GPLv2或GPLv3软件时应遵循的义务；

-   How to build a plan for proper and successful compliance with the GPL.
-   如何制定计划以正确且成功地遵守GPL协议；

-   The business advantages that the GPL provides.
-   GPL提供的业务优势；

-   The most common business models used in conjunction with the GPL.
-   与GPL结合使用的最常见的商业模式；

-   How existing GPL'd software can be used in existing enterprises.
-   企业如何使用已有的GPL软件；

-   The basics of LGPLv2.1 and LGPLv3, and how they differ from the GPLv2 and GPLv3, respectively.
-   LGPLv2.1和LGPLv3的基础知识，以及它们分别与GPLv2和GPLv3的区别；

-   The basics to begin understanding the complexities regarding derivative and combined works of software.
-   开始了解有关软件的衍生和组合作品的复杂性的基础知识。

[]{#_bookmark2 .anchor}

**CHAPTER 1 WHAT IS SOFTWARE FREEDOM?**

**第一章 什么是软件自由？**

Study of the GNU General Public License (herein, abbreviated as *GNU GPL* or just *GPL*) must begin by first considering the broader world of software freedom. The GPL was not created in a vacuum. Rather, it was created to embody and defend a set of principles that were set forth at the founding of the GNU Project and the Free Software Foundation (FSF) -- the preeminent organization that upholds, defends and promotes the philosophy of software freedom. A prerequisite for
understanding both of the popular versions of the GPL (GPLv2 and
GPLv3) and their terms and conditions is a basic understanding of the
principles behind them. The GPL family of licenses are unlike nearly
all other software licenses in that they are designed to defend and
uphold these principles.

## The Free Software Definition

The Free Software Definition is set forth in full on FSF's website at
<http://fsf.org/> philosophy/free-sw.html. This section presents an
abbreviated version that will focus on the parts that are most
pertinent to the GPL.

A particular user has software freedom with respect to a particular
program if that user has the following freedoms:

-   The freedom to run the program, for any purpose.

-   The freedom to study how the program works, and modify it

-   The freedom to redistribute copies.

-   The freedom to distribute copies of modified versions to others.

The focus on "a particular user" is particularly pertinent here. It is
not uncommon for a subset of a specific program's user base to have
these freedoms, while other users of the same version the program have
none or only some of these freedoms. Section [12.2](#business-models)
talks in detail about how this can unfortunately happen even if a
program is released under the GPL.

Many people refer to software with these freedoms as "Open Source."
Besides having a different political focus from those who call such
software by the name "Free Software",[^1^](#_bookmark4), those who
call the software "Open Source" are often focused on a side issue.
Specifically, user access to the source code of a program is a
prerequisite to make use of the freedom to modify. However, the
important issue is what freedoms are granted in the license that
applies to that source code.

Software freedom is only complete when no restrictions are imposed on
how these freedoms are exercised. Specifically, users and programmers
can exercise these freedoms noncommercially or commercially. Licenses

^1^[]{#_bookmark4 .anchor}The political differences between the Free
Software Movement and the Open Source Movement are documented on FSF's
Web site at
<http://www.fsf.org/licensing/essays/free-software-for-freedom.html>.

that grant these freedoms for noncommercial activities but prohibit
them for commercial activities are considered non-free. The Open
Source Initiative (*OSI* ) (the arbiter of what is considered "Open
Source") also regards such licenses as inconsistent with its "Open
Source Definition".

In general, software for which any of these freedoms are restricted in
any way is called "nonfree" software. Some use the term "proprietary
software" more or less interchangeably with "nonfree software". The
FSF published a useful [explanation of various types of software and
how they relate to one
another.](http://www.gnu.org/philosophy/categories.html)

Keep in mind that none of the terms "software freedom", "open source"
and "free software" are known to be trademarked or otherwise legally
restricted by any organization in any jurisdiction. As such, it's
quite common that these terms are abused and misused by parties who
wish to bank on the popularity of software freedom. When one considers
using, modifying or redistributing a software package that purports to
be Open Source or Free Software, one **must** verify that the license
grants software freedom.

Furthermore, throughout this text, we generally prefer the term
"software freedom", as this is the least ambiguous term available to
describe software that meets the Free Software Definition. For
example, it is well known and often discussed that the adjective
"free" has two unrelated meanings in English: "free as in freedom" and
"free as in price". Meanwhile, the term "open source" is even more
confusing, because it appears to refer only to the "freedom to study",
which is merely a subset of one of the four freedoms.

The remainder of this section considers each of each component of
software freedom in detail.

### The Freedom to Run

The first tenet of software freedom is the user's fully unfettered
right to run the program. The software's license must permit any
conceivable use of the software. Perhaps, for example, the user has
discovered an innovative use for a particular program, one that the
programmer never could have predicted. Such a use must not be
restricted.

It was once rare that this freedom was restricted by even proprietary
software; but such is quite common today. Most End User License
Agreements (EULAs) that cover most proprietary software typically
restrict some types of uses. Such restrictions of any kind are an
unacceptable restriction on software freedom.

### The Freedom to Change and Modify

Perhaps the most useful right of software freedom is the users' right
to change, modify and adapt the software to suit their needs. Access
to the source code and related build and installation scripts are an
essential part of this freedom. Without the source code, and the
ability to build and install the binary applications from that source,
users cannot effectively exercise this freedom.

Programmers directly benefit from this freedom. However, this freedom
remains important to users who are not programmers. While it may seem
counterintuitive at first, non-programmer users often exercise this
freedom indirectly in both commercial and noncommercial settings. For
example, users often seek noncommercial help with the software on
email lists and in user groups. To make use of such help they must
either have the freedom to recruit programmers who might
altruistically assist them to modify their software, or to at least
follow rote instructions to make basic modifications themselves.

More commonly, users also exercise this freedom commercially. Each
user, or group of users, may hire anyone they wish in a competitive
free market to modify and change the software. This means that
companies have a right to hire anyone they wish to modify their Free
Software. Additionally, such companies may contract with other
companies to commission software modifications.

### The Freedom to Copy and Share

Users share Free Software in a variety of ways. Software freedom
advocates work to eliminate a fundamental ethical dilemma of the
software age: choosing between obeying a software license and
friendship (by giving away a copy of a program to your friend who
likes the software you are using). Licenses that respect software
freedom, therefore, permit altruistic sharing of software among
friends.

The commercial environment also benefits from this freedom. Commercial
sharing includes selling copies of Free Software: that is, Free
Software can be distributed for any monetary price to anyone. Those
who

redistribute Free Software commercially also have the freedom to
selectively distribute (i.e., you can pick your customers) and to set
prices at any level that redistributor sees fit.

Of course, most people get copies of Free Software very cheaply (and
sometimes without charge). The competitive free market of Free
Software tends to keep prices low and reasonable. However, if someone
is willing to pay billions of dollars for one copy of the GNU Compiler
Collection, such a sale is completely permitted.

Another common instance of commercial sharing is service-oriented
distribution. For example, some distribution vendors provide immediate
security and upgrade distribution via a special network service. Such
distribution is not necessarily contradictory with software freedom.

(Section [12.2](#business-models) of this tutorial talks in detail
about some common Free Software business models that take advantage of
the freedom to share commercially.)

### The Freedom to Share Improvements

The freedom to modify and improve is somewhat empty without the
freedom to share those improvements. The software freedom community is
built on the pillar of altruistic sharing of improved Free Software.
Historically it was typical for a Free Software project to sprout a
mailing list where improvements would be shared freely among members
of the development community.[^2^](#_bookmark10) Such noncommercial
sharing is the primary reason that Free Software thrives.

Commercial sharing of modified Free Software is equally important. For
commercial support to exist in a competitive free market, all
developers -- from single-person contractors to large software
companies -- must have the freedom to market their services as
augmenters of Free Software. All forms of such service marketing must
be equally available to all.

For example, selling support services for Free Software is fully
permitted. Companies and individuals can offer themselves as "the
place to call" when software fails or does not function properly. For
such a service to be meaningful, the entity offering that service
needs the right to modify and improve the software for the customer to
correct any problems that are beyond mere user error.

Software freedom licenses also permit any entity to distribute
modified versions of Free Software. Most Free Software programs have a
"standard version" that is made available from the primary developers
of the software. However, all who have the software have the "freedom
to fork" -- that is, make available nontrivial modified versions of
the software on a permanent or semi-permanent basis. Such freedom is
central to vibrant developer and user interaction.

Companies and individuals have the right to make true value-added
versions of Free Software. They may use freedom to share improvements
to distribute distinct versions of Free Software with different
functionality and features. Furthermore, this freedom can be exercised
to serve a disenfranchised subset of the user community. If the
developers of the standard version refuse to serve the needs of some
of the software's users, other entities have the right to create a
long- or short-lived fork to serve that sub-community.

## How Does Software Become Free?

The previous section set forth key freedoms and rights that are
referred to as "software freedom". This section discusses the
licensing mechanisms used to enable software freedom. These licensing
mechanisms were ultimately created as a community-oriented "answer" to
the existing proprietary software licensing mechanisms. Thus, first,
consider carefully why proprietary software exists in the first place.

The primary legal regime that applies to software is copyright law.
Proprietary software exists at all only because copyright law governs
software.[^3^](#_bookmark11) Copyright law, with respect to software,
typically governs copying, modifying, and redistributing that software
(For details of this in the USA, see []{#_bookmark10 .anchor}[*§*
106](http://www.copyright.gov/title17/92chap1.html#106) and [*§*
117](http://www.copyright.gov/title17/92chap1.html#117) of [Title
17](http://www.law.cornell.edu/uscode/text/17) of

^2^[]{#_bookmark11 .anchor}This is still commonly the case, though
today there are additional ways of sharing Free Software.

^3^This statement is admittedly an oversimplification. Patents and
trade secrets can cover software and make it effectively non-Free, and
one can contract away their rights and freedoms regarding software, or
source code can be practically obscured in binary-only distribution
without reliance on any legal system. However, the primary control
mechanism for software is copyright, and therefore this section
focuses on how copyright restrictions make software proprietary.

the *United States Code*).[^4^](#_bookmark13) By law (in the USA and
in most other jurisdictions), the copyright holder (most typically,
the author) of the work controls how others may copy, modify and/or
distribute the work. For proprietary software, these controls are used
to prohibit these activities. In addition, proprietary software
distributors further impede modification in a practical sense by
distributing only binary code and keeping the source code of the
software secret.

Copyright is not a natural state, it is a legal construction. In the
USA, the Constitution permits, but does not require, the creation of
copyright law as federal legislation. Software, since it is an
"original work of authorship fixed in any tangible medium of
expression \... from which they can be perceived, reproduced, or
otherwise communicated, either directly or with the aid of a machine
or device" (as stated in [17
USC](http://www.law.cornell.edu/uscode/text/17/102)

[102)](http://www.law.cornell.edu/uscode/text/17/102), is thus covered
by the statute, and is copyrighted by default.

However, software, in its natural state without copyright, is Free
Software. In an imaginary world with no copyright, the rules would be
different. In this world, when you received a copy of a program's
source code, there would be no default legal system to restrict you
from sharing it with others, making modifications, or redistributing
those modified versions.[^5^](#_bookmark14)

Software in the real world is copyrighted by default and is
automatically covered by that legal system. However, it is possible to
move software out of the domain of the copyright system. A copyright
holder can often *disclaim* their copyright. (For example, under USA
copyright law it is possible for a copyright holder to engage in
conduct resulting in abandonment of copyright.) If copyright is
disclaimed, the software is effectively no longer restricted by
copyright law. Software not restricted by copyright is in the "public
domain."

### Public Domain Software

In the USA and other countries that are parties to the Berne
Convention on Copyright, software is copyrighted automatically by the
author when she fixes the software in a tangible medium. In the
software world, this usually means typing the source code of the
software into a file.

Imagine if authors could truly disclaim those default controls of
copyright law. If so, the software is in the public domain --- no
longer covered by copyright. Since copyright law is the construction
allowing for most restrictions on software (i.e., prohibition of
copying, modification, and redistribution), removing the software from
the copyright system usually yields software freedom for its users.

Carefully note that software truly in the public domain is *not*
licensed in any way. It is confusing to say software is "licensed for
the public domain," or any phrase that implies the copyright holder
gave express permission to take actions governed by copyright law.

Copyright holders who state that they are releasing their code into
the public domain are effectively renouncing copyright controls on the
work. The law gave the copyright holders exclusive controls over the
work, and they chose to waive those controls. Software that is, in
this sense, in the public domain is conceptualized by the developer as
having no copyright and thus no license. The software freedoms
discussed in Section [1.1](#the-free-software-definition) are all
granted because there is no legal system in play to take them away.

Admittedly, a discussion of public domain software is an
oversimplified example. Because copyright controls are usually
automatically granted and because, in some jurisdictions, some
copyright controls cannot be waived (see Section
[1.2.4](#non-usa-copyright-regimes) for further discussion), many
copyright holders sometimes incorrectly believe a work has been placed
in the public domain. Second, due to aggressive lobbying by the
entertainment industry, the "exclusive Right" of copyright, that was
supposed to only exist for "Limited Times" according to the USA
Constitution, appears to be infinite: simply purchased on the
installment plan rather than in whole. Thus, we must assume no works
of software will fall into the public domain merely due to the passage
of time.

Nevertheless, under USA law it is likely that the typical disclaimers
of copyright or public domain dedications we see in the Free Software
world would be interpreted by courts as copyright abandonment, leading
to a situation in which the user effectively receives a maximum grant
of copyright freedoms, similar to a maximally-permissive Free Software
license.

^4^[]{#_bookmark13 .anchor}Copyright law in general also governs
"public performance" of copyrighted works. There is no generally
agreed definition for []{#_bookmark14 .anchor}public performance of
software and both GPLv2 and GPLv3 do not restrict public performance.

^5^Note that this is again an oversimplification; the complexities
with this argument are discussed in Section
[1.2.3.](#software-and-non-copyright-legal-regimes)

The best example of software known to truly be in the public domain is
software that is published by the USA government. Under [17 USC 101
105,](http://www.law.cornell.edu/uscode/text/17/105) all works
published by the USA Government are not copyrightable in the USA.

### Why Copyright Free Software?

If simply disclaiming copyright on software yields Free Software, then
it stands to reason that putting software into the public domain is
the easiest and most straightforward way to produce Free Software.
Indeed, some major Free Software projects have chosen this method for
making their software Free. However, most of the Free Software in
existence *is* copyrighted. In most cases (particularly in those of
FSF and the GNU Project), this was done due to very careful planning.

Software released into the public domain does grant freedom to those
users who receive the standard versions on which the original author
disclaimed copyright. However, since the work is not copyrighted, any
nontrivial modification made to the work is fully copyrightable.

Free Software released into the public domain initially is Free, and
perhaps some who modify the software choose to place their work into
the public domain as well. However, over time, some entities will
choose to proprietarize their modified versions. The public domain
body of software feeds the proprietary software. The public commons
disappears, because fewer and fewer entities have an incentive to
contribute back to the commons. They know that any of their
competitors can proprietarize their enhancements. Over time, almost no
interesting work is left in the public domain, because nearly all new
work is done by proprietarization.

A legal mechanism is needed to redress this problem. FSF was in fact
originally created primarily as a legal entity to defend software
freedom, and that work of defending software freedom is a substantial
part of its work today. Specifically because of this "embrace,
proprietarize and extend" cycle, FSF made a conscious choice to
copyright its Free Software, and then license it under "copyleft"
terms. Many, including the developers of the kernel named Linux, have
chosen to follow this paradigm.

Copyleft is a strategy of utilizing copyright law to pursue the policy
goal of fostering and encouraging the equal and inalienable right to
copy, share, modify and improve creative works of authorship. Copyleft
(as a general term) describes any method that utilizes the copyright
system to achieve the aforementioned goal. Copyleft as a concept is
usually implemented in the details of a specific copyright license,
such as the [GNU](#_bookmark259) [General Public License
(GPL)](#_bookmark259) and the Creative Commons Attribution Share Alike
License (the latter of which is the license of this work itself).
Copyright holders of creative work can unilaterally implement these
licenses for their own works to build communities that collaboratively
share and improve those copylefted creative works.

Copyleft uses functional parts of the copyright system to achieve an
unusual result (legal protection for free sharing). Copyleft modifies,
or "hacks" copyright law, which is usually employed to strengthen the
rights of authors or publishers, to strengthen instead the rights of
users. Thus, Copyleft is a legal strategy and mechanism to defend,
uphold and propagate software freedom. The basic technique of copyleft
is as follows: copyright the software, license it under terms that
give all the software freedoms, but use the copyright law controls to
ensure that all who receive a copy of the software have equal rights
and freedom. In essence, copyleft grants freedom, but forbids others
to forbid that freedom to anyone else along the distribution and
modification chains.

Copyleft's "reciprocity" or "share and share alike" rule protects both
developers, who avoid facing a "prioritized" competitor of their
project, and users, who can be sure that they will have all four
software freedoms --- not only in the present version of the program
they use, but in all its future improved versions. Copyleft is a
general concept. Much like ideas for what a computer might do must be
*implemented* by a program that actually does the job, so too must
copyleft be implemented in some concrete legal structure. "Share and
share alike" is a phrase that is used often enough to explain the
concept behind copyleft, but to actually make it work in the real
world, a true implementation in legal text must exist, written as a
"copyright license". The GPL implements the concept of copyleft for
software-oriented and other functional works of a technical nature.
The "CC BY SA" license implements copyleft for works of textual,
musical and

visual authorship, such as this tutorial.

Copyleft advocates often distinguish between the concept of a "strong
copyleft" or a "weak copyleft". However, "strong vs. weak" copyleft is
not a dichotomy, it's a spectrum. The strongest copylefts strive to
the exclusive rights that copyright grants to authors as extensively
as possible to maximize software freedom.

As a copyleft gets "weaker", the copyleft license typically makes
"trade offs" that might impede software freedom, but reach other
tactic goals for the community of users and developers of the work.

In other words, strong copyleft licenses place the more requirements
on how "the work" is licensed. The unit of copyright law is "the
work". In that sense, the "work" referenced by the licenses is
anything that can be copyrighted or will be subject to the terms of
copyright law. Strong copyleft licenses exercise their scope fully.
Anything which is "a work" or a "work based on a work" licensed under
a strong copyleft is subject to its requirements, including the
requirement of complete, corresponding source code[^6^](#_bookmark18).
Thus, copyleft licenses, particularly strong ones, seek to ensure the
same license covers every version of "work based on the work", as
recognized by local copyright law, and thereby achieve the specific
strategic policy aim of ensuring software freedom for all users,
developers, authors, and readers who encounter the copylefted work.

### Software and Non-Copyright Legal Regimes

The use, modification and distribution of software, like many
endeavors, simultaneously interacts with mul- tiple different legal
regimes. As was noted early via footnotes, copyright is merely the
*most common way* to restrict users' rights to copy, share, modify
and/or redistribute software. However, proprietary software licenses
typically use every mechanism available to subjugate users. For
example:

Unfortunately, despite much effort by many in the software freedom
community to end patents that read on software (i.e., patents on
computational ideas), they still exist. As such, a software program
might otherwise seem to be unrestricted, but a patent might read on
the software and ruin everything for its users.[^7^](#_bookmark19)

Digital Restrictions Management (usually called *DRM* ) is often used
to impose technological restric- tions on users' ability to exercise
software freedom that they might otherwise be
granted.[^8^](#_bookmark20) The simplest (and perhaps oldest) form of
DRM, of course, is separating software source code (read by humans),
from their compiled binaries (read only by computers). Furthermore,
[17 USC 1201](http://www.law.cornell.edu/uscode/text/17/1201) often
prohibits users legally from circumventing some of these DRM systems.

Most EULAs also include a contractual agreement that bind users
further by forcing them to agree to a contractual, prohibitive
software license before ever even using the software.

Thus, most proprietary software restricts users via multiple
interlocking legal and technological means. Any license that truly
respect the software freedom of all users must not only grant
appropriate copyright permissions, but also *prevent* restrictions
from other legal and technological means like those listed above.

### Non-USA Copyright Regimes

Generally speaking, copyright law operates similarly enough in
countries that have signed the Berne Con- vention on Copyright, and
software freedom licenses have generally taken advantage of this
international standardization of copyright law. However, copyright law
does differ from country to country, and com- monly, software freedom
licenses like the GPL must be considered under the copyright law in
the jurisdiction where any licensing dispute occurs.

Those who are most familiar with the USA's system of copyright often
are surprised to learn that there are certain copyright controls that
cannot be waived nor disclaimed. Specifically, many copyright regimes
outside the USA recognize a concept of moral rights of authors.
Typically, moral rights are fully compatible with respecting software
freedom, as they are usually centered around controls that software
freedom licenses generally respect, such as the right of an authors to
require proper attribution for their work.

^6^[]{#_bookmark18 .anchor}Copyleft communities' use of the term
"strong copyleft" is undoubtedly imprecise. For example, most will
call the GNU GPL a "strong copyleft" license, even though the GPL
itself has various exceptions, such as the [GPLv3's system library
exception](#the-system-library-exception) written into the text of the
license itself. Furthermore, the copyleft community continues to
debate where the a license cross the line from "strong copyleft" to
"license that fails to respect software freedom", although ultimately
these debates are actually []{#_bookmark19 .anchor}regarding whether
the license fits [Free Software
definition](#the-free-software-definition) at all.

^7^See [6,](#_bookmark68)
[7.5,](#gplv2-7-give-software-liberty-or-give-it-death)
[9.14](#gplv3-11-explicit-patent-licensing) for more discussion on how
the patent system interacts with copyleft, and read Richard M.
Stallman's essay, [*Let's Limit the Effect of Software Patents, Since
We Can't Eliminate
Them*](http://www.wired.com/opinion/2012/11/richard-stallman-software-patents/)
for more information on the problems these []{#_bookmark20
.anchor}patents present to society.

8See *§* [9.5](#gplv3s-views-on-drm-and-device-lock-down) for more
information on how GPL deals with this issue.

## A Community of Equality

The previous section described the principles of software freedom, a
brief introduction to mechanisms that typically block these freedoms,
and the simplest ways that copyright holders might grant those
freedoms to their users for their copyrighted works of software. The
previous section also introduced the idea of *copyleft* : a licensing
mechanism to use copyright to not only grant software freedom to
users, but also to uphold those rights against those who might seek to
curtail them.

Copyleft, as defined in [1.2.2,](#why-copyright-free-software) is a
general term for this mechanism. The remainder of this text will
discuss details of various real-world implementations of copyleft --
most notably, the GPL.

This discussion begins first with some general explanation of what the
GPL is able to do in software devel- opment communities. After that
brief discussion in this section, deeper discussion of how GPL
accomplishes this in practice follows in the next chapter.

Simply put, though, the GPL ultimately creates a community of equality
for both business and noncom- mercial users.

### The Noncommercial Community

A GPL'd code base becomes a center of a vibrant development and user
community. Traditionally, volunteers, operating noncommercially out of
keen interest or "scratch an itch" motivations, produce initial
versions of a GPL'd system. Because of the efficient distribution
channels of the Internet, any useful GPL'd system is adopted quickly
by noncommercial users.

Fundamentally, the early release and quick distribution of the
software gives birth to a thriving noncom- mercial community. Users
and developers begin sharing bug reports and bug fixes across a shared
intellectual commons. Users can trust the developers, because they
know that if the developers fail to address their needs or abandon the
project, the GPL ensures that someone else has the right to pick up
development. Developers know that the users cannot redistribute their
software without passing along the rights granted by the GPL, so they
are assured that every one of their users is treated equally.

Because of the symmetry and fairness inherent in GPL'd distribution,
nearly every GPL'd package in existence has a vibrant noncommercial
user and developer base.

### The Commercial Community

By the same token, nearly all established GPL'd software systems have
a vibrant commercial community. Nearly every GPL'd system that has
gained wide adoption from noncommercial users and developers even-
tually begins to fuel a commercial system around that software.

For example, consider the Samba file server system that allows
Unix-like systems (including GNU/Linux) to serve files to Microsoft
Windows systems. Two graduate students originally developed Samba in
their spare time and it was deployed noncommercially in academic
environments.[^9^](#_bookmark24) However, very soon for-profit
companies discovered that the software could work for them as well,
and their system administrators began to use it in place of Microsoft
Windows NT file-servers. This served to lower the cost of running such
servers by orders of magnitude. There was suddenly room in Windows
file-server budgets to hire contractors to improve Samba. Some of the
first people hired to do such work were those same two graduate
students who originally developed the software.

The noncommercial users, however, were not concerned when these two
fellows began collecting paychecks off of their GPL'd work. They knew
that because of the nature of the GPL that improvements that were
distributed in the commercial environment could easily be folded back
into the standard version. Companies are not permitted to
proprietarize Samba, so the noncommercial users, and even other
commercial users are safe in the knowledge that the software freedom
ensured by the GPL will remain protected.

Commercial developers also work in concert with noncommercial
developers. Those two now-long-since graduated students continue to
contribute to Samba altruistically, but also get paid work doing it.
Priorities change when a client is in the mix, but all the code is
contributed back to the standard version. Meanwhile, many other
individuals have gotten involved noncommercially as developers,
because they want to "cut their

^9^[]{#_bookmark24 .anchor}See [Andrew Tridgell's "A bit of history
and a bit of fun"](http://turtle.ee.ncku.edu.tw/docs/samba/history)

teeth on Free Software," or because the problems interest them. When
they get good at it, perhaps they will move on to another project, or
perhaps they will become commercial developers of the software
themselves. No party is a threat to another in the GPL software
scenario because everyone is on equal ground. The GPL protects rights
of the commercial and noncommercial contributors and users equally.
The GPL creates

trust, because it is a level playing field for all.

### Law Analogy

In his introduction to Stallman's *Free Software, Free Society*,
Lawrence Lessig draws an interesting analogy between the law and Free
Software. He argues that the laws of a free society must be protected
much like the GPL protects software. So that I might do true justice
to Lessig's argument, I quote it verbatim:

A "free society" is regulated by law. But there are limits that any
free society places on this regulation through law: No society that
kept its laws secret could ever be called free. No government that hid
its regulations from the regulated could ever stand in our tradition.
Law controls. But it does so justly only when visibly. And law is
visible only when its terms are knowable and controllable by those it
regulates, or by the agents of those it regulates (lawyers,
legislatures).

This condition on law extends beyond the work of a legislature. Think
about the practice of law in American courts. Lawyers are hired by
their clients to advance their clients' interests. Sometimes that
interest is advanced through litigation. In the course of this
litigation, lawyers write briefs. These briefs in turn affect opinions
written by judges. These opinions decide who wins a particular case,
or whether a certain law can stand consistently with a constitution.

All the material in this process is free in the sense that Stallman
means. Legal briefs are open and free for others to use. The arguments
are transparent (which is different from saying they are good), and
the reasoning can be taken without the permission of the original
lawyers. The opinions they produce can be quoted in later briefs. They
can be copied and integrated into another brief or opinion. The
"source code" for American law is by design, and by principle, open
and free for anyone to take. And take lawyers do---for it is a measure
of a great brief that it achieves its creativity through the reuse of
what happened before. The source is free; creativity and an economy is
built upon it.

This economy of free code (and here I mean free legal code) doesn't
starve lawyers. Law firms have enough incentive to produce great
briefs even though the stuff they build can be taken and copied by
anyone else. The lawyer is a craftsman; his or her product is public.
Yet the crafting is not charity. Lawyers get paid; the public doesn't
demand such work without price. Instead this economy flourishes, with
later work added to the earlier.

We could imagine a legal practice that was different --- briefs and
arguments that were kept secret; rulings that announced a result but
not the reasoning. Laws that were kept by the police but published to
no one else. Regulation that operated without explaining its rule.

We could imagine this society, but we could not imagine calling it
"free." Whether or not the incentives in such a society would be
better or more efficiently allocated, such a society could not be
known as free. The ideals of freedom, of life within a free society,
demand more than efficient application. Instead, openness and
transparency are the constraints within which a legal system gets
built, not options to be added if convenient to the leaders. Life
governed by software code should be no less.

Code writing is not litigation. It is better, richer, more productive.
But the law is an obvious instance of how creativity and incentives do
not depend upon perfect control over the products created. Like jazz,
or novels, or architecture, the law gets built upon the work that went
before. This adding and changing is what creativity always is. And a
free society is one that assures that its most important resources
remain free in just this sense.[^10^](#_bookmark26)

10[]{#_bookmark26 .anchor}This quotation is Copyright c 2002, Lawrence
Lessig. It is licensed under the terms of [the "Attribution License"
version](http://creativecommons.org/licenses/by/1.0/)

[1.0](http://creativecommons.org/licenses/by/1.0/) or any later
version as published by Creative Commons.

In essence, lawyers are paid to service the shared commons of legal
infrastructure. Few citizens defend themselves in court or write their
own briefs (even though they are legally permitted to do so) because
everyone would prefer to have an expert do that job.

The Free Software economy is a market ripe for experts. It functions
similarly to other well established professional fields like the law.
The GPL, in turn, serves as the legal scaffolding that permits the
creation of this vibrant commercial and noncommercial Free Software
economy.

