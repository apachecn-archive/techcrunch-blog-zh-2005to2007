# 快速嵌入代码，为任何网站添加评论 

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2006/11/29/quick-embed-code-to-add-comments-to-any-site/>

# 快速嵌入代码，为任何网站添加评论

[![](img/14cbd58458255532e112ba32297198de.png)](https://web.archive.org/web/20221208135824/http://js-kit.com/) 这可能不是一家数百万美元风险投资的初创公司，但[列夫·沃金](https://web.archive.org/web/20221208135824/http://lionet.info/)对社交网络的一个常见功能提出了一个优雅的解决方案，即评论。JS-Kit 是一个完全免费的小 javascript embed，它允许你在一行中向任何网页添加线程注释:

```
"<script src="http://js-kit.com/comments.js"></script>"

```

JS-Kit 通过运行 Lev 的 javascript 代码工作，该代码与网站的引用一起，从他的服务器获取适当的评论数据。CSS 可以完全定制注释，通过改变注释的“path”属性，可以在同一个引用 URL 上显示多个注释实例。这样你就可以有一个照片页面，每张照片都有独特的评论线索。然而，尽管 JS-Kit 允许很多定制，但它仍然缺乏完全集成的评论的一些更高级的管理功能，比如我们的 WordPress 博客。

Lev Walkin 是圣克拉拉的一名思科安全工程师，最初想出这个主意是为了帮助他的妻子，一名网页设计师，轻松地在她的网站上添加评论。

跳转之后，请随意测试脚本…

注意:如果你提供的话，JS-Kit 会把你的评论转发到你的邮箱。