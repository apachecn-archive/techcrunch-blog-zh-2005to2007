# 五种混合、分解和融合数据的方法 TechCrunch

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2007/03/02/5-ways-to-mix-rip-and-mash-your-data/>

称它们为 pipes、teqlos、dapps、modules、mashup 或其他任何东西，但事实是，最近我们已经看到了许多新的服务，它们允许开发者和用户构建迷你应用程序和 mashup 来混合和重新混合数据。在这里，我们运行 5 个应用程序，允许您混合、抓取和混合您的数据，查看数据输入、输出、 [REST](https://web.archive.org/web/20221001090542/http://en.wikipedia.org/wiki/REST) 支持、建议使用和所需的技能水平:

![mashfeatcomp.png](img/161f9670ae71feed0de7e5b2463d4ea0.png)

**雅虎管道**

[![pipes200.png](img/7c98aba1d4a6b70d1bb41fb28b5bda7e.png)](https://web.archive.org/web/20221001090542/http://pipes.yahoo.com/) 雅虎！ [Pipes](https://web.archive.org/web/20221001090542/http://www.beta.techcrunch.com/2007/02/07/yahoo-launches-pipes/) 是一个 GUI web 应用程序，允许您通过重新混合联合提要(RSS、Atom、RDF)来创建新的数据提要。Pipes 从网络上获取提要，允许您在将提要输出到 RSS 或 JSON 之前对其进行排序、连接和分析。它还有一个很好的查询构建器模块，可以让您根据 URL 参数获取提要。雅虎！还围绕这项服务创建了一个社区，让用户发布和重新混合其他人的管道。从管道得到的数据甚至可以用于其他混搭，就像 Teqlo 已经完成的一样。

**非常适合** :Pipes 最适合与 Yahoo！诸如搜索、本地、Flickr 甚至 Google Base 等服务，因为这些模块已经包含在内。编程经验仅限于对过程编程控制结构(循环、逻辑测试)的理解，并借助可视化界面。

**例子** : [公寓附近的东西](https://web.archive.org/web/20221001090542/http://pipes.yahoo.com/pipes/1mrlkB232xGjJDdwXqIxGw/) (Craigslist 和 Yahoo！本地)。[易贝价格观察](https://web.archive.org/web/20221001090542/http://pipes.yahoo.com/pipes/avkEShi32xG_EF6KZVUMqA/)(易贝 RSS API)。

**Teqlo**

[![teqlologo.png](img/dec0c5be6ba2a414332c74a559e0d908.png) ](https://web.archive.org/web/20221001090542/http://teqlo.com/) [Teqlo](https://web.archive.org/web/20221001090542/http://teqlo.com/) 是一个新的基于小部件的混搭应用。您可以通过将专门的小部件放到画布上并指定它们之间的交互来构建混搭。例如，您可以通过将易贝搜索小部件和谷歌地图小部件放到画布上来映射易贝搜索的结果。然后，通过指定交互来连接这两个小部件，比如当在易贝小部件中选择一个项目时，在谷歌地图上添加一个标记。然后，通过带有活动 AJAX 小部件的网页来访问该应用程序。其他小工具包括谷歌日历、小工具、电子表格、LinkedIn 搜索、DabbleDB 搜索、YouTube 浏览器、联系人列表和待办事项列表。

这项服务目前处于测试阶段，所以他们的模块数量有限，而且还没有发布到网络上。

**最适合** : Teqlo 是一个高级的 masher，最适合非程序员。用户通过在一个部件中指定一个动作引起另一个部件的反应来创建部件之间的交互。然而，Teqlo 的高级方法意味着它的大部分能力在于它的开发者能够制作有用的小部件和交互。

**示例**:示例尚未公开，但他们的[博客](https://web.archive.org/web/20221001090542/http://teqlo.com/blog/rboothby/2007/02/teqlo-turns-a-pipe-into-an-application)中有一个 Teqlo 示例。

**原型**

[![protologo.png](img/d3cf6702bf9ef3b7d7209220f77995d2.png) ](https://web.archive.org/web/20221001090542/http://protosw.com/) [Proto](https://web.archive.org/web/20221001090542/http://protosw.com/) 是一款基于 Windows 的混搭应用，旨在将你的桌面应用与网络连接起来。您需要 Windows 应用程序来创建和使用混搭。它是基于组件的，通过从桌面应用程序(如 Outlook)中提取数据，并将其输入在线 web 组件(如 Yahoo！地图。Proto 内置了 Visual Basic for Applications 开发环境(VBA IDE)和 Adobe Flash，因此您可以创建自己的模块来从应用程序中提取和显示数据。Proto 还有一个轻量级数据库，用于在应用程序和在线组件之间分解和操作数据。

**最适合** : Proto 需要熟悉一些数据库概念，希望有 VBA 的经验，这样你就可以编写自己的模块。他们 5 分钟的[介绍](https://web.archive.org/web/20221001090542/http://www.protosw.com/products/intro-movie)表明了你真正使用该程序所需的经验水平。由于 Proto 允许你共享你的混搭，非程序员也可以使用 Proto 作为他们的已有混搭的[库](https://web.archive.org/web/20221001090542/http://www.protosw.com/mods/app)。

**示例**:介绍视频提供了一个很好的程序示例，但是需要下载[查看器](https://web.archive.org/web/20221001090542/http://www.protosw.com/products/viewer)来查看类似[餐厅查看器](https://web.archive.org/web/20221001090542/http://www.protosw.com/mods/app/view/380)或更具企业意识的 [Salesforce reporter](https://web.archive.org/web/20221001090542/http://www.protosw.com/mods/app/view/309) 的模块。

**衣冠楚楚**

[![dapper](img/f368e202c7f36d56c654fba7b28d72db.png) ](https://web.archive.org/web/20221001090542/http://dappit.com/) [Dapper](https://web.archive.org/web/20221001090542/http://www.beta.techcrunch.com/2006/11/22/make-your-own-netvibes-modules-with-dapper/) 是一个基于 web 的应用程序，用于为网站内容生成 XML。你通过使用 Dapper 的虚拟浏览器从网页中抓取内容来创建“Dapps”(网络服务)。Dapper 是通过输入几个包含你感兴趣的内容的示例 URL 来训练的。Dapper 通过查看页面之间的相似性来猜测页面中的重要内容。在 Dapper 分析了页面之后，您可以缩小页面上您想要跟踪的字段。例如，Digg 上的故事标题。然后，Dapper 可以以各种格式(XML、JSON、HTML 和 YAML)输出您从页面中选择的内容，并结合这些数据来触发警报，甚至是在提要中找到的地图位置。每个 Dapper 应用程序“Dapp”都发布到社区供任何人使用。

**最适合** : Dapper 需要最少的编程经验，对于为还没有结构化提要的页面创建结构化提要非常有用。他们的演示电影是一个很好的开始。

**例子** : [坐立不安](https://web.archive.org/web/20221001090542/http://www.dappit.com/dapplications/Fidget/)是一个工具，让你根据 Dapper 进行的搜索找到你喜欢的乐队的视频。

**OpenKapow**

[![openkapow](img/cb8085f9658ee473bd8a71ab4462d318.png) ](https://web.archive.org/web/20221001090542/http://openkapow.com/) [OpenKapow](https://web.archive.org/web/20221001090542/http://www.beta.techcrunch.com/2006/12/04/openkapow-not-quite-dapper/) 是衣冠楚楚的工业实力版。这是一个桌面应用程序，通过浏览器界面对 RSS 提要、REST 应用程序和 web 剪辑进行编程。您可以使用 OpenKapow 让 web 机器人像 Dapper 一样从 web 页面中提取数据，但是您可以指导该机器人导航 web 页面(包括表单提交)、执行循环、分支、从错误中恢复，以及在过程中的任何点接受用户输入。OpenKapow 有一个社区，开发者可以分享他们的机器人，供其他用户使用和重新混合。

**非常适合** : OpenKapow 非常适合严重的 web 报废。使用它需要过程编程和 web 标记的基础知识。

**示例** : [这里的](https://web.archive.org/web/20221001090542/http://service.openkapow.com/Andreas/gmailreader.rest)是一个登录 Gmail 并以 XML 格式输出你的电子邮件的机器人。这是另一个[在 TechCrunch 的帖子中搜索关键词的](https://web.archive.org/web/20221001090542/http://service.openkapow.com/Andreas/techcrunchpostsearch.rest)。