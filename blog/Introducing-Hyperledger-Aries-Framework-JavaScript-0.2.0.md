# Introducing Hyperledger Aries Framework JavaScript 0.2.0
# 介绍 Hyperledger Aries 框架 JavaScript 0.2.0
By Karim Stekelenburg, Hyperledger Aries Framework JavaScript Maintainer and Animo Solutions Co-founder July 6, 2022 Blog, Hyperledger Aries, Identity
作者：Karim Stekelenburg，Hyperledger Aries 框架JavaScript 维护者、Animo Solutions 联合创始人 | 2022年7月6日 | 博客，Hyperledger Aries，身份

About half a year before we started Animo Solutions, my co-founders and I discovered Hyperledger Aries Framework JavaScript, an open source JavaScript/TypeScript framework designed to create interoperable self-sovereign identity solutions. At the time we were just getting acquainted with the concept of SSI. Just the idea that we could use TypeScript to build made our lives so much easier and the tech so much less daunting. It turned into one of the building blocks of our company, and I would end up becoming a maintainer and strong advocate of Hyperledger Aries Framework JavaScript. Now, after two years of hard work by the community, we’re excited to announce the 0.2.0 release of the framework. In this article, I’ll take you through what this newest release entails and why it will change the way self-sovereign solutions are built.
在我们开始 Animo Solutions 前大约半年，我和我的联合创始人发现了 Hyperledger Aries Framework JavaScript，这是一个开源 JavaScript/TypeScript 框架，旨在创建可互操作的自我主权身份解决方案。 当时我们刚刚熟悉 SSI 的概念。 仅仅是我们可以使用 TypeScript 来构建的想法就让我们的生活变得更加轻松，技术也变得不那么令人生畏。 它变成了我们公司的基石之一，我最终将成为 Hyperledger Aries Framework JavaScript 的维护者和大力倡导者。 现在，经过社区两年的努力，我们很高兴地宣布该框架的 0.2.0 版本发布。 在本文中，我将带您了解这个最新版本的含义以及它为什么会改变构建自主解决方案的方式。

Hyperledger Aries Framework JavaScript (AFJ) is a framework written in TypeScript for creating interoperable self-sovereign identity (SSI) solutions. The framework has two main focus points. It aims to be as accessible as possible for any developer whether new or experienced in the world of SSI. It is also designed specifically for multi-platform development, so both server-side and mobile solutions can be built with the framework.
Hyperledger Aries Framework JavaScript (AFJ) 是一个用TypeScript编写的框架，用于创建可互操作的用户自主身份（SSI）解决方案。该框架有两个主要重点。 它的目标是让任何开发人员，无论是在 SSI 领域的新手还是经验丰富的开发人员，都可以尽可能地易入手。它还多平台开发做了专门的设计，因此可以使用该框架构建服务器端和移动解决方案。

The framework has gained a lot of momentum lately. The community has been growing quickly with various governments and organizations stepping in. Our current contributor count is 37, and the working group calls now have around 10 active participants (as opposed to the two we had two years ago). The potential of the framework has become clear to developers other than us (the fanatics). For example, at Animo we recently received funding from the EU NGI eSSIF-Lab initiative to lift the framework to the next level regarding mobile development options.
该框架最近发展势头很不错。随着各种政府和组织的加入，社区一直在迅速发展。我们目前的贡献者人数为 37 人，工作组电话会议现在有大约 10 名积极参与者（与两年前的两个相比）。除了我们（狂热者）之外的开发人员也已经清楚了该框架的潜力。例如，在 Animo，我们最近收到了来自欧盟 NGI eSSIF-Lab 计划的资助，这将使框架在有关移动开发选项上提升到一个新水平。

The new Hyperledger Aries Framework JavaScript release (0.2.0) contains some incredible steps forward. Especially in our goal to make the framework AIP 2.0 compliant. AIP 2.0 compliance will not only ensure the framework supports the latest standards and protocols, but it will also greatly increase interoperability and make it more useful outside of the Hyperledger Indy ecosystem. Specifically, this release contains:
新的 Hyperledger Aries 框架 JavaScript 版本 (0.2.0) 包含一些令人难以置信的进步。 尤其是我们的目标是使框架符合 AIP 2.0。 AIP 2.0 合规性不仅将确保框架支持最新的标准和协议，而且还将大大提高互操作性并使其在 Hyperledger Indy 生态系统之外更加有用。 具体来说，此版本包含：
- Full support for the out of band and did-exchange protocols
- Postgres wallet support
   - Previously the framework only supported SQLite. This addition ensures the framework is better suited for cloud infrastructure.
- Wallet import/export support
   - This addition enables users to migrate their wallet data to and from other Hyperledger Indy-based wallets.
- Pickup protocol v2 for better control over interactions with the mediator
- Support for the issue-credential-v2 protocol
   - The issue credential and present proof v2 extend the framework with the ability to support multiple credential and proof formats. Instead of adding a separate API for the v2 protocols, we have put a lot of effort in designing a single, easy-to-use API that works with both versions and is extensible for later versions in the future. In the next release we’ll be adding support for the present proof v2 protocol.
- Credential revocation and revocation notifications for holders and verifiers
   - This allows holders to prove that a credential hasn’t been revoked and verifiers to verify this. The revocation notifications allow the holders to be informed about the fact that one of their credentials has been revoked, rather than discovering this when trying to present proof.
- Full did:peer support
- A generic DID resolver that currently supports did:key, did:web, did:sov and did:peer.
- An upgrade assistant to help users update their wallets to newer versions of the framework
   - As the framework evolves over time, some of the underlying data structures may change. With the upgrade assistant, we aim to make it as easy as possible for users to migrate.

- 完全支持带外和做交换协议
- 支持Postgres 钱包
  - 以前该框架仅支持 SQLite。此添加确保该框架对云基础架构有更好的适应性。
- 支持钱包导入/导出
  - 这一新增功能使用户能够将他们的钱包数据迁移到其他基于 Hyperledger Indy 的钱包或从其他钱包迁移出去。
- 采用协议 v2 以便更好地控制与中介的交互
- 支持 issue-credential-v2 协议
  - Issue Creditial 和 Present Proof v2扩展了框架，能够支持多种凭证和证明格式。我们没有为 v2 协议添加单独的 API，而是付出了很多努力来设计一个单一的、易于使用的 API，该 API 在两个版本都可使用，并且可以在未来的更高版本中扩展。在下一个版本中，我们将添加对Present Proof v2 协议的支持。
- 持有者和验证者的证书撤销和撤销通知
  - 这允许持有者证实证书并未被撤销，验证者也可以验证这一点。撤销通知允许持有人被告知他们的凭证之一已被撤销的事实，而不是在尝试提供证据时发现这一点。
- 对 did:peer 的完全支持
- 一个当前支持 did:key、did:web、did:sov 和 did:peer 的通用 DID 解析器。
- 一个升级助手，帮助用户将他们的钱包更新到框架的更新版本
  - 随着框架随着时间的推移而发展，一些底层数据结构可能会发生变化。通过升级助手，我们的目标是让用户迁移尽可能容易。

We’re already working hard on version 0.3.0 that will, just like the 0.2.0 release, be packed with new features such as support for the W3C Verifiable Credential Format and BBS+ Signatures 2020, making the framework fully AIP 2.0 compliant.
我们已经在努力开发 0.3.0 版本，就像 0.2.0 版本一样，它将包含新功能，例如支持 W3C 可验证凭证格式和 BBS+ 签名 2020，使框架完全兼容 AIP 2.0。

Check out the 0.2.0 release here and the update instructions here. For general documentation, please see aries.js.org.
在[此处](https://github.com/hyperledger/aries-framework-javascript/releases/tag/v0.2.0)查看 0.2.0 版本, 以及[此处](https://aries.js.org/guides/updating)可查看更新说明。有关一般文档，请参阅 [aries.js.org](https://aries.js.org/)。

If you’re interested in Hyperledger Aries Framework JavaScript and its developments, we recommend you join the working group call (07:00 MT / 14:00 UTC on zoom) and check out the GitHub repo. If you want to discuss building a solution with the framework, feel free to reach out to me at karim@animo.id.
如果您对 Hyperledger Aries Framework JavaScript 及其开发感兴趣，我们建议您加入工作组电话会议（07:00 MT / 14:00 UTC on [zoom](https://zoom.us/j/92215586249?pwd=Vm5ZTGV4T0cwVEl4blh3MjBzYjVYZz09)）并查看 [GitHub Repo](https://github.com/hyperledger/aries-framework-javascript)。 如果您想讨论使用该框架构建解决方案，请随时通过 karim@animo.id 与我联系。

For hands-on experience with AFJ, join us at Hyperledger Global Forum (HGF) for the half day workshop: How To Build a Self-Sovereign Identity Agent With Hyperledger Aries Framework JavaScript. To get a 20% discount to attend HGF and learn more about Hyperledger Foundation Identity projects, use the code: HGFHLFWG22.
有关 AFJ 的实践经验，请加入我们的 [Hyperledger 全球论坛](https://events.linuxfoundation.org/hyperledger-global-forum/) (HGF) 参加为期半天的研讨会：[如何使用 Hyperledger Aries 框架 JavaScript 构建自我主权身份代理](https://sched.co/15Bjb)。 要获得 20% 的折扣以参加 HGF 并了解有关 Hyperledger Foundation Identity 项目的更多信息，请使用代码：HGFHLFWG22。
