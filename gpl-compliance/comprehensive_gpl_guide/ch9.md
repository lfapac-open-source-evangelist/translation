# CHAPTER 9 GPL VERSION 3

# 第9章 GPL 第3版

This chapter discusses the text of GPLv3. Much of this material herein
includes text that was adapted (with permission) from text that FSF
originally published as part of the so-called "rationale documents"
for the various discussion drafts of GPLv3.

本章讨论GPLv3的文本。本文中的大部分材料是从FSF（经许可）最初作为各种讨论草案的所谓“基本原理文件”的部分文本编写。

The FSF ran a somewhat public process to develop GPLv3, and it was the
first attempt of its kind to develop a Free Software license this way.
Ultimately, RMS was the primary author of GPLv3, but he listened to
feedback from all sorts of individuals and even for-profit companies.
Nevertheless, in attempting to understand GPLv3 after the fact, the
materials available from the GPLv3 process have a somewhat "drinking
from the firehose" effect. This chapter seeks to explain GPLv3 to
newcomers, who perhaps are familiar with GPLv2 and who did not
participate in the GPLv3 process.

FSF运行了一个公开的开发GPLv3的流程，这是首次尝试开发自由软件许可证的方法。最终，RMS是GPLv3的主要作者，但是他听取了各种个人甚至是营利性公司的反馈。然而，试图在事后理解GPLv3，有点像“就着消防栓喝水”的感觉。本章旨在向可能熟悉GPLv2，而未参与过GPLv3流程的新手解释GPLv3。

Those who wish to drink from the firehose and take a diachronic
approach to GPLv3 study by reading the step-by-step public drafting
process of the GPLv3 (which occurred from Monday 16 January 2006
through Monday 19 November 2007) should visit <http://gplv3.fsf.org/>.

那些希望通过阅读GPLv3起草过程（从2006年1月16日星期一到2007年11月19日星期一）对GPLv3研究采取历时方法的人应该访问<http://gplv3.fsf.org>。

## Understanding GPLv3 As An Upgraded GPLv2

## 9.1 把GPLv3理解为GPLv2的升级版

Ultimately, GPLv2 and GPLv3 co-exist as active licenses in regular
use. As discussed in Chapter [2,](#_bookmark27) GPLv1 was never
regularly used alongside GPLv2. However, given GPLv2's widespread
popularity and existing longevity by the time GPLv3 was published, it
is not surprising that some licensors still prefer GPLv2-only or
GPLv2-or-later. GPLv3 gained major adoption by many projects, old and
new, but many projects have not upgraded due to (in some cases) mere
laziness and (in other cases) policy preference for some of GPLv2's
terms and/or policy opposition to GPLv3's terms.

最终，GPLv2和GPLv3作为常规有效许可证共存。如第2章所述。GPL第1版从未与GPLv2一起常规使用。然而，鉴于GPLv2的广泛流行和GPLv3发布时的现有寿命，一些人许可人更喜欢采用仅GPLv2，或者，GPLv2或者后续版本就不足为奇了。

Given this "two GPLs world" is reality, it makes sense to consider
GPLv3 in terms of how it differs from GPLv2. Also, most of the best
GPL experts in the world must deal regularly with both licenses, and
admittedly have decades of experience with GPLv2 while the most
experience with GPLv3 that's possible is by definition less than a
decade. These two factors usually cause even new students of GPL to
start with GPLv2 and move on to GPLv3, and this tutorial follows that
pattern.

鉴于这个“两个 GPL 世界”是现实，对 GPLv3 与 GPLv2 的区别来考虑它是有意义的。此外，世界上大多数最优秀的 GPL 专家必须定期处理这两个许可证，并且公认的是拥有数十年的 GPLv2 经验，理论上讲，最多的 GPLv3 经验可能不到10年。这两个因素通常甚至会导致 GPL 的新人不是从 GPLv2 开始，而是直接然后转向 GPLv3，本教程遵循这种模式。

Overall, the changes made in GPLv3 admittedly *increased* the
complexity of the license. The FSF stated at the start of the GPLv3
process that they would have liked to oblige those who have asked for
a simpler and shorter GPL. Ultimately, the FSF gave priority to making
GPLv3 a better copyleft license in the spirit of past GPL's. Obsession
for concision should never trump software freedom.

总的来说，GPLv3 中所做的更改无疑增加了许可证的复杂性。FSF 在 GPLv3 流程开始时表示，他们愿意帮助那些要求更简单、更短的 GPL 的人。最终，FSF 本着过去 GPL 的精神，优先考虑让 GPLv3 成为更好的 copyleft 许可证。对简洁的痴迷永远不应胜过软件自由。

The FSF had many different, important goals in seeking to upgrade to
GPLv3. However, one important goal that is often lost in the
discussion of policy minutia is a rather simple but important issue.
Namely, FSF sought to assure that GPLv3 was more easily
internationalized than GPLv2. In particular, the FSF sought to ease
interpretation of GPL in other countries by replacement of
USA-centric[^1^](#_bookmark95) copyright phrases
and wording with neutral terminology rooted in description of behavior
rather than specific statute. As can be seen in the section-by-section
discussion of GPLv3 that follows, nearly every section had changes
related to issues of internationalization.

FSF 在寻求升级到 GPLv3 方面有许多不同的重要目标。然而，在讨论政策细枝末节时经常遗漏的一个重要目标是一个相当简单但重要的问题。那就是，FSF 试图确保 GPLv3 比 GPLv2 更容易国际化。特别是，FSF 试图通过替换以美国为中心的 [^1] 版权术语来简化其他国家/地区对 GPL 的解释。以及植根于行为描述而非特定法规的中性术语措辞。从接下来对 GPLv3 的逐节讨论中可以看出，几乎每一节都有与国际化问题相关的更改。

[^1]:有关非美国版权系统的简要讨论，请参阅本教程的第 1.2.4 节。

## GPLv3 §0: Giving In On "Defined Terms"

## 9.2 GPLv3 第0条：在“条款定义”上的让步

One of lawyers' most common complaints about GPLv2 is that defined
terms in the document appear throughout. Most licenses define terms
up-front. However, the GPL was always designed both as a document that
should be easily understood both by lawyers and by software
developers: it is a document designed to give freedom to software
developers and users, and therefore it should be comprehensible to
that constituency.

律师对 GPLv2 最常见的抱怨之一是文档中术语的定义贯穿始终。大多数许可证预先定义条款。然而，GPL 始终被设计成一个应该易于被律师和软件开发人员理解的文件：它是一个旨在为软件开发人员和用户提供自由的文件，因此它应该易于被这类用户所理解。

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

有趣的是，本教程的一位合著者既是律师又是开发人员，她指出，在法学院，由于她的编程背景，她比其他法学院学生更快地理解术语的定义。对于开发人员来说，拥有 **#define** （在 C 编程语言中）或其他类型的常量和/或在使用它们的地方自动扩展的宏是第二天性。因此，添加一个术语的定义对开发人员来说并不是什么大问题，因此 GPLv3 也确实增加了新的定义。这些定义的术语中的大多数都有些直截了当，并从 GPLv2 中提出了更好的措辞定义。在此，本教程讨论的那些新增加的。

GPLv3 0 includes definitions of five new terms not found in any form
in GPLv2: "modify" "covered work", "propagate", "convey", and
"Appropriate Legal Notices".

GPLv3 第0条包括 GPLv2 中没有以任何形式出现的五个新术语的定义：“修改”、“涵盖的作品”、“传播”、“传达”和“适当的法律声明”。

### Modify and the Work Based on the Program

### 9.2.1 基于程序的修改和工作

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

GPLv2 包括一个术语“基于程序的作品”的定义，但在整个许可证中也使用了术语“修改”和“基于”。GPLv2 的“基于程序的作品”定义使用了美国版权法特有的艺术术语“衍生作品”[^2]。GPLv2 始终寻求涵盖美国相关版权法管辖的所有权利和其他地方。尽管与衍生作品相对应的不同标签概念在所有版权法体系中都得到认可，但这些对应概念可能在范围和广度上与美国衍生作品存在一定程度的差异。因此，GPLv3 通过删除 GPLv2 对衍生作品的引用并提供更具全球实用性的定义，使这个问题国际化。GPLv3 删除了所有对美国“衍生作品”的引用，并仅返回基本概念：GPL 涵盖许可作品和所有获得许可作品版权所有者版权许可的作品。

[^2]:具有讽刺意味的是，在 GPLv2 的“基于程序的作品”定义中，对美国特定法律术语的大多数批评历史上主要不是来自美国以外的读者，而是来自美国境内的读者。FSF 指出，它一般不同意这些观点，并对表达这些观点的精力表示困惑，因为 GPL 涉及许多其他更困难的法律问题。尽管如此，FSF 认为，消除对本地版权术语的使用是有道理的。

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

新定义回归版权法的共同要素。软件作品的版权持有者拥有通过修改原件形成新作品的专有权——这种权利在不同的法律体系中可能以不同的方式表达。GPLv3 将此权利授予连续几代用户（特别是通过 GPLv3 第5条中规定的 copyleft 条件，如本教程后面的 9.8 中所述）。这里在 GPLv3 第0条中，“修改”指的是基本版权，然后这个“修改”的定义用来定义“修改版本”和“基于”的同义词。

### The Covered Work

### 9.2.2 涵盖的工作

GPLv3 uses a common license drafting technique of building upon
simpler definitions to make complex ones. The Program is a defined
term found throughout GPLv2, and the word "covered" and the phrase
"covered by this license" are used in tandem with the Program in
GPLv2, but not as part of a definition. GPLv3 offers a single term
"covered work", which enables some of the wording in GPLv3 to be
simpler and clearer than its GPLv2 counterparts.

GPLv3 使用一种通用的许可证起草技术，即在更简单的定义基础上构建复杂的定义。“本程序”是贯穿 GPLv2 的一个定义术语，“涵盖”一词和短语“受本许可证涵盖”在 GPLv2 中与“本程序”一起使用，但不作为定义的一部分。GPLv3 提供了一个单一的术语“涵盖的作品”，这使得 GPLv3 中的一些措辞比 GPLv2 对应的措辞更简单、更清晰。

Next, to avoid locking GPLv3 into specific copyright statues, the
GPLv3 defines two terms that are otherwise exotic to the language of
international copyright.

接下来，为了避免将 GPLv3 锁定在特定的版权法规中，GPLv3 定义了两个对国际版权语言来说陌生的术语。

### Propagate

### 9.2.3 传播

To "propagate" a work covered by the license means any activity in a
locale that requires permission of copyright holders in that locale's
legal system. However, personal use or modification for personal use
are activities explicitly excluded from "propagation" *regardless* of
domestic copyright law.

“传播”许可证涵盖的作品是指在该地区的法律体系中需要版权所有者许可的地区的任何活动。然而，无论国内版权法如何，个人使用或为个人使用而修改是明确排除在“传播”之外的活动。

The term "propagate" serves two purposes. First, "propagate" provides
a simple and convenient means for distinguishing between the kinds of
uses of a work that GPL imposes conditions on and the kinds of uses
that GPL does not (for the most part) impose conditions on.

“传播”一词有两个目的。首先，“传播”提供了一种简单方便的方式来区分 GPL 施加条件的作品的使用类型和 GPL 不（在大多数情况下）施加条件的使用类型。

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

其次，“传播”有助于 GPL 在措辞和效果上的全球化：“衍生作品”实际上并不是当地版权法规常用的唯一术语。一些国家的版权法规中也使用了诸如“分发”（或英语以外的其他语言中的等效词）之类的术语。GPLv2 的实践经验揭示了在全球使用的许可证中使用术语“分发”的尴尬：版权上下文中的“分发”范围可能因国家/地区而异。GPL 未必意指美国（或任何其他国家/地区）版权法下存在的“分发”的特定含义。

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

事实上，即使在单一的国家和语言中，术语分布也可能是模棱两可的； 作为一个法律术语，分配在承认它的国家之间的含义差异很大。例如，GPLv3 起草过程中的评论表明，至少在一个国家/地区，分发可能不包括软件的网络传输，但可能包括组织内物理副本的部门间传输。同时，许多国家的版权法以及某些国际版权条约都承认“向公众提供”或“向公众传播”是版权人的专有权利之一。

Therefore, the GPLv3 defines the term "propagate" by reference to
activities that require permission un- der "applicable copyright law",
but excludes execution and private modification from the definition.
GPLv3's definition also gives examples of activities that may be
included within "propagation" but it also makes clear that, under the
copyright laws of a given country, "propagation" may include other
activities as well.

因此，GPLv3 通过引用根据“适用版权法”需要许可的活动来定义术语“传播”，但从定义中排除了执行和私人修改。GPLv3 的定义还给出了可能包含在“传播”范围内的活动示例，但它也明确指出，根据特定国家/地区的版权法，“传播”也可能包括其他活动。

Thus, propagation is defined by behavior, and not by categories drawn
from some particular national copyright statute. This helps not only
with internationalization, but also factually-based terminology aids
in developers' and users' understanding of the GPL.

因此，传播是由行为定义的，而不是由某些特定国家版权法规中的类别定义的。这不仅有助于国际化，而且基于事实的术语有助于开发人员和用户理解 GPL。

As a further benefit, because "propagation" includes all exclusive
rights granted under any particular copyright regime, the term
automatically accounts for all exclusive rights under that regime.

作为进一步的好处，因为“传播”包括任何特定版权制度下授予的所有专有权，该术语自动说明该制度下的所有专有权。


### Convey

### 9.2.4 传达

Next, GPLv3 defines a subset of propagate --- "convey". Conveying
includes activities that constitute propagation of copies to others.
As with the definition of propagate, GPLv3 thus addresses transfers of
copies of software in behavioral rather than statutory terms. Any
propagation that enables other parties to receive or make copies of
the work, is called "conveying". Usually, conveying is the activity
that triggers most of the other obligations of GPLv3.

接下来，GPLv3 定义了传播的一个子集——“传达”（convey）。传送包括构成向他人传播副本的活动。与传播的定义一样，GPLv3 因此以行为而非法定条款处理软件副本的传输。使其他方能够接收或复制作品的任何传播都称为“传送”。通常，传送是触发 GPLv3 的大部分其他义务的活动。

### Appropriate Legal Notices

### 9.2.5 适当的法律声明

GPLv2 used the term "appropriate copyright notice and disclaimer of
warranty" in two places, which is a rather bulky term. Also,
experience with GPLv2 and other licenses that grant software freedom
showed throughout the 1990s that the scope of types of notices that
need preservation upon conveyance were more broad that merely the
copyright notices. The Appropriate Legal Notice definition
consolidates the material that GPLv2 traditionally required preserved
into one definition.

GPLv2 在两处使用了术语“适当的版权声明和免责声明”，这是一个相当庞大的术语。此外，GPLv2 和其他授予软件自由的许可的经验表明，在整个 1990 年代，需要在传输时保存的通知类型的范围比仅版权通知更广泛。适当的法律声明定义将 GPLv2 传统上要求保留的材料整合到一个定义中。

### Other Defined Terms

### 9.2.6 其他术语的定义

Note finally that not all defined terms in GPLv3 appear in GPLv3 0.
Specifically, those defined terms that are confined in use to a single
section are defined in the section in which they are used, and GPLv3 1
contains those definitions focused on source code. In this tutorial,
those defined terms are discussed in the section where they are
defined and/or used.

最后请注意，并不是所有 GPLv3 中定义的术语都出现在 GPLv3 第0条中。具体来说，那些被限制在单个部分中使用的定义术语在使用它们的部分中定义，而 GPLv3 条款一包含那些专注于源代码的定义。在本教程中，这些定义的术语将在定义和/或使用它们的部分进行讨论。

## GPLv3 §1: Understanding CCS

## 9.3 GPLv3 第1条：理解CCS

Ensuring that users have the source code to the software they receive
and the freedom to modify remains the paramount right embodied in the
Free Software Definition (found in
[1.1](#the-free-software-definition) of this tutorial). As such, GPLv3
1 is likely one of the most important sections of GPLv3, as it
contains all the defined terms related to this important software
freedom.

确保用户拥有他们收到的软件的源代码和修改的自由仍然是自由软件定义（参见本教程的 1.1 ）中体现的首要权利。因此，GPLv3 条款一可能是 GPLv3 最重要的部分之一，因为它包含与这一重要软件自由相关的所有定义条款。

### Source Code Definition

### 源代码的定义

First, GPLv3 1 retains GPLv2's definition of "source code" and adds an
explicit definition of "object code" as "any non-source version of a
work". Object code is not restricted to a narrow technical meaning and
is understood broadly to include any form of the work other than the
preferred form for making modifications to it. Object code therefore
includes any kind of transformed version of source code, such as
bytecode or minified Javascript. The definition of object code also
ensures that licensees cannot escape their obligations under the GPL
by resorting to shrouded source or obfuscated programming.

首先，GPLv3 条款一保留了 GPLv2 对“源代码”的定义，并将“目标代码”明确定义为“作品的任何非源版本”。目标代码并不局限于狭义的技术含义，而是广义地理解为包括除对其进行修改的首选形式之外的任何形式的作品。因此，目标代码包括任何类型的源代码转换版本，例如字节码或缩小的 Javascript。目标代码的定义还确保被许可人无法通过诉诸隐藏源代码或混淆编程来逃避 GPL 规定的义务。

### CCS Definition

### CCS的定义

The definition of CCS,[^3^](#_bookmark107) or, as GPLv3 officially
calls it, "Corresponding Source" in GPLv3 1 4 is possibly the most
complex definition in the license.

CCS 的定义[^3]，或 GPLv3 官方称之为 GPLv3 条款一 4 中的“对应源”可能是许可证中最复杂的定义。

[^3]:请注意，经常使用 GPLv2 和 GPLv3 的人的首选术语是“Complete Corresponding Source”，缩写为“CCS”。诚然，“完整”一词不再出现在 GPLv3 中（它使用“全部”一词代替）。然而，GPLv2 和 GPLv3 的早期草案本身都使用了“完整”一词，而早期的 GPLv3 草案甚至将这一定义术语称为“完整对应源”。同时，首字母缩略词“CCS”（有时称为“C&CS”）在 GPL 执法者中的使用如此广泛，以至于即使专注于 GPLv3 的专家倾向于只说定义的术语“对应源”，它的使用仍在继续。

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

CCS 的定义很宽泛，以保护用户行使其在 GPL 下的权利。该定义包括特定示例，以消除对它们被视为 CCS 的任何疑问。GPLv3 力求完全清楚地表明，被许可人无法通过将子程序组件动态链接到程序的原始版本来避免遵守 GPL 的要求。这些示例还阐明了相应源代码中包含的共享库和动态链接的子程序是作品“专门”设计需要的那些，这阐明了它们不包括作品调用的库，这些库可以很容易地被其他人替换现有的实施。虽然 Copyleft 倡导者从不怀疑这是 GPLv2 对 CCS 的定义所要求的，但 GPLv3 通过一个额外的例子使其非常清楚。

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

GPL 一如既往地寻求确保用户真正能够安装和运行他们修改后的程序版本； CCS 定义旨在扩展以确保这种软件自由。然而，尽管 CCS 的定义很广泛，但在许多情况下不足以保护用户的自由。例如，GPL 程序或此类程序的修改版本可能会被锁定和限制。GPLv3 条款六中的要求（在本教程的第 9.9 节中讨论）解决了这个问题。（GPLv3 的早期草案在 CCS 的定义中包含了这些要求；然而，鉴于锁定问题只出现在目标代码的分发中，将这些要求放在 GPLv3 直接处理目标代码的部分中更为合乎逻辑分配）。

The penultimate paragraph in GPLv3 2 notes that GPLv3's CCS definition
does not require source that can be automatically generated. Many code
generators, preprocessors and take source code as input and sometimes
even have output that is still source code. Source code should always
be whatever the original programmer preferred to modify.

GPLv3 第2条中的倒数第二段指出 GPLv3 的 CCS 定义不需要可以自动生成的源。许多代码生成器、预处理器和将源代码作为输入，有时甚至输出仍然是源代码。源代码应该始终是原始程序员喜欢修改的任何内容。

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

GPLv3 条款一的最后一段消除了关于应该在纯源代码发行版上做什么的任何歧义。具体而言，完全允许传输未编译、无法运行或处于实验性进行中工作的源代码的权利，前提是不传输任何目标代码形式。事实上，当结合 GPLv3 第5条中的许可时，很明显，如果一个人只传达源代码，就永远不会被要求提供更多。人们始终有权通过删除源代码作品的任何部分来修改源代码作品，并且可以不要求自由软件源代码是一个完整的功能程序。

### The System Library Exception

### 系统库例外

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

上一节跳过了 CCS 定义的一部分，即所谓的系统库异常。“系统库”定义（以及其中包含的“标准接口”和“主要组件”定义）旨在允许 copyleft 倡导者认为合理的某些分发安排。系统库例外旨在允许 copylefted 软件与这些库链接，而禁止该链接对软件自由的伤害大于对专有软件的伤害。系统库异常有两部分。(a) 部分重写了 GPLv2 例外，以清楚地将 GPLv2 的措辞“除非该组件本身伴随可执行文件”替换为“它不是主要组件的一部分”。这里的目标是不要求公开某些库的源代码，例如必要的 Microsoft Windows DLL（它们不是 Windows 内核的一部分，但伴随它）是为 Windows 编译的 copylefted 程序运行所必需的。

However, in isolation, (a) would be too permissive, as it would
sometimes allow distributors to evade important GPL requirements. Part
(b) reigns in (a). Specifically, (b) specifies only a few
functionalities that a system library may provide and still qualify
for the exception. The goal is to ensure system libraries are truly
adjunct to a major essential operating system component, compiler, or
interpreter. The more low-level the functionality provided by the
library, the more likely it is to be qualified for this exception.

但是，单独来看，(a) 过于宽容，因为它有时会允许发行商规避重要的 GPL 要求。(b) 部分优先于 (a) 部分。具体来说，(b) 仅指定了系统库可能提供的少数功能，并且仍然符合例外条件。目标是确保系统库真正附属于主要的基本操作系统组件、编译器或解释器。库提供的功能越低级，越有可能符合此异常。


Admittedly, the system library exception is a frequently discussed
topic of obsessed GPL theorists. The amount that has been written on
the system library exception (both the GPLv2 and GPLv3 versions of
it), if included herein, could easily increase this section of the
tutorial to a length greater than all the others.

诚然，系统库异常是痴迷于 GPL 的理论家经常讨论的话题。如果包含在系统库异常（它的 GPLv2 和 GPLv3 版本）上的数量，很容易将本教程的这一部分增加到比其他所有部分都长的长度。

Like any exception to the copyleft requirements of GPL, would-be GPL
violators frequently look to the system library exception as a
potential software freedom circumvention technique. When considering
whether or not a library qualifies for the system library exception,
here is a pragmatic thesis to consider, based on the combined decades
of experience in GPL interpretation of this tutorial's authors: the
harder and more strained the reader must study and read the system
library exception, the more likely it is that the library in question
does not qualify for it.

与 GPL 的 copyleft 要求的任何例外一样，潜在的 GPL 违反者经常将系统库例外视为潜在的软件自由规避技术。在考虑一个库是否符合系统库例外条件时，根据本教程作者数十年的 GPL 解释经验，这里有一个实用的论点需要考虑：读者必须越努力、越紧张地学习和阅读系统 library exception，有问题的图书馆越有可能不符合条件。

## GPLv3 §2: Basic Permissions

## 9.4 GPLv3 第2条：基本权利

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

GPLv3 条款可以粗略地视为等同于 GPLv2 第0条（在本教程的 3.1 中讨论）。但是，这里也可以找到 GPLv3 中常见的改进方式。例如，GPLv3 条款二的第一句进一步推进了目标国际化。根据某些国家/地区的版权法，版权许可可能需要包括明确规定授予权利的期限。在包括美国在内的其他国家，这样的规定是不必要的，但却是允许的。GPLv3 条款二第1项还承认 GPL 下的被许可人享有版权合理使用权或适用法律下的同等权利。这些权利与自由相容而不冲突GPL 寻求保护的内容，而 GPL 不能也不应该限制它们。

However, note that (sadly to some copyleft advocates) the unlimited
freedom to run is confined to the *unmodified* Program. This
confinement is unfortunately necessary since Programs that do not
qualify as a User Product in GPLv3 6 (see [9.9.2](#user-products) in
this tutorial) might have certain unfortunate restrictions on the
freedom to run.[^4^](#_bookmark110)

然而，请注意（对某些 copyleft 拥护者而言令人遗憾的是）无限的运行自由仅限于未修改的程序。不幸的是，这种限制是必要的，因为在 GPLv3 条款六中不符合用户产品资格的程序（请参阅本教程中的 9.9.2）可能对运行自由有某些不幸的限制[^4]。

[^4]: 详见本教程的§1.1.1“运行的自由”。

GPLv3 2 2 distinguishes between activities of a licensee that are
permitted without limitation and activities that trigger additional
requirements. Specifically, GPLv3 2 2 guarantees the basic freedoms of
privately modifying and running the program. While these basic
freedoms were generally considered a standard part of users' rights
under GPLv2 as well, the GPLv3 states them herein more explicitly. In
other words, there is no direct analog to the first sentence of GPLv3
2 2 in GPLv2 (See [5.1.3](#right-to-private-modification) of this
tutorial for more on this issue.)

GPLv3 第2条第2款区分被许可人允许但不限于的活动和触发额外要求的活动。具体来说，GPLv3 第2条第2款保证了私下修改和运行程序的基本自由。虽然这些基本自由通常也被视为 GPLv2 下用户权利的标准部分，但 GPLv3 在此更明确地说明了它们。换句话说，在 GPLv2 中没有直接模拟 GPLv3 条款二第2项的第一句（有关此问题的更多信息，请参见本教程的 5.1.3。）

Also, GPLv3 2 2 gives an explicit permission for a client to provide a
copy of its modified software to a contractor exclusively for that
contractor to modify it further, or run it, on behalf of the client.
However, the client can *only* exercise this control over its own
copyrighted changes to the GPL-covered program. The parts of the
program it obtained from other contributors must be provided to the
contractor with the usual GPL freedoms. Thus, GPLv3 permits users to
convey covered works to contractors operating exclusively on the users' behalf, under the users' direction and control, and to
require the contractors to keep the users' copyrighted changes
confidential, but *only if* the contractor is limited to acting on the
users' behalf (just as the users' employees would have to act).

此外，GPLv3 第2条第2款明确允许客户向承包商提供其修改后软件的副本，专供承包商代表客户进一步修改或运行。但是，客户只能对其自己对受 GPL 保护的程序的版权更改行使此控制权。它从其他贡献者那里获得的程序部分必须以通常的 GPL 自由提供给承包商。因此，GPLv3 允许用户将涵盖的作品传送给专门在代表用户，在用户的指导和控制下，并要求承包商对用户的受版权保护的更改保密，但前提是承包商仅限于代表用户行事（就像用户的员工会行动）。


The strict conditions in this "contractors provision" are needed so
that it cannot be twisted to fit other activities, such as making a
program available to downstream users or customers. By making the
limits on this provision very narrow, GPLv3 ensures that, in all other
cases, contractor gets the full freedoms of the GPL that they deserve.

需要此“承包商条款”中的严格条件，以使其不能被扭曲以适应其他活动，例如向下游用户或客户提供程序。GPLv3 使这一条款的限制非常狭窄，确保在所有其他情况下，承包商获得他们应得的 GPL 的全部自由。

The FSF was specifically asked to add this "contractors provisions" by
large enterprise users of Free Software, who often contract with
non-employee developers, working offsite, to make modifications
intended for the user's private or internal use, and often arrange
with other companies to operate their data centers. Whether GPLv2
permits these activities is not clear and may depend on variations in
copyright law in different jurisdictions. The practices seem basically
harmless, so FSF decided to make it clear they are permitted.

FSF 被自由软件的大型企业用户特别要求添加这个“承包商规定”，他们经常与非雇员开发人员签订合同，在异地工作，进行修改供用户私人或内部使用，并经常与其他公司安排运营他们的数据中心。GPLv2 是否允许这些活动尚不清楚，可能取决于不同司法管辖区版权法的变化。这些做法基本上看起来是无害的，因此 FSF 决定明确表示它们是允许的。


GPLv3 2's final paragraph includes an explicit prohibition of
sublicensing. This provision ensures that GPL enforcement is always by
the copyright holder. Usually, sublicensing is regarded as a practical
convenience or necessity for the licensee, to avoid having to
negotiate a license with each licensor in a chain of distribution. The
GPL solves this problem in another way --- through its automatic
licensing provision found in GPLv3 *§*10 (which is discussed in more
detail in *§* [9.13](#gplv3-10-explicit-downstream-license) of this
tutorial).

GPLv3 第2条的最后一段明确禁止再许可。此条确保 GPL 强制执行始终由版权所有者执行。通常，再许可被认为是被许可人的实际便利或必要，以避免必须与分销链中的每个许可人协商许可。GPL 以另一种方式解决了这个问题——通过 GPLv3 第10条中的自动许可条款（在本教程的第 9.13 节中有更详细的讨论）。

## GPLv3's views on DRM and Device Lock-Down

## 9.5 GPLv3 对 DRM 和设备锁定的看法

The issues of DRM, device lock-down and encryption key disclosure were
the most hotly debated during the GPLv3 process. FSF's views on this
were sadly frequently misunderstood and, comparing the provisions
related to these issues in the earliest drafts of GPLv3 to the final
version of GPLv3 shows the FSF's willingness to compromise on tactical
issues to reach the larger goal of software freedom.

DRM、设备锁定和加密密钥泄露等问题是 GPLv3 过程中争论最激烈的问题。遗憾的是，FSF 对此的看法经常被误解，将 GPLv3 最早草案中与这些问题相关的条款与 GPLv3 的最终版本进行比较，表明 FSF 愿意在战术问题上做出妥协，以实现更大的软件自由目标。

Specifically, GPLv3 introduced provisions that respond to the growing
practice of distributing GPL- covered programs in devices that employ
technical means to restrict users from installing and running modified
versions. This practice thwarts the expectations of developers and
users alike, because the right to modify is one of the core freedoms
the GPL is designed to secure.

具体来说，GPLv3 引入了一些条款，以应对越来越多的在设备中分发 GPL 覆盖程序的做法，这些设备采用技术手段来限制用户安装和运行修改版本。这种做法违背了开发人员和用户的期望，因为修改权是 GPL 旨在保护的核心自由之一。

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

破坏用户权利的技术措施。这些措施通常用这样的奥威尔式短语来描述，例如“数字版权管理”实际上意味着限制或彻底破坏用户的合法权利，或者“可信计算”实际上意味着向人们出售他们不信任的计算机。然而，这些措施在一个基本方面是相似的。他们都采用技术手段将版权法体系（版权持有者的权力是一般自由的有限例外）变成虚拟监狱，凡是未明确允许的事情都被完全禁止。这种“副版权”系统是在编写 GPLv2 之后很久就创建的——最初是通过美国和欧盟的立法，后来也通过其他司法管辖区的立法。该立法规定了严重的民事甚至刑事处罚以逃避这些限制（通常被恰当地称为“越狱设备”），即使这样做的目的是恢复用户的合法权利，而该技术错误地阻止了他们使用。GPLv2 没有解决使用技术措施收回 GPL 授予的权利的问题，因为这些措施在 1991 年不存在，并且与当时向用户交付软件的形式无关。GPLv3 解决了这些问题，特别是因为 copylefted 软件永远是更广泛地嵌入到对用户更改它的自由施加技术限制的设备中。

However, FSF always made a clear distinction to avoid conflating these
"lock-down" measures with legitimate applications that give users
control, as by enabling them to choose higher levels of system or data
security within their networks, or by allowing them to protect the
security of their communications using keys they can generate or copy
to other devices for sending or receiving messages. Such technologies
present no obstacles to software freedom and the goals of copyleft.

然而，FSF 始终明确区分以避免将这些“锁定”措施与赋予用户控制权的合法应用程序混为一谈，例如通过使他们能够在其网络中选择更高级别的系统或数据安全，或通过允许他们保护使用他们可以生成或复制到其他设备以发送或接收消息的密钥来确保他们的通信安全。这些技术对软件自由和 copyleft 的目标没有任何障碍。

The public GPLv3 drafting process sought to balance these positions of
copyleft advocates with various disparate views of the larger
Free-Software-using community. Ultimately, FSF compromised to the
GPLv3 3 and GPLv3 6 provisions that, taken together, are a minimalist
set of terms sufficient to protect the software freedom against the
threat of invasive para-copyright.

公共 GPLv3 起草过程试图平衡 copyleft 倡导者的这些立场与更大的自由软件使用社区的各种不同观点。最终，FSF 妥协于 GPLv3 第3条和第6条，这些条款合在一起是一组足以保护软件自由免受侵犯性准版权威胁的极简主义条款。

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

做出的妥协最终是相当合理的。第一个体现在 GPLv3 第6条的“用户产品”定义（详见本教程9.9.2）。此外，一些早期 GPLv3 草案的读者似乎认为 GPLv3 包含对 DRM 的全面禁止； 但事实并非如此。事实上，GPLv3 的任何部分都没有禁止对非 GPL 作品进行 DRM； 相反，GPLv3 禁止使用 DRM，专门用于锁定限制用户安装 GPL 软件本身的修改版本的能力，但同样仅限于用户产品。

## GPLv3 §3: What Hath DMCA Wrought

## 9.6 GPLv3 第三款：DMCA做了什么

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

如本教程 1.2.3 中所述，17 USC 1201 和相关部[^5]禁止用户规避实施 DRM 的技术措施。由于这是版权法的一部分，而 GPL 主要是版权许可，而 DMCA 所说的“规避”只是 GPL 下的“修改软件”，因此 GPLv3 必须否认此类反规避条款不适用于 GPLv3 的软件。GPLv3 第三款保护用户在 GPL 允许的范围内行使他们在 GPL 项下的权利时免于承担反规避法规定的责任。

[^5]:USC 的这些部分通常被称为“数字千年版权法”或“DMCA”，因为这是对 USC 这些部分进行如此修改的法案的名称。

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

首先，GPLv3 第3条第1款声明任何 GPL 程序都不是有效技术保护措施的一部分，无论该程序做什么。GPLv3 第3条第1款的早期草案直接引用了 DMCA，但最终版本反而包含了对根据 1996 年 WIPO 条约和任何类似法律颁布的反规避法的国际法律引用。美国境外的律师担心，美国法定参考可能被解读为表明选择将美国法律应用于整个许可。尽管 FSF 不一定同意该观点，但 FSF 还是决定参考 WIPO 条约而不是 DMCA，因为一些国家的反规避法律在实施中已经（或可能）在结构上更类似于 DMCA 的反规避条款 产权组织。此外，添加“或类似法律”提供了适当的包罗万象。

GPLv3 3 2 states precisely that a conveying party waives the power to
forbid circumvention of techno- logical measures only to the extent
that such circumvention is accomplished through the exercise of GPL
rights in the conveyed work. GPLv3 3 2 makes clear that the referenced
"legal rights" are specifically rights arising under anticircumvention
law. and refers to both the conveying party's rights and to third
party rights, as in some cases the conveying party will also be the
party legally empowered to enforce or invoke rights arising under
anticircumvention law.

GPLv3 第3条第2款明确指出，仅当这种规避是通过在所传送的作品中行使 GPL 权利来实现时，传送方才放弃禁止规避技术措施的权力。GPLv3 第3条第2款明确指出，所引用的“合法权利”是根据反规避法产生的具体权利。并且指的是转让方的权利和第三方的权利，因为在某些情况下，转让方也将是依法有权执行或援引反规避法规定的权利的一方。

These disclaimers by each licensor of any intention to use GPL'd
software to stringently control access to other copyrighted works
should effectively prevent any private or public parties from invoking
DMCA-like laws against users who escape technical restriction measures
implemented by GPL'd software.

每个许可方的这些关于使用 GPL 软件严格控制对其他受版权保护作品的访问的意图的免责声明应该有效地防止任何私人或公共团体援引类似 DMCA 的法律来对付那些逃避 GPL 软件实施的技术限制措施的用户。

## GPLv3 §4: Verbatim Copying

## 9.7 GPLv3 第4条：逐字复制

GPLv3 4 is a revision of GPLv2 1 (as discussed in
[3.2](#gplv2-1-verbatim-copying) of this tutorial). There are almost
no changes to this section from the GPLv2 1, other than to use the new
defined terms.

GPLv3 第4条是 GPLv2 第1条的修订版（如本教程 3.2 中所述）。除了使用新定义的术语外，GPLv2 第1条的这一部分几乎没有变化。

The only notable change, of "a fee" to "any price or no price", is in
the first sentence of GPLv3 4 2. The GPLv2 1 1 means that the GPL
permits one to charge money for the distribution of software. Despite
efforts by copyleft advocates to explain this in GPLv2 itself and in
other documents, there are evidently some people who still believe
that GPLv2 allows charging for services but not for selling copies of
software and/or that the GPL requires downloads to be gratis. Perhaps
this is because GPLv2 referred to charging a "fee"; the term "fee" is
generally used in connection with services.

唯一值得注意的变化是 GPLv3 第4条第2款的第一句中将“收费”改为“任何价格或无价格”。GPLv2 第1条第1款表示 GPL 允许对软件分发收费。尽管 copyleft 拥护者努力在 GPLv2 本身和其他文档中解释这一点，但显然仍有一些人认为 GPLv2 允许对服务收费但不允许销售软件副本和/或 GPL 要求免费下载。也许这是因为 GPLv2 提到了收取“费用”； “费用”一词通常与服务相关。


GPLv2's wording also referred to "the physical act of transferring."
The intention was to distinguish charging for transfers from attempts
to impose licensing fees on all third parties. "Physical" might be
read, however, as suggesting "distribution in a physical medium only".

GPLv2 的措辞还提到了“传输的物理行为”。目的是将转让收费与向所有第三方征收许可费的尝试区分开来。然而，“物理”可能被解读为暗示“仅在物理介质中分发”。

To address these two issues, GPLv3 says "price" in place of "fee," and
removes the term "physical." GPLv3 *§*4 has also been revised from its
corresponding section in GPLv2 in light of the GPLv3 *§*7 (see

*§* [9.9.3](#gplv3-7-additional-permissions) in this tutorial for
more). Specifically, a distributor of verbatim copies of the program's
source code must obey any existing additional terms that apply to
parts of the program pursuant to GPLv3 []{#_bookmark114 .anchor}*§*7.
In addition, the distributor is required to keep intact all license
notices, including notices of such additional terms.

为了解决这两个问题，GPLv3 用“价格”代替“费用”，并删除了“物理”一词。GPLv3 第4条也根据 GPLv3 第7条对 GPLv2 中的相应部分进行了修订（有关更多信息，请参见本教程的第 9.9.3 节）。具体来说，程序源代码的逐字副本的分发者必须遵守根据 GPLv3 适用于程序部分的任何现有附加条款。此外，经销商必须完整保留所有许可通知，包括此类附加条款的通知。

Finally, there is no harm in explicitly pointing out what ought to be
obvious: that those who convey GPL-covered software may offer
commercial services for the support of that software.

最后，明确指出应该显而易见的事情并没有什么害处：那些传送 GPL 软件的人可能会提供商业服务来支持该软件。

## GPLv3 §5: Modified Source

## 9.8 GPLv3 第5条：修改源代码

GPLv3 5 is the rewrite of GPLv2 2, which was discussed in
[5.1](#gplv2-2-share-and-share-alike) of this tutorial. This section
discusses the changes found in GPLv3 5 compared to GPLv2 2.

GPLv3 第5条是 GPLv2 第5条的重写，在本教程的 5.1 中讨论过。本节讨论 GPLv3 第5条与 GPLv2 第2条相比的变化。

GPLv3 5(a) still requires modified versions be marked with "relevant
date", but no longer says "the date of any change". The best practice
is to include the date of the latest and/or most significant changes
and who made those. Of course, compared to its GPLv2 2(a), GPLv3 5(a)
slightly relaxes the requirements regarding notice of changes to the
program. In particular, the modified files themselves need no longer
be marked. This reduces administrative burdens for developers of
modified versions of GPL'd software.

GPLv3 5(a) 仍然要求修改版本标明“relevant date”，但不再写“date of any change”。最佳做法是包括最新和/或最重要更改的日期以及进行这些更改的人员。当然，与其 GPLv2 2(a) 相比，GPLv3 5(a) 稍微放宽了对程序变更通知的要求。特别是，修改后的文件本身不再需要标记。这减轻了 GPL 软件修改版本开发人员的管理负担。

GPLv3 5(b) is a new but simple provision. GPLv3 5(b) requires that the
license text itself must be unmodified (except as permitted by GPLv3
7; see [9.9.3](#gplv3-7-additional-permissions) in this tutorial).
Furthermore, it removes any perceived conflict between the words "keep
intact all notices" in GPLv3 4, since operating under GPLv3 5 still
includes all the requirements of GPLv3 4 by reference.

GPLv3 5(b) 是一项新的但简单的规定。GPLv3 5(b) 要求许可证文本本身必须未经修改（除非 GPLv3 7 允许；请参阅本教程中的 9.9.3）。此外，它消除了 GPLv3 第4条中“保持所有通知完整”一词之间的任何明显冲突，因为在 GPLv3 第5条下运行仍然通过引用包含 GPLv3 第4条的所有要求。


GPLv3 5(c) is the primary source-code-related copyleft provision of
GPL. (The object-code-related copy- left provisions are in GPLv3 6,
discussed in [9.9](#gplv3-6-non-source-and-corresponding-source) of
this tutorial). Compared to GPLv2 2(b), GPLv3 5(c) states that the GPL
applies to the whole of the work. Such was stated already in GPLv2
2(b), in "in whole or in part", but this simplified wording makes it
clear it applies to the entire covered work.

GPLv3 第5条 c 项是 GPL 中与源代码相关的主要 copyleft 条款。（与目标代码相关的版权条款在 GPLv3 第六款中，在本教程的 9.9 中讨论）。与 GPLv2 2(b) 相比，GPLv3 第5条 c 项声明 GPL 适用于整个作品。GPLv2 2(b) 中已经以“全部或部分”的形式说明了这一点，但这种简化的措辞清楚地表明它适用于整个涵盖的作品。

Another change in GPLv3 5(c) is the removal of the words "at no
charge," which was often is misunder- stood upon na¨ıve reading of in
GPLv2 (b) (as discussed in [5.1.2](#gplv2-2b) of this tutorial).

GPLv3 第5条 c 项的另一个变化是删除了“免费”一词，这在天真阅读 GPLv2 (b) 时经常被误解（如本教程的 5.1.2 中所述）。

Note that of GPLv2 2's penultimate and ante-penultimate paragraphs are
now handled adequately by the definitions in GPLv3 0 and as such, have
no direct analogs in GPLv3.

请注意，GPLv2 第2条的倒数第二个和倒数第二个段落现在已由 GPLv3 第0条中的定义充分处理，因此，在 GPLv3 中没有直接类似物。

GPLv2 2's final paragraph, however, is reworded and expanded into the
final paragraph of GPLv3 5, which now also covers issues related to
copyright compilations (but not compilations into object code ---
that's in the next section!). The intent and scope is the same as was
intended in GPLv2.

然而，GPLv2 第2条的最后一段被改写并扩展到 GPLv3 第5条的最后一段，现在还涵盖了与版权编译相关的问题（但不包括编译成目标代码——那是在下一节！）。意图和范围与 GPLv2 中的意图和范围相同。

## GPLv3 §6: Non-Source and Corresponding Source

## 9.9 GPLv3 第6条：非源代码和对应源代码

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

GPLv3 第6条规定了分发程序“非源代码形式”（即 CCS 以外的任何形式）的合规义务。如 9.2 中所述，GPLv3 中的“目标代码”被广泛定义为作品的任何非源版本，因此不仅包括二进制文件或可执行文件，还包括混淆、最小化、压缩或其他非首选形式修改。因此，GPLv3 第六款澄清并修订了 GPLv2 第三款。事实上，GPLv3 第六款的 CCS 要求与 GPLv2 第三款的规定非常相似，其变化旨在使合规供应在当代技术条件下更容易。GPLv3 目标代码的分发者必须以四种指定方式之一提供对相应源代码的访问。


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

GPLv3 6(a–b) 现在专门适用于在物理产品中分发目标代码。物理产品包括嵌入式系统，以及物理软件分发介质，例如 CD。与 GPLv2 第3条（在本教程的 5.2 中讨论）一样，目标代码的分发可能伴随着机器可读的源代码，或者它可能伴随着提供机器可读源代码的有效书面报价。但是，与 GPLv2 不同的是，任何第三方都不能行使该要约； 相反，只有那些“拥有目标代码”的人才能行使要约。（请注意，这是对要约履行要求的实质性缩小，并且是对 GPLv3 比 GPLv2 有更多要求的说法提出异议的一个很好的反例。）

GPLv3 6(b) further revises the requirements for the written offer to
provide source code. As before, the offer must remain valid for at
least three years. In addition, even after three years, a distributor
of a product containing GPL'd object code must offer to provide source
code for as long as the distributor also continues to offer spare
parts or customer support for the product model. This is a reasonable
and appropriate requirement; a distributor should be prepared to provide
source code if he or she is prepared to provide support for other
aspects of a physical product.

GPLv3 第六款(b) 进一步修改了对书面报价提供源代码的要求。和以前一样，要约必须至少保持3年有效。此外，即使在3年后，包含 GPL 目标代码的产品的分销商也必须提供源代码，只要该分销商还继续为该产品模型提供备件或客户支持。这是一个合理且适当的要求； 如果分销商准备为物理产品的其他方面提供支持，则他或她应该准备好提供源代码。


GPLv3 6(a--b) clarifies that the medium for software interchange on
which the machine-readable source code is provided must be a durable
physical medium. GPLv3 6(b)(2), however, permits a distributor to
instead offer to provide source code from a network server instead,
which is yet another example GPLv3 looser in its requirements than
GPLv2 (see [5.2.2](#additional-source-provision-options) for details).

GPLv3 第6条(a–b) 阐明了提供机器可读源代码的软件交换介质必须是耐用的物理介质。然而，GPLv3 第6条(b)(2) 允许发行商转而提议从网络服务器提供源代码，这是 GPLv3 的要求比 GPLv2 宽松的另一个例子（详见 5.2.2）。

GPLv3 6(c) gives narrower permission than GPLv2 3(c). The "pass along"
option for GPLv3 6(c)(1) offers is now available only for individual
distribution of object code; moreover, such individual distribution
can occur only "occasionally and noncommercially." A distributor
cannot comply with the GPL merely by making object code available on a
publicly-accessible network server accompanied by a copy of the
written offer to provide source code received from an upstream
distributor.

GPLv3 第6条（c）提供比 GPLv2 第3条（c）更窄的许可。GPLv3 第6条（c）(1) 所述的“传递”选项现在仅适用于目标代码的单独分发； 此外，这种个人分发只能“偶尔且非商业性地”发生。分销商不能仅通过在可公开访问的网络服务器上提供目标代码并附上书面报价的副本以提供从上游分销商收到的源代码来遵守 GPL。

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

GPLv3 第6条(d) 修改并改进了 GPLv2 第3条的最后一段。当通过提供从指定位置复制代码的访问权限（例如通过启用对网络服务器的电子访问权限）来提供目标代码时，分销商必须仅提供等效的访问权限以“以相同方式通过相同位置”复制源代码 ”。该措辞还允许分销商在单个网络门户或网页上向第三方提供对目标代码和源代码的访问权限，即使该访问权限可能包含指向不同物理服务器的链接。例如，下游分销商可以提供到上游分销商服务器的链接，并与该服务器的运营商安排，只要下游分销商能够访问目标代码，就可以保持源代码可供复制。因此，分发目标代码的一方仍有义务在显着位置（“目标代码下载旁边”）指向第三方源代码供应服务器，并确保该第三方服务器在规定的时间内保持运行。这正式编纂了 GPLv2 的典型历史解释。


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

此外，根据 GPLv3 第6条(d)，分销商可以对传送的目标代码收费； 但是，那些为获得目标代码而付费的人必须获得同等的免费访问权限才能获得 CCS。（如果分销商免费提供目标代码，分销商必须同样免费提供 CCS。）那些没有从分销商那里获得目标代码的人（可能是因为他们选择不支付目标代码的费用）不在范围之内。条款; 分销商没有特定义务向未根据 GPLv3 第六款(d) 购买目标代码下载的人提供 CCS。（注意：这不会改变或影响 GPLv3 第6条(b)(2) 下的任何义务；GPLv3 第6条(d) 是完全不同的规定。）

### GPLv3 §6(e): Peer-to-Peer Sharing Networks

### GPLv3 第6条e款：点对点共享网络


GPLv3 6(e) allows provision of CCS via another server when the binary
or other non-source form is dis- tributed by peer-to-peer protocols
such as BitTorrent. Here the requirement is only that each peer be
effectively informed of the location of the source code on a server as
above.

当二进制或其他非源代码形式通过对等协议（如 BitTorrent）分发时，GPLv3 第6条(e) 允许通过另一台服务器提供 CCS。这里的要求只是像上面那样有效地通知每个对等方源代码在服务器上的位置。

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

GPLv3 确实需要添加这一内容，尽管它增加了 GPL 关键部分的复杂性。特别是，去中心化点对点文件共享对 GPLv2 和 GPLv3 初始草案中隐含的单向分发视图提出了挑战。在 BitTorrent 分发中识别上游/下游链接既不简单也不合理； 这种分布是多向的、合作的和（有点）匿名的。在点对点分发系统中，参与者既充当特定文件块的发送者又充当接收者，但他们仅将体验视为用户和接收者，而不是任何传统意义上的分发者。在任何给定的时刻，大多数同行都不会拥有完整的文件。

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
effective seeding and distribution.

同时，GPLv3 第6条(d) 允许通过网络以目标代码形式分发作品，前提是分发者提供同等访问权限以“以相同方式通过相同位置”复制相应的源代码。如果二进制文件与 CCS 打包在一起，则该措辞可能被解释为允许二进制文件的点对点分发，但至少出于三个原因，这种打包是不切实际的。首先，即使 CCS 与目标代码打包在一起，它也只能在分发过程结束时供非播种对等方使用，但对等方已经向网络中的其他人提供了部分二进制文件。其次，在实践中，点对点传输形式不太适合分发 CCS。在大型发行版中，将 CCS 与目标代码打包在一起可能会导致文件大小和传输时间大幅增加。第三，在目前的实践中，CCS 包本身往往不通过 BitTorrent 传输——由于需求减少——因此，通常同时下载相同源包的参与者太少，无法实现有效的播种和分配。

GPLv3 6(e) addresses these issues. If a licensee conveys such a work
of object code using peer-to-peer transmission, that licensee is in
compliance with GPLv3 6 if the licensee informs other peers where the
object code and its CCS are publicly available at no charge under
subsection GPLv3 6(d). The CCS therefore need not be provided through
the peer-to-peer system that was used for providing the binary.

GPLv3 第6条(e) 解决了这些问题。如果被许可人使用点对点传输传送此类目标代码作品，如果被许可人根据 GPLv3 第6条通知其他同行目标代码及其 CCS 是免费公开可用的，则该被许可人符合 GPLv3 第6条（ d). 因此，不需要通过用于提供二进制文件的对等系统来提供 CCS。

Second, GPLv3 9 also clarifies that ancillary propagation of a covered
work that occurs as part of the process of peer-to-peer file
transmission does not require acceptance, just as mere receipt and
execution of the Program does not require acceptance. Such ancillary
propagation is permitted without limitation or further obligation.

其次，GPLv3 第9条还阐明了作为点对点文件传输过程的一部分发生的涵盖作品的辅助传播不需要接受，就像仅仅接收和执行程序不需要接受一样。这种辅助传播是允许的，没有限制或进一步的义务。

### User Products, Installation Information and Device Lock-Down

### 用户产品、安装信息和设备锁定
As discussed in [9.5](#gplv3s-views-on-drm-and-device-lock-down) of
this tutorial, GPLv3 seeks to thwart technical measures such as
signature checks in hardware to prevent modification of GPL'd software
on a device.

正如本教程 9.5 中所讨论的，GPLv3 试图阻止技术措施，例如硬件中的签名检查，以防止在设备上修改 GPL 软件。

To address this issue, GPLv3 6 requires that parties distributing
object code provide recipients with the source code through certain
means. When those distributors pass on the CCS, they are also required
to pass on any information or data necessary to install modified
software on the particular device that included it. (This strategy is
not unlike that used in LGPLv2.1 to enable users to link proprietary
programs to modified libraries.)

为了解决这个问题，GPLv3 第6条要求分发目标代码的各方通过某种方式向接收者提供源代码。当这些分销商传递 CCS 时，他们还需要传递在包含它的特定设备上安装修改后的软件所需的任何信息或数据。（此策略与 LGPLv2.1 中使用的策略没有什么不同，使用户能够将专有程序链接到修改后的库。）


#### User Products

#### 用户产品

The scope of these requirements is narrow. GPLv3 6 introduces the
concept of a "User Product", which includes devices that are sold for
personal, family, or household use. Distributors are only required to
provide Installation Information when they convey object code in a
User Product.

这些要求的范围很窄。GPLv3 第6条引入了“用户产品”的概念，其中包括为个人、家庭或家庭使用而销售的设备。当经销商在用户产品中传送目标代码时，他们只需要提供安装信息。

In brief, the right to convey object code in a defined class of "User
Products," under certain circumstances, depends on providing whatever
information is required to enable a recipient to replace the object
code with a functioning modified version.

简而言之，在某些情况下，在定义的“用户产品”类别中传送目标代码的权利取决于提供使接收者能够使用功能修改版本替换目标代码所需的任何信息。

This was a compromise that was difficult for the FSF to agree to
during the GPLv3 drafting process. However, companies and governments
that use specialized or enterprise-level computer facilities reported
that they actually *want* their systems not to be under their own
control. Rather than agreeing to this as a concession, or bowing to
pressure, they ask for this as a *preference*. It is not clear that
the GPL should interfere here, since the main problem lies elsewhere.

这是 FSF 在 GPLv3 起草过程中难以同意的妥协。然而，使用专业或企业级计算机设施的公司和政府报告称，他们实际上希望自己的系统不受自己的控制。他们没有将此作为让步或屈服于压力而同意，而是将此视为一种偏好。不清楚 GPL 是否应该干预这里，因为主要问题在别处。尽管在任何情况下对修改施加技术障碍都是错误的，但受限设备在当今最实际关注的领域属于用户产品定义。大多数（如果不是全部）运行受 GPL 保护的程序的技术限制设备都是消费电子设备。此外，制造商和这些用户之间的影响力悬殊，使得用户很难以其微弱和无组织的市场力量拒绝技术限制。即使仅限于用户产品，该条款也解决了根本问题。


While imposing technical barriers to modification is wrong regardless
of circumstances, the areas where restricted devices are of the
greatest practical concern today fall within the User Product
definition. Most, if not all, technically-restricted devices running
GPL-covered programs are consumer electronics devices. Moreover, the
disparity in clout between the manufacturers and these users makes it
difficult for the users to reject technical restrictions through their
weak and unorganized market power. Even limited to User Products, this
provision addresses the fundamental problem.

用户产品定义的核心是根据美国联邦消费者保护法 Magnuson-Moss 保修法改编的“消费品”的子定义，该法案载于 15 USC 2301：“任何通常用于个人、 家庭或家庭目的。” 美国在以有利于消费者权利的方式对此定义进行自由司法和行政解释已有 30 年的经验[^6]。理想情况下，该解释体系[^7]将指导对 GPLv3 6 中消费品子定义的解释，并且这有望为设备制造商和下游被许可人提供一定程度的法律确定性。

[^6]:Magnuson-Moss 消费品定义本身在美国和加拿大具有影响力，已被多个州和省的消费者保护法采纳。

[^7]:然而，FSF 非常清楚，纳入此类法律解释绝不是为了作为美国法律对 GPLv3 的一般选择。

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

Magnuson-Moss 下的一个公认的解释原则是解决歧义以支持覆盖。也就是说，在不清楚产品是否属于消费品定义的情况下，该产品将被视为消费品[^8]。此外，对于给定的产品，“通常使用”被理解为是指 该类型产品的典型用途，而不是特定用途

One well-established interpretive principle under Magnuson-Moss is
that ambiguities are resolved in favor of coverage. That is, in cases
where it is not clear whether a product falls under the definition of
consumer product, the product will be treated as a consumer
product.[^8^](#_bookmark122) Moreover, for a given product, "normally
used" is understood to refer to the typical use of that type of
product, rather than a particular use by

[^8]:16 CFR § 700.1(a)； McFadden 诉 Dryvit Systems, Inc., 54 UCC Rep. Serv.2d 934 (D. Ore. 2004)。

a particular buyer. Products that are commonly used for personal as
well as commercial purposes are consumer products, even if the person
invoking rights is a commercial entity intending to use the product
for commercial purposes.[^9^](#_bookmark124) Even a small amount of
"normal" personal use is enough to cause an entire product line to be
treated as a consumer product under
Magnuson-Moss.[^10^](#_bookmark125)

一个特定的买家。通常用于个人和商业目的的产品是消费品，即使调用权利的人是打算将产品用于商业目的的商业实体[^9]。即使是少量的“正常”个人使用也足够了 使整个产品线在 Magnuson-Moss 下被视为消费品[^10]。

^9^16 CFR 700.1(a). Numerous court decisions
interpreting Magnuson-Moss are in accord; see, e.g., *Stroebner
Motors, Inc.* []{#_bookmark125 .anchor}*v. Automobili Lamborghini
S.p.A.*, 459 F. Supp.2d 1028, 1033 (D. Hawaii 2006).

[^9]:16 美国联邦法规 700.1(a)。许多解释 Magnuson-Moss 的法院判决是一致的； 参见，例如，Stroebner Motors, Inc. []{#_bookmark125 .anchor}v。Automobili Lamborghini S.p.A.，459 F. Supp.2d 1028, 1033（D. Hawaii 2006）。

^10^*Tandy Corp. v. Marymac Industries, Inc.*, 213 U.S.P.Q. 702 (S.D.
Tex. 1981). In this case, the court concluded that TRS-80
microcomputers were consumer products, where such computers were
designed and advertised for a variety of users, []{#_bookmark126
.anchor}including small businesses and schools, and had only recently
been promoted for use in the home.

[^10]:Tandy Corp. 诉 Marymac Industries, Inc.，213 U.S.P.Q. 702（S.D. Tex. 1981）。在本案中，法院得出结论认为 TRS-80 微型计算机是消费品，此类计算机是为各种用户设计和宣传的，包括小型企业和学校，并且最近才被推广用于 在家里使用。

However, Magnuson-Moss is not a perfect fit because in the area of
components of dwellings, the settled interpretation under
Magnuson-Moss is under-inclusive. Depending on how such components are
manufac- tured or sold, they may or may not be considered
Magnuson-Moss consumer products.[^11^](#_bookmark126) Therefore, GPLv3
defines User Products as a superset of consumer products that also
includes "anything designed or sold for incorporation into a
dwelling."

然而，Magnuson-Moss 并不是一个完美的选择，因为在住宅的组成部分，Magnuson-Moss 下的固定解释是包容性不足的。根据此类组件的制造或销售方式，它们可能被视为也可能不被视为 Magnuson-Moss 消费产品[^11]。因此，GPLv3 将用户产品定义为消费产品的超集，其中还包括“任何为公司设计或销售的产品” 住处。”

^11^Building materials that are purchased directly by a consumer from
a retailer, for improving or modifying an existing dwelling, are
consumer products under Magnuson-Moss, but building materials that are
integral component parts of the structure of a dwelling at the time
that the consumer buys the dwelling are not consumer products. 16
C.F.R. 700.1(c)--(f); Federal Trade Commission, Final Action
Concerning Review of Interpretations of Magnuson-Moss Warranty Act, 64
Fed. Reg. 19,700 (April 22, 1999); see also, e.g., *McFadden*, 54
U.C.C. Rep. Serv.2d at 934.

[^11]:消费者直接从零售商处购买的建筑材料，用于改善或改造现有住宅，属于 Magnuson-Moss 下的消费品，但在 消费者购买住宅的时间不属于消费品。16 C.F.R. 700.1©–(f)； 联邦贸易委员会，关于审查 Magnuson-Moss 保证法案解释的最终行动，64 Fed。注册。19,700（1999 年 4 月 22 日）； 另见，例如，McFadden, 54 U.C.C. Rep. Serv.2d 在 934。

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

因此，GPLv3 用户产品定义中心的三句话概括了美国过去三十年建立的关于 Magnuson-Moss 消费产品定义的司法和行政原则。首先，它声明疑似案件的解决有利于定义下的覆盖范围。其次，它表明消费品定义中的“通常使用”一词是指一类产品的典型或普遍使用，而不是特定用户的状态或特定用户的预期或实际使用。第三，它明确指出，产品的大量非消费者使用的存在并不能否定它是消费品的决定，除非这种非消费者使用代表了该产品的唯一重要使用方式。

It should be clear from these added sentences that it is the general
mode of use of a product that determines objectively whether or not it
is a consumer product. One could not escape the effects of the User
Products provisions by labeling what is demonstrably a consumer
product in ways that suggest it is "for professionals", for example.

从这些增加的句子中应该清楚，是产品的一般使用方式客观地决定了它是否是消费品。例如，通过以表明它是“专业人士”的方式标记明显是消费品的东西，无法逃避用户产品条款的影响。

#### Installation Information

#### 安装信息

With the User Products definition complete, the "Installation
Information" definition uses that to define what those receiving
object code inside a User Product must receive.

随着用户产品定义的完成，“安装信息”定义使用它来定义用户产品中那些接收目标代码必须接收的内容。

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

安装信息是“安装和执行涵盖作品的修改版本所需的信息。……来自其修改版本”。CSS，在传达涵盖工作的同一用户产品中。GPLv3 提供了关于必须提供多少信息的指南：它“必须足以确保修改后的目标代码的继续运行在任何情况下都不会仅仅因为进行了修改而受到阻止或干扰。” 例如，如果仅仅因为修改的事实（不管修改的实际性质）使修改后的版本仅以禁用方式运行，那么所提供的信息将是不充分的。信息不需要包含密钥； 安装信息可以是“任何方法、程序、授权密钥或其他信息”。请注意，GPLv3 没有进一步定义“持续运行”。但是，GPLv3 确实提供了一些额外的指导，涉及技术受限用户产品的分销商可以针对下游接收者采取的符合 GPLv3 的行动或不行动的范围，后者将所传送的目标代码替换为修改后的版本。首先，GPLv3 明确了 GPLv3 意味着不为此类作品“继续提供支持服务、保证或更新”的义务。

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

其次，大多数受技术限制的用户产品旨在跨网络通信。对于用户和网络提供商来说，了解拒绝对运行修改版本的设备进行网络访问何时会违反 GPL 非常重要。GPLv3 允许在两种情况下拒绝访问：“当修改本身对网络的运行产生重大不利影响时”，以及当修改本身“违反了网络通信的规则和协议时”。第二种情况是故意用笼统的术语来描述的，它是合理执行政策的基础，这些政策尊重接收者的修改权，同时承认网络提供者的合法利益。


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

请注意，GPLv3 允许以一种实际上不易被任何一方修改的模式传送目标代码，例如在 ROM 中烧录或嵌入硅中的代码。安装信息要求的目标是确保下游被许可人在设备制造商或某些其他方保留修改权时获得真正的修改权。因此，GPLv3 第六款的倒数第二段规定，提供安装信息的要求“不适用，如果您或任何第三方都没有保留在用户产品上安装修改后的目标代码的能力”。

Finally, GPLv3 第六款makes it clear that there is also no requirement to
provide warranty or support for the User Product itself.

请注意，GPLv3 允许以一种实际上不易被任何一方修改的模式传送目标代码，例如在 ROM 中烧录或嵌入硅中的代码。安装信息要求的目标是确保下游被许可人在设备制造商或某些其他方保留修改权时获得真正的修改权。因此，GPLv3 第六款的倒数第二段规定，提供安装信息的要求“不适用，如果您或任何第三方都没有保留在用户产品上安装修改后的目标代码的能力”。

### GPLv3 §7: Additional Permissions

### GPLv3 第7条：附加权限

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

GPL 是一种权限声明，其中一些是有条件的。附加条款——补充 GPL 条款的条款——可能会以某些常见的方式添加到 GPL 代码中，或从中删除。Copyleft 许可理论家通常将这些添加的条款称为“附加许可”，如果他们授予 GPL 条件的例外，如果他们将条件添加到 GPL 的基本许可，则称为“附加要求”。GPLv3 下对额外许可和额外要求的处理必然是不对称的，因为它们不会引发相同的解释问题； 特别是，如果在没有仔细限制的情况下允许附加要求，可能会将 GPL 程序转换为非自由程序。

Due to the latter fear, historically, GPLv2 did not permit any
additional requirements. However, over time, many copyright holders
generally tolerated certain types of benign additional requirements
merely through a "failure to enforce" estoppel-esque scenario.
Therefore, GPLv3 allows for some specific limited requirement
variations that GPLv2 technically prohibits.

由于后一种恐惧，从历史上看，GPLv2 不允许任何额外的要求。然而，随着时间的推移，许多版权持有者通常仅仅通过“未能执行”禁止反言式的场景来容忍某些类型的良性附加要求。因此，GPLv3 允许 GPLv2 在技术上禁止的一些特定的有限要求变化。

With these principles in the background, GPLv3 *§*7 answers the
following questions:

在这些原则的背景下，GPLv3 第7条回答了以下问题：

1.  How does the presence of additional terms on all or part of a GPL'd
     program affect users' rights?

1. GPL 程序的全部或部分附加条款的存在如何影响用户的权利？

2.  When and how may a licensee add terms to code being distributed
     under the GPL?

2. 被许可人何时以及如何向根据 GPL 分发的代码添加条款？

3.  When may a licensee remove additional terms?

3. 被许可人何时可以删除附加条款？

Additional permissions present the easier case. Since the mid-1990s,
permissive exceptions often appeared alongside GPLv2 to allow
combination with certain non-free code. Typically, downstream stream
recipients could remove those exceptions and operate under pure GPLv2.
Similarly, LGPLv2.1 is in essence a permissive variant of GPLv2, and
it permits relicensing under the GPL.

附加权限呈现更简单的情况。自 20 世纪 90 年代中期以来，宽容例外经常与 GPLv2 一起出现，以允许与某些非自由代码结合。通常，下游流接收者可以删除这些例外并在纯 GPLv2 下运行。同样，LGPLv2.1 本质上是 GPLv2 的许可变体，它允许在 GPL 下重新授权。

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

这些做法现在通过 GPLv3 第7条得到推广。被许可人可以从涵盖的作品中删除任何额外的许可，无论它是由原作者还是由上游分发者引入的。被许可人还可以对作品的任何部分添加任何类型的额外许可，而被许可人已对其拥有或可以给予适当的版权许可。例如，如果被许可人编写了该部分，则被许可人是该部分的版权所有者，因此可以授予适用于该部分的额外许可。或者，该部分可能是由其他人编写的，并以附加许可的形式许可给该被许可人。反过来，下游接收者可以删除该部分的任何其他权限。正如 GPLv3 第7条第1款所解释的那样，附加许可的效果取决于该许可是适用于整个作品还是部分作品。

Indeed, LGPLv3 is itself simply a list of additional permissions
supplementing the terms of GPLv3. GPLv3 7 has thus provided the basis
for recasting a formally complex license as an elegant set of added
terms, without changing any of the fundamental features of the
existing LGPL. LGPLv3 is thus a model for developers wishing to
license their works under the GPL with permissive exceptions. The
removability of additional permissions under GPLv3 7 does not alter
any existing behavior of the LGPL since the LGPL has always allowed
relicensing under the ordinary GPL.

事实上，LGPLv3 本身只是一个补充 GPLv3 条款的附加许可列表。因此，GPLv3 第7条为将形式上复杂的许可证重铸为一组优雅的附加条款提供了基础，而无需改变现有 LGPL 的任何基本特征。因此，LGPLv3 是希望根据 GPL 许可其作品的开发人员的模型，但有例外。GPLv3 第7条下附加许可的可移除性不会改变 LGPL 的任何现有行为，因为 LGPL 始终允许在普通 GPL 下重新许可。

## GPLv3 §7: Understanding License Compatibility

## 9.10 GPLv3 第7条：理解许可证兼容性

A challenge that faced the Free Software community heavily through out
the early 2000s was the proliferation of incompatible Free Software
licenses. Of course, the GPL cannot possibly be compatible with all
such licenses. However, GPLv3 contains provisions that are designed to
reduce license incompatibility by making it easier for developers to
combine code carrying non-GPL terms with GPL'd code.

在 2000 年代初期，自由软件社区面临的一个严峻挑战是不兼容的自由软件许可证的激增。当然，GPL 不可能兼容所有这些许可证。但是，GPLv3 包含旨在通过使开发人员更容易将带有非 GPL 条款的代码与 GPL 代码结合起来来减少许可证不兼容性的条款。

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

出现此许可证兼容性问题的原因有以下三个。首先，GPL 是一个强大的 copyleft 许可证，要求在 GPL 下分发修改后的版本。其次，GPL 声明不能对接收者的权利施加进一步的限制。第三，所有其他尊重通用许可证的软件自由都包含某些要求，其中许多不是 GPL 规定的条件。因此，当 GPL 代码与另一个指定其他要求的正式许可证所涵盖的代码相结合进行修改，然后将修改后的代码分发给其他人时，接收者的自由可能会受到违反 GPL 的额外要求的负担。可以看出，其他许可证中的附加权限不会引起任何许可证兼容性问题。


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

GPLv3 采取了一种新方法来解决将 GPL 代码与受其他软件自由许可条款约束的代码相结合的问题。传统的 GPLv2 许可兼容性理论（GPLv2 本身并未明确说明，但被 FSF 视为许可解释事项）认为 GPLv2 仅在非 GPL 许可条款允许在 GPL 下分发并且不对任何限制施加限制的情况下才允许此类组合 GPL 也没有强加的代码。在实践中，FSF 历来为该政策补充了针对某些类型组合的例外结构。


GPLv3 7 implements a more explicit policy on license compatibility. It
formalizes the circumstances under which a licensee may release a
covered work that includes an added part carrying non-GPL terms. GPLv3
7 distinguish between terms that provide additional permissions, and
terms that place additional requirements on the code, relative to the
permissions and requirements established by applying the GPL to the
code.

GPLv3 第7条在许可证兼容性方面实施了更明确的政策。它正式规定了被许可人可以发布包含带有非 GPL 条款的附加部分的涵盖作品的情况。GPLv3 第7条区分提供额外权限的条款和对代码提出额外要求的条款，相对于通过将 GPL 应用于代码而建立的权限和要求。

As discussed in the previous section of this tutorial, GPLv3 7 first
and foremost explicitly allows added parts covered by terms with
additional permissions to be combined with GPL'd code. This codifies
the existing practice of regarding such licensing terms as compatible
with the GPL. A downstream user of a combined GPL'd work who modifies
such an added part may remove the additional permissions, in which
case the broader permissions no longer apply to the modified version,
and only the terms of the GPL apply to it.

正如本教程上一节中所讨论的，GPLv3 第7条首先明确允许将具有附加权限的条款所涵盖的附加部分与 GPL 代码相结合。这规范了将此类许可条款视为与 GPL 兼容的现有做法。修改此类添加部分的组合 GPL 作品的下游用户可以删除额外的权限，在这种情况下，更广泛的权限不再适用于修改后的版本，只有 GPL 的条款适用于它。

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
case ^12^ (#_bookmark129) would a user have the right to do so.

在处理附加要求的条款时，GPLv3 第7条扩展了与 GPL 兼容的许可条款范围。带有附加要求的附加部分可以与 GPL 代码组合，但前提是这些要求属于 GPLv3 第7条中列举的集合。当然，可接受的附加要求是有限制的，这确保增强的许可证兼容性不会击败 GPL 更广泛的软件自由捍卫条款。与授予额外权限的条款不同，施加额外要求的条款不能被组合 GPL 作品的下游用户删除，因为只有在病态情况下 [^12] 用户才有权这样做。

^12^ Theoretically, a user could collect
copyright assignment from all known contributors and then do this, but
this would indeed be the pathological case.
7(e): This provision clarifies that refusal to grant trademark rights
for a GPLv3'd covered work remains compatible with GPLv3. Again, some
non-copyleft permissive licenses include such clauses.


[^12]: 理论上，用户可以从所有已知的贡献者那里收集版权转让，然后这样做，但这确实是病态的情况。7(e)：该条款阐明拒绝授予 GPLv3 涵盖作品的商标权仍然与 GPLv3 兼容。同样，一些非 copyleft 许可包含此类条款。

In general, the types of additional requirements were those terms in
regular use by other non-copyleft Free Software licenses that the FSF
found unobjectionable. The specific details GPLv3's permitted
additional requirements hat GPLv3 are as follows:

一般来说，附加要求的类型是 FSF 认为无异议的其他非 copyleft 自由软件许可证经常使用的条款。GPLv3允许的附加要求 GPLv3的具体细节如下：

7(a): This provision allows alternative "disclaimer of warranty"
forms. Copyright holders can disclaim warranty or limit liability
differently from the terms as provided under GPLv3 15--16. Drafters
included this permission to advance the internationalization goals of
GPLv3; international treaties lack adequate harmonization for laws
regarding warranty and disclaimer.

7(a)：该条款允许使用替代的“保证免责声明”形式。版权所有者可以放弃保证或限制与 GPLv3 第15-16条下提供的条款不同的责任。起草者包括此许可以推进 GPLv3 的国际化目标； 国际条约缺乏关于保证和免责声明的法律的充分协调。

7(b): This provision allows alternative requirements for preservation
of appropriate legal notices. GPLv3 permits additional requirements
regarding preservation of legal notices, including on output from exe-
cution of covered works. Preserved information can include information
about the origins of the code or alterations of the code.

7(b)：本条款允许对适当的法律声明进行保存的替代要求。GPLv3 允许关于保存法律声明的额外要求，包括关于执行涵盖作品的输出。保留的信息可以包括有关代码来源或代码更改的信息。

7(c): This provision allows prohibition of misrepresentation of
original material. The provision yields com- patibility with
non-copyleft Free Software licenses that require marking of modified
versions in "rea- sonable"ways which differ from GPL's own precise
marking requirements.

7(c)：该条款允许禁止对原始材料进行虚假陈述。该条款与非 copyleft 自由软件许可证兼容，这些许可证要求以“合理”的方式标记修改版本，这与 GPL 自己的精确标记要求不同。

7(d): This provision allows limitations on the use of names of
licensor for publicity purposes. This provision also yields additional
compatibility with non-copyleft Free Software licenses that prohibit
the use of the licensor's name on unmodified versions (or other prohibitions on
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

7(d)：该条款允许限制出于宣传目的使用许可方名称。该规定还与非 copyleft 自由软件许可证产生了额外的兼容性，这些许可证禁止在未修改的版本上使用许可方的名称（或其他广告权禁令）。例如，3 条款 BSD 许可证的第3条，长期以来一直被认为事实上与 GPLv2 兼容，通过该条款明确兼容 GPLv3。然而，该条款并没有使 GPL 与 FSF 很久以前认为有问题的旧 BSD 广告条款兼容。

7(f): This provision allows indemnification requirements of authors
and licensors. The FSF specifically designed this clause to achieve
GPLv3 compatibility for the [Apache Software License, Version
2.0.](http://www.apache.org/licenses/LICENSE-2.0.html)

7(f)：该条款允许作者和许可人提出赔偿要求。FSF 专门设计了此条款以实现 Apache 软件许可证版本 2.0 的 GPLv3 兼容性。

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

在 GPLv3 起草过程中，有人质疑 GPLv3 第7条的必要性； 这些批评者认为，它造成了以前不存在的复杂性。然而，在 GPLv3 起草之时，许多现有的 GPLv2 软件包已经与各种非 copyleft 自由软件许可代码相结合，这些代码带有此类附加条款。因此，GPLv3 第7条合理化了这些软件包作者和修改者的现有做法，因为它为删除和添加这些附加条款设定了明确的指导方针。GPLv3 第7条仔细限制了允许的附加要求列表，还实现了其他目标，因为它允许扩展 GPL 开发人员可用的代码基础，同时还鼓励对 GPLv3 默认不包含的要求进行有用的实验。

However, any other non-permissive additional terms apart from those
stated above are considered "fur- ther" restrictions which [GPLv3
10](#gplv3-10-explicit-downstream-license) prohibits. Furthermore, as
a compliance matter, if you add additional terms in accordance with
GPLv3 7, you must ensure that the terms are placed in the relevant
source files or provide a conspicuous notice about where to find the
additional terms.

但是，除上述条款之外的任何其他非许可附加条款均被视为 GPLv3 第10条禁止的“进一步”限制。此外，作为合规性事项，如果您根据 GPLv3 第7条添加附加条款，您必须确保将这些条款放在相关源文件中或提供关于在哪里可以找到附加条款的显着通知。

## GPLv3 §8: A Lighter Termination

## 9.11 GPLv3 第8条：更轻松的终止


GPLv2 provided for automatic termination of the rights of a person who
copied, modified, sublicensed, or distributed a work in violation of
the license. Automatic termination can be too harsh for those who have
committed an inadvertent violation, particularly in cases involving
distribution of large collections of software having numerous
copyright holders. A violator who resumes compliance with GPLv2
technically needs to obtain forgiveness from all copyright holders,
and even contacting them all might be impossible.

GPLv2 规定自动终止违反许可证复制、修改、再许可或分发作品的人的权利。自动终止对于那些无意中违规的人来说可能过于严厉，尤其是在涉及分发拥有众多版权所有者的大量软件的情况下。恢复遵守 GPLv2 的违规者在技术上需要获得所有版权所有者的原谅，甚至连联系他们都可能是不可能的。

GPLv3 8 now grants opportunities for provisional and permanent
reinstatement of rights. The termi- nation procedure provides a
limited opportunity to cure license violations. If a licensee has
committed a first-time violation of the GPL with respect to a given
copyright holder, but the licensee cures the violation within 30 days
following receipt of notice of the violation, then any of the
licensee's GPL rights that have been terminated by the copyright
holder are "automatically reinstated".

GPLv3 第8条现在授予临时和永久恢复权利的机会。终止程序提供了有限的机会来解决许可证违规问题。如果被许可人首次违反与给定版权所有者有关的 GPL，但被许可人在收到违规通知后 30 天内纠正了违规行为，则被许可人的任何已被终止的 GPL 权利 版权所有者“自动恢复原状”。

Finally, if a licensee violates the GPL, a contributor may terminate
any patent licenses that it granted under GPLv3 *§*11, in addition to
any copyright permissions the contributor granted to the licensee.

最后，如果被许可人违反 GPL，贡献者可以终止其根据 GPLv3 第11条授予的任何专利许可，以及贡献者授予被许可人的任何版权许可。

## GPLv3 §9: Acceptance

## 9.12 GPLv3 第9条：接受

GPLv3 9 means what it says: mere receipt or execution of code neither
requires nor signifies contractual acceptance under the GPL. Speaking
more broadly, GPLv3 is intentionally structured as a unilateral grant
of copyright permissions, the basic operation of which exists outside
of any law of contract. Whether and when a contractual relationship is
formed between licensor and licensee under local law do not
necessarily matter to the working of the license.

代码既不需要也不表示 GPL 下的合同接受。更广泛地说，GPLv3 被有意构建为单方面授予版权许可，其基本操作存在于任何合同法之外。根据当地法律，许可人和被许可人之间是否以及何时形成合同关系不一定对许可的运作有影响。

## GPLv3 §10: Explicit Downstream License

## 9.13 GPLv3 第10条：显式下游许可

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

GPLv3 第10条通常是一个简单明了的部分，可确保下游的每个人都从所有版权所有者那里获得许可。每次您重新分发 GPL 程序时，接收者都会根据 GPL 的条款自动从每个上游许可人那里收到一份许可，其受版权保护的材料出现在您重新分配的工作。您可以将其视为创建三维而非线性的许可权流。作品的每个接收者都是“私密的”，或者直接从每个许可人那里获得许可。这种自动下游许可机制是 Copyleft 功能的核心。每个许可人独立地授予许可，并且每个许可人在违反时独立地终止许可。侵权方下游的各方仍然获得许可，只要他们自己不实施侵权行为。他们的许可直接来自所有上游版权所有者，不依赖于向他们分发的违约方的许可。出于同样的原因，获得该程序的另一个副本的侵权者并没有因此获得任何新的许可权：一旦该程序的任何上游许可人因违反其条款而终止许可，则不会有新的自动许可只需获取另一份副本即可发送给收件人[^13]。

[^13]: 脚注 3 也适用于 GPLv3 的讨论，就像它在 GPLv2 的讨论中一样。

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

同时，GPLv3 第10条中 GPLv3 中的一个特定添加值得特别提及。具体来说，GPLv3 从 GPLv2 2(b)（顺便说一句，后来变成了 GPLv3 5(b)）中删除了“免费”一词，因为它造成了一种误解，即 GPL 不允许对副本的分发收费。“不收费”措辞的目的是防止试图从第三方收取版税。删除这些词会产生危险，即征收许可费将不再被视为违反许可。因此，GPLv3 第10条新增了一项明确禁止征收许可费或版税的规定。本节是此类条款的适当位置，因为它是一般要求的特定结果，即不对 GPL 代码的下游接收者施加进一步的限制。

## GPLv3 §11: Explicit Patent Licensing

## 9.14 GPLv3 第11条：显式专利许可

Software patenting is a harmful and unjust policy, and should be
abolished; recent experience makes this all the more evident. Since
many countries grant patents that can apply to and prohibit software
packages, in various guises and to varying degrees, GPLv3 seeks to
protect the users of GPL-covered programs from those patents, while at
the same time making it feasible for patent holders to contribute to
and distribute GPL-covered programs as long as they do not attack the
users of those programs.

软件专利是一种有害和不公正的政策，应该废除；最近的经验使这一点更加明显。由于许多国家/地区以各种形式和不同程度授予可以应用于和禁止软件包的专利，因此 GPLv3 旨在保护受 GPL 保护的程序的用户免受这些专利的影响，同时使专利持有人能够贡献自己的力量 分发 GPL 程序，只要它们不攻击这些程序的用户。

It is generally understood that GPLv2 implies some limits on a
licensee's power to assert patent claims against the use of
GPL-covered works. However, the patent licensing practice that GPLv2 7
(corresponding to GPLv3 12) is designed to prevent is only one of
several ways in which software patents threaten to make free programs
non-free and to prevent users from exercising their rights under the
GPL. GPLv3 takes a more comprehensive approach to combating the danger
of patents.

人们普遍认为，GPLv2 意味着对被许可人针对 GPL 保护作品的使用提出专利索赔的权力的一些限制。然而，GPLv2 第7条（对应于 GPLv3 第12条）旨在防止的专利许可实践只是软件专利威胁使免费程序成为非自由软件并阻止用户行使 GPL 下的权利的几种方式之一。GPLv3 采用更全面的方法来对抗专利的危险。

GPLv2 7 has seen some success in deterring conduct that would
otherwise result in denial of full downstream enjoyment of GPL rights,
and thus it is preserved in GPLv3 12. Experience has shown that more
is necessary, however, to ensure adequate community safety where
companies act in concert to heighten the anticompetitive use of
patents that they hold or license.

GPLv2 第7条在阻止可能导致下游无法完全享受 GPL 权利的行为方面取得了一些成功，因此它在 GPLv3 第12条中得到了保留。然而，经验表明，在公司采取行动的地方，还需要做更多的工作来确保充分的社区安全 共同加强对他们持有或许可的专利的反竞争使用。

Therefore, GPLv3 is designed to reduce the patent risks that distort
and threaten the activities of users who make, run, modify and share
Free Software. At the same time, GPLv3 gives favorable consideration
to practical goals such as certainty and administrability for patent
holders that participate in distribution and development of
GPL-covered software. GPLv3's policy requires each such patent holder
to provide appropriate levels of patent assurance to users, according
to the nature of the patent holder's relationship to the program.

因此，GPLv3 旨在降低扭曲和威胁制作、运行、修改和共享自由软件的用户的活动的专利风险。同时，GPLv3 对参与 GPL 软件分发和开发的专利持有人的确定性和可管理性等实际目标给予了有利的考虑。GPLv3 的政策要求每个此类专利持有人根据专利持有人与程序的关系性质，向用户提供适当级别的专利保证。

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

一般来说，GPLv3 提供两类专利承诺：

授予贡献者版本中声明的许可：GPLv3 第11条引入了对那些为 GPL 程序贡献代码的人的专利声明的肯定性授予权利。这样做的目的是防止各方针对他们自己修改的代码的用户积极主张专利——理论上防止 copyleft 社区的“内部人士”背叛。贡献者的专利声明必然会受到其修改的合并所创建的程序版本的侵犯，该版本将许可给该程序或基于该程序的程序的所有后续用户和修改者。仅因其他方的后续修改而侵犯的专利权利要求不会因此获得许可。在制作“贡献者版本”后获得的专利权利要求必然受到该版本的侵犯，在其获得或完善时也根据本条款获得许可。

^13^{#_bookmark134 .anchor}Footnote [3](#_bookmark77) also applies
here in discussion of GPLv3 just as it did in discussion of GPLv2.

Prohibition of enforcement of patent claims against those to whom you
distribute: GPLv3 10 makes explicit that licensees who directly
distribute may not make demands for acceptance of patent licenses or
payment of patent royalties from distribution recipients. This
provision establishes a uniform rule of patent exhaustion with respect
to GPL'd programs regardless of the domestic patent law in any
particular system or locale.

禁止对您分发的人执行专利索赔：GPLv3 第10条明确规定直接分发的被许可人不得要求接受专利许可或支付分发接收者的专利使用费。无论任何特定系统或地区的国内专利法如何，该条款都针对 GPL 程序建立了统一的专利用尽规则。

The following two subsections discuss in order each of the above
mentioned classes of patent commitments.

以下两小节按顺序讨论上述每一类专利承诺。

### The Contributor's Explicit Patent License

### 贡献者的显示专利许可

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

具体来说，理想的情况可能是 GPLv3 具有由 GPLv3 涵盖作品的所有分发行为触发的专利许可授予。FSF 在 GPLv3 起草过程中考虑过这一点，但许多专利持有公司反对这一政策。他们提出了两个反对意见：（1）授予专利许可对专利持有人的深远影响与仅分发代码而不进行修改或改造的行为不相称，（2）期望拥有大量专利的所有者是不合理的专利资产，以尽必要的努力审查其提供给他人的所有 GPL 软件。一些人对“无意”分发的后果表示特别关注。

The argument that the impact of the patent license grant would be
"disproportionate", that is to say unfair, is not valid. Since
software patents are weapons that no one should have, and using them
for aggression against free software developers is an egregious act
(thus preventing that act cannot be unfair).

专利许可授予的影响将“不成比例”，即不公平的论点是无效的。由于软件专利是任何人都不应该拥有的武器，使用它们来攻击自由软件开发者是一种恶劣的行为（因此阻止这种行为是不公平的）。

However, the second argument seems valid in a practical sense. A
typical GNU/Linux distribution includes thousands of programs. It
would be quite difficult for a re-distributor with a large patent
portfolio to review all those programs against that portfolio every
time it receives and passes on a new version of the distribution.
Moreover, this question raises a strategic issue. If the GPLv3 patent
license requirements convince patent-holding companies to remain
outside the distribution path of all GPL-covered software, then these
requirements, no matter how strong, will cover few patents.

然而，第二个论点在实际意义上似乎是有效的。典型的 GNU/Linux 发行版包括数千个程序。对于拥有大量专利组合的再分发者来说，每次收到并传递新版本的分发时，都很难根据该组合审查所有这些程序。此外，这个问题提出了一个战略问题。如果 GPLv3 专利许可要求说服专利持有公司置身于所有受 GPL 保护的软件的分发路径之外，那么这些要求，无论多么强烈，都将覆盖很少的专利。

GPLv3 therefore makes a partial concession which would lead these
companies to feel secure in doing the distribution themselves. GPLv3
11 applies only to those distributors that have modified the program.
The other changes we have made in sections 10 and 11 provide
strengthened defenses against patent assertion and compensate partly
for this concession.

因此，GPLv3 做出了部分让步，这将使这些公司在自己进行分发时感到安全。GPLv3 第11条仅适用于修改了程序的发行商。我们在第10条和第11条中所做的其他更改提供了针对专利主张的强化抗辩，并部分补偿了这种让步。

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

因此，GPLv3 第11条第3款引入了 GPLv3 第11条中使用的术语“贡献者”、“贡献者版本”和“必要的专利权利要求”。从程序接收者的角度来看，贡献者包括程序所有版权持有者，最初根据非 GPL 条款许可并后来合并到 GPL 作品中的材料的版权所有者除外。因此，贡献者是本程序的初始 GPLv3 许可人，以及根据 GPLv3 第5条传送修改后的涵盖作品的所有后续上游许可人。因此，“贡献者版本”包括贡献者从贡献者已修改的上游版本复制的材料。GPLv3 第11条第3款不适用于那些不加改动地重新发布程序的人[^14]。换句话说，“贡献者版本”不仅包括贡献者添加或更改的材料，还包括贡献者从中复制的现有材料上游版本并保留在修改版本中。（GPLv3 对“贡献者”和“贡献”的使用不应与这些术语在某些其他自由软件许可中的各种其他使用方式相混淆[^15]。）

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
however, a conveying party can freely grant patent sublicenses to
downstream recipients without violating the GPL.

“必要专利权利要求”定义的一些细节值得特别提及。对于给定的一方，“必要专利权利要求”是该方“拥有或控制”的权利要求的子集。它们确实包括已由第三方许可给贡献者的可再许可声明。^16^ 大多数允许再许可的商业专利许可协议都是在与 GPL 要求不一致的限制性条款下进行的。例如，一些专利许可允许专利被许可人进行再许可，但要求从任何被再许可人处收取使用费。专利被许可人不能在不违反 GPLv3 第12条的情况下分发受 GPL 保护的程序并向接收者授予该程序的专利从属许可^17^ 然而，在极少数情况下，传送方可以在不违反 GPLv3 的情况下自由向下游接收者授予专利从属许可 GPL。

^14^An implied patent license from the distributor, however, often arises. See
[6]in this tutorial

^15^Cf., e.g., Apache License, version 2.0, section 1; Eclipse Public
License, version 1.0, section 1; Mozilla Public License,
v[]{#_bookmark138 .anchor}ersion 1.1, section 1.1.

^16^This issue is typically handled in other software freedom licenses
having patent licensing provisions by use of the unhelpful
[]{#_bookmark139 .anchor}term "licensable," which is either left
undefined or is given an ambiguous definition.

^17^GPLv3 also provides an example in section 12 that makes this point
clear.


[^14]:但是，经常会出现来自分销商的默示专利许可。参见本教程中的 6

[^15]: Cf.，例如，Apache 许可证，版本 2.0，第 1 节； Eclipse 公共许可证，版本 1.0，第 1 节； Mozilla 公共许可证，v[]{#_bookmark138 .anchor}版本 1.1，第 1.1 节。

[^16]: 此问题通常在具有专利许可条款的其他软件自由许可中通过使用无用的 []{#_bookmark139 .anchor} 术语“可许可”来处理，该术语要么未定义，要么给出了模棱两可的定义。

[^17]: GPLv3 还在第 12 节中提供了一个示例，清楚地说明了这一点。

Additionally, "essential patent claims" are those patents "that would
be infringed by some manner, permitted by this License, of making,
using, or selling the work". This intends to make clear that a patent
claim is "essential" if some mode of usage would infringe that claim,
even if there are other modes of usage that would not infringe.

此外，“基本专利权利要求”是那些“在本许可证允许的情况下，以某种方式侵犯制作、使用或销售作品的专利”。这旨在表明，如果某种使用方式会侵犯专利权利要求，则该专利权利要求是“必要的”，即使存在其他不会侵权的使用方式也是如此。

Finally, "essential patent claims . . . do not include claims that
would be infringed only as a consequence of further modification of
the work." The set of essential patent claims licensed is fixed by the
particular version of the work that was contributed. The claim set
cannot expand as a work is further modified downstream. (If it could,
then any software patent claim would be included, since any software
patent claim can be infringed by some further modification of the
work.)[^18^](#_bookmark141)

最后，“必要的专利声明……不包括仅因进一步修改作品而被侵权的索赔。” 许可的基本专利权利要求集由所贡献作品的特定版本确定。随着作品在下游进一步修改，声明集无法扩展。（如果可以，那么将包括任何软件专利声明，因为任何软件专利声明都可能因对作品的进一步修改而受到侵犯。）^18^

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

理想情况下，这种贡献者专利政策将导致贡献者相当频繁地许可专利权利要求。贡献者有责任意识到自己修改了作品并将其提供给他人；任何捐助行为都不应被视为无意。对于贡献者来说，GPLv3 的规则也不需要比专利持有人提出的较弱的规则更多的工作。根据他们的规定，贡献者必须始终将整个作品与其专利组合进行比较，以确定修改与作品其余部分的组合是否会导致其阅读贡献者的任何专利声明。

Finally, GPLv3's explicit patent license for contributors has an
interesting and useful side effect. When a company with a large number
of such claims acquires the program's modifier, all claims held or
thereafter acquired by the purchaser are automatically licensed under
this provision. For example, Microsoft's acqui- sition of Nokia
resulted in the automatic licensing of all Microsoft patent claims now
or hereafter acquired which read on any contributor version of any
GPLv3 program ever modified by Nokia.

最后，GPLv3 对贡献者的明确专利许可有一个有趣且有用的副作用。当拥有大量此类权利要求的公司获得该程序的修改器时，购买者持有或之后获得的所有权利要求将根据本条款自动获得许可。例如，微软对诺基亚的收购导致微软现在或以后获得的所有专利权利要求的自动许可，这些权利要求阅读诺基亚曾经修改过的任何 GPLv3 程序的任何贡献者版本。

### Conveyors' Patent Licensing

### 专利许可的传递

The remaining patent licensing in GPLv3 deals with patent licenses
that are granted by conveyance. The licensing is not as complete or
far reaching as the contributor patent licenses discussed in the
preceding section.

GPLv3 中剩余的专利许可涉及通过转让授予的专利许可。许可不像上一节中讨论的贡献者专利许可那样完整或广泛。

The term "patent license," as used in GPLv3 11 4--6, is not meant to
be confined to agreements formally identified or classified as patent
licenses. GPLv3 11 3 makes this clear by defining "patent license,"
for purposes of the subsequent three paragraphs, as "any express
agreement or commitment, however denomi- nated, not to enforce a
patent (such as an express permission to practice a patent or covenant
not to sue for patent infringement)"

GPLv3 第11条第4-6款中使用的术语“专利许可”并不意味着仅限于正式确定或归类为专利许可的协议。GPLv3 第11条第3款通过为后续三段的目的将“专利许可”定义为“任何明确的协议或承诺，无论名称如何，不强制执行专利（例如明确许可实施专利或 承诺不起诉专利侵权）”

GPLv3 11 5 is commonly called GPLv3's downstream shielding provision.
It responds particularly to the problem of exclusive deals between
patent holders and distributors, which threaten to distort the free
software distribution system in a manner adverse to developers and
users. The fundamental idea is to make a trade-off between assuring a
patent license for downstream and making (possibly patent-encumbered)
CCS publicly available.

GPLv3 第11条第5款通常称为 GPLv3 的下游屏蔽条款。它特别针对专利持有人和分销商之间的排他性交易问题作出回应，这些交易有可能以对开发者和用户不利的方式扭曲自由软件分发系统。基本思想是在确保下游专利许可和公开提供（可能受专利保护的）CCS 之间做出权衡。

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

简而言之，在几乎所有满足“故意依赖”测试的情况下，专利许可确实不可再许可或普遍免费提供给所有人。另一方面，如果专利许可在符合 GPL 要求的条款下普遍可用，则分销商自动遵守，因为专利许可已经扩展到所有下游接收者。最后，如果专利许可可以按照与 GPL 一致的条款进行再许可，则分发者可以选择向下游接收者授予再许可，而不是让 CCS 公开可用。（在这种情况下，如果分销商也是贡献者，那么无论如何它已经授予了专利从属许可，因此它不需要做任何进一步的事情来遵守第三段。）

Admittedly, public disclosure of CCS is not necessarily required by
other sections of the GPL, and the FSF in drafting GPLv3 did not
necessarily wish to impose a general requirement to make source code
available to all, which has never been a GPL condition. However, many
vendors who produce products that include copylefted software, and who
are most likely to be affected by the downstream shielding provision,
lobbied for the addition of the source code availability option, so it
remains.

诚然，CCS 的公开披露不一定是 GPL 的其他部分所要求的，并且 FSF 在起草 GPLv3 时并不一定希望强加一个通用的要求，即向所有人提供源代码，这从来都不是 GPL 的条件。然而，许多生产包含 copylefted 软件的产品的供应商，以及最有可能受到下游屏蔽条款影响的供应商，游说添加源代码可用性选项，因此它仍然存在。

^18^[]{#_bookmark141 .anchor}However, "the work" should not be
understood to be restricted to a particular mechanical affixation of,
or medium for distributing, a program, where the same program might be
provided in other forms or in other ways that may be captured by other
patent claims held by the contributor.

[^18]: 但是，“作品”不应被理解为仅限于程序的特定机械附加或分发媒介，其中相同的程序可能以其他形式提供或 以其他方式可能被贡献者持有的其他专利权利要求所捕获。

Meanwhile, two specific alternatives to the source code availability
option are also available. The dis- tributor may comply by disclaiming
the patent license it has been granted for the conveyed work, or by
arranging to extend the patent license to downstream
recipients.[^19^](#_bookmark143) The GPL is intended to permit private
distribution as well as public distribution, and the addition of these
options ensures that this remains the case, even though it remains
likely that distributors in this situation will usually choose the
source code availability option.

同时，还提供了源代码可用性选项的两个特定替代方案。发行商可以通过放弃已授予其所传送作品的专利许可，或通过安排将专利许可扩展到下游接收者来遵守。^19^ GPL 旨在允许私人发行和公共发行，并且这些选项的添加确保了这种情况仍然存在，即使在这种情况下分销商仍然可能通常会选择源代码可用性选项。

Note that GPLv3 11 5 is activated only if the CCS is not already
otherwise publicly available. (Most often it will, in fact, already be
available on some network server operated by a third party.) Even if
it is not already available, the option to "cause the Corresponding
Source to be so available" can then be satisfied by verifying that a
third party has acted to make it available. That is to say, the
affected distributor need not itself host the CCS to take advantage of
the source code availability option. This subtlety may help the
distributor avoid certain peculiar assumptions of liability.

请注意，仅当 CCS 尚未以其他方式公开可用时，GPLv3 第11条第5款才会被激活。（事实上，大多数情况下，它已经在第三方运营的某些网络服务器上可用。）即使它还不可用，“使相应的源如此可用”的选项也可以通过验证来满足第三方已采取行动使其可用。也就是说，受影响的分销商不需要自己托管 CCS 来利用源代码可用性选项。这种微妙之处可能有助于分销商避免某些特殊的责任假设。

Note that GPLv3 11 6--7 are designed to stop distributors from
colluding with third parties to offer selective patent protection.
GPLv3 is designed to ensure that all users receive the same rights;
arrangements that circumvent this make a mockery of free software, and
we must do everything in our power to stop them. First, GPLv3 11 6
states that any license that protects some recipients of GPL'd
software must be extended to all recipients of the software. If
conveyors arrange to provide patent protection to some of the people
who get the software from you, that protection is automatically
extended to everyone who receives the software, no matter how they get it.

请注意，GPLv3 第11条第6–7款旨在阻止分销商与第三方串通以提供选择性专利保护。GPLv3 旨在确保所有用户获得相同的权利； 规避这一点的安排是对自由软件的嘲弄，我们必须竭尽全力阻止它们。首先，GPLv3 第11条第6款声明任何保护 GPL 软件的某些接收者的许可证必须扩展到该软件的所有接收者。如果传送者安排向从您那里获得软件的某些人提供专利保护，则该保护会自动扩展到接收到软件的每个人，无论他们如何获得它。

Second, GPLv3 11 7 prohibits anyone who made such an agreement from
distributing software released under GPLv3. Conveyors are prohibited
from distributing software under GPLv3 if the conveyor makes an
agreement of that nature in the future.

其次，GPLv3 第11条第7款禁止任何签订此类协议的人分发根据 GPLv3 发布的软件。如果传送者将来达成此类性质的协议，则禁止传送者分发 GPLv3 下的软件。


The date in GPLv3 11 7 likely seems arbitrary to those who did not
follow the GPLv3 drafting process. This issue was hotly debated during
the drafting of GPLv3, but ultimately one specific deal of this type
--- a deal between Microsoft and Novell for Microsoft to provide
so-called "coupons" to Microsoft customers to redeem for copies of
Novell's GNU/Linux distribution with a Microsoft patent license -- was
designed to be excluded.

对于那些不遵循 GPLv3 起草过程的人来说，GPLv3 第11条第7款中的日期可能看起来很武断。这个问题在 GPLv3 的起草过程中引起了激烈的争论，但最终达成了一项此类具体交易——微软和 Novell 之间的一项交易，微软向微软客户提供所谓的“优惠券”，以兑换 Novell 的 GNU/Linux 发行版副本 微软专利许可——被设计为被排除在外。

The main reason for this was a tactical decision by the FSF. FSF
believed they can do more to protect the community by allowing Novell
to use software under GPLv3 than by forbidding it to do so. This is
because of paragraph 6 of section 11 (corresponding to paragraph 4 in
Draft 3). It will apply, under the Microsoft/Novell deal, because of
the coupons that Microsoft has acquired that essentially commit it to
participate in the distribution of the Novell SLES GNU/Linux system.

主要原因是 FSF 的战术决定。FSF 认为，与禁止 Novell 使用 GPLv3 软件相比，他们可以通过允许 Novell 使用 GPLv3 软件来保护社区。这是因为第11条第6款（对应草案3中的第4款）。根据 Microsoft/Novell 协议，它将适用，因为 Microsoft 获得的优惠券实质上承诺参与 Novell SLES GNU/Linux 系统的分发。


The FSF also gave a secondary reason: to avoid affecting other kinds
of agreements for other kinds of activities. While GPLv3 sought to
distinguish pernicious deals of the Microsoft/Novell type from
business conduct that is not particularly harmful, the FSF also did
not assume success in that drafting, and thus there remained some risk
that other unchangeable past agreements could fall within the scope of
GPLv3 11 7. In future deals, distributors engaging in ordinary
business practices can structure the agreements so that they do not
fall under GPLv3 *§*11*¶*7.

FSF 还给出了一个次要原因：避免影响其他类型活动的其他类型协议。虽然 GPLv3 试图将 Microsoft/Novell 类型的有害交易与不是特别有害的商业行为区分开来，但 FSF 也没有假设在该起草中取得成功，因此仍然存在一些风险，即其他不可更改的过去协议可能属于 GPLv3 的范围 GPLv3 第11条第7款。在未来的交易中，从事普通商业行为的分销商可以构建协议，使其不属于 GPLv3 第11条第7款。

## GPLv3 §12: Familiar as GPLv2 §7

## 9.15 GPLv3 第12条：与GPLv2 第7条相似

GPLv2 12 remains almost completely unchanged from the text that
appears in GPLv2 7. This is an important provision that ensures a
catch-all to ensure that nothing "surprising" interferes with the
continued conveyance safely under copyleft.

GPLv3 第12条 与 GPLv2 第7条中出现的文本几乎完全保持不变。这是一项重要的规定，确保包罗万象，确保没有任何“意外”干扰 copyleft 下的安全继续传输。

The wording in the first sentence of GPLv3 12 has been revised
slightly to clarify that an agreement -- such as a litigation
settlement agreement or a patent license agreement -- is one of the
ways in which conditions may be "imposed" on a GPL licensee that may
contradict the conditions of the GPL, but which do not excuse the
licensee from compliance with those conditions. This change codifies
the historical interpretation of GPLv2.

GPLv3 第12条第一句的措辞略有修改，以阐明协议（例如诉讼和解协议或专利许可协议）是可以对 GPL 被许可人“施加”条件的方式之一 与 GPL 的条件相矛盾，但不能成为被许可人不遵守这些条件的借口。此更改整理了 GPLv2 的历史解释。

GPLv3 removed the limited severability clause of GPLv2 7 as a matter
of tactical judgment, believing that this is the best way to ensure
that all provisions of the GPL will be upheld in court. GPLv3 also
removed the final sentence of GPLv2 section 7, which the FSF consider
to be unnecessary.

^19^[]{#_bookmark143 .anchor}The latter option, if chosen, must be
done "in a manner consistent with the requirements of this License";
for example, it is unavailable if extension of the patent license
would result in a violation of GPLv3 *§*12.

[^19]: 如果选择后一个选项，则必须“以符合本许可证要求的方式”进行； 例如，如果延长专利许可会导致违反 GPLv3 第12条，则不可用。


GPLv3 作为战术判断删除了 GPLv2 第7条的有限可分割性条款，认为这是确保 GPL 所有条款在法庭上得到维护的最佳方式。GPLv3 还删除了 GPLv2 第 7 条的最后一句，FSF 认为这是不必要的。


## GPLv3 §13: The Great Affero Compromise

## 9.16 GPLv3 第13条：伟大的Affero妥协

The Affero GPL was written with the expectation that its additional
requirement would be incorporated into the terms of GPLv3 itself. Many
software freedom advocates, including some authors of this tutorial,
advocated heavily for that, and fully expected it to happen.

Affero GPL 的编写期望将其附加要求纳入 GPLv3 本身的条款中。许多软件自由倡导者，包括本教程的一些作者，大力倡导这一点，并完全期待它的发生。

The FSF, however, chose not to include the Affero clause in GPLv3, due
to what it called "irreconcilable views from different parts of the
community". Many commercial users of Free Software were opposed to the
inclusion of a mandatory Affero-like requirement in the body of GPLv3
itself. In fact, some wealthier companies even threatened to
permanently fund forks of many FSF copyrighted-programs under GPLv2 if
the Affero clause appeared in GPLv3.

然而，由于所谓的“来自社区不同部分的不可调和的观点”，FSF 选择不将 Affero 条款包含在 GPLv3 中。许多自由软件的商业用户反对在 GPLv3 本身的主体中包含强制性的类似 Affero 的要求。事实上，如果 Affero 条款出现在 GPLv3 中，一些更富有的公司甚至威胁要永久资助许多 GPLv2 下的 FSF 版权程序的分支。

Meanwhile, there was disagreement even among copyleft enthusiasts
about the importance of the pro- vision. A coalition never formed, and
ultimately the more powerful interests implicitly allied with the
companies who deeply opposed the Affero clause such that the FSF felt
the Affero clause would need its own license, but one compatible with
GPLv3.

与此同时，甚至在 copyleft 爱好者中也对该条款的重要性存在分歧。一个联盟从未形成，最终更强大的利益集团与那些强烈反对 Affero 条款的公司暗中结盟，以至于 FSF 认为 Affero 条款需要自己的许可，但要与 GPLv3 兼容。

GPLv3 13 makes GPLv3 compatible with the AGPLv3, so that at least code
can be shared between AGPLv3'd and GPLv3'd projects, even if the
Affero clause does not automatically apply to all GPLv3'd works.

GPLv3 第13条使 GPLv3 与 AGPLv3 兼容，因此至少可以在 AGPLv3 和 GPLv3 项目之间共享代码，即使 Affero 条款不会自动适用于所有 GPLv3 作品。

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

人应该认识到，大多数其他自由软件许可证也允许此类链接。特别是，当通过将 GPLv3 覆盖的代码与 AGPLv3 覆盖的代码链接起来制作组合作品时，一部分的 copyleft 不会扩展到另一部分。在此类组合中，Affero 要求将仅适用于最初根据 Affero 许可引入组合的部分。理论上，那些收到此类组合并且不想根据 Affero 要求使用代码的人可以删除组合中 Affero 覆盖的部分。（诚然，在实践中，组合代码的去混合在技术上可能很困难。）

## GPLv3 §14: So, When's GPLv4?

## 9.17 GPLv3 第14条：那么GPLv4什么时候会出？

No substantive change has been made in section 14. The wording of the
section has been revised slightly to make it clearer.

第 14 条未作实质性更改。该节的措辞已略作修改，以使其更加清晰。

It's unclear when the FSF might consider publishing GPLv4. However,
this section makes it clear that the FSF is the sole authority who can
decide such.

目前尚不清楚 FSF 何时会考虑发布 GPLv4。但是，本节明确表示 FSF 是唯一可以做出此类决定的机构。


The main addition to this section allows a third-party proxy to be
appointed by contributors who wish someone else to make relicensing to
new versions of GPL when they are released. This is a "halfway" point
between using "-only" or "-or-later" by consolidating the
decision-making on that issue to a single authority.

本节的主要新增内容允许贡献者指定第三方代理，这些贡献者希望其他人在发布新版本的 GPL 时重新授权。通过将该问题的决策整合到一个单一的权威机构，这是使用“仅”或“及后续”之间的“中间”点。

## GPLv3 §15--17: Warranty Disclaimers and Liability Limita- tion

## 9.18 GPLv3 第15——17条：免责声明与有限责任

No substantive changes have been made in sections 15 and 16.

第 15 和 16 条未作实质性修改。

Finally, the FSF shortened the section on "How to Apply These Terms to
Your New Programs" to just the bare essentials.

最后，FSF 将“如何将这些条款应用于您的新程序”部分缩短为仅保留基本要素。
