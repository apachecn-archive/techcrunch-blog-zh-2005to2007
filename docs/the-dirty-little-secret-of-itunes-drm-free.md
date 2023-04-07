# iTunes DRM 免费的肮脏小秘密

> 原文：<https://web.archive.org/web/http://techcrunch.com/2007/05/30/the-dirty-little-secret-of-itunes-drm-free/>

好吧，好吧，这其实并不令人震惊，但对于那些还没有考虑过的人来说，这是值得一提的。虽然 iTunes 现在提供无数字版权管理的音乐，但这并不意味着你可以随意分发它。

你看，像以前的 iTunes 曲目一样，m4a 文件嵌入了你的帐户信息。TUAW 的 Erica Sadun 写道:

> 你自己试试这个。
> 
> 1.发射终端。您需要熟悉命令行来执行这个检查。
> 
> 2.导航到您的一个 iTunes plus 下载。如果你有一个美国 iTunes 账户，你可以下载 iTunes plus“Ooh La”本周单曲。
> 
> 3.使用 UNIX“strings”命令查看数据中的文本，并使用 grep 搜索您的姓名。例如
> strings 01 \ Ooh \ la . m4a | grep name
> 或者，在“文本编辑”中打开所有字符串:
> strings 01\ Ooh\ La.m4a | open -f
> 
> 一句话:无 DRM 并不意味着苹果突然支持盗版。

就像我说的，不令人震惊，但在你开始疯狂上传专辑之前，请记住这一点。

[别放那首歌…](https://web.archive.org/web/20161022225815/http://www.tuaw.com/2007/05/30/tuaw-tip-dont-torrent-that-song/) [TUAW]