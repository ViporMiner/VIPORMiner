<div id="top"></div>

<div align="center">

# VIPORMiner

<h2>一款矿池级别的矿机管理运维系统👍 </h2>

<img src="/image/logo.png" alt="Logo" width="170">


[![VIPORMiner][VIPORMiner.io-badge]][VIPORMiner.io]
[![Downloads][downloads-badge]][releases]
[![Stargazers][stars-shield]][stars-url]

<a href="https://github.com/TLSminer/VIPORMiner">简体中文</a>｜<a href="https://github.com/TLSminer/VIPORMiner/tree/main/i18n">English</a>

强大且经验丰富的监控和记录系统可以立即解决矿场异常情况。

在矿池级别上统计哈希率，并可以一目了然地查看任何货币的哈希率。

根据终端设备自动调整工作模式和数据流量，避免高度低效的任务共享。

主动防御和过滤系统提高了环境的安全性并及时发现危险。

前端客户端具有高性能的TCP集成和压缩技术。无论矿场距离矿池有多远，它们都可以有效地减少矿场延迟并防止所有中间人攻击。

兼容各种算法的佣金系统可以合理地提高矿场利润。

内置算法引擎可以更新流行货币而不会产生热量。

仪表盘完美兼容各种设备，PC、MOBILE、PAD一目了然。

完美的控制逻辑，即使开启了服务费，矿池端也不会显示设备离线。

基于Rust的开发，高效的语言带来无与伦比的性能。

高性能，下一代运维体验，是由硅谷顶尖的研发团队和Cake专家带来的专业矿场运维系统-VIPORMiner

（部分预览）

<img src="/image/4.png" alt="Logo" width="670">
      <img src="/image/3.png" alt="Logo" width="670">

</div>



# 端口导入、导出

三种方式可以进行端口的导入导出, 此处仅强调EXCEL文件导入, 如需使用Excel导入, 请下载并参照Excel模板文件:

<a href="https://github.com/TLSminer/VIPORMiner/blob/a55555eeb4cc3b3cee851d0acbb5cb68423418d7/excel%E7%AB%AF%E5%8F%A3%E5%AF%BC%E5%85%A5%E6%A8%A1%E6%9D%BF.xlsx">下载Excel模板</a>

# 加入聊天组

QQ群：279505847

# 本地加密安全客户端下载地址RMS

https://github.com/TLSminer/RMS

<!-- Discord：<a href="sadfasfdasfsa">sadfasfdasfsa</a> -->

# 特别感谢

<img src="/image/icon-logo-blue.png" alt="Logo" width="100">

<img src="/image/poolin.svg" alt="Logo" width="100">

<img src="/image/5.png" alt="Logo" width="100">

<img src="/image/6.png" alt="Logo" width="100">

<img src="/image/bitmain.webp" alt="Logo" width="100">

<img src="/image/7.png" alt="Logo" width="100">

<img src="/image/8.png" alt="Logo" width="100">

<p>感谢以上矿池在一定范围内提供了技术支持😊</p>

# 支持的算法

对于支持的算法，相应的货币将随时热更新，客户端0将承担负担


| arithmetic      | Support     | Relevant currency |
| --------------- | ------------| ------------------|
| SHA256          | ✅          | BTC、BCH...        
| ETHASH          | ✅          | ETC、ETHW、ETHF、ETC+ZIL、ETHW+ZIL、ETHF+ZIL
| SCRYPT          | ✅          | LTC...
| KHEAVYHASH      | ✅          | KASPA...
| BLAKE2B         | ✅          | SC...
| OCTOPUS         | ✅          | CFX...

# 服务协议

VIPORMiner受香港法律监管。请注意，不同国家/地区的法律要求可能会限制此类产品和服务。因此，该产品和服务以及某些功能可能不可用，或者在某些司法管辖区或地区或某些用户中可能受到限制。您应该理解并遵守当地的法律法规。如果您使用此产品，默认代表将接受上述许可证。如果本产品引起的法律问题与本产品无关。


[VIPORMiner.io]: https://github.com/TLSminer/VIPORMiner
[VIPORMiner.io-badge]: https://img.shields.io/badge/VIPORMiner-v3.6.0-green?logo=VIPORMiner
[downloads-badge]: https://img.shields.io/github/downloads/ajeetdsouza/zoxide/total?logo=github&logoColor=white&style=flat-square
[releases]: https://github.com/TLSminer/VIPORMiner/releases
[stars-url]: https://github.com/TLSminer/VIPORMiner/stargazers
[stars-shield]: https://img.shields.io/github/stars/TLSminer/VIPORMiner.svg?style=flat
[stars-url]: https://github.com/TLSminer/VIPORMiner/stargazers

# 安装 

1. **Install**

   选择适合您的操作系统

   <details open>
   <summary>Linux</summary>

   > 运行以下shell指令以运行工具包
   >
   > ```sh
   >  bash <(curl -s -L https://raw.githubusercontent.com/TLSminer/VIPORMiner/main/install.sh)
   > ```
   >
   > 成功运行后，您将看到以下菜单。
   >

   </details>

   <details open>
   <summary>Windows</summary>

   > 请直接从此项目的Windows目录下载指定的版本：
   >
   > ```sh
   > https://github.com/TLSminer/VIPORMiner/tree/main/windows
   > ```
   >

   </details>

   Windows版本直接双击启动即可。

   Linux运行脚本后，输入1或2选择安装菜单语言, 随后弹出如下界面

   ---------- 中文菜单 ----------
   1. 安装
   2. 更新
   3. 启动软件
   4. 停止软件
   5. 重启软件
   6. 修改启动端口
   7. 解除Linux系统连接数限制（需要重启服务器生效）
   8. 设置开机启动
   9. 关闭开机启动
   10. 查看程序运行状态
   11. 查看错误日志
   12. 清理日志文件
   13. 查看当前WEB访问端口
   14. 卸载
   15. 重置认账号密码
   16. 安装指定版本
   [1-16]：
   
   <br>

   输入1安装即可

   安装完成后会输出以下提示

   |----------------------------------------------------------------|<br>
      程序启动成功, WEB访问端口4360, 默认账号 qzpm19kkx 默认密码 xloqslz913<br>
      如果您是默认密码及默认端口, 请及时在网页设置中修改账号密码及web访问端口。<br>
   |----------------------------------------------------------------|

   <br>

   看到以上提示代表安装已成功, 在浏览器内输入服务器IP:端口号, 即可访问后台。



# 更新日志
```
   3.6.0
   增加了后台https访问, 可在设置 -> https后台访问中设置, 
   或着从安装脚本中进行设置, 设置完后需要重启软件, 重启后需要使用指定协议(http或https访问)

   增加掉线提醒

   增加ip黑名单功能

   修复钱包替换功能无法清空的bug

   对已替换的钱包，在设备列表里给出钱包重定向的提示

   设备列表页的时间算力统计，现在可根据自己的选择统计任意时间段的算力数据

   增加了kas、eth的算力保护开关, 可自行斟酌在编辑端口中进行开启或关闭
   关闭算力保护后, 可抽到精准算力, 但是不对客户算力进行保护

   增加了eth并发优化的开关, gtv66机型需要关闭此开关, 默认开启

   稳定性提升 优化了极小概率矿池和矿机同时发生不稳定的情况下，导致连接数爆炸的问题

   修复了一个关联rms的小bug，修复编辑rust端口的时候导致rms矿机半天进不来的问题

   增加了所有ip访问的日志

   端口日志以及设备日志里的ip现在可以点击进行相关操作

   增加了更多的提示

   大幅优化页面流畅度

   页面细节优化

3.5.0
再次重构抽水算法及算力统计图表逻辑, 现在不管任何比例都能抽到精准算力, 不再因为比例设置越大, 少抽的越多

优化了蚂蚁出产的ks3机器

增加了kenc协议以及socks5(下版本开放socks5)协议, 现在可以直接在rust内开启这些协议

增加了CKB

增加了ZEN

增加了HNS

增加了LBC

修复了一些因为上游问题导致的算力统计没有清理掉的bug

修复了端口冲突后, 端口异常报错没有被清理掉的bug

关闭了动画效果 页面更流畅

增加了断线重连机制, 现在频繁断开的机器也能抽到相关算力

优化了仅有的一些无效率


3.4.1
[重要更新] 修复了BTC抽水不够的严重BUG

3.4.0
重构了算力统计, 现在vipor内算力统计精度大幅提升

得益于重构的算力统计, 现在btc的抽水更准确了

增加了替换钱包功能

优化了KA0 1 2 3 3l在鱼池内抽水的表现, 现在鱼池也可以抽到较为大量的算力了

增加了OCTA的支持

增加了KDA的支持

装配了cfx的算力计算单位

octa、etc等ethash算法币种, 不同协议的矿机币种在同一个端口工作，也可正常统计不同协议的算力了

3.3.0已发布 【RMS客户端发布】
修复无法导入配置的bug
增加程序更新日志
优化端口列表分类显示，增加了所有端口的显示
大幅优化ltc抽水精准度，提升其他币种计算以及抽水精准度
修复了部分etc机型无法连接的问题

RMS客户端下载地址 （RMS客户端需要VIPORMiner版本> 3.3.0才能正常使用） 教程和linux版本的安装教程随后编写, windows直接下载windows目录里的二进制文件即可
地址：https://github.com/TLSminer/RMS

3.2.4已发布
大幅提升当前支持的所有币种的算力统计及抽水的精准度

3.2.3已发布
彻底解决kas爆内存问题（1千台机器测试）

3.2.2+3.2.1合并发布
修复了kas缓慢爆内存的bug
修复了多台设备相同钱包但没有配置矿机名称导致的高无效bug

3.2.0已发布
增加了对k1矿池的支持
优化了蚂蚁矿池的连接次数统计
增加了kas系列机型币种对应的端口
彻底解除跨池抽水限制
开放了RMS服务的配置
优化了抽水的精准度，现在大算力波动的机器也能抽到较为精准的比例了
增加了清除单独矿机抽水的选项
持续优化算力统计

3.1.0已发布
调优ETC算法下新算法的表现
单台矿机详情页面增加平均算力统计信息

KAS专业机无损抽水！！！支持ks0，ks1，ks2，ks3l等机器！
humpool，herominer，kas-pool，tw-pool测试后抽1得1！！！
币印鱼池等可以抽到herominer池1207端口，低损耗！

3.0.0已发布

重构了抽水算法, 现在所有币种都可以精准到千分位的抽水了

在容易发生损耗的矿池和矿机, 现在能确保终端客户减少的算力不会大于设置的比例

ks0、ks1、ks2这种机器，基于现有算法保证客户最小的算力损耗，不同矿池可能抽到的算力也不同,  通常不会抽到设置的百分比算力，为了保证客户尽量少损耗只能这样啦

e9pro完美优化, 且rust内可计算出与矿池一致的算力

重构了界面, 增加了钱包列表、设备列表筛选条件等等

增加了单矿机抽水的设置

优化了算力统计, 现在算力统计不再凌乱

优化了无效

2.1.0已发布
彻底解决卡死问题

2.0.9已发布
解决卡死问题
优化抽水

2.0.8已发布
合并了两种抽水算法
再次修复假死

2.0.7已发布
修复了.6版本假死的问题
优化了均衡模式下的算力抽不够的问题

2.0.6已发布
优化了算力补偿, 现在隐藏掉了算力补偿的选项, 算力默认分配给所有矿机
优化了E9pro, 现在所有矿池的E9pro都可以跑满了, 且cake里计算的e9pro算力精准的与矿池一致
增加了一种抽水的模式
增加了一种连接矿池的模式
优化了大算力的矿机

2.0.5已发布
[重要更新] 修复了CAKE在windows下假死的bug
修复了kas冰河以及其他芯片机的高无效
兼容了etc gtv66芯片机，完善了etc的算力计算
修复了一些算力统计的bug

2.0.4已发布
优化了算力补偿默认模式,  进一步降低了无效率
优化了kaspa在不同矿池协议下的表现, 现在lolminer和gminer可以在所有矿池正常工作了
优化了etc相关算法的算力计算逻辑, 现在计算和抽水更精准了
底层优化,  提升了硬件利用率
优化份额显示bug
优化首页活跃分布列表

2.0.2
修复了一个并发导致的软件崩溃
算力统计优化

2.0.0
多处客户端细节优化

现在抽水精准度MAX

增加算力补偿配置, 现在端口上可以配置损耗的算力补偿

增加了断线重连机制，最大限度保证频繁掉线的矿机也可以正常抽水

修复kas高无效的bug

算法引擎底层更新重构, 开始飞速支持小币种了

增加了SC币种

增加了CFX币种

修复了LTC在viabtc内高无效的问题

修复LTC算力显示不准确的问题

修复了LTC算力损耗大的问题

解除配置抽水钱包数量限制

解除跨池抽水限制

优化了端口日志，增加了程序运行时日志, 开启了设备日志

底层优化, 避免了几处容易引发程序崩溃的bug

1.0.4
优化了一些BTC机型的效率，优化了viabtc以及蚂蚁矿池的拒绝率
优化了一个细节bug, 无效率进一步降低
   
1.0.3
性能优化
增加了json、kt、excel格式的配置导入导出
   
1.0.2
底层重构，优化了多链接的处理与统计
针对e9pro进行了深度优化
开放错误日志
   
1.0.1
修复了因为链接导致的一些bug
   
1.0.0
公开测试版本发布
修复了证书相关问题
优化了e9pro
细节优化
   
0.9.999
修复了一个严重的安全漏洞
优化了所有币种的抽水逻辑
   
0.9.99
优化了一些btc的矿池
细节优化
   
0.9.98   
底层优化, 降低损耗
   
0.9.97
修复了程序假死的严重BUG

0.9.96
完美的btc&kaspa
多个细节修复

0.9.95
效率提升大大滴
多个细节修复

0.9.94
大大降低无效率

0.9.93
修复了一些bug
尝试使用新的方式解决延迟带来的无效

0.9.92
修复了部分内核kas连不进来的问题

完善了ltc小算力显示的bug

0.9.91
修复了热更新钱包导致程序崩溃的bug

修复了因为上个版本改动导致的kas无法正常工作的问题

0.9.9
优化了很多细节

优化的亚米设备

进一步降低无效的概率（尽管已经很低）

优化的内存和CPU使用率

0.1.4
优化e9以及e9pro

0.1.3
优化了蚂蚁s17

0.1.2
修复了Rust下多台设备任务混乱的严重问题

修正了kas无法接收任务的问题

0.1.0
内部测试版本
```
# 帮助

<span id="dingzhi"></span>

   
# Other issues
   
  
这是一个免费软件，不收取任何费用。从技术角度来看，它只需要终端设备计算能力的0.2%作为技术回报。由于不同货币的矿池逻辑，计费能力可能会上下波动。一般情况下，浮动范围不会超过+-%0.2
