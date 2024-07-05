# Understanding Probes to Ensure Application Health and Reliability

Greetings, Kubernetes Community! Probes in Kubernetes are diagnostic tools used to determine the status of a container within a pod. They help Kubernetes make decisions about container management based on the health of the running containers. They play a vital role in ensuring the smooth operation of applications in Kubernetes. Correctly configuring these probes according to the specific needs of your application enhances stability and reliability in your Kubernetes environment. Let’s discuss why these probes are so crucial.

# 理解确保应用程序的健康和可靠性的探针

你好，Kubernetes 社区！Kubernetes 中的探针是用于确定 Pod 中容器的状态的诊断工具。它们帮助 Kubernetes 根据运行容器的健康状况做出容器管理决策。它们在确保 Kubernetes 中应用程序平稳运行方面发挥着重要作用。根据应用程序的特定需求正确配置这些探针可以增强 Kubernetes 环境的稳定性和可靠性。让我们讨论一下为什么这些探针如此重要。

## Key Aspects of Probes in Kubernetes

Let’s explore their benefits.

- **Increased uptime and reliability**: By restarting unhealthy pods quickly, probes ensure your applications are always available and responsive.
- **Improved resource utilization**: By preventing traffic from reaching unready pods, probes free up resources for healthy ones, optimizing your cluster’s performance.
- **Faster scaling**: With accurate health information, Kubernetes can make informed decisions about scaling your applications up or down based, on actual demand.
- **Simplified troubleshooting**: Probes provide valuable insights into your application’s health, making it easier to diagnose and fix issues.

## Kubernetes 中探针的关键优势

让我们探索它们的好处：

- **提高正常运行时间和可靠性：** 通过快速重新启动不健康的 Pod，探针确保您的应用程序始终可用和可响应。
- **改善资源利用率：** 通过阻止流量到达未就绪的 Pod，探针为健康的 Pod 释放资源，优化集群的性能。
- **更快的扩展：** 凭借准确的健康信息，Kubernetes 可以根据实际需求做出关于扩缩应用程序的决策。
- **简化故障排除：** 探针为您的应用程序健康提供了宝贵的见解，使诊断和解决问题变得更加容易。

## Types of Probes

- **Liveness Probes**: Determines if a container is running properly. If a liveness probe fails, Kubernetes will restart the container.
- **Readiness Probes**: Checks if a container is ready to serve requests. If a readiness probe fails, Kubernetes will stop routing traffic to the pod until it passes.
- **Startup Probes**: Used for containers that take a long time to start. If a startup probe is configured, liveness and readiness checks are disabled until it succeeds, ensuring the application has enough time to start up.

Let’s look at the probes with the help of an example, by imagining a bustling restaurant during peak hour.

## 探针类型

- **存活探针：** 确定容器是否正常运行。如果存活探针失败，Kubernetes 将重新启动容器。
- **就绪探针：** 检查容器是否准备好提供服务。如果就绪探针失败，Kubernetes 将停止将流量路由到该 Pod，直到它通过为止。
- **启动探针：** 用于需要较长时间启动的容器。如果配置了启动探针，存活和就绪检查将在其成功之前被禁用，确保应用有足够的时间启动。

让我们通过一个例子来看看探针的作用，想象一家在高峰时段繁忙的餐厅。

### 1. Readiness Probe – The Maitre D’s Checklist

- Imagine the maitre d’ as the readiness probe. Their job is to ensure a table is clean and ready for guests before seating them. This translates to checking if the application within the container (think of it as the kitchen) is fully prepared to handle incoming traffic.
- The probe could involve one or more of the following:
  - Verifying if the web server is listening on the correct port
  - Testing database connectivity
  - Confirming that key services are up and running
- If any of these checks fail, the maitre d’ informs the host (Kubernetes) that the table isn’t ready (application not ready). The host then delays sending new customers (traffic) until the table is prepared. This prevents frustrated diners (unhappy users) from receiving incomplete or slow service.

### 1. 就绪探针 - 餐厅服务员的清单

- 想象餐厅服务员就像就绪探针一样。他们的工作是在客人入座之前确保餐桌干净整洁。这可以理解为检查容器内的应用程序（就像是厨房）是否完全准备好处理传入的流量。
- 就绪探针可能涉及以下一项或多项工作：
  - 验证 Web 服务器是否在正确的端口上监听；
  - 测试数据库连接性；
  - 确认关键服务是否已经启动运行。
- 如果这些检查中有任何一项失败，餐厅服务员会通知主人（Kubernetes）餐桌还没有准备好（应用程序还没有准备好）。主人会延迟发送新的顾客（流量），直到餐桌准备好。这样就可以避免让沮丧的用餐者（不满意的用户）收到不完整或者缓慢的服务。

### 2. Liveness Probe – The Kitchen Manager’s Patrol

- Picture the kitchen manager as the liveness probe. They constantly walk around the kitchen to ensure everything is running smoothly and food is being prepared safely.
- This translates to checking if the application within the container is still alive and functioning properly.
- The probe could involve one or more of the following:
  - Testing the health of the running processes
  - Monitoring resource utilization (CPU, memory)
  - Checking for errors or crashes
- If the manager finds any problems, they alert the staff (Kubernetes) that the kitchen is having issues (application crash). The staff then reboots the container (restarting the application) to get things back on track. This ensures diners (users) don’t encounter a closed kitchen (unresponsive application).

### 2. 存活探针 - 厨房经理的巡视

- 想象一下厨房经理就是存活探针。他们不断地在厨房里走动，确保一切运行顺利，食物被安全地准备着。
- 这相当于检查容器内的应用程序是否仍然活着并且正常运行。
- 探针可能涉及以下一项或多项工作：
    - 测试正在运行的进程的健康状况；
    - 监控资源利用率（CPU、内存）；
    - 检查错误或崩溃情况。
- 如果经理发现任何问题，他们会警告员工（Kubernetes）厨房出现问题（应用程序崩溃）。然后工作人员会重新启动容器（重新启动应用程序）以使一切恢复正常。这样可以确保用餐者（用户）不会遇到关闭的厨房（无响应的应用程序）。

### 3. Startup Probe – The Chef’s Warm-up Time

- Think of the chef preheating the oven as the startup probe. They need some time to get the kitchen properly heated before taking on orders.
- This translates to giving the application within the container enough time to initialize and start up services before expecting it to handle traffic.
- The probe could involve one or more of the following:
  - Waiting for a specific application process to become active
  - Checking for successful database connection establishment
  - Verifying resource availability after initial setup
- Only after the pre-heating (startup) is complete does the kitchen accept orders (traffic is routed to the container). This avoids sending requests to a half-prepared kitchen (slow or incomplete application response).

By using these three probes like dedicated restaurant staff, you can ensure your applications in Kubernetes are always ready to serve delicious experiences to your users, avoiding indigestion (frustration) from incomplete or unavailable services.

### 3. 启动探针 - 厨师的预热时间

- 把厨师预热烤箱想象成启动探针。他们需要一些时间来让厨房适当地加热，然后才能接受订单。
- 这意味着在期望容器中的应用处理流量之前，需要给予足够的时间来初始化和启动服务。
- 探针可能涉及以下一项或多项操作：
  - 等待特定应用程序进程变为活动状态；
  - 检查成功建立数据库连接；
  - 验证初始设置后资源的可用性。
- 只有在预热（启动）完成后，厨房才会接受订单（流量被路由到容器）。这样可以避免向半准备好的厨房发送请求（应用响应缓慢或不完整）。

通过使用这三个探针，就像专门的餐厅员工一样，您可以确保您在 Kubernetes 中的应用程序随时准备好为用户提供美味的体验，避免因服务不完整或不可用而引起的不愉快（沮丧）。

## Additional Points to Consider

- Probes can be configured using various methods, including YAML files and annotations.
- Different types of probes (HTTP, exec, TCP) are available to suit your application’s needs.
- You can fine-tune probe behavior by setting parameters like failure thresholds and intervals.

By mastering the art of probes, you can build resilient and reliable applications that thrive within the bustling kingdom of Kubernetes.

I hope this blog post clarifies the role of probes in Kubernetes and empowers you to leverage them for seamless application usage!

**Read the first part in the Unraveling Kubernetes series [here](https://training.linuxfoundation.org/blog/unraveling-kubernetes/)** and stay tuned for further posts delving deeper into specific use cases, technical implementation details and best practices for leveraging Kubernetes!

## 其他注意事项

- 探针可以通过各种方法进行配置，包括使用YAML文件和注释。
- 不同类型的探针（HTTP、exec、TCP）可供选择，以满足应用程序的需求。
- 您可以通过设置失败阈值和间隔等参数来微调探针的行为。

通过掌握探针的艺术，您可以构建在 Kubernetes 繁忙王国中蓬勃发展的弹性和可靠的应用程序。

希望这篇博客文章能够澄清 Kubernetes 中探针的作用，并使您能够充分利用它们来实现无缝的应用程序使用！

**阅读[《揭秘 Kubernetes 系列》的第一部分](https://training.linuxfoundation.org/blog/unraveling-kubernetes/)**，并继续关注更深入探讨特定用例、技术实施细节和利用 Kubernetes 的最佳实践的进一步文章！

---

**Grow Your Kubernetes Skill Set — Enroll Today!**

LIVE, Instructor-led [Kubernetes for Developers (LFD459)](https://training.linuxfoundation.org/training/kubernetes-for-app-developers/)

or

Self-paced, e-Learning [Kubernetes for Developers (LFD259) ](https://training.linuxfoundation.org/training/kubernetes-for-developers/)

---

---

**提升你的 Kubernetes 技能 - 立即报名！**

直播，讲师主讲的 [Kubernetes for Developers (LFD459)](https://training.linuxfoundation.org/training/kubernetes-for-app-developers/)

或者

自主学习，线上学习的 [Kubernetes for Developers (LFD259) ](https://training.linuxfoundation.org/training/kubernetes-for-developers/)

---


By: Fazlur Rahman Khan

CKA, CKS, CKAD, KCNA

Technical Trainer, Linux Foundation

作者：Fazlur Rahman Khan

CKA, CKS, CKAD, KCNA

Liunx 基金会，技术培训师

