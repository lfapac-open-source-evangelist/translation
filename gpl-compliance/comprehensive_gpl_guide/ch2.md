
[]{#_bookmark27 .anchor}**CHAPTER 2**

A TALE OF TWO COPYLEFT LICENSES

While determining the proper methodology and criteria to yield an
accurate count remains difficult, the GPL is generally considered one
of the most widely used Free Software licenses. For most of its
history --- for 16 years from June 1991 to June 2007 --- there was
really only one version of the GPL, version 2.

However, the GPL had both earlier versions before version 2, and, more
well known, a revision to version

3\.

## Historical Motivations for the General Public License

The earliest license to grant software freedom was likely the Berkeley
Software Distribution ("BSD") license. This license is typical of what
are often called lax, highly permissive licenses. Not unlike software
in the public domain, these non-copyleft licenses (usually) grant
software freedom to users, but they do not go to any effort to uphold
that software freedom for users. The so-called "downstream" (those who
receive the software and then build new things based on that software)
can restrict the software and distribute further. The GNU's Not Unix
("GNU") project, which Richard M. Stallman ("RMS") founded in 1984 to
make a complete Unix-compatible operating system implementation that
assured software freedom for all. However, RMS saw that using a
license that gave but did not assure software freedom would be counter
to the goals of the GNU Project. RMS invented "copyleft" as an answer
to that problem, and began using various copyleft

licenses for the early GNU Project programs.[^1^](#_bookmark30)

## Proto-GPLs And Their Impact

The earliest copyleft licenses were specific to various GNU programs.
For example, The Emacs General Public License was likely the first
copyleft license ever published. Interesting to note that even this
earliest copyleft license contains a version of the well-known GPL
copyleft clause:

You may modify your copy or copies of GNU Emacs . . . provided that
you also . . . cause the whole of any work that you distribute or
publish, that in whole or in part contains or is a derivative of GNU
Emacs or any part thereof, to be licensed at no charge to all third
parties on terms identical to those contained in this License
Agreement.

This simply stated clause is the fundamental innovation of copyleft.
Specifically, copyleft *uses* the copy- right holders' controls on
permission to modify the work to add a conditional requirement.
Namely, down-

^1^[]{#_bookmark30 .anchor}RMS writes more fully about this topic in
his essay entitled simply [*The GNU
Project*](http://www.gnu.org/gnu/thegnuproject.html) . For those who
want to hear the story in his own voice, [speech
recordings](http://audio-video.gnu.org/audio/) of his talk, *The Free
Software Movement and the GNU/Linux Operating System* are also widely
available

stream users may only have permission to modify the work if they pass
along the same permissions on the modified version that came
originally to them.

These original program-specific proto-GPLs give an interesting window
into the central ideas and devel- opment of copyleft. In particular,
reviewing them shows how the text of the GPL we know has evolved to
address more of the issues discussed earlier in *§*
[1.2.3.](#software-and-non-copyright-legal-regimes)

## The GNU General Public License, Version 1

In January 1989, the FSF announced that the GPL had been converted
into a "subroutine" that could be reused not just for all
FSF-copyrighted programs, but also by anyone else. As the FSF claimed
in its announcement of the GPLv1:[^2^](#_bookmark33)

To make it easier to copyleft programs, we have been improving on the
legalbol architecture of the General Public License to produce a new
version that serves as a general-purpose subroutine: it can apply to
any program without modification, no matter who is publishing it.

This, like many inventive ideas, seems somewhat obvious in retrospect.
But, the FSF had some bright people and access to good lawyers when it
started. It took almost five years from the first copyleft licenses to
get to a generalized, reusable GPLv1. In the context and mindset of
the 1980s, this is not surprising. The idea of reusable licensing
infrastructure was not only uncommon, it was virtually nonexistent!
Even the early BSD licenses were simply copied and rewritten slightly
for each new use.[^3^](#_bookmark34) The GPLv1's innovation of
reusable licensing infrastructure, an obvious fact today, was indeed a
novel invention for its day.[^4^](#_bookmark35)

## The GNU General Public License, Version 2

The GPLv2 was released two and a half years after GPLv1, and over the
following sixteen years, it became the standard for copyleft licensing
until the release of GPLv3 in 2007 (discussed in more detail in the
next section).

While this tutorial does not discuss the terms of GPLv1 in detail, it
is worth noting below the three key changes that GPLv2 brought:

-   Software patents and their danger are explicitly mentioned,
    > inspiring (in part) the addition of GPLv2 *§§*5--

7\. (These sections are discussed in detail in *§*
[7.2,](#gplv2-5-acceptance-copyright-style) *§*
[7.3](#gplv2-6-gpl-my-one-and-only) and *§*
[7.5](#gplv2-7-give-software-liberty-or-give-it-death) of this
tutorial.)

-   GPLv2 *§*2's copyleft terms are expanded to more explicitly discuss
    > the issue of combined works. (GPLv2 *§*2 is discussed in detail in
    > *§* [5.1](#gplv2-2-share-and-share-alike) in this tutorial).

GPLv2 3 includes more detailed requirements, including the phrase "the
scripts used to control compi- lation and installation of the
executable", which is a central component of current GPLv2
enforcement. (GPLv2 *§*3 is discussed in detail in *§*
[5.2](#gplv2-3-producing-binaries) in this tutorial).

The next chapter discusses GPLv2 in full detail, and readers who wish
to dive into the section-by-section discussion of the GPL should jump
ahead now to that chapter. However, the most interesting fact to note
here is how GPLv2 was published with little fanfare and limited
commentary. This contrasts greatly with the creation of GPLv3.

^2^[]{#_bookmark33 .anchor}The announcement of GPLv1 was published in
the [GNU's Bulletin, vol 1, number 6 dated January
1989.](http://www.gnu.org/bulletins/bull6.html#SEC8) (Thanks very
mu[]{#_bookmark34 .anchor}ch to Andy Tai for his [consolidation of
research on the history of the pre-v1
GPL's.)](http://www.free-soft.org/gpl_history/)

^3^It remains an interesting accident of history that the early BSD
problematic "advertising clause" (discussion of which is somewhat
beyond the scope of this tutorial) lives on into current day, simply
because while the University of California at Berkeley gave unilateral
permission to remove the clause from *its* copyrighted works, others
who adapted the BSD license with []{#_bookmark35 .anchor}their own
names in place of UC-Berkeley's never have.

^4^We're all just grateful that the FSF also opposes business method
patents, since the FSF's patent on a "method for reusable licensing
infrastructure" would have not expired until 2006!

## The GNU General Public License, Version 3

RMS began drafting GPLv2.2 in mid-2002, and FSF ran a few discussion
groups during that era about new text of that license. However,
rampant violations of the GPL required more immediate attention of
FSF's licensing staff, and as such, much of the early 2000's was spent
doing GPL enforcement work.[^5^](#_bookmark38) In 2006, FSF began in
earnest drafting work for GPLv3.

The GPLv3 process began in earnest in January 2006. It became clear
that many provisions of the GPL could benefit from modification to fit
new circumstances and to reflect what the entire community learned
from experience with version 2. Given the scale of revision it seems
proper to approach the work through public discussion in a transparent
and accessible manner.

The GPLv3 process continued through June 2007, culminating in
publication of GPLv3 and LGPLv3 on 29 June 2007, AGPLv3 on 19 November
2007, and the GCC Runtime Library Exception on 27 January 2009.

All told, four discussion drafts of GPLv3, two discussion drafts of
LGPLv3 and two discussion drafts of AGPLv3 were published and
discussed. Ultimately, FSF remained the final arbiter and publisher of
the licenses, and RMS himself their primary author, but input was
sought from many parties, and these licenses do admittedly look and
read more like legislation as a result. Nevertheless, all of the "v3"
group are substantially better and improved licenses.

GPLv3 and its terms are discussed in detail in Chapter
[9.](#_bookmark93)

## The Innovation of Optional "Or Any Later" Version

An interesting fact of all GPL licenses is that there are ultimately
multiple choices for use of the license. The FSF is the primary
steward of GPL (as discussed later in
[8.1](#gplv2-9-fsf-as-stewards-of-gpl) and
[9.17).](#gplv3-14-so-whens-gplv4) However, those who wish to license
works under GPL are not required to automatically accept changes made
by the FSF for their own copyrighted works.

Each licensor may chose three different methods of licensing, as
follows:

explicitly name a single version of GPL for their work (usually
indicated in shorthand by saying the license is "GPLv*X*-only"), or

name no version of the GPL, thus they allow their downstream
recipients to select any version of the GPL they choose (usually
indicated in shorthand by saying the license is simply "GPL"), or

name a specific version of GPL and give downstream recipients the
option to choose that version "or any later version as published by
the FSF" (usually indicated by saying the license is
"GPLv*X*-or-later")[^6^](#_bookmark39)

Oddly, this flexibility has received (in the opinion of the authors,
undue) criticism, primarily because of the complex and oft-debated
notion of "license compatibility" (which is explained in detail in
[9.10).](#gplv3-7-understanding-license-compatibility) Copyleft
licenses are generally incompatible with each other, because the
details of how they implement copyleft differs. Specifically, copyleft
works only because of its requirement that downstream licensors use
the *same* license for combined and modified works. As such, software
licensed under the terms of "GPLv2- only" cannot be combined with
works licensed "GPLv3-or-later". This is admittedly a frustrating
outcome. Other copyleft licenses that appeared after GPL, such as the
Creative Commons "Attribution-Share Alike" licenses, the Eclipse
Public License and the Mozilla Public License **require** all
copyright holders choosing to use any version of those licenses to
automatically allow use of their copyrighted works under new
versions.[^7^](#_bookmark40) Of course, Creative Commons, the Eclipse
Foundation, and the Mozilla Foundation (like the FSF) have generally
served as excellent stewards of their licenses. Copyright holders
using those licenses seems to

^5^[[]{#_bookmark39 .anchor}]{#_bookmark38 .anchor}More on GPL
enforcement is discussed in Part [II](#_bookmark169) of this tutorial.

^6^The shorthand of "GPL*X*+" is also popular for this situation. The
authors of this tutorial prefer "-or-later" syntax, because it (a)
mirrors the words "or" and "later from the licensing statement, (b)
the *X*+ doesn't make it abundantly clear that *X* is clearly included
as a license option and (c) the + symbol has other uses in computing
(such as with regular expressions) that []{#_bookmark40 .anchor}mean
something different.

^7^CC-BY-SA-2.0 and greater only permit licensing of adaptations under
future versions; 1.0 did not have any accomodation for future version
compatibility.

find it acceptable to fully delegate all future licensing decisions
for their copyrights to these organizations without a second thought.

However, note that FSF gives herein the control of copyright holders
to decide whether or not to implicitly trust the FSF in its work of
drafting future GPL versions. The FSF, for its part, does encourage
copyright holders to chose by default "GPLv*X*-or-later" (where *X* is
the most recent version of the GPL published by the FSF). However, the
FSF **does not mandate** that a choice to use any GPL requires a
copyright holder ceding its authority for future licensing decisions
to the FSF. In fact, the FSF considered this possibility for GPLv3 and
chose not to do so, instead opting for the third-party steward
designation clause discussed in Section
[9.17.](#gplv3-14-so-whens-gplv4)

## Complexities of Two Simultaneously Popular Copylefts

Obviously most GPL advocates would prefer widespread migration to
GPLv3, and many newly formed projects who seek a copyleft license tend
to choose a GPLv3-based license. However, many existing copylefted
projects continue with GPLv2-only or GPLv2-or-later as their default
license.

While GPLv3 introduces many improvements --- many of which were
designed to increase adoption by for-profit companies --- GPLv2
remains a widely used and extremely popular license. The GPLv2 is, no
doubt, a good and useful license.

However, unlike GPLv1 before it, GPLv2 remains an integral part of the
copyleft licensing infrastructure. As such, those who seek to have
expertise in current topics of copyleft licensing need to study both
the GPLv2 and GPLv3 family of licenses.

Furthermore, GPLv3 is more easily understood by first studying GPLv2.
This is not only because of their chronological order, but also
because much of the discussion material available for GPLv3 tends to
talk about GPLv3 in contrast to GPLv2. As such, a strong understanding
of GPLv2 helps in understanding most of the third-party material found
regarding GPLv3. Thus, the following chapter begins a deep discussion
of GPLv2.

