### Introducing Hyperledger Cacti, a multi-faceted pluggable interoperability framework
### Hyperledger Cacti 项目介绍，一个多方面的可插拔的互操作性框架

By Peter Somogyvari (Accenture), Jagpreet Singh Sasan (Accenture), Izuru Sato (Fujitsu), Takuma Takeuchi (Fujitsu), 
Venkatraman Ramakrishna (IBM), Sandeep Nishad (IBM), Krishnasuri Narayanam (IBM), Dhinakaran Vinayagamurthy (IBM) 
November 7, 2022 Blog, Hyperledger Cacti, Interoperability

作者：Peter Somogyvari（埃森哲），Jagpreet Singh Sasan（埃森哲），Izuru Sato （富士通），Takuma Takeuchi（富士通），
Venkatraman Ramakrishna (IBM), Sandeep Nishad (IBM), Krishnasuri Narayanam (IBM), Dhinakaran Vinayagamurthy (IBM)
2022年11月7日，博客，Hyperledger Cacti，互操作性

In a Hyperledger first, the community has merged two systems (architectures as well as code bases) to create a new project. [Hyperledger Cacti](https://www.hyperledger.org/use/cacti) is a multi-faceted interoperability platform that draws on the cutting-edge technical features of Hyperledger Cactus and Weaver, a Hyperledger Lab, and provides a clear path forward for users of both technologies.

首先在超级账本中，社区合并了两个项目系统（包括架构和代码库）创建了一个新项目。[Hyperledger Cacti](https://www.hyperledger.org/use/cacti) 是一个多方面的互操作性平台，它借鉴了 Hyperledger Cactus 和 Weaver（一个超级账本的实验室项目）的前沿技术特性，为这两种技术的用户提供了清晰的技术路线。

Hyperledger Cacti is a pluggable interoperability framework to link networks built on heterogeneous distributed ledger and blockchain technologies and to run transactions spanning multiple networks. Cacti was motivated by the observation that the blockchain/DLT ecosystem is fragmented into several independent networks built on a diverse set of DLTs, many of which are permissioned, but which cannot afford to remain isolated from each other, limiting the scale and utility of their business processes (smart contracts and “dapps”) and trapping their assets in silos.

Hyperledger Cacti 是一个可插拔的互操作性框架，用于链接基于异构分布式账本和区块链技术构建的网络，并运行跨多个网络的交易。建立 Cacti 的初衷是观察到区块链/DLT生态系统被分割成了几个独立的网络，每个网络基于不同的DLT技术构建而成，其中许多是许可链项目，但这些项目因为彼此隔离，限制了它们的业务流程（基于智能合约和去中心化应用“dapps”）的规模和效用，使其资产被困在孤岛中。

Consider a trade logistics network (like [TradeLens](https://www.tradelens.com/)) that maintains bills of lading for shipments on its ledger. These bills are necessary to fulfill letters of credits’ payment obligations on a trade finance network (like [Marco Polo](https://marcopolonetwork.com/)), but without an institutionalized mechanism to share a bill of lading with proof of authenticity between the two networks, the trade finance network will have to depend on untrustworthy shippers, who are incentivized to supply fake bills in order to get payment. In another scenario that is increasingly common and salient in the DeFi world, financial instruments and currency accounts (e.g., Central Bank DIgital Currency, or CBDC) are maintained on different ledgers. But this state-of-affairs will inhibit trading, and limit the utility of these networks as well as the DLTs they are built on, unless mechanisms to atomically exchange, say, a security on one network for digital currency tokens on another, are institutionalized.

以一个贸易物流网络（如 [TradeLens](https://www.tradelens.com/)）为例，它采用区块链账本记录货物提单。在贸易融资网络（如 [Marco Polo 马可波罗](https://marcopolonetwork.com/)）上履行信用证付款义务时，需要使用这些票据提单，但当前欠缺制度化的机制以支持在两个网络之间共享提单和真实性证明，贸易融资网络不得不依赖于不可信的托运人，为了能顺利获得付款，就贿赂托运人提供虚假账单。另一种是在 DeFi 场景中越来越普遍和突出的需求，金融工具和货币账户（例如，中央银行数字货币或CBDC）维护在不同的区块链账本中。但是这种事态将抑制货币的交换，并限制这些网络及其所建立的 DLT 的效用，除非实现原子交换机制（比如将一个网络上的证券转换成另一个网络上的数字代币）的制度化。

Extrapolating from these examples and others that are commonly encountered by enterprises and business consortia, we can identify the need for networks to interoperate for the purposes of sharing ledger state, moving assets across network boundaries, and exchanging assets atomically. But, because there are cogent privacy, autonomy, and performance reasons for a large number of such networks to co-exist, such interoperability must be enabled without forcing them all to coalesce into a single global chain or subscribe to a single global settlement chain.

从这些例子以及企业和商业联盟经常遇到的其他例子中推断，我们可以确定为了实现账本状态的共享、跨网络边界的资产转移和资产的原子性交换而进行网络互操作的必要性。但是，考虑到各个网络的隐私性、自治性及性能的原因，必然需要多个网络共存，不能迫使它们全部合并成一个单一的全球性网络或基于单一的全球结算链的订阅模式，因此必须实现这些网络间的互操作性。

Hyperledger Cacti provides an interoperability solution that does not require the networks’ respective chains to coalesce into one “chain to rule them all.” It also does not require the creation of yet another settlement chain and consensus protocol to which existing networks must subscribe. Instead, Cacti allows networks to preserve autonomy of decision-making while conducting cross-network transactions on a need basis. In effect, Hyperledger Cacti scales decentralized trust above and beyond the confines of a single network without requiring networks to merge or integrate, in effect enabling a network-of-networks, as illustrated in the figure below using samples of DLT networks and cross-chain operations. 

Hyperledger Cacti 提供了一种互操作性解决方案，它不需要将多条链合并成一条“统一链”来统治管理，也不需要创建一条新的结算链及共识协议让现有的网络订阅。相反，Cacti 允许每条网络在根据需要进行跨链交易时保持决策自主权。实际上，Hyperledger Cacti 将去中心化的信任延伸到了单个网络的范围之外，无需合并或集成网络，而是采用了基于网络的网络，如下图的示例中使用的 DLT 网络和跨链操作。

![image](https://user-images.githubusercontent.com/89500827/201513568-65fae50e-441a-474e-bb93-8a30f628f83e.png)

A core design tenet of Hyperledger Cacti is that it does not require modification to any existing DLT stack, and operates purely at the contract- and-application layers (or Layer 2). This allows Cacti to be used not only for networks built on existing DLTs but potentially for DLTs that have yet to emerge. The initial release of Hyperledger Cacti will provide interoperability and connectivity features to varying extents for the following nine DLTs. (Interoperability support for other DLTs will be added to the future roadmap of the project.)

Hyperledger Cacti 的一个核心设计原则是，它不需要修改任何现有的 DLT 技术堆栈，只是在合约层和应用层（或第2层）运行。这使得 Cacti 不仅可以适用于现有的 DLT 技术构建的网络，还可以适用于未来的 DLT 技术。Hyperledger Cacti 的初始版本将为以下九种 DLT 技术提供不同程度的互操作性和连接功能（在后续的项目路线图中会添加对其他DLT技术的互操作性支持）。

* Hyperledger Besu
* Hyperledger Fabric
* Hyperledger Indy
* Hyperledger Iroha
* Hyperledger Sawtooth
* R3 Corda
* Go-Ethereum
* Quorum
* Xdai

The Cacti architecture builds on the pre-existing architecture of both Hyperledger Cactus and the Weaver Labs frameworks, merging components having similar or identical functionality and aggregating distinct components to offer several features that span a wide spectrum of trust and usability. The Cacti plugin architecture will enable the coexistence and maintenance of different feature/protocol implementations which can be selectively activated on demand with minimum configuration overhead. Users can customize the level of decentralization they require using a combination of the Node Server inherited from Cactus and a pluggable network-centric relay (or gateway) inherited from Weaver. The figure below illustrates how distributed applications running on distinct ledgers can trigger cross-network transactions either from a centralized Node Server or in a peer-to-peer manner using relays. The applications can be deployed in a standalone legacy manner or be “plugged into” the Node Server; developers and administrators may choose the option that fits their requirements better. All cross-relay communication protocols implemented in Cacti will be DLT-agnostic and comply with emerging standards. 

Cacti 的架构建立在 Hyperledger Cactus 和 Weaver Labs 现有的架构之上，已经合并了两者相似或相同的组件，并整合了不同的功能组件，以提供更广泛的信任技术和可用性的多个功能。Cacti 的插件架构可支持不同功能/协议实现的共存，这些功能/协议可以根据需要以最小的配置开销选择性地激活。用户可以使用继承自 Cactus 的节点服务器（Node Server）和继承自 Weaver 的可插拔网络中心中继器（或网关）的组合，来自定义所需的去中心化应用级别。下图说明了在不同的区块链账本上运行的分布式应用程序，如何基于集中的节点服务器或使用点对点的中继器触发跨网络交易的。应用程序可以采用传统的方式独立部署，也可以“插入”节点服务器；开发人员和管理员可以根据需要自行选择。Cacti 中实现的所有跨中继通信协议，与具体的 DLT 技术无关，并可兼容后续的新兴标准。

![image](https://user-images.githubusercontent.com/89500827/201515064-bd16fdb9-2dce-4251-9738-12f8082a55be.png)

Core interoperability features of proof validation and lock management can be performed using either designated validator pools or with smart contracts and DApps installed in the core networks themselves; users may select these options depending on the level of trust they require and correspondingly, the level of administrative overhead they are willing to accept. Cacti will offer these features and the ability to select and activate them through a common (and comprehensive) client SDK and API. To provide a foundation for interoperability across heterogeneous DLTs, Cacti will maintain a pool of DLT- and version-specific connectors or drivers that will act as entry points for operations in a given ledger that must occur in the context of a multi-ledger transaction.

互操作性的核心功能，如证明验证和锁定管理，可以使用指定的验证池或安装在核心网络中的智能合约和 DApp 来执行；用户可以根据所需的信任级别和愿意接受的管理开销进行选择。Cacti 提供通用的（或者说全面的）客户端 SDK 和 API 的方式，支持用户自行选择和激活相关的功能。为了提供异构 DLT 的互操作性基础，Cacti 将维护一个连接器或驱动程序池，支持多种DLT技术的不同版本，在跨账本交易的场景中，这些连接器或驱动程序就充当某个特定账本的操作的入口。

To learn more, join us Monday, November 14, from 11am-2pm EST for the “Blockchain Interoperability with Hyperledger Cacti” hands-on workshop. To register, go [here](https://zoom.us/meeting/register/tJ0vdOuoqT0qH9bRetrLUqbuHH_UykJs7DTf). 

想要了解更多信息，请在美国东部标准时间11月14日星期一上午11点至下午2点加入我们，参加“与 Hyperledger Cacti 的区块链互操作性”实践研讨会。想要注册，请点击[这里](https://zoom.us/meeting/register/tJ0vdOuoqT0qH9bRetrLUqbuHH_UykJs7DTf)。

To get involved in the Hyperledger Cacti community, connect with us on [Discord](https://discord.com/channels/905194001349627914/908379366650703943). All are welcome!

想要加入 Hyperledger Cacti 社区，请在[Discord](https://discord.com/channels/905194001349627914/908379366650703943)上与我们联系。欢迎大家！


