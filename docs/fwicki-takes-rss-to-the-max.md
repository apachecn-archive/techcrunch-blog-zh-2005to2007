# Fwicki 将 RSS 推向极致| TechCrunch

> 原文：<https://web.archive.org/web/http://techcrunch.com/2006/09/12/fwicki-takes-rss-to-the-max/>

![](img/1ec618df5cd71b89084617032e5dc2c8.png)

最近戴夫·温纳一直在谈论新闻河流。例如，当河水流过时，Dave 站在河岸上，看到的不是水，而是传递给他的 RSS 提要。这个想法是从哪里来的呢？戴夫最近买了一部黑莓手机，他发现了侧边滚动按钮，可以让他快速上下移动电子邮件或网页。

因此，戴夫利用他的 [OPML 编辑](https://web.archive.org/web/20140526074551/http://support.opml.org/)开发了许多[“移动”河流](https://web.archive.org/web/20140526074551/http://bbcriver.com/)，他可以在他的黑莓手机上查看这些河流，并且与大多数 RSS 聚合器不同，这些河流没有被组织成文件夹，因此没有层次结构可供点击。例如 [BBC](https://web.archive.org/web/20140526074551/http://bbcriver.com/) ，[纽约时报](https://web.archive.org/web/20140526074551/http://nytimesriver.com/)， [Digg](https://web.archive.org/web/20140526074551/http://www.diggriver.com/)

![](img/97bc7022e42db0b00eb070317d0243f2.png)

像戴夫的大多数想法一样，它们需要时间来理解，但最终它们还是理解了。例如博客、RSS 2.0、XML-RPC、播客、OPML 和现在的 rivers。因此，很高兴遇到一个 web 2.0 (Ajax)应用程序，它可以将来自多个来源的 RSS 提要聚合在一起，创建一条“河流”。

我决定为自己创建一条 [TechCrunch 全球河](https://web.archive.org/web/20140526074551/http://www.fwicki.com/fwickis/samsethi01/TechCrunch-World)。我只是在 fwicki 中添加了 TechCrunch.com、英国、CrunchNotes、CrunchGear 和 MobileCrunch 的 RSS 源，然后让它创建了我的河流。我给了它一个标题，标签，并按日期顺序排序。几秒钟后，我有了自己的 fwicki 和唯一的网址。

Fwicki 是两个网络爱好者的想法，他们在 2006 年初相遇——David Ridge 和 Justin Barone——他们创建了 fwicki，因为他们无法找到一种简单的方法来创建 mashup river，所以他们为自己创建了 fwicki。

![](img/cf4fa7b4f23fe72f4c8c42dd237fcef6.png)

> “这个应用程序的优点在于它的简单性。凭借集成的智能视频帮助系统，fwicki 非常容易使用，您不必成为“技术专家”就可以利用它的功能。用户可以快速轻松地创建自己的 fwicki，其中包含基于他们选择的提要的独特新闻和内容。Fwicki 还为用户提供了一个独特的免费在线托管的 fwicki 页面。Fwicki 提供了一个页眉和页脚修改机制，允许用户自定义他们的 fwicki 的外观。页眉和页脚机制也可以用来通过谷歌广告来赚钱。这使得新的互联网用户可以免费获得一个包含虚拟主机的 fwicki，并免费启动他们的第一个创业网站。

Fwicki 是 Justin 和 David 即将发布的几款应用中的第一款。如果你使用 RSS，并且想要一个杀手级的 AJAX 应用程序，让你的 RSS 体验更上一层楼，那么 fwicki 就是你的选择。

但是这条混搭河会把我们带到哪里呢？

目前，fwicki 只允许你按日期排序，但我也想按作者或特定类别标签排序/过滤。这可能会在未来的 fwicki 版本中出现，但我没有等待，而是获取了 [RSS 提要 URL](https://web.archive.org/web/20140526074551/http://www.fwicki.com/rss/samsethi01/TechCrunch-World) ，并用 Internet Explorer 7 打开了该 URL。因为 IE7 支持“[简单列表扩展](https://web.archive.org/web/20140526074551/http://blogs.msdn.com/rssteam/archive/2006/03/28/563116.aspx)”，它允许 RSS 和 Atom 提要按照微软所谓的“列表语义”进行分类/过滤，我能够通过特定的标签动态地进一步过滤提要，只看到我想要的内容。

例如，如果所有 TechCrunch 网站都使用一致/一致的标签 folksonomy，那么我可以先按日期对 mashup river 进行排序，然后进一步过滤，只查看使用相同标签名称的“一组”帖子。即谷歌。这会让我很快看到 TechCrunch 在我们所有网站上对谷歌的评价。

当然，我也可以选择用其他网站，比如 Digg，TechMeme，Scoble，Battelle 等等来创建一个 fwicki river。然后，我可以很容易地看到博客世界中某个特定标签“主题”上的内容。我认为这是一个非常强大的想法，这一切都是从戴夫·维纳开始的。

公司现在可以选择他们最喜欢的订阅源，创建一条新闻河，然后通过他们自己的公司标签进一步过滤，以获得整个网络的 RSS 警报。唯一美中不足的是标签名称所有权的不一致性和潜在冲突。例如，我想使用标签 TCUK 的 TechCrunch 英国网站，除了。TCUK 也是英国一家建筑商的名字？因此，当我输入 TCUK 时，使用传统的搜索引擎没有帮助，但是如果其他人也想使用 TCUK 作为他们的标签名称，我们如何解决冲突呢？

![](img/7c5a1f48d4fc2746fe69e8833a668d16.png)

一个选择是在这个网站的顶部声明我希望拥有标签名 TCUK，请大家在关于 TechCrunch UK 的帖子上加上 rel="TCUK "。如果这真的发生了，我就可以使用类似于 [Pingerati](https://web.archive.org/web/20140526074551/http://www.pingerati.net/) 、Pingomatic 或 Technorati 的服务，通过这个特定的 TCUK 标签来追踪 TechCrunch UK。目前，Technorati 上只有一个标签为 TCUK 的帖子。

所以想象一下，如果你的公司拥有一个特定的标签品牌，而人们在发布关于你的帖子时一直使用正确的标签。然后你可以创造自己的河流，看着信息在整个网络上流动。你如何看待和在哪里看待也会变得非常有趣。

Dave Winer 的河流是故意稀疏的，以便可以在移动设备上快速查看。IE7 中的 XSLT 模板提供了另一个更丰富的视图。这个标准 XSLT 文件可以换成一个品牌模板，进一步增强阅读效果。微软 Max 是几天前发布的，起初我并不理解它，除了它是微软即将推出的. NET3 平台的演示。但是想了更多，我决定在 TechCrunch river 中添加，现在使用 Microsoft Max，我可以更像看报纸一样查看它，像看报纸一样，我可以查看由标签主题过滤的多个页面。

![](img/050246504f4a74fde57975e982d79a36.png)

这是一个可能的未来。Mashup rivers 以报纸的形式显示，用户可以根据日期、主题或其他标准动态标记，然后可能在火车或厕所上通过 UMPC 查看？