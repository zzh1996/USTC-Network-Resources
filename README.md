# 中国科大网络资源一览

## 注意

**本文原载于 http://sqrt-1.me/?p=282 ，发表日期为 2016 年 1 月。现在部分内容已经过时，故迁移到 GitHub，希望大家可以通过 Issue 和 PR 的形式一起帮助维护这份文档。**

## 〇、前言

我们学校有丰富的网络资源供我们学生使用，仅仅以 ustc.edu.cn 结尾的域名就有[数百个](http://webscan.360.cn/sub/index/?url=ustc.edu.cn)，但我们大多数人对这些资源知之甚少。我经常看到同学在得知某个网站或者听说一种让下载速度更快的方法时，心想如果大一的时候就知道该多好啊！同时，学校官方辛辛苦苦搭建的网站或者花很多钱购买的服务，没有几个学生去用，也是一笔很大的浪费。于是我决定写这样一篇文章来总结一下我所知道的资源和相应的使用方法，如果有我没提到的或者错误的地方，欢迎提出 Issue 和 Pull request。

## 一、网络接入

* 网络通：  
当通过有线或无线的方式接入学校网络时，必须使用网络通才可以访问校外的互联网。网络通的官网是 wlt.ustc.edu.cn，开通方法、费用以及其他相关细节可以在[这里](http://netfee.ustc.edu.cn/faq/)找到。正常上网建议开通 20 块钱的，因为 10 块钱的只能访问部分网站。不开网络通的情况下只能访问校内和 ipv6 网站。

* 有线接入：  
图书馆、西区的网络自习室等地点有插网线的接口，可以使用有线网，自备网线，插上后登录网络通就可以使用，网速一般是 100Mbps（使用时最快可以达到 10M/s 以上），西图新装修的部分（包括自习室、学习空间、休息区等）网线是千兆（1Gbps）。

* 无线接入：  
校园很多地方都有校园网的 wifi，很多地方都同时有 2.4G 和 5G 频段，手机和电脑可以连接使用。网速快的时候 2.4G 频段可以达到 3~5M/s，5G 频段可以达到有线网的速度。

  * ustcnet（或 USTCnet）没有密码，连上后打开任何校外网页会跳转到网络通登录界面，登录即可使用。

  * ustc-guest 也没有密码，连接后需要输入手机号，并通过手机接收验证码使用。

  * eduroam 连接时需要验证，用户名和密码就是网络通的用户名和密码，其中用户名也可以是“网络通用户名@ustc.edu.cn”的形式。在地球上其他有 eduroam 热点的高校也可以使用我们学校的网络通登录，只不过必须使用有后缀的用户名形式，注意后缀是“@ustc.edu.cn”而不是“@mail.ustc.edu.cn”。**如果电脑连不上 eduroam，请参见[这里](http://bbs.ustc.edu.cn/cgi/bbscon?bn=USTCnet&fn=M55948FC7&num=7079)和[这里](http://www.ecampus.fudan.edu.cn/2262/list.htm)。**

  * ustc-Internet 没有密码，连接后应该可以直接上网。

  * 除此之外，有些地方有 SIST 这个 wifi，也可以登录网络通后使用。

网络通同一时间只能在一处登录，不能多台设备共用。eduroam 可以任意多台设备同时使用。

关于出口选择：看文献选 1 号出口（教育网），**下载东西选 9 号出口**（不限 p2p）。只有 1 号出口可以让其他人连接自己的端口。官方的解释在[这里](http://wlt.ustc.edu.cn/link.html)，知乎上面也有[相关的讨论](https://www.zhihu.com/question/38271609)可以参考。

[这里](http://linux.ustc.edu.cn/ap/)有热点的分布和当前用户数量统计，[这里](http://202.38.64.1/)可以查看全校网络的状态。如果需要测试网速可以到[这里](http://test.ustc.edu.cn/)。

* 其他热点：  
学校很多地方有 CMCC、ChinaNet 等热点，速度较快，也可以使用。

* 本科生宿舍上网：  
可以使用电信的天翼宽带，网速是 2M（256K/s）或者 4M（512K/s），网络和学校无关。如果离学校的热点比较近，也可以尝试在窗外用路由器桥接 ustcnet。也可以用手机的校园流量开热点给电脑用。

校园网的优势：免费下载文献、可以使用谷歌（包括谷歌邮箱）、可以使用 ipv6。

## 二、网站

* [www.ustc.edu.cn](http://www.ustc.edu.cn)（科大官网首页）：  
中国科学技术大学官网，似乎[新版](http://www.ustc.edu.cn/zh_CN/)更好看一些。

* [mail.ustc.edu.cn](http://mail.ustc.edu.cn)（科大邮箱）：  
每名学生可以申请一个以 @mail.ustc.edu.cn 结尾的邮箱，一般用于官方用途（比如提交一些申请、交作业、联系老师和助教、接收学校通知等）。申请时邮箱名建议正式一些，推荐姓名拼音。不要使用奇怪的名字，否则以后没办法修改。小技巧：  
有些浏览器保存密码时不能保存下拉列表的状态，每次登录都要选“@mail.ustc.edu.cn”，这时可以直接在用户名处填写“xxx@mail.ustc.edu.cn”，即使下拉列表选择了“@ustc.edu.cn”也可以正常登录。

* [lib.ustc.edu.cn](http://lib.ustc.edu.cn)（图书馆）：  
登录时学号的“PB”要改为“01”。登录后可以查询自己在图书馆借的书和应还日期，还可以在到期之前续借。通过荐购功能可以让图书馆购买当前没有的书或供不应求的书，也可以预约别人正在读的书。**在书籍查询页面可以下载到书附带光盘的文件。**不知道想借什么书时可以去[热门借阅](http://opac.lib.ustc.edu.cn/top/top_lend.php)看一看。绑定了邮箱和手机号之后，借阅的书要到期时还会有邮件和短信提醒。图书馆首页可以看到开放时间的通知。**学校还购买了种类很丰富的[数据库](http://lib.ustc.edu.cn/dbmap/)，在校内都可以免费使用。**

* [ic.lib.ustc.edu.cn](http://ic.lib.ustc.edu.cn/)（学习空间预约系统）：  
可以在线预约西区图书馆的学习空间，预约后刷卡即可进入，细节请查看网站的帮助。学习空间也可以在西区图书馆一楼的预约机器上预约。

* [202.141.162.24](http://202.141.162.24/)（自助打印复印管理系统）：  
首次登录用户名为学号，密码为空。可以在此上传文档后在西区和东区图书馆的自助打印机器上刷卡打印，也可以扫描后在这个网站上下载扫描的文档。

* [mis.teach.ustc.edu.cn](http://mis.teach.ustc.edu.cn)（综合教务系统）：  
用于选课、查成绩、教学评价等。大一军训期间学校会统一教学生如何使用并进行第一次选课，所以选课相关的操作此处不再赘述。登录后左侧的选课结果可以看到每学期选过的课，在这里也可以看到当前学期课程的**期末考试时间**（是在学期中不断更新的）。成绩查询可以查询每学期的成绩和总成绩，但查看单科分数之前要先进行教学评估。左侧联系方式可以看到每个学院教学秘书的联系方式。教务系统的[公共信息查询平台](http://mis.teach.ustc.edu.cn/search_public.html)可以查询**培养计划**（也就是每个院每学期要上的课表）、**空闲教室**、课程列表等信息。在[课程列表](http://mis.teach.ustc.edu.cn/kbcx.do)页面点击课程名称可以看到学分、考核方式、预修课程、教材等有用信息。

* [huodongweb.com](http://huodongweb.com/)（大学活动平台）：  
几乎所有活动的海报都会发到这里，也可以查看各个社团的信息等等。

* [ms.ustc.edu.cn](http://ms.ustc.edu.cn)（正版软件）：  
需要先在 i.ustc.edu.cn 登录。提供了**正版 Windows、正版 Office、正版 Matlab、正版福昕 PDF 套件、正版 NOD32 杀毒软件**等。

* [rec.ustc.edu.cn](http://rec.ustc.edu.cn)（睿客网）：  
每人拥有 **100GB 的云盘空间**，可以分享文件（可以设置为仅校内可见）。上面有**大家上传的很多资源**，也有很多课程。

* [cloud.ustc.edu.cn](http://cloud.ustc.edu.cn)（科大云）：  
学生都可以创建**免费的云主机**，可以选择 Windows 或 Linux 系统，两核心 CPU、40G 硬盘、4GB 内存，可以上网，可以拥有一个校内的 IP。在任何地方都可以使用网页版的 VNC 远程桌面操作。如果搭建服务器，仅校内可以访问。需要每个月延时一次，否则会被关机。

* [blog.ustc.edu.cn](http://blog.ustc.edu.cn)（科大博客）：  
可以免费申请的**博客空间**，基于 WordPress。域名是 xxx.blog.ustc.edu.cn 的形式，也可以使用自己注册的域名。

* [home.ustc.edu.cn](http://home.ustc.edu.cn)（个人主页）：  
每人拥有 300M 的免费 ftp 空间，可以用来搭建静态**个人主页**。由于是科大域名，显得比较正规。使用方法在[这里](http://home.ustc.edu.cn/)。

* [staff.ustc.edu.cn](http://staff.ustc.edu.cn)（教工个人主页）：  
教师的 ftp 空间和个人主页服务，如果知道老师的邮箱，可以通过“staff.ustc.edu.cn/~邮箱名/”来访问。

* [bbs.ustc.edu.cn](http://bbs.ustc.edu.cn)（瀚海星云 BBS）：  
学校的官方论坛，需要使用校内网络注册。当**需要和学校某些部门联系**时，在瀚海星云发帖是一个不错的选择，对应的版块会有官方人员回复。

* [mirrors.ustc.edu.cn](http://mirrors.ustc.edu.cn)（开源软件镜像）：  
提供很多**开源软件的镜像服务**，在校内使用速度很快（校外也很快）。如果你使用 Linux 系统，一定要把软件源设置为科大源，可以大幅加快安装软件的速度。Linux 系统的安装镜像也可以在这里下载。还有安卓源代码等等。

* [git.ustclug.org](http://git.ustclug.org)（GitLab）：  
像 GitHub 一样的**代码托管**和项目管理服务，支持私有项目。服务器在校内，访问速度比较快。

* [icourse.club](https://icourse.club)（评课社区）：  
**课程点评系统，选课之前可以看看上过这门课的人的评价，很实用。**你也可以去点评学过的课程，为以后学这门课的学生提供参考。

* [i.ustc.edu.cn](http://i.ustc.edu.cn)（校园信息门户）：  
一个单点登录系统，可以由这个网站登录学校的各种服务，也有各种通知和常用的链接。

* [www.teach.ustc.edu.cn](http://www.teach.ustc.edu.cn)（教务处）：  
可以查看教学日历（查询考试周、**放假开学时间**等）、查看各种交流实习的通知、甚至教学评估统计结果等。

* [www.bb.ustc.edu.cn](http://www.bb.ustc.edu.cn)（网络教学平台）：  
其中的bb代表blackboard，是一个网络的教学系统，很多老师喜欢在上面发通知、上传课件、留作业，也可以看其他课程的资源。

* [acm.ustc.edu.cn](http://acm.ustc.edu.cn)（Online Judge）：  
ACM 的训练系统，上面有很多算法题可以做，可以提交自己的代码进行评测。ACM 的迎新赛也在上面进行。

* [jxzy.ustc.edu.cn](http://jxzy.ustc.edu.cn)（大物实验）：  
大物实验成绩查询、课表查询，可以下载讲义、视频、软件和其他资源。

* [moocs.ustc.edu.cn](http://moocs.ustc.edu.cn)（慕课平台）：  
有一些课程可以在线学习。

* [sf.ustc.edu.cn](http://sf.ustc.edu.cn)（网上缴费系统）：  
可以用银行卡交学费和其他费用。

* [bookface.ustc.edu.cn](http://bookface.ustc.edu.cn)（南七书谱）：  
校内**二手书交易市场**。

* [icard.ustc.edu.cn](http://icard.ustc.edu.cn)（一卡通消费统计）：  
**一卡通消费分析**，统计自己的消费趋势、在各个食堂的消费比例等等。

* [ecard.ustc.edu.cn](http://ecard.ustc.edu.cn)（校园一卡通信息管理系统）：  
可以查询自己**一卡通的详细消费记录**，也可以挂失解挂。

* [infopublish.ustc.edu.cn](http://infopublish.ustc.edu.cn)（信息发布）：  
和教室、寝室门口电视上显示的内容相同，滚动播放**近期活动的海报**。

* [pxe.ustc.edu.cn](http://pxe.ustc.edu.cn)（网络启动服务）：  
从校园网络启动电脑，详见[这里](https://lug.ustc.edu.cn/wiki/server/pxe/start)。

* [zsb.ustc.edu.cn](http://zsb.ustc.edu.cn)（招生办）：  
发布自主招生和其他形式招生的信息、录取名单公示等。

* [welcome.ustc.edu.cn](http://welcome.ustc.edu.cn)（迎新网）：  
录取的新生可以由此注册科大邮箱、预定军训服装尺寸、查询寝室房间等。可以查询相同城市的人以便同行。

* [vi.ustc.edu.cn](http://vi.ustc.edu.cn)（科大文化）：  
**校名、校徽、校歌、校园风光**等资源的官方下载，还有**[科大 ppt 模板](http://vi.ustc.edu.cn/visual/201104/t20110428_104212.html)**。

* [grid.ustc.edu.cn](http://grid.ustc.edu.cn)：  
一个 FTP 搜索引擎。

* [ty.ustc.edu.cn](http://ty.ustc.edu.cn)：  
查询体测成绩。

## 三、手机 APP

* iUSTC：  
校车查询、科大地图（可以定位）等。

* 瀚海星云：  
瀚海星云 BBS 客户端。

完整列表及下载地址：[http://i.ustc.edu.cn/m/](http://i.ustc.edu.cn/m/)（安卓、iOS、Windows Phone 都有）。

## 四、其他

**支付宝可以给一卡通充值**，很方便，具体教程参考[这里](http://ustcnet.ustc.edu.cn/xyykt/fwzn/201501/P020150127370318796849.pdf)和[这里](http://bbs.ustc.edu.cn/cgi/bbscon?bn=SmartCard&fn=M541ED733&num=7519)。

中国科大图书馆的微信公众号绑定个人身份后可以方便的查询当前借阅、续借图书等等。

支付宝也可以给网络通付费，网络通欠费时提醒邮件里会有详细说明。
