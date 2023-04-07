# Google Gears 让开发者将应用离线 

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2007/05/30/google-gears-lets-developers-take-apps-offline/>

# 谷歌 Gears 允许开发者离线下载应用

明天，谷歌将为全球 5000 名开发者举办开发者日。大部分开发人员将聚集在圣何塞会议中心，听取谷歌工程副总裁杰夫·胡伯的主题演讲。在会议上，谷歌将概述他们的开发者战略。但是最大的宣布将是 [Google Gears](https://web.archive.org/web/20221224072038/http://gears.google.com/) ，一个开源浏览器插件，它将使开发者能够使用 JavaScript APIs 创建离线网络应用。作为一名开发人员，你将能够创建一个应用程序，保证它可以跨浏览器脱机和联机工作。

该插件是 Firefox 1.5+和 Internet Explorer 6.0+的 700K 下载版，安装了三个开发人员 API。一个 API 将处理数据对象的创建，以在本地存储应用程序信息，另一个将是用于搜索数据的 SQLite 关系数据库，最后一部分将启用异步 JavaScript，以便应用程序可以在后台同步数据，而不会使浏览器负担过重。关于 API 的更多信息可以在 [gears](https://web.archive.org/web/20221224072038/http://gears.google.com/) 网站上找到。

Gears 的第一个演示将用于谷歌阅读器，但预计会有更多的谷歌应用程序推出。Reader 将在用户界面上添加一个绿色的下载按钮。当您点按该按钮时，Reader 会将最后 2，000 封邮件下载到您的电脑，让您的电脑准备好脱机工作或在不稳定的互联网连接下工作。

下载将在后台进行，使用异步 JavaScript API。离线时，你可以阅读这些文章，并进行日常的分享和标记。当你重新上线时，只需点击按钮，Reader 就会将你的离线活动与他们的服务器同步。现在同步是手动启动的，但很容易看到，随着程序的发展，它会变得更加无缝。Gears 可以解决谷歌 AJAX 应用程序的大量数据开销问题，将更新推送到你的桌面，而不是减慢你的浏览器。

谷歌正在向开发者发布开源软件，以获得一些初步的反馈。他们还与 Opera、Mozilla 和 Adobe 等其他合作伙伴合作，将 flash 和 Apollo 集成到他们的系统中。

罗伯特·斯科博([报道](https://web.archive.org/web/20221224072038/http://scobleizer.com/2007/05/30/google-brings-developers-offline-with-gears-new-offline-reader/))和阿图尔·伯格曼([报道](https://web.archive.org/web/20221224072038/http://radar.oreilly.com/archives/2007/05/google_releases.html))也出席了新闻发布会。