# znipinfo
本软件首发 蓝极站队 公众号
一键部署自己的ipinfo站点
在实战中，很多时候curl ipinfo想查看目标的互联网出口IP，就只能用通用的那些网站，但是很多防火墙策略都会把这些屏蔽掉，于是我想干嘛不自己搭建一个。
最近比较喜欢用rust写小工具，花了20分钟写了一个小web,一个二进制文件，直接一件部署自己的curl ipinfo站点。
可以自定义IP和端口，默认监听0.0.0.0:9115
浏览器访问显示html页面
curl访问，直接返回标准json数据
只编译了linux amd64的可执行程序，我觉得没人会在windows上部署这个web服务吧～～～～～～
