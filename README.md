## Mir2 in Javascript

![https://github.com/chenzhuo1992/Mir2/blob/master/README.gif](https://github.com/chenzhuo1992/Mir2/blob/master/README.gif?raw=true)

### 介绍

复刻2001年的Mir2，客户端使用Javascript+Canvas。

线上地址：[这里](http://122.114.162.204/login.html)（地图文件没传上去，太大了，有空再搞）。

作者QQ：272643575，基础库[Easycanvas](https://github.com/chenzhuo1992/easycanvas)，服务端使用Node.

服务器比较低配、部分类型检查没有完成，所以请高抬贵手，不要试图寻找bug……

素材源自盛大《热血传奇》等游戏、m6m等游戏素材网，只供学习使用。

### 杂项

- 性能方面没啥问题，我用我自己14年买的3000块钱的笔记本（独显都没有）可以保持不降帧；

- 上面那个gif的demo大概是8、9个周末的程度，目前还原了人物、装备、刷怪、战斗、背包等功能。可以联机，我自己的Mac和Windows联机效果正常；

- 代码还没放出来，图片资源几百兆，传上来太难了，我想想办法，看看能不能随便找几个图替代；

- 为什么服务端用Node？因为主要是试试Canvas动画的性能和扩展性，服务端用Node的话还可以复用一部分js逻辑；

- 因为从网上找的素材都是一张大图里几十个小元素，所以切图用脚本切的。脚本写的糙，所以人物可能有毛边，不是渲染问题；

### 架构

![https://github.com/chenzhuo1992/Mir2/blob/master/README.png](https://github.com/chenzhuo1992/Mir2/blob/master/README.png?raw=true)
