## Solution Brief: Self-Assessing Service Level Agreements (SLAs) in Telecom
## 解决方案简介：电信内部的服务级别协议(SLA)的自我评估

By Nikos Kapsoulis and Gordon Graham | January 4, 2023 | Blog, Hyperledger Fabric, Research, Special Interest Group, Telecom

作者：Nikos Kapsoulis和Gordon Graham | 2023年1月4日 | 博客，Hyperledger Fabric，研究，特定兴趣小组，电信

![image](https://user-images.githubusercontent.com/89500827/211971961-da32e5cd-ad6a-4e31-a3ea-891fdfbd0033.png)


The [Telecom Special Interest Group](https://wiki.hyperledger.org/display/TCSIG), in collaboration with the Linux Foundation’s [LF Edge](https://www.lfedge.org/) initiative, has just [published](https://www.hyperledger.org/learn/research) a solution brief on the self-assessment of Service Level Agreements (SLAs) in telecom. 

[电信特别兴趣小组](https://wiki.hyperledger.org/display/TCSIG)与Linux基金会的[LF Edge](https://www.lfedge.org/) initiative项目合作，刚刚[发布](https://www.hyperledger.org/learn/research)了一份关于电信服务级别协议(SLA)自我评估的解决方案的简介。

An SLA defines the services delivered by a provider to a client and the metrics for measuring those services. If the actual services received by the client do not meet the SLA guarantees promised by the provider, the agreement has been violated. In that case, the provider may owe the client a refund or whatever penalty is defined in the SLA. 

SLA定义了供应商向客户提供的服务标准以及衡量这些服务的指标。如果客户收到的实际服务不符合供应商承诺的SLA承诺，则视为违反了协议。在这种情况下，供应商可能需要向客户支付退款或支付SLA中定义的罚款数目。

![image](https://user-images.githubusercontent.com/89500827/211970890-1cc82543-a077-4dbb-9b9a-a264bf8931e3.png)


The solution brief includes a high-level overview of a proposed solution for self-assessing SLAs. This proposed solution uses Hyperledger Fabric blockchain technology to tackle the gray areas of conventional SLA assessment. 

本篇电信解决方案的简介包括对自评估SLA解决方案的高度概括。该解决方案使用Hyperledger Fabric区块链技术来解决传统SLA评估过程中的灰色区域。

This unique architecture provides a trusted and privacy-preserving network that can precisely monitor and compute SLA metrics, with full transparency for both provider and client. 

这种独特的体系架构提供了一个可信的、隐私保护的网络，可以精确地监控和计算SLA指标，对供应商和客户都完全透明。

Achieving effective SLA self-assessments will benefit everyone in the ecosystem by building trust, removing friction, streamlining processes, and saving costs. 

通过建立信任、消除摩擦、简化流程并节省成本，实现有效的SLA自我评估，将使生态系统中的每个人都受益。

#### The Problem: Lack of transparency
#### 问题所在：缺乏透明度

An effective SLA clearly defines all performance metrics and parameters. 

有效的SLA明确定义了所有性能指标和参数。

But in most conventional SLAs, the provider assesses their own performance using their own tools and frameworks. The client generally has no way to see how these metrics are monitored or calculated. This increases the risk of biased results that favor the provider. 

但在大多数传统的SLA中，供应商使用自己的工具和框架来评估提供的服务的性能。客户通常无法查看这些指标是如何监控或计算的。这种方式的测评结果明显有利于服务提供商。

This lack of transparency means the client could well suffer from misunderstandings, missed violations, and insufficient refunds. All this undermines trust between the provider and the client. 

这种缺乏透明度的测评方式，意味着客户很可能会误解服务标准、感知不到供应商的违规行为，或是最终退款不足。所有这些潜在的行为，都破坏了供应商和客户之间的信任关系。

#### The Solution: Using blockchain for transparent self-assessment
#### 解决方案：使用区块链进行透明的自我评估

This solution brief proposes a novel architecture that is based on the Hyperledger Fabric blockchain framework and Hyperledger Fabric Private Chaincode (FPC). As shown in the figure below, the installed Trusted Execution Environment (TEE) provides secure and private monitoring, and computation of all performance metrics governed by the SLA.

这个解决方案提出了一种基于Hyperledger Fabric区块链框架和Hyperledger Fabric私有智能合约(FPC)的新型架构。如下图所示，安装的可信执行环境(TEE)提供了安全和私密的监控，并计算了SLA管理的所有性能指标。

Both client and provider benefit from the presented solution, which builds trust where little previously existed. More details are provided in the full white paper. 

客户和服务供应商都可以从这个解决方案中受益，建立了双方的信任关系，这在以前是不存在的。更多详细信息请查看完整的白皮书中。

![image](https://user-images.githubusercontent.com/89500827/211970956-82708323-f789-46f4-ba6a-a968cd3c5666.png)


The scientific research performed on SLA Self-Assessment and applied to the telecom context adheres to work accomplished under the [Pledger project](http://pledger-project.eu/).

对SLA自我评估的工作及应用在电信环境的科学研究，是基于[Pledger项目](http://pledger-project.eu/)实现完成的。

The full paper is available to download [here](https://www.hyperledger.org/wp-content/uploads/2023/01/HL_SolutionsBrief_SLAs_120922.pdf). 

完整的论文详见[这里](https://www.hyperledger.org/wp-content/uploads/2023/01/HL_SolutionsBrief_SLAs_120922.pdf)。

#### Get Involved with the Group
#### 如何加入

To learn more about the Hyperledger Telecom Special Interest Group, check out [the group’s wiki](https://wiki.hyperledger.org/display/TCSIG/) and [mailing list](https://lists.hyperledger.org/g/telecom-sig). If you have questions, comments or suggestions, feel free to post messages to the list.  And you’re welcome to join any of [the group’s upcoming calls](https://lists.hyperledger.org/g/telecom-sig/calendar) to meet group members and learn how to get involved. On [February 9 at 9:00 am PT, the authors will be presenting the paper during the Telecom Special Interest Group call](https://wiki.hyperledger.org/display/TCSIG/2023+February+Event+About+Self+Assessing+SLAs). All are welcome to join.

想要了解有关Hyperledger电信特别兴趣小组的更多信息，请查看[该小组的wiki](https://wiki.hyperledger.org/display/TCSIG/)和[邮件列表](https://lists.hyperledger.org/g/telecom-sig) 。如果您有任何问题、意见或建议，请随时在列表中留言。欢迎加入该小组[即将举行的电话会议](https://lists.hyperledger.org/g/telecom-sig/calendar)，与小组成员会面并了解如何参与。[在太平洋时间2月9号上午9点，作者将在电信特别兴趣小组电话会议上展示这篇论文](https://wiki.hyperledger.org/display/TCSIG/2023+February+Event+About+Self+Assessing+SLAs)。欢迎大家加入。

#### Acknowledgements
#### 感谢

The Hyperledger Telecom Special Interest Group would like to thank the following people who contributed to this solution brief: Nima Afraz, David Boswell, Gordon Graham, Nikolaos Kapsoulis, Antonios Litke, Alexandros Psychas, Vipin Rathi, and Theodora Varvarigou. 

Hyperledger电信特别兴趣小组感谢以下为本解决方案做出贡献的相关人士：Nima Afraz、David Boswell、Gordon Graham、Nikolaos Kapsoulis、Antonios Litke、Alexandros Psychas、Vipin Rathi和Theodora Varvarigou。
