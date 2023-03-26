
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
