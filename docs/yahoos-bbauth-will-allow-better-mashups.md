# 雅虎的 BBAuth 将允许更好的混搭

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2006/09/29/yahoos-bbauth-will-allow-better-mashups/>

# 雅虎的 BBAuth 将允许更好的混搭

雅虎发布了名为 [BBAuth](https://web.archive.org/web/20211017150214/http://developer.yahoo.com/auth/) 的新产品，正好赶上今明两天的[黑客日](https://web.archive.org/web/20211017150214/http://www.beta.techcrunch.com/2006/09/22/more-details-on-yahoo-hack-day/)。这是非雅虎应用程序以安全的方式访问雅虎认证机制和用户数据的一种机制。

由于安全问题(更不用说公司通常认为用户数据是私有的了)，现在大多数 mashups 都不访问个人数据。典型的混搭例子是将谷歌或雅虎地图与其他数据混合在一起。但是很少有混搭的例子涉及到通过登录程序保护用户数据不受互联网其他部分的影响。

BBAuth 解决了在访问雅虎锁定的数据时出现的问题。使用 Yahoo 提供的工具，非 Yahoo 应用程序可以请求用户登录 Yahoo，并允许将 Yahoo 用户数据发送到非 Yahoo 应用程序。Yahoo'er [Dan Theurer](https://web.archive.org/web/20211017150214/http://www.theurer.cc/blog/2006/09/29/launching-the-un-launch-able/) 详细解释了它是如何工作的，并指出了他创建的两个测试应用程序。第一个[展示了如何通过雅虎凭证登录，第二个](https://web.archive.org/web/20211017150214/http://theurer.cc/code/sso)[展示了如何在雅虎之外访问雅虎照片数据。](https://web.archive.org/web/20211017150214/http://theurer.cc/code/auth)

有两部分需要验证。第一个是验证用户身份的单点登录工具。第二部分是一组 API，用于进入特定的雅虎服务并与用户数据进行交互。例如，Yahoo Photos API 允许其他应用程序上传照片、标记照片以及修改标题和描述。雅虎也在通过 BBAuth 开放雅虎邮箱。

![](img/41d41a906feb87801987721f7ea62fa1.png)

Dave Winer 说这是一件“大事”,我同意。看看雅虎的 Jeremy Zawodny 对 BBAuth 的评论。

值得注意的是，亚马逊正在用它的 [S3](https://web.archive.org/web/20211017150214/http://www.beta.techcrunch.com/2006/07/12/amazon-releases-early-info-on-s3-storage-use/) 存储产品做同样的事情(但方式有限)，易贝据说正在测试第三方认证，目的是验证(但不改变)用户反馈评级。