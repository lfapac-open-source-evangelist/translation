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

If you\'re like most corporate leaders, you\'re likely to be familiar
with open source and may even already have an open source program in
place. But what exactly is an [O[pen Source Program Office
(OSPO)](https://github.com/todogroup/ospodefinition.org)]{.underline},
what roles and responsibilities does it have, and how can it
contribute to your organization\'s success?

An OSPO is a corporate entity that is responsible for managing and
coordinating an organization\'s open source activities. The OSPO can
be seen as the central nervous system for an organization\'s open
source strategy, and it provides governance, oversight, and support
for all things related to open source.

At The Linux Foundation, we view OSPOs as critical components of
successful organizations. We\'ve seen firsthand how an effective OSPO
can help an organization achieve its business goals and objectives by
leveraging the power of open source. The
[[TODO]{.underline}](https://todogroup.org/) can help you set up an
OSPO or take your existing program to the next level.

The TODO Group is a group of organizations that are committed to
building the best practices and tools for managing successful open
source programs. We are the leading voice on all things related to
open source program management, with a growing community of practice
that includes some of the world\'s largest organizations. We encourage
you as a practice leader, or someone who is thinking about setting up
an OSPO, to join us.

This paper is an introduction to setting up an OSPO. It covers the
what, why, and how of open source program management, with a focus on
the role of an OSPO and the benefits. It also includes descriptions of
various structural models for OSPOs and provides tips and best prac-
tices for success. We hope that you find it helpful as you embark on
your open source journey.

**Chris Aniszczyk**

_CTO, The Linux Foundation Co-Founder, The TODO Group_

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

# Abstract

Open source projects and initiatives provide enterprises with proven,
successful models to collaborate with other organizations, create new
technologies, and support the development of new commu- nities.
Organizations across many industries are establishing
[[Open]{.underline}](https://github.com/todogroup/ospodefinition.org)
[[Source Program
Offices]{.underline}](https://github.com/todogroup/ospodefinition.org)
(OSPOs) and staffing them with highly skilled individuals to drive
open source software(OSS) leadership and gain

a critical foothold in this external research and development (R&D)
ecosystem.

This report examines how enterprises structure their OSPOs and the
required minimal staffing needed for their operation, discusses the
responsibilities of such offices, and elaborates on the challenges
that are faced in open source enterprise adoption.

# Introduction

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

OSS allows shared development and lowers research and development
(R&D) costs by enabling organizations to reap the benefit of billions

of dollars of OSS, which they can harness to create better products

and services. In addition, it helps to accelerate product development
and enables a faster time to market by aligning business needs with
upstream open source projects. Organizations do not get involved in
open source projects because it is fun; they do it because it is a
part of their business or product strategy. OSPOs often manage and
orches- trate that involvement.

The first step in establishing an OSPO is understanding that open
source is key to mastering software engineering, as almost every
software product that exists today relies on OSS. Leading organiza-
tions in a growing number of industries have established their
position by becoming leaders in software development, and OSS is a
critical component of this leadership. The second step is the
availability of

an executive sponsor within the organization who will support the

![](media/image34.png)[]{#\_bookmark3 .anchor}establishment of an OSPO,
provide funding for it, and offer a long-term commitment to improving
and growing open source engineering in

the organization. This person also plays a critical role in
identifying a trusted open source leader who can create and develop
the OSPO.

# OSPO Definition 
# 开源项目办公室OSPO的定义

An OSPO is designed to do the following: (1) be the center of compe-tency for an organization\'s open source operations and structure and (2) place a strategy and set of policies on top of an organization\'s open source efforts. This can include setting code use, distribution, selection, auditing, and other policies; training developers; ensuring legal compliance; and promoting and building community engagement to benefit the organization strategically. See the [OSPO definition](https://github.com/todogroup/ospodefinition.org) by the TODO for more information.

设立开源项目办公室OSPO的目的包括：（1）成为该组织里开源运作、架构的能力中心，以及（2）在该组织的开源努力的基础上制定战略和系列策略。其中可以包括设置开源代码的使用、分发、选择、审计等策略；培训开发者；确保法务合规性；以及建立并促进社区参与来支撑组织战略。更多信息，请参见TODO的【OSPO定义】(https://github.com/todogroup/ospodefinition.org)。

# OSPO Characteristics
# 开源项目办公室OSPO的特征
To a certain degree, an organization calling itself an OSPO indicates that the organization has reached a mature stage, gained critical mass support with its enterprise, and manifests the following five key characteristics:

1.  Employees are tasked with fostering and nurturing OSS usage.

2.  The organization has a formal policy regarding the use and production of OSS.

3.  Executives recognize that OSS and open source are important strategic assets.

4.  Significant numbers of employees are contributing code to open source projects.

5.  Processes, procedures, and tools are in place to streamline and facilitate open source consumption and participation.

在一定程度上，自称为开源项目办公室OSPO表明开源在该组织到了相对成熟的阶段，已在企业内已获得达到群聚效应的支持，并表现出以下五个关键特征：

1.员工的任务是培养和孵化培养开源软件的使用。

2.该组织有关于使用和生产开源软件的正式策略。

3.高层认识到开源软件和开源是重要的战略资产。

4.大量的员工正在为开源项目贡献代码。

5.用来简化和促进开源的使用和参与的的流程、机制和工具已到位。

# OSPO Maturity Model

To better explain the evolution of OSPOs, the TODO Group has developed
a model (**FIGURE 3**) to assist organizations in determining their
OSPO and identifying the elements that need to be implemented to
advance the maturity of their OSPO. This model is composed of the
following two vari- ables and five stages:

##### MODEL VARIABLES:

- Y variable: Ability to execute.

- X variable: OSPO level.

##### MODEL STAGES:

- Stage 0: Ad-hoc adoption.

- Stage 1: Legal-driven.

- Stage 2: Community-driven.

- Stage 3: Engagement-driven.

- Stage 4: Leadership-driven.

![](media/image37.png)

### Stage 0: Ad-Hoc Approach

Nowadays, almost all organizations use OSS, although how they adapt
and initially use it varies. They may use OSS as a building block or
library in a product or tool, a key part of a vendor's solution stack,
or in support of their service offering. Modern cloud native
applications, almost by default, use open source systems for container
orches- tration, observability, data storage, messaging, and more. In
other words, nearly every organization is using open source. However,
the earliest form of adoption is ad hoc due to developers solving
problems using readily available tools and technologies. This "ad-hoc
adoption" usually means that little thought is given to license
compliance outside the basic defaults or to the longer-term impacts of
consuming OSS and distributing products that are built with OSS
components.

### Stage 1: Legal-Driven Adoption

In general, an organization forms an OSPO when it realizes that its
people are consuming open source products and code across nearly all
engineering and development departments and functions. This usage is
typically internal rather than part of its products or services to its
customers or users. At this early stage, organizations often use many
different names for the OSPO. For example, IBM initially called its
programmatic open source efforts the "Open Source Steering Committee."

Organizations in Stage 1 recognize that OSS is a key part of their
business and technology strategies. They understand that the security
practices of OSS projects differ from those of proprietary software
organizations.

Organizations must identify their legal and security risks. The risk
miti- gation strategies include the following:

- Compliant licensing.

- Developer education.

- Inventory-tracking.

## In general, an organization forms an OSPO when it realizes that its people are consuming open source products and code across nearly all engineering and development departments and functions. This usage is typically internal rather than part of its products or services to its customers or users.

### Stage 2: Community-Driven Adoption

##### EARLY STAGE

After organizations recognize the value of OSS and the need for
compliance, education, and a Software Bill of Materials (SBOM), they
begin to realize the economic benefits of OSS usage and seek to expand
it. OSPOs in Stage 2 create such internal mechanisms as ambas-

sadors who promote the usage of approved OSS products, educational
programs on good OSS hygiene, and technical training or tuition reim-
bursement for OSS skill building and certification. With these
initiatives, an organization can grow its use of OSS and amplify its
message that OSS is not only important but also desirable and
preferable to propri- etary software.

##### GROWTH STAGE

When advancing in this stage, organizations begin encouraging their
developers to work on OSS projects that are critical to their
operations to the extent that the developers become highly active
contributors or primary maintainers. During this stage, OSPOs begin to
streamline and optimize open outbound source contributions for their
developers and create and launch open source projects to establish
broad credibility in the open source community.

### Stage 3: Engagement-Driven Adoption

During Stage 3, organizations initiate and host or act as primary
sponsors of OSS projects. They will dedicate one or more full-time
employees to a project, and they accept responsibility for nurturing a
project community and ensuring its health. They do not confuse this
level of organizational commitment with individual employees who
decide to open source their projects. Additionally, during this stage,
organizational leaders support incubating and launching OSS projects
into the public sphere because they understand how these projects
benefit their organization. Such projects tend to offer improved
perfor- mance and economics on crucial capabilities that may be
noncore

to the organization's value proposition but critical to its technology
infrastructure.

Additionally, during this stage, the OSPO develops several mechanisms
to vet, organize, and operate open source projects and prepare and
coach their leaders, such as the following:

- Internal processes.

- Playbooks.

- Checklists.

- Tooling.

### Stage 4: Leadership-Driven Adoption

During this maturity stage, the OSPO becomes a strategic partner for
technology decisions, guides choices, and shapes long-term commitments
to projects. Additionally, the Chief Technology Officer

(CTO) and other technology leaders consult the OSPO and its leadership
on which open source technologies to rely and which decision criteria
to use in judging open source projects. Because major open source
technology choices tend to generate significant secondary and tertiary
costs and affect both upstream and downstream technologies and hiring
plans, the choice of open source projects becomes a major business
decision. The following three main types of strategic guidance take
shape in this final stage:

1.  Advise the CTO and technology leadership on open source technologies
    to adopt/remove from the organization's technology stack.

2.  Take the lead on benchmarking what constitutes an acceptable OSS
    project.

3.  Help organizations understand and navigate project politics.

![](media/image42.png)

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

The staffing of an OSPO depends on many variables. However, several
roles are required, regardless of the specific structure of any given
OSPO. These roles do not have to be distinct positions. In some cases,
distin- guished individuals with strong sets of skills can fulfill
more than one role.

### Head of OSPO

The head of the OSPO is often called the director or vice president of
open source, depending on the size of the organization and the open
source team. The head of open source is responsible for managing and
executing organization-wide open source strategies and business
metrics to track the business and technical success of the program.

Depending on the structure of the OSPO, the office leader could also
be responsible for open source engineering resources, ensuring open
source compliance, representing the organization among open source
organizations, and participating in open standards efforts.

This individual should possess the following traits:

- A strong engineering background and experience in software

  > development.

- Contacts with open source organizations.

- A comprehensive understanding of open source licenses.

- Knowledge of industry best practices.

- Knowledge and experience in establishing corporate-wide policies and

  > processes.

- Technical knowledge related to the organization's products and

  > services.

- Historical perspective of open source.

- Knowledge of how various technical project communities operate.

The TODO Group has published a [[template job
specification]{.underline}](https://todogroup.org/blog/%20sample-job-req)
for this role that you can customize to your needs.

### Software Architect

We believe that it is mandatory for an OSPO to have a senior software
architect or principal engineer to act as a high-level technical deci-
sion-maker on topics that are related to OSS: from design choices to
technical standards, such as platforms and coding standards.

### Technical Evangelist

A technical evangelist is an individual with a strong technical back-
ground whose primary role is to evangelize the open source contribu-
tions and solutions that are developed by the open source group to the
organization's customers, prospects, and partners, and the open source
community in general. They are responsible for running demonstrations
at events, delivering technical presentations, creating documentation,
and generally building support to a critical mass for a given
technology.

### Compliance Engineer

The compliance engineer supports the execution of the organiza- tion's
compliance policy and process and ensures that the organization
fulfills all license obligations for the OSS that is used in its
products and services. Some OSPOs have complete ownership of the open

source compliance function; in these cases, the OSPO may need to host
multiple compliance engineers.

### Legal Counsel

It is rare for an OSPO to have legal counsel among its staff. In most
cases, having access to a legal counsel that is versed in open source
licensing is sufficient for small and medium-sized organizations.

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

OSPOs face many challenges that we can group into the following five
areas: culture, processes, tools, continuity, and education. **FIGURE
14** illustrates these challenge areas. The general goal of an OSPO is

to make it easy for the organization to use and contribute to OSS in
support of its business goals. As such, facing and resolving these
chal- lenges and possibly others that are unique to your organization
will help you achieve your goal.

### Culture

Cultural challenges often stem from the gap between traditional
software development practices and the requirements of open source
development. To bridge this gap, you can hire open source experts and

ask them to train other groups that are unfamiliar with the open
source development model. These experts can provide guidance to assist
with the following:

- Create internal processes that follow the open source development
  practices of release, doing so early and often, and including peer
  reviews.

- Improve transparency between departments to encourage more
  cross-functional collaboration.

- Form engineering teams around the ideals of meritocracy.

- Establish proper success metrics to encourage open source and
  cross-department contributions.

---

**Culture** **Processes**

---

Development model Governance

Collaboration Usage

Transparency Compliance

Meritocracy Contribution

Team formation Approvals

Hiring practices Performance Operational model
metrics

---

### Processes

Open source development is dynamic, moves very quickly, and has unique
requirements for compliance. Software-driven industries will leave
behind those organizations that do not adapt their internal

processes to support this type of development. As developers must be
able to contribute code upstream quickly, the enterprise must modify
any internal code policies that hinder such development. We suggest
implementing the following to improve internal processes:

- Put a team in charge of maintaining open source compliance to avoid
  legal problems and set up a simple internal approval model for open
  source use and contributions.

- Move from highly complex and cumbersome policies to a more
  straightforward approach for receiving, reviewing, and approving
  source code contributions.

- Balance the interests of legal, engineering, and open source and
  give the dedicated open source team blanket approval to contribute
  to many open source projects.

- Use different levels of approval depending on the nature of the code
  that is contributed (e.g., code to fix simple bugs, code to improve
  existing functionality, code to affect new functionality, or code to
  seed a new project).

## The IT environment that you create should allow developers to join a team without requiring any significant changes to how they work. The tools must support

the open source development model, fulfill the needs of the OSPO, and
meet corporate IT guidelines.

##### TOOLS

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

- Allow communication with public mailing lists from organization
  accounts without obstruction.

- Give engineers devices that support the development distribution of
  their choice.

- Make sure that all open source developers can access all vital
  internal tools and resources on Linux or via a separate compatible
  device.

- Support fully distributed teams that are working in remote locations
  so that they can connect to internal business resources through a
  virtual private network or similar technology.

- Evaluate your IT policies for help desk support, with secure methods
  for resolving IT issues for remote employees.

### Continuity

For some organizations, continuity suggests a long, boring document
that nobody reads. When it comes to OSS, continuity is an ongoing
chal- lenge as the organization adapts to changes in its business,
business strategy, and industry. In practical terms, we can break
continuity into the following three categories:

1.  []{#\_bookmark19 .anchor}**Continuity of the open source strategy.**
    Informing current and future employees of the ever-evolving open
    source strategy, with updates on new developments and changes in
    real time.

2.  **Continuity of projects and priorities.** Ensuring continued
    involvement in open source projects and initiatives to make use of
    any momentum that preceded a period of disruption or changes in the
    organizational environment.

3.  **Continuity of executive support and funding.** Ensuring continued
    financial and executive support and providing adequate resources to
    support the open source program.

The executive sponsor is critical to continuity and communicating the
value of the open source efforts and expectations across

the organization to encourage the successful adoption, implementation,
and contribution to open source projects.

### Education

Open source software is an integral part of the software landscape,
with significant benefits for users and the ecosystem. However, to
realize these benefits, organizations must overcome knowledge deficits
through education and training as follows:

##### EXECUTIVE TRAINING

These courses help executives and managers to understand and artic-
ulate the basic concepts for building effective open source practices.
Such courses often cover techniques for building effective processes
and strategies for consuming OSS, creating new open source projects,
contributing to projects, and driving software leadership in the open
ecosystem.

##### COMPLIANCE TRAINING

With the adoption of OSS comes the responsibility to respect and
fulfill the IP obligations of applicable open source licenses. To that
end, orga- nizations provide employee training on the basics of OSS,
open source licenses, how copyright works, and the organization's
policies and processes.

##### MENTORSHIP PROGRAMS

To increase open source knowledge and technical skills, organizations
set up mentoring programs in which a senior open source developer
guides a junior developer in a structured and often one-to-one rela-
tionship. The goal is to transfer knowledge and train mentees on how
to work effectively with open source projects while increasing their
tech- nical competencies in their specific domain.

##### TECHNICAL TRAINING

Technical training expands the technical knowledge base of staff. It
addresses weaknesses and upskills employees to do new and different
tasks. The open source training industry is thriving because of the
high demand for open source skills and training on the latest open
source technologies.

# The TODO Group

The TODO Group is an OSPO resource hub and open community of
practitioners who aim to create and share knowledge and collaborate on
practices, tools, and other ways to run successful and effective OSPOs
or similar open source initiatives. It was formed by its 1,700+
community participants and 80+ general members across different
sectors and regions and managed as an open source project under The
Linux Foundation. The TODO Group offers a maturity model, set of

guides, mind map, 101 course, annual surveys, and case studies to help
organizations advance in their OSPO journey. These OSPO resources are
developed by the TODO Group in collaboration with The Linux Foundation
and the larger open source community. If you are looking to establish
an OSPO in your organization, or you lead an OSPO and are looking to
connect with peers at other organizations, please visit
todogroup.org/community to get started and join our Slack channel or
OSPO forum discussions.

### Conclusion

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

# Acknowledgments Feedback

The author would like to express his sincere appreciation to his Linux
The author apologizes in advance for any spelling mistakes or possible
Foundation and TODO Group colleagues, Chris Aniszczyk, Hilary Carter,
errors and is grateful to receive corrections and suggestions for

Ana Jimenez, Jason Perlow, Melissa Schmidt, and Barry Hall, for their
improvements via
[[ibrahimatlinux.com/contact.html]{.underline}](http://www.ibrahimatlinux.com/contact.html).
valuable reviews and feedback. This report has benefited immensely

from their experiences and contributions.

# Linux Foundation Resources

- [[E-book: Guide to Enterprise Open
  Source]{.underline}](https://linuxfoundation.org/tools/guide-to-enterprise-open-source/)

- [[E-book: Open Source Compliance in the
  Enterprise]{.underline}](https://www.linuxfoundation.org/publications/open-source-compliance-enterprise/)

- [[E-book: Open Source Audits in Merger and
  Acquisition]{.underline}](https://www.linuxfoundation.org/resources/open-source-audits-merger-acquisition-transactions/)
  [[Transactions]{.underline}](https://www.linuxfoundation.org/resources/open-source-audits-merger-acquisition-transactions/)

- [[Linux Foundation Enterprise
  Guides]{.underline}](https://www.linuxfoundation.org/resources/open-source-guides/)

- [[Linux Foundation Open Compliance
  Program]{.underline}](https://compliance.linuxfoundation.org/) ---
  Resources to support organizations with open source compliance.

- [[TODO Group](http://todogroup.org/)]{.underline} --- Open community
  of practitioners and organizations that collaborate on best
  practices, tools, and other ways to run successful open source
  programs.

# About the Author

![](media/image54.jpeg){width="1.3351246719160106in"
height="2.01665791776028in"}Dr. Ibrahim Haddad is Vice President of
Strategic Programs at The Linux Foundation and the General Manager of
LF AI & Data, which provides a trusted hub for developers to code,
manage, and scale critical open source artificial intelligence and
data projects. Before The Linux Foundation, he served as Vice
President of R&D and Head of the Open Source Division at Samsung
Electronics. Throughout his career, Haddad held technology and
portfolio management roles at Ericsson Research, the Open Source
Development Labs, Motorola, Palm, Hewlett-Packard, and The Linux
Foundation. He graduated with honors from Concordia University
(Montréal, Canada) with a Ph.D. in Computer Science.

**Twitter:** \@IbrahimAtLinux

**Website:** IbrahimAtLinux.com

# Disclaimer

This report is provided "as is." The Linux Foundation and its authors,
contributors, and sponsors expressly disclaim any warranties (express,
implied, or otherwise), including implied warranties of
merchantability, noninfringement, fitness for a particular purpose, or
title, related to this report. In no event will The Linux Foundation
and its authors, contributors, and sponsors be liable to any other
party for lost profits or any form of indirect, special, incidental,
or consequential damages of any character from any causes of action of
any kind with respect to this report, whether based on breach of
contract, tort (including negligence), or otherwise, and whether they
have been advised of the possibility of such damage. Sponsorship of
the creation of this report does not constitute an endorsement of its
findings by any of its sponsors.

![](media/image1.jpeg)

Founded in 2021, [Linux Foundation Research]{.underline} explores the
growing scale of open source collaboration, providing insight into
emerging technology trends, best practices, and the global impact of
open source projects. Through leveraging project databases and
networks, and a commitment to best practices in quantitative

and qualitative methodologies, Linux Foundation Research is creating
the go to repository for open source insights for the benefit of
organizations the world over.

[twitter.com/linuxfoundation](https://twitter.com/linuxfoundation)
facebook.com/TheLinuxFoundation [linkedin.com/company/the linux
foundation](https://inkedin.com/) youtube.com/user/TheLinuxFoundation

Part of The Linux Foundation, LF AI & Data supports open source
innovation in artificial intelligence, machine learning, deep
learning, and data. LF AI & Data was established to support a
sustainable open source AI ecosystem that makes it easy to create AI
and data products and services using open source technologies. We
foster collaboration under a neutral environment with an open
governance model to support the harmonization and acceleration of open
source technical projects.

[[TODO]{.underline}](https://todogroup.org/) is an open group of 70+
organizations with years of experience running open source programs
that want to collaborate on practices, tools, and other ways to run
successful and effective open source projects and programs. It is a
place to share experiences, develop best practices and guidance as
well as work on common tooling to improve OSPO adoption and education
worldwide across sectors. Discover more about all the ongoing TODO
Initiatives [[here]{.underline}](https://github.com/todogroup) and
check out the OSPO landscape:
[[https://landscape.todogroup.org]{.underline}](https://landscape.todogroup.org/)

twitter.com/todogroup facebook.com/todo
linkedin.com/company/todo-group

Copyright © 2022 [[The Linux
Foundation]{.underline}](https://www.linuxfoundation.org/)

This report is licensed under the [Creative Commons
Attribution-NoDerivatives 4.0 International Public
License]{.underline}. This material may be copied and distributed
under the terms of the Creative Commons license.

To reference the work, please cite as follows: Ibrahim Haddad, "**A
Deep Dive Into Open Source Program Offices: Structure, Roles,
Responsibilities, and Challenges** " foreword by Chris Aniszczyk,
August, 2022.
