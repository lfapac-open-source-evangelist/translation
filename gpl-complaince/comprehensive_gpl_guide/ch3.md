

[]{#_bookmark42 .anchor}**CHAPTER 3**

RUNNING SOFTWARE AND VERBATIM COPYING

This chapter begins the deep discussion of the details of the terms of
GPLv2. In this chapter, we consider the first two sections: GPLv2
0--2. These are the straightforward sections of the GPL that define
the simplest rights that the user receives.

## GPLv2 §0: Freedom to Run

GPLv2 0, the opening section of GPLv2, sets forth that copyright law
governs the work. It specifically points out that it is the "copyright
holder" who decides if a work is licensed under its terms and explains
how the copyright holder might indicate this fact.

A bit more subtly, GPLv2 0 makes an inference that copyright law is
the only system that can restrict the software. Specifically, it
states:

Activities other than copying, distribution and modification are not
covered by this License; they are outside its scope.

In essence, the license governs *only* those activities, and all other
activities are unrestricted, provided that no other agreements trump
GPLv2 (which they cannot; see Sections
[7.3](#gplv2-6-gpl-my-one-and-only) and
[7.5).](#gplv2-7-give-software-liberty-or-give-it-death) This is very
important, because the Free Software community heavily supports users'
rights to "fair use" and "unregulated use" of copyrighted material.
GPLv2 asserts through this clause that it supports users' rights to
fair and unregulated uses.

Fair use (called "fair dealing" in some jurisdictions) of copyrighted
material is an established legal doctrine that permits certain
activities regardless of whether copyright law would otherwise
restrict those activities. Discussion of the various types of fair use
activity are beyond the scope of this tutorial. However, one important
example of fair use is the right to quote portions of the text in a
larger work so as to criticize or suggest changes. This fair use right
is commonly used on mailing lists when discussing potential
improvements or changes to Free Software.

Fair use is a doctrine established by the courts or by statute. By
contrast, unregulated uses are those that are not covered by the
statue nor determined by a court to be covered, but are common and
enjoyed by many users. An example of unregulated use is reading a
printout of the program's source code like an instruction book for the
purpose of learning how to be a better programmer. The right to read
something that you have access to is and should remain unregulated and
unrestricted.

Thus, the GPLv2 protects users' fair and unregulated use rights
precisely by not attempting to cover them. Furthermore, the GPLv2
ensures the freedom to run specifically by stating the following:

"The act of running the Program is not restricted."

Thus, users are explicitly given the freedom to run by GPLv2 *§*0.

The bulk of GPLv2 0 not yet discussed gives definitions for other
terms used throughout. The only one worth discussing in detail is
"work based on the Program". The reason this definition is
particularly interesting is not for the definition itself, which is
rather straightforward, but because it clears up a common
misconception about the GPL.

The GPL is often mistakenly criticized because it fails to give a
definition of "derivative work" or "com- bined work". In fact, it
would be incorrect and problematic if the GPL attempted to define
these terms. A copyright license, in fact, has no control over the
rules of copyright themselves. Such rules are the domain of copyright
law and the courts --- not the licenses that utilize those systems.

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

## GPLv2 §1: Verbatim Copying

GPLv2 1 covers the matter of redistributing the source code of a
program exactly as it was received. This section is quite
straightforward. However, there are a few details worth noting here.

The phrase "in any medium" is important. This, for example, gives the
freedom to publish a book that is the printed copy of the program's
source code. It also allows for changes in the medium of distribution.
Some vendors may ship Free Software on a CD, but others may place it
right on the hard drive of a pre-installed computer. Any such
redistribution media is allowed.

Preservation of copyright notice and license notifications are
mentioned specifically in GPLv2 1. These are in some ways the most
important part of the redistribution, which is why they are mentioned
by name. GPL always strives to make it abundantly clear to anyone who
receives the software what its license is. The goal is to make sure
users know their rights and freedoms under GPL, and to leave no reason
that users might be surprised the software is GPL'd. Thus throughout
the GPL, there are specific references to the importance of notifying
others down the distribution chain that they have rights under GPL.

GPL disclaims all warranties that legally can be disclaimed (which is
discussed later in sections [8.3](#gplv2-11-no-warranty) and
[8.4).](#gplv2-12-limitation-of-liability) Users generally rarely
expect their software comes with any warranties, since typically all
EULAs and other Free Software licenses disclaim warranties too.
However, since many local laws require "consipi- cous" warranty
disclaimers, GPLv2 1 explicitly mentions the importance of keeping
warranty disclaimers in tact upon redistribution.

Note finally that GPLv2 1 creates groundwork for the important defense
of commercial freedom. GPLv2 1 clearly states that in the case of
verbatim copies, one may make money. Re-distributors are fully
permitted to charge for the re-distribution of copies of Free
Software. In addition, they may provide the warranty protection that
the GPL disclaims as an additional service for a fee. (See Section
[12.2](#business-models) for more discussion on making a profit from
Free Software redistribution.)

