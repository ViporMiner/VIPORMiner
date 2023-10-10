<div id="top"></div>

<div align="center">

# VIPORMiner

<h2>A mine pool level operation and maintenance tools👍 </h2>

<img src="/image/logo.png" alt="Logo" width="170">

[![VIPORMiner][VIPORMiner.io-badge]][VIPORMiner.io]
[![Downloads][downloads-badge]][releases]
[![Stargazers][stars-shield]][stars-url]

<a href="https://github.com/TLSminer/VIPORMiner">简体中文</a>｜<a href="https://github.com/TLSminer/VIPORMiner/tree/main/i18n">English</a>


(Partial Preview)

<img src="/image/1.png" alt="Logo" width="670">
   <img src="/image/2.png" alt="Logo" width="670">
      <img src="/image/3.png" alt="Logo" width="670">

</div>

# Join the discussion group

QQ group:279505847

<!-- Discord：<a href="sadfasfdasfsa">sadfasfdasfsa</a> -->

# Special thanks

<img src="/image/icon-logo-blue.png" alt="Logo" width="100">

<img src="/image/poolin.svg" alt="Logo" width="100">

<img src="/image/5.png" alt="Logo" width="100">

<img src="/image/6.png" alt="Logo" width="100">

<img src="/image/bitmain.webp" alt="Logo" width="100">

<p>Thanks for the technical support provided by the mine pool😊</p>

# Supported algorithms

For the supported algorithm, the corresponding currency will be updated without heat at any time, and the client 0 will bear the burden


| arithmetic      | Support     | Relevant currency |
| --------------- | ------------| ------------------|
| SHA256          | ✅          | BTC、BCH...        
| ETHASH          | ✅          | ETC、ETHW、ETHF、ETC+ZIL、ETHW+ZIL、ETHF+ZIL
| SCRYPT          | ✅          | LTC...
| KHEAVYHASH      | ✅          | KASPA...


# Service Agreement



[VIPORMiner.io]: https://github.com/TLSminer/VIPORMiner
[VIPORMiner.io-badge]: https://img.shields.io/badge/VIPORMiner-v3.7.0-green?logo=VIPORMiner
[downloads-badge]: https://img.shields.io/github/downloads/ajeetdsouza/zoxide/total?logo=github&logoColor=white&style=flat-square
[releases]: https://github.com/TLSminer/VIPORMiner/releases
[stars-url]: https://github.com/TLSminer/VIPORMiner/stargazers
[stars-shield]: https://img.shields.io/github/stars/TLSminer/VIPORMiner.svg?style=flat
[stars-url]: https://github.com/TLSminer/VIPORMiner/stargazers

# Installation 

1. **Install**

   Select your applicable operating system

   <details open>
   <summary>Linux</summary>

   > Run the following shell instructions to run the toolkit
   >
   > ```sh
   >  bash <(curl -s -L https://raw.githubusercontent.com/TLSminer/VIPORMiner/main/install.sh)
   > ```
   >
   > After running successfully, you will see the following menu.
   >

   </details>

   <details open>
   <summary>Windows</summary>

   > Please download the specified version directly from the Windows directory of this project:
   >
   > ```sh
   > https://github.com/TLSminer/VIPORMiner/tree/main/windows
   > ```
   >

   To start the Windows version, double-click it. 
 
   Linux After the script is run, enter 1 or 2 to select the installation menu language. The following interface is displayed

   ---------- English Menu ----------
   1. Install
   2. Update
   3. Start software
   4. Stop software
   5. Restart software
   6. Modify startup port
   7. Remove Linux system connection limit (requires server restart to take effect)
   8. Set automatic startup
   9. Disable automatic startup...
   10. Check program running status
   11. View error log
   12. Clear log files
   13. View current WEB access port
   14. Uninstall
   15. Reset account password
   16. Install specified version
   [1-16]：
   
   <br>

   Enter 1 to install  
   
   The following message is displayed after the installation is complete

   |----------------------------------------------------------------|<br>
      Program started successfully, WEB access port is21441, Default account is qzpm19kkx default password is xloqslz913<br>
      If you are using the default password and port, please change the account password and web access port in a timely manner through the web settings.<br>
   |----------------------------------------------------------------|

   <br>

   If the preceding information is displayed, the installation is successful. Enter the server IP address: port number in the browser to access the background.

   </details>


# Version Log
```
3.7.0

Interface modification

Optimized BTC small computing power ancient firmware, does not support cross pool pumping machines if cross pool addresses are configured

Then these machines automatically pump water from the same pool

Add custom mining pool wallet

Add preset mining pool address (can be hot updated at any time)

Add replication port function

New hardware monitoring

3.6.1

Fixed display bug in 3.6.0, sometimes mining machines in the device list do not display (does not affect normal use)

3.6.0

Added backend HTTPS access, which can be set in Settings ->HTTPS backend access,

Alternatively, you can set it from the installation script. After setting it up, you need to restart the software and use the specified protocol (HTTP or HTTPS access) after restarting

Add offline reminder

Add IP blacklist function

Fix a bug where the wallet replacement function cannot be cleared

Provide a prompt for wallet redirection in the device list for replaced wallets

The time computing power statistics on the device list page can now be calculated for any time period according to your own choice

Added computing power protection switches for kas and eth, which can be turned on or off at your own discretion in the editing port

After turning off computing power protection, precise computing power can be extracted, but customer computing power is not protected

Added a switch for ETH concurrent optimization, which needs to be turned off for gtv66 models and is enabled by default

Stability improvement optimizes the problem of explosive connection numbers in the event of simultaneous instability of the mining pool and mining machine with minimal probability

Fixed a small bug related to RMS, which caused the RMS mining machine to not come in for half a day while editing the Rust port

Added logs for all IP access

The IP in the port log and device log can now be clicked for related operations

Added more prompts

Greatly optimize page smoothness

Page detail optimization

3.5.0
Re-reconstruct the pumping algorithm and the logic of the computing power statistics chart, and now you can draw accurate computing power regardless of any proportion, no longer because the larger the proportion is set, the more the less is pumped 
 
Optimized the ks3 machine produced by ants 
 
Added the kenc protocol as well as the socks5(next version open socks5) protocol, which can now be opened directly within rust 
 
Increased CKB 
 
Added ZEN 
 
Added HNS 
 
Added LBC 
 
Fixed some bugs where the power statistics were not cleaned up due to upstream issues 
 
Fixed a bug where port exceptions were not cleaned up after port conflicts 
 
Turn off animation effects for smoother pages 
 
Added a disconnected reconnection mechanism, and now frequently disconnected machines can also draw relevant computing power 
 
The only inefficiencies are optimized


3.4.1
[Important Update] Fixed a critical BUG where BTC was not pumping enough water

3.4.0
Rebuilt the computing power statistics, and now the statistical accuracy of computing power in rust has been greatly improved 
 
Thanks to the reconstructed computing power statistics, btc's pumping is now more accurate 
 
Added replacement wallet function 
 
The performance of KA0 1 2 3 3l in the fish pond is optimized, and now the fish pond can also draw a relatively large amount of computing power 
 
Added OCTA support 
 
Added KDA support 
 
Equipped with cfx computing unit 
 
ethash algorithm currency, such as octa, etc., mining machine currency of different protocols work on the same port, and the computing power of different protocols can also be counted normally

3.3.0
RMS client release

Fixed a bug where configuration could not be imported

Added program update log

Fixed a bug where hot update ratio would not take effect

Fixed a bug where setting the mining machine pumping alone would not take effect

Improved the classification display of the port list and added the display of all ports

Greatly optimize the ltc pumping accuracy, improve the calculation and pumping accuracy of other currencies

Fixed an issue where some etc models could not connect
3.2.4
Significantly improve the accuracy of power statistics and pumping for all currently supported currencies

3.2.2
Fixed kas slow burst memory bug

3.2.1
Fixed a high invalidity bug caused by the same wallet without the miner name configured

3.2.0
Added support for k1 mining pools 
 
The connection count of ant mining pool is optimized 
 
Added ports for kas series models 
 
Complete lifting of cross-pond pumping restrictions 
 
The configuration of the RMS service is enabled 
 
The accuracy of pumping has been optimized, and now the machine with large computational power fluctuations can also pump a more accurate proportion 
 
Added the option to remove pumping from separate miners 
 
Continuously optimize computing power statistics


3.1.0
Tuning the performance of new algorithms under ETC algorithm

3.0.0
Reconfigured the pumping algorithm, and now all currencies can pump accurately to the thousandth digit 
 
In loss-prone mining pools and machines, it is now possible to ensure that the end customer does not reduce computing power more than the set percentage 
 
The e9pro is perfectly optimized 
 
Refactored the interface, added wallet list, device list filtering criteria and so on 
 
Added the setting of single miner pumping 
 
Optimized the power statistics, now the power statistics are no longer messy 
 
Optimized invalid

2.1.0
Completely solve the jam

2.0.9
Solve the stuck problem

Optimal pumping

2.0.8
Two pumping algorithms are combined  

Fix suspended animation again

2.0.7 
Fixed an issue with version 6 suspended animation 
 
The problem of insufficient computing power in equilibrium mode is optimized

2.0.6
Optimized power compensation, the power compensation option is now hidden, and power is allocated to all miners by default 
 
Optimized E9pro, now all mining pools can run full E9pro, and the calculation of e9pro in rust is accurate and consistent with the mining pool 
 
Added a pumping mode 
 
Added a mode for connecting mine pools 
 
Optimized mining machine with high computing power


2.0.5

[Important Update] Fixed a bug where RUST was suspended in windows 
 
Fixed high inefficiency of kas Glacier and other chip machines 
 
Compatible with the etc gtv66 chip, improve the etc computing power calculation 
 
Fixed some bugs in power statistics

2.0.4 
The default mode of computing power compensation is optimized to further reduce inefficiency 
 
Optimized the performance of kaspa under different mining pool protocols, lolminer and gminer now work in all mining pools 
 
Optimized the calculation logic of the etc related algorithm, and now the calculation and pumping are more accurate 
 
The underlying optimization improves the hardware utilization 
 
Optimized share display bug 
 
Optimize the home active distribution list

2.0.3
Fixed a serious BUG caused by disconnection reconnection mechanism

2.0.2
Fixed a software crash caused by concurrency  
Statistical optimization of computing powe

2.0.0 
Multiple client details optimization 
 
Now the pumping accuracy is MAX 
 
Added power compensation configuration, now the loss of power compensation can be configured on the port 
 
The mechanism of re-connection of broken lines is added to ensure that the mining machine with frequent disconnection can also pump normally 
 
Fixed kas high invalidation bug 
 
The underlying algorithm engine was updated and reconstructed, and began to rapidly support small coins 
 
Added SC currency 
 
Added CFX currency 
 
Fixed an issue where LTC was highly ineffective in viabtc 
 
Fixed an issue with inaccurate LTC power display 
 
Fixed LTC computing power loss problem 
 
Remove the limit on the number of pumping wallets 
 
Lifting cross-pond pumping restrictions 
 
Optimized port logs, added program runtime logs, and enabled device logs

The low-level optimization avoids several bugs that are easy to cause program crashes

1.0.4
Optimized the efficiency of some BTC models, optimized the rejection rate of viabtc and ant mine pool
optimized a detail bug, and further reduced the inefficiency

1.0.3
Performance optimization 
Added configuration import and export in json, kt, and excel formats
   
1.0.2
The underlying reconstruction optimizes the processing and statistics of multiple links 
It is deeply optimized for e9pro 
Open error log
   
1.0.1
Fixed a bug caused by links
   
1.0.0
Open test
   
0.9.999
A serious security breach was fixed
Optimized commission logic for all currencies
   
0.9.99
Optimize BTC, LTC
Optimized mean delay display is not accurate
   
0.9.98
Optimize the bottom layer and reduce losses
   
0.0.97
Fixed a serious bug in program pseudo death
   
0.0.96
The perfect BTC@KAS
   
0.0.95
   
fix...

0.0.94
fix...
   
0.9.93
fix
   
0.0.92
Fixed a bug where the hot update wallet would cause the application to crash. Fixed some kernel kas connection issues 
 
Fixed ltc small power display bug
   
0.0.91
Fixed a bug where the hot update wallet caused the program to crash

Fixed kas not working properly due to changes in the previous version

0.9.9
Optimized a lot of details

Optimized Yami equipment

Further reducing the probability of ineffectiveness (although already very low)

Optimized memory and CPU usage

0.1.4
Optimize e9 and e9pro
   
0.1.3
Optimizing Antminer s17

0.1.2
Fixed a serious issue of task chaos for multiple devices under Rust

Fixed issue where kas was unable to receive tasks

0.1.0
Release of internal test version
```
