# Storage Expansion Simplified
# 揭秘 Kubernetes 系列: 理解简化存储扩展
Greetings, Kubernetes Community! Remember the days of scrambling to migrate data and rebuild entire Kubernetes deployments just to increase storage capacity? Those days are officially over, thanks to the volume expansion feature in Kubernetes. Today, I’m excited to delve into a storage expansion in our Kubernetes ecosystem by **Simplifying Storage Volume Expansion**.

你好，Kubernetes 社区！还记得仅仅为增加存储容量而争分夺秒匆忙迁移数据和重建整个 Kubernetes 部署调度的日子吗？由于 Kubernetes 中的卷扩展功能，那些日子正式结束了。今天我异常兴奋，将通过简化存储卷扩展这项功能深入探讨Kubernetes生态系统中的存储扩展。

## What is the Volume Expansion Feature?
## 什么是卷扩展功能？
In simpler terms, you can now dynamically grow the size of existing persistent volumes (PVs) without downtime or data loss. Simply edit your persistent volume claim (PVC) specification to request a larger size, and Kubernetes will handle the rest, seamlessly expanding the underlying storage and filesystem with minimal disruption.
简单来说，你现在可以动态增大现有的持久卷（PV）的大小，而无需停机或数据丢失。简单编辑你的持久卷声明（PVC）规范以请求更大的大小，Kubernetes 将处理其余的工作，以最小化中断来无缝扩展底层存储和文件系统。

## Understanding the Impact
## 理解影响
Imagine trying to enlarge a suitcase without unpacking it – that’s how we used to expand storage in live systems. But now, Kubernetes has introduced a seamless way to increase storage volume on-the-fly, without any system downtime. This translates to enhanced adaptability, smarter resource utilization, and continuous service delivery to our clients.
想象一下在不拆包的情况下放大一个手提箱 - 这就是我们过去在线上系统中扩展存储的方式。但现在，Kubernetes已经引入了一种无缝增加存储容量的方法，无需任何系统停机。这意味着增强的适应性、更智能的资源利用以及对客户的持续服务交付。

## Why is This a Big Deal?
## 为什么这很重要？
It’s a beneficial feature for several reasons:
这是一个有益的功能，原因如下：

 - **Agility and Efficiency**: No more clunky migrations or disruptive downtime. Grow your storage capacity on-demand as your needs evolve.
 - **Cost Optimization**: Eliminate the need for additional PVs, allowing you to make the most of your existing storage resources.
 - **Improved Management**: Streamline operations by avoiding complex data movements and ensuring data consistency throughout the expansion process.
 - **Peace of Mind**: Say goodbye to storage-related panic attacks. Focus on building awesome applications knowing your data has room to breathe.

 - **敏捷性和效率**：不再有笨重的迁移或破坏性的停机。随着需求的变化，按需增加存储容量。
 - **成本优化**：消除了额外 PV 的需求，让你充分利用已有的存储资源。
 - **改进的管理**：通过避免复杂的数据移动并确保扩展过程中的数据一致性，来简化操作。
 - **放心**：向存储相关的致命袭击道声告别。专注于构建令人惊叹的应用程序，知道你的数据有空间可以呼吸。

## How Does it Work?
## 它是如何工作的？
The magic happens behind the scenes with Kubernetes orchestrating the following:
魔法发生于幕后的Kubernetes协调了如下的工作：

  1. **Storage Backend Expansion**: Kubernetes communicates with the underlying storage provider (e.g., AWS EBS, Ceph RBD) to increase the physical volume size.
  2. **Filesystem Resizing**: For supported filesystems (XFS, Ext3/4), Kubernetes automatically expands the filesystem within the Pod, making the additional storage immediately accessible.
  3. **Minimal Disruption**: If possible, the entire process happens online, meaning your applications experience minimal to no downtime.


  1. **存储后端扩展**：Kubernetes 与底层存储提供商（例如 AWS EBS、Ceph RBD）通信，以增加物理卷大小。
  2. **文件系统调整大小**：对于支持的文件系统（XFS、Ext3/4），Kubernetes 自动扩展 Pod 内的文件系统，使附加存储立即可访问。
  3. **最小中断**：如果可能，整个过程在线进行，意味着你的应用程序经历最小停机或压根没有停机。



Getting Started with Volume Expansion:
开始使用卷扩展：

 1. **Check Compatibility**: Ensure your Kubernetes version supports volume expansion (minimum v1.24) and confirm your storage provider’s compatibility.
 2. **Enable the Feature**: Set the **allowVolumeExpansion** field to **true** in your StorageClass definition.
 3. **Expand Your PVCs**: Simply edit your PVCs and specify the desired new size. Kubernetes will take care of the rest!
   
 1. **检查兼容性**：确保您的 Kubernetes 版本支持卷扩展（最低 v1.24），并确认你的存储提供商的兼容性。
 2. **启用功能**：在你的 StorageClass 定义中将 **allowVolumeExpansion** 字段设置为 **true**。
 3. **扩展PVC**：简单地编辑你的 PVC ，并指明所需的新大小。Kubernetes 将处理其余的事

## Beyond the Basics
## 进阶内容
While core functionality is impressive, keep in mind some additional points:

核心功能令人印象深刻，同时请记住一些额外的要点：

  - **Offline Expansion**: For unsupported filesystems or complex scenarios, a temporary Pod restart might be needed for offline expansion.
  - **Shrinking Not Supported**: Currently, volume expansion only works for growing, not shrinking, your storage.
  - **Cluster Admin Control**: Cluster admins have the power to grant or restrict volume expansion capabilities for specific StorageClasses and users.

  - **离线扩展**：对于不支持的文件系统或复杂情况，可能需要临时 Pod 重新启动进行离线扩展。
  - **不支持缩小**：目前，卷扩展仅适用于增大存储容量，不适用于缩小存储容量。
  - **集群管理员控制**：集群管理员可以授予或限制特定 StorageClasses 和用户的卷扩展能力。
  
The volume expansion is a nice feature in Kubernetes storage management. With the ability to easily resize volumes on-demand, you can now manage your storage resources with greater agility, efficiency and peace of mind. So, go forth and build with confidence, knowing your data has the space to grow alongside your ambitions!
卷扩展是 Kubernetes 存储管理中的一个不错的功能。通过轻松调整卷大小的能力，你现在能够以更大的灵活性、效率和来放心管理你的存储资源。所以，继续前进，并充满信心地构建你的软件，知道数据有足够的空间可以与你的雄心一起成长！

Stay tuned for further posts delving deeper into specific use cases, technical implementation details and best practices for leveraging this powerful feature!
请继续关注更多深入探讨特定用例、技术实现细节和最佳实践的文章，以便利用这个强大的功能！

**Read more posts from the Unraveling Kubernetes series ([Part 1](https://training.linuxfoundation.org/blog/unraveling-kubernetes/) & [Part 2](https://training.linuxfoundation.org/blog/unraveling-kubernetes/)])** and stay tuned for further posts delving deeper into specific use cases, technical implementation details and best practices for leveraging Kubernetes!

**阅读更多来之Kubernetes解密系列，点击((系列一 理解 Kubernetes 中 Runtime 与 RuntimeClass 的关键区别)[https://mp.weixin.qq.com/s/lTeq5LRIh4VkxaySMtnx9Q]((系列二 理解 Kubernetes 中 Runtime 与 RuntimeClass 的关键区别)[https://mp.weixin.qq.com/s/YJDlbVPY-VYJONd8WDxauQ]))**，和敬请期待更多博客深入分析应用Kubernetes的特别用例，技术实现细节和最佳实践。

By: Fazlur Rahman Khan

CKA, CKS, CKAD, KCNA

Technical Trainer, Linux Foundation

作者：Fazlur Rahman Khan

CKA, CKS, CKAD, KCNA

Liunx 基金会，技术培训师

翻译：赵梅 
校对：马冬梅
