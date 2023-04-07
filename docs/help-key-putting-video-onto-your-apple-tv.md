# 帮助键:把视频放到你的苹果电视上

> 原文：<https://web.archive.org/web/http://techcrunch.com:80/2007/04/02/help-key-putting-video-onto-your-apple-tv/>

你已经有了苹果电视，但出于某种奇怪的原因，你对 9.99 美元的迪士尼经典下载不满意。支持 HDMI 的视频播放设备的粉丝应该做些什么？

这里有一个快速教程，教你如何将几乎任何来源的视频下载到你的苹果电视。

移动视频的真正关键是转换。这是大多数设备到设备传输的致命弱点，在很大程度上，也是所有反 DRM 努力的真正目的。说出你对自由、婴儿和爱情的想法——当涉及 DRM 时，试图让设备一起工作几乎是不可能的。我们将把本教程分为三个步骤:获取，转换，导入。我也是以 OS X 为中心的，所以请原谅我。我将努力为这两个平台找到解决方案。

**收购**

好吧，脏鸟们。如果你不知道如何把内容放到你的硬盘上，我不会教你如何下载你喜欢的内容。

例如，你也可以从 TiVoToGo 获取内容，并使用免费工具和你已经在 TiVo 中的密钥，将它们转换成普通的 MPEG 文件。然后，您可以将该内容转换为 iPod 兼容的格式。

![](img/6256f3db62de7586369b61a21f85f8da.png)
您还可以翻录 DVD，将其添加到您的收藏中。我用[手刹](https://web.archive.org/web/20160406070229/http://handbrake.m0k.org/?page_id=8)现在叫 MediaFork。这是一个免费的开源解决方案，本质上是为 Windows 提取一个 MPEG-4 文件。这显然是最后的选择，因为这是 1 对 1 的下载和转换时间，这意味着你需要 2 个小时来捕捉一部 2 小时的电影。诚然，你可以安排这些设备在一周内获取内容，但这很无聊，西德尼，很无聊。

**转换**

。这是一个基于 MPEG-4 的标准，从 DivX 和 XviD 等标准格式的转换非常简单。

转换后的质量取决于您输入的视频，但除了黑暗场景和屏幕上有很多动作的场景，我在 56 英寸的背投屏幕上观看撕裂的 DVD 没有任何问题。不是很理想，但是可以接受。将 ffmpegX 中的格式设定为“iPod h.264 640w”该计划还支持 SRT 字幕文件，你添加在过滤器标签。然而，这可能有点不可靠，所以不要依赖它。

，但这需要一些设置。

现在你有了 iTunes 可以读取的格式的视频。幸福在等待着。

**进口**

现在，您可以开始将内容放入 iTunes 并与 Apple TV 同步了。你可以使用类似[的 iPodifier](https://web.archive.org/web/20160406070229/http://www.ipodifier.com/) 在 Windows 下几乎自动地将视频发送到 iTunes，但是为什么要让它变得简单呢？这将是如此之酷，只是让它自动发送我们的视频，只要它转换下。OS X 球迷欢欣鼓舞——有一个简单的方法可以做到这一点。我们只需将一个动作附加到我们的“已转换项目文件夹”

使用我们公然从优秀的[MaxOSXHints.com](https://web.archive.org/web/20160406070229/http://www.macosxhints.com/article.php?story=20070301051316596)网站窃取的代码，我们创建了一个 AppleScript:

`property extension_list : {"mp4", "mov"}
-- These are the two extensions made by ffmpegX. We can also look for .ff. in the filename, another surefire signal, but this is a bit easier and assumes we use ffmpegX only.`

在收到 _files 后将文件夹项目添加到 my_folder 时
重复 I 从 1 到 _files 中的项目数
将此 _item 设置为(文件的项目 I)
将 item_info 设置为此 _item 的信息
如果 item_info 的扩展名在 extension_list 中，则
-调试显示
-显示对话框“将 item_info 的名称&添加到 iTunes”

告诉应用程序“iTunes”
尝试
设置 this_track 将 this_item 添加到源“Library”的播放列表“Library”
结束尝试
结束告诉
结束 if
结束重复
结束将文件夹项目添加到

![](img/4d01610480075c972a1a10306aeaf23e.png)
亲爱的美国电影协会:这是我和 300 个我最亲密的斯巴达朋友的家庭视频。不要起诉。

现在，通过将脚本拷贝到/Library/Scripts/Folder Action Scripts 并选择 downloads 文件夹，将该脚本附加到一个文件夹。将此脚本分配到该文件夹，每次有东西保存在那里时，它都会自动转到 iTunes 和/或与 Apple TV 同步。例如，我将所有下载的文件保存在一个名为~/Downloads 的文件夹中。我只是将动作添加到那个文件夹中，现在无论什么时候下载和转换东西，我都准备好了。

只要稍加规划，您几乎可以自动化整个过程。因为许多文件都是 rar 格式的，所以您可以使用 Applescript 来解压缩文件，使用 [AppleScript](https://web.archive.org/web/20160406070229/http://www.gregwalsh.com/articles/applescript_flv.htm) 来转换文件，然后在没有您干预的情况下将它们放入 iTunes。只是记得偶尔进入那个文件夹，以确保它不会变成一个 500 GB 的庞然大物。

正如我们所看到的，创建 Apple TV 转换工作流是相当容易的。使用一些免费或便宜的工具，我们可以在书房里创建一个迷你电影院。

* * *

想要你自己的破解 DRM 封面？得到它

[here](https://web.archive.org/web/20160406070229/http://wrappers.typepad.com/ipod/ipod_video/index.html)

.