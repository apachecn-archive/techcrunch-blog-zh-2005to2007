# Bloglines 希望阻止搜索 TechCrunch 的私人订阅源

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2006/08/01/bloglines-will-block-your-feed-from-search/>

# Bloglines 想在搜索中屏蔽私人订阅

“你在博客上写的每一件事都会被永久记录下来！”我们最近听过多少次了？从就业到家庭状况，许多人沮丧地发现，他们打算写给个人读者的东西现在可以被世界上任何人通过搜索引擎发现。 **Bloglines [提议](https://web.archive.org/web/20220928200849/http://www.bloglines.com/about/news#114)一个[新标准](https://web.archive.org/web/20220928200849/http://www.bloglines.com/about/specs/fac-1.0)今晚改变这一切。**

你可以在 Flickr 和 MySpace 这样的地方拥有私人页面，但是你的页面的 RSS 提要仍然可以被搜索引擎发现。这就是新标准想要改变的。

提议的标准将允许 XML/RSS/Atom 提要发布者通过在提要的顶部添加一个 access:restriction 标签，使它们的提要不被搜索引擎发现。Bloglines 和 Ask 现在支持这一标签，并将把被标记为受限的订阅源排除在搜索和订阅结果之外。

你可以向你想订阅的朋友发送一个私人订阅网址，但是如果你有一个私人账户，你未来的雇主不会在搜索引擎中找到它。

Robots.txt 协议告诉搜索引擎不要索引网页[是在 1994 年](https://web.archive.org/web/20220928200849/http://www.robotstxt.org/wc/norobots.html)达成的，但那只是针对 HTML 网页。越来越多的搜索引擎现在首先索引更动态的 XML/RSS/Atom 提要。这一新标准是限制我们私人账户在线传播的重要组成部分。

我刚刚与 Bloglines 的高级产品经理 Robyn DeuPree 和高级软件工程师 Paul Querna 进行了交谈，他们告诉我，该公司希望内容出版商(Flickr、Myspace)和搜索引擎(Google、Google Blogsearch、Technorati、Icerocket)都能加入进来，并向那些希望自己的内容不被搜索引擎发现的用户提供这一功能。

还没有与任何其他公司达成正式协议，但很难知道为什么他们不会热情地接受这个想法。许多提要阅读器不支持正式认证的提要(需要密码)，但这应该很容易实现。

其他提要阅读器会尊重这个提议的标准吗？我当然希望他们这样做——这是一个伟大的想法，是时候了。天知道我会开始一个全新的 MySpace 帐户，如果我知道它的 feed 将被保留在搜索之外！