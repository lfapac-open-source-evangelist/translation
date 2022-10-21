
[]{#_bookmark93 .anchor}**CHAPTER 9**

GPL VERSION 3

This chapter discusses the text of GPLv3. Much of this material herein
includes text that was adapted (with permission) from text that FSF
originally published as part of the so-called "rationale documents"
for the various discussion drafts of GPLv3.

The FSF ran a somewhat public process to develop GPLv3, and it was the
first attempt of its kind to develop a Free Software license this way.
Ultimately, RMS was the primary author of GPLv3, but he listened to
feedback from all sorts of individuals and even for-profit companies.
Nevertheless, in attempting to understand GPLv3 after the fact, the
materials available from the GPLv3 process have a somewhat "drinking
from the firehose" effect. This chapter seeks to explain GPLv3 to
newcomers, who perhaps are familiar with GPLv2 and who did not
participate in the GPLv3 process.

Those who wish to drink from the firehose and take a diachronic
approach to GPLv3 study by reading the step-by-step public drafting
process of the GPLv3 (which occurred from Monday 16 January 2006
through Monday 19 November 2007) should visit <http://gplv3.fsf.org/>.

## Understanding GPLv3 As An Upgraded GPLv2

Ultimately, GPLv2 and GPLv3 co-exist as active licenses in regular
use. As discussed in Chapter [2,](#_bookmark27) GPLv1 was never
regularly used alongside GPLv2. However, given GPLv2's widespread
popularity and existing longevity by the time GPLv3 was published, it
is not surprising that some licensors still prefer GPLv2-only or
GPLv2-or-later. GPLv3 gained major adoption by many projects, old and
new, but many projects have not upgraded due to (in some cases) mere
laziness and (in other cases) policy preference for some of GPLv2's
terms and/or policy opposition to GPLv3's terms.

Given this "two GPLs world" is reality, it makes sense to consider
GPLv3 in terms of how it differs from GPLv2. Also, most of the best
GPL experts in the world must deal regularly with both licenses, and
admittedly have decades of experience with GPLv2 while the most
experience with GPLv3 that's possible is by definition less than a
decade. These two factors usually cause even new students of GPL to
start with GPLv2 and move on to GPLv3, and this tutorial follows that
pattern.

Overall, the changes made in GPLv3 admittedly *increased* the
complexity of the license. The FSF stated at the start of the GPLv3
process that they would have liked to oblige those who have asked for
a simpler and shorter GPL. Ultimately, the FSF gave priority to making
GPLv3 a better copyleft license in the spirit of past GPL's. Obsession
for concision should never trump software freedom.

The FSF had many different, important goals in seeking to upgrade to
GPLv3. However, one important goal that is often lost in the
discussion of policy minutia is a rather simple but important issue.
Namely, FSF sought to assure that GPLv3 was more easily
internationalized than GPLv2. In particular, the FSF sought to ease
interpretation of GPL in other countries by replacement of
USA-centric[^1^](#_bookmark95) copyright phrases

^1^[]{#_bookmark95 .anchor}See Section
[1.2.4](#non-usa-copyright-regimes) of this tutorial for a brief
discussion about non-USA copyright systems.

and wording with neutral terminology rooted in description of behavior
rather than specific statute. As can be seen in the section-by-section
discussion of GPLv3 that follows, nearly every section had changes
related to issues of internationalization.

## GPLv3 §0: Giving In On "Defined Terms"

One of lawyers' most common complaints about GPLv2 is that defined
terms in the document appear throughout. Most licenses define terms
up-front. However, the GPL was always designed both as a document that
should be easily understood both by lawyers and by software
developers: it is a document designed to give freedom to software
developers and users, and therefore it should be comprehensible to
that constituency.

Interestingly enough, one coauthor of this tutorial who is both a
lawyer and a developer pointed out that in law school, she understood
defined terms more quickly than other law students precisely because
of her programming background. For developers, having #define (in the
C programming language) or other types of constants and/or macros that
automatically expand in the place where they are used is second
nature. As such, adding a defined terms section was not terribly
problematic for developers, and thus GPLv3 adds one. Most of these
defined terms are somewhat straightforward and bring forward better
worded definitions from GPLv2. Herein, this tutorial discusses a few
of the new ones.

GPLv3 0 includes definitions of five new terms not found in any form
in GPLv2: "modify" "covered work", "propagate", "convey", and
"Appropriate Legal Notices".

### Modify and the Work Based on the Program

GPLv2 included a defined term, "work based on the Program", but also
used the term "modify" and "based on" throughout the license. GPLv2's
"work based on the Program" definition made use of a legal term of
art, "derivative work", which is peculiar to USA copyright
law.[^2^](#_bookmark99) GPLv2 always sought to cover all rights
governed by relevant copyright law, in the USA and elsewhere. Even
though differently-labeled concepts corresponding to the derivative
work are recognized in all copyright law systems, these counterpart
concepts might differ to some degree in scope and breadth from the USA
derivative work. GPLv3 therefore internationalizes on this issue by
removing GPLv2's references to derivative works and by providing a
more globally useful definition. GPLv3 drops all reference to USA
"derivative works" and returns to the base concept only: GPL covers
the licensed work and all works where copyright permission from the
licensed work's copyright holder.

The new definitions returns to the common elements of copyright law.
Copyright holders of works of software have the exclusive right to
form new works by modification of the original --- a right that may be
expressed in various ways in different legal systems. GPLv3 operates
to grant this right to successive generations of users (particularly
through the copyleft conditions set forth in GPLv3 5, as described
later in this tutorial in its [9.8).](#gplv3-5-modified-source) Here
in GPLv3 0, "modify" refers to basic copyright rights, and then this
definition of "modify" is used to define "modified version of" and
"work based on" as synonyms.

### The Covered Work

GPLv3 uses a common license drafting technique of building upon
simpler definitions to make complex ones. The Program is a defined
term found throughout GPLv2, and the word "covered" and the phrase
"covered by this license" are used in tandem with the Program in
GPLv2, but not as part of a definition. GPLv3 offers a single term
"covered work", which enables some of the wording in GPLv3 to be
simpler and clearer than its GPLv2 counterparts.

Next, to avoid locking GPLv3 into specific copyright statues, the
GPLv3 defines two terms that are otherwise exotic to the language of
international copyright.

^2^[]{#_bookmark99 .anchor}Ironically, most criticism of USA-specific
legal terminology in GPLv2's "work based on the Program" definition
historically came not primarily from readers outside the USA, but from
those within it. The FSF noted in that it did not generally agree with
these views, and expressed puzzlement by the energy with which they
were expressed, given the existence of many other, more difficult
legal issues implicated by the GPL. Nevertheless, the FSF argued that
it made sense to eliminate usage of local copyright terminology to
good effect.

### Propagate

To "propagate" a work covered by the license means any activity in a
locale that requires permission of copyright holders in that locale's
legal system. However, personal use or modification for personal use
are activities explicitly excluded from "propagation" *regardless* of
domestic copyright law.

The term "propagate" serves two purposes. First, "propagate" provides
a simple and convenient means for distinguishing between the kinds of
uses of a work that GPL imposes conditions on and the kinds of uses
that GPL does not (for the most part) impose conditions on.

Second, "propagate" helps globalize GPL in its wording and effect:
"derivative work" was in fact not the only term commonly used by local
copyright statutes. A term like "distribute" (or its equivalent in
languages other than English) is also used in several national
copyright statutes. Practical experience with GPLv2 revealed the
awkwardness of using the term "distribution" in a license intended for
global use: the scope of "distribution" in the copyright context can
differ from country to country. The GPL never necessarily intended the
specific meaning of "distribution" that exists under USA (or any other
country's) copyright law.

Indeed, even within a single country and language, the term
distribution may be ambiguous; as a legal term of art, distribution
varies significantly in meaning among those countries that recognize
it. For example, comments during GPLv3's drafting process indicated
that in at least one country, distribution may not include network
transfers of software but may include interdepartmental transfers of
physical copies within an organization. Meanwhile, the copyright laws
of many countries, as well as certain international copyright
treaties, recognize "making available to the public" or "communication
to the public" as one of the exclusive rights of copyright holders.

Therefore, the GPLv3 defines the term "propagate" by reference to
activities that require permission un- der "applicable copyright law",
but excludes execution and private modification from the definition.
GPLv3's definition also gives examples of activities that may be
included within "propagation" but it also makes clear that, under the
copyright laws of a given country, "propagation" may include other
activities as well.

Thus, propagation is defined by behavior, and not by categories drawn
from some particular national copyright statute. This helps not only
with internationalization, but also factually-based terminology aids
in developers' and users' understanding of the GPL.

As a further benefit, because "propagation" includes all exclusive
rights granted under any particular copyright regime, the term
automatically accounts for all exclusive rights under that regime.

### Convey

Next, GPLv3 defines a subset of propagate --- "convey". Conveying
includes activities that constitute propagation of copies to others.
As with the definition of propagate, GPLv3 thus addresses transfers of
copies of software in behavioral rather than statutory terms. Any
propagation that enables other parties to receive or make copies of
the work, is called "conveying". Usually, conveying is the activity
that triggers most of the other obligations of GPLv3.

### Appropriate Legal Notices

GPLv2 used the term "appropriate copyright notice and disclaimer of
warranty" in two places, which is a rather bulky term. Also,
experience with GPLv2 and other licenses that grant software freedom
showed throughout the 1990s that the scope of types of notices that
need preservation upon conveyance were more broad that merely the
copyright notices. The Appropriate Legal Notice definition
consolidates the material that GPLv2 traditionally required preserved
into one definition.

### Other Defined Terms

Note finally that not all defined terms in GPLv3 appear in GPLv3 0.
Specifically, those defined terms that are confined in use to a single
section are defined in the section in which they are used, and GPLv3 1
contains those definitions focused on source code. In this tutorial,
those defined terms are discussed in the section where they are
defined and/or used.

## GPLv3 §1: Understanding CCS

Ensuring that users have the source code to the software they receive
and the freedom to modify remains the paramount right embodied in the
Free Software Definition (found in
[1.1](#the-free-software-definition) of this tutorial). As such, GPLv3
1 is likely one of the most important sections of GPLv3, as it
contains all the defined terms related to this important software
freedom.

### Source Code Definition

First, GPLv3 1 retains GPLv2's definition of "source code" and adds an
explicit definition of "object code" as "any non-source version of a
work". Object code is not restricted to a narrow technical meaning and
is understood broadly to include any form of the work other than the
preferred form for making modifications to it. Object code therefore
includes any kind of transformed version of source code, such as
bytecode or minified Javascript. The definition of object code also
ensures that licensees cannot escape their obligations under the GPL
by resorting to shrouded source or obfuscated programming.

### CCS Definition

The definition of CCS,[^3^](#_bookmark107) or, as GPLv3 officially
calls it, "Corresponding Source" in GPLv3 1 4 is possibly the most
complex definition in the license.

The CCS definition is broad so as to protect users' exercise of their
rights under the GPL. The definition includes particular examples to
remove any doubt that they are to be considered CCS. GPLv3 seeks to
make it completely clear that a licensee cannot avoid complying with
the requirements of the GPL by dynamically linking a subprogram
component to the original version of a program. The examples also
clarify that the shared libraries and dynamically linked subprograms
that are included in Corresponding Source are those that the work is
"specifically" designed to require, which clarifies that they do not
include libraries invoked by the work that can be readily substituted
by other existing implementations. While copyleft advocates never
doubted this was required under GPLv2's definition of CCS, GPLv3 makes
it abundantly clear with an extra example.

The GPL, as always, seeks to ensure users are truly in a position to
install and run their modified versions of the program; the CCS
definition is designed to be expansive to ensure this software
freedom. However, although the definition of CCS is expansive, it is
not sufficient to protect users' freedoms in many circumstances. For
example, a GPL'd program, or a modified version of such a program,
might be locked- down and restricted. The requirements in GPLv3 6
(discussed in Section
[9.9](#gplv3-6-non-source-and-corresponding-source) of this tutorial)
handle that issue. (Early drafts of GPLv3 included those requirements
in the definition of CCS; however, given that the lock-down issue only
comes up in distribution of object code, it is more logical to place
those requirements with the parts of GPLv3 dealing directly with
object code distribution).

The penultimate paragraph in GPLv3 2 notes that GPLv3's CCS definition
does not require source that can be automatically generated. Many code
generators, preprocessors and take source code as input and sometimes
even have output that is still source code. Source code should always
be whatever the original programmer preferred to modify.

GPLv3 1's final paragraph removes any ambiguity about what should be
done on source-only distribu- tions. Specifically, the right to convey
source code that does not compile, does not work, or otherwise is
experimental in-progress work is fully permitted, *provided that* no
object code form is conveyed as well. Indeed, when combined with the
permissions in GPLv3 5, it is clear that if one conveys *only* source
code, one can never be required to provide more than that. One always
has the right to modify a source code work by deleting any part of it,
and there can be no requirement that free software source code be a
whole functioning program.

^3^[]{#_bookmark107 .anchor}Note that the preferred term for those who
work regularly with both GPLv2 and GPLv3 is "Complete Corresponding
Source", abbreviated to "CCS". Admittedly, the word "complete" no
longer appears in GPLv3 (which uses the word "all" instead). However,
both GPLv2 and the early drafts of GPLv3 itself used the word
"complete", and early GPLv3 drafts even called this defined term
"Complete Corresponding Source". Meanwhile, use of the acronym "CCS"
(sometimes, "C&CS") was so widespread among GPL enforcers that its use
continues even though GPLv3-focused experts tend to say just the
defined term of "Corresponding Source".

### The System Library Exception

The previous section skipped over one part of the CCS definition, the
so-called system library exception. The "System Libraries" definition
(and the "Standard Interface" and "Major Component" definitions, which
it includes) are designed to permit certain distribution arrangements
that are considered reasonable by copyleft advocates. The system
library exception is designed to allow copylefted software to link
with these libraries when prohibition of that linking would hurt
software freedom more than it would hurt proprietary software. The
system library exception has two parts. Part (a) rewords the GPLv2
exception for clarity replacing GPLv2's words "unless that component
itself accompanies the executable" with "which is not part of the
Major Component". The goal here is to not require disclosure of source
code of certain libraries, such as necessary Microsoft Windows DLLs
(which aren't part of Windows' kernel but accompany it) that are

required for functioning of copylefted programs compiled for Windows.

However, in isolation, (a) would be too permissive, as it would
sometimes allow distributors to evade important GPL requirements. Part
(b) reigns in (a). Specifically, (b) specifies only a few
functionalities that a system library may provide and still qualify
for the exception. The goal is to ensure system libraries are truly
adjunct to a major essential operating system component, compiler, or
interpreter. The more low-level the functionality provided by the
library, the more likely it is to be qualified for this exception.

Admittedly, the system library exception is a frequently discussed
topic of obsessed GPL theorists. The amount that has been written on
the system library exception (both the GPLv2 and GPLv3 versions of
it), if included herein, could easily increase this section of the
tutorial to a length greater than all the others.

Like any exception to the copyleft requirements of GPL, would-be GPL
violators frequently look to the system library exception as a
potential software freedom circumvention technique. When considering
whether or not a library qualifies for the system library exception,
here is a pragmatic thesis to consider, based on the combined decades
of experience in GPL interpretation of this tutorial's authors: the
harder and more strained the reader must study and read the system
library exception, the more likely it is that the library in question
does not qualify for it.

## GPLv3 §2: Basic Permissions

GPLv3 2 can roughly be considered as an equivalent to GPLv2 0
(discussed in [3.1](#gplv2-0-freedom-to-run) of this tutorial).
However, the usual style of improvements found in GPLv3 are found here
as well. For example, the first sentence of GPLv3 2 furthers the goal
internationalization. Under the copyright laws of some countries, it
may be necessary for a copyright license to include an explicit
provision setting forth the duration of the rights being granted. In
other countries, including the USA, such a provision is unnecessary
but permissible. GPLv3 2 1 also acknowledges that licensees under the
GPL enjoy rights of copyright fair use, or the equivalent under
applicable law. These rights are compatible with, and not in conflict
with, the freedoms

that the GPL seeks to protect, and the GPL cannot and should not
restrict them.

However, note that (sadly to some copyleft advocates) the unlimited
freedom to run is confined to the *unmodified* Program. This
confinement is unfortunately necessary since Programs that do not
qualify as a User Product in GPLv3 6 (see [9.9.2](#user-products) in
this tutorial) might have certain unfortunate restrictions on the
freedom to run.[^4^](#_bookmark110)

GPLv3 2 2 distinguishes between activities of a licensee that are
permitted without limitation and activities that trigger additional
requirements. Specifically, GPLv3 2 2 guarantees the basic freedoms of
privately modifying and running the program. While these basic
freedoms were generally considered a standard part of users' rights
under GPLv2 as well, the GPLv3 states them herein more explicitly. In
other words, there is no direct analog to the first sentence of GPLv3
2 2 in GPLv2 (See [5.1.3](#right-to-private-modification) of this
tutorial for more on this issue.)

Also, GPLv3 2 2 gives an explicit permission for a client to provide a
copy of its modified software to a contractor exclusively for that
contractor to modify it further, or run it, on behalf of the client.
However, the client can *only* exercise this control over its own
copyrighted changes to the GPL-covered program. The parts of the
program it obtained from other contributors must be provided to the
contractor with the usual GPL freedoms. Thus, GPLv3 permits users to
convey covered works to contractors operating exclusively on

4[]{#_bookmark110 .anchor}See *§* [1.1.1](#the-freedom-to-run) of this
tutorial for the details on "the freedom to run".

the users' behalf, under the users' direction and control, and to
require the contractors to keep the users' copyrighted changes
confidential, but *only if* the contractor is limited to acting on the
users' behalf (just as the users' employees would have to act).

The strict conditions in this "contractors provision" are needed so
that it cannot be twisted to fit other activities, such as making a
program available to downstream users or customers. By making the
limits on this provision very narrow, GPLv3 ensures that, in all other
cases, contractor gets the full freedoms of the GPL that they deserve.

The FSF was specifically asked to add this "contractors provisions" by
large enterprise users of Free Software, who often contract with
non-employee developers, working offsite, to make modifications
intended for the user's private or internal use, and often arrange
with other companies to operate their data centers. Whether GPLv2
permits these activities is not clear and may depend on variations in
copyright law in different jurisdictions. The practices seem basically
harmless, so FSF decided to make it clear they are permitted.

GPLv3 2's final paragraph includes an explicit prohibition of
sublicensing. This provision ensures that GPL enforcement is always by
the copyright holder. Usually, sublicensing is regarded as a practical
convenience or necessity for the licensee, to avoid having to
negotiate a license with each licensor in a chain of distribution. The
GPL solves this problem in another way --- through its automatic
licensing provision found in GPLv3 *§*10 (which is discussed in more
detail in *§* [9.13](#gplv3-10-explicit-downstream-license) of this
tutorial).

## GPLv3's views on DRM and Device Lock-Down

The issues of DRM, device lock-down and encryption key disclosure were
the most hotly debated during the GPLv3 process. FSF's views on this
were sadly frequently misunderstood and, comparing the provisions
related to these issues in the earliest drafts of GPLv3 to the final
version of GPLv3 shows the FSF's willingness to compromise on tactical
issues to reach the larger goal of software freedom.

Specifically, GPLv3 introduced provisions that respond to the growing
practice of distributing GPL- covered programs in devices that employ
technical means to restrict users from installing and running modified
versions. This practice thwarts the expectations of developers and
users alike, because the right to modify is one of the core freedoms
the GPL is designed to secure.

Technological measures to defeat users' rights. These measures are
often described by such Orwellian phrases, such as "digital rights
management," which actually means limitation or outright destruction
of users' legal rights, or "trusted computing," which actually means
selling people computers they cannot trust. However, these measures
are alike in one basic respect. They all employ technical means to
turn the system of copyright law (where the powers of the copyright
holder are limited exceptions to general freedom) into a virtual
prison, where everything not specifically permitted is utterly
forbidden. This system of "para- copyright" was created well after
GPLv2 was written --- initially through legislation in the USA and the
EU, and later in other jurisdictions as well. This legislation creates
serious civil or even criminal penalties to escape from these
restrictions (commonly and aptly called "jail-breaking a device"),
even where the purpose in doing so is to restore the users' legal
rights that the technology wrongfully prevents them from exercising.
GPLv2 did not address the use of technical measures to take back the
rights that the GPL granted, because such measures did not exist in
1991, and would have been irrelevant to the forms in which software
was then delivered to users. GPLv3 addresses these issues,
particularly because copylefted software is ever

more widely embedded in devices that impose technical limitations on
the user's freedom to change it.

However, FSF always made a clear distinction to avoid conflating these
"lock-down" measures with legitimate applications that give users
control, as by enabling them to choose higher levels of system or data
security within their networks, or by allowing them to protect the
security of their communications using keys they can generate or copy
to other devices for sending or receiving messages. Such technologies
present no obstacles to software freedom and the goals of copyleft.

The public GPLv3 drafting process sought to balance these positions of
copyleft advocates with various disparate views of the larger
Free-Software-using community. Ultimately, FSF compromised to the
GPLv3 3 and GPLv3 6 provisions that, taken together, are a minimalist
set of terms sufficient to protect the software freedom against the
threat of invasive para-copyright.

The compromises made were ultimately quite reasonable. The primary one
is embodied in GPLv3*§*6's

"User Product" definition (see [9.9.2](#user-products) in this
tutorial for details). Additionally, some readers of early GPLv3
drafts seem to have assumed GPLv3 contained a blanket prohibition on
DRM; but it does not. In fact, no part of GPLv3 forbids DRM regarding
non-GPL'd works; rather, GPLv3 forbids the use of DRM specifically to
lock-down restrictions on users' ability to install modified versions
of the GPL'd software itself, but again, *only* with regard to User
Products.

## GPLv3 §3: What Hath DMCA Wrought

As discussed in [1.2.3](#software-and-non-copyright-legal-regimes) of
this tutorial, [17 USC
1201](http://www.law.cornell.edu/uscode/text/17/1201) and related
sections[^5^](#_bookmark114) prohibits users from circumventing
technological measures that implement DRM. Since this is part of
copyright law and the GPL is primarily a copyright license, and since
what the DMCA calls "circumvention" is simply "modifying the software"
under the GPL, GPLv3 must disclaim that such anti-circumvention
provisions are not applicable to the GPLv3'd software. GPLv3 3 shields
users from being subjected to liability under anti-circumvention law
for exercising their rights under the GPL, so far as the GPL can do
so.

First, GPLv3 3 1 declares that no GPL'd program is part of an
effective technological protection measure, regardless of what the
program does. Early drafts of GPLv3 3 1 referred directly to the DMCA,
but the final version instead includes instead an international legal
reference to anticircumvention laws enacted pursuant to the 1996 WIPO
treaty and any similar laws. Lawyers outside the USA worried that a
USA statutory reference could be read as indicating a choice for
application of USA law to the license as a whole. While the FSF did
not necessarily agree with that view, the FSF decided anyway to refer
to the WIPO treaty rather than DMCA, since several national
anticircumvention laws were (or will likely be) structured more
similarly to the anticircumvention provisions of the DMCA in their
implementation of WIPO. Furthermore, the addition of "or similar laws"
provides an appropriate catch-all.

GPLv3 3 2 states precisely that a conveying party waives the power to
forbid circumvention of techno- logical measures only to the extent
that such circumvention is accomplished through the exercise of GPL
rights in the conveyed work. GPLv3 3 2 makes clear that the referenced
"legal rights" are specifically rights arising under anticircumvention
law. and refers to both the conveying party's rights and to third
party rights, as in some cases the conveying party will also be the
party legally empowered to enforce or invoke rights arising under
anticircumvention law.

These disclaimers by each licensor of any intention to use GPL'd
software to stringently control access to other copyrighted works
should effectively prevent any private or public parties from invoking
DMCA-like laws against users who escape technical restriction measures
implemented by GPL'd software.

## GPLv3 §4: Verbatim Copying

GPLv3 4 is a revision of GPLv2 1 (as discussed in
[3.2](#gplv2-1-verbatim-copying) of this tutorial). There are almost
no changes to this section from the GPLv2 1, other than to use the new
defined terms.

The only notable change, of "a fee" to "any price or no price", is in
the first sentence of GPLv3 4 2. The GPLv2 1 1 means that the GPL
permits one to charge money for the distribution of software. Despite
efforts by copyleft advocates to explain this in GPLv2 itself and in
other documents, there are evidently some people who still believe
that GPLv2 allows charging for services but not for selling copies of
software and/or that the GPL requires downloads to be gratis. Perhaps
this is because GPLv2 referred to charging a "fee"; the term "fee" is
generally used in connection with services.

GPLv2's wording also referred to "the physical act of transferring."
The intention was to distinguish charging for transfers from attempts
to impose licensing fees on all third parties. "Physical" might be
read, however, as suggesting "distribution in a physical medium only".

To address these two issues, GPLv3 says "price" in place of "fee," and
removes the term "physical." GPLv3 *§*4 has also been revised from its
corresponding section in GPLv2 in light of the GPLv3 *§*7 (see

*§* [9.9.3](#gplv3-7-additional-permissions) in this tutorial for
more). Specifically, a distributor of verbatim copies of the program's
source code must obey any existing additional terms that apply to
parts of the program pursuant to GPLv3 []{#_bookmark114 .anchor}*§*7.
In

^5^These sections of the USC are often referred to as the "Digital
Millennium Copyright Act", or "DMCA", as that was the name of the bill
that so-modified these sections of the USC.

addition, the distributor is required to keep intact all license
notices, including notices of such additional terms.

Finally, there is no harm in explicitly pointing out what ought to be
obvious: that those who convey GPL-covered software may offer
commercial services for the support of that software.

## GPLv3 §5: Modified Source

GPLv3 5 is the rewrite of GPLv2 2, which was discussed in
[5.1](#gplv2-2-share-and-share-alike) of this tutorial. This section
discusses the changes found in GPLv3 5 compared to GPLv2 2.

GPLv3 5(a) still requires modified versions be marked with "relevant
date", but no longer says "the date of any change". The best practice
is to include the date of the latest and/or most significant changes
and who made those. Of course, compared to its GPLv2 2(a), GPLv3 5(a)
slightly relaxes the requirements regarding notice of changes to the
program. In particular, the modified files themselves need no longer
be marked. This reduces administrative burdens for developers of
modified versions of GPL'd software.

GPLv3 5(b) is a new but simple provision. GPLv3 5(b) requires that the
license text itself must be unmodified (except as permitted by GPLv3
7; see [9.9.3](#gplv3-7-additional-permissions) in this tutorial).
Furthermore, it removes any perceived conflict between the words "keep
intact all notices" in GPLv3 4, since operating under GPLv3 5 still
includes all the requirements of GPLv3 4 by reference.

GPLv3 5(c) is the primary source-code-related copyleft provision of
GPL. (The object-code-related copy- left provisions are in GPLv3 6,
discussed in [9.9](#gplv3-6-non-source-and-corresponding-source) of
this tutorial). Compared to GPLv2 2(b), GPLv3 5(c) states that the GPL
applies to the whole of the work. Such was stated already in GPLv2
2(b), in "in whole or in part", but this simplified wording makes it
clear it applies to the entire covered work.

Another change in GPLv3 5(c) is the removal of the words "at no
charge," which was often is misunder- stood upon na¨ıve reading of in
GPLv2 (b) (as discussed in [5.1.2](#gplv2-2b) of this tutorial).

Note that of GPLv2 2's penultimate and ante-penultimate paragraphs are
now handled adequately by the definitions in GPLv3 0 and as such, have
no direct analogs in GPLv3.

GPLv2 2's final paragraph, however, is reworded and expanded into the
final paragraph of GPLv3 5, which now also covers issues related to
copyright compilations (but not compilations into object code ---
that's in the next section!). The intent and scope is the same as was
intended in GPLv2.

## GPLv3 §6: Non-Source and Corresponding Source

GPLv3 6 states the compliance obligations for distributing "non-source
forms" of a program (which means any form other than CCS). As noted in
[9.2,](#gplv3-0-giving-in-on-defined-terms) "object code" in GPLv3 is
defined broadly to mean any non-source version of a work, and thus
includes not only binaries or executables, but also obfuscated, mini-
mized, compressed or otherwise non-preferred forms for modification.
Thus, GPLv3 6 clarifies and revises GPLv2 3. Indeed, GPLv3 6's CCS
requirement under closely parallels the provisions of [GPLv2
3,](#gplv2-3-producing-binaries) with changes designed to make
compliant provisioning easier under contemporary technological
conditions. Dis- tributors of GPLv3'd object code must provide access
to the corresponding source code, in one of four specified ways.

GPLv3 6(a--b) now apply specifically to distribution of object code in
a physical product. Physical products include embedded systems, as
well as physical software distribution media such as CDs. As in GPLv2
3 (discussed in [5.2](#gplv2-3-producing-binaries) of this tutorial),
the distribution of object code may either be accompanied by the
machine-readable source code, or it may be accompanied by a valid
written offer to provide the machine-readable source code. However,
unlike in GPLv2, that offer cannot be exercised by any third party;
rather, only those "who possess the object code" can exercise the
offer. (Note that this is a substantial narrowing of requirements of
offer fulfillment, and is a wonderful counterexample to dispute claims
that the GPLv3 has more requirements than GPLv2.)

GPLv3 6(b) further revises the requirements for the written offer to
provide source code. As before, the offer must remain valid for at
least three years. In addition, even after three years, a distributor
of a product containing GPL'd object code must offer to provide source
code for as long as the distributor also continues to offer spare
parts or customer support for the product model. This is a reasonable
and

appropriate requirement; a distributor should be prepared to provide
source code if he or she is prepared to provide support for other
aspects of a physical product.

GPLv3 6(a--b) clarifies that the medium for software interchange on
which the machine-readable source code is provided must be a durable
physical medium. GPLv3 6(b)(2), however, permits a distributor to
instead offer to provide source code from a network server instead,
which is yet another example GPLv3 looser in its requirements than
GPLv2 (see [5.2.2](#additional-source-provision-options) for details).

GPLv3 6(c) gives narrower permission than GPLv2 3(c). The "pass along"
option for GPLv3 6(c)(1) offers is now available only for individual
distribution of object code; moreover, such individual distribution
can occur only "occasionally and noncommercially." A distributor
cannot comply with the GPL merely by making object code available on a
publicly-accessible network server accompanied by a copy of the
written offer to provide source code received from an upstream
distributor.

GPLv3 6(d) revises and improves GPLv2 3's final paragraph. When object
code is provided by offering access to copy the code from a designated
place (such as by enabling electronic access to a network server), the
distributor must merely offer equivalent access to copy the source
code "in the same way through the same place". This wording also
permits a distributor to offer a third party access to both object
code and source code on a single network portal or web page, even
though the access may include links to different physical servers. For
example, a downstream distributor may provide a link to an upstream
distributor's server and arrange with the operator of that server to
keep the source code available for copying for as long as the
downstream distributor enables access to the object code. Thus, the
obligation remains on the party distributing object code to point
prominently ("next to" the object code download) to the third-party
source code provisioning server, and to ensure that this third-party
server remains in operation for required period. This codifies
formally the typical historical interpretation of GPLv2.

Furthermore, under GPLv3 6(d), distributors may charge for the
conveyed object code; however, those who pay to obtain the object code
must be given equivalent and gratis access to obtain the CCS. (If
distributors convey the object code gratis, distributors must likewise
make CCS available without charge.) Those who do not obtain the object
code from that distributors (perhaps because they choose not to pay
the fee for object code) are outside the scope of the provision;
distributors are under no specific obligation to give CCS to someone
who has not purchased an object code download under GPLv3 *§*6(d).
(Note: this does not change nor impact any obligations under GPLv3
*§*6(b)(2); GPLv3 *§*6(d) is a wholly different provision.)

### GPLv3 §6(e): Peer-to-Peer Sharing Networks

GPLv3 6(e) allows provision of CCS via another server when the binary
or other non-source form is dis- tributed by peer-to-peer protocols
such as BitTorrent. Here the requirement is only that each peer be
effectively informed of the location of the source code on a server as
above.

GPLv3 really did require this addition, even though it adds complexity
to a key section of GPL. In particular, Decentralized peer-to-peer
file sharing present a challenge to the unidirectional view of
distribution that is implicit in GPLv2 and initial drafts of GPLv3.
Identification of an upstream/downstream link in BitTorrent
distribution is neither straightforward nor reasonable; such
distribution is multidirectional, cooperative and (somewhat)
anonymous. In peer-to-peer distribution systems, participants act both
as transmitters and recipients of blocks of a particular file, but
they perceive the experience merely as users and receivers, and not as
distributors in any conventional sense. At any given moment of time,
most peers will not have the complete file.

Meanwhile, GPLv3 6(d) permits distribution of a work in object code
form over a network, provided that the distributor offers equivalent
access to copy the Corresponding Source Code "in the same way through
the same place". This wording might be interpreted to permit
peer-to-peer distribution of binaries *if* they are packaged together
with the CCS, but such packaging is impractical, for at least three
reasons. First, even if the CCS is packaged with the object code, it
will only be available to a non-seeding peer at the end of the
distribution process, but the peer will already have been providing
parts of the binary to others in the network. Second, in practice,
peer-to-peer forms of transmission are poorly suited means for
distributing CCS. In large distributions, packaging CCS with the
object code may result in a substantial increase in file size and
transmission time. Third, in current practice, CCS packages themselves
tend *not* to be transmitted through BitTorrent --- owing to reduced
demand -- thus, there generally will be too few participants
downloading the same source package at the same time to enable
effective seeding and

distribution.

GPLv3 6(e) addresses these issues. If a licensee conveys such a work
of object code using peer-to-peer transmission, that licensee is in
compliance with GPLv3 6 if the licensee informs other peers where the
object code and its CCS are publicly available at no charge under
subsection GPLv3 6(d). The CCS therefore need not be provided through
the peer-to-peer system that was used for providing the binary.

Second, GPLv3 9 also clarifies that ancillary propagation of a covered
work that occurs as part of the process of peer-to-peer file
transmission does not require acceptance, just as mere receipt and
execution of the Program does not require acceptance. Such ancillary
propagation is permitted without limitation or further obligation.

### User Products, Installation Information and Device Lock-Down

As discussed in [9.5](#gplv3s-views-on-drm-and-device-lock-down) of
this tutorial, GPLv3 seeks to thwart technical measures such as
signature checks in hardware to prevent modification of GPL'd software
on a device.

To address this issue, GPLv3 6 requires that parties distributing
object code provide recipients with the source code through certain
means. When those distributors pass on the CCS, they are also required
to pass on any information or data necessary to install modified
software on the particular device that included it. (This strategy is
not unlike that used in LGPLv2.1 to enable users to link proprietary
programs to modified libraries.)

#### User Products

The scope of these requirements is narrow. GPLv3 6 introduces the
concept of a "User Product", which includes devices that are sold for
personal, family, or household use. Distributors are only required to
provide Installation Information when they convey object code in a
User Product.

In brief, the right to convey object code in a defined class of "User
Products," under certain circumstances, depends on providing whatever
information is required to enable a recipient to replace the object
code with a functioning modified version.

This was a compromise that was difficult for the FSF to agree to
during the GPLv3 drafting process. However, companies and governments
that use specialized or enterprise-level computer facilities reported
that they actually *want* their systems not to be under their own
control. Rather than agreeing to this as a concession, or bowing to
pressure, they ask for this as a *preference*. It is not clear that
the GPL should interfere here, since the main problem lies elsewhere.

While imposing technical barriers to modification is wrong regardless
of circumstances, the areas where restricted devices are of the
greatest practical concern today fall within the User Product
definition. Most, if not all, technically-restricted devices running
GPL-covered programs are consumer electronics devices. Moreover, the
disparity in clout between the manufacturers and these users makes it
difficult for the users to reject technical restrictions through their
weak and unorganized market power. Even limited to User Products, this
provision addresses the fundamental problem.

The core of the User Product definition is a subdefinition of
"consumer product" adapted from the Magnuson-Moss Warranty Act, a
federal consumer protection law in the USA found in 15 USC 2301: "any
tangible personal property which is normally used for personal,
family, or household purposes." The USA has had three decades of
experience of liberal judicial and administrative interpretation of
this definition in a manner favorable to consumer
rights.[^6^](#_bookmark120) Ideally, this body of
interpretation[^7^](#_bookmark121) will guide interpretation of the
consumer product subdefinition in GPLv3 6, and this will hopefully
provide a degree of legal certainty advantageous to device
manufacturers and downstream licensees alike.

One well-established interpretive principle under Magnuson-Moss is
that ambiguities are resolved in favor of coverage. That is, in cases
where it is not clear whether a product falls under the definition of
consumer product, the product will be treated as a consumer
product.[^8^](#_bookmark122) Moreover, for a given product, "normally
used" is understood to refer to the typical use of that type of
product, rather than a particular use by

^6^[]{#_bookmark120 .anchor}The Magnuson-Moss consumer product
definition itself has been influential in the USA and Canada, having
been adopted in []{#_bookmark121 .anchor}several state and provincial
consumer protection laws.

^7^The FSF, however, was very clear that incorporation of such legal
interpretation was in no way intended to work as a []{#_bookmark122
.anchor}general choice of USA law for GPLv3.

816 CFR *§* 700.1(a); *McFadden v. Dryvit Systems, Inc.*, 54 UCC Rep.
Serv.2d 934 (D. Ore. 2004).

a particular buyer. Products that are commonly used for personal as
well as commercial purposes are consumer products, even if the person
invoking rights is a commercial entity intending to use the product
for commercial purposes.[^9^](#_bookmark124) Even a small amount of
"normal" personal use is enough to cause an entire product line to be
treated as a consumer product under
Magnuson-Moss.[^10^](#_bookmark125)

However, Magnuson-Moss is not a perfect fit because in the area of
components of dwellings, the settled interpretation under
Magnuson-Moss is under-inclusive. Depending on how such components are
manufac- tured or sold, they may or may not be considered
Magnuson-Moss consumer products.[^11^](#_bookmark126) Therefore, GPLv3
defines User Products as a superset of consumer products that also
includes "anything designed or sold for incorporation into a
dwelling."

Thus, the three sentences in the center of GPLv3's User Product
definition encapsulate the judicial and administrative principles
established over the past three decades in the USA concerning the
Magnuson-Moss consumer product definition. First, it states that
doubtful cases are resolved in favor of coverage under the definition.
Second, it indicates that the words "normally used" in the consumer
product definition refer to a typical or common use of a class of
product, and not the status of a particular user or expected or actual
uses by a particular user. Third, it clearly states that the existence
of substantial non-consumer uses of a product does not negate a
determination that it is a consumer product, unless such non-consumer
uses represent the only significant mode of use of that product.

It should be clear from these added sentences that it is the general
mode of use of a product that determines objectively whether or not it
is a consumer product. One could not escape the effects of the User
Products provisions by labeling what is demonstrably a consumer
product in ways that suggest it is "for professionals", for example.

#### Installation Information

With the User Products definition complete, the "Installation
Information" definition uses that to define what those receiving
object code inside a User Product must receive.

Installation Information is information that is "required to install
and execute modified versions of a covered work . . . from a modified
version of its" CCS, in the same User Product for which the covered
work is conveyed. GPLv3 provides guidance concerning how much
information must be provided: it "must suffice to ensure that the
continued functioning of the modified object code is in no case
prevented or interfered with solely because modification has been
made." For example, the information provided would be insufficient if
it enabled a modified version to run only in a disabled fashion,
solely because of the fact of modification (regardless of the actual
nature of the modification). The information need not consist of
cryptographic keys; Installation Information may be "any methods,
procedures, authorization keys, or other information". Note that GPLv3
does not define "continued functioning" further. However, GPLv3 does
provide some additional guidance concerning the scope of
GPLv3-compliant action or inaction that distributors of
technically-restricted User Products can take with respect to a
downstream recipient who replaces the conveyed object code with a
modified version. First of all, GPLv3 makes clear that GPLv3 implies
no

obligation "to continue to provide support service, warranty, or
updates" for such a work.

Second, most technically-restricted User Products are designed to
communicate across networks. It is important for both users and
network providers to know when denial of network access to devices
running modified versions becomes a GPL violation. GPLv3 permits
denial of access in two cases: "when the modification itself
materially and adversely affects the operation of the network," and
when the modification itself "violates the rules and protocols for
communication across the network". The second case is deliberately
drawn in general terms, and it serves as a foundation for reasonable
enforcement policies that respect recipients' right to modify while
recognizing the legitimate interests of network providers.

^9^[]{#_bookmark124 .anchor}16 CFR 700.1(a). Numerous court decisions
interpreting Magnuson-Moss are in accord; see, e.g., *Stroebner
Motors, Inc.* []{#_bookmark125 .anchor}*v. Automobili Lamborghini
S.p.A.*, 459 F. Supp.2d 1028, 1033 (D. Hawaii 2006).

^10^*Tandy Corp. v. Marymac Industries, Inc.*, 213 U.S.P.Q. 702 (S.D.
Tex. 1981). In this case, the court concluded that TRS-80
microcomputers were consumer products, where such computers were
designed and advertised for a variety of users, []{#_bookmark126
.anchor}including small businesses and schools, and had only recently
been promoted for use in the home.

^11^Building materials that are purchased directly by a consumer from
a retailer, for improving or modifying an existing dwelling, are
consumer products under Magnuson-Moss, but building materials that are
integral component parts of the structure of a dwelling at the time
that the consumer buys the dwelling are not consumer products. 16
C.F.R. 700.1(c)--(f); Federal Trade Commission, Final Action
Concerning Review of Interpretations of Magnuson-Moss Warranty Act, 64
Fed. Reg. 19,700 (April 22, 1999); see also, e.g., *McFadden*, 54
U.C.C. Rep. Serv.2d at 934.

Note that GPLv3 permits the practice of conveying object code in a
mode not practically susceptible to modification by any party, such as
code burned in ROM or embedded in silicon. The goal of the
Installation Information requirement is to ensure the downstream
licensee receives the real right to modify when the device
manufacturer or some other party retains that right. Accordingly,
GPLv3 6's ante-penultimate paragraph states that the requirement to
provide Installation Information "does not apply if neither you nor
any third party retains the ability to install modified object code on
the User Product".

Finally, GPLv3 6 makes it clear that there is also no requirement to
provide warranty or support for the User Product itself.

### GPLv3 §7: Additional Permissions

The GPL is a statement of permissions, some of which have conditions.
Additional terms --- terms that supplement those of the GPL --- may
come to be placed on, or removed from, GPL-covered code in certain
common ways. Copyleft licensing theorists have generally called those
added terms "additional permissions" if they grant exceptions from the
conditions of the GPL, and "additional requirements" if they add
conditions to the basic permissions of the GPL. The treatment of
additional permissions and additional requirements under GPLv3 is
necessarily asymmetrical, because they do not raise the same
interpretive issues; in particular, additional requirements, if
allowed without careful limitation, could transform a GPL'd program
into a non- free one.

Due to the latter fear, historically, GPLv2 did not permit any
additional requirements. However, over time, many copyright holders
generally tolerated certain types of benign additional requirements
merely through a "failure to enforce" estoppel-esque scenario.
Therefore, GPLv3 allows for some specific limited requirement
variations that GPLv2 technically prohibits.

With these principles in the background, GPLv3 *§*7 answers the
following questions:

1.  How does the presence of additional terms on all or part of a GPL'd
    > program affect users' rights?

2.  When and how may a licensee add terms to code being distributed
    > under the GPL?

3.  When may a licensee remove additional terms?

Additional permissions present the easier case. Since the mid-1990s,
permissive exceptions often appeared alongside GPLv2 to allow
combination with certain non-free code. Typically, downstream stream
recipients could remove those exceptions and operate under pure GPLv2.
Similarly, LGPLv2.1 is in essence a permissive variant of GPLv2, and
it permits relicensing under the GPL.

These practices are now generalized via GPLv3 7. A licensee may remove
any additional permission from a covered work, whether it was placed
by the original author or by an upstream distributor. A licensee may
also add any kind of additional permission to any part of a work for
which the licensee has, or can give, appropriate copyright permission.
For example, if the licensee has written that part, the licensee is
the copyright holder for that part and can therefore give additional
permissions that are applicable to it. Alternatively, the part may
have been written by someone else and licensed, with the additional
permissions, to that licensee. Any additional permissions on that part
are, in turn, removable by downstream recipients. As GPLv3 7 1
explains, the effect of an additional permission depends on whether
the permission applies to the whole work or a part.

Indeed, LGPLv3 is itself simply a list of additional permissions
supplementing the terms of GPLv3. GPLv3 7 has thus provided the basis
for recasting a formally complex license as an elegant set of added
terms, without changing any of the fundamental features of the
existing LGPL. LGPLv3 is thus a model for developers wishing to
license their works under the GPL with permissive exceptions. The
removability of additional permissions under GPLv3 7 does not alter
any existing behavior of the LGPL since the LGPL has always allowed
relicensing under the ordinary GPL.

## GPLv3 §7: Understanding License Compatibility

A challenge that faced the Free Software community heavily through out
the early 2000s was the proliferation of incompatible Free Software
licenses. Of course, the GPL cannot possibly be compatible with all
such

licenses. However, GPLv3 contains provisions that are designed to
reduce license incompatibility by making it easier for developers to
combine code carrying non-GPL terms with GPL'd code.

This license compatibility issue arises for three reasons. First, the
GPL is a strong copyleft license, requiring modified versions to be
distributed under the GPL. Second, the GPL states that no further
restrictions may be placed on the rights of recipients. Third, all
other software freedom respecting licenses in common use contain
certain requirements, many of which are not conditions made by the
GPL. Thus, when GPL'd code is modified by combination with code
covered by another formal license that specifies other requirements,
and that modified code is then distributed to others, the freedom of
recipients may be burdened by additional requirements in violation of
the GPL. It can be seen that additional permissions in other licenses
do not raise any problems of license compatibility.

GPLv3 took a new approach to the issue of combining GPL'd code with
code governed by the terms of other software freedom licenses.
Traditional GPLv2 license compatibility theory (which was not
explicitly stated in GPLv2 itself, but treated as a license
interpretation matter by the FSF) held that GPLv2 allowed such
combinations only if the non-GPL licensing terms permitted
distribution under the GPL and imposed no restrictions on the code
that were not also imposed by the GPL. In practice, the FSF
historically supplemented that policy with a structure of exceptions
for certain kinds of combinations.

GPLv3 7 implements a more explicit policy on license compatibility. It
formalizes the circumstances under which a licensee may release a
covered work that includes an added part carrying non-GPL terms. GPLv3
7 distinguish between terms that provide additional permissions, and
terms that place additional requirements on the code, relative to the
permissions and requirements established by applying the GPL to the
code.

As discussed in the previous section of this tutorial, GPLv3 7 first
and foremost explicitly allows added parts covered by terms with
additional permissions to be combined with GPL'd code. This codifies
the existing practice of regarding such licensing terms as compatible
with the GPL. A downstream user of a combined GPL'd work who modifies
such an added part may remove the additional permissions, in which
case the broader permissions no longer apply to the modified version,
and only the terms of the GPL apply to it.

In its treatment of terms that impose additional requirements, GPLv3 7
extends the range of licensing terms with which the GPL is compatible.
An added part carrying additional requirements may be combined with
GPL'd code, but only if those requirements belong to a set enumerated
in GPLv3 7. There are, of course, limits on the acceptable additional
requirements, which ensures that enhanced license compatibility does
not defeat the broader software-freedom-defending terms of the GPL.
Unlike terms that grant additional permissions, terms that impose
additional requirements cannot be removed by a downstream user of the
combined GPL'd work, because only in the pathological
case[^12^](#_bookmark129) would a user have the right to do so.

In general, the types of additional requirements were those terms in
regular use by other non-copyleft Free Software licenses that the FSF
found unobjectionable. The specific details GPLv3's permitted
additional requirements hat GPLv3 are as follows:

7(a): This provision allows alternative "disclaimer of warranty"
forms. Copyright holders can disclaim warranty or limit liability
differently from the terms as provided under GPLv3 15--16. Drafters
included this permission to advance the internationalization goals of
GPLv3; international treaties lack adequate harmonization for laws
regarding warranty and disclaimer.

7(b): This provision allows alternative requirements for preservation
of appropriate legal notices. GPLv3 permits additional requirements
regarding preservation of legal notices, including on output from exe-
cution of covered works. Preserved information can include information
about the origins of the code or alterations of the code.

7(c): This provision allows prohibition of misrepresentation of
original material. The provision yields com- patibility with
non-copyleft Free Software licenses that require marking of modified
versions in "rea- sonable"ways which differ from GPL's own precise
marking requirements.

7(d): This provision allows limitations on the use of names of
licensor for publicity purposes. This provision also yields additional
compatibility with non-copyleft Free Software licenses that prohibit
the use of

^12^[]{#_bookmark129 .anchor}Theoretically, a user could collect
copyright assignment from all known contributors and then do this, but
this would indeed be the pathological case.

the licensor's name on unmodified versions (or other prohibitions on
advertising rights). The third clause of the [3-Clause BSD
License,](http://opensource.org/licenses/BSD-3-Clause) for example,
long considered de-facto compatible with GPLv2 anyway, is via this
clause unequivocally compatible with GPLv3. However, [this clause
*does not*
make](https://www.gnu.org/licenses/license-list.html#OriginalBSD) [GPL
compatible with the old BSD advertising
clause](https://www.gnu.org/licenses/license-list.html#OriginalBSD)
that the FSF [long ago identified as
problematic.](https://www.gnu.org/philosophy/bsd.html)

7(e): This provision clarifies that refusal to grant trademark rights
for a GPLv3'd covered work remains compatible with GPLv3. Again, some
non-copyleft permissive licenses include such clauses.

7(f): This provision allows indemnification requirements of authors
and licensors. The FSF specifically designed this clause to achieve
GPLv3 compatibility for the [Apache Software License, Version
2.0.](http://www.apache.org/licenses/LICENSE-2.0.html)

During the GPLv3 drafting process, some questioned the necessity of
GPLv3 7; those critics suggested that it creates complexity that did
not previously exist. However, by the time of GPLv3's drafting, many
existing GPLv2'd software packages already combined with various
non-copylefted Free Software licensed code that carried such
additional terms. Therefore, GPLv3 7 is rationalized existing
practices of those package authors and modifiers, since it sets clear
guidelines regarding the removal and addition of these additional
terms. With its carefully limited list of allowed additional
requirements, GPLv3 7 accomplishes additional objectives as well,
since it permits the expansion of the base of code available for GPL
developers, while also encouraging useful experimentation with
requirements the GPLv3 does not include by default.

However, any other non-permissive additional terms apart from those
stated above are considered "fur- ther" restrictions which [GPLv3
10](#gplv3-10-explicit-downstream-license) prohibits. Furthermore, as
a compliance matter, if you add additional terms in accordance with
GPLv3 7, you must ensure that the terms are placed in the relevant
source files or provide a conspicuous notice about where to find the
additional terms.

## GPLv3 §8: A Lighter Termination

GPLv2 provided for automatic termination of the rights of a person who
copied, modified, sublicensed, or distributed a work in violation of
the license. Automatic termination can be too harsh for those who have
committed an inadvertent violation, particularly in cases involving
distribution of large collections of software having numerous
copyright holders. A violator who resumes compliance with GPLv2
technically needs to obtain forgiveness from all copyright holders,
and even contacting them all might be impossible.

GPLv3 8 now grants opportunities for provisional and permanent
reinstatement of rights. The termi- nation procedure provides a
limited opportunity to cure license violations. If a licensee has
committed a first-time violation of the GPL with respect to a given
copyright holder, but the licensee cures the violation within 30 days
following receipt of notice of the violation, then any of the
licensee's GPL rights that have been terminated by the copyright
holder are "automatically reinstated".

Finally, if a licensee violates the GPL, a contributor may terminate
any patent licenses that it granted under GPLv3 *§*11, in addition to
any copyright permissions the contributor granted to the licensee.

## GPLv3 §9: Acceptance

GPLv3 9 means what it says: mere receipt or execution of code neither
requires nor signifies contractual acceptance under the GPL. Speaking
more broadly, GPLv3 is intentionally structured as a unilateral grant
of copyright permissions, the basic operation of which exists outside
of any law of contract. Whether and when a contractual relationship is
formed between licensor and licensee under local law do not
necessarily matter to the working of the license.

## GPLv3 §10: Explicit Downstream License

GPLv3 10 is a generally straightforward section that ensures that
everyone downstream receives licenses from all copyright holders. Each
time you redistribute a GPL'd program, the recipient automatically
receives a license, under the terms of GPL, from every upstream
licensor whose copyrighted material is present in

the work you redistribute. You could think of this as creating a
three-dimensional rather than linear flow of license rights. Every
recipient of the work is "in privity," or is directly receiving a
license from every licensor. This mechanism of automatic downstream
licensing is central to copyleft's function. Every licensor in-
dependently grants licenses, and every licensor independently
terminates the license on violation. Parties further downstream from
the infringing party remain licensed, so long as they don't themselves
commit infringing actions. Their licenses come directly from all the
upstream copyright holders, and are not depen- dent on the license of
the breaching party who distributed to them. For the same reason, an
infringer who acquires another copy of the program has not thereby
acquired any new license rights: once any upstream licensor of that
program has terminated the license for breach of its terms, no new
automatic license will

issue to the recipient just by acquiring another
copy[^13^](#_bookmark134)

Meanwhile, one specific addition in GPLv3 here in GPLv3 10 deserves
special mention. Specifically, GPLv3 removed the words "at no charge"
from GPLv2 2(b) (which, BTW, became GPLv3 5(b)) because it contributed
to a misconception that the GPL did not permit charging for
distribution of copies. The purpose of the "at no charge" wording was
to prevent attempts to collect royalties from third parties. The
removal of these words created the danger that the imposition of
licensing fees would no longer be seen as a license violation.
Therefore, GPLv3 10 adds a new explicit prohibition on imposition of
licensing fees or royalties. This section is an appropriate place for
such a clause, since it is a specific consequence of the general
requirement that no further restrictions be imposed on downstream
recipients of GPL-covered code.

## GPLv3 §11: Explicit Patent Licensing

Software patenting is a harmful and unjust policy, and should be
abolished; recent experience makes this all the more evident. Since
many countries grant patents that can apply to and prohibit software
packages, in various guises and to varying degrees, GPLv3 seeks to
protect the users of GPL-covered programs from those patents, while at
the same time making it feasible for patent holders to contribute to
and distribute GPL-covered programs as long as they do not attack the
users of those programs.

It is generally understood that GPLv2 implies some limits on a
licensee's power to assert patent claims against the use of
GPL-covered works. However, the patent licensing practice that GPLv2 7
(corresponding to GPLv3 12) is designed to prevent is only one of
several ways in which software patents threaten to make free programs
non-free and to prevent users from exercising their rights under the
GPL. GPLv3 takes a more comprehensive approach to combating the danger
of patents.

GPLv2 7 has seen some success in deterring conduct that would
otherwise result in denial of full downstream enjoyment of GPL rights,
and thus it is preserved in GPLv3 12. Experience has shown that more
is necessary, however, to ensure adequate community safety where
companies act in concert to heighten the anticompetitive use of
patents that they hold or license.

Therefore, GPLv3 is designed to reduce the patent risks that distort
and threaten the activities of users who make, run, modify and share
Free Software. At the same time, GPLv3 gives favorable consideration
to practical goals such as certainty and administrability for patent
holders that participate in distribution and development of
GPL-covered software. GPLv3's policy requires each such patent holder
to provide appropriate levels of patent assurance to users, according
to the nature of the patent holder's relationship to the program.

In general, GPLv3 provides for two classes of patent commitments:

Grant of license to claims in contributor versions: GPLv3 11
introduces an affirmative grant of rights to patent claims by those
who contribute code to GPL'd programs. The intent is to prevent
parties from aggressively asserting patents against users of code
those parties have themselves modified --- in theory preventing
betrayal by "insiders" of the copyleft community. A contributor's
patent claims necessarily infringed by the version of the program
created by the incorporation of its modifications are licensed to all
subsequent users and modifiers of the program, or programs based on
the program. No patent claims only infringed by subsequent
modifications by other parties are thus licensed. Patent claims
acquired after the making of the "contributor version" necessarily
infringed by that version are also licensed by this provision at the
time of their acquisition or perfection.

^13^[]{#_bookmark134 .anchor}Footnote [3](#_bookmark77) also applies
here in discussion of GPLv3 just as it did in discussion of GPLv2.

Prohibition of enforcement of patent claims against those to whom you
distribute: GPLv3 10 makes explicit that licensees who directly
distribute may not make demands for acceptance of patent licenses or
payment of patent royalties from distribution recipients. This
provision establishes a uniform rule of patent exhaustion with respect
to GPL'd programs regardless of the domestic patent law in any
particular system or locale.

The following two subsections discuss in order each of the above
mentioned classes of patent commitments.

### The Contributor's Explicit Patent License

Specifically, the ideal might have been for GPLv3 to feature a patent
license grant triggered by all acts of distribution of GPLv3-covered
works. The FSF considered it during the GPLv3 drafting process, but
many patent-holding companies objected to this policy. They have made
two objections: (1) the far-reaching impact of the patent license
grant on the patent holder is disproportionate to the act of merely
distributing code without modification or transformation, and (2) it
is unreasonable to expect an owner of vast patent assets to exercise
requisite diligence in reviewing all the GPL-covered software that it
provides to others. Some expressed particular concern about the
consequences of "inadvertent" distribution.

The argument that the impact of the patent license grant would be
"disproportionate", that is to say unfair, is not valid. Since
software patents are weapons that no one should have, and using them
for aggression against free software developers is an egregious act
(thus preventing that act cannot be unfair).

However, the second argument seems valid in a practical sense. A
typical GNU/Linux distribution includes thousands of programs. It
would be quite difficult for a re-distributor with a large patent
portfolio to review all those programs against that portfolio every
time it receives and passes on a new version of the distribution.
Moreover, this question raises a strategic issue. If the GPLv3 patent
license requirements convince patent-holding companies to remain
outside the distribution path of all GPL-covered software, then these
requirements, no matter how strong, will cover few patents.

GPLv3 therefore makes a partial concession which would lead these
companies to feel secure in doing the distribution themselves. GPLv3
11 applies only to those distributors that have modified the program.
The other changes we have made in sections 10 and 11 provide
strengthened defenses against patent assertion and compensate partly
for this concession.

Therefore, GPLv3 11 introduces the terms "contributor", "contributor
version", and "essential patent claims", which are used in the GPLv3
11 3. Viewed from the perspective of a recipient of the Program,
contributors include all the copyright holders for the Program, other
than copyright holders of material originally licensed under non-GPL
terms and later incorporated into a GPL-covered work. The contributors
are therefore the initial GPLv3 licensors of the Program and all
subsequent upstream licensors who convey, under the terms of GPLv3 5,
modified covered works. Thus, the "contributor version" includes the
material the contributor has copied from the upstream version that the
contributor has modified. GPLv3 11 3 does not apply to those that
redistribute the program without change.[^14^](#_bookmark136) In other
words, the "contributor version" includes not just the material added
or altered by the contributor, but also the pre-existing material the
contributor copied from the upstream version and retained in the
modified version. (GPLv3's usage of "contributor" and "contribution"
should not be confused with the various other ways in which those
terms are used in certain other free software
licenses.[^15^](#_bookmark137))

Some details of the "essential patent claims" definition deserve
special mention. "Essential patent claims", for a given party, are a
subset of the claims "owned or controlled" by the party. They do
include sublicensable claims that have been licensed to the
contributor by a third party.[^16^](#_bookmark138) Most commercial
patent license agreements that permit sublicensing do so under
restrictive terms that are inconsistent with the requirements of the
GPL. For example, some patent licenses allow the patent licensee to
sublicense but require collection of royalties from any sublicensees.
The patent licensee could not distribute a GPL-covered program and
grant the recipient a patent sublicense for the program without
violating section 12 of GPLv3.[^17^](#_bookmark139) In rare cases,

^14^[[]{#_bookmark137 .anchor}]{#_bookmark136 .anchor}An implied
patent license from the distributor, however, often arises. See
[6](#_bookmark68) in this tutorial

^15^Cf., e.g., Apache License, version 2.0, section 1; Eclipse Public
License, version 1.0, section 1; Mozilla Public License,
v[]{#_bookmark138 .anchor}ersion 1.1, section 1.1.

^16^This issue is typically handled in other software freedom licenses
having patent licensing provisions by use of the unhelpful
[]{#_bookmark139 .anchor}term "licensable," which is either left
undefined or is given an ambiguous definition.

^17^GPLv3 also provides an example in section 12 that makes this point
clear.

however, a conveying party can freely grant patent sublicenses to
downstream recipients without violating the GPL.

Additionally, "essential patent claims" are those patents "that would
be infringed by some manner, permitted by this License, of making,
using, or selling the work". This intends to make clear that a patent
claim is "essential" if some mode of usage would infringe that claim,
even if there are other modes of usage that would not infringe.

Finally, "essential patent claims . . . do not include claims that
would be infringed only as a consequence of further modification of
the work." The set of essential patent claims licensed is fixed by the
particular version of the work that was contributed. The claim set
cannot expand as a work is further modified downstream. (If it could,
then any software patent claim would be included, since any software
patent claim can be infringed by some further modification of the
work.)[^18^](#_bookmark141)

Ideally, this contributor patent policy will result in fairly frequent
licensing of patent claims by contrib- utors. A contributor is charged
with awareness of the fact that it has modified a work and provided it
to others; no act of contribution should be treated as inadvertent.
GPLv3's rule also requires no more work, for a contributor, than the
weaker rule proposed by the patent holders. Under their rule, the
contributor must always compare the entire work against its patent
portfolio to determine whether the combination of the modifications
with the remainder of the work cause it to read on any of the
contributor's patent claims.

Finally, GPLv3's explicit patent license for contributors has an
interesting and useful side effect. When a company with a large number
of such claims acquires the program's modifier, all claims held or
thereafter acquired by the purchaser are automatically licensed under
this provision. For example, Microsoft's acqui- sition of Nokia
resulted in the automatic licensing of all Microsoft patent claims now
or hereafter acquired which read on any contributor version of any
GPLv3 program ever modified by Nokia.

### Conveyors' Patent Licensing

The remaining patent licensing in GPLv3 deals with patent licenses
that are granted by conveyance. The licensing is not as complete or
far reaching as the contributor patent licenses discussed in the
preceding section.

The term "patent license," as used in GPLv3 11 4--6, is not meant to
be confined to agreements formally identified or classified as patent
licenses. GPLv3 11 3 makes this clear by defining "patent license,"
for purposes of the subsequent three paragraphs, as "any express
agreement or commitment, however denomi- nated, not to enforce a
patent (such as an express permission to practice a patent or covenant
not to sue for patent infringement)"

GPLv3 11 5 is commonly called GPLv3's downstream shielding provision.
It responds particularly to the problem of exclusive deals between
patent holders and distributors, which threaten to distort the free
software distribution system in a manner adverse to developers and
users. The fundamental idea is to make a trade-off between assuring a
patent license for downstream and making (possibly patent-encumbered)
CCS publicly available.

Simply put, in nearly all cases in which the "knowingly relying" test
is met, the patent license will indeed not be sublicensable or
generally available to all on free terms. If, on the other hand, the
patent license is generally available under terms consistent with the
requirements of the GPL, the distributor is automatically in
compliance, because the patent license has already been extended to
all downstream recipients. Finally, if the patent license is
sublicensable on GPL-consistent terms, the distributor may choose to
grant sublicenses to downstream recipients instead of causing the CCS
to be publicly available. (In such a case, if the distributor is also
a contributor, it will already have granted a patent sublicense
anyway, and so it need not do anything further to comply with the
third paragraph.)

Admittedly, public disclosure of CCS is not necessarily required by
other sections of the GPL, and the FSF in drafting GPLv3 did not
necessarily wish to impose a general requirement to make source code
available to all, which has never been a GPL condition. However, many
vendors who produce products that include copylefted software, and who
are most likely to be affected by the downstream shielding provision,
lobbied for the addition of the source code availability option, so it
remains.

^18^[]{#_bookmark141 .anchor}However, "the work" should not be
understood to be restricted to a particular mechanical affixation of,
or medium for distributing, a program, where the same program might be
provided in other forms or in other ways that may be captured by other
patent claims held by the contributor.

Meanwhile, two specific alternatives to the source code availability
option are also available. The dis- tributor may comply by disclaiming
the patent license it has been granted for the conveyed work, or by
arranging to extend the patent license to downstream
recipients.[^19^](#_bookmark143) The GPL is intended to permit private
distribution as well as public distribution, and the addition of these
options ensures that this remains the case, even though it remains
likely that distributors in this situation will usually choose the
source code availability option.

Note that GPLv3 11 5 is activated only if the CCS is not already
otherwise publicly available. (Most often it will, in fact, already be
available on some network server operated by a third party.) Even if
it is not already available, the option to "cause the Corresponding
Source to be so available" can then be satisfied by verifying that a
third party has acted to make it available. That is to say, the
affected distributor need not itself host the CCS to take advantage of
the source code availability option. This subtlety may help the
distributor avoid certain peculiar assumptions of liability.

Note that GPLv3 11 6--7 are designed to stop distributors from
colluding with third parties to offer selective patent protection.
GPLv3 is designed to ensure that all users receive the same rights;
arrangements that circumvent this make a mockery of free software, and
we must do everything in our power to stop them. First, GPLv3 11 6
states that any license that protects some recipients of GPL'd
software must be extended to all recipients of the software. If
conveyors arrange to provide patent protection to some of the people
who get the software from you, that protection is automatically
extended to everyone who receives

the software, no matter how they get it.

Second, GPLv3 11 7 prohibits anyone who made such an agreement from
distributing software released under GPLv3. Conveyors are prohibited
from distributing software under GPLv3 if the conveyor makes an
agreement of that nature in the future.

The date in GPLv3 11 7 likely seems arbitrary to those who did not
follow the GPLv3 drafting process. This issue was hotly debated during
the drafting of GPLv3, but ultimately one specific deal of this type
--- a deal between Microsoft and Novell for Microsoft to provide
so-called "coupons" to Microsoft customers to redeem for copies of
Novell's GNU/Linux distribution with a Microsoft patent license -- was
designed to be excluded.

The main reason for this was a tactical decision by the FSF. FSF
believed they can do more to protect the community by allowing Novell
to use software under GPLv3 than by forbidding it to do so. This is
because of paragraph 6 of section 11 (corresponding to paragraph 4 in
Draft 3). It will apply, under the Microsoft/Novell deal, because of
the coupons that Microsoft has acquired that essentially commit it to
participate in the distribution of the Novell SLES GNU/Linux system.

The FSF also gave a secondary reason: to avoid affecting other kinds
of agreements for other kinds of activities. While GPLv3 sought to
distinguish pernicious deals of the Microsoft/Novell type from
business conduct that is not particularly harmful, the FSF also did
not assume success in that drafting, and thus there remained some risk
that other unchangeable past agreements could fall within the scope of
GPLv3 11 7. In future deals, distributors engaging in ordinary
business practices can structure the agreements so that they do not
fall under GPLv3 *§*11*¶*7.

## GPLv3 §12: Familiar as GPLv2 §7

GPLv2 12 remains almost completely unchanged from the text that
appears in GPLv2 7. This is an important provision that ensures a
catch-all to ensure that nothing "surprising" interferes with the
continued conveyance safely under copyleft.

The wording in the first sentence of GPLv3 12 has been revised
slightly to clarify that an agreement -- such as a litigation
settlement agreement or a patent license agreement -- is one of the
ways in which conditions may be "imposed" on a GPL licensee that may
contradict the conditions of the GPL, but which do not excuse the
licensee from compliance with those conditions. This change codifies
the historical interpretation of GPLv2.

GPLv3 removed the limited severability clause of GPLv2 7 as a matter
of tactical judgment, believing that this is the best way to ensure
that all provisions of the GPL will be upheld in court. GPLv3 also

^19^[]{#_bookmark143 .anchor}The latter option, if chosen, must be
done "in a manner consistent with the requirements of this License";
for example, it is unavailable if extension of the patent license
would result in a violation of GPLv3 *§*12.

removed the final sentence of GPLv2 section 7, which the FSF consider
to be unnecessary.

## GPLv3 §13: The Great Affero Compromise

The Affero GPL was written with the expectation that its additional
requirement would be incorporated into the terms of GPLv3 itself. Many
software freedom advocates, including some authors of this tutorial,
advocated heavily for that, and fully expected it to happen.

The FSF, however, chose not to include the Affero clause in GPLv3, due
to what it called "irreconcilable views from different parts of the
community". Many commercial users of Free Software were opposed to the
inclusion of a mandatory Affero-like requirement in the body of GPLv3
itself. In fact, some wealthier companies even threatened to
permanently fund forks of many FSF copyrighted-programs under GPLv2 if
the Affero clause appeared in GPLv3.

Meanwhile, there was disagreement even among copyleft enthusiasts
about the importance of the pro- vision. A coalition never formed, and
ultimately the more powerful interests implicitly allied with the
companies who deeply opposed the Affero clause such that the FSF felt
the Affero clause would need its own license, but one compatible with
GPLv3.

GPLv3 13 makes GPLv3 compatible with the AGPLv3, so that at least code
can be shared between AGPLv3'd and GPLv3'd projects, even if the
Affero clause does not automatically apply to all GPLv3'd works.

Meanwhile, those who criticize the permission to link with code under
the Affero GPL should recognize that most other free software licenses
also permit such linking. In particular, when a combined work is made
by linking GPLv3-covered code with AGPLv3-covered code, the copyleft
on one part will not extend to the other part. In such combinations,
the Affero requirement will apply only to the part originally brought
into the combination under the Affero license. In theory, those who
receive such a combination and do not wish to use code under the
Affero requirement may remove the Affero-covered portion of the
combination. (Admittedly, in practice, de-mingling of combined code
can be technically difficult.)

## GPLv3 §14: So, When's GPLv4?

No substantive change has been made in section 14. The wording of the
section has been revised slightly to make it clearer.

It's unclear when the FSF might consider publishing GPLv4. However,
this section makes it clear that the FSF is the sole authority who can
decide such.

The main addition to this section allows a third-party proxy to be
appointed by contributors who wish someone else to make relicensing to
new versions of GPL when they are released. This is a "halfway" point
between using "-only" or "-or-later" by consolidating the
decision-making on that issue to a single authority.

## GPLv3 §15--17: Warranty Disclaimers and Liability Limita- tion

No substantive changes have been made in sections 15 and 16.

Finally, the FSF shortened the section on "How to Apply These Terms to
Your New Programs" to just the bare essentials.

