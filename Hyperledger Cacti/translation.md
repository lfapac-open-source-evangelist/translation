### Introducing Hyperledger Cacti, a multi-faceted pluggable interoperability framework
### 介绍Hyperledger Cacti项目，一个多方面的可插拔的互操作性框架

By Peter Somogyvari (Accenture), Jagpreet Singh Sasan (Accenture), Izuru Sato (Fujitsu), Takuma Takeuchi (Fujitsu), 
Venkatraman Ramakrishna (IBM), Sandeep Nishad (IBM), Krishnasuri Narayanam (IBM), Dhinakaran Vinayagamurthy (IBM) 
November 7, 2022 Blog, Hyperledger Cacti, Interoperability

作者：Peter Somogyvari（埃森哲），Jagpreet Singh Sasan（埃森哲），Izuru Sato （富士通），Takuma Takeuchi（富士通），
Venkatraman Ramakrishna (IBM), Sandeep Nishad (IBM), Krishnasuri Narayanam (IBM), Dhinakaran Vinayagamurthy (IBM)
2022年11月7日，博客，Hyperledger Cacti，互操作性

In a Hyperledger first, the community has merged two systems (architectures as well as code bases) to create a new project. [Hyperledger Cacti](https://www.hyperledger.org/use/cacti) is a multi-faceted interoperability platform that draws on the cutting-edge technical features of Hyperledger Cactus and Weaver, a Hyperledger Lab, and provides a clear path forward for users of both technologies.

首先在超级账本中，社区合并了两个项目系统（包括架构和代码库）以创建一个新项目。[Hyperledger Cacti](https://www.hyperledger.org/use/cacti)是一个多方面的互操作性平台，它借鉴了Hyperledger Cactus和Weaver（一个超级账本的实验室项目）的前沿技术特性，为这两种技术的用户提供了清晰的前进道路。

Hyperledger Cacti is a pluggable interoperability framework to link networks built on heterogeneous distributed ledger and blockchain technologies and to run transactions spanning multiple networks. Cacti was motivated by the observation that the blockchain/DLT ecosystem is fragmented into several independent networks built on a diverse set of DLTs, many of which are permissioned, but which cannot afford to remain isolated from each other, limiting the scale and utility of their business processes (smart contracts and “dapps”) and trapping their assets in silos.

Hyperledger Cacti是一个可插拔的互操作性框架，用于链接基于异构分布式账本和区块链技术构建的网络，并运行跨多个网络的交易。Cacti的初衷是观察到区块链/DLT生态系统被分割成几个独立的网络，每个网络基于不同的DLT技术构建而成，其中许多是许可链项目，但这些项目因为彼此隔离，限制了它们的业务流程（基于智能合约和去中心化应用“dapps”）的规模和效用，使其资产被困在孤岛中。

Consider a trade logistics network (like [TradeLens](https://www.tradelens.com/)) that maintains bills of lading for shipments on its ledger. These bills are necessary to fulfill letters of credits’ payment obligations on a trade finance network (like [Marco Polo](https://marcopolonetwork.com/)), but without an institutionalized mechanism to share a bill of lading with proof of authenticity between the two networks, the trade finance network will have to depend on untrustworthy shippers, who are incentivized to supply fake bills in order to get payment. In another scenario that is increasingly common and salient in the DeFi world, financial instruments and currency accounts (e.g., Central Bank DIgital Currency, or CBDC) are maintained on different ledgers. But this state-of-affairs will inhibit trading, and limit the utility of these networks as well as the DLTs they are built on, unless mechanisms to atomically exchange, say, a security on one network for digital currency tokens on another, are institutionalized.

以一个贸易物流网络（如[TradeLens](https://www.tradelens.com/)）为例，它采用区块链账本记录货物提单。在贸易融资网络（如[Marco Polo 马可波罗](https://marcopolonetwork.com/)）上履行信用证付款义务时，需要使用这些票据提单，但当前欠缺制度化的机制支持在两个网络之间共享提单和真实性证明，贸易融资网络不得不依赖于不可信的托运人，为了能顺利获得付款，就贿赂托运人提供虚假账单。另一种是在DeFi场景中越来越普遍和突出的需求，金融工具和货币账户（例如，中央银行数字货币或CBDC）维护在不同的区块链账本中。但是这种事态将抑制货币的交换，并限制这些网络及其所建立的DLT的效用，除非实现原子交换机制（比如将一个网络上的证券转换成另一个网络上的数字代币）的制度化。

Extrapolating from these examples and others that are commonly encountered by enterprises and business consortia, we can identify the need for networks to interoperate for the purposes of sharing ledger state, moving assets across network boundaries, and exchanging assets atomically. But, because there are cogent privacy, autonomy, and performance reasons for a large number of such networks to co-exist, such interoperability must be enabled without forcing them all to coalesce into a single global chain or subscribe to a single global settlement chain.

从这些例子以及企业和商业联盟经常遇到的其他例子中推断，我们可以确定为了实现账本状态的共享、跨网络边界的资产转移和资产的原子性交换而进行网络互操作的必要性。但是，考虑到各个网络的隐私性、自治性及性能的原因，必然需要多个网络共存，不能迫使它们全部合并成一个单一的全球链网络或订阅单一的全球结算链，但必须实现这些网络间的互操作性。

Hyperledger Cacti provides an interoperability solution that does not require the networks’ respective chains to coalesce into one “chain to rule them all.” It also does not require the creation of yet another settlement chain and consensus protocol to which existing networks must subscribe. Instead, Cacti allows networks to preserve autonomy of decision-making while conducting cross-network transactions on a need basis. In effect, Hyperledger Cacti scales decentralized trust above and beyond the confines of a single network without requiring networks to merge or integrate, in effect enabling a network-of-networks, as illustrated in the figure below using samples of DLT networks and cross-chain operations. 

Hyperledger Cacti提供了一种互操作性解决方案，它不需要将多条链合并成一条“统一链”来统治管理，也不需要创建一条新的结算链及共识协议让现有的网络订阅。相反，Cacti允许每条网络在根据需要进行跨链交易时保持决策自主权。实际上，Hyperledger Cacti将去中心化的信任延伸到了单个网络的范围之外，无需合并或集成网络，实际上启用了基于网络的网络，如下图所示的示例中使用了DLT网络和跨链操作。


