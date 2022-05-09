## 闲鱼自动抓取/筛选/发送系统， idlefish / xianyu spider crawler sender program blablabla

#### 联系QQ （用QQ扫二维码，或者添加QQ号）
####  - 📫 联系本人 ...

* 购买软件、收购项目，可联系本人邮箱或添加QQ

* Email: 26010455@qq.com

* QQ: 26010455（添加请注明来意 否则不予通过）

![](demo/demo11.png)

#### 0506 v 1.1.16增加手机客户端。

1.1.16版本经过14，15代集中优化，目前已经稳定运行。详细版本目前会继承1.1.13的各个版本，并添加手机客户端APP

v 1.1.16 客户端APP demo

![](demo/demo202204.png)


#### 0315 v 1.1.16优化完毕，暂未上线。

1、适配最新版闲鱼至 7.3.80。

2、进一步优化采集效率。在不破解闲鱼程序，不绕闲鱼防护的前提下，进一步优化采集效率。

3、适配安卓6至10系统代码。


#### 0207 v 1.1.13可以上线了。

v 1.1.13版更新详情

1、 更新UI，更简洁，更美观。

2、 更新功能，由原来的普通版、AI两个小版本，增加到普通版（正式版）、AI版、速刷版、全数据版， 以及HTTP版。

    1） 正式版（普通版）与原来功能一样，只优化UI，及数据优化。
    
    2） AI版 增加了普通版的AI模块，自动识别闲鱼广告，自动识别关键词抓取结束。
    
    3） 速刷版 为追求速度和最新数据的客户开发，可以抓取特定时间内（如10秒内、10分钟内）、特定Tag（如5人以下想要）的数据。
    
    4） 全数据版 为某些不追求数据及时性，但倾向于数据更全更多的朋友。
    
    5） 新增加 HTTP版， 主要为局域网内多客户端访问的朋友设计，可以一台服务，多台显示。

v 1.1.13 demo

![](demo/demo202203.png)

v 1.1.13 http版demo

![](demo/demo202001.png)

![](demo/demo202202.png)


#### ---------- 2022年 更新 -------------

#### 1225 在优化基础上重构钉钉模块

#### 1225 优化数据库打开速度

#### 1225 优化钉钉发送格式模块

#### 1221 v 1.1.12 优化钉钉发送模块

#### 1213 v 1.1.12 添加AI智能模块


目前正在添加和优化AI搜索功能，可以AI智能跳过无效搜索，提高搜索效率。

![](demo/demo19.png)

#### 1212 v 1.1.11 

版本号从1.0 过渡到1.1
整个程序模块重构。
1.0.9 添加数据库监控模块
1.1.10 模块重构， 优化搜索分词模块。
1.1.11 继续优化了搜索分词模块

![](demo/demo17.png)


#### 1102 v 1.0.8 更新搜索入库分词优化

#### 10-30 v 1.0.8 更新预览图片。
![](demo/demo14.png)
![](demo/demo15.png)

#### v 1.0.6 更新黑名单。
可以在客户端添加黑名单。

![](demo/demo13.png)


#### v 1.0.5 更新bug
因为闲鱼价格过万会变换显示方式，导致程序无法识别。
更新价格显示方式。

#### v 1.0.4更次更新
为抓取程序重构代码，并升级UI

![](demo/demo12.png)


#### v 1.0.4更新抓取首页和数据库页面

再次更新，
将原来杂乱的列表型数据显示更新为表格，这样看起来就没有那么乱了。
更新下效果图：

![](demo/demo7.png)
![](demo/demo8.png)
![](demo/demo9.png)


#### v 1.0.3添加多终端采集

在分布式采集的基础上，再次添加同一终端上面的多线程采集，进一步提高采集效率。
采集端代码在原有基础上再次升级。


#### v 1.0.3已经升级完毕

抓取数据目前比较快的话，可以达到10秒钟入库体现，关键词多的话，会有一定延迟。


同时，数据库从本地移到服务器，开始使用远程连接和储存数据，更方便分布式搭建、站库分离，以及一服多客模式。

更重要的是，不再需要配制本地数据库，不会再因为本地数据库问题导致程序down掉。

虽然原来也写了自动化配制数据库的程序，但因为系统权限问题，始终不太理想。这次干脆干掉本地数据库，只需要一个客户端，为所欲为了。

![](demo/demo3.png)
![](demo/demo4.png)
![](demo/demo5.png)
![](demo/demo6.png)

#### v 1.0.1.2升级数据库启动文件，自动检测系统数据库配制情况。

#### 1 建议使用mongodb 4.2.14， 将mongod.exe移动到bin文件中

#### 2 运行数据库启动软件，自动建立数据库文件和日志文件。

#### 3 运行程序


![](demo/demo1.png)
![](demo/demo2.png)
![](demo/weixin.png)
