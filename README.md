# NanoPi R4S固件，自动编译更新插件和内核版本

### 默认编译

- 用户名：root 密码：password 管理IP：192.168.2.1

- 已开启SSH，可自定义选择编译，自动生成`.config`

## 目前的编译已修复卡刷无法开机的问题。

我的固件很挑卡。不过目前已解决了卡刷不开机的问题。

方法两种：

- 下载r2s固件刷到卡上，然后再刷r4s即可解决挑卡问题，就能开机

- 用软件卡写到一半就拔出，再写卡完了即可清除分区里的垃圾。（感谢Aney提供）

     以上这两种方法即可解决挑卡不开机问题！

     还有一件事 我的固件加了动态超频，不管热不热这是取决后台运行程序在跑什么。
 
     感觉很热  就加风扇，推荐 风扇6cm×6cm，薄1cm，usb也行 或者端子线zh1.5

### 提示

在你的存储库介绍中添加一些你构建的固件的元信息（比如固件体系结构和安装的软件包），这样可以节省其他人的时间。

### 版本日志 2.6版	

- 增新 OpenAppFilter插件 一键治疗熊孩子	

  家长对小孩上网行为进行管控，限制小孩玩游戏等	

  限制员工使用某些app， 如视频、招聘、购物、游戏、常用网站等	

  记录终端的上网记录，实时了解当前app使用情况，比如xxx正在访问抖音	

  在网络→应用过滤里

- 更新了passwall和ssrp

- 修复卡刷无法开机，再次优化	

- 修复小问题

### 版本日志 2.1号

- 增新完整语言

- 再次优化了ipv6功能

- 修复了小问题

### 版本日志 1.30号

- 增新了ipv6客户端，快速获取ipv6；

- 修复了ipv6情况下节点有时断开，提高上网质量；

- 修复了adguardhome插件无法启动问题，改为Lienol源码仓库的插件；

- 通过本地编译增加了华为拔号仿真（华为开源挖来的）提高任何协议拔号速度。

### 版本日志 1.18号

-  待机超10天无法上网,需要重启才解决（已修复）

- 再次增强DHCP稳定性，增加多种协议（已优化） 

- 优化DNS在加载情况下无法启动进后台（已增强） 

- 降级到DDNS版本，最新版有问题（已降级，不清楚没试过） 

- 再次添poeee拔号多种协议（后期提高拔号稳定） 

- 优化部分内核代码重新优化一下 

- 更新rk3399驱动（友善官网提供） 

- 更新网卡驱动 

- 修复了其他小问题

## 后续更新

