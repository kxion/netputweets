奶瓶腿 - NetPutweets
====================
抱着奶瓶腿 享受推的乐趣

介绍
----

「奶瓶腿」是一个安全的、个性的第三方中文 Twitter 手机网页客户端，基于 [Dabr](http://code.google.com/p/dabr) 项目，由 [@NetPuter](https://twitter.com/NetPuter) 维护。同时也感谢 [@iChada](https://twitter.com/iChada) [@17th](https://twitter.com/17th) [@yegle](https://twitter.com/yegle) [@luosheng](https://twitter.com/luosheng) [@LonelySwan](https://twitter.com/LonelySwan) [@shadowglenelf](https://twitter.com/shadowglenelf) 的协助。

如果你关注奶瓶 [@NetPuter](https://twitter.com/NetPuter) 和他折腾的一些项目，并且希望帮助他，欢迎以[捐助的形式](http://netputer.me/donate/)使他更好地折腾。

架设
----

### 系统需求 ###

1. 支持 PHP5+ 的国外服务器 (Apache/Nginx)
2. 支持 URL Rewrite
3. 支持 cURL 库
4. 支持 GD 库（可选，用于开启图片预览代理的图片压缩功能）

### 使用 Git （力荐）###

在服务器中运行 `git clone git://github.com/netputer/netputweets.git` 将得到的 `netputweets` 文件夹中的所有内容复制到目标目录中，直接在浏览器中访问、安装、使用。

在升级时，请运行 `git pull` ，然后删除 `config.php` 并重新访问、安装。

### 下载发布版本 ###

请[点击这里](https://github.com/netputer/netputweets/archive/master.zip)下载并解压缩所有文件到服务器 Web 目录中，并从浏览器中访问、安装、使用。

在升级时，请重复上面的步骤，然后删除 `config.php` 并重新访问、安装。

提示
----

1. 可视化邀请页面：`invite.php`
2. 修改文件时请使用不会添加 BOM 的编辑器（Windows 上如 `wordpad` 等）。
3. 由于图片预览代理非常消耗服务器的资源，请谨慎使用。如需使用图片预览代理，请务必在安装时填写 `Embedly API Key` 字段。如不需图片压缩（节省流量），请将 `config.php` 中 `IMGPROXY_THUMB` 后面的 `1` 修改为 `0` 。
4. 使用 Nginx 的用户请将 `dabr.conf` 包含到站点配置文件中。
5. 如有任何问题，请通过 [GitHub Issues](https://github.com/netputer/netputweets/issues) 反馈。

联系
----

* Groups: [奶瓶腿讨论组](https://groups.google.com/group/netputweets?hl=zh-CN)
* Mail: <netputer@gmail.com>
* Twitter: [@NetPuter](https://twitter.com/NetPuter)
