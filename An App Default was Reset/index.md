
### 补丁又闯祸：Windows 10 默认应用被重置 附解决方法
[来源](https://www.landiannews.com/archives/20966.html)

Update：微软已经发布补丁修复了这一问题，请各位及时安装 Windows Update 提供的补丁。

本文中提供的方法并非对所有[Windows 10](http://www.landiannews.com/archives/tag/Windows-10)版本都有效，最好还是通过安装补丁来解决。

[微软](http://www.landiannews.com/archives/tag/%E5%BE%AE%E8%BD%AF)近期在[Windows 10](http://www.landiannews.com/archives/tag/Windows-10)系统补丁上出的问题次数估计是之前一年的量了，这次出问题的还是 Windows 10 的更新更新补丁。

微软前几天向[Windows 10](http://www.landiannews.com/archives/tag/Windows-10)用户推送了 KB3135173 号累计更新补丁，这个补丁和之前补丁的情况差不多：部分用户死活安装不上。

除了没法安装意外还有更让用户蛋疼的问题：重置部分文件的打开默认应用。

鸭子哥是前天安装的这个补丁，当时安装还是比较顺利的、期间也没出现什么问题，不过昨天开始通知中心频繁通知有应用出现问题、某个格式的文件重置为系统默认。

昨天忘了截图刚刚写这篇内容的时候还在考虑配图怎么办的时候[Windows 10](http://www.landiannews.com/archives/tag/Windows-10)来了个神助攻：

补丁又闯祸：Windows 10默认应用被重置 附解决方法

就像这样的通知：**某个应用导致.amr 文件的默认应用设置出现问题，因此它已经重置为 Groove 音乐**。

这种关联应用被重置的包括 **Microsoft Edge（.html 文件）、视频（.mkv 文件）**等，鸭子哥出现的基本都是音乐类和视频类文件的默认播放器被重置的问题。

然而比较无奈的是你手动给改回你安装的其他播放器或者浏览器后，上述问题还会在某个时间点里再次出现。

有的时候还会比较集中的隔几分钟就弹一个，让你频繁的要去清除通知或者直接开启免打扰功能。

目前还不知道微软是否已经知道了这个问题以及何时提供解决方案和更新补丁，不过 WinHelpOnline 网站已经提供了一个临时解决方案。

下载这个注册表文件导入到本机注册表后，再去控制面板重新关联应用即可解决。

注册表下载地址：（部分无法使用百度云的地区请直接通过蓝点网下载服务器节点进行下载）

[百度云](http://pan.baidu.com/s/1o7zrHdK)
[节点](http://xiazai.landiannews.com/files/2016/02/w10_stop_reset_fileasso.zip)
[本站地址下载地址](\resource\w10_stop_reset_fileasso_2.zip)
