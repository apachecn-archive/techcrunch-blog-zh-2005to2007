# 哦，不，谷歌支持 XML-RPC！TechCrunch

> 原文：<https://web.archive.org/web/http://techcrunch.com:80/2006/10/06/oh-no-google-supports-xml-rpc/>

Google [宣布它为博客们开放了一个 ping 服务器](https://web.archive.org/web/20160528232854/http://googleblog.blogspot.com/2006/10/got-blog-will-ping.html),当你使用 XML-RPC 协议创建一个新的博客条目时，可以直接 ping 他们。为了直接 ping 谷歌，你只需要在你的博客软件中添加以下链接:【http://blogsearch.google.com/ping/RPC2 

所发生的是博客软件通过 HTTP POST 方法警告 Google 服务器有一个新的条目要索引，这就是为什么创建一个新的博客条目有时被称为创建一篇文章。大多数人会认为这是个好消息，当然除非你是 [Technorati](https://web.archive.org/web/20160528232854/http://www.technorati.com/developers/ping/) 、 [Pingomatic](https://web.archive.org/web/20160528232854/http://pingomatic.com/) 等。

通读[常见问题解答](https://web.archive.org/web/20160528232854/http://www.google.com/help/blogsearch/pinging_API.html)很高兴看到谷歌坚持 XML-RPC 标准，而不是“谷歌搜索”它，也就是说，最大的担心是他们可能只是为了创建像 [Gdata](https://web.archive.org/web/20160528232854/http://code.google.com/apis/gdata/) (Atom 发布协议)或 [Coop](https://web.archive.org/web/20160528232854/http://www.google.com/coop) (OpenSearch)这样的专有扩展而接受 XML-RPC 协议？

【注意:这种*拥抱&扩展*的策略，或者更广为人知的说法是“*复制&杀死*”正是微软在网络标准上使用的创造专有知识产权的策略。谷歌是新的微软吗？]

我必须承认，当我第一次看到这个公告时，我非常惊讶，因为我原本预计谷歌会采用 Atom 1.0 发布协议。[ **注意**:这个链接是 Joe Gregorio 的一个精彩的在线演示，描述了 XML-RPC 从发展到 MetaWeblog API 再到今天的 Atom Publishing Protocol (APP)的演变]

工程副总裁 Adam Bosworth 是 Atom 的忠实支持者。去年四月的[采访](https://web.archive.org/web/20160528232854/http://www.itconversations.com/shows/detail571.html)暗示了 ping 服务器使用 Atom (XML 数据)存储的可能性，这将使人们能够使用 Gdata 协议查询 Ping 服务器(Atom 存储),使用 Google 编写的查询扩展或通过 HTTP 的 GET 方法。
这是我的看法。谷歌仍在推进他们使用 Atom 商店和 Gdata 的计划，但没有多少人使用过 Gdata 协议。Google 的新版本 Blogger 可能会实现 Atom 发布协议 POST 方法，以便在有新条目时提醒这个新的 Google Ping 服务器，并支持 Gdata 协议来查询和删除条目。

我猜想今天的公告是为了确保使用 XML-RPC ping 通知方法的遗留应用程序(如 Typepad、WordPress 和 Spaces)将快速帮助填充 Google Ping 服务器。

向前发展，Atom 发布协议 1.0 是最好的方法。

> “美国情报社区元数据工作组发布了一项建议,建议情报社区随着时间的推移，逐步采用 Atom 联合格式作为社区基于 XML 的标准联合供稿语言。”– 23/09/2006