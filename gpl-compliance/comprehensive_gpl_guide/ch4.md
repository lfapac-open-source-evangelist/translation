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
