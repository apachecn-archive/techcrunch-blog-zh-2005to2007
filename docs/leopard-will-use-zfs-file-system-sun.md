# Leopard 将使用 ZFS 文件系统

> 原文：<https://web.archive.org/web/http://techcrunch.com:80/2007/06/06/leopard-will-use-zfs-file-system-sun/>

[![lzfs.jpg](img/15fc7252becc2c3f73d8dd673e0689c7.png)](https://web.archive.org/web/20150626224000/http://old.crunchgear.com/wp-content/uploads/lzfs.jpg "lzfs.jpg")

今天，Sun 公司张开了大嘴，宣布苹果公司即将推出的美洲豹将使用的默认文件系统。(MAC 目前使用启用日志功能的 HFS+作为默认文件系统。)在孙的网站上可以找到关于优势的完整列表，但在快速浏览时，这一条引起了我的注意:

> 所有操作都是写入时复制事务，因此磁盘上的状态总是有效的。永远不需要 fsck(1M)ZFS 文件系统。每个数据块都经过校验和检查，以防止静默数据损坏，并且数据在复制(镜像或 RAID)配置中可以自我修复。如果一个副本被损坏，ZFS 将检测到它，并使用另一个副本来修复它。

哎呀，现在大爸爸乔布斯要生气了。

[视频公告](https://web.archive.org/web/20150626224000/http://www.sun.com/jsp_utils/rvideo.jsp?video=74cd4547-01df-440b-823d-48878ae34c73)【孙 via [Mac 辟谣](https://web.archive.org/web/20150626224000/http://www.macrumors.com/2007/06/06/zfs-to-become-default-file-system-in-leopard/)