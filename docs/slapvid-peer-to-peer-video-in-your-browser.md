# 闹剧:浏览器中的点对点视频——技术危机

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2007/06/25/slapvid-peer-to-peer-video-in-your-browser/>

# 闹剧:浏览器中的点对点视频

[![slapvidlogo.png](img/566e4bebba6a19926fccd776cd2c1fe9.png)](https://web.archive.org/web/20211024093025/http://slapvid.com/) 网络视频是一个杀手级应用，但它也是一个带宽猪。[据《福布斯》](https://web.archive.org/web/20211024093025/http://www.forbes.com/intelligentinfrastructure/2006/04/27/video-youtube-myspace_cx_df_0428video.html)估算，阿卡米(Akami)或“聚光灯”等内容分销网络可以向分销商收取每分钟 1 美分左右的费用，而较大的分销商可以以 0.5 或 0.1 美分左右的价格获得交易。去年，据估计 Youtube 每月花费超过 100 万美元每天播放超过 1 亿个视频。作为回应，寻求廉价提供更高质量视频的视频分销商正通过对等网络将带宽负担推给用户。到目前为止，这已经广泛集中在较大的桌面播放器(Veoh，Joost，Babelgum)。视频播放器初创公司[想在你的浏览器中做点对点游戏。](https://web.archive.org/web/20211024093025/http://slapvid.com/)

Slapvid 作为一个 Java 小程序与一个 Flash 视频播放器结合运行。不幸的是，这意味着用户必须授权 300Kb 小程序第一次运行，但这仍然比一个成熟的浏览器插件需要更少的用户主动性。小程序在后台运行，管理要在播放器中显示的视频块的传送。

[![slapvidplayer.png](img/88b8e5f97823dadc92662787809c28ee.png)](https://web.archive.org/web/20211024093025/http://slapvid.com/) 当您第一次开始视频时，播放器直接连接到他们的中央视频服务器，下载足够的视频开始部分作为缓冲，同时对等网络开始工作。在此请求过程中，他们的服务器还会向您发回一份播放相同视频的 3 到 5 个对等方的列表。小程序然后在视频中寻找更远的对等体，以 64KB 块的形式获得视频的发送位。如果您没有收到其他人的回复，视频只会从中央服务器流出。

为了展示对等技术，他们开发了自己的 flash 播放器，可以在 5 分钟内显示 Youtube 上的热门视频。播放器将每个视频的短片混合在一起。点一下手就能看到整个视频。然而，由于中央服务器的带宽问题，对等技术只对一小部分用户开放。所有其他用户只会看到从 Youtube 上传的视频。为了保证你得到对等小程序，你可以申请 Techcrunch 阅读器的 100 个测试账户之一。跳完后可以看到视频播放器。

Slapvid 是由卡耐基梅隆大学的四名毕业生创立的 T2 Y 组合公司。