# Flickr 支持“地理”微格式 TechCrunch

> 原文：<https://web.archive.org/web/http://techcrunch.com/2006/08/29/flickr-supports-geo-microformat/>

# Flickr 支持“地理”微格式

今天网络上有很多关于雅虎的报道。整合了它的一堆资产——Flickr，Yahoo！地图，即将推出，和雅虎！本地，最后在 Flickr 中增加了对“地理标签”的支持。回到六月，在伦敦的[内容 2.0](https://web.archive.org/web/20221007193212/http://www.content2point0.com/2006/) 活动上，雅虎副总裁 ~~S~~ 布拉德利·霍洛维茨提到他们将“很快提供地理标签支持”。

当然，他们的竞争对手, [Zooomr](https://web.archive.org/web/20221007193212/http://beta.zooomr.com/home) 已经拥有这个非常有用的功能有一段时间了，英国最古老的地图绘制公司之一,[Multimap.com](https://web.archive.org/web/20221007193212/http://www.multimap.com/ "http://www.multimap.com"),一直支持geo 微格式来标记他们地图页面上的经纬度值。

![](img/6ca5d2f08a14e35e1544c72faee963f8.png)

通读大量的报道，有一件事似乎没有被提及，那就是对微格式的支持，雅虎正在悄悄地将这种支持构建到他们的所有产品中，这只是这种支持的另一个例子。

*   Upcoming.org–vevent
*   雅虎！本地 hcard
*   雅虎！技术–hreview
*   Flickr -hcard，geo

在 Flickr 中添加“地理标记”支持意味着未来人们将能够使用底层的“ [geo](https://web.archive.org/web/20221007193212/http://microformats.org/wiki/geo) ”微格式来搜索和更好地发现新的基于位置的数据。

那么 geo 微格式标记是什么样子的呢？如果您的地理位置是:N 37 24.491 W 122 08.313，那么您的地理标记看起来会像这样，并且它会像这样显示在网页上。N 37 24.491 W 122 08.313。

![](img/209edb716535e26043d906c0c08df51f.png)

Technorati 是首批拥有语义搜索引擎的公司之一。它目前允许人们搜索 hcard、vevent 和 hcalendar 微格式标记，但目前不支持 geo 微格式，我希望它很快会支持。下面是一个搜索本周在英国举行的“[公园里的极客](https://web.archive.org/web/20221007193212/http://www.geekinthepark.co.uk/)”活动的例子，该活动标有许多微格式。

这一搜索是使用 hcalendar 微格式完成的，它使我能够将活动细节(日期、时间、地点等)添加到我的日历中，而不必手动剪切和粘贴或键入内容。(**注意** : *在接下来的几周，我也将使用 hcalendar 微格式在 TechCrunch 上标记英国的活动，所有评论都将使用 hreview* 标记。)

那么有什么好处呢？随着更多微格式内容的产生和更多语义搜索引擎支持的出现，希望它能让我们更快地找到我们想要的东西并重用这些内容。微软宣布，他们将很快推出一款名为 [Live Clipboard](https://web.archive.org/web/20221007193212/http://microformats.org/blog/2006/03/08/ray-ozzie-on-microformats/) 的产品，它可以让你在网站或应用程序之间剪切和粘贴数据，同时保留底层结构。

有多少次，你访问一家公司的网站，想要将他们的地址复制到你的联系人数据库中，但使用当前的剪切和粘贴方法，你发现自己需要手动将数据添加到每个相关字段中。有了 Live Clipboard 和 microformats，你就可以将数据直接剪切并粘贴到你的联系人列表中，并让软件为你填充正确的字段，因为这是潜在的语义结构。

我们所看到的微格式仅仅是语义网的开始。有一件事我已经想了一段时间，那就是雅虎什么时候会。买 Technorati。雅虎！很明显，他们喜欢微格式的想法，并在他们的产品中构建的支持中展示了这一点。现在缺少的是使用 Yahoo Search 搜索微格式的方法。

一旦微软推出 Live Clipboard，我猜人们会开始在他们的网站上添加这项功能。我们多久才会听到微格式混搭这个术语？

注: [Calvin Yu](https://web.archive.org/web/20221007193212/http://blog.codeeg.com/ "http://blog.codeeg.com/") 已经编写了一个 [web 服务，它将允许你使用](https://web.archive.org/web/20221007193212/http://blog.codeeg.com/2006/01/28/using-microformats-to-plot-my-favorite-places/ "http://blog.codeeg.com/2006/01/28/using-microformats-to-plot-my-favorite-places/") [hReview](https://web.archive.org/web/20221007193212/http://uk.beta.techcrunch.com/wiki/hreview "hreview") 和 **geo** 在雅虎地图上轻松地绘制和描述地点。

**更新:来自 Flickr**

[**地理标记——一天后**](https://web.archive.org/web/20221007193212/http://blog.flickr.com/flickrblog/2006/08/geotagging_one_.html)——第一天——“当我们预测 Flickr 会员会对多少照片进行地理标记时，我们认为我们会在第一个月达到 100 万，甚至可能会在两周内达到。相反，在 24 小时内，有 1，234，384 张带地理标签的照片…