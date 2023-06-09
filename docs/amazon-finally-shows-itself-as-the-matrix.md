# 亚马逊最终展示了自己的黑客帝国 

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2005/11/04/amazon-finally-shows-itself-as-the-matrix/>

亚马逊的新产品 [Mechanical Turk](https://web.archive.org/web/20221129070259/http://www.mturk.com/mturk/welcome) 非常出色，因为它将帮助应用程序开发人员克服某些类型的问题(为新类型的应用程序创造了可能性),同时也有些可怕，因为我无法摆脱“我们都连接到一台机器上”的愿景。

“机器”是亚马逊称之为“人工智能”的网络服务如果你需要一个在现有技术下只有人类才能完成的过程(判断呼叫、文本起草或编辑等)。)，您可以简单地向服务发出请求来完成该过程。然后，机器将与志愿者一起完成任务，并将结果返回到您的软件中。

志愿者为每项任务支付不同的金额，赚到的钱存入他们的亚马逊账户。亚马逊为请求者支付的费用保留 10%的利润。

> 今天，我们基于计算机擅长的事情构建复杂的软件应用程序，例如存储和检索大量信息或快速执行计算。然而，在完成像识别照片中的物体这样简单的任务方面，人类仍然明显优于最强大的计算机——这是儿童甚至在学会说话之前就可以做到的事情。
> 
> 当我们想到人和计算机之间的接口时，我们通常假设人是请求完成任务的人，而计算机正在完成任务并提供结果。如果这个过程反过来，计算机程序可以要求人类执行一项任务并返回结果，会怎么样？如果它可以协调许多人类来执行一项任务会怎么样？
> 
> Amazon Mechanical Turk 为计算机提供了一个 web 服务 API，通过向人类发出请求，将人工智能直接集成到它们的处理中。开发人员使用 Amazon Mechanical Turk web 服务 API 向 Amazon Mechanical Turk 网站提交任务，批准已完成的任务，并将答案合并到他们的软件应用程序中。对于应用程序来说，事务看起来非常像任何远程过程调用——应用程序发送请求，服务返回结果。事实上，人类网络通过访问网站，搜索和完成任务，并为他们的工作获得报酬来推动这种人工智能。
> 
> 所有软件开发人员需要做的就是编写正常的代码。下面的伪代码说明了这有多简单。
> 
> 阅读(照片)；
> photoContainsHuman = callMechanicalTurk(图片)；
> if(photoContainsHuman = = TRUE){
> accept photo；
> }
> else {
> 拒绝照片；
> }

“机械土耳其人”这个名字很棒，因为它指的是 18 世纪制造的一台与真人下棋并经常击败他们的机器。然而，将近一百年后，人们终于发现这台机器实际上是由藏在里面的一个人驱动的。今年早些时候，我实际上读过一本关于这种机器的书，当时我在出差，这是我能找到的全部资料。

这可以用于很多任务。所以插上~~矩阵~~机试试吧。

更多信息请见[罗布·霍夫](https://web.archive.org/web/20221129070259/http://www.businessweek.com/the_thread/techbeat/archives/2005/11/amazons_mechani.html?campaign_id=rss_blog_blogspotting)、[格雷格·亚德里](https://web.archive.org/web/20221129070259/http://www.yardley.ca/blog/index.php/archives/2005/11/04/mechanical-turk-genius/)和[其他人](https://web.archive.org/web/20221129070259/http://tech.memeorandum.com/051104/p53#a051104p53)。