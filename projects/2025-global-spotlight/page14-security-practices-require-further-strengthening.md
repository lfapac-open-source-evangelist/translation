## Security practices require further strengthening
## 开源安全实践需要进一步增强

### Most OSS evaluation practices see limited adoption
### 大多数开源软件评估实践只得到有限度的采纳

Organizations demonstrate concerning gaps in their evaluation practices for open source components, with most security-focused assessments adopted by fewer than half of the surveyed organizations. Figure 10 reveals that checking community activity levels is the most common strategy. This emphasis on community health assessment directly connects to the enterprise support expectations: organizations that fail to evaluate project health may find themselves dependent on components with declining maintainer engagement and a lack of support.
在开源组件评估实践上，各类组织机构普遍存在令人担忧的缺口或差距：大多数聚焦安全的评估方法在受访组织机构中的采用率不足一半。图10显示，检查开源社区活跃度是最常见的评估策略。对开源社区健康的重视，与预期得到企业级技术支持直接相关：组织机构若未能评估开源项目的健康状况，可能陷入到依赖于维护者下滑、缺乏支持的开源组件的困境。

### 图10 使用开源组件前的评估实践落地占比
|   |   |   |   |
|---|---|---|---|
| 44%饼图 | 检查项目社区活跃度<br>比2024年 +1% | 36%饼图 | 检查项目仓库评分和下载次数<br>比2024年 +1% |
| 37%饼图 | 检查发版频率<br>比2024年 +0% | 31%饼图 | 使用自动化安全测试工具<br>比2024年 +2% |
| 36%饼图 | 评估直接依赖的开源组件<br>比2024年 +2% | 28%饼图 | 人工评审/检查源代码<br>比2024年 +2% |
|   |   |   | 来源：2025年全球开源软件调查，Q25调查问题"您的组织机构在引入新的开源组件时，通常会做哪些工作(多选)"<br>调查样本数=851，本表格只列出排第一的选项，完整数据见附录A10  |


The negligible increases across all evaluation practices from 2024 to 2025ranging from 0% to 2%—signal organizational inertia that directly undermines security posture. This limited adoption of security evaluation creates cascading risks: organizations deploying unvetted components may face supply chain attacks, discover critical vulnerabilities in production systems, or encounter compliance violations in regulated environments. The failure to evaluate direct dependencies, adopted by only 36% of organizations (Figure 10), compounds these risks by creating blind spots in the supply chain, which have driven recent high-profile security incidents across multiple industries.
从2024年到2025年，各类开源软件评估实践的提升微乎其微（提升率从0%至2%），这反映出组织机构的惯性，直接削弱了安全态势。对安全评估的有限采纳会引发连锁风险：在未经审查开源组件的情况下进行部署，可能导致供应链攻击、在生产系统中暴露严重漏洞，或在受监管环境中遭遇许可证违规。仅有36%的组织机构会评估其使用的直接开源依赖（见图10），这一缺失导致了供应链中的盲点，进一步加剧上述风险，并已引发近期跨多个行业的重大且备受关注的安全事件。

As observed in Figure 11, smaller organizations (1-249 employees) are particularly interested in community health, with 58% checking community activity levels, 47% looking at the frequency of releases, and 44% examining ratings or statistics as their top three evaluation practices. However, these community health-focused approaches drop significantly in ranking among larger organizations (10,000+ employees), where checking community activity levels falls from 1st to 6th place, frequency of releases drops from 2nd to 5th place, and ratings or statistics plummet from 3rd to 9th place. Instead, larger enterprises prioritize automated tools (47%), direct dependency evaluation (43%), and internal policy compliance (34%) as their top three practices.
如图11所示，小型组织（1-249名员工）对开源社区健康尤为关注：58%会检查社区活跃度，47%关注发版频率，44%查看评分或统计数据——这是其前三大评估实践。然而，在大型组织（10,000名以上员工）中，这些以社区健康为中心的方法排名显著下滑：检查社区活跃度从第1降至第6，发版频率从第2降至第5，评分或统计从第3骤降至第9。相应地，大型企业将自动化工具（47%）、直接依赖评估（43%）以及内部政策合规（34%）列为前三大实践。
### 图11 不同员工规模的组织机构安全实践排序
| 1-249员工 | 250-999员工 | 1000以上员工 |
|---|---|---|
| 58% 检查项目社区活跃度 | 37% 检查项目社区活跃度 | 47% 使用自动化工具 |
| 47% 检查发版频率 | 35% 检查项目评分和统计数据 | 43% 评估直接依赖组件 |
| 44% 检查项目评分和统计数据 | 35% 使用自动化工具 | 36% 检查项目社区活跃度度 |
| 36% 评估直接依赖组件 | 33% 评估直接依赖组件 | 34% 检查内部开源策略 |
| 33% 人工评审代码 | 31% 检查发版频率 | 32% 检查发版频率 |
| 24% 检查内部开源策略 | 28% 人工评审代码 | 31% 评估传递性依赖 |
| 22% 检查信息披露策略 | 26% 评估传递性依赖 | 27% 检查信息披露策略 |
| 20% 评估传递性依赖 | 19% 检查内部开源策略 | 27% 检查项目评分和统计数据 |
| 16% 使用自动化工具 | 15% 检查信息披露策略 | 22% 人工评审代码 |
| 来源：2025年全球开源软件调查，以Q11答案分类统计Q25调查问题<br>调查样本数=840，Q11有填写员工规模的才纳入统计 |   |   |

Small companies use automated security testing tools far less often than large companies (roughly 16% adoption for small firms vs. 47% for large firms). These findings indicate that smaller organizations rely on community health indicators that require minimal infrastructure investment, while larger enterprises prioritize systematic security assessment methods that demand dedicated tooling and specialized expertise. The disparity suggests that smaller organizations over-rely on community-driven support, while larger enterprises may consider community response timelines incompatible with their operational requirements and customer commitments.
小型公司使用自动化安全测试工具的频率远低于大型公司（小型公司采用率约16%，大型公司为47%）。这一发现表明，小型组织更依赖几乎不需额外基础设施投入的开源社区健康指标，而大型企业则优先采用需要专用工具与专业能力的系统化安全评估方法。该差异也意味着，小型组织对社区驱动的支持存在过度依赖；而大型企业则可能认为社区的响应时效与其运营需求和客户承诺并不匹配。

The gap between widespread open source adoption and limited evaluation practices creates a fundamental mismatch between organizational risk exposure and risk management capabilities. While organizations have embraced open source as core infrastructure, they have not correspondingly invested in the assessment frameworks necessary to ensure secure and sustainable implementation. This gap becomes particularly problematic given the mission-critical nature of many open source deployments, where inadequate evaluation can lead to downstream security incidents, compliance violations, or unexpected maintenance burdens that compromise system reliability.
开源软件的广泛采用与评估实践的有限度实施之间的差距，造成了组织机构的风险暴露与风险管理能力之间的根本性错配。尽管各类组织机构已将开源软件纳入核心基础设施，但并未相应地投资到必需的评估框架与方法体系以确保安全和可持续实施。考虑到许多开源软件被部署到关键任务场景，这一差距变得尤为严峻：评估不足可能引发后续的安全事故、许可证违规，或意外的维护负担，进而损害系统可靠性。


### Fragmentation in security evaluation criteria
### 安全评估标准的碎片化

Organizations understand that security assurances matter, but no single security assurance drives OSS trust. Figure 12 reveals a lack of consensus for open source trust, with no certification or assurance mechanism achieving adoption by more than a quarter of the organizations and with slight variation among the options (18%-25%). ISO27001 coverage and NIST compliance (such as 800-53, CSF) tie at the top with 25% each, followed closely by SBOM availability and third-party audits at 22%. Notably, 28% of respondents indicated “Don’t know or not sure,” the highest response rate, further evidencing the uncertainty and lack of standardization in OSS security assurance practices.
组织机构能理解多种开源软件安全机制的重要性，但只凭单一的安全机制无法推动对开源软件的信任。图12显示，组织机构在开源信任上缺乏共识：没有任何安全认证或保证机制的采用率超过四分之一，各个可选机制之间的采用率差异也很小（18%—25%）。ISO27001安全标准覆盖与NIST安全合规（如800-53、CSF）以25%并列第一；软件物料清单SBOM可用性和第三方审计紧随其后，为22%。值得注意的是，28%的受访者表示“不了解或不确定”，占比最高，进一步印证了开源软件安全机制实践中的不确定性与标准化不足。
### 图12 在开源安全保障上没有清晰的共识来实现开源信任
|   |   |
|---|---|
| ISO27001安全标准覆盖度 | 25%条形图 |
| NIST安全合规(例如 800-53, CSF) | 25%条形图 |
| SBOM可用性 | 22%条形图 |
| 第三方审计 | 22%条形图 |
| OpenSSF开源安全最佳实践勋章 | 20%条形图 |
| Common Criteria，CC 通用准则认证 | 20%条形图 |
| CIS Hardening安全加固 | 19%条形图 |
| FIPS联邦信息处理标准 | 18%条形图 |
| SOC 2安全合规 | 18%条形图 |
| 其他 | 3%条形图 |
| 不知道或不清楚 | 28%条形图 |
|  | 来源：2025年全球开源软件调查，Q26调查问题"哪些开源认证或安全机制，会让您采用或信任特定开源方案(多选)"<br>调查样本数=851，回复的选项总数=1865 |


Regional variations compound this fragmentation challenge, as shown in Figure 13. North America favors NIST compliance, SBOM availability and third-party audits at 28%, 24% and 23% respectively. Europe exhibits an opposite pattern with NIST compliance as the fourth most preferred certificate, whereas ISO coverage leads as the top at 29%. The Asia-Pacific region presents a third different profile, with Common Criteria certification leading at 45%—more than doubling the preference shown in other regions—followed by the OpenSSF Best Practices Badge at 30%.
地区差异进一步加剧了安全评估标准碎片化的挑战，如图13所示。北美更偏好 NIST 合规、SBOM 可用性和第三方审计，分别为28%、24%和23%。欧洲则呈现相反的情况：NIST 合规仅列第四，而 ISO 覆盖以29%位居首位。亚太地区呈现第三种不同情况，其中通用准则认证（Common Criteria，CC）以45%领跑——超过其他地区该偏好比例的两倍——其次是 OpenSSF 开源安全最佳实践徽章，为30%。
### 图13 无法全球对齐的开源安全认证偏好
| 北美 | 欧洲 | 亚太 |
|---|---|---|
| 28% NIST安全合规(例如 800-53, CSF) | 29% ISO27001安全标准覆盖度 | 45% Common Criteria，CC 通用准则认证 |
| 24% SBOM可用性 | 26% 第三方审计 | 30% OpenSSF开源安全最佳实践勋章 |
| 23% 第三方审计 | 23% SBOM可用性 | 28% NIST安全合规(例如 800-53, CSF) |
| 21% FIPS联邦信息处理标准 | 21% NIST安全合规(例如 800-53, CSF) | 26% ISO27001安全标准覆盖度 |
| 20% CIS Hardening安全加固 | 17% CIS Hardening安全加固 | 26% SBOM可用性 |
| 20% SOC 2安全合规 | 17% OpenSSF开源安全最佳实践勋章 | 21% CIS Hardening安全加固  |
| 19% OpenSSF开源安全最佳实践勋章 | 16% SOC 2安全合规 | 21% FIPS联邦信息处理标准 |
| 18% ISO27001安全标准覆盖度 | 15% FIPS联邦信息处理标准 | 20% SOC 2安全合规 |
| 13% Common Criteria，CC 通用准则认证 | 13% Common Criteria，CC 通用准则认证 | 9% 第三方审计 |
| 来源：2025年全球开源软件调查，以Q6答案分类统计Q26调查问题<br>调查样本数=851，某些区域因样本数少而不纳入统计 |   |   |


The absence of a dominant security standard creates operational challenges for both open source projects and consuming organizations. Projects need to pursue multiple, potentially conflicting, certification pathways to satisfy diverse organizational requirements, while enterprises must develop internal expertise across numerous security frameworks rather than focusing on a single, widely accepted standard. The implications extend to fundamental questions about open source security maturity. Without convergence toward common security evaluation criteria, the ecosystem risks perpetuating the security assessment gaps identified in previous sections, where organizations continue to rely on inconsistent evaluation practices rather than standardized security validation processes.
缺乏主导性的安全标准，给开源项目和使用开源项目的组织机构都带来了运营挑战。开源项目不得不追求多条、且可能相互冲突的认证路径，以满足多样性的组织机构要求；与此同时，企业也必须在众多安全框架上构建内部专业能力，而不是聚焦于一个被广泛接受的单一标准。这个问题延伸到了对开源安全成熟度的根本性探讨。如果无法向共同的安全评估准则收敛，整个开源生态就有持久化前文所述安全评估缺口和差距的风险——企业机构将继续依赖不一致的评估实践，而非标准化的安全验证流程。

The security evaluation challenges identified in this study align closely with findings from our EU Cyber Resilience Act (CRA) readiness research, which showed that 46% of manufacturers passively rely on upstream OSS projects for security fixes[7]. The CRA readiness research shows that those implementing automated tools, conducting security assessments, and maintaining SBOMs are better positioned for regulatory compliance. The regulatory pressure from the CRA, which takes full effect in December 2027, provides additional urgency for addressing the security evaluation gaps identified here and move beyond the current fragmented approach to security evaluation and adopt more comprehensive, standardized frameworks for assessing and managing open source security risks.
本研究报告发现的安全评估挑战，与我们对欧盟《网络韧性法案》（CRA）准备度的研究结果高度一致；后者显示，46%的制造商是被动地依赖上游开源软件项目提供安全修复[7](@ref)。该准备度研究还表明：正在实施自动化工具、开展安全评估、并维护软件物料清单（SBOM）的组织机构，在法规合规方面处于更有利位置。随着CRA将于2027年12月全面生效，将带来额外的监管压力，行业亟需弥补本报告指出的安全评估缺口和差距，跨越当前碎片化的评估方式，转而采用更全面、标准化的框架来评估和管理开源安全风险。

The CRA regulation presents an opportunity to improve how organizations engage with open source software, as the regulation requires manufacturers to take active responsibility for the security of their open source dependencies, meaning they can no longer remain passive consumers of communitydeveloped software. The CRA awareness and readiness study shows that organizations actively engaging with OSS projects are twice as likely to assess security practices compared to passive users, demonstrating that engagement drives better security outcomes. The regulation encourages manufacturers to contribute security fixes upstream and provide financial support to open source projects. This creates a legal pathway for organizations to invest in the sustainability and security of their critical dependencies.
《网络韧性法案》（CRA）为改进组织机构与开源软件的互动方式提供了契机。该法规要求制造商对其依赖的开源软件的安全性承担主动的责任，这意味着他们不能继续做开源社区所开发软件的被动使用者。CRA法案认知与准备度的研究显示，与被动一方相比，积极参与开源项目的组织机构，在实践开源安全评估的可能性高出两倍，这表明开源项目参与度可带来更佳的安全成效。CRA法案还鼓励制造商向上游开源项目贡献安全修复，并提供资金支持，这为企业机构投资在其依赖的关键开源软件的可持续性与安全性，开辟了法律路径。

### Organizations view open source participation as a strategic investment that accelerates their market positioning.
### 组织机构把参与开源项目视为提升其行业地位的战略投资。

[7](@ref): Adrienn Lawson, Stephen Hendrick, “Unaware and Uncertain: The Stark Realities of Cyber Resilience Act Readiness in Open Source,” foreword by Christopher (CRob) Robinson, The Linux Foundation, March 2025. https://www.linuxfoundation.org/research/cra-readiness