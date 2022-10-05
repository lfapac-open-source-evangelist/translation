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

### NHS Covid-19 Digital Staff Passport
### NHS Covid-19 数字员工护照

In 2019, the NHS was preparing to pilot a digital passport project that would allow staff to carry their HR and other records as credentials on their phones as a long-term plan to make it easier to transfer from one facility to another. When the pandemic hit, this went from a pilot to a production deployment quickly. The [NHS Covid-19 Digital Staff Passport](https://beta.staffpassports.nhs.uk/) rolled out in summer to support swift and efficient staff movement between NHS organizations in response to the response health emergency. The COVID-19 Digital Staff Passport provided a solid legal framework for staff to be temporarily deployed into other NHS organizations with evidence available that checks have been completed before staff move. As laid out in the pilot, the information was transferred securely by the staff member as verified credentials stored on their own smartphone, putting them in control.

2019年，NHS 正准备试行一个数字护照项目，该项目允许员工在手机上保存他们的HR记录和其他记录的凭证信息，作为一项长期计划，还要便于员工将凭证信息从一个设备迁移到另一个设备。当疫情来袭时，这一举措迅速从试点项目转变为实际生产部署。[NHS Covid-19 数字员工护照](https://beta.staffpassports.nhs.uk/)于2020年夏季推出，支持 NHS 组织之间快速高效的员工流动，以应对卫生紧急情况。 COVID-19 数字员工护照为临时调度到其他 NHS 组织的员工提供了坚实的法律框架，在员工调动之前已完成检查，相关的凭证立等可取。正如试点中所述，信息由工作人员安全传输，验证过的凭证存储在他们自己的智能手机上，由他们自己控制。

This staff passport used the Sorvin Network, which is built on Hyperledger Indy, to verify the digital credentials, and the Evernym (now Avast) Connect.me digital wallet app, which is powered by Hyperledger Aries, Indy and Ursa, to enable staff to store and share their credentials. 

该员工护照使用基于 Hyperledger Indy 构建的 Sorvin 网络来验证数字凭证，由Hyperledger Aries、Indy 和 Ursa 提供支持的 Evernym（现在是 Avast）Connect.me 数字钱包应用程序，使员工能够存储和共享他们的凭据。

The NHS is now gearing up to roll out the next generation of its Digital Staff Passport, which will streamline transfers and staff movements through the NHS. 

NHS 现在正准备推出下一代数字员工护照，这将通过NHS简化人员调度和员工流动。

### OrgBook BC 
### OrgBook BC 

OrgBook BC is a searchable public directory of organizations registered in British Columbia, Canada, provided by the BC Government’s Ministry of Citizens’ Services. OrgBook BC provides verified data, including legal names and DBA names, business numbers, BC registration status and select licensee and permits, for more than 1.4 million organizations. All of the information in the OrgBookBC is received, stored, verified and displayed using the latest digital trust technologies. 

OrgBook BC 提供一个公共目录服务，可搜索在加拿大不列颠哥伦比亚省注册的组织信息，该服务由不列颠哥伦比亚省政府的公民服务部提供。 OrgBook BC 为超过 140 万个组织提供验证过的数据，包括法定名称和 DBA 名称、企业编号、在不列颠哥伦比亚的注册状态以及选定的被许可人和许可证。 OrgBook BC 中的所有信息都是使用最新的数字信任技术传输、存储、验证和显示的。

OrgBookBC uses verifiable credentials to ensure that information about organizations are digitally signed by the entity that issues it. Issuers are public sector organizations that hold information about businesses, issue licenses or permits or certify processes. That electronic signature stays with the data throughout its life in OrgBook and is validated before its is display on the website. 

OrgBook BC 使用可验证的凭证，确保有关组织的信息已经由发行的实体进行了数字签名。凭证的发行人是持有企业信息、颁发执照或许可证或认证流程的公共部门组织。该电子签名在 OrgBook 的整个生命周期中都保留在数据中，并在网站上显示之前进行验证。

OrgBookBC is part of an overall commitment to digital trust technologies by the Government of British Columbia. In addition to deploying Hyperledger Aries, Indy and Ursa, the team there is leading much of the open source development for those projects. Read more on the Government of BC’s investment in verifiable credentials and digital wallet technologies [here](https://www.hyperledger.org/blog/2022/08/23/investing-in-verifiable-credentials-technical-interoperability-and-open-source). 

OrgBookBC 是不列颠哥伦比亚省政府承诺全面数字信任技术的一部分。除了部署 Hyperledger Aries、Indy 和 Ursa 之外，该团队还领导着这些项目的大部分开源代码的开发。有关不列颠哥伦比亚省政府对可验证凭证和数字钱包技术的投资的更多信息，详见[这里](https://www.hyperledger.org/blog/2022/08/23/investing-in-verifiable-credentials-technical-interoperability-and-open-source)。

### Digital Identity updates from Hyperledger Global Forum
### Hyperledger 全球论坛的数字身份更新信息

At Hyperledger Global Forum 2022, there was a range of business, technical and demo sessions focused on digital identity, including:

在2022年的Hyperledger 全球论坛上，有一系列专注于数字身份的商业、技术和演示章节，包括：

- [Bringing Trustworthiness in Industrial Device Lifecycle using Verifiable Credentials](https://sched.co/14H61) – Marquart Franz & Saad Bin Shams, Siemens AG

   [使用可验证凭证，提升工业设备生命周期中的可信度](https://sched.co/14H61) -- 西门子股份公司的Marquart Franz & Saad Bin Shams, 
   
- Findy Agency — Highway to Verified Data Networks – Laura Vuorenoja & Harri Lainio, OP Financial Group
   
   [Findy Agency -- 通往已验证数据网络的高速公路](Findy Agency — Highway to Verified Data Networks ) -- OP财务组的Laura Vuorenoja & Harri Lainio, 

- [Digital Identity Using the vLEI](https://sched.co/14H6n) – Christoph Schneider, Global Legal Entity Identifier Foundation (GLEIF)

  [使用vLEI 的数字身份](https://sched.co/14H6n) --  全球法律实体识别基金会(GLEIF)的Christoph Schneider
  
- [Blockchain, Biometrics and Geo-Location: Lessons Learned from the Implementation of Innovative Technologies at the United Nations Joint Staff Pension Fund](https://sched.co/14H5m) – Dino Cataldo Dellaccio, United Nations Joint Staff Pension Fund & Shashank Rai, United Nations International Computing Centre (UNICC)

  [区块链、生物识别和地理位置：联合国合办工作人员养恤基金在实施创新技术中的经验教训](https://sched.co/14H5m) -- 联合国合办工作人员养恤基金的Dino Cataldo Dellaccio和联合国国际计算中心（UNICC）的Shashank Rai
   
- [Hosted Discussion: Rhode Island Leads on Digital Identity Solutions with Hyperledger](https://sched.co/14H6e) – Liz Tanner, State of Rhode Island & Jim Mason, DTCC

  [主持讨论：罗德岛州通过Hyperledger引领数字身份解决方案](https://sched.co/14H6e) -- 罗德岛州的Liz Tanner和DTCC的Jim Mason
  
- [Last Mile Problem in Self-Sovereign Identity – Biometric Authentification and Device Independent Wallet for Hyperledger Indy](https://sched.co/14H4u) – Non Kawana & Ken Naganuma, Hitachi, Ltd.

  [自我主权身份的最后一英里问题 -- Hyperledger Indy的生物识别认证和设备独立钱包](https://sched.co/14H4u) -- 日立公司的Non Kawana & Ken Naganuma
  
- [Workshop: How To Build a Self-Sovereign Identity Agent With Hyperledger Aries Framework JavaScript](https://sched.co/15Bid) – Timo Glastra & Berend Sliedrecht, ANIMO & Jakub Koci, ABSA

  [研讨会：如何使用Hyperledger Aries Javascript 框架构建自我主权身份代理](https://sched.co/15Bid) -- ANIMO的Timo Glastra & Berend Sliedrecht 和ABSA的Jakub Koci
  
[Join the conversation](https://twitter.com/Hyperledger) about blockchain-based identity technologies and solutions with #HyperledgerIdentity on social channels. For a hands-on introduction to the market and technologies, join the free four hour [Build Your Identity Solution Using Hyperledger Aries](https://wiki.hyperledger.org/display/events/Build+Your+Identity+Solution+Using+Hyperledger+Aries) workshop. Or, for a more business level introduction, sign up for the free Getting Started with Self-Sovereign Identity (LFS178x) online course from Linux Foundation Training & Certification.

通过社交渠道上的#HyperledgerIdentity 加入[关于基于区块链的身份技术和解决方案的对话](https://twitter.com/Hyperledger)中来。要获得市场和技术的实际介绍，请参加大约四小时的“[使用Hyperledger Aries构建您的身份解决方案](https://wiki.hyperledger.org/display/events/Build+Your+Identity+Solution+Using+Hyperledger+Aries)”研讨会（免费的）。或者，要了解更多业务级别的介绍，请注册 Linux Foundation Training & Certification提供的的“[自我主权身份入门(LFS178x)](https://training.linuxfoundation.org/blog/learn-the-fundamentals-of-self-sovereign-identity-in-free-online-training-course/?utm_medium=partner-marketing&utm_source=lf&utm_campaign=linuxfoundation&utm_content=pr-lfs178)”在线课程（免费的）。

  
  
   
