
[**CHAPTER 2**]{#_bookmark27 .anchor}

[**第2章**]{#_bookmark27 .anchor}

A TALE OF TWO COPYLEFT LICENSES

两个著佐权许可证的故事

While determining the proper methodology and criteria to yield an
accurate count remains difficult, the GPL is generally considered one
of the most widely used Free Software licenses. For most of its
history --- for 16 years from June 1991 to June 2007 --- there was
really only one version of the GPL, version 2.

尽管还没办法选择适当的方法和标准给出准确统计，但GPL是公认最广泛使用的自由软件许可证之一。在它大部分历史（从1991年6月到2007年6月的16年）中，GPL实际上只有一个版本，即第二版。

However, the GPL had both earlier versions before version 2, and, more
well known, a revision to version

然而，GPL既有第二版之前的早期版本，也有更知名的第三版修订版。

## Historical Motivations for the General Public License

## 2.1 通用公共许可证的历史动因

The earliest license to grant software freedom was likely the Berkeley
Software Distribution ("BSD") license. This license is typical of what
are often called lax, highly permissive licenses. Not unlike software
in the public domain, these non-copyleft licenses (usually) grant
software freedom to users, but they do not go to any effort to uphold
that software freedom for users. The so-called "downstream" (those who
receive the software and then build new things based on that software)
can restrict the software and distribute further. 

最早的授予软件自由的许可证可能是伯克利软件分发（Berkeley Software Distribution，“BSD”）许可证。这个许可证是典型的、高度宽松的许可证，通常被称为“宽松许可证”。与公共领域的软件不一样，这些非著佐权许可证（通常）将软件自由授予用户，但它们并不为用户维护这种软件自由。所谓的 "下游"（那些收到软件后在该软件基础上添砖加瓦的人）可以限制该软件进一步分发。

The GNU's Not Unix
("GNU") project, which Richard M. Stallman ("RMS") founded in 1984 to
make a complete Unix-compatible operating system implementation that
assured software freedom for all. However, RMS saw that using a
license that gave but did not assure software freedom would be counter
to the goals of the GNU Project. RMS invented "copyleft" as an answer
to that problem, and began using various copyleft

licenses for the early GNU Project programs.[^1](#_bookmark30)

为了实现对完全兼容Unix的操作系统的应用、保证所有人的软件自由，Richard M. Stallman（RMS）于1984年创建“GUN Not Unix（GNU）”项目。然而，RMS发现使用许可证可以赋予却不能保证软件自由，这可能与GUN项目的目标背道而驰。于是RMS发明了“著佐权”来解决这个问题，并且开始在早期GNU项目程序中使用各种形式的著佐权许可证。[^1](#_bookmark30)

## Proto-GPLs And Their Impact

## 2.2 原始GPL及其影响

The earliest copyleft licenses were specific to various GNU programs.
For example, The Emacs General Public License was likely the first
copyleft license ever published. Interesting to note that even this
earliest copyleft license contains a version of the well-known GPL
copyleft clause:

最早的著佐权许可证是专门针对各种GNU程序的。例如，Emacs通用公共许可证可能是有史以来发布的第一个著佐权许可证。有趣的是，即使是这个最早的著佐权许可证也包含了著名的GPL著佐权条款的一个版本：

You may modify your copy or copies of GNU Emacs . . . provided that
you also . . . cause the whole of any work that you distribute or
publish, that in whole or in part contains or is a derivative of GNU
Emacs or any part thereof, to be licensed at no charge to all third
parties on terms identical to those contained in this License
Agreement.

你可以修改你的GNU Emacs副本……如果你也……使你的任何全部或部分包含GNU Emacs或作为其衍生作品分发或发布的作品的整体，以与本许可协议中包含的条款相同的条款免费授权给所有第三方。

This simply stated clause is the fundamental innovation of copyleft.
Specifically, copyleft *uses* the copy- right holders' controls on
permission to modify the work to add a conditional requirement.
Namely, down-

这个阐述简明的条款是著佐权的根本创新。具体来说，著佐权通过著作权所有者对修改作品的权限的控制，增加了一个条件，即：

[^1]{#_bookmark30 .anchor}RMS writes more fully about this topic in
his essay entitled simply [*The GNU
Project*](http://www.gnu.org/gnu/thegnuproject.html) . For those who
want to hear the story in his own voice, [speech
recordings](http://audio-video.gnu.org/audio/) of his talk, *The Free
Software Movement and the GNU/Linux Operating System* are also widely
available
*
[^1]{#_bookmark30 .anchor}RMS在其题为[《GNU工程》](http://www.gnu.org/gnu/thegnuproject.html)的文章中更详细地描述了这个话题。他关于*自由软件运动和GNU/Linux操作系统*的[演讲录音](http://audio-video.gnu.org/audio/)也随处可见，那些想通过他的声音听故事的人可以轻松获取。

stream users may only have permission to modify the work if they pass
along the same permissions on the modified version that came
originally to them.

下游用户只有在将他们最初被赋予的修改版本的权限传递给他人时，才可能拥有修改作品的权限。

These original program-specific proto-GPLs give an interesting window
into the central ideas and devel- opment of copyleft. In particular,
reviewing them shows how the text of the GPL we know has evolved to
address more of the issues discussed earlier in §
[1.2.3.](#software-and-non-copyright-legal-regimes)

这些起初特定于程序的原始GPL提供了一个了解著佐权的中心思想和发展的有趣窗口。此外，仔细研究它们可以看到我们熟悉的GPL文本是如何逐步演变以解决前面§
[1.2.3.](#software-and-non-copyright-legal-regimes)中讨论过的更多问题的。

## The GNU General Public License, Version 1

## 2.3 GNU通用公共许可证，第一版

In January 1989, the FSF announced that the GPL had been converted
into a "subroutine" that could be reused not just for all
FSF-copyrighted programs, but also by anyone else. As the FSF claimed
in its announcement of the GPLv1:[^2](#_bookmark33)

1989年1月，FSF宣布GPL已经被转换成为一个“子例程”，不仅可以被所有受FSF著作权保护的程序重复使用，还可以被任何其他人重复使用。正如FSF在GPLv1的公告中所宣称的那样：[^2](#_bookmark33)

To make it easier to copyleft programs, we have been improving on the
legalbol architecture of the General Public License to produce a new
version that serves as a general-purpose subroutine: it can apply to
any program without modification, no matter who is publishing it.

为了使著佐权程序更方便使用，我们一直在改进通用公共许可证的法律体系结构，以便产生一个可以作为通用子例程的新版本：无论由谁发布，它都适用于任何程序而无需修改。

This, like many inventive ideas, seems somewhat obvious in retrospect.
But, the FSF had some bright people and access to good lawyers when it
started. It took almost five years from the first copyleft licenses to
get to a generalized, reusable GPLv1. In the context and mindset of
the 1980s, this is not surprising. The idea of reusable licensing
infrastructure was not only uncommon, it was virtually nonexistent!
Even the early BSD licenses were simply copied and rewritten slightly
for each new use.[^3](#_bookmark34) The GPLv1's innovation of
reusable licensing infrastructure, an obvious fact today, was indeed a
novel invention for its day.[^4](#_bookmark35)

这一点，就像许多具有创造性的想法一样，回想起来似乎是显而易见的。但是，FSF在成立之初拥有一些人才，也能接触到优秀的律师。从第一个著佐权许可证到形成通用的、可重复使用的GPLv1，花了将近五年的时间。在20世纪80年代的背景和思维模式下，这并不奇怪。可重复使用基础许可的想法不仅不常见，而且几乎不存在！即使是早期的BSD许可证也只是通过简单地复制和改写来适应每个新用途。[^3](#_bookmark34)GPLv1对可重复使用基础许可的创新，在今天是显而易见的事实，在当时确实是一项新颖的发明。[^4](#_bookmark35)

## The GNU General Public License, Version 2

## 2.4 GNU通用公共许可证，第二版

The GPLv2 was released two and a half years after GPLv1, and over the
following sixteen years, it became the standard for copyleft licensing
until the release of GPLv3 in 2007 (discussed in more detail in the
next section).

GPLv2比GPLv1晚两年半发布，在接下来的16年里，它成为了著佐权许可的标准，直到2007年GPLv3发布(下一节将详细讨论)。

While this tutorial does not discuss the terms of GPLv1 in detail, it
is worth noting below the three key changes that GPLv2 brought:

虽然本指南不详细讨论GPLv1的条款，但GPLv2带来的三个关键变化值得一提：

-   Software patents and their danger are explicitly mentioned, inspiring (in part) the addition of GPLv2 §§5--7. (These sections are discussed in detail in §[7.2,](#gplv2-5-acceptance-copyright-style) §[7.3](#gplv2-6-gpl-my-one-and-only) and §[7.5](#gplv2-7-give-software-liberty-or-give-it-death) of this tutorial.)
-   软件专利及其风险被明确提及，(在一定程度上)激发了GPLv2 §§5-7的加入。(这些部分将在本指南的§[7.2](#gplv2-5-acceptance-copyright-style)、§[7.3](#gplv2-6-gpl-my-one-and-only)和§[7.5](#gplv2-7-give-software-liberty-or-give-it-death)中详细讨论。)

-   GPLv2 §2's copyleft terms are expanded to more explicitly discuss the issue of combined works. (GPLv2 *§*2 is discussed in detail in *§* [5.1](#gplv2-2-share-and-share-alike) in this tutorial).
- GPLv2 §2的著佐权术语得到了扩展，可以更明确地讨论组合作品的问题。(GPLv2 §2将在本指南的§[5.1](#gplv2-2-share-and-share-alike)中详细讨论)。

-   GPLv2 §3 includes more detailed requirements, including the phrase "the scripts used to control compi- lation and installation of the executable", which is a central component of current GPLv2 enforcement. (GPLv2 §3 is discussed in detail in §[5.2](#gplv2-3-producing-binaries) in this tutorial).
-   GPLv2 §3包含了更详细的需求，包括短语“用于控制可执行文件的编译和安装的脚本”，这是当前GPLv2实施的核心组件。(GPLv2 §3将在本指南的§[5.2](#gplv2-3-producing-binaries)中详细讨论)。

The next chapter discusses GPLv2 in full detail, and readers who wish
to dive into the section-by-section discussion of the GPL should jump
ahead now to that chapter. However, the most interesting fact to note
here is how GPLv2 was published with little fanfare and limited
commentary. This contrasts greatly with the creation of GPLv3.

下一章将详细讨论GPLv2，希望深入了解GPL逐节讨论的读者现在可以跳到那一章。然而，这里要指出的最有趣的事实是，GPLv2是如何在没有大肆宣传和有限报道的情况下发布的。这与GPLv3的诞生形成了鲜明对比。

[^2]{#_bookmark33 .anchor}The announcement of GPLv1 was published in
the [GNU's Bulletin, vol 1, number 6 dated January
1989.](http://www.gnu.org/bulletins/bull6.html#SEC8) (Thanks very
much to Andy Tai for his [consolidation of
research on the history of the pre-v1
GPL's.)](http://www.free-soft.org/gpl_history/)

[^2]{#_bookmark33 .anchor}GPLv1的公告发表在1989年1月的[GNU公报第1卷第6期](http://www.gnu.org/bulletins/bull6.html#SEC8)。(非常感谢Andy Tai[对GPL v1之前的历史进行的整合研究](http://www.free-soft.org/gpl_history/)。)

[^3]{#_bookmark34 .anchor}It remains an interesting accident of history that the early BSD
problematic "advertising clause" (discussion of which is somewhat
beyond the scope of this tutorial) lives on into current day, simply
because while the University of California at Berkeley gave unilateral
permission to remove the clause from *its* copyrighted works, others
who adapted the BSD license with their own
names in place of UC-Berkeley's never have.

[^3]{#_bookmark34 .anchor}早期BSD有问题的“广告条款”(关于它的讨论在某种程度上超出了本指南的范围)直到今天依然存在，这一直是历史上一个有趣的偶然事件，仅仅是因为当加州大学伯克利分校单方面允许从其受著作权保护的作品中删除该条款时，那些修改BSD许可证时用自己的名字代替加州大学伯克利分校的其他组织却从来没有这样做。

[^4]{#_bookmark35 .anchor}We're all just grateful that the FSF also opposes business method
patents, since the FSF's patent on a "method for reusable licensing
infrastructure" would have not expired until 2006!

[^4]{#_bookmark35 .anchor}我们都很感激FSF也反对商业方法专利，因为FSF的专利作为一种“可重复使用的基础许可模式”到2006年才失效！

## The GNU General Public License, Version 3

## 2.5 GNU通用公共许可证，第三版

RMS began drafting GPLv2.2 in mid-2002, and FSF ran a few discussion
groups during that era about new text of that license. However,
rampant violations of the GPL required more immediate attention of
FSF's licensing staff, and as such, much of the early 2000's was spent
doing GPL enforcement work.[^5](#_bookmark38) In 2006, FSF began in
earnest drafting work for GPLv3.

RMS在2002年年中开始起草GPLv2.2, FSF在那个时期组织了一些讨论小组，讨论该许可证的新文本。然而，猖獗的GPL侵权行为需要FSF的授权人员更加及时的关注，因此，2000年早期的大部分时间都花在了GPL的实施工作上。5 2006年，FSF正式开始GPLv3的起草工作。

The GPLv3 process began in earnest in January 2006. It became clear
that many provisions of the GPL could benefit from modification to fit
new circumstances and to reflect what the entire community learned
from experience with version 2. Given the scale of revision it seems
proper to approach the work through public discussion in a transparent
and accessible manner.

GPLv3的进程于2006年1月正式开始。很明显，GPL的许多条款可以从修改中完善，以适应新的情况并反映出整个社区从第二版的经验中得到的教训。考虑到修订的规模，似乎以透明和可访问的方式通过公开讨论来处理工作是合适的。

The GPLv3 process continued through June 2007, culminating in
publication of GPLv3 and LGPLv3 on 29 June 2007, AGPLv3 on 19 November
2007, and the GCC Runtime Library Exception on 27 January 2009.

GPLv3进程一直持续到2007年6月，最终于2007年6月29日发布了GPLv3和LGPLv3，并于2007年11月19日发布了AGPLv3，以及于2009年1月27日发布了GCC运行时库异常。

All told, four discussion drafts of GPLv3, two discussion drafts of
LGPLv3 and two discussion drafts of AGPLv3 were published and
discussed. Ultimately, FSF remained the final arbiter and publisher of
the licenses, and RMS himself their primary author, but input was
sought from many parties, and these licenses do admittedly look and
read more like legislation as a result. Nevertheless, all of the "v3"
group are substantially better and improved licenses.

总共发布并讨论了四份GPLv3讨论草案、两份LGPLv3讨论草案和两份AGPLv3讨论草案。最终，FSF仍然是许可证的最终仲裁者和出版方，RMS自己是许可证的主要作者，但是征求了许多人士的意见，因此这些许可证确实看起来和读起来更像立法。尽管如此，整个“v3”组都有了很大的改进，成为了更好的许可证。

GPLv3 and its terms are discussed in detail in Chapter
[9.](#_bookmark93)

GPLv3及其术语将在第[9](#_bookmark93)章中详细讨论。

## The Innovation of Optional "Or Any Later" Version

## 2.6 可选“或任何后来”版本的创新

An interesting fact of all GPL licenses is that there are ultimately
multiple choices for use of the license. The FSF is the primary
steward of GPL (as discussed later in
*§*[8.1](#gplv2-9-fsf-as-stewards-of-gpl) and
*§*[9.17).](#gplv3-14-so-whens-gplv4) However, those who wish to license
works under GPL are not required to automatically accept changes made
by the FSF for their own copyrighted works.

所有GPL许可证的一个有趣的事实是：最终有多种使用许可证的选择。FSF是GPL的主要管理者（稍后将在*§*[8.1](#gplv2-9-fsf-as-stewards-of-gpl) 和*§*[9.17).](#gplv3-14-so-whens-gplv4)中讨论）。然而，那些希望在GPL下授权作品的人不需要自动接受FSF对他们自己受著作权保护的作品所做的更改。

Each licensor may chose three different methods of licensing, as
follows:

每个许可人可以选择以下三种不同的许可方式：

- explicitly name a single version of GPL for their work (usually
indicated in shorthand by saying the license is "GPLv*X*-only"), or

- 为他们的作品明确指定一个GPL版本（一般用“仅限GPLvX”这样的简写来表示），或者

- name no version of the GPL, thus they allow their downstream
recipients to select any version of the GPL they choose (usually
indicated in shorthand by saying the license is simply "GPL"), or

- 不指定GPL的任何版本，这样他们允许下游接收者任意选择GPL的任何版本（一般只简称许可证是“GPL”），或者

- name a specific version of GPL and give downstream recipients the
option to choose that version "or any later version as published by
the FSF" (usually indicated by saying the license is
"GPLv*X*-or-later")[^6](#_bookmark39)

- 指定一个特定的GPL版本，并让下游接收者选择该版本“或由FSF发布的任何更高版本”（一般会说许可证是“GPLv*X*或更高版本”）。[^6^](#_bookmark39)

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
outcome. 

奇怪的是，这种灵活性受到了（在作者看来是不适当的）批评，主要是因为“许可证兼容性”（x 9.10中有详细解释）的复杂性以及对其概念的争论不断。著佐权许可证通常彼此不兼容，因为履行著佐权的细节不同。具体来说，著佐权生效的唯一条件是它要求下游许可方对合并和修改的作品使用相同许可。因此，在“仅限GPLv2”条款下授权的软件不能与使用“GPLv3或更高版本”许可的作品结合。诚然，这是一个令人沮丧的结果。

Other copyleft licenses that appeared after GPL, such as the
Creative Commons "Attribution-Share Alike" licenses, the Eclipse
Public License and the Mozilla Public License **require** all
copyright holders choosing to use any version of those licenses to
automatically allow use of their copyrighted works under new
versions.[^7^](#_bookmark40) Of course, Creative Commons, the Eclipse
Foundation, and the Mozilla Foundation (like the FSF) have generally
served as excellent stewards of their licenses. Copyright holders
using those licenses seems to

在GPL之后出现的其他著佐权许可证，如知识共享“署名-相同方式共享”许可证、Eclipse公共许可证和Mozilla公共许可证要求所有选择使用这些许可证的任何版本的著作权所有者自动允许在新版本下使用其受著作权保护的作品。7 当然，知识共享组织、Eclipse基金会和Mozilla基金会（像FSF一样）通常都是他们自己的许可证的优秀管理员。使用这些许可证的著作权所有者似乎

[^5]{#_bookmark38 .anchor}More on GPL
enforcement is discussed in Part [II](#_bookmark169) of this tutorial.

[^5]{#_bookmark38 .anchor}关于GPL实施的更多内容将在本指南的第[二](#_bookmark169)部分中讨论.

[^6]{#_bookmark39 .anchor}The shorthand of "GPL*X*+" is also popular for this situation. The
authors of this tutorial prefer "-or-later" syntax, because it (a)
mirrors the words "or" and "later from the licensing statement, (b)
the *X*+ doesn't make it abundantly clear that *X* is clearly included
as a license option and (c) the + symbol has other uses in computing
(such as with regular expressions) that []{#_bookmark40 .anchor}mean
something different.

[^6]{#_bookmark39 .anchor}“GPLX+”的简写在这种情况下也很流行。本指南的作者更倾向于使用“或更高版本”语法，因为它：(a)反映了许可陈述中的单词“or（或）”和“later（更高版本）”；(b) X+不能非常清楚地表明许可选项中包含X；(c) +符号在计算中有其他用途（例如正则表达式），其含义不同。

[^7]{#_bookmark40 .anchor}CC-BY-SA-2.0 and greater only permit licensing of adaptations under
future versions; 1.0 did not have any accomodation for future version
compatibility.

[^7]{#_bookmark40 .anchor}CC-BY-SA-2.0及更高版本只允许未来版本的改编许可；1.0没有为将来的版本兼容性做任何安排。

find it acceptable to fully delegate all future licensing decisions
for their copyrights to these organizations without a second thought.

发现可以毫不犹豫地将其著作权的所有未来许可决策完全委托给这些组织。

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

但是请注意，FSF在此赋予了著作权所有者决策权，他们可以决定是否在起草未来GPL版本的工作中绝对信任FSF。就FSF而言，它确实鼓励著作权所有者默认选择“GPLv*X*或更高版本”（其中*X*是FSF发布的GPL的最新版本）。然而，FSF并**没有强制**要求选择使用任何GPL需要著作权所有者将其未来许可决策的权力交给FSF。事实上，FSF考虑了GPLv3的这种可能性却选择不这样做，而是选择了[9.17.](#gplv3-14-so-whens-gplv4)节中讨论的第三方管理指定条款。

## Complexities of Two Simultaneously Popular Copylefts

## 2.7 两个著佐权同时普遍使用的复杂性

Obviously most GPL advocates would prefer widespread migration to
GPLv3, and many newly formed projects who seek a copyleft license tend
to choose a GPLv3-based license. However, many existing copylefted
projects continue with GPLv2-only or GPLv2-or-later as their default
license.

显然，大多数GPL倡导者更倾向于广泛迁移至GPLv3，而且许多新成立的项目在挑选著佐权许可证时倾向于选择基于GPLv3的许可证。然而，许多现有受著佐权保护的项目仍继续使用“仅限GPLv2”或“GPLv2或更高版本”作为默认许可证。

While GPLv3 introduces many improvements --- many of which were
designed to increase adoption by for-profit companies --- GPLv2
remains a widely used and extremely popular license. The GPLv2 is, no
doubt, a good and useful license.

虽然GPLv3引入了许多改进——其中许多改进旨在促进营利性公司的采用——GPLv2仍是一个被广泛使用和非常受欢迎的许可证。毫无疑问，GPLv2是一个优秀且实用的许可证。

However, unlike GPLv1 before it, GPLv2 remains an integral part of the
copyleft licensing infrastructure. As such, those who seek to have
expertise in current topics of copyleft licensing need to study both
the GPLv2 and GPLv3 family of licenses.

然而，与之前的GPLv1不同的是，GPLv2仍然是著佐权基础许可中不可分割的一部分。因此，那些希望在当前著佐权许可相关的话题方面拥有专业知识的人需要同时研究GPLv2和GPLv3系列许可证。

Furthermore, GPLv3 is more easily understood by first studying GPLv2.
This is not only because of their chronological order, but also
because much of the discussion material available for GPLv3 tends to
talk about GPLv3 in contrast to GPLv2. As such, a strong understanding
of GPLv2 helps in understanding most of the third-party material found
regarding GPLv3. Thus, the following chapter begins a deep discussion
of GPLv2.

此外，先研究GPLv2会更容易理解GPLv3。这不仅是因为它们的时间顺序，还因为许多关于GPLv3的可用讨论材料倾向于将GPLv3与GPLv2进行对比。因此，对GPLv2的深刻理解有助于理解大多数关于GPLv3的第三方材料。因此，下一章开始深入讨论GPLv2。

