

[**CHAPTER 3**]{#_bookmark42 .anchor}


[**第3章**]{#_bookmark42 .anchor}

RUNNING SOFTWARE AND VERBATIM COPYING

运行软件与逐字复制

This chapter begins the deep discussion of the details of the terms of
GPLv2. In this chapter, we consider the first two sections: GPLv2
§§0--2. These are the straightforward sections of the GPL that define
the simplest rights that the user receives.

本章开始深入讨论GPLv2条款的细节。在本章中，我们将考虑前两个部分：GPLv2 §§0-2。这些是GPL中简单明了的部分，定义了用户获得的最单纯的权利。

## 3.1 GPLv2 §0: Freedom to Run
## 3.1 GPLv2 §0：自由运行

GPLv2 §0, the opening section of GPLv2, sets forth that copyright law
governs the work. It specifically points out that it is the "copyright
holder" who decides if a work is licensed under its terms and explains
how the copyright holder might indicate this fact.

GPLv2 §0——GPLv2的开篇部分阐述了作品受著作权法管辖。该部分特别指出由“著作权所有者”决定作品是否根据其条款进行许可，并解释了著作权所有者如何表明这一事实。

A bit more subtly, GPLv2 §0 makes an inference that copyright law is
the only system that can restrict the software. Specifically, it
states:

更微妙的一点是，GPLv2 §0推断著作权法是唯一可以限制软件的系统。具体来说，它指出:

Activities other than copying, distribution and modification are not
covered by this License; they are outside its scope.

本许可证对除复制、分发和修改外的其他活动无效；它们超出了其适用范围。

In essence, the license governs *only* those activities, and all other
activities are unrestricted, provided that no other agreements trump
GPLv2 (which they cannot; see Sections
[7.3](#gplv2-6-gpl-my-one-and-only) and
[7.5).](#gplv2-7-give-software-liberty-or-give-it-death) This is very
important, because the Free Software community heavily supports users'
rights to "fair use" and "unregulated use" of copyrighted material.
GPLv2 asserts through this clause that it supports users' rights to
fair and unregulated uses.

本质上，许可证*只*管理这些活动，所有其他活动都是不受限制的，如果没有其他协议限制GPLv2（这是不可能的；参见第[7.3](#gplv2-6-gpl-my-one-and-only)和[7.5).](#gplv2-7-give-software-liberty-or-give-it-death)节）。这是非常重要的，因为自由软件社区大力支持用户享有对受著作权保护的材料的“合理使用”和“不受管制的使用”的权利。GPLv2通过这一条款声明它支持用户公平和不受管制的使用权利。

Fair use (called "fair dealing" in some jurisdictions) of copyrighted
material is an established legal doctrine that permits certain
activities regardless of whether copyright law would otherwise
restrict those activities. Discussion of the various types of fair use
activity are beyond the scope of this tutorial. However, one important
example of fair use is the right to quote portions of the text in a
larger work so as to criticize or suggest changes. This fair use right
is commonly used on mailing lists when discussing potential
improvements or changes to Free Software.

对受著作权保护的材料的合理使用（在某些司法管辖区称为“公平交易”）是一种既定的法律原则，允许进行某些活动而不管著作权法是否会限制这些活动。关于各种类型的合理使用活动的讨论超出了本指南的范围。然而，合理使用的一个重要典型是有权在较大的作品中引用文本的部分内容，以便进行批评或提出修改建议。当讨论自由软件的潜在改进或变化时，这种合理使用权在邮件列表中会被经常使用。

Fair use is a doctrine established by the courts or by statute. By
contrast, unregulated uses are those that are not covered by the
statue nor determined by a court to be covered, but are common and
enjoyed by many users. An example of unregulated use is reading a
printout of the program's source code like an instruction book for the
purpose of learning how to be a better programmer. The right to read
something that you have access to is and should remain unregulated and
unrestricted.

合理使用是由法院或法令确立的原则。相比之下，不受管制的使用是指那些不受法令保护也不在法院管辖范围内、但很常见且深受广大用户喜爱的使用方式。它的一个例子是：为了学习如何成为一个更好的程序员，像阅读说明书一样阅读程序源代码的打印资料。阅读你能读到的东西的权利是且应该保持不受监管和限制的。

Thus, the GPLv2 protects users' fair and unregulated use rights
precisely by not attempting to cover them. Furthermore, the GPLv2
ensures the freedom to run specifically by stating the following:

因此，GPLv2正是通过不试图包含它们来保护用户的公平和不受监管的使用权。此外，GPLv2通过声明以下内容确保了运行的自由：

"The act of running the Program is not restricted."

“运行程序的行为不受限制。”

Thus, users are explicitly given the freedom to run by GPLv2 §0.

因此，用户明确地获得了使用GPLv2 §0运行的自由。

The bulk of GPLv2 §0 not yet discussed gives definitions for other
terms used throughout. The only one worth discussing in detail is
"work based on the Program". The reason this definition is
particularly interesting is not for the definition itself, which is
rather straightforward, but because it clears up a common
misconception about the GPL.

尚未讨论的大部分GPLv2 §0给出了贯穿始终的其他术语的定义。唯一值得详细讨论的是“基于程序的作品”。这个定义之所以特别有趣不是因为这个相当简明的定义本身，而是因为它澄清了关于GPL的一个常见误解。

The GPL is often mistakenly criticized because it fails to give a
definition of "derivative work" or "com- bined work". In fact, it
would be incorrect and problematic if the GPL attempted to define
these terms. A copyright license, in fact, has no control over the
rules of copyright themselves. Such rules are the domain of copyright
law and the courts --- not the licenses that utilize those systems.

GPL经常被错误地批评，因为它没有给出“衍生作品”或“组合作品”的定义。事实上，如果GPL试图定义这些术语，才是不正确且有问题的。著作权许可证实际上并不能控制著作权规则本身。这样的规则属于著作权法和法院（而不是使用这些系统的许可证）的管辖范围。

Copyright law as a whole does not propose clear and straightforward
guidelines for identifying the deriva- tive and/or combined works of
software. However, no copyright license --- not even the GNU GPL ---
can be blamed for this. Legislators and court opinions must give us
guidance in borderline cases. Meanwhile, lawyers will likely based
their conclusions on the application of rules made in the context of
literary or artistic copyright to the different context of computer
programming and by analyzing the (somewhat limited) case law and
guidance available from various sources. (Chapter
[14.1](#evaluate-license-applicability) discusses this issue in
depth.)

著作权法整体并没有就识别软件的衍生作品和/或组合作品提出明确而直接的指导方针。然而，没有著作权许可证——甚至GNU GPL——才应该对此负责。立法者和法院必须在边界模糊的案件中为我们提供指导。与此同时，律师们可能会根据文学或艺术著作权背景下制定的规则在计算机编程的不同背景下的应用情况，以及通过分析（有限的）案例法和各种渠道获得的指导来得出结论。（第[14.1](#evaluate-license-applicability)章深入讨论了这个问题。）

## 3.2 GPLv2 §1: Verbatim Copying

## 3.2 GPLv2 §1：逐字复制

GPLv2 §1 covers the matter of redistributing the source code of a
program exactly as it was received. This section is quite
straightforward. However, there are a few details worth noting here.

GPLv2 §1涵盖了重新完整分发程序源代码的问题。这部分相当简单明了。但有一些细节值得一提。

The phrase "in any medium" is important. This, for example, gives the
freedom to publish a book that is the printed copy of the program's
source code. It also allows for changes in the medium of distribution.
Some vendors may ship Free Software on a CD, but others may place it
right on the hard drive of a pre-installed computer. Any such
redistribution media is allowed.

“在任何媒介中”这句话很重要。举个例子，它交出了将程序源代码的打印副本作为一本书出版的自由。它还允许更改分发媒介。一些厂商可能以CD的形式推出自由软件，但其他厂商可能将其直接置入预装计算机的硬盘驱动器中。任何这样的重新分发媒体都是允许的。

Preservation of copyright notice and license notifications are
mentioned specifically in GPLv2 *§*1. These are in some ways the most
important part of the redistribution, which is why they are mentioned
by name. GPL always strives to make it abundantly clear to anyone who
receives the software what its license is. The goal is to make sure
users know their rights and freedoms under GPL, and to leave no reason
that users might be surprised the software is GPL'd. Thus throughout
the GPL, there are specific references to the importance of notifying
others down the distribution chain that they have rights under GPL.

GPLv2 §1中特别提到著作权通知和许可证通知的保存。在某种程度上，这些是重新分发作品中最重要的部分，这就是提及它们的原因。GPL一直在努力让收到软件的人都清楚地知道它的许可证是什么。我们的目标是确保用户知道他们在GPL限制下的权利和自由，没有理由让用户对软件使用GPL感到惊讶。因此，整个GPL中都有专门提到通知分发链下游的其他人他们拥有GPL限制下的权利的重要性。

GPL disclaims all warranties that legally can be disclaimed (which is
discussed later in sections [8.3](#gplv2-11-no-warranty) and
[8.4).](#gplv2-12-limitation-of-liability) Users generally rarely
expect their software comes with any warranties, since typically all
EULAs and other Free Software licenses disclaim warranties too.
However, since many local laws require "consipi- cous" warranty
disclaimers, GPLv2 1 explicitly mentions the importance of keeping
warranty disclaimers in tact upon redistribution.

GPL放弃所有法律上可以放弃的担保（这将在后面的[8.3](#gplv2-11-no-warranty)节和[8.4).](#gplv2-12-limitation-of-liability)节中讨论）。用户通常很少期望他们的软件附带任何担保，因为通常所有的EULA和其他自由软件许可证也都放弃担保。然而，由于许多地方法律要求“明显的”免责声明，GPLv2 *§*1明确提到在重新分发时完整保留免责声明的重要性。

Note finally that GPLv2 §1 creates groundwork for the important defense
of commercial freedom. GPLv2 §1 clearly states that in the case of
verbatim copies, one may make money. Re-distributors are fully
permitted to charge for the re-distribution of copies of Free
Software. In addition, they may provide the warranty protection that
the GPL disclaims as an additional service for a fee. (See Section
[12.2](#business-models) for more discussion on making a profit from
Free Software redistribution.)

最后请注意，GPLv2 §1为捍卫商业自由奠定了基础。GPLv2 §1明确指出在逐字复制的情况下可以赚钱。重新分发者对自由软件副本的重新分发版进行收费是完全允许的。此外，他们还可以提供GPL拒绝的担保，将其作为附加服务进行收费。（有关从自由软件重新分发中获利的更多讨论，请参见第[12.2](#business-models)节。）
