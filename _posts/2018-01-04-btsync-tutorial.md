---
layout: post
title: Resilio Sync 介绍
category: software
tags: p2p
---
![](https://cdn.kelu.org/blog/tags/btsync.jpg)

# 一、什么是中心化分享

如下图所示，不管是论坛还是网盘，它们的性质其实是一样的，总绕不开一个“中心”服务器，用户只有从服务器端到本地这唯一的资源获取途径。一旦这个服务器出现故障，所有人都无法获取资源。

![](https://cdn.kelu.org/blog/2018/01/server-share.png)

# 二、什么是去中心化分享

互联网的发展的一个趋势是去中心化，一如最近如火如荼的区块链技术，本质上也是去中心化思维。

那么何为分布式分享？类似于 BT 种子下载电影，你所下载的电影数据不是来自某一个服务器，而是来自分享这部电影的某台电脑（如下图所示）。

![](https://cdn.kelu.org/blog/2018/01/bittorrent-share.png)

# 三、Resilio Sync 使用场景

什么能实现这种分布式的分享呢？那就是本文推荐的“Resilio Sync”。

Resilio Sync 是由BitTorrent公司开发的专有的对等网络数据同步工具，可在Windows、OS X、Linux、Android、iOS和FreeBSD上使用。其可在局域网、互联网上通过安全的、分布式的P2P技术在不同设备之间同步文件。

**个人办公**

同时可以在单位的电脑、家里的电脑同步。

但由于缺乏版本控制和非原子操作、乱序执行的原因，这个工具并不适用于团队协作。参考[《P2P 文件同步工具 BitTorrent Sync 是否适合用于团队协作？ - 卿培的回答 - 知乎》 ](https://www.zhihu.com/question/21243434/answer/17639037)

**小型CDN系统**

现在的CDN提供商不少，如果小网站，也可以用BTSync来同步放在不同网络（电信、移动、联通）上的服务器，再配上DnsPod的智能解析，比使用CDN要来的实惠。

**网站备份工具**

BTSync兼容多系统，可以在Windows、Mac、Linux上安装，我们可以利用它来备份VPS上的数据到本地电脑上。

# 四、如何使用

软件的使用很简单，下载安装稍微熟悉一下就能上手。

![](https://cdn.kelu.org/blog/2018/01/20180228140119.jpg)

## 安装

1.  下载安装包。打开 [官网](https://www.getsync.com/platforms/desktop/) ，选择对应的版本下载

## 下载（同步）

1.  使用秘钥下载。类似BLZAUABVOPOBJ5AUGKSQIRE7EMFK7QDAX 的秘钥；点击“添加文件夹”并选择“输入秘钥或链接”； 
    ![](http://ww3.sinaimg.cn/large/005P1HiVgw1f8emq8l28dj30lu0ibq5n)
2.  点“下一步”即可； **这里需要手动指定存放文件夹，建议自己新建一个文件夹存放**。
3.  分享给朋友。觉得这个资源不错，想分享给朋友，你只需要把光标悬停在该资源上面，然后点击最右边出现的“共享”。总共有三种共享方法： 

	*   链接共享；
	*   秘钥（Key）共享
	*   二维码共享（这三种共享方式的区别参加附录）。如下图所示 

## 发布

1.  我们也可以发布资源让网友下载，类似于BT下载的“做种”。点击“添加文件夹”并选择“标准文件夹”。
2.  选择要发布的资源。 
3.  开始做种。由于你尚未在网络中公开该资源的链接、秘钥或二维码，所以目前还没有人下载该资源，在线用户为0。 
4.  直接复制共享秘钥。你也可以直接右键该资源并点击“复制只读秘钥”，即可将秘钥保存到剪贴板中，并快速分享到任何位置。
5.  移除资源。如果你不打算继续做种，请右键该资源并点击“移除”，但是，和BT下载一样，如果已经有人100%下载，则他会继续做种，让后来的人也可以下载。

## 附录

### 链接、秘钥和二维码分享有什么区别？

1.  链接：连接中包含文件夹名，如果已经安装 BitTorrent Sync 2.0.0 及以上版本，可以直接点击，BitTorrent Sync 客户端会自动启动并帮你命名文件夹；链接适合放在自己的网站或博客上；缺点是链接太长，不是每个地方都可以发链接。
2.  秘钥：一段随机字符，可以方便地通过微信、QQ、贴吧、论坛共享；缺点是需要手动命名文件夹，而且下载前不知道该资源的内容。
3.  二维码：适合手机客户端扫码下载，手机客户端免费支持“选择性同步”。
