## 太晚了，技术债务已经背上了，要‘摆烂’吗？

您所在的组织已经欠下了很多的技术债务，上述的症状都有，这个时候我们该如何处理？我们都希望有一个能够解决问题的必杀技，可是真实的情况是必杀技并不存在。您要采取的行动，取决于应对不同的情形，不过在进一步之前，可以对照一下下面的情形：

* 摘选出需要保留的功能/特性；
* 确认代码还是有用处的；
* 移除不再使用和维护的代码；
* 减少分支和fork；
* 重构、清理，以符合上游需要，并合并到上游代码中；

以上这些活动相当的耗时，所以会拖慢您现有的进度，而且还需要专门腾出人手来做这些。在完成上述这些工作的时候，团队也很难添加任何的功能，而且还可能会产生抵触以及更多有争议的地方。

现在也有可能存在一个开源项目，它确实或可以提供您需要的功能或某些功能。迁移到该开源项目也可能比尝试处理当前的代码库更有意义。但是，请不要忘记，这个世界并不会因为我们不去关注而停止，千万不要盯着眼前的某些可以暂时满足的功能。所以一定不要让贵司阻止你寻找更具长远意义的解决方案，尤其是当前方案看起来颇具商业意义的时候。

还有另外一个更为激进的做法：连同现有的代码一道将技术债务一股脑扔掉。可以通过多种方式来完成：贵司的业务已经无力承担维护代码的费用，而且客户也没有多少，此时直接丢弃即可；当然，一定要和客户说明即将废弃的代码，这个过程相当于破产清算，及时止损，也就不再有技术债务。
  
