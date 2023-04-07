# 苹果电视被黑客攻击以支持 u 盘|技术崩溃

> 原文：<https://web.archive.org/web/http://techcrunch.com:80/2007/07/30/apple-tv-hacked-to-support-usb-drives/>

![appletv_holy_grail.jpg](img/37069eeba558222f2e11876a77cab1e7.png)

我梦想成为一名世界级的黑客，只是因为我虚荣，我想看到我的名字在我搜索自己的时候第一个出现。黑客做了伟大的事情，这给我带来了微笑。我更喜欢苹果产品被黑客攻击。如果你对苹果沉默而沉思的继子[苹果电视](https://web.archive.org/web/20160913025846/http://crunchgear.com/category/apple-tv/)犹豫不决，那么这可能会改变投票结果，因为它已经被黑客攻击成使用 u 盘作为主驱动器，一切都可以完全同步。伙计们，别开玩笑了。

> 说明
> 
> 该补丁是为苹果电视软件 1.0 版编写的，因此在该版本上进行了测试。如果您有 1.1 版，修补程序可能不起作用。请告诉我们您是否能在 1.1 版上安装补丁。
> 
> 您需要的是:
> 
> *支持 ssh 的苹果电视。如果您还没有启用它，您可以参考这篇文章来启用它。有关如何在不打开案例的情况下启用 ssh 的说明，请参阅此 wiki 页面。
> *英特尔-Mac 或基于英特尔的*nix。这是运行脚本远程修补苹果电视内核所需要的。也许可以使用 cygwin 在 Windows 下运行安装脚本。然而，我们没有尝试过。
> *苹果 OS X 10.4 英特尔的安装版本。或者是其中一个“/System/Library/Extensions”文件夹内容的完整副本。
> *苹果电视上“mach_kernel.prelink”文件的原始未修改副本。如果你的苹果电视的内核还没有被修改，你可以告诉脚本从那里得到它。否则，您可以从这里提供的苹果电视软件 1.1 更新中获得该文件。
> *外部 USB 驱动器，格式为“HFS 日志+”。这是苹果电视期望的形式。
> 
> 程序
> 
> *完成上述所有操作后，提取 zip 文件并阅读自述文件。在其中，您可以找到有关如何运行脚本以及如何使 USB 驱动器工作的说明。
> *重要:请先备份苹果电视的内容，然后再运行补丁脚本。如果说安装补丁有一个重要的步骤，那就是备份你的苹果电视。
> *备份苹果电视后，运行脚本“install-atvrhd.sh”并按照说明进行操作。这个过程需要您不到 5 分钟的时间。一旦苹果电视上的内核打了补丁，设备就会重新启动。
> 
> 使用它
> 
> *在未插入 USB 驱动器的情况下打开 Apple TV。等待介绍序列(飞行电视屏幕等)。)然后插入 USB 驱动器。
> *一旦插入，内置硬盘的内容将被复制到外置硬盘。这个过程可能需要很长时间。要解决这一问题，我们建议您首先擦除内部硬盘的内容，这样就不需要复制内容。【The Apple TV 将在内容复制后自动重启。
> *此时，您的 Apple TV 将使用外置硬盘作为其主存储器。

[下载我](https://web.archive.org/web/20160913025846/http://www.appletvhacks.net/wp-content/uploads/2007/07/appletvhacks_usb_patch.zip)

[USB 补丁发布。哈利路亚！](https://web.archive.org/web/20160913025846/http://www.appletvhacks.net/2007/07/28/usb-patch-released-hallelujah/)【经由[马森斯坦](https://web.archive.org/web/20160913025846/http://macenstein.com/default/archives/739)