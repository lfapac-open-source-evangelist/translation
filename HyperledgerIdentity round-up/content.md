## HyperledgerIdentity round-up: A cross section of production digital identity solutions built using Hyperledger technologies
## HyperledgerIdentity 综述：使用 Hyperledger 相关技术构建的数字身份产品解决方案的剖析

#### By Hyperledger September 28, 2022 Blog, Hyperledger Aries, Hyperledger Fabric, Hyperledger Indy, Hyperledger Ursa, Identity
#### 作者：Hyperledger | 2022年9月28日 | 博客，Hyperledger Aries, Hyperledger Fabric, Hyperledger Indy, Hyperledger Ursa, 身份

Verifying identities and information in a digital world is critical for establishing trust. But there are issues of privacy as well as efficiency, scale and accuracy in models that rely on centralized data collectors and databases. 

在数字世界里，验证身份和信息对于建立信任至关重要。 但是，传统的依赖于数据采集中心和数据库的模式，存在着隐私、效率、可扩展性和准确性的问题。

The adoption of a new generation of digital identity solutions that leverage decentralized technologies such as distributed ledgers and verifiable credentials is accelerating. And Hyperledger technologies are playing a major role in this transformation. 

最近，新一代的数字身份解决方案广为流行，它是利用分布式账本和可验证凭证等去中心化技术实现的。 Hyperledger 技术在这一转变中发挥着重要作用。

Read on for a cross section of the many Hyperledger-powered solutions that are in production now. For other examples, check out these past #HyperledgerIdentity round-ups:

请继续阅读，以了解多种目前由Hyperledger提供技术支持的产品解决方案的详情。有关其他示例，请查看这些过去的 #HyperledgerIdentity 的汇总：

- Hyperledger-Powered Digital Identity Solutions at Work  

  由 Hyperledger 赋能的数字身份解决方案
  
- Identity Applications in Action & Powered by Hyperledger

  由 Hyperledger 提供支持的实际身份应用程序

### IBM Digital Health Pass
### IBM 数字健康通行证

[IBM Digital Health Pass](https://www.ibm.com/products/digital-health-pass), built on [Hyperledger Fabric](https://www.hyperledger.org/use/fabric), offers a multi-credential verifier that organizations can use to manage and execute their verification policies for COVID-19 and vaccination status in a way that balances the privacy of the individual with the requirements set by the organization and local health authorities. With IBM Digital Health Pass, organizations can verify multiple types of health credentials, such as Good Health Pass, IBM Digital Health Pass, Smart Health Card and EU Digital COVID Certificate. Privacy is central to the solution, where the verifier application minimizes the personal data that is ever displayed to the user through the execution of business rules and it never lets any personal data leave, or be stored in, the verifier app.

基于 [Hyperledger Fabric](https://www.hyperledger.org/use/fabric) 构建的 [IBM Digital Health Pass](https://www.ibm.com/products/digital-health-pass) 提供了一个多凭证验证器，组织可以使用该验证器管理和执行针对COVID-19新冠肺炎和疫苗接种状态的验证策略，以平衡个人隐私与由组织和当地卫生当局设置的要求。借助 IBM Digital Health Pass，组织可以验证多种类型的健康凭证，例如 Good Health Pass、IBM Digital Health Pass、Smart Health Card 和 EU Digital COVID Certificate。 隐私是该解决方案的核心，验证程序通过执行业务规则，以最小化向用户显示的个人数据，并且绝不允许任何个人数据离开或存储在验证程序中。

### Indicio Network 
### Indicio 网络

The Indicio Network is a collection of four professionally-staffed, enterprise-grade public-permissioned ledgers that provide a neutral, independent, and reliable network for the exchange of verifiable credentials. MainNet, DemoNet, TestNet, and TempNet are all Hyperledger Indy-based networks with nodes operating on five continents—and a growing number of node operators. The Indicio Network is one of the networks that can support Indicio Proven, a complete suite of decentralized identity components for authenticating and sharing high value data in a privacy-preserving way using verifiable digital credentials. Built on Hyperledger Aries and Hyperledger Ursa, as well as AnonCreds and DIDComm, Proven is designed to make implementing and using these open source codebases simple, providing users with a fully-owned solution that’s easy to integrate with existing systems, to innovate on, and to scale.  

Indicio 网络是由四个配备专业人员的企业级公共许可账本组成的，它们为交换可验证凭证提供了中立、独立和可靠的网络。 MainNet、DemoNet、TestNet 和 TempNet 都是基于 Hyperledger Indy 的网络，其节点分布在五大洲运行，节点运营商的数量也在不断增加。 Indicio 网络是可以支持 Indicio Proven 的网络之一，Indicio Proven 是一套完整的去中心化身份组件，用于使用可验证的数字凭证以保护隐私的方式验证和共享高价值的数据。 Proven 建立在 Hyperledger Aries 和 Hyperledger Ursa 以及 AnonCreds 和 DIDComm 之上，旨在简化这些开源代码库的实施和使用，为用户提供一个完全自主的解决方案，便于用户与现有系统集成，进行创新和规模化使用。

### IDUnion 
### IDUnion

[IDUnion](https://idunion.org/?lang=en), the European identity verification network created as part of the “Secure Digital Identities Showcase” funding project, brings together public institutions, government agencies, private organizations, associations, educational institutions and other stakeholders from various fields to enable a fundamentally new, secure digital infrastructure for the verification of identity information. In August, 2022, IDUnion spun off Sociedad Cooperativa Europea (SCE) to operate the production network for credential verification. 

[IDUnion](https://idunion.org/?lang=en) 是作为“安全数字身份示范案例”资助项目的一部分而创建的欧洲身份验证网络，它汇集了公共机构、政府机构、私人组织、协会、教育机构和其他来自各个领域的利益相关者，以实现一个全新的、用于身份信息验证的安全数字基础设施。2022年8月，IDUnion 从 Sociedad Cooperativa Europea (SCE) 中剥离出来，以运营验证凭证的生产网络。

The IDUnion network, which is built on [Hyperledger Indy](https://www.hyperledger.org/use/hyperledger-indy), enables the clear verification of individuals, companies and institutions while allowing people and organizations to manage their identity information by themselves and to decide when they want to share this information and with whom. It has a decentralized structure and stores no personal data – not even as a hash. In order to protect privacy right from the start, all personal data is stored on the user’s end device. Users have a choice of wallets for storing and presenting credentials to third parties as required. Credentials are issued, verified and stored using open standards to ensure interoperability. Hyperledger Aries is the framework for managing the credentials.

基于[Hyperledger Indy](https://www.hyperledger.org/use/hyperledger-indy)构建的 IDUnion 网络，能够清晰地验证个人、公司和机构，同时允许个人和组织自行管理身份信息，并可决定什么时间、与谁共享这些信息。它具有去中心化的结构，不存储个人数据----甚至不存储一个哈希。 为了从一开始就保护隐私权，所有个人数据都存储在用户的终端设备上。用户可以根据需要选择钱包，用于存储凭证并出示给第三方。使用开放标准颁发、验证和存储凭证，以确保互操作性。Hyperledger Aries 是管理凭证的框架。

