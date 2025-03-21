# 技术债务

## 定义

技术债务，在软件开发中的定义有点类似于现实世界的经济债务，指的是维护源代码的成本，这些成本主要是由偏离了联合（joint ）开发的主分支引起的。其实，这个词在专有代码中有着更为广泛的解释：

* 由单一的组织所开发
* 源代码的服务和维护主要由这个组织独自承担
* 在某些情况下，组织依赖于合作伙伴维护代码并承担所述债务的能力。

这里需要先澄清一个事实，上游代码也会有技术债务的，尤其是当上游项目没有资源/时间通过其开发者社区维护自身时。这种情况的一个案例是 OpenSSL 项目，很多公司都严重依赖于这个项目，但是并没有亲力亲为的参与到这个项目，然而当出了问题时才发现这么重要的项目竟然是仅仅只有一个人在业余时间进行维护。当然，由于正是这个案例的发生，促使 Linux 基金会发起了 Core Infrastructure Initiative ，以支持至关重要的现代核心基础设施开源项目。

## 技术债务的外在表现

我们通常是如何识别那些技术债务的？它们有什么明显的表现吗？在这个小节中，笔者根据自身的经验，就将这些技术债务一一列出，并将它们的外在表现描述一番。以下所列并没有覆盖所有技术债务相关的详尽清单，而是笔者认为的最为常见的，也是被很多人所观察到的技术债务外在表现。

* **较慢的发布节奏** 新的功能交付周期变长。
* **新人参与的时间变久** ：首要的表现是新来的开发者非常难以参与到项目中，而只有内部开发人员熟悉代码的复杂性；第二种表现则是，老员工留不住，又招不来新员工。
* **安全方面的问题增加**：相比于上游项目，遇到了更多的安全问题。
* **投入代码库的力度加大**：随着要维护的代码体量变得更大、更复杂，维护任务变得更加耗时。
* **与上游渐行渐远**：无法与上游开发、发布周期保持同步和一致。

## 技术债务的类型

（有关开源的）技术债务类型，并没有一个标准，或者形成普遍的共识，当然也就没有现成的定义，这个任务需要我们自己来完成。

### 临时技术债务

这里假设是一个正在正在开发的团队，基于上游开源项目做一些研究，可能涉及多个组件、多个系统/子系统等复杂的功能。随着项目的进度，开始有了一些没有和上游进行整合的技术债务，此时，团队里的人也意识到了这些，也明白自己已经欠了债务，然而，由于赶着上市，团队最终的决策是先将这些债务暂时搁置一旁，不予理会，并承诺在将来再去做和上游合并的事。

### 未知的技术债务

由于不良的工程实践，在无形中产生的技术债务。这样的情况常见的例子：一段糟糕的代码并没有被上游接受，甚至也不适合在其它地方重复利用。那么这段代码就成了“弃之可惜，食之无味”的债务。

### 有目的地欠下了技术债务

更多的情况是开发者自己有意为之的。常见的情形是：一个开发团队基于上游项目开发了自己认为先进而独特的功能，然而并不想和上游以及整个开源共同体分享，于是，他们创建了自己的分支，而拒绝和上游合并。随着时间的推移，自行开发的fork版本也会不断累积，这就导致了更多的技术债务，相应的维护成本也在不断的增加。

### 过时的技术债务

这是一种较为独特的技术债务类型，主要是由于强调“自主可控”的执念，以及不想让更多人知道自己的开发所导致。 由于自身的封闭，以及缺乏技术监督，最后只有自己一家在使用这项实现。然而，开源世界在不断的迭代和进化，并优雅的解决了问题并成为了事实上的标准，但是和内部实现并不兼容。这种情况就是发展过时的技术债务的来由。

### 组织的技术债务

人们经常会讨论的一个话题是一家企业的代码和这家企业的组织是高度相关的（康威定律——译者注），这是一个非常有意思的现象。

在某些情况下，尤其是利用开源，会出现一些代码企业内无人理解，也无人能修改和debug的情况，然而这些代码也是没有人负责的，没有人愿意为这些代码负责到底。

当出现人员和代码不相匹配的情况时，请小心，说明这家企业已经欠下了技术债务。

## 引起技术债务的几个原因

造成技术债务的形成和累积有非常多的原因，在本小节中，尝试列举出一些常见的原因及其概要的描述。

* 低质量的代码，从而无法被上游所接受，例如不符合上游项目所设置的开发质量标准，“意大利面条”式的内部开发的代码通常是引起这样结果的缘由。
* 所开发的代码仅适用于企业自身的业务需求，而非项目的通用，这样的代码，上游通常是不接受的，要进行一定的调整，以使一般用例和更广泛的用户群受益。
* 碎片化的开发导致重复的努力，和同质竞争的出现。
* 缺乏推动上游优先的动力 —— 在很多情况下，开发团队所在的组织没有更多的资源、能力参与到共同体，以及驱动开发者基于上游而工作。在短期来看，该组织获得了一定的红利，获得了不错的效率，但是从代码维护和改进的方面来看则产生了技术债务，长期而言，这是相当糟糕的负面影响。
* 需要跨多个组件或各种系统/子系统进行额外协调的侵入性代码（Intrusive code）。（当然这是一种不好的编码习惯。—— 译者注）
* 从本地提交给上游，到被上游接受，中间是有一个时间差，也就是所谓的临时的技术债务代码，但是代码一旦被接受并合并到上游分支中，这些债务就会被很好的抵消。从长远来看，这么做没有不良影响。
* 测试的缺失，不仅会阻碍完整的测试覆盖率，还会导致提交的失败。
* 文档的缺失，或者是文档的陈旧。
* 技术领导力的缺乏，会导致和技术项目共同体的疏远，团队就会变得边缘化，这样的话，就意味着团队只能另外开辟路径来确保项目的可持续发展。
* 在任何组织中，内部开发的需求都是不断的发生着变化。
* 采用了非标准的技术，或者是标准缺乏一致性。
* 所在组织不够重视，加上技术领导力的不足，会导致对上游缺乏了解，这种情况越发的在非原生数字公司成为了普遍现象，这些公司被迫承担本不属于自身的工作。

## 后果

欠下技术债务，或者说累积技术债务，对于公司会产生很多的负面影响，例如：

* 代码维护的高昂代价
* 创新的匮乏与拖沓的开发周期
* 需不断交付的债务利息 —— 技术债务不是说可以不还的，而是以另外的形式存在：为了跟上上游的额外开发、无效的恶性竞争、无暇顾及其它。
* 主分支中可能缺少新功能，或者必须将所有新开发内容向后移植到内部分支中。
* 内部版本和上游版本差异太大，因此需要投入额外的精力去做和上游一样重复的工作。

最糟糕的后果是对代码库的长期可维护性的影响，组织经常会发现只有自己在维护了一个 fork 版。
