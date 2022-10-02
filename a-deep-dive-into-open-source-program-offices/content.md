![](media/image1.jpeg)

**A Deep Dive Into**

**Open Source Program Offices**

**Structure, Roles, Responsibilities, and Challenges**

**August 2022**

Ibrahim Haddad, Ph.D.

Vice President of Strategic Programs, _Linux Foundation_

and General Manager, _LF AI & Data_

With a foreword by Chris Aniszczyk,

Chief Technology Officer, _Linux Foundation_

and Co Founder, _TODO Group_

**In partnership with:**

# Contents

[Foreword 3](#foreword)

[Abstract 5](#abstract)

[Introduction 6](#introduction)

[OSPO Definition 7](#_bookmark3)

[OSPO Characteristics 7](#_bookmark3)

[OSPO Maturity Model 8](#ospo-maturity-model)

[Stage 0: Ad-Hoc Approach 9](#stage-0-ad-hoc-approach)

[Stage 1: Legal-Driven Adoption 9](#stage-0-ad-hoc-approach)

[Stage 2: Community-Driven Adoption 9](#stage-0-ad-hoc-approach)

[Stage 3: Engagement-Driven Adoption
10](#stage-3-engagement-driven-adoption)

[Stage 4: Leadership-Driven Adoption
10](#stage-3-engagement-driven-adoption)

[OSPO Structure 11](#ospo-structure)

[Example 1: OSPO Within an R&D Department 11](#ospo-structure)

[Example 2: Corporate-Level OSPO With Supporting Division-Level OSPOs
12](#example-2-corporate-level-ospo-with-supporting-division-level-ospos)
[Example 3: OSPO as Part of the CTO Office or Engineering Department
12](#example-2-corporate-level-ospo-with-supporting-division-level-ospos)

[Example 4: Virtual OSPO 13](#example-4-virtual-ospo)

[Example 5: No Official OSPO 13](#example-4-virtual-ospo)

[Staffing an OSPO 14](#staffing-an-ospo)

[Head of OSPO 14](#staffing-an-ospo)

[Software Architect 14](#staffing-an-ospo)

[Technical Evangelist 14](#staffing-an-ospo)

[Compliance Engineer 14](#staffing-an-ospo)

[Legal Counsel 14](#staffing-an-ospo)

[OSPO Responsibilities 15](#ospo-responsibilities)

[Develop and Execute an Open Source Strategy 15](#ospo-responsibilities)

[Oversee Open Source Compliance 19](#oversee-open-source-compliance)

[Establish Open Source Policies and Processes 21](#_bookmark15)

[Prioritize and Drive Upstream Open Source Development 22](#_bookmark16)

[Engage with Open Source Organizations 22](#_bookmark16)

[Track Performance Metrics 22](#_bookmark16)

[OSPOs and Eliminating Friction
From](#ospos-and-eliminating-friction-from-using-or-contributing-to-oss)

[Using or Contributing to OSS
25](#ospos-and-eliminating-friction-from-using-or-contributing-to-oss)

[Culture
25](#ospos-and-eliminating-friction-from-using-or-contributing-to-oss)

[Processes 26](#processes)

[Continuity 26](#processes)

[Education 27](#_bookmark19)

[The TODO Group 28](#the-todo-group)

[Conclusion 28](#the-todo-group)

[Acknowledgments 29](#acknowledgments-feedback)

[Linux Foundation Resources 29](#acknowledgments-feedback)

[Feedback 29](#acknowledgments-feedback)

[About the Author 30](#about-the-author)

[Disclaimer 30](#about-the-author)

# Foreword

前言

If you\'re like most corporate leaders, you\'re likely to be familiar
with open source and may even already have an open source program in
place. But what exactly is an [O[pen Source Program Office
(OSPO)](https://github.com/todogroup/ospodefinition.org)]{.underline},
what roles and responsibilities does it have, and how can it
contribute to your organization\'s success?

如果您跟大多数企业领导一样，那么您可能已经对开源很熟悉，甚至可能已经有开源项目在运作中。但[开源项目办公室（OSPO）](https://github.com/todogroup/ospodefinition.org)究竟是什么，它有哪些角色和职责，以及它能为您组织的成功做出怎样的贡献呢？

An OSPO is a corporate entity that is responsible for managing and
coordinating an organization\'s open source activities. The OSPO can
be seen as the central nervous system for an organization\'s open
source strategy, and it provides governance, oversight, and support
for all things related to open source.

OSPO是公司内负责管理和协调组织开源活动的一个实体部门。OSPO可以被视为组织开源战略的中枢神经系统，它为所有与开源相关的事情提供治理、监督和支持。

At The Linux Foundation, we view OSPOs as critical components of
successful organizations. We\'ve seen firsthand how an effective OSPO
can help an organization achieve its business goals and objectives by
leveraging the power of open source. The
[[TODO]{.underline}](https://todogroup.org/) can help you set up an
OSPO or take your existing program to the next level.

在Linux基金会，我们将OSPO视为成功组织的关键组成部分。我们亲眼目睹了有效的OSPO如何通过利用开源的力量帮助组织实现其业务目标。[TODO工作组](https://todogroup.org/)可以帮助您创建一个OSPO或将您现有的项目提升到一个新的水平。

The TODO Group is a group of organizations that are committed to
building the best practices and tools for managing successful open
source programs. We are the leading voice on all things related to
open source program management, with a growing community of practice
that includes some of the world\'s largest organizations. We encourage
you as a practice leader, or someone who is thinking about setting up
an OSPO, to join us.

TODO工作组是致力于构建最佳实践和工具以管理成功开源项目的一群组织。我们是所有与开源项目管理相关事务的引领者，拥有不断增长的实践社区，其中包括一些世界上最大的组织。我们鼓励作为实践领导者的您或正在考虑建立OSPO的其他人加入我们。

This paper is an introduction to setting up an OSPO. It covers the
what, why, and how of open source program management, with a focus on
the role of an OSPO and the benefits. It also includes descriptions of
various structural models for OSPOs and provides tips and best prac-
tices for success. We hope that you find it helpful as you embark on
your open source journey.

本文是对建立OSPO的介绍，涵盖了开源项目管理的内容、原因和方式，重点介绍了OSPO的作用和益处。文中还包括了对OSPO各种结构模型的描述，并提供了取得成功的技巧和最佳实践。我们希望它为您踏上开源之旅带来帮助。

**Chris Aniszczyk**

Chris Aniszczyk 

_CTO, The Linux Foundation Co-Founder, The TODO Group_

CTO，Linux基金会联合创始人，TODO工作组

![](media/image5.png)![](media/image6.png){width="0.49392607174103237in"
height="9.17836832895888e-2in"}A DEEP DIVE INTO OPEN SOURCE PROGRAM
OFFICES: STRUCTURE, ROLES, RESPONSIBILITIES, AND CHALLENGES **3**

![](media/image7.png) ![](media/image8.png) ![](media/image11.png)

![](media/image12.png)![](media/image13.png)![](media/image18.png)![](media/image23.png)![](media/image24.png)![](media/image25.png)

![](media/image29.png){width="0.6569291338582677in"
height="0.229831583552056in"}Copyright © 2022 [[The Linux
Foundation]{.underline}](https://linuxfoundation.org/) \| August 2022

This report is licensed under the [[Creative Commons
Attribution-NoDerivatives 4.0 International Public
Licens](https://creativecommons.org/licenses/by-nd/4.0/)e]{.underline}

WHAT IS AN OSPO?
OSPO is designed to be the center of competency for an organization's open source operations and structure.

什么是OSPO？
OSPO旨在成为组织中开源运营和结构的能力中心。

WHY FORM AN OSPO?
Organizations across industries establish OSPOs to drive OSS leadership and gain a critical foothold in a robust, external R&D ecosystem.

为什么要成立OSPO？
跨行业的组织建立OSPO以推动OSS的领导地位，并在强大的外部研发生态系统中获得关键立足点。

CHARACTERISTICS OF OSPO MATURITY
Mature OSPOs oversee OSS consumption, governance, strategy, contribution, processes, and tooling.

OSPO成熟度的特征
成熟的OSPO负责监督OSS的使用、治理、战略、贡献、流程和工具。

OSPO MATURITY MODEL 
OSPO maturity evolves in the following stages: ad-hoc adoption -> legal motivations -> community-driven -> engagement-driven -> leadership-driven.

OSPO成熟度模型
OSPO成熟度分为以下阶段：临时采用 -> 法务驱动 -> 社区驱动 -> 参与驱动 -> 领导力驱动

OSPOS IN THE ORGANIZATION
OSPOs may exist unoﬃcially; virtually; within research and development (R&D), engineering, or other corporate departments; or in executive-level oﬃces of the Chief Technology Oﬃcer (CTO) or Chief Legal Oﬃcer.

组织中的OSPO
OSPO可能以非正式和虚拟的形式存在于研发（R&D）、工程或其他公司部门中；或者在首席技术官（CTO）或首席法律官的管理层办公室中。

OSPO STAFF
OSPOs can be run by any distinguished individuals with strong sets of skills, such as software architects, technical evangelists, compliance engineers, and legal counsel. 

OSPO工作人员
OSPO可以由任何具有强大技能的杰出人士运营，例如软件架构师、技术布道者、合规工程师和法律顾问。

OSPO RESPONSIBILITIES
The OSPO assumes diﬀerent responsibilities that change over time, including developing and executing the open source  ( OS ) strategy, setting priorities, tracking performance, and leading community engagement.

OSPO职责
OSPO会随着时间的推移承担不同的职责，包括开发和执行开源（OS）战略、设置优先级、跟踪表现和领导社区参与。

OSPO BENEFITS: CULTURE
OSPOs help to bridge the cultural gap between traditional software development practices and the requirements of open source development. 

OSPO的益处：文化
OSPO有助于跨越传统软件开发实践与开源开发要求之间的文化鸿沟。

OSPO BENEFITS: PROCESSES 
OSPOs oversee the establishment or adaptation of internal policies to better manage open source software (OSS) compliance in fast-moving, dynamic environments. 

OSPO的益处：流程 
OSPO监督内部政策的制定或调整，以在快速变化的动态环境中更好地管理开源软件 (OSS) 合规性。

OSPO BENEFITS: TOOLS
OSPOs help to implement unique and ﬂexible sets of tools that support OSS development models while meeting corporate Information Technology guidelines. 

OSPO的益处：工具
OSPO有助于实施独特而灵活的工具集，这些工具集支持OSS开发模型，同时可以满足企业信息技术准则。

OSPO BENEFITS: CONTINUITY
As organizational needs or strategies evolve, OSPOs enable continuity in executive support, funding, software development practices, and OSS project prioritization.

OSPO的益处：延续性
随着组织需求或战略的发展，OSPO能够实现行政支持、资金、软件开发实践和OSS项目优先级的延续性。

OSPO BENEFITS: EDUCATION
OSPOs improve technical, mentorship, and compliance-related education and training programming for team members across all levels of the organization.

OSPO的益处：教育
OSPO为组织内各级别的团队成员改进技术、指导和合规相关的教育和培训方案。

# Abstract

摘要

Open source projects and initiatives provide enterprises with proven,successful models to collaborate with other organizations, create new technologies, and support the development of new communities. Organizations across many industries are establishing [[Open]{.underline}](https://github.com/todogroup/ospodefinition.org) [[Source Program Offices]{.underline}](https://github.com/todogroup/ospodefinition.org)(OSPOs) and staffing them with highly skilled individuals to drive open source software(OSS) leadership and gaina critical foothold in this external research and development (R&D) ecosystem.

开源项目和方案为企业提供了经过验证的成功模型，以指导企业与其他组织协作、创建新技术和支持新社区的开发。许多行业的组织正在建立[开源项目办公室（OSPO）](https://github.com/todogroup/ospodefinition.org)，并为他们聘请高技能人士，以推动开源软件（OSS）的领导地位，并在这个外部研发（R&D）生态系统中获得关键的立足点。

This report examines how enterprises structure their OSPOs and the required minimal staffing needed for their operation, discusses the responsibilities of such offices, and elaborates on the challenges that are faced in open source enterprise adoption.

本报告探讨了企业如何构建他们的OSPO，以及运营所需的最低人员配置，讨论了此类办公室的职责，并详细阐述了开源企业采用所面临的挑战。

# Introduction

介绍

![](media/image30.png)The availability of open source software (OSS)
is changing how organi- zations develop and deliver products. The
combination of a transparent development community and access to
public source code enables orga- nizations to think differently about
how they procure, implement, test, deploy, and maintain software
(**FIGURE 1**). OSS has created an ecosystem with a wealth of benefits
for all those involved. Organizations of all types, across all
industries and domains, are racing to build and grow their open source
operations under an Open Source Program Office (OSPO) to help them use
and contribute to open source more efficiently and effectively and
benefit from its strategic impact (**FIGURE 2**).

开源软件（OSS）的可用性正在改变组织开发和交付产品的方式。透明的开发社区和对公开源代码的获取相结合，使组织能够以不同的方式思考他们如何采购、实施、测试、部署和维护软件（图1）。OSS创造了一个可为所有相关人员带来丰富利益的生态系统。所有行业和领域中各种类型的组织竞相在开源项目办公室（OSPO）下建立和发展他们的开源业务，以帮助他们更有效地使用开源并为之贡献，同时从其战略影响中受益（图2）。

OSS allows shared development and lowers research and development
(R&D) costs by enabling organizations to reap the benefit of billions
of dollars of OSS, which they can harness to create better products
and services. In addition, it helps to accelerate product development
and enables a faster time to market by aligning business needs with
upstream open source projects. Organizations do not get involved in
open source projects because it is fun; they do it because it is a
part of their business or product strategy. OSPOs often manage and
orches- trate that involvement.

OSS允许共享开发，并能让组织从OSS中获益数十亿美元，从而降低研发 (R&D) 成本。组织可以利用这些收益来创造更好的产品和服务。此外，通过将业务需求与上游开源项目保持一致，它有助于加速产品开发并缩短产品上市时间。组织参与开源项目不是因为它有趣，他们这样做是因为这是他们业务或产品战略的一部分。OSPO经常管理和协调这种参与工作。

The first step in establishing an OSPO is understanding that open
source is key to mastering software engineering, as almost every
software product that exists today relies on OSS. Leading organiza-
tions in a growing number of industries have established their
position by becoming leaders in software development, and OSS is a
critical component of this leadership. The second step is the
availability of an executive sponsor within the organization who will support the 
![](media/image34.png)[]{#\_bookmark3 .anchor}establishment of an OSPO,
provide funding for it, and offer a long-term commitment to improving
and growing open source engineering in the organization. This person also plays a critical role in
identifying a trusted open source leader who can create and develop
the OSPO.

建立OSPO的第一步是理解开源是掌握软件工程的关键，因为当今存在的几乎所有软件产品都依赖于OSS。越来越多的行业领先组织通过成为软件开发的领导者确立了自己的地位，而OSS是这种领导地位的关键组成部分。第二步是组织管理层中存在一位发起人，他将支持OSPO的建立、为其提供资金，并长期致力于改进和发展组织中的开源工程。此人对识别值得信赖的、能创建和发展OSPO的开源领导者也发挥着关键作用。

FIGURE 1 Open source is a technology market accelerant

1 Neutral environment for collaboration & cross-pollination 

2 Innovation multiplier – community driven 

3 Minimizes fragmentation and supports the upstream development model 

4 Enables better interoperability 

5 Facilitates standardization on open technologies 

6 Qualiﬁes reference architectures 

7 Lowers barriers to enter a new domain 

8 Enables business opportunities supported by flexible licensing model

9 Leads to better products, improved quality and security

10 Allows fast trailing twelve months and shared cost of development 

图1 开源是技术市场的助推器

1 协作和相互交流的中立环境
2 创新倍增器——社区驱动
3 最大限度减少碎片化，支持上游开发模式
4 实现更好的互操作性
5 促进开放技术的标准化
6 限定参考架构
7 降低进入新领域的门槛
8 实现受灵活许可模式支持的商机
9 带来更好的产品、更高的质量和安全性
10 允许快速跟踪12个月并分摊开发成本

FIGURE 2 Strategic impact of OSS

- Accelerate the development of open solutions 
- Provide an implementation to an open standard

- Drive demand by building an ecosystem for products & services

- Commoditize a market 
- Reduce prices of nonstrategic software assets 
- Share development costs

- Partner with others 
- Engage customers
- Strengthen relationships with common goals

图2 OSS的战略影响

- 加快开发开放式解决方案
- 提供开放标准的实施方案

- 通过建立产品和服务的生态系统来拉动需求

- 形成商品化的市场
- 降低非战略性软件资产的价格
- 分摊开发成本

- 与他人合作
- 吸引客户
- 加强与共同目标的关系

# OSPO Definition 
# OSPO的定义

An OSPO is designed to do the following: (1) be the center of compe-tency for an organization\'s open source operations and structure and (2) place a strategy and set of policies on top of an organization\'s open source efforts. This can include setting code use, distribution, selection, auditing, and other policies; training developers; ensuring legal compliance; and promoting and building community engagement to benefit the organization strategically. See the [OSPO definition](https://github.com/todogroup/ospodefinition.org) by the TODO for more information.

设立OSPO的目的包括：（1）成为组织中开源运作和架构的能力中心，以及（2）基于组织的开源活动制定一套战略和政策。其中可能包括设置开源代码的使用、分发、选择、审计等策略；培训开发者；确保法务合规性；促进和逐步增强社区参与，使组织在战略上受益。如果你想要了解更多信息，请参考TODO的[OSPO定义](https://github.com/todogroup/ospodefinition.org)。

# OSPO Characteristics
# OSPO的特征
To a certain degree, an organization calling itself an OSPO indicates that the organization has reached a mature stage, gained critical mass support with its enterprise, and manifests the following five key characteristics:

1.  Employees are tasked with fostering and nurturing OSS usage.

2.  The organization has a formal policy regarding the use and production of OSS.

3.  Executives recognize that OSS and open source are important strategic assets.

4.  Significant numbers of employees are contributing code to open source projects.

5.  Processes, procedures, and tools are in place to streamline and facilitate open source consumption and participation.

在一定程度上，如果组织中有被称为OSPO的部门，则表明开源在该组织中已达到相对成熟的阶段，且已在企业内获得绝大多数支持，同时组织表现出以下五个关键特征：
1. 员工负责促进开源软件的使用。
2. 组织正式发布了关于使用和生产开源软件的策略。
3. 管理层意识到开源软件和开源是重要的战略资产。
4. 大量的员工在为开源项目贡献代码。
5. 用来简化组织使用和参与开源的流程、步骤和工具已就绪。

# OSPO Maturity Model
# OSPO成熟度模型
To better explain the evolution of OSPOs, the TODO Group has developed a model (**FIGURE 3**) to assist organizations in determining their OSPO and identifying the elements that need to be implemented to advance the maturity of their OSPO. This model is composed of the following two vari- ables and five stages:

为了更好地解释OSPO的演变，TODO工作组建立了一个模型（图3）来协助各组织确定其OSPO所处阶段、找出为促进其OSPO走向成熟而需要实施的要素。该模型由以下两个变量和五个阶段组成：

##### MODEL VARIABLES:
- Y variable: Ability to execute.

- X variable: OSPO level.

##### 模型变量
Y变量：执行能力。
X变量：OSPO级别。

##### MODEL STAGES:

- Stage 0: Ad-hoc adoption.

- Stage 1: Legal-driven.

- Stage 2: Community-driven.

- Stage 3: Engagement-driven.

- Stage 4: Leadership-driven.

![](media/image37.png)

#### 模型阶段

阶段0：临时采用。
阶段1：法务驱动。
阶段2：社区驱动。
阶段3：参与驱动。
阶段4：领导力驱动。

FIGURE 3 图3 
Maturity stages of OSPOs OSPO成熟度阶段 
Source: TODO Group 来源：TODO工作组 
high 高 
low 低 
Ability to execute 执行能力
Stage0~4 阶段0~4
null 空
OSPO Level OSPO级别
Adoption 采用
Adopting 采用
OS Ad Hoc 临时采用OS
Legal Education 法律教育
Providing OSS Compliance, Inventory, Developer Education 提供OSS合规性、清单、开发者教育
Community Education 社区教育
Evangelizing OSS Use and Ecosystem Participation 为OSS的使用和生态参与布道
Engagement 参与
Hosting OSS Projects and Growing Communities 孵化OSS项目和发展社区
Leadership 领导力
Becoming a Strategic Decision-Making Partner 成为战略决策合伙人

### Stage 0: Ad-Hoc Approach
### 阶段0：临时采用
Nowadays, almost all organizations use OSS, although how they adapt and initially use it varies. 
They may use OSS as a building block or library in a product or tool, a key part of a vendor's solution stack, or in support of their service offering. Modern cloud native applications, almost by default, use open source systems for container orches- tration, observability, data storage, messaging, and more. In other words, nearly every organization is using open source. However,the earliest form of adoption is ad hoc due to developers solving problems using readily available tools and technologies.
This "ad-hoc adoption" usually means that little thought is given to license compliance outside the basic defaults or to the longer-term impacts of consuming OSS and distributing products that are built with OSS components.

如今，尽管适配和最初使用的方式各不相同，几乎所有的组织都使用OSS。他们可能将OSS用作产品或工具中的构建模块或库、供应商解决方案堆栈的关键部分，或将其用来支持其服务产品。现代云原生应用几乎默认使用开源系统来实现容器编排、可观察性、数据存储、消息传递等功能。换句话说，几乎每个组织都在使用开源。然而，最早期的使用形式是临时的，起因是开发者倾向于使用现成的工具和技术解决问题。这种“临时采用”通常意味着很少考虑基本默认因素之外的开源许可协议合规性或者使用OSS和分发通过OSS组件构建的产品所带来的长期影响。

### Stage 1: Legal-Driven Adoption
### 阶段1：法务驱动采用
In general, an organization forms an OSPO when it realizes that its people are consuming open source products and code across nearly all engineering and development departments and functions. This usage is typically internal rather than part of its products or services to its customers or users. At this early stage, organizations often use many different names for the OSPO. For example, IBM initially called its programmatic open source efforts the "Open Source Steering Committee."Organizations in Stage 1 recognize that OSS is a key part of their business and technology strategies. They understand that the security practices of OSS projects differ from those of proprietary software organizations. Organizations must identify their legal and security risks. The risk mitigation strategies include the following:

- Compliant licensing.

- Developer education.

- Inventory-tracking.

**In general, an organization forms an OSPO when it realizes that its people are consuming open source products and code across nearly all engineering and development departments and functions. This usage is typically internal rather than part of its products or services to its customers or users.**

通常，当一个组织意识到其员工在几乎所有工程和研发部门以及职能模块中使用开源产品和代码时，它就会成立OSPO。这种开源办公室通常是供组织内部使用的，而不是为了给客户或用户提供产品及服务。在这个早期阶段，组织往往使用很多不同的名称来称呼这个OSPO。例如，IBM最初将其开源编程工作部门称为“开源指导委员会”。 

处于阶段1的组织认识到开源软件是其业务和技术战略的关键部分。他们明白OSS项目的安全实践与专有软件组织的安全实践不同。 

组织必须识别其法务和安全风险。降低风险的策略包括：
- 遵从许可协议。
- 开发者教育。
- 库存跟踪。

**通常，当一个组织意识到其员工在几乎所有工程和研发部门以及职能模块中使用开源产品和代码时，它就会成立OSPO。这种开源办公室通常是供组织内部使用的，而不是为了给客户或用户提供产品及服务。**

### Stage 2: Community-Driven Adoption
### 阶段2：社区驱动采用

##### EARLY STAGE

After organizations recognize the value of OSS and the need for compliance, education, and a Software Bill of Materials (SBOM), they begin to realize the economic benefits of OSS usage and seek to expand it. 
OSPOs in Stage 2 create such internal mechanisms as ambas-sadors who promote the usage of approved OSS products, educational programs on good OSS hygiene, and technical training or tuition reim-bursement for OSS skill building and certification. 
With these initiatives, an organization can grow its use of OSS and amplify its message that OSS is not only important but also desirable andpreferable to propri- etary software.

##### 早期阶段

在组织认识到OSS的价值以及合规、教育和软件物料清单（SBOM）的必要性之后，他们开始了解使用OSS带来的经济效益，并想方设法扩大效益。阶段2的OSPO建立了诸如获批准OSS产品使用推广大使、良好OSS社区行为教育计划以及OSS技能构建和认证技术培训或学费报销等内部机制。通过这些举措，组织会增加对OSS的使用并强化OSS不仅重要而且比专有软件更理想与可取这个信息。

##### GROWTH STAGE

When advancing in this stage, organizations begin encouraging their developers to work on OSS projects that are critical to their operations to the extent that the developers become highly active contributors or primary maintainers. 
During this stage, OSPOs begin to streamline and optimize open outbound source contributions for their developers and create and launch open source projects to establish broad credibility in the open source community.

#### 成长阶段

在此阶段的发展过程中，组织开始鼓励其开发者从事对其运营至关重要的OSS项目，直至这些开发者成为高度活跃的贡献者或主要维护者。在这一阶段，OSPO开始帮助其开发者简化和优化对外开源贡献，并创建和发起开源项目以便在开源社区建立广泛的信誉。

### Stage 3: Engagement-Driven Adoption
### 阶段3：参与驱动采用

During Stage 3, organizations initiate and host or act as primary sponsors of OSS projects. They will dedicate one or more full-time employees to a project, and they accept responsibility for nurturing a project community and ensuring its health. They do not confuse this level of organizational commitment with individual employees who decide to open source their projects. Additionally, during this stage,organizational leaders support incubating and launching OSS projects into the public sphere because they understand how these projects benefit their organization. Such projects tend to offer improved performance and economics on crucial capabilities that may be noncore to the organization's value proposition but critical to its technology infrastructure.

在阶段3，组织发起和主办OSS项目或充当项目的主要赞助人。他们将为一个项目投入一名或多名全职员工，并承担培育项目社区和确保其健康发展的责任。他们不会将这种组织层面的投入与能决定将其项目开源的个别员工混淆。此外，在该阶段，组织领导者支持公开孵化和发起OSS项目，因为他们明白这些项目是如何让其组织受益的。这些项目往往在关键能力上提供更好的性能和经济效益，这些能力可能不是该组织价值主张的核心能力，但对其技术基础设施至关重要。

Additionally, during this stage, the OSPO develops several mechanisms to vet, organize, and operate open source projects and prepare and coach their leaders, such as the following:

- Internal processes.

- Playbooks.

- Checklists.

- Tooling.

此外，在该阶段，OSPO开发了多种机制来审查、组织和运营开源项目，并准备指导其领导者，例如：

- 内部流程。
- 攻略。
- 检查清单。
- 工具。

### Stage 4: Leadership-Driven Adoption
### 阶段4：领导力驱动采用
During this maturity stage, the OSPO becomes a strategic partner for technology decisions, guides choices, and shapes long-term commitments to projects. 
Additionally, the Chief Technology Officer(CTO) and other technology leaders consult the OSPO and its leadership on 
which open source technologies to rely and which decision criteria to use in judging open source projects. Because major open source technology choices tend to generate significant secondary and tertiary costs and affect both upstream and downstream technologies and hiring plans, the choice of open source projects becomes a major business decision. 
The following three main types of strategic guidance take shape in this final stage:

1.  Advise the CTO and technology leadership on open source technologies to adopt/remove from the organization's technology stack.

2.  Take the lead on benchmarking what constitutes an acceptable OSS project.

3.  Help organizations understand and navigate project politics.

![](media/image42.png)

在这个成熟阶段，OSPO成为做技术决策的战略合作伙伴，指导抉择并使长期投入符合项目需求。此外，首席技术官（CTO）和其他技术主管会向OSPO及其领导层咨询应依赖哪些开源技术以及可以使用哪些决策标准来评判开源项目。由于主要的开源技术选择往往会产生巨大的二级和三级成本，并影响上下游技术和招聘计划，因此开源项目的选择已成为一项主要的商业决策。以下三类主要战略指导出现在这个最后的阶段：

1. 向CTO和技术主管提建议，从组织的技术堆栈中采用/删除某项开源技术。
2. 带头对可接受的OSS项目的构成进行基准测试。
3. 帮助组织理解和驾驭项目政治。

# OSPO Structure

In this section, we explore common OSPO structures. It is important to
keep in mind that no two organizations are the same. Therefore, there
are no cookie-cutter OSPO structures. Instead, many organiza- tions,
including those with a long record of open source involvement,
experiment with different setups. Generally, an organization's goal is
to find the most suitable and efficient structure based upon its
overall

software strategy, open source aspirations, reliance on OSS in
products, unfilled positions in open source, and other factors.

### Example 1: OSPO Within an R&D Department

A common placement for an OSPO is within an R&D organization. For
instance, the author of this paper adopted this model (**FIGURE 4**)
when he was hired by Samsung in early 2013 to establish Samsung's Open
Source Group. In this example, the open source leader owns

open source engineering, and the strategy and support functions, and
reports directly to the head of R&D. The Samsung OSPO has a dedi-
cated budget to cover the head count, travel, and sponsorship costs
for open source events, membership dues for open source foundations,
hardware and software expenses, and various other miscellaneous
expenses (including promotional items, such as tee shirts, hats,
etc.).

This specific setup has worked very well for many years.

There are two main reasons to structure the OSPO under an R&D function
(or department). The first is to isolate the group from product
divisions, thereby preventing it from becoming an auxiliary develop-
ment arm for those divisions. This setup allows the OSPO to maintain a
certain level of independence, both financially and in terms of
projects, so it can focus on open source technologies of the highest
priority without being influenced by any product division. The second
reason to structure an OSPO within R&D is to better support efforts
that involve external parties, such as other organizations and
universities, away from daily product pressures.

### Example 2: Corporate-Level OSPO With Supporting Division-Level OSPOs

This model (**FIGURE 5**) works best in large organizations with
multiple product divisions. It consists of a corporate-level OSPO,
which coordinates the activity of multiple supporting OSPOs at the
division level. The corporate OSPO is responsible for establishing
organization-wide policies and processes, deciding on the strategy,
working with open source foundations, driving major open source
initiatives, and managing open source matters at the corporate level
in general.

The supporting OSPOs are responsible for executing the open source
strategy at the division level, ensuring staff follows the corpo- rate
policies and processes, delivering training, and in many cases,
managing upstream open source engineering. The corporate OSPO

may not have any engineering resources, except for a principal
engineer or a senior architect, to provide technical expertise and
leadership.

### Example 3: OSPO as Part of the CTO Office or Engineering Department

In medium-sized organizations, it is common to house the OSPO either
within the engineering department or under the CTO office. This OSPO
structure typically has a dedicated budget that is managed by the
exec- utive sponsor (Sr. Vice President of Engineering or the CTO).
Although the OSPO may have its own budget, all spending and any
external commitments require the approval of the executive sponsor.
The OSPO might have dedicated engineering resources that work on
upstream projects depending on the organization\'s needs. **FIGURE 6**
illustrates these two scenarios.

### Example 4: Virtual OSPO

The virtual OSPO (**FIGURE 7**) is a common setup in an organization
that has a head of open source, which is typically within the
engineering department, without any dedicated staff. The head of open
source works with a virtual OSPO staff comprising individuals from
different teams, such as legal, engineering, and marketing, each of
whom dedi- cates a certain percentage of their time to support open
source activ- ities. A virtual OSPO does not typically have a
dedicated budget; instead, the budget for any open source spending
would come from the engineering department or CTO office.

### Example 5: No Official OSPO

![](media/image43.png)This example (**FIGURE 8)** is of an
organization that does not have an official OSPO. This is a typical
setup in smaller organizations and start-ups where different
individuals fulfill the duties that are associated with an OSPO.
Although this structure provides more flexibility for smaller
organizations, it is difficult to scale as the organization grows.

![](media/image5.png)![](media/image6.png){width="0.4955325896762905in"
height="9.2082239720035e-2in"}

# Staffing an OSPO
# OSPO人员配备
The staffing of an OSPO depends on many variables. However, several roles are required, regardless of the specific structure of any given OSPO. These roles do not have to be distinct positions. In some cases, distin- guished individuals with strong sets of skills can fulfill more than one role.

OSPO的人员配备取决于许多变量。但是，无论任一给定OSPO的具体结构如何，有几个角色都是需要的。这些角色不一定非得是不同的职位。在某些情况下，拥有强大技能的杰出人才可以胜任多个职位。

### Head of OSPO
### OSPO负责人
The head of the OSPO is often called the director or vice president of open source, depending on the size of the organization and the open source team. The head of open source is responsible for managing and executing organization-wide open source strategies and business metrics to track the business and technical success of the program. Depending on the structure of the OSPO, the office leader could also be responsible for open source engineering resources, ensuring open source compliance, representing the organization among open source organizations, and participating in open standards efforts.

OSPO的负责人通常被称为开源总监或副总裁，这取决于组织和开源团队的规模。开源负责人负责管理和执行组织范围内的开源战略和业务指标，以跟踪项目的的业务和技术成功度。根据OSPO的结构，办公室负责人还可以负责开源工程资源、确保开源合规、在开源机构中代表其组织参与开放标准制定工作。

This individual should possess the following traits:

- A strong engineering background and experience in software development.

- Contacts with open source organizations.

- A comprehensive understanding of open source licenses.

- Knowledge of industry best practices.

- Knowledge and experience in establishing corporate-wide policies and processes.

- Technical knowledge related to the organization's products and services.

- Historical perspective of open source.

- Knowledge of how various technical project communities operate.

The TODO Group has published a [[template job specification]{.underline}](https://todogroup.org/blog/%20sample-job-req) for this role that you can customize to your needs.

此人应具有以下特征：

- 具有强大的工程背景和软件开发经验。
- 与开源组织有联系。
- 对开源许可协议有全面深入的了解。
- 了解业界最佳实践。
- 有制定公司相关政策和流程方面的知识和经验。
- 拥有与本组织产品和服务有关的技术知识。
- 有开源历史发展视角。
- 了解各种技术项目社区如何运作。

TODO工作组已发布此职位的[工作要求模板](https://todogroup.org/blog/%20sample-job-req) ，您可以根据自己的需要进行定制。

### Software Architect

We believe that it is mandatory for an OSPO to have a senior software architect or principal engineer to act as a high-level technical decision-maker on topics that are related to OSS: from design choices to technical standards, such as platforms and coding standards.

### 软件架构师
我们认为，OSPO必须有一名高级软件架构师或首席工程师担任OSS相关主题的高级技术决策者：从设计选择到技术标准，如平台和编码标准。

### Technical Evangelist

A technical evangelist is an individual with a strong technical background whose primary role is to evangelize the open source contributions and solutions that are developed by the open source group to the organization's customers, prospects, and partners, and the open source community in general. They are responsible for running demonstrations at events, delivering technical presentations, creating documentation, and generally building support to a critical mass for a given technology.
### 技术布道者
技术布道者是拥有强大技术背景的人，其主要职责通常是向组织的客户、潜在客户、合作伙伴以及开源社区宣传开源团队所做的开源贡献和研发的解决方案。他们负责在活动中做展示、提供技术报告、创建文档并在总体上为特定技术提供足够多的支持。

### Compliance Engineer

The compliance engineer supports the execution of the organization's compliance policy and process and ensures that the organization fulfills all license obligations for the OSS that is used in its products and services. Some OSPOs have complete ownership of the open source compliance function; in these cases, the OSPO may need to host multiple compliance engineers.

### 合规工程师
合规工程师支持组织的合规政策和流程的执行，并确保组织履行其产品和服务中使用的OSS许可规定的所有义务。一些OSPO全权负责开源合规职能；在这些情况下，OSPO可能需要聘请多名合规工程师。

### Legal Counsel

It is rare for an OSPO to have legal counsel among its staff. In most cases, having access to a legal counsel that is versed in open source licensing is sufficient for small and medium-sized organizations.

### 法律顾问
OSPO的工作人员中很少有法律顾问。在大多数情况下，对于中小型组织来说，能够获得精通开源许可的法律顾问的帮助就足够了。

# OSPO Responsibilities

The OSPO assumes different responsibilities that change over time. In
the following subsections, we explore these responsibilities and
discuss them at length. You can also explore these responsibilities in
this [inter-](https://ospomindmap.todogroup.org/) [active OSPO mind
map](https://ospomindmap.todogroup.org/).

### Develop and Execute an Open Source Strategy

![](media/image48.png)Since the beginning of the software industry,
nearly every software organization has followed the same business
model as follows: source code was developed by its employees or
licensed from a third party, intellectual property was closely held,
and software was delivered in a binary format to its clients. However,
the availability of enterprise-grade

OSS is changing how organizations develop and deliver products. With
open access to source code and transparent development communities,
software providers can reduce development costs while remaining active
participants in the development process. In addition, end users of the
software can also be active in the development process by contributing
directly to upstream projects rather than be passive recipients of
what the software vendor delivers to them. This development model
enables organizations to think differently about how they procure,
implement, test, deploy, and maintain software. In this report, we
explore the following four basic strategies for organizations that
utilize and integrate OSS in their products: consumer, participant,
contributor, and leader.

**FIGURE 9** illustrates the following four primary OSS strategies:
consump- tion, participation, contribution, and leadership. Each
strategy requires organizations to be successful at the previous
strategy. How far your organization advances up this ladder is
entirely dependent upon its objectives and overall open source
strategy.

These four strategies overlap as organizations transition from one
position into another. Typically, the early stages are
engineering-driven due to engineers using open source components in
product develop- ment. Initially, their participation in strategic
projects may be limited to joining the conversation or making small
contributions. Over time, this usage can grow within the organization
and become part of the business strategy as it gains traction.

Some organizations can achieve their goals simply by being consumers
of open source code and are content to stay at that level, while
others have ambitions to attain certain leadership positions. As it is
likely that your organization is already at one of these levels of the
ladder, it is important to identify both your current position on the
ladder and your target position.

###### **Consumer Scenario**

The common starting point is the adoption of OSS and integration

of OSS in products and services. Voraciously consuming open source
components will increase your ability to differentiate products and
services and reduce your overall time and costs in delivering those
products and services. The following action items are essential to
this strategy:

- Set up an open source review board to serve as a clearinghouse for
  all open source activities, including license compliance.

- Use a strategic classification scheme to guide decisions on what OSS
  to consume.

- Create an inventory of all software that is used via SBOM to enable
  a more granular view of the licenses of the OSS in use to

## Some organizations can achieve their goals simply by being consumers of open source code and

are content to stay at that level, while others have ambitions to
attain certain leadership positions.

determine whether the enterprise is complying with all license
obligations and identify any known security vulnerabilities.

- Deploy automated workflow software for evaluating/approving open
  source usage.

- Create a plan for incremental investment in head count and
  infrastructure in engineering, product management, and legal to
  manage a complex mix of closed and open source software.

When establishing a software strategy that encourages the use of OSS
in commercial products, the following actions can be taken to ensure
the successful adoption of OSS:

- Communicate the strategy for the use of OSS.

- Educate staff on open source compliance, license obligations, and
  the open source development model.

- Establish explicit criteria for determining which OSS is a candidate
  for inclusion in your products. Examples include the availability of
  new features, the maturity of the project's source code, the size
  and composition of the project's development community, and other
  factors that measure the state of the code and the people who
  maintain it.

- Establish an open source compliance program to ensure that you have
  the processes in place to meet the license obligations of the OSS
  that you are using in your products.

  - Encourage your developers to identify and adopt open source
    development tools that can enable better internal collaboration,
    increased and transparent team communication, and faster
    development cycles.

  - Encourage your staff to subscribe to open source mailing lists
    and magazines, follow blogs, and participate in discussion
    forums.

  - Encourage and fund staff's attendance at open source conferences
    for learning and networking opportunities.

  - Join open source industry bodies and foundations, such as The
    Linux Foundation, for opportunities to share development and
    legal best practices with other leaders in the industry.

  - Hire developers from the open source community.

  - Host local open source user groups and encourage your staff to
    get involved in local open source activities.

  - Invite community members to present to your development team on
    topics that are related to the project.

###### **Participant Scenario**

Once your organization is successfully using OSS in products or
services, you can expand your strategy to participate in the open
source community. Unless you have already hired experienced devel-
opers, you may need to engage more closely with the community,
increase your visibility, and begin attracting the talent that you
need. The following action items are essential to participation:

- Monitor community communication platforms, such as chat servers,
  mailing lists, forums, and websites, to keep on top of project
  developments.

- Attend relevant conferences and meetups to establish relationships
  within the community.

- Sponsor project events and foundations to improve the enterprise's
  visibility.

## Once your organization is successfully using OSS in products or services, you can expand your strategy to participate in the open source community.

###### **Contributor Scenario**

Once your enterprise realizes the benefits of participating regularly
in the community, you can assess the advantages of contributing code
to projects and communities. As code contributors help to shape future
features, contributing source code to those open source projects that
are critical to your business objectives is the best way to influence
those projects and build a positive reputation. The following action
items are essential to this scenario:

- Educate your team on community development best practices.

- Actively participate and drive technical discussions on the mailing
  list, Slack, discussion forums, etc.

- Follow the open source community's established working methods and
  processes.

- File bug reports and contribute fixes to existing bugs.

- Contribute code to improve or extend functionality.

- Contribute code to implement new features.

- Contribute bug fixes or other security measures

- Contribute to documentation efforts.

- Contribute to testing and integration efforts (e.g., write test
  code, create test cases).

- Listen to feedback on your contributions and act on it.

- Establish trust with the project maintainer and other project
  participants via your contributions and active participation.

  - Hire a staff director to lead the open source strategy and

    > manage the OSPO.

  - Hire contributors and committers to open source communities that

    > are vital to your products and services.

  - Deploy open source collaboration tools to support open source

    > usage and contributions.

  - Invest incrementally in engineering, product management, and
    > legal resources to engage with external communities.

###### **Leadership Scenario**

The highest form of open source strategy is leadership. Open source
leaders earn their strategic positions by establishing trust with
project members and maintaining a high level of continuous
contribution.

Leading organizations can capitalize on emerging trends in technology.

This scenario requires significant investment in targeted open source
communities and consortia to establish a leadership agenda. In
addition, it will require incremental investment primarily in
engineering, product management, and legal to establish leadership in
external communities and industry consortia. Below are some of the
tactical steps that can help steer your organization toward a
leadership role within a specific open source project:

Participate actively and openly within all aspects of the project,
including planning, development, testing, and release management,
thereby demonstrating your capacity to act as a good steward of the
project.

- Achieve a higher level of participation and contribution.

 Engage with the various project participants.

 Contribute to patching bugs, adding new features, and extending
functionality in existing open source projects using the best
practices, which are outlined above.

 Demonstrate good faith by contributing (when relevant) proprietary
source code from internal development to open source projects under an
appropriate open source license that makes it usable and useful to the
community.

- Publicly acknowledge that the organization has achieved tangible
  benefits by working with open source communities for critical
  software product development.

- Empower employees to seek maintainer status within the project.

- Sponsor events, provide financial support for project
  infrastructure, and consider hiring recognized open source
  developers from within the project.

- Increase participation in relevant open source organizations and
  foundations.

- Lead architectural and requirement-gathering initiatives within the
  various communities and consortia to achieve commercial objectives.

- Establish an open source architect role to proactively guide the use
  of and contributions to OSS.

While there are numerous strategic objectives to choose from, the
following objectives are common among organizations that use and
develop OSS:

- Reduce development costs.

- Improve the quality and flexibility of products.

- Achieve a faster time to market for products.

- Increase engineering capacity through community engagement.

- Broaden and deepen developer community commitment to your open
  source efforts.

### Oversee Open Source Compliance

Open source initiatives provide organizations with a vehicle to accel-
erate innovation through collaboration with open source communities.
One core responsibility for organizations is their compliance with
open source licenses. Open source compliance is the process by which
users, integrators, and software developers observe copyright notices
and satisfy the license obligations for their OSS components.

Open source compliance helps to achieve the following four main
objectives:

- Comply with open source licensing obligations.

- Facilitate effective use of OSS in commercial products and services.

```{=html}
<!-- -->
```

- Comply with third-party software supplier contractual obligations.

- Protect commercial product differentiation.

OSPOs are generally involved in open source compliance in the
following two ways:

1.  They are responsible for implementing and running a complete

end-to-open source compliance program, which includes the policy,
process, tools, automation, education, and final fulfillment of
obligations for OSS integrated into products, software, or services.

Or

2.  They are responsible for establishing the organization's general
    open source policies, and the execution and enforcement of these
    policies are pushed into the various divisions across the
    organization. For instance, ensuring open source compliance

is a great example of a scenario where the OSPO is focused on policies
and processes, and dedicated teams on the product side are more
trusted than the actual implementation and execution of a compliance
program.

The OSPO has a direct impact on the full scale of compliance responsi-
bilities. Regardless of the specific role of an OSPO, it must have at
least one individual who is very knowledgeable in open source
licensing, compliance practices, and engineering.

The minimum set of individuals that represent the core compliance team
includes a legal representative, an engineering or product repre-
sentative, and an open source compliance expert, who is often a member
of the OSPO. In the following table, we briefly present the primary
roles of these individuals who form the core open source compliance
team. For a detailed discussion on the topic of open source
compliance, please download the free e-book _[[Open Source
Compliance]{.underline}](https://www.linuxfoundation.org/publications/open-source-compliance-enterprise/)
[[in the
Enterprise]{.underline}](https://www.linuxfoundation.org/publications/open-source-compliance-enterprise/)_,
which was published by The Linux Foundation. The

b. ook is a practical guide for organizations on how best to use open
source code in products and services and legally and responsibly
partic- ipate in open source communities.

![](media/image5.png)
![](media/image6.png){width="0.4955325896762905in"
height="9.2082239720035e-2in"}

**FIGURE 11**

#### **Roles and responsibilities of the core compliance team members**

![](media/image5.png)![](media/image50.png){width="0.49392607174103237in"
height="9.178258967629047e-2in"}A DEEP DIVE INTO OPEN SOURCE PROGRAM
OFFICES: STRUCTURE, ROLES, RESPONSIBILITIES, AND CHALLENGES **20**

[]{#\_bookmark15 .anchor}Collectively, these three roles (legal,
engineering, and compliance) are responsible for the following three
main tasks:

1.  Ensuring mutual compliance with third-party software and OSS
    licenses.

2.  Facilitating the usage of and contributions to OSS.

3.  Protecting proprietary intellectual property (and product
    differentiation) by ensuring that open source license obligations do
    not propagate to proprietary or third-party software.

### Establish Open Source Policies and Processes

The policies and processes that the OSPO needs to create depend on the
organization's current and target position on the strategy ladder.
During the first stage (consumption), the OSPO needs to implement an
open source infrastructure that can support the consumption and
compliance aspects of OSS. **FIGURE 12** illustrates infrastructure
that goes beyond a simple policy to define the organization's
guidelines for using OSS. It extends to encompass a strategy that
covers usage and compliance, incorporates compliance checkpoints in
the development process, establishes a team to supervise the proper
usage of open

source, provides the necessary training, enables tooling, and
facilitates relationships with relevant open source organizations.

![](media/image51.png)

**FIGURE 12**

#### **Enabling infrastructure for open source consumption and compliance**

**21**

[]{#\_bookmark16 .anchor}show a return on investment across multiple
products. In an enter- prise setting, where the OSPO and open source
engineering are cost centers, the driving force should be to focus on
open source projects that directly support product development.

**FIGURE 13** illustrates the additional elements that the OSPO needs
to implement to support open source contributions.

### Engage with Open Source Organizations

Open source foundations are a great resource to extend your impact
within the open source ecosystem. The best place to start is with
foundations that host initiatives that are relevant to your products
or technical interests. Many organizations find it worthwhile to get

involved with well-known, established foundations, such as The Linux
Foundation's TODO Group, the Mozilla Foundation, or the Apache
Foundation. If your organization is primarily concerned with legal
dynamics, getting involved with organizations such as the Software
Freedom Law Center or the Open Invention Network will prove valuable.
The primary goal is to identify the opportunities within the ecosystem
that your organization relies on. The OSPO is the entity that drives
these relationships based on the organization's open source strategy
and product priorities.

### Prioritize and Drive Upstream Open Source Development

One of the primary responsibilities of an OSPO is to improve the orga-
nization's engagement with the key open source projects that are used
in products and services. The first step is to identify where the
organi- zation relies on OSS by surveying all products and reviewing
the SBOM. The next step is to prioritize the OSS that is already in
use and establish a contribution strategy. Such a focused approach
allows the OSPO to

### Track Performance Metrics

One of the more difficult tasks for an OSPO is decision-making on key
performance indicators or metrics that the office should track to
incentivize engineers toward the desired behavior. The traditional
metrics, which are often used in product organizations, do not apply
in the context of open source development. Therefore, new metrics

are required. Many OSPOs use specialized tools to track their
organiza- tion's contributions to open source projects, analyze the
type of contri- butions from their organization, identify contribution
patterns, and provide recommendations to improve the development
impact.

##### IMPLEMENT INNERSOURCE PRACTICES

Innersource describes the process of applying the lessons that were
learned from open source development methodology to internal projects.
The goal is to incubate the same values in the enterprise as those
that are common in the collaborative, open source development model.

A great method for OSPOs to expand the impact of open source is to
foster internal collaboration using innersource practices. These
internal collaborations present incredible visibility opportunities
for the OSPO with other departments or teams within the organization.
In addition, such interactions and collaborations position the OSPO
staff as the internal experts on open source practices and create new
opportunities to collaborate with R&D and product teams.

##### GROW OPEN SOURCE TALENT INSIDE THE ORGANIZATION

One of the core responsibilities of an OSPO is to grow the open source
talent inside the organization. To do so, OSPOs can run various

programs, including workshops, training, mentoring, and internal evan-
gelizing. Education is an essential building block in an OSPO, and it
falls into the following two categories: technical training to expand
open source technical knowledge and compliance training to ensure that
the employees possess a good understanding of the policies that govern
the use of OSS. The goal of this training is to raise awareness of
open source policies and strategies to build a common understanding of
the issues and facts of open source licensing and the business and
legal risks of incorporating OSS in products or software portfolios.
The training also serves as a venue to publicize and promote
compliance policies and processes within the organization and foster a
culture of compliance.

Moreover, OSPOs can create mentoring programs where senior open source
developers mentor junior developers, review their code commits,
provide feedback on code before it is submitted to the

upstream projects, and generally act as an advisor. The goal is to
accel- erate learning and support junior developers to become more
effective and influential in open source projects.

## A great method for OSPOs to expand the impact of open source is to foster internal collaboration using innersource practices. These internal collaborations present incredible visibility opportunities for the OSPO with other departments or teams within the organization.

##### OFFER ADVICE ON OPEN SOURCE

OSPOs act as advisors on all matters related to OSS, whether they are
internal issues to the organization or external issues relating to
compliance, open source foundations, open standards, mergers and
acquisitions, or other matters. Because of the importance of this
advisory role, senior OSPO staff plays a critical role in shaping
their organizations' software strategy, as OSS is critical within the
larger software ecosystem.

##### MANAGE OPEN SOURCE IT INFRASTRUCTURE

One of the OSPO's challenges is to ensure that their organization
provides an IT infrastructure that allows open source developers to
communicate and work with the open source projects with minimal
challenges. The following three primary domains of IT services are
common in open source development:

1.  Knowledge sharing: wikis, collaborative editing platforms, and
    public websites.

2.  Communication and problem-solving: mailing lists, forums, and
    real-time chat.

3.  Code development and distribution: code repositories and
    bug-tracking platforms.

Some or all of these tools will need to be available internally to
effec- tively support open source development. These open source
practices typically require an IT infrastructure that is less
restrictive than a typical corporate environment. If this situation
conflicts with existing orga- nization-wide IT policies, it is vital
to resolve these conflicts and allow open source developers to use the
tools that are most familiar to them. It is worth noting that some
OSPOs in large organizations create and manage their own IT
infrastructure independently from their corporate IT departments.

## Saying "no" is unequivocally the author's favorite OSPO responsibility. OSPOs act as a gating function for all major contributions that leave the organization, including new projects or contributing major proprietary code. Saying "no" is the responsibility of OSPO leaders when

proposals to release open source projects or contribute significant
bodies of code do not meet the proper requirements for success.

##### ELIMINATE FRICTION FROM USING

**AND CONTRIBUTING TO OPEN SOURCE**

OSPOs help organizations navigate internal politics or policies,
maintain relationships with communities of strategic importance, and
continuously improve processes and tools to scale and reduce the
learning curve and manual effort that is required.

##### SUPPORT CORPORATE DEVELOPMENT ACTIVITIES

OSPOs should be involved with open source due diligence (technical and
compliance) as a part of corporate development. The two major
scenarios are merger and acquisition transactions and outsourced
development.

###### **Mergers and Acquisitions**

If an organization is considering a merger or is the target of an
acqui- sition, the OSPO is a great source of expertise for open source
technology and compliance due diligence. OSPOs can help their orga-
nization to understand the open source code that is used by the target
organization and its implications as part of the due diligence
process.

###### **Outsourced Development**

The OSPO can also support corporate development when negotiating the
outsourced development of software, which will ensure that the proper
compliance procedures are followed according to the organiza- tion's
policies and processes.

##### COLLABORATE WITH UNIVERSITIES ON OPEN SOURCE PROJECTS

Many universities are eager to work with organizations that offer
learning opportunities for their students and provide them with real-
world development experience. Often, this relationship is also bene-
ficial to the organizations that are involved because it can be a
great way to develop new talent in existing open source communities
and attract new development talent from a trusted source. This is
partic- ularly useful for projects that have a shortage of experienced
devel- opers and are typically more difficult to hire for. As the
supply of talented programmers is limited, finding a way to tap into
new knowledge and influence favorable outcomes in external projects,
including academia, is vital.

##### KNOW WHEN TO SAY "NO"

Saying "no" is unequivocally the author's favorite OSPO
responsibility. OSPOs act as a gating function for all major
contributions that leave the organization, including new projects or
contributing major proprietary code. Saying "no" is the responsibility
of OSPO leaders when proposals to release open source projects or
contribute significant bodies of code do not meet the proper
requirements for success.

# OSPOs and Eliminating Friction From Using or Contributing to OSS

OSPO 与消除使用或贡献 OSS 的摩擦 

OSPOs face many challenges that we can group into the following five
areas: culture, processes, tools, continuity, and education. **FIGURE
14** illustrates these challenge areas. The general goal of an OSPO is
to make it easy for the organization to use and contribute to OSS in
support of its business goals. As such, facing and resolving these
chal- lenges and possibly others that are unique to your organization
will help you achieve your goal.

OSPO 面临许多挑战，我们可以将其分为以下五个领域：文化、流程、工具、连续性和教育。图 14 说明了这些挑战领域。 OSPO 的总体目标是使组织更容易使用 OSS 并为 OSS 做出贡献，以支持其业务目标。因此，面对并解决这些挑战以及可能是您组织独有的其他挑战，将帮助您实现目标。

### Culture
文化

Cultural challenges often stem from the gap between traditional
software development practices and the requirements of open source
development. To bridge this gap, you can hire open source experts and
ask them to train other groups that are unfamiliar with the open
source development model. These experts can provide guidance to assist
with the following:

文化挑战往往源于传统软件开发实践与开源开发需求之间的差距。为了弥补这一差距，您可以聘请开源专家并要求他们培训其他不熟悉开源开发模型的团队。这些专家可以提供指导以协助完成以下工作：

- Create internal processes that follow the open source development
  practices of release, doing so early and often, and including peer
  reviews.
 
  创建遵循开源开发实践的内部流程，尽早并经常这样做，包括同行评审。

- Improve transparency between departments to encourage more
  cross-functional collaboration.
  
  提高部门之间的透明度，以鼓励更多的跨职能协作。

- Form engineering teams around the ideals of meritocracy.

  围绕精英管理的理想组建工程团队。

- Establish proper success metrics to encourage open source and
  cross-department contributions.
  
  建立适当的成功指标以鼓励开源和跨部门的贡献。

---


FIGURE 14 Challenges that OSPOs face

图14 OSPOs面临的挑战

**Culture**
Development model
Collaboration
Transparency
Meritocracy Team
formation
Hiring practices
Performance metrics

**文化**
发展模式
协作
透明度
精英团队
形成
招聘实践
绩效指标


**Processes**
Governance 
Usage 
Compliance 
Contribution 
Approvals 
Operational model

**流程**
治理 
用法 
合规 
贡献 
批准 
运营模式

**Tools**
IT infrastructure
Development tools
Tracking metrics
Knowledge sharing
Code reuse 
Software composition
Analysis tool adoption

**工具类**
IT基础设施
开发工具
跟踪指标
知识共享
代码重用 
软件组成
分析工具的采用

**Continuity**
Strategy 
Projects 
Priorities 
Funding 
Executive support

**持续性**
策略 
项目 
优先事项 
资助
高管支持

**Education**
Executive education
 Knowledge transfer 
Technical training
Compliance training
 Mentorship program
 
**教育**
高管教育
知识转移 
技术培训
合规培训
导师计划

---

### Processes

流程

Open source development is dynamic, moves very quickly, and has unique
requirements for compliance. Software-driven industries will leave
behind those organizations that do not adapt their internal
processes to support this type of development. As developers must be
able to contribute code upstream quickly, the enterprise must modify
any internal code policies that hinder such development. We suggest
implementing the following to improve internal processes:

开源开发是动态的，发展非常迅速，并且对合规性有独特的要求。软件驱动的行业将抛弃那些不调整其内部流程以支持此类开发的组织。由于开发人员必须能够快速向上游贡献代码，因此企业必须修改任何阻碍此类开发的内部代码策略。我们建议实施以下措施来改进内部流程：

- Put a team in charge of maintaining open source compliance to avoid
  legal problems and set up a simple internal approval model for open
  source use and contributions.
  
  让一个团队负责维护开源合规性以避免法律问题，并为开源使用和贡献建立一个简单的内部批准模型。

- Move from highly complex and cumbersome policies to a more
  straightforward approach for receiving, reviewing, and approving
  source code contributions.
  
  从高度复杂和繁琐的策略转变为更直接的方法来接收、审查和批准源代码贡献。

- Balance the interests of legal, engineering, and open source and
  give the dedicated open source team blanket approval to contribute
  to many open source projects.
  
  平衡法律、工程和开源的收益，让专门的开源团队整体批准为众多开源项目做出贡献。

- Use different levels of approval depending on the nature of the code
  that is contributed (e.g., code to fix simple bugs, code to improve
  existing functionality, code to affect new functionality, or code to
  seed a new project).
  
  根据贡献的代码的性质，使用不同级别的批准（例如，修复简单错误的代码、改进现有功能的代码、影响新功能的代码或发展新项目的代码）。

## The IT environment that you create should allow developers to join a team without requiring any significant changes to how they work. The tools must support the open source development model, fulfill the needs of the OSPO, and meet corporate IT guidelines.
**

您创建的 IT 环境应允许开发人员加入任何团队，而无需对他们的工作方式进行重大更改。这些工具必须支持开源开发模型，满足 OSPO 的需求，并满足企业 IT 指南。

##### TOOLS

工具

The IT environment that you create should allow developers to join a
team without requiring any significant changes to how they work. The
tools must support the open source development model, fulfill the
needs of the OSPO, and meet corporate IT guidelines. Open source
engineers require flexibility to communicate with external
participants via email, chat, and code development platforms, and
their IT tools must facilitate this communication. For example, emails
to an open source project should never include attachments that claim
the content as the intellectual property of the email sender's
organization. We suggest implementing the following changes for
facilitating communi- cation within your OSPO:

您创建的 IT 环境应该允许开发人员加入任何团队，而无需对他们的工作方式进行任何重大更改。这些工具必须支持开源开发模型，满足 OSPO 的需求，并符合企业 IT 准则。开源工程师需要灵活地通过电子邮件、聊天和代码开发平台与外部参与者进行交流，他们的 IT 工具必须促进这种交流。例如，发给开源项目的电子邮件绝不应包含声称内容为电子邮件发件人组织的知识产权的附件。我们建议实施以下更改以促进您的 OSPO 内的交流：

- Allow communication with public mailing lists from organization
  accounts without obstruction.
  
  允许与来自组织帐户中的公共邮件列表进行通信而不受阻碍。

- Give engineers devices that support the development distribution of
  their choice.
  
  为工程师提供支持他们选择的开发发行版的设备。

- Make sure that all open source developers can access all vital
  internal tools and resources on Linux or via a separate compatible
  device.
  
  确保所有开源开发人员都可以在Linux或通过单独的兼容设备访问所有重要的内部工具和资源。 

- Support fully distributed teams that are working in remote locations
  so that they can connect to internal business resources through a
  virtual private network or similar technology.
  
  支持在远程位置工作的完全分布式团队，以便他们可以通过虚拟专用网络或类似技术连接到内部业务资源。 

- Evaluate your IT policies for help desk support, with secure methods
  for resolving IT issues for remote employees.
  
  评估您的IT策略中关于服务台的支持，并使用安全方法解决远程员工的 IT 问题。

### Continuity

持续性

For some organizations, continuity suggests a long, boring document
that nobody reads. When it comes to OSS, continuity is an ongoing
chal- lenge as the organization adapts to changes in its business,
business strategy, and industry. In practical terms, we can break
continuity into the following three categories:

对于一些组织来说，持续性意味着一个没有人阅读的冗长乏味的文件。对于 OSS，随着组织适应其业务、业务战略和行业的变化，持续性是一个不断的挑战。实际上，我们可以将持续性分为以下三类：

1.  []{#\_bookmark19 .anchor}**Continuity of the open source strategy.**
    Informing current and future employees of the ever-evolving open
    source strategy, with updates on new developments and changes in
    real time.
    
1. 开源战略的持续性。包括通知当前和未来的员工不断发展的开源战略，并实时更新新的发展和变化。


2.  **Continuity of projects and priorities.** Ensuring continued
    involvement in open source projects and initiatives to make use of
    any momentum that preceded a period of disruption or changes in the
    organizational environment.
    
2. 项目和优先事项的持续性。利用组织环境混乱或变化之前的任何势头，确保持续参与开源项目和计划。

3.  **Continuity of executive support and funding.** Ensuring continued
    financial and executive support and providing adequate resources to
    support the open source program.
    
3.  高管支持和资金的连续性。确保持续的财务和高管支持，并提供足够的资源来支持开源项目。  
   

The executive sponsor is critical to continuity and communicating the
value of the open source efforts and expectations across the organization to encourage the successful adoption, implementation,
and contribution to open source projects.

高管支持方对于持续性和在整个组织中传达开源努力和期望的价值，以鼓励开源项目的成功采用、实施和贡献至关重要。

### Education

教育

Open source software is an integral part of the software landscape,
with significant benefits for users and the ecosystem. However, to
realize these benefits, organizations must overcome knowledge deficits
through education and training as follows:

开源软件是软件领域不可或缺的一部分，为用户和生态系统带来了巨大的益处。然而，要实现这些益处，组织必须通过以下教育和培训来克服知识缺陷：

##### EXECUTIVE TRAINING

高管培训

These courses help executives and managers to understand and artic-
ulate the basic concepts for building effective open source practices.
Such courses often cover techniques for building effective processes
and strategies for consuming OSS, creating new open source projects,
contributing to projects, and driving software leadership in the open
ecosystem.

这些课程帮助高管和经理理解和阐明构建有效开源实践的基本概念。此类课程通常涵盖构建有效流程和策略以使用 OSS、创建新的开源项目、为项目做出贡献以及在开放生态系统中推动软件领导力的技术。


##### COMPLIANCE TRAINING

合规培训

With the adoption of OSS comes the responsibility to respect and
fulfill the IP obligations of applicable open source licenses. To that
end, orga- nizations provide employee training on the basics of OSS,
open source licenses, how copyright works, and the organization's
policies and processes.

随着 OSS 的采用，我们有责任尊重和履行适用的开源许可的知识产权义务。为此，组织为员工提供 OSS 基础知识、开源许可证、版权如何运作以及组织的政策和流程方面的培训。

##### MENTORSHIP PROGRAMS

辅导计划

To increase open source knowledge and technical skills, organizations
set up mentoring programs in which a senior open source developer
guides a junior developer in a structured and often one-to-one rela-
tionship. The goal is to transfer knowledge and train mentees on how
to work effectively with open source projects while increasing their
tech- nical competencies in their specific domain.

为了增加开源知识和技术技能，组织建立了指导计划，其中高级开源开发人员以结构化且通常是一对一的关系指导初级开发人员。目标是传授知识并培训学员如何有效地使用开源项目，同时提高他们在特定领域的技术能力。

##### TECHNICAL TRAINING

技术培训

Technical training expands the technical knowledge base of staff. It
addresses weaknesses and upskills employees to do new and different
tasks. The open source training industry is thriving because of the
high demand for open source skills and training on the latest open
source technologies.

技术培训扩大了员工的技术知识库。它解决了弱点并提高了员工完成新任务和不同任务的技能。由于对开源技能和最新开源技术培训的高需求，开源培训行业正在蓬勃发展。

# The TODO Group
# TODO工作组
The TODO Group is an OSPO resource hub and open community of practitioners who aim to create and share knowledge and collaborate on practices, tools, and other ways to run successful and effective OSPOs or similar open source initiatives. It was formed by its 1,700+community participants and 80+ general members across different sectors and regions and managed as an open source project under The Linux Foundation. The TODO Group offers a maturity model, set of guides, mind map, 101 course, annual surveys, and case studies to help organizations advance in their OSPO journey. These OSPO resources are developed by the TODO Group in collaboration with The Linux Foundation and the larger open source community. If you are looking to establish an OSPO in your organization, or you lead an OSPO and are looking to connect with peers at other organizations, please visit todogroup.org/community to get started and join our Slack channel or OSPO forum discussions.

TODO工作组是一个OSPO的资源中心和从业者开放社区，旨在创建和共享知识、并在实践、工具等他方式上协作，来成功、高效地运作OSPO或类似的开源项目。它由来自于不同的领域和地域的1700+名社区参与者和80多名会员组成，并被作为Linux基金会的一个开源项目管理。TODO工作组通过提供成熟度模型、系列指南、思维导图、101入门课程、年度调查和案例研究来帮助各组织在OSPO旅程中持续前进。这些OSPO资源是由TODO工作组和Linux基金会以及更大范围的开源社区合作开发的。如果您希望在您的组织中建立开源项目办公室OSPO，或者您已在一个OSPO中并希望与其他组织的OSPO人员建立联系，请从访问todogroup.org/community 开始，加入我们的Slack频道或者OSPO论坛讨论。

### Conclusion
### 总结
OSPOs play a critical role in helping organizations master OSS and
driving organizations into leadership positions in open technologies
that are critical to their products, services, and IT solutions. OSPOs
can support their organizations in the following four key areas:

1.  **Consumption ---** Establish an internal infrastructure that
    enables proper open source practices and incorporates open source
    policies, processes, checklists, and training.

2.  **Participation ---** Engage with the open source community on
    communication platforms and at events. Sponsor projects and
    organizations that are important to the OSS that your organization
    relies on for its products and services.

3.  **Contribution ---** Hire or train developers that focus
    specifically on open source contributions and deploy the necessary
    tools to support internal open source engineering.

4.  **Leadership ---** Increase engagement with open source communities,
    open standards bodies, and open source foundations; launch new open
    source initiatives and projects; and increase your organization's
    visibility in open source communities.

If you are part of an organization that relies on OSS for products or
services and your organization does not have a formalized OSPO yet,
please consider this report a call to action to do exactly that.

OSPO 在帮助组织掌握 OSS 并推动组织在对其产品、服务和 IT 解决方案至关重要的开放技术方面占据领导地位发挥了关键作用。OSPO 可以在以下四个关键领域为其组织提供支持：
1. **消费 ---** 建立一个内部基础设施，以便实施合适的开源实践并整合开源政策、流程、清单和训练。
2. **参与 --—** 在交流平台和活动上与开源社区互动。赞助对您的组织而言在项目或服务上存在依赖的重要的OSS项目和组织。
3. **贡献 ---** 雇用或培训专门关注开源贡献的员工，并部署必要工具来支持内部开源工程。
4  **领导力 ---** 增加与开源社区、开放标准机构和开源基金会的互动；启动新的开源计划和项目；并提高您的组织在开源社区中的知名度。
如果你是一个依赖OSS项目和服务的组织的一员且你们组织目前没有一个正式的OSPO，请将此报告视为采取行动的号召。

# Acknowledgments 
# 致谢
The author would like to express his sincere appreciation to his Linux Foundation and TODO Group colleagues, Chris Aniszczyk, Hilary Carter,Ana Jimenez, Jason Perlow, Melissa Schmidt, and Barry Hall, for their improvements via valuable reviews and feedback. This report has benefited immensely from their experiences and contributions.

作者衷心感谢他的Linux基金会和TODO工作组的同事们，克里斯·阿尼什切克、希拉瑞.卡特、安娜·希门尼斯、杰森·佩洛、梅丽莎·施密特和巴里·霍尔，通过宝贵的评论和反馈提供的改进。本报告从他们的经验和贡献中受益匪浅。

# Feedback
# 反馈
The author apologizes in advance for any spelling mistakes or possible errors and is grateful to receive corrections and suggestions for improvements via ibrahimatlinux.com/contact.html.

作者对任何拼写错误或可能的错误提前致歉，并非常感激能通过ibrahimatlinux.com/contact.html 收到更正和改进建议。

# Linux Foundation Resources
# Linux基金会资源

- [[E-book: Guide to Enterprise Open Source]{.underline}](https://linuxfoundation.org/tools/guide-to-enterprise-open-source/)

- [[E-book: Open Source Compliance in the Enterprise]{.underline}](https://www.linuxfoundation.org/publications/open-source-compliance-enterprise/)

- [[E-book: Open Source Audits in Merger and Acquisition]{.underline}](https://www.linuxfoundation.org/resources/open-source-audits-merger-acquisition-transactions/)
  [[Transactions]{.underline}](https://www.linuxfoundation.org/resources/open-source-audits-merger-acquisition-transactions/)

- [[Linux Foundation Enterprise Guides]{.underline}](https://www.linuxfoundation.org/resources/open-source-guides/)

- [[Linux Foundation Open Compliance Program]{.underline}](https://compliance.linuxfoundation.org/) ---  Resources to support organizations with open source compliance.

- [[TODO Group](http://todogroup.org/)]{.underline} --- Open community of practitioners and organizations that collaborate on best practices, tools, and other ways to run successful open source programs.


- [[电子书：企业开源指南]{.underline}](https://linuxfoundation.org/tools/guide-to-enterprise-open-source/)

- [[电子书：企业中的开源合规性]{.underline}](https://www.linuxfoundation.org/publications/open-source-compliance-enterprise/)

- [[电子书：合并收购中的开源审计]{.underline}](https://www.linuxfoundation.org/resources/open-source-audits-merger-acquisition-transactions/)
  [[Transactions]{.underline}](https://www.linuxfoundation.org/resources/open-source-audits-merger-acquisition-transactions/)

- [[Linux基金会企业指南]{.underline}](https://www.linuxfoundation.org/resources/open-source-guides/)

- [[Linux基金会开放合规计划]{.underline}](https://compliance.linuxfoundation.org/) --- 在开源合规性上支持各组织的资源。

- [[TODO工作组](http://todogroup.org/)]{.underline} ---面向从业者和组织的开放社区，旨在最佳实践、工具等他方式上协作来运作成功的开源项目。



# About the Author
# 关于作者
![](media/image54.jpeg){width="1.3351246719160106in"
height="2.01665791776028in"}Dr. Ibrahim Haddad is Vice President of Strategic Programs at The Linux Foundation and the General Manager of LF AI & Data, which provides a trusted hub for developers to code, manage, and scale critical open source artificial intelligence and data projects. 
Before The Linux Foundation, he served as Vice
President of R&D and Head of the Open Source Division at Samsung Electronics. Throughout his career, Haddad held technology and portfolio management roles at Ericsson Research, the Open Source Development Labs, Motorola, Palm, Hewlett-Packard, and The Linux Foundation. He graduated with honors from Concordia University (Montréal, Canada) with a Ph.D. in Computer Science.

**Twitter:** \@IbrahimAtLinux

**Website:** IbrahimAtLinux.com

易卜拉欣·哈达德博士是Linux基金会战略项目副总裁，也是大伞项目LF AI & data的执行总监，该大伞项目提供了一个可信赖的中心平台，开发者可以写代码、管理和扩展关键的人工智能和数据开源项目。在Linux基金会之前，他曾担任副三星电子研发总裁兼开源总监。在他的职业生涯中，哈达德曾在爱立信研发、开源开发实验室、摩托罗拉、Palm、惠普和Linux基金会担任技术和产品管理职务。他以优异成绩毕业于康科迪亚大学（加拿大蒙特利尔），获得计算机科学博士学位。

**推特:** \@IbrahimAtLinux

**网站:** IbrahimAtLinux.com


# Disclaimer
# 声明
This report is provided "as is." The Linux Foundation and its authors, contributors, and sponsors expressly disclaim any warranties (express, implied, or otherwise), including implied warranties of merchantability, noninfringement, fitness for a particular purpose, or title, related to this report. In no event will The Linux Foundation and its authors, contributors, and sponsors be liable to any other party for lost profits or any form of indirect, special, incidental, or consequential damages of any character from any causes of action of any kind with respect to this report, whether based on breach of contract, tort (including negligence), or otherwise, and whether they have been advised of the possibility of such damage. Sponsorship of the creation of this report does not constitute an endorsement of its
findings by any of its sponsors.

本报告按“原样”提供。Linux基金会及其作者、贡献者和赞助人明确不承担与本报告相关的任何保证（明示、暗示或其他），包括适销性、不侵权、适用于特定目的或标题的默示保证。在任何情况下，Linux基金会及其作者、贡献者和赞助人都不对任何其他方负责，因为与本报告有关的任何类型的诉讼原因造成的利润损失或任何形式的间接、特殊、附带或间接损害，无论是基于违约、侵权（包括疏忽）还是其他原因，以及是否已告知他们可能发生这种损害。赞助编写本报告并不构成对其任何提案国的调查结果。

![](media/image1.jpeg)

Founded in 2021, [Linux Foundation Research]{.underline} explores the growing scale of open source collaboration, providing insight into emerging technology trends, best practices, and the global impact of open source projects. Through leveraging project databases and networks, and a commitment to best practices in quantitative and qualitative methodologies, Linux Foundation Research is creating the go to repository for open source insights for the benefit of organizations the world over.

[twitter.com/linuxfoundation](https://twitter.com/linuxfoundation)
facebook.com/TheLinuxFoundation [linkedin.com/company/the linux
foundation](https://inkedin.com/) youtube.com/user/TheLinuxFoundation

[Linux基金会研究]{.underline}成立于2021年，探索规模不断扩大的开源协作，深入了解新兴技术趋势、最佳实践和开源项目的全球影响。通过利用项目数据库和网络，以及对定量和定性方法的最佳实践的承诺，Linux基金会研究正在为世界各地的组织创建以开源洞见的平台宝库。

Part of The Linux Foundation, LF AI & Data supports open source innovation in artificial intelligence, machine learning, deep learning, and data. LF AI & Data was established to support a sustainable open source AI ecosystem that makes it easy to create AI and data products and services using open source technologies. We foster collaboration under a neutral environment with an open governance model to support the harmonization and acceleration of open source technical projects.
作为Linux基金会的一部分，LF AI & Data支持人工智能、机器学习、深度学习和数据领域的开源创新。LF AI & Data的建立是为了支持可持续的开源人工智能生态系统，使开发者可以轻松地使用开源技术创建人工智能和数据产品和服务。我们通过开放治理模式促进中立环境下的合作，以支持开源技术项目的协调和加速。

[[TODO]{.underline}](https://todogroup.org/) is an open group of 70+ organizations with years of experience running open source programs that want to collaborate on practices, tools, and other ways to run successful and effective open source projects and programs. It is a place to share experiences, develop best practices and guidance as well as work on common tooling to improve OSPO adoption and education worldwide across sectors. Discover more about all the ongoing TODO Initiatives [[here]{.underline}](https://github.com/todogroup) and check out the OSPO landscape:
[[https://landscape.todogroup.org]{.underline}](https://landscape.todogroup.org/)

twitter.com/todogroup facebook.com/todo linkedin.com/company/todo-group

[[TODO工作组]{.underline}](https://todogroup.org/) 是一个由70+个组织组成的开放工作组，他们拥有多年的开源项目运作经验，希望在实践、工具等他方式上协作来成功、高效地运作开源项目/计划。它是一个通过分享经验、制定最佳实践和指导以及开发通用工具的地方，进而推进全球各环节采用OSPO和教育。请想了解更多进行中的TODO计划的信息。 了解有关所有正在进行的TODO计划的更多信息[[此处]{.underline}](https://github.com/todogroup) ，并查看OSPO一览图[[https://landscape.todogroup.org]{.underline}](https://landscape.todogroup.org/)

twitter.com/todogroup facebook.com/todo linkedin.com/company/todo-group

【[TODO]{.underline}】（https://todogroup.org/）是一个由70+个组织组成的开放小组，他们拥有多年的开源程序运行经验，希望在实践、工具和其他方式上进行协作，以运行成功有效的开源项目和程序。它是一个分享经验、制定最佳做法和指导以及共同工具的地方，以改善全球各部门采用OSPO和教育。了解有关所有正在进行的TODO计划的更多信息【【此处】{.underline}】（https://github.com/todogroup），并查看OSPO格局：
【【https://landscape.todogroup.org】{.underline}】(https://landscape.todogroup.org/)

**ter.com/todogroup facebook.com/todo linkin.com/Company/todo-group

Copyright © 2022 [[The Linux Foundation]{.underline}](https://www.linuxfoundation.org/)

This report is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International Public License]{.underline}. This material may be copied and distributed under the terms of the Creative Commons license.

To reference the work, please cite as follows: Ibrahim Haddad, "**A Deep Dive Into Open Source Program Offices: Structure, Roles, Responsibilities, and Challenges** " foreword by Chris Aniszczyk, August, 2022.

版权所有 © 2022 [[Linux基金会]{.underline}](https://www.linuxfoundation.org/)
本报告使用 [知识共享署名-禁止演绎4.0 国际许可协议（CC BY-ND 4.0）]{.underline}。可根据知识共享许可协议的条款复制和分发本材料。
要参考这项工作时请引用以下信息：易卜拉欣·哈达德，“*深入开源项目办公室：结构、角色、责任和挑战**” 克里斯·阿尼什切克的前言，2022年8月。
