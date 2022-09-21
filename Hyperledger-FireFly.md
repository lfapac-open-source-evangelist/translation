# Hyperledger FireFly V1.1 现已推出
作者：Nicko Guyer，Kaleido 高级全栈工程师和 Hyperledger FireFly 社区负责人 | 2022年9月12日 | Hyperledger Firefly 博客

(图)
|  英文   | 中文  |
|  ----  | ----  |
| and more  | 和其他 |

在[Hyperledger FireFly](https://www.hyperledger.org/use/firefly)出现之前，区块链开发人员花费了大量时间来构建应用程序的工具箱。他们从无到有开发复杂的中间件组件。Hyperledger FireFly为此带来了翻天覆地的变化。作为第一个开源的超级节点，Hyperledger FireFly为开发人员提供了一个完整的堆栈来构建和扩展安全的Web3应用程序。

(图)
|  英文   | 中文  |
|  ----  | ----  |
| Without Hyperledger FireFly | 不使用 Hyperledger FireFly |
| Your Build and Update | 您的构建和更新 |
| Business Application | 商业应用 |
| Tokens | 代币 |
| Onboarding | 引导流程 |
| Events | 事件 |
| Identity | 身份 |
| Messaging | 信息收发 |
| Privacy | 隐私 |
| Doc Mgmt | 文档管理 |
| Data Mgmt | 数据管理 |
| Data Orchestration | 数据编排 |
| Blockchain Node | 区块链节点 |
| Web3 Connections | Web3 连接 |
| Tokens | 代币 |
| Onboarding | 引导流程 |
| With Hyperledger FireFly  | 使用 Hyperledger FireFly |
| Your Build | 您的构建 |
| Business Application | 商业应用 |
| Community Build & Update | 社区构建和更新 |
| SuperNode | 超级节点 |
| Web3 Connections | Web3 连接 |
| Tokens | 代币 |
| Onboarding | 引导流程 |

Hyperledger FireFly通过丰富的原生Web3、B2B和集成服务堆栈加速开发。它通过单个控制台简化了许多应用程序的部署和管理，并提供了一个可以连接到多种链和多种Web3协议世界的新工具。

这比以往任何时候都更加重要，因为公有链和私有链应用在新兴企业的应用程序中越来越多地混合在一起。这就是新版 Hyperledger FireFly 令人兴奋的原因所在。基于堆栈的开发让开发人员发布生产就绪的应用程序变得很简单，支持公有链和私有链，并可从具有多用户支持、插件灵活性和可插拔安全性的单个控制台管理多个应用程序。

## Web3 网关模式介绍
Hyperledger FireFly现在可以在两种模式下运行。第一种是当前堆栈用户所熟悉的。联盟模式用于建立联盟或多方业务网络，在该模式下数据需要在联盟之间达成共识，并实现共享。联盟模式的应用案例包括医疗保健和保险联盟、供应链、金融网络，以及多方参与的协调系统以简化其业务方式的其他案例。

此次版本引入了新的Web3网关模式。当超级节点的主要目标是连接到公有区块链时，则使用网关模式。以前的开发人员需要使用公共系链以访问流行的公有链，现在的新网关模式充当了进入Web3完整世界的门户，支持流行的公有链，包括Ethereum、Polygon、Avalanche、Optimism、BNB Chain、Arbitrum、Moonbeam、Fantom以及其他公有链。

公有链和私有区块链的世界正在融合。企业渴望利用公有链的广泛的覆盖范围、安全性和去中心化。与此同时，公有链开发者正在寻求以企业网络早已熟悉的方式优化吞吐量、可扩展性和 gas 费用。本版本的Hyperledger FireFly提供了一个可以构建这两个世界的堆栈架构。

(图)
|  英文   | 中文  |
|  ----  | ----  |
| Security | 安全性 |
| Application | 应用 |
| API Security  | API 安全性 |
| E2E Encryption | 端到端加密 |
| Identity | 身份 |
| SSO | 单点登录 |
| Key Mgmt | 密匙管理 |
| Address Book | 通讯簿 |
| Apps | 应用程序 |
| API Gateway | API 网关 |
| Event Stream API | 事件流 API |
| API Generator | API 生成器 |
| Flows | 流量 |
| Privacy | 隐私 |
| Multi-Party | 多方 |
| Data Exchange | 数据交换 |
| Digital Assets | 数字资产 |
| Token API | 代币 API |
| Transfers | 资产转让 |
| Wallets | 钱包 |
| FireFly Core | FireFly 内核 |
| Data | 数据 |
| Private | 隐私的 |
| Shared | 共享的 |
| Public | 公开的 |
| Orchestration Engine | 编排引擎 |
| Event Bus | 事件总线 |
| State | 状态 |
| Network | 网络 |
| Chain | 链 |
| Internal | 内部的 |
| Tools | 工具 |
| Explorer | 浏览器 |
| Developer | 开发工具 |
| SDK | SDK |
| CLI | 命令行 |
| API | API |
| DevOps | 开发运维 |
| Kubernetes | Kubernetes |
| Prometheus | Prometheus |
| Shared Storage | 共享存储 |
| Private Data Bus | 隐私数据总线 |
| Blockchain | 区块链 |

## 公有区块链支持
除了跨公有链连接的能力外，Hyperledger FireFly 1.1还提供了新的工具和支持来简化企业的公共用例。

- FireFly事务管理器是一个全新的EVM连接器，可处理公有链的复杂问题，包括 gas 估算、重新提交策略等。 
- FireFly Signer可用于需要将私钥与区块链节点分开的网络中的交易签名。
- 增强的网关支持与公有链进行交互的同时，轻松地保护私有数据的私密性。

Hyperleger FireFly 1.1允许开发人员同时访问公有链和私有链，并构建企业空间的特定防护，以确保新应用程序满足用户和合规性要求。

## 多用户支持
Hyperledger FireFly 1.1增加了用于隔离数据和操作的命名空间隔离。在超级节点内部，每个命名空间都是FireFly运行时中的一个隔离环境。这允许独立配置各种插件和基础设施组件，以及API安全性、身份广播、链上数据索引等，并支持数据共享方式的管理。

命名空间在这两种模式下都有效。当多方需要共享链上和链下数据并就该数据的排序和真实性达成一致时，可以使用联盟命名空间。Web3网关命名空间在直接与区块链交互时可用，且无需假设交互需要符合FireFly的多方系统模型。

单个FireFly节点在任一模式下都可以同时运行多个命名空间。这使开发人员可以构建协调公有链和私有链的流程。下图说明了组织从单个控制台运行多个应用程序时可用的可见性和控制能力，其中每个应用程序都会被隔离以满足安全要求。

(图)
|  英文   | 中文  |
|  ----  | ----  |
| Your Organization | 您的组织 |
| Your FireFly SuperNode | 您的 FireFly 超级节点 |
| namespace: alpha | 命名空间：alpha |
| mode: multiparty | 模式：多方 |
| namespace: beta | 命名空间：beta |
| mode: multiparty | 模式：多方 |
| namespace: omega | 命名空间：omega |
| mode: gateway | 模式：网关 |
| namespace: iota | 命名空间：iota |
| mode: gateway | 模式：网关 |
| Multi-Party System 1 | 多方系统 1 |
| Multi-Party System 2 | 多方系统 2 |
| Public Chain 1 | 公有链 1 |
| Public Chain 2 | 公有链 2 |
| Hyperledger FireFly Namespaces & Modes Example | Hyperledger FireFly 命名空间和模式示例 |

## 插件的多个实例
在新版本中，单个FireFly节点现在可以使用每种可用插件类型的多个实例。如上所示，通常我们会根据不同的用例或目标同时连接到多个区块链。在每个命名空间中运行不同插件的能力意味着开发人员可以更灵活地协调每个链或联盟的流程。

## 可插拔 API 安全性
在企业环境中，无论是为了网络的完整性还是为了合规性标准，只有在能够与适当的安全性相匹配时，连接到多个应用程序和多个链的灵活性才有价值。

使用Hyperledger FireFly 1.1，可以在多个级别启用API安全性，包括在任何服务中或任一特定命名空间内。通过两种不同的操作模式、租户隔离、插件的灵活性和任何级别的定制安全性，开发人员部署和管理具有恰当功能和许可访问的应用程序的能力大大提高。

## 下一代平台
Hyperledger FireFly v1.0 是区块链开发者工具集中受欢迎的新成员。它为区块链带来了 Web 2.0 空间中常见的丰富中间件堆栈的便利。

随着新版本的发布，Hyperledger FireFly 将引导企业利用公有和私有区块链技术的优势。它使开发人员能够快速启动多个应用程序，根据所需的业务逻辑和安全要求定制每个应用程序，同时提供通往更广阔的 web3 世界的网关。

Hyperledger FireFly 1.1让企业离实现Web3的全部潜力又进了一步——通过许可链和与公共生态系统的连接。如果您对此感兴趣，我们会邀请您加入我们的社区。您可以在 [FireFly 文档](https://hyperledger.github.io/firefly/)中了解更多信息，并在Github上[FireFly](https://github.com/hyperledger/firefly)中下载CLI。如果您有任何问题，请在[Hyperledger Discord](https://discord.com/channels/905194001349627914/928377875827154984)的FireFly频道中找到我们。
