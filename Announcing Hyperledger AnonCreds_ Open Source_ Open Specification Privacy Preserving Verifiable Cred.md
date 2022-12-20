# Announcing Hyperledger AnonCreds: Open Source, Open Specification Privacy Preserving Verifiable Credentials

声明 Hyperledger AnonCreds: 开源, 开放规范，保护隐私的可验证凭证

By Stephen Curran, Maintainer, Hyperledger AnonCreds November 15, 2022 [Blog](https://www.hyperledger.org/category/blog), [Hyperledger AnonCreds](https://www.hyperledger.org/category/hyperledger-anoncreds), [Identity](https://www.hyperledger.org/category/identity)

作者：Stephen Curran，Hyperledger AnonCreds的维护者 2022年11月15日 博客, Hyperledger AnonCreds, 身份识别

AnonCreds, the most commonly used Verifiable Credential (VC) format in the world*, is now a Hyperledger project. Ledger agnostic and with a formal open specification, AnonCreds continues to evolve as a mature verifiable credential format with unique privacy-protecting capabilities. As a Hyperledger project, AnonCreds will have support to grow its code base and community on a global level with technical governance that fosters best open development and security practices.

AnonCreds是世界上最常用的可验证凭证（VC）格式*，现在是一个Hyperledger项目。AnonCreds与账本无关，并且有正式的开放规范，它作为一种成熟的可验证凭证格式继续发展，具有独特的隐私保护能力。作为一个Hyperledger项目，AnonCreds将得到支持，在全球范围内发展其代码库和社区，并通过技术管理来促进最佳的开放开发和安全实践。

As the Internet transitions to allowing people, organizations, and things to have greater control over the sharing of their credentials, protecting privacy is of paramount concern.

随着互联网过渡到允许人们、组织和事物对其凭证的共享拥有更大的控制权，保护隐私是最重要的问题。

[Hyperledger AnonCreds](https://www.hyperledger.org/use/anoncreds)—short for “Anonymous Credentials”—is a type of VC that adds important privacy-protecting ZKP (zero-knowledge proof) capabilities to the core VC assurances. A core element of the Hyperledger Indy project for more than five years, AnonCreds is a mature, complete model and interactions set, with extensive support across Hyperledger Aries frameworks.

Hyperledger AnonCreds--"匿名凭证 "的缩写--是一种VC，它在核心VC保证的基础上增加了重要的隐私保护ZKP（零知识证明）能力。作为Hyperledger Indy项目五年多来的核心要素，AnonCreds是一个成熟、完整的模型和交互集，在Hyperledger Aries框架中得到广泛支持。

The creation of this project signifies the continued healthy evolution of an open source software project that was once monolithic and is now a set of well-defined independent components. 

这个项目的创建标志着一个开源软件项目的持续健康发展，这个项目曾经是单一的，现在是一套定义明确的独立组件。

Hyperledger AnonCreds is ledger-agnostic and client-agnostic. It is not tied to Hyperledger Indy or Aries. This makes it usable with other verifiable data registries/ledgers and verifiable credential client stacks. As a result, important  privacy-protecting capabilities become available to a much broader audience, and the underlying cryptography can evolve without affecting the features above it.

Hyperledger AnonCreds是分类账无关的，也是客户无关的。它不与Hyperledger Indy或Aries绑定。这使得它可以与其他可验证的数据注册表/分类账和可验证的凭证客户端堆栈一起使用。因此，重要的隐私保护功能可以被更多的人使用，而且底层的密码学可以在不影响上面功能的情况下发展。

Additional benefits of using Hyperledger AnonCreds include:

使用Hyperledger AnonCreds的其他好处包括。

* Avoidance of identifiers: No correlatable identifiers are required in presenting data to a verifier. Correlatable identifiers may be applied in a use case specific manner.
避免标识符的使用。在向验证者展示数据时，不需要可关联的标识符。可关联的标识符可以以特定的方式应用于使用情况。

* Verifier assurances: Credentials are bound to the holder, so verifiers know that credentials presented together were all issued to the holder providing the presentation.
验证人的保证。凭证与持有者绑定，所以验证者知道一起提交的凭证都是发放给提供演示的持有者的。

* Minimal data sharing: Data to be shared by a holder to a verifier is minimized through the use of selective disclosure and ZKP predicates
最小的数据共享。通过使用选择性披露和ZKP谓词，持有者向验证者共享的数据被最小化。

Flexible formatting: Credentials and presentations can be formatted in the W3C VC Data Model standard format.

灵活的格式化。凭证和演示文稿可以用W3C VC数据模型的标准格式进行格式化。

AnonCreds has joined the Hyperledger ecosystem with [over 25 sponsors](https://hyperledger.github.io/hyperledger-hip/HIPs/anoncreds.html). The project consists of:

AnonCreds已经加入了Hyperledger生态系统，有超过25个赞助商。该项目由以下部分组成。

* The AnonCreds Specification, managed by the [Hyperledger AnonCreds Specification Working Group](https://wiki.hyperledger.org/display/ANONCREDS/AnonCreds+Specification+Working+Group) and with the potential of being submitted to an appropriate Standards organization
AnonCreds规范，由Hyperledger AnonCreds规范工作组管理，并有可能提交给一个适当的标准组织

* Ledger/Verifiable Data Registry-agnostic, open source code implementations of the AnonCreds specification, suitable for use with Hyperledger Aries and non-Aries agents
账本/可验证数据注册表--AnonCreds规范的开放源代码实现，适用于Hyperledger Aries和非Aries代理。

* Guidance for creating ledger-specific [AnonCreds Methods](https://hyperledger.github.io/anoncreds-methods-registry/) to write and resolve AnonCreds objects for specific ledgers
创建特定分类账的AnonCreds方法的指导，为特定分类账编写和解决AnonCreds对象

* Documentation on AnonCreds suitable for all audiences, from business audiences to cryptographers
关于AnonCreds的文件适合所有受众，从商业受众到密码学家。

* A test suite to verify adherence to the AnonCreds specification and the interoperability of AnonCreds implementations.
一个测试套件，以验证对AnonCreds规范的遵守和AnonCreds实施的互操作性。

Next steps include evolving the existing [AnonCreds Rust implementation](https://github.com/hyperledger/anoncreds-rs) to be friendlier to VDRs/ledgers other than Indy, wrapping up the v1.0 specification, and gaining compliance with the W3C Verifiable Credentials Data Model Standard.

接下来的步骤包括发展现有的AnonCreds Rust实现，使其对Indy以外的VDR/ledger更友好，完成V1.0规范，并符合W3C可验证凭证数据模型标准。

If you’re interested in learning more about AnonCreds start with the [Hyperledger AnonCreds project page](https://hyperledger.org/use/anoncreds). From there you can find how to join project discussions on Discord, add yourself to the project mailing list, find the AnonCreds repositories on GitHub, and join the AnonCreds Working Groups.

如果你有兴趣了解更多关于AnonCreds的信息，请从Hyperledger AnonCreds项目页面开始。在那里，你可以找到如何在Discord上加入项目讨论，将自己添加到项目邮件列表中，在GitHub上找到AnonCreds存储库，并加入AnonCreds工作组。

We welcome interest from all groups and organizations, including enterprises and standards organizations. We look forward to hearing from you!

我们欢迎所有团体和组织的兴趣，包括企业和标准组织。我们期待着您的来信!

**Source: godiddy.com combined “sov” (Indy) network volume*

