# Employ a GitHub Security Posture to Overcome Common Cyber Threats 
# 采用GitHub安全立场来克服常见的网络威胁 

October 20, 2022
2022年10月20日
 
GitHub is one of the most popular source-control systems in the world hosting over 83 million developers, 4 million organizations, and more than 200 million code repositories. Yet, for all its versatility and strengths, it was not initially built with securing code in mind – its main objective is to help facilitate collaboration and cooperation between developers, both in the same organization and between different organizations. That said, you definitely can secure your projects on GitHub, but this will require some awareness, and a little more elbow grease on your behalf.
[GitHub](https://github.com/)是世界上最受欢迎的源代码控制系统之一，拥有超过8300万开发者、400万组织和超过2亿个代码存储库。然而，尽管它具有通用性和各种优势，但在最初构建时并没有考虑到保护代码——它的主要目标是促进同一组织内以及不同组织间开发者之间的协同与合作。也就是说，你绝对可以在GitHub上保护你的项目，但这需要一定的意识，同时还需要为你费点功夫。

There are several platform functions that you want to be aware of as you assess the security of your code on GitHub:
在评估GitHub上代码的安全性时，你要了解平台的以下几个功能：

Public repositories – sometimes we unintentionally place secret information (likes keys, secrets, or proprietary code) in a public repository. We need to remember that anyone on the internet can clone and fork such a repository so you might be inadvertently hosting other people on your AWS S3. And paying for it.
**公共存储库**——有时我们无意中将秘密信息（如密钥、机密或专有代码）放在[公共存储库](https://www.theverge.com/2019/5/6/18531222/hacker-data-theft-ransom-stolen-git-code-bitcoin)中。我们需要记住，互联网上的任何人都可以克隆和复制这样的存储库，因此你可能不经意间就在你的AWS S3上托管了其他人，并为此买单。

Unprotected branches – GitHub has a feature that allows you to add various protections to selected (usually your main) branches. These protections range from mandating signed commits to maintaining linear commit history. It’s a useful tool that makes your main branch much more resilient to potential attacks.
**不受保护的分支**——GitHub有一项功能，它允许你向选定的（通常是你的主）分支添加各种保护。这些保护范围从强制签名提交到维护线性提交历史。这是一个有用的工具，可以让你的主分支对潜在的攻击更具弹性。

Signed commits – It is shockingly easy to impersonate a person on GitHub. All you need is their email and user handle. With this, anyone can pretend to be anyone when pushing a commit to your repository. Signed commits include – you guessed it – an electronic signature that helps determine if the committer is verified. That means that you can follow the commit history with more certainty that what you see is real and not a smokescreen put in place to obfuscate the truth of a malicious commit.
**签名提交**——[在GitHub上冒充一个人](https://dev.to/agrinman/spoof-a-commit-on-github-from-anyone-4gf4)非常容易。你只需要有他们的电子邮件地址和用户句柄。有了这个，任何人都可以在推送提交到你的存储库时假装是别人。签名提交包括——你猜对了——一个有助于确定提交者是否经过验证的电子签名。这意味着你可以跟踪提交历史，更加确信你所看到的都是真实的，而不是为了混淆恶意提交的真相而设置的障眼法。

Two-factor authentication – you can require that all members of an organization use 2FA. It’s a helpful security measure designed to make it harder to steal accounts and infiltrate an organization with it.   
**双重身份验证** ——你可以要求组织的所有成员都使用2FA。这是一种有用的安全措施，旨在使[窃取帐户](https://www.bleepingcomputer.com/news/security/hackers-stealing-github-accounts-using-fake-circleci-notifications/)和渗透到组织中变得更加困难。

SSH and Deploy keys – both these types of keys are there to make it easier to connect to your GitHub account. Unfortunately what is meant to be easy for you is also easy for cybercriminals. It’s much too easy to forget to rotate your keys or to share them with the wrong people. Remember that these keys represent almost unfettered access to your account and you should protect them just like any other Secret.
**SSH和部署密钥**——这两种类型的密钥都可以让你更轻松地连接到你的GitHub帐户。不幸的是，对你来说容易的事情对网络犯罪分子来说也很容易。忘记定期更换密钥或与错误的人共享密钥太容易发生了。请记住，这些密钥代表着几乎可以不受限制地访问你的帐户，你应该像保护任何其他秘密一样保护它们。

Having too many Admins – Admin permission on GitHub is considered by a lot of people to be a sort of silver bullet to handle almost any access issue. The problem is that you end up with teams in which almost every member is an Admin. Since Admins have almost full access to the account and can usually make far-reaching (not always welcome) changes, you should pick and choose your Admins with more care. Also, be sure to revoke Admin access if it is no longer required. 
**管理员过多**——很多人认为GitHub的管理员权限是处理几乎所有访问问题的灵丹妙药。问题是你最终将拥有一个几乎每个成员都是管理员的团队。由于管理员几乎可以完全访问该帐户，并且通常可以进行影响深远（并非总是受欢迎）的更改，因此你应该更加谨慎地选择你的管理员。此外，如果不再需要，请务必撤消管理员访问权限。

The bottom line is that your code on GitHub is only as secure as you make it. Do not trust the platform to do it for you. Invest some time and energy in to reading the GitHub documentation before you decide what steps, if any, you need to take in order to protect your repositories.
最重要的是，你在GitHub上的代码仅与你创建的代码一样安全。不要相信平台会为你做这件事。在决定需要采取哪些步骤（如果有）来保护你的存储库之前，请花一些时间和精力阅读GitHub文档。

Contributed by Barak Brudo, Developer Advocate at Scribe. 
本文由[Scribe](https://scribesecurity.com/)的开发者维护者Barak Brudo提供。

# Developer Portals Made Easy: Learn Backstage to Gain Control of Your Development Ecosystem 
# 开发者门户变得简单：学习用后台控制你的开发生态系统 

October 25, 2022
2022年10月25日
 
Backstage is a new open source platform for building developer portals developed in-house at Spotify and donated to the Cloud Native Computing Foundation for incubation. In a nutshell, Backstage unifies all your infrastructure tooling, services, and documentation to create a streamlined development environment from end to end. Developer portals like Backstage can help teams reduce tech fragmentation, knowledge silos, and lack of ownership while promoting creativity and autonomy. 
[Backstage](https://backstage.io/)是一个新的开源平台，用于构建Spotify内部开发的开发者门户，并已捐赠给云原生计算基金会进行孵化。简而言之，Backstage统一了你的所有基础设施工具、服务和文档，以创建端到端的简化开发环境。Backstage等开发者门户网站可以帮助团队减少技术碎片化、知识孤岛和缺乏所有权，同时促进创造力和自主权。

Our new course, Introduction to Backstage: Developer Portals Made Easy (LFS142x), is designed for DevOps engineers and professionals interested in or working in Developer Productivity or Developer Experience teams. 
我们的新课程，[**后台简介：开发者门户变得简单 (LFS142x)**](https://www.edx.org/course/introduction-to-backstage-developer-portals-made-easy?utm_medium=partner-marketing&utm_source=social&utm_campaign=lftraining&utm_content=blog-lf142x)，专为对开发者生产力或开发者体验团队感兴趣或在其中工作的开发运维工程师和专业人士而设计。

The course starts with a discussion on developer portals, arguing in favor of implementing one in your organization. It then goes on to discuss Backstage, the leading open source framework for creating developer portals, covering the architecture and features (Catalog, Scaffolder, TechDocs, and Plugins). The curriculum then goes over running Backstage both locally and in production and helps you map your organization’s needs to what Backstage has to offer. Last but not least, you will learn how you can get involved and contribute to the Backstage project.
本课程首先讨论开发者门户，支持在你的组织中实现一个门户。然后，继续讨论Backstage，这是用于创建开发者门户的领先开源框架，涵盖架构和功能（Catalog、Scaffolder、TechDocs和Plugins）。接着，该课程将重新讨论在本地和生产环境中运行Backstage，并帮助你将组织的需求映射到Backstage必须提供的内容。最后但同样重要的是，你将了解如何参与并为Backstage项目做贡献。

This online, self-paced course features hands-on labs & assignments, and discussion forums to help you in your learning. While the course is free and accessible for ten weeks after registration, you may also opt to pay for a certificate of completion.
此在线自定进度课程以动手实验、作业和用于帮助你学习的论坛为特色。虽然该课程在注册后十周内可免费访问，但你也可以选择付费获得结业证书。

The course author, Jorge Lainfiesta, is a Technical Marketing Manager at roadie.io. Lainfiesta has a background in software engineering (PayPal) and digital communication (UCLA). He’s been working around Backstage since it was open sourced by Spotify and co-hosts community initiatives like the Backstage Users Unconference. 
课程作者Jorge Lainfiesta是roadie.io的技术营销经理。Lainfiesta拥有软件工程 (PayPal) 和数字通信 (UCLA) 的背景。自从Backstage由Spotify开源以来，他一直在围绕Backstage工作，并共同主持了Backstage Users Unconference等社区活动。

Register today and get started learning Backstage for a more streamlined development ecosystem. 
[立即注册](https://www.edx.org/course/introduction-to-backstage-developer-portals-made-easy?utm_medium=partner-marketing&utm_source=social&utm_campaign=lftraining&utm_content=blog-lf142x)并开始学习Backstage，以获得更精简的开发生态系统。

# Use GitGat to Secure your GitHub Supply Chain 
# 使用GitGat保护你的GitHub供应链 

October 25, 2022
2022年10月25日
 
GitHub is one of the most popular SCM (source control management) systems in the world and is used by millions of open source developers. Take your first steps in learning to secure your GitHub repositories with GitGat. Learning to properly protect the SCM is an essential step towards securing the software supply chain, and specifically – securing your code. 
GitHub是世界上最流行的SCM（源代码控制管理）系统之一，被数百万开源开发者使用。迈出学习使用GitGat保护GitHub存储库的第一步。学习正确保护SCM是保护软件供应链的重要一步，特别是——保护你的代码。

In this new course, GitHub Supply Chain Security Using GitGat (LFD122x), you will gain an understanding of these categories, why they are important, and how to implement the security controls in GitHub. 
在[**GitHub供应链安全使用GitGat (LFD122x)**](https://www.edx.org/course/github-supply-chain-security-using-gitgat?utm_medium=partner-marketing&utm_source=social&utm_campaign=lftraining&utm_content=blog-lfd122x)这门新课程中，你将了解这些类别、它们为何重要以及如何在GitHub中实施安全控制。

Additionally, you will use the open source GitGat security report as a guide to the needed security steps and then see how to use GitGat to set a continuous security audit that takes the current state into account. Finally, we’ll peek under the hood to understand OPA (Open Policy Agent), GitGat’s underlying technology. 
此外，你将使用开源GitGat安全报告作为所需安全步骤的指南，然后了解如何使用GitGat设置考虑当前状态的持续安全审计。最后，我们将深入了解OPA（Open Policy Agent，开放代理），这是GitGat的底层技术。

The course is for anyone who has a GitHub account, manages repositories on GitHub, or is responsible for securing such repositories or accounts. The course could fit both hobbyists and professionals who manage GitHub organizations. In addition, the “under the hood” sections could interest developers wanting to learn more about Open Policy Agent-based projects.
本课程适用于拥有GitHub帐户、管理GitHub上的存储库或负责保护此类存储库或帐户的任何人。该课程适合爱好者和管理GitHub组织的专业人士。此外，“幕后”部分可能会让想要对基于OPA的项目有更多了解的开发者感兴趣。

The course authors are Scribe Security’s Danny Nebenzahl and Barak Brudo. Nebenzahl is the Co-Founder and Chief Technology Officer at Scribe Security. He previously served as a Lieutenant Colonel in Matzov – the Israel Defense Forces cyber defense center – where he led the research division for over a decade and was responsible for developing innovative cyber technologies. Brudo is an ERP, and full-stack developer now turned DevRel. He has a B.Ed in art education, so he is uniquely qualified to pass on information in a clear and concise manner. 
课程作者是Scribe Security的Danny Nebenzahl和Barak Brudo。Nebenzahl是Scribe Security的联合创始人兼首席技术官。他之前曾在以色列国防军网络防御中心Matzov担任中校，在那里他领导了研究部门十多年，并负责开发创新的网络技术。Brudo是一名ERP和全栈开发者，现在已转为DevRel。他拥有艺术教育学士学位，因此具有以清晰简洁的方式传递信息的独特资格。

This new course is open to all for immediate enrollment. While the course is free and accessible for seven weeks after registration, you may also opt to pay for a certificate of completion. Visit the course landing page to learn more about the curriculum and how GitGat can keep your code secure.
这门新课程对所有人开放，可立即注册。虽然该课程在注册后七周内可免费访问，但你也可以选择付费获得结业证书。[访问课程登录页面](https://www.edx.org/course/github-supply-chain-security-using-gitgat?utm_medium=partner-marketing&utm_source=social&utm_campaign=lftraining&utm_content=blog-lfd122x)以了解有关课程的更多信息以及GitGat如何确保你的代码安全。
