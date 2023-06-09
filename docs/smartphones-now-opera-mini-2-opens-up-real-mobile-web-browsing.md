# 现在的智能手机:Opera Mini 2 开启真正的移动网络浏览

> 原文：<https://web.archive.org/web/http://techcrunch.com:80/2006/11/02/smartphones-now-opera-mini-2-opens-up-real-mobile-web-browsing/>

Opera Mini 是免费的，运行在可移植的 Java 运行时上，所以大多数现代手机都受到支持。此外，程序本身很小，大多数版本都在 1 MB 以下。

我们一直在 T-Moile 数据网络上的 Palm Treo 650 上使用 Opera Mini。一般来说，我们在西雅图的 EDGE 连接大约是 166k，这似乎不是那么糟糕，直到你尝试下载一个内容丰富的页面，例如 CNN.com 的首页，大约有 310k。Opera 代理服务器会把它嚼碎，然后吐回 31k 左右。这意味着节省了 90%，这就是美所在。

除了为您的小屏幕和有限的带宽优化页面本身之外，代理服务器还可以动态转换图像。这消除了传统浏览所浪费的大量开销，同时仍然提供了完整的体验。如果您的屏幕是 320×320 像素，观看 450 像素的图像就太多了。大多数移动浏览器只是按比例缩小图像，而下载整个东西，这是低效的。Opera Mini 的代理实际上将图像转换为移动设备友好的大小，并链接到实际的全尺寸图像。

为了在我们的 Treo 上运行该程序，我们首先必须安装 IBM 的 Websphere Java 虚拟机，这是 Palm 网站为大多数 Treo 用户提供的免费升级。虽然这个运行时软件的应用程序下载页面说它需要 8MB(当您的 Treo 总共只有 22MB 可用时，这一点很重要)，但我们发现，一旦安装，它使用的内存不到 1MB，并且使用扩展卡运行良好。

这是浏览器的另一个奇妙的特点:集成了从主屏幕上搜索的维基百科，以及谷歌和你的书签和历史。由于移动网络浏览器经常被用于快速参考，这是完美的。而且速度很快。

上下键在页面上平滑地从一个链接跳到另一个链接，便于单手浏览。左右键分别用作向上翻页和向下翻页。滚动是平滑和直观的，用上一屏幕的最后一行文本停止页面顶部。当点击一个链接时，快速过渡到目标页面，并且“翻页”动画确实是显示页面已加载的有效方式。

然而，一切并不完美。“home”和“menu”键位于屏幕下方的左右两侧，不像在手机上那样作为“软键”使用。我们猜测这是操作系统的限制，而不是浏览器本身。另一个问题是，作为一个 Java 应用程序，它有时会有点不稳定。有几个程序在检索网页时死机的例子。这需要对设备背面进行软复位，这需要移除电池，进而需要放下我们的饮料。我们没有被逗乐。幸运的是，这种情况很少发生，足以被认为是有问题的。

[Opera Mini](https://web.archive.org/web/20130627201830/http://www.opera.com/products/mobile/operamini/) 【产品页面】