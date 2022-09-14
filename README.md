Xcode14：”Failed to prepare the device for development“解决

升级Xcode14后，顺带把手里的一台测试机也升级到了iOS15.7,结果出现提示：Failed to prepare the device for development。经过Clean,重装都无效，最后发现其他人也有类似的问题

https://developer.apple.com/forums/thread/714388

解决办法如下：

1、再保留Xcode14的同时，安装Xcode13.4.1，解压后，修改Xcode名称为Xcode13。

2、关闭Xcode14，使用Xcode13正常运行一遍后，再打开Xcode14就发现能正常连接了

期待后续Xcode的更新能修复这个问题。

毕竟特么需要保留两个Xcode的安装，那岂不是给我以磁盘不够的理由换M2吗？

没钱是原罪啊～
