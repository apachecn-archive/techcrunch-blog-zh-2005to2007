# Folding@Home 在 GPU 上比 CPU 快 20 倍？TechCrunch

> 原文：<https://web.archive.org/web/http://techcrunch.com/2006/10/17/foldinghome-works-20x-faster-on-a-gpu-than-cpu/>

# Folding@Home 在 GPU 上比 CPU 快 20 倍？

我们之前研究过运行 Folding@Home 软件，你会得到 20 到 40 倍于 CPU 的输出。这是一个非常大胆的主张，但 Techreport 发现事实并非如此。

尽管斯坦福声称测试版 GPU 客户端在新的 Radeons 上运行速度快 20 到 40 倍，尽管 Radeons 具有许多千兆次的处理能力，但当前的客户端并没有报告这种巨大的工作量。在测试中，GPU 客户端完成了 2640 个工作点，而 CPU 客户端只完成了 899 个。这与报道的 20 ~ 40 倍相差甚远。怎么回事？

实际上，这种差异来自于这样一个事实，即点和工作单元是在不同的尺度上，取决于你使用的是 CPU 还是 GPU。GPU 客户端实际上做了 20 到 40 倍的工作，但因为基准设置得如此之高，结果是分数，给或拿，没有太大的不同。因此，由于评分方案没有反映更大的工作量，所以不要指望向你的书呆子朋友炫耀你的 Folding@Home 分数，吹嘘你做了多少癌症研究。然而，GPU 的处理能力比 CPU 高出一个数量级。

[近距离观察 GPU 上的 Folding @ home](https://web.archive.org/web/20130627215229/http://techreport.com/etc/2006q4/gpu-folding/index.x?pg=1)【tech report】