# 使用 Dapper  为任何网站创建 API

> 原文：<https://web.archive.org/web/http://www.techcrunch.com/2006/08/17/create-an-api-for-any-site-with-dapper/>

# 用 Dapper 为任何站点创建一个 API

今天，一项名为[记事本](https://web.archive.org/web/20230225072056/http://www.dappit.com/dapplications/Blotter)的新兴服务[Dapper](https://web.archive.org/web/20230225072056/http://dappit.com/)(dappit.com)在博客圈获得了一些[好的](https://web.archive.org/web/20230225072056/http://battellemedia.com/archives/002814.php) [报道](https://web.archive.org/web/20230225072056/http://www.siliconbeat.com/entries/2006/08/17/roundup_the_vc_carwash_popsugar_khoslas_latest_facebook_opens_decentraltv_blotter.html)。一段时间内任何博客的吸墨纸图表 Technorati 数据。不过，最让我兴奋的是 Dapper 本周刚刚推出的基础服务。该公司表示，它有效地提供了一种从任何网站创建 API 的简单方法。这可能看起来像表面上粗糙的屏幕抓取，但该公司的目标是提供一些合法的，有价值的服务，并建立一种尊重版权的方式。该网站现在显然是有用的。

 Dapper 提供了一个点击 GUI，可以从任何网站提取数据，然后可以通过 XML、HTML、RSS、电子邮件提醒、谷歌地图、谷歌小工具、javascript 图像循环或 JSON 进行处理和显示。该网站可以对用户界面进行彻底的修改，让非技术用户更容易使用，版权问题也必须得到解决。也就是说，Dapper 相当不错。

Dapper 由 Jon Aizen 领导，Jon Aizen 毕业于康奈尔大学 CS，曾在 Alexa 档案馆和互联网档案馆工作，并担任首席执行官 Eran Shir。蓝染表示，该公司的最终目标是通过 Dapper 提供一个内容重用市场，允许出版商为他们发布的内容的任何创造性重用设置条款和价格。这是今天需要认真谈判才能做到的事情，但 Dapper 有潜力让更多人更容易达成这样的交易。蓝染说，对开发人员来说，Dapper 只会节省时间。

它是这样工作的。用户识别出一个他们感兴趣的网站，并通过短小精悍的虚拟浏览器进行浏览。蓝染以 Digg 为例向我展示了如何做到这一点。我点击了一个故事的标题，点击了 diggs 的数量和 via URL 字段。我去了同一个网站的另一个页面，做了同样的事情，以便 Dapper 可以清楚地识别我感兴趣的领域。然后，我浏览了网站上可用的各种工具，设置了特定的条件和阈值，最终得到了可以做各种事情的 XML 提要。比如，每当 digg 首页出现 TechCrunch 的报道，或者搜索结果页面显示 TechCrunch 的报道有超过 10 个 diggs 时，就给我发一封电子邮件。在我通过该网站创建一个最终产品后，其他用户将能够(在 24 小时内，我可以编辑项目)使用我的项目，或者是改变以适应他们的需求，或者在未来，与其他项目结合使用。

我最感兴趣的是提醒，但来自其他网站的数据可以在谷歌地图上映射，为不发布订阅源的网站转换成 RSS 订阅源，如果数据是图像的形式，可以转换成幻灯片。蓝染说他已经为自己开发了一个工具，可以自动通过 Babblefish 运行 feed 并生成一个翻译过的 feed。可能性很大。

隐私和授权技术在你自己的服务器上运行是该公司未来的目标。两者都很关键。

虽然该公司表示，该网站在很大程度上是一个概念证明，他们也在寻求种子资金，它已经非常有用。Dapper 说它的目标很高:Geocities 为静态网页所做的，他们想为动态内容重用所做的。如果他们能够找到一种好的方法来管理围绕重用内容的权利陷阱，我愿意相信这是可能的，那么我们可能会开始看到许多令人眼花缭乱的新方法来与通过 Dapper 构建的数据进行交互，并在网络上出现。