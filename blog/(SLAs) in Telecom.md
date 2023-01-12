# 解决方案简介：电信内部的服务级别协议(SLA)的自我评估

作者：Nikos Kapsoulis，Gordon Graham | 2023年1月4日 | 博客，Hyperledger Fabric，研究，特定兴趣小组，电信

![image](https://user-images.githubusercontent.com/89500827/211971961-da32e5cd-ad6a-4e31-a3ea-891fdfbd0033.png)


[电信特别兴趣小组](https://wiki.hyperledger.org/display/TCSIG)与Linux基金会的[LF Networking](https://www.lfnetworking.org/) 合作，刚刚[发布](https://www.hyperledger.org/learn/research)了一份关于电信服务级别协议(Service Level Agreement, SLA)自我评估的解决方案的简介。

SLA定义了供应商向客户提供的服务标准以及衡量这些服务的指标。如果客户收到的实际服务不符合供应商承诺的SLA承诺，则视为违反了协议。在这种情况下，供应商可能需要向客户支付退款或支付SLA中定义的罚款数目。

![image](https://user-images.githubusercontent.com/89500827/211970890-1cc82543-a077-4dbb-9b9a-a264bf8931e3.png)


该电信解决方案包括对自评估SLA解决方案的高度概括。该解决方案使用Hyperledger Fabric区块链技术来解决传统SLA评估过程中的灰色区域。

这种独特的体系架构提供了一个可信的、隐私保护的网络，可以精确地监控和计算SLA指标，对供应商和客户都完全透明。

通过建立信任、消除摩擦、简化流程并节省成本，实现有效的SLA自我评估，将使生态系统中的每个人都受益。

## 问题所在：缺乏透明度

有效的SLA明确定义了所有性能指标和参数。

But in most conventional SLAs, the provider assesses their own performance using their own tools and frameworks. The client generally has no way to see how these metrics are monitored or calculated. This increases the risk of biased results that favor the provider. 

但在大多数传统的SLA中，供应商使用自己的工具和框架来评估提供的服务的性能。客户通常无法查看这些指标是如何监控或计算的。这种方式的测评结果明显有利于服务提供商。

This lack of transparency means the client could well suffer from misunderstandings, missed violations, and insufficient refunds. All this undermines trust between the provider and the client. 

这种缺乏透明度的测评方式，意味着客户很可能会误解服务标准、感知不到供应商的违规行为，或是最终退款不足。所有这些潜在的行为，都破坏了供应商和客户之间的信任关系。

## 解决方案：使用区块链进行透明的自我评估

这个解决方案提出了一种基于Hyperledger Fabric区块链框架和Hyperledger Fabric私有智能合约(FPC)的新型架构。如下图所示，安装的可信执行环境(TEE)提供了安全和私密的监控，并计算了SLA管理的所有性能指标。

客户和服务供应商都可以从这个解决方案中受益，建立了双方的信任关系，这在以前是不存在的。更多详细信息请查看完整的白皮书中。

![image](https://user-images.githubusercontent.com/89500827/211970956-82708323-f789-46f4-ba6a-a968cd3c5666.png)


对SLA自我评估的工作及应用在电信环境的科学研究，是基于[Pledger项目](http://pledger-project.eu/)实现完成的。

完整的解决方案详见[这里](https://www.hyperledger.org/wp-content/uploads/2023/01/HL_SolutionsBrief_SLAs_120922.pdf)。

## 如何加入

想要了解有关Hyperledger电信特别兴趣小组的更多信息，请查看[该小组的wiki](https://wiki.hyperledger.org/display/TCSIG/)和[邮件列表](https://lists.hyperledger.org/g/telecom-sig) 。如果您有任何问题、意见或建议，请随时在列表中留言。欢迎加入该小组[即将举行的电话会议](https://lists.hyperledger.org/g/telecom-sig/calendar)，与小组成员会面并了解如何参与。[在太平洋时间2月9号上午9点，作者将在电信特别兴趣小组电话会议上展示这篇论文](https://wiki.hyperledger.org/display/TCSIG/2023+February+Event+About+Self+Assessing+SLAs)。欢迎大家加入。

## 致谢

Hyperledger电信特别兴趣小组感谢以下为本解决方案做出贡献的相关人士：Nima Afraz、David Boswell、Gordon Graham、Nikolaos Kapsoulis、Antonios Litke、Alexandros Psychas、Vipin Rathi和Theodora Varvarigou。
