Open source Kubernetes policy engine technology Kyverno has been certified for use and formalized with a new Kyverno Certified Associate (KCA) exam by the Cloud Native Computing Foundation at KubeCon + CloudNativeCon North America this month in Salt Lake City.
开源的 Kubernetes 策略引擎技术 Kyverno 已获得云原生计算基金会（CNCF）的使用认证，并随着在本月于盐湖城举办的 KubeCon + CloudNativeCon 北美大会上新推出的 Kyverno 认证助理（KCA）考试而进一步规范化。

Kyverno was created by security and governance specialist Nirmata and contributed to the CNCF in November 2020. It graduated as a CNCF Incubator in July 2022 and since then it has experienced nearly 10X growth in downloads and gained over 2,000 GitHub stars.
Kyverno由安全与治理专家Nirmata创建，并于2020年11月贡献给CNCF。2022年7月，它正式毕业成为CNCF孵化项目。自那时到目前，其下载量增长了近10倍，Github上的Star数超过了2000.

The technology works as a Kubernetes policy engine to validate, mutate and generate configurations, enabling the automation of security policies as code, beyond just audit and enforcement. As a result of its simplicity and range of features, Kyverno has been widely adopted by platform engineering teams that use Kubernetes as a composable platform for building Internal Developer Platforms (IDPs).
作为Kurbenetes的策略引擎技术，它能够验证，修改和生成配置，使安全策略作为代码得以自动化管理，超越了传统的审计和强制执行功能。因其简单性和功能丰富，使用 Kubernetes 作为构建内部开发者平台（IDP）的可组合平台的工程团队广泛采用了 Kyverno。

“Kyverno simplifies Kubernetes policy management and enhances security in cloud-native environments, making it a valuable tool for platform engineering teams,” said Chris Aniszczyk, CTO, of CNCF. “Kyverno being Kubernetes-native and having such prominent ease of use features – [especially] on top of its integration into CI/CD pipelines – has contributed to its widespread adoption in cloud-native projects.”
“Kyverno简化了Kubernetes策略管理，并在云原生环境中增强了安全性，是平台过程团队的宝贵工具，”CNCF的首席技术官Chris Aniszcyk表示，“Kyverno的Kubernetes原生性以及易用性，尤其是其在CI/CD流水线中的集成，使其在云原生项目中得到了广泛采用。"

**Admins, Ops & DevOps**
**管理员，运维和Devops**
Kyverno is designed to be used by Kubernetes administrators, operators and DevOps teams who are responsible for managing and maintaining Kubernetes clusters. It can be valuable in situations where policy management, resource validation and dynamic policy enforcement are required.
Kyverno专为负责管理和维护Kubernetes集群的Kubernetes管理员，运维人员和DevOps团队而设计。Kyverno在策略管理，资源验证和动态策略执行等场景中非常有价值。

Kyverno, which means “govern” in Greek, works to provide policies that can enforce best practices so that it can scan workloads and block, patch and mutate API requests to enforce them. Kyverno can check if resource specifications match predefined policies, including Open Container Initiative (OCI) container images, to help secure the software supply chain. The Kyverno Command Line Interface (CLI) can be used to test policies and validate resources as part of a CI/CD pipeline.
Kyverno在希腊语中的意思是”治理“，其功能旨在提供一套策略来实施最佳实践，从而扫描工作负载并阻止，修补或者修改API请求以强制执行策略。Kyverno能够检查资源规范是否符合预定义策略，包括Open Container Initiative(OCI)容器镜像，以帮助保护软件供应链。Kyverno的命令行界面(CLI)可以用于测试策略和验证资源，作为CI/CD流水线的一部分。

Kyverno policies can be managed as Kubernetes resources and “familiar tools” like kubectl, git and kustomize can be used, so users do not need to learn a new programming language. Kyverno can also create additional objects and resources. It allows users to build rules for their Kubernetes resources that can allow or deny the resource to be applied to a cluster. 
Kyverno策略可以作为Kubernetes资源进行管理，用户可以使用诸如kubectl，git和kustomize等熟悉的工具，而无需学习新的编程语言。此外，Kyverno还可以创建其他对象和资源，允许用户为其Kubernetes资源构建规则，以决定是否允许资源被应用到集群中。

**Kyverno Certified Associate (KCA)**
**Kyverno认证助理(KCA)**
“We are excited to launch the Kyverno Certified Associate (KCA) exam in partnership with the CNCF and Linux Foundation Education. Kubernetes runs mission-critical workloads across all major verticals and Kyverno has become an indispensable tool with its ability to automate security and operations with policy as code,” says Jim Bugwadia, Nirmata co-founder and CEO. “ With this certification, Kubernetes administrators will be able to assess their expertise in Kyverno and prove their ability to address key use cases for their organizations.
Nirmata联合创始人兼首席执行官Jim Bugwadia表示，"我们很高兴与CNCF和Linux基金会教育联合推出Kyverno认证助理(KCA)考试。Kubernetes 在所有主要行业都承载着关键工作负载，而 Kyverno 凭借其将策略作为代码来实现安全和操作自动化的能力，已成为不可或缺的工具。通过这一认证，Kubernetes管理员将能够评估其在Kyverno上的专业知识，并证明其为组织解决关键用例的能力."

Kyverno secures software supply chains by automating security, compliance and best practices validation. It can verify container images and metadata, allowing teams to create an allowed list of approved base images for constructing containers. Additionally, Kyverno tailors security configurations with fine-grained pod security controls, offering flexibility to exempt specific controls within a pod security profile.
Kyverno通过自动化安全，合规性和最佳实践验证来保护软件供应链。它可以验证容器镜像和元数据，帮助团队创建一份允许的基础镜像列表，用于构建容器。此外，Kyverno还提供细粒度的Pod安全控制，允许灵活地在Pod安全配置文件汇总豁免特别控制。

**Streamlined DevSecOps Workflows**
**简化的DevSecOps工作流**
According to the CNCF project maintainer team, Kyverno streamlines the DevSecOps workflow and security management in cloud-native environments by validating resources as part of the CI/CD pipeline, producing policy reports that show the results of policy decisions, and enforcing policies as a Kubernetes admission controller, CLI-based scanner, or at runtime.
根据CNCF项目维护团队的说法，Kyverno在云原生环境中通过以下方式简化了DevSpecOps龚总流和安全管理：
- 在CI/CD流水线中验证资源
- 生成显示策略决策结果的策略报告
- 作为Kubernetes的准入控制器，基于CLI的扫描工具或者运行时组件强制执行策略。

“Earning a Kyverno certification can enhance knowledge of Kubernetes policy management and demonstrate the ability to handle security, compliance and operational aspects of cloud-native projects. The education required for the certification will help [engineers] learn how to create, apply and manage Kyverno policies, while also building professional credibility and standing out from the competition. Additionally, certification prepares you for roles such as Kubernetes security specialist, DevSecOps engineer, or Kubernetes administrator,” notes the CNCF.
CNCF表示，”获得Kyverno认证可以提高duiKubernetes策略管理的理解，并展示处理云原生项目安全，合规和运营方面的能力。为通过认证所需的学习将帮助工程师掌握创建，应用和管理Kyverno策略的技能，同时建立职业信誉，在竞争中脱颖而出。此外，认证还为从事Kubernetes安全专家，DevSpecOps工程师或Kubernetes管理员等角色做好准备。”

CNCF with Linux Foundation Education currently offers one Kyverno-specific course, Mastering Kubernetes Security with Kyverno (LFS255) and KubeCon + CloudNativeCon 2024 also saw the launch of the Kyverno Certified Associate (KCA). 
CNCF与Linux基金会教育目前提供一门专注于Kyverno的课程《运用 Kyverno 掌握 Kubernetes 安全》(LFS255),并在KubeCon+CloudNativeCon 2024上发布了Kyverno认证助理(KCA)考试。

Author: Adrian Bridgwater
作者：Adrian Bridgwater
翻译: 赵梅
原文链接： https://cloudnativenow.com/topics/cloudnativedevelopment/application-dev/cncf-automates-kubernetes-secops-with-kyverno/ 

