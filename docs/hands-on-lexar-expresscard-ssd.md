# Lexar ExpressCard 固态硬盘评论–TechCrunch

> 原文：<https://web.archive.org/web/http://techcrunch.com/2007/05/07/hands-on-lexar-expresscard-ssd/>

# Lexar ExpressCard 固态硬盘评论

Lexar 最近发布了其 ExpressCard SSD 系列，这是一系列固态硬盘，有 4GB、8GB 和 16GB 三种规格。在过去的几周里，我有机会广泛地测试了一款 8GB 的型号，现在我准备发表我的想法。它能送货吗？


简而言之，不能。虽然该驱动器本身是 Mac 兼容的，但它是为 PC 使用而设计的。它的所有软件都只能在 PC 上使用，所以它的自动备份功能在 Mac 上无法使用。

该驱动器针对 Windows Vista 进行了优化。特别是它的 ReadyBoost 功能。ReadyBoost 允许用户通过将数据直接快速缓存到 ExpressCard SSD 来增强系统性能。问题是该卡是通过 USB 2.0 而不是 PCI Express 插入的，这意味着 SSD 的访问速度仅为 480Mbps，而不是 PCI-E 支持的 2.5Gbps。

还要考虑系统中通常使用的 DDR2 内存传输速度至少为 3.2GBps，SATA 硬盘的吞吐量为 1.5Gbps 和 3Gbps。这些数字表明 ReadyBoost 只对基于 PCI-E 的 ExpressCards 有效。

至于额外的存储空间，这是一个可以接受的解决方案。我实现了与我的 USB 2.0 闪存驱动器完全相当的访问速度——它的写入速度约为 4MBps，读取速度约为 13MBps。也就是说，我看不出有人会购买这个，比如说，市场上的任何其他闪存驱动器。

它会消耗您的 ExpressCard 插槽，并且不会提供任何性能增益。因此，在 PCI-E 版本出现之前，请坚持使用拇指驱动器。这项技术还没有出现。

[产品页面](https://web.archive.org/web/20201123193149/http://www.lexar.com/ssd/expresscard.html)