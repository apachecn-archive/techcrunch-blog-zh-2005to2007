# Twitter 的网络服务——TechCrunch

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2007/03/27/twitter-becomes-mobile-dev-platform/>

[![twitter.png](img/9a4fdafabf5fb50020fea50335c8ba7e.png)](https://web.archive.org/web/20220627090344/http://www.twitter.com/techcrunch) 今年早些时候，我们讨论了通过一套语法查询多个 web 服务的简单命令行的[效用。我们讨论过的网络服务之一 Yubnub](https://web.archive.org/web/20220627090344/http://www.beta.techcrunch.com/2007/01/03/the-usefulness-of-the-simple-command-line/) 就是这么做的。在 Yubnub 中输入“天气 90210 ”,获得 Weather.com 的天气信息。或者用这个命令行查询数以千计的其他服务。

Twitter 的 API 即将进行的微妙变化也将允许这种功能。Twitter 是一种围绕 SMS/文本消息的社交网络，拥有一个快速增长的用户群体，他们每天花费数小时发送关于他们正在做什么或在想什么的文本消息。要发布消息，用户只需将他们想要发布的消息发送到“40404”任何想追随另一个用户意思的人都可以这样做。你关注的人发来的所有消息都可以在你的 Twitter 页面上看到，还可以通过短信发送到你的移动设备上。

Twitter 的一个受欢迎的功能是“直接”发送消息给一个朋友。语法很简单——你输入“d[用户名][你的消息]。”

直到现在，Twitter 的 API 还不允许你访问这些直接信息。有了今天的 API，您现在可以检索 Twitter 的直接消息。那是什么意思？坦白说，很多。

用户现在可以向用户名发送命令(“直接消息”)，这个用户名只是像 weather.com 这样的网络服务的名称。例如，可以有一个 Twitter 用户名“天气”，我可以通过文本、web 或 IM 发送一条 Twitter 消息“d 天气 14202”。Twitter 用户名“weather”可以通过 API 获得这个命令(呃，Twitter“direct message”)，在 web 服务器上运行一个进程来检索 14202 年的当前天气预报，并将其作为直接消息发送回我(即“d TechCrunch current:partially Cloudy，50F。明天的天气预报:上午云/下午太阳。高:55 低:40”)。

或者可以有一个用户名“score ”,您可以发送“d score Yankees ”,以立即请求 Yankees 比赛的比分。或者另一个例子可以是“d 411 Starbucks 14202”来检索离邮政编码 14202 最近的星巴克的电话号码。

目前，在短信/移动领域启动一家初创企业需要花费大量资金——你必须每月获得一个[短码](https://web.archive.org/web/20220627090344/http://www.usshortcodes.com/)的许可(500-1000 美元/月)，向短信网关提供商付费，然后为每条入站或出站短信支付 0.03-0.05 美元不等的费用。它加起来。但是现在，如果一家初创公司选择使用 Twitter 作为他们网络服务的命令行，它是免费的(直到 Twitter 开始收费)。

正如你所知，有一件事有点烦人，那就是用“d”作为消息的开头，但是 Twitter 内部正在讨论使用“@”作为“d”的等价物——我希望他们这样做。目前，人们正在使用“@(用户名)”来[公开回复](https://web.archive.org/web/20220627090344/http://twitter.com/TechCrunch/statuses/12693951)其他 Twitter 消息——如果你是一个用户的朋友，而这个用户正在回复另一个用户说的话(而你甚至不知道最初说的是什么)，这可能会很烦人。

更新后的 Twitter API 代码应该会在早上发布，附带的 API 文档也应该会在今天结束前发布。

*编者按:这篇文章由 [Ringside Startup](https://web.archive.org/web/20220627090344/http://www.ringsidestartup.com/) 的 [Steve Poland](https://web.archive.org/web/20220627090344/http://www.techquilashots.com/) 撰写，他在博客中记录了自己的网络创业之旅，沿途得到了风投和经验丰富的企业家的建议。你可以在 twitter.com/techquilashots 关注史蒂夫的生活，在 twitter.com/techcrunch[关注迈克尔·阿灵顿的生活。](https://web.archive.org/web/20220627090344/http://www.twitter.com/techcrunch)*