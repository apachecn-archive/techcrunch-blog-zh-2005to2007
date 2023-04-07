# 让我们分享一些文件——比较四种服务

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2006/08/24/lets-share-some-files-four-services-compared/>

文件共享长期以来一直是互联网的流行应用。我记得我坐在我的笔记本电脑前，让一个朋友给一首歌命名，然后看我能否从 Napster 下载这首歌，并在他找到架子上的 cd，放入播放器并自己播放这首歌之前播放它。我经常赢得那些比赛。

旧的 Napster 早已不复存在，但当然被许多其他 P2P 网络所取代。今天，互联网流量的很大一部分是由通过 bittorent 移动的文件组成的，bittorent 是一种流行的、完全分散的文件共享方式。

然而，Bittorent 需要一些基本的技术知识，既不匿名也不安全。RIAA 和美国电影协会定期监控这些网络，并试图收集他们认为涉及版权文件传输的计算机的 IP 地址。bittorent 因传输(有时)包含病毒、间谍软件和其他恶意软件的文件而臭名昭著。

进入私人文件共享网络。WASTE 于 2003 年发布，允许人们在信任的朋友之间创建私人网络。文件可以共享，而不用担心恶意软件或窥探。所需要的只是特定网络成员之间的信任。浪费的负面影响是建立和参与一个网络并不是一件轻而易举的事情。私有网络并没有起飞并实现大规模使用和采用。

最近出现了一批新的服务，使与朋友和其他受信任的人的私人网络共享文件变得更加容易。[所有同行](https://web.archive.org/web/20211027123044/http://www.allpeers.com/)、 [Zapr](https://web.archive.org/web/20211027123044/http://zapr.com/) 、 [Pando](https://web.archive.org/web/20211027123044/http://www.pando.com/) 和 [Exaroom](https://web.archive.org/web/20211027123044/http://www.exaroom.com/) 都是相当新的进入者。

**所有同行**

 [](https://web.archive.org/web/20211027123044/http://www.allpeers.com/) [我们从一开始就关注](https://web.archive.org/web/20211027123044/http://www.beta.techcrunch.com/tag/allpeers)布拉格/英国的[所有同行](https://web.archive.org/web/20211027123044/http://www.allpeers.com/)，非常熟悉这个产品。

Allpeers 是一个 Firefox 插件，使用 bittorent 技术来完成文件传输，显然即将推出。您将朋友添加到您的 AllPeers 网络，然后从他们那里发送和接收文件。界面很直观，而且对文件大小或传输量没有限制。AllPeers 非常容易使用，允许传输文件和/或文件夹，可以在任何运行 Firefox 的机器上运行。我们还通过传输非常大的文件，关闭 Firefox，然后在传输过程中关闭电脑，对产品进行了压力测试。Firefox 一重新开放，AllPeers 就从中断的地方开始了工作，这很好。

像其他人一样，AllPeers 是免费的。但是，与 Pando 和 Zapr 不同，AllPeers 无需先通过电子邮件确认即可完成文件传输。但是，传输的所有方面都必须在 Firefox 上安装所有对等设备。

Zapr

 [](https://web.archive.org/web/20211027123044/http://www.zapr.com/) 位于悉尼和新加坡的 [Zapr](https://web.archive.org/web/20211027123044/http://www.zapr.com/) ，我们[在这里](https://web.archive.org/web/20211027123044/http://www.beta.techcrunch.com/2006/08/10/zapr-makes-drag-and-drop-file-transfer-easy/)进行了简介，本周早些时候开放了公开测试——你可以在这里注册[。](https://web.archive.org/web/20211027123044/http://www.zapr.net/signup.aspx)

Zapr 是一个可下载的应用程序，看起来和感觉上很像一个即时消息客户端。你可以将文件拖到 Zapr 中，然后发送到一个电子邮件地址或 Zapr 用户名。收件人会收到一封包含该文件链接的电子邮件。单击该链接将通过浏览器启动文件下载。文件大小没有限制。

Zapr 没有在后端使用 bittorent，并且在传输之前没有将文件上传到它的服务器。文件直接从一台计算机传输到另一台计算机，并且需要发送者在线才能正确传输文件。这也意味着，如果一个用户与 100 个人共享一个文件，这将触发来自该用户计算机的 100 个不同的下载，这将占用带宽，并很可能破坏个人传输。出于这个原因，Zapr 并不是一个真正的私人共享网络，而是一个启动一对一传输的简单方法。当传输停止时，我们在重新启动传输时也遇到了问题。此外，任何访问该链接的人都可以下载该文件。

Zapr 建立在。NET 平台，因此只能在 Windows 机器上使用。

总的来说，我们喜欢 Zapr 的用户界面，但它目前的局限性使它明显不如 AllPeers 或 Pando 有用。值得注意的是，在这四项服务中，Zapr 是唯一一项不要求接收者在电脑上安装 Zapr 软件的服务。

**潘多**

总部位于纽约的 Pando 公司的软件下载量最近达到了 100 万次。Pando 是运行在 Windows 或 Mac 机器上的桌面应用程序。用户将文件拖入应用程序，并告诉它要发送给谁的电子邮件地址。多个收件人没问题，Pando 可以传输文件夹或文件。

Pando 有一个智能的、基于 bittorent 的后端。当你发送一个文件时，Pando 做的第一件事就是把它上传到它的服务器上。收件人直接从发件人以及 Pando 服务器接收文件，如果有多个收件人，bittorent 效率效应就会真正发挥作用，因为所有收件人都会成为发件人。

收件人会收到一封电子邮件，并通过打开一个小附件来启动传输(您必须有 Pando 来下载文件)。

Pando 是一项高效且用户友好的服务。我们希望看到它无需点击电子邮件附件就能启动转账，添加好友列表将是一个很好的方式，可以减轻重复输入经常与你分享的某人的电子邮件地址的烦恼。

**检查室**

于 2006 年 7 月底推出的旧金山 exa room(T21)是一项只支持 Windows 的服务，需要下载。安装后，用户可以与其他 exaroom 用户共享其“我的文档”文件夹中的文件。可以通过应用程序界面查看新的共享文件，并通过浏览器下载管理器完成下载。

Exaroom 是一个让你的 My Documents 文件夹永久与某些朋友共享的好方法，但与其他服务相比，它缺乏功能，这使它成为一个不太有用的产品。

**总结**

所有这四种服务都是与可信网络共享大文件的有用工具。

每一个对不同的目标都是有用的。然而，我们从这篇评论中排除的一个受欢迎的服务， [yousendit](https://web.archive.org/web/20211027123044/http://www.yousendit.com/) (这里是[的简介](https://web.archive.org/web/20211027123044/http://www.beta.techcrunch.com/2006/01/04/i-finally-got-you-send-it-to-work/))，也解决了向另一个人或一群人传输大文件的基本需求。如果你想创建一个长期的共享网络，Allpeers 是一个不错的选择。它具有平台灵活性(可在 Windows、Linux 和 Mac 上工作)，允许创建好友列表，从而可以随着时间的推移轻松进行多次传输，并且不需要使用电子邮件来确认文件下载。

感谢 Nick Gonzalez 对本文的研究帮助。