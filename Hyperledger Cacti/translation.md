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

