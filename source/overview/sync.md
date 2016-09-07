title: 实时数据同步 Sync
---
<h2 id='简介' class="article-heading top-heading">简介</h2>
**Sync 是野狗的核心实时通信引擎。** 用户在设备上对数据的任何修改，云端会自动推送到所有连接设备，毫秒可达。

![](/images/syncdevices.png)

首先通过 2 个例子，让你了解野狗 Sync 的强大之处。

第 1 个例子：打开 2 个浏览器，进入[在线画板](http://drawing.wilddogapp.com/)，这是通过野狗实现的在线画板，一个人画的画可以实时同步到其他连接的浏览器。

![](/images/sketchboard.png)

第 2 个例子：打开浏览器，进入[多人外太空对战](https://www.wilddog.com/examples/game#)，这是通过野狗实现的 H5 实时游戏，扫描二维码，立刻可以体验实时多端对战。

![](/images/starwar.png)

野狗 Sync 采用`本地操作，云端同步`。我们在每台设备上维护了一个数据副本，用户更改数据时，会优先对本地数据进行操作，再同步到云端。这样做能有效提升访问速度，同时很好地解决了网络不稳定时断网、离线问题。


## Sync 能做什么 
Sync主要应用在：基础实时通信、实时数据分发、数据持久化存储三个方向。以下介绍Sync常见的应用场景。

### 实时物联
- 支持智能家居设备远程操作及状态同步、消息推送，地理位置实时更新，大量设备集中控制，实时状态统计，设备故障等实时推送场景。

### 实时游戏
- H5 互动游戏中的操作实时同步；可配合白鹭引擎等第三方开发工具，开发强互动的 H5 3D游戏。[查看 Demo](http://starwars.wilddogapp.com/)

### 实时协作
- 适用于多人在线文档协同编辑，资料实时同步、在线问答、需求沟通、项目管理等场景。[查看 Demo](http://wildpad.wilddogapp.com/#1)

### 实时金融

- 适用金融服务中大量的 Sync 业务、包括股票行情、实盘演示；期货、黄金、债券、证券等金融领域的实时新闻推送。


### 实时定位

- 结合GPS数据，可以应用于外卖配送、物流定位等互动场景；也可应用于打车应用中的司机、乘客实时定位；社交应用中，最常见的场景就是：分享我的位置。[查看 Demo](http://geomap.wilddogapp.com/)



## Sync 解决的问题

### 改变通信方式
提升应用使用体验。帮助开发者将数据从一端迅速传递到另外一端，毫秒可达。

### 改变开发方式
让开发者避开基础设施的构建，只需不到原来一半的时间和成本，完成产品开发任务。

### 节省流量资源
让开发者避免长期购买带宽造成资源浪费，使用野狗来完成动态数据的海量分发。


## 数据访问控制

![](/images/protect.png)

野狗采用基于资源的数据访问控制列表(ACL)来进行数据保护。访问控制列表(ACL)采用类似 JavaScript 语法的表达式。更多具体细节，请参考 [规则表达式](/guide/sync/rules/introduce.html) 的文档。



 

  



