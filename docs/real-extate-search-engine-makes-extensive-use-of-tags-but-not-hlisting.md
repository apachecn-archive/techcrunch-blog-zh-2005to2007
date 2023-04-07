# 真正的搜索引擎大量使用标签而不是列表。TechCrunch

> 原文：<https://web.archive.org/web/http://techcrunch.com:80/2006/08/31/real-extate-search-engine-makes-extensive-use-of-tags-but-not-hlisting/>

![](img/dda13d2d41bd6f67f6810685f0caa8f7.png)[【Extate.com】](https://web.archive.org/web/20130627213429/http://www.extate.com/ "http://www.extate.com")是一个全国性的房产搜索引擎，由私人投资的伦敦科技创业公司开发[。](https://web.archive.org/web/20130627213429/http://wck2.companieshouse.gov.uk/c79b60188b2d012d567f339ba361468f/compdetails)

Extate 的工作原理是每 24 小时抓取所有最大的全国房地产中介网站，为购房者提供最新的搜索结果。

它使用自然语言搜索查询功能，让任何人都能轻松找到合适的房产。即“Cookham Dean 房产 80 多万，带四间卧室”。

一旦你对你的财产清单感到满意，你可以保存它们，并通过电子邮件与他人分享。

我喜欢 extate 的一点是应用程序的简单性，以及利用大量元数据标签进一步过滤搜索标准的速度。例如，通过点击“ *Garage* ”标签，它会立即重新显示搜索结果，只显示那些被标记为有车库的酒店。这个动态过滤似乎使用了一个简单的列表扩展，但是我在客户端代码中找不到 xml 名称空间。

我希望在 extate 的未来版本中看到一些东西。首先是与映射解决方案的更好集成。点击地图链接，只需打开一个新的浏览器窗口，显示多地图位置。像 [OnOneMap](https://web.archive.org/web/20130627213429/http://www.ononemap.com/) 和 [Zoomf](https://web.archive.org/web/20130627213429/http://www.zoomf.com/) 这样的竞争网站广泛使用谷歌的地图混搭功能来组合数据。

另一个很好的功能是支持 [hListing](https://web.archive.org/web/20130627213429/http://microformats.org/wiki/hlisting-proposal) 和 geo 微格式。[微格式](https://web.archive.org/web/20130627213429/http://microformats.org/)是网页中标记[联系人](https://web.archive.org/web/20130627213429/http://microformats.org/wiki/hcard)、[事件](https://web.archive.org/web/20130627213429/http://microformats.org/wiki/hcalendar)、[评论](https://web.archive.org/web/20130627213429/http://microformats.org/wiki/hreview)、[地址](https://web.archive.org/web/20130627213429/http://microformats.org/wiki/adr)、[地理位置](https://web.archive.org/web/20130627213429/http://microformats.org/wiki/geo)以及其他公共发布的大量信息的微小标记。微格式经常发布在博客和提要中，但也越来越多地发布在其他类型的网页上，如事件数据库、社交网络档案、评论网站和联系信息页面。

hListings 微格式使待售商品能够被标记，这样微格式搜索引擎如 [Technorati](https://web.archive.org/web/20130627213429/http://kitchen.technorati.com/) 或分类网站如 [Edgeio](https://web.archive.org/web/20130627213429/http://www.edgeio.com/ "http://www.edgeio.com/") 可以帮助人们使用语义标记轻松找到它们。其他现实世界中支持列表的网站包括 Craigslist、eBay.com 和 Match.com

> “虽然产品和服务的描述在网上很常见，特别是在电子商务网站上，但我们提出了一个列表微格式，用于共享、搜索和联合信息，帮助匹配买方和卖方。这一提议遵循了 Edgeio、Craigslist、易贝和报纸分类广告等交易网站的常见做法。”

在很多方面，extate、OnOneMap 和 zoomf 都可以成为列表微格式分类网站的例子，但它们不是，这“不是”它们的错，因为目前没有英国的房地产代理商用列表微格式发布他们的房屋细节。如果他们这样做了，那么他们都可以简单地使用新的微格式 ping 服务—[ping erati](https://web.archive.org/web/20130627213429/http://uk.techcrunch.com/www.pingerati.com)——来动态捕获发布的房屋信息。

房地产代理商使用 hListing 微格式需要多长时间取决于 web 设计人员将微格式集成到他们的客户站点需要多长时间。为了使它更容易，Dreamweaver 刚刚发布了一个微格式扩展来帮助创建它们。

8 月 28 日发表的这篇[文章解释了更多关于微格式和当前存在的鸡和蛋的情况，人们说“如果最终用户没有直接的好处，我为什么要嵌入微格式标记，以搜索引擎或浏览器支持的形式”。它来了，希望很快。](https://web.archive.org/web/20130627213429/http://www.digital-web.com/articles/the_big_picture_on_microformats/)