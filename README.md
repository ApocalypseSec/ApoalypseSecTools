# <img src="images\Apocalypse.png" style="zoom:10%;" />

# 天启安全系统

# Apocalypse Sec System



![image](https://img.shields.io/badge/Author-Apocalypse-yellowgreen)  ![image](https://img.shields.io/badge/RE-V1-yellowgreen)  ![image](https://img.shields.io/badge/Platform-Windows-red.svg) ![image](https://img.shields.io/badge/WSL-Kali-9cf.svg) ![image](https://img.shields.io/badge/Property-%E6%AD%A6%E5%99%A8%E5%BA%93-brightgreen.svg) ![image](https://img.shields.io/badge/update-20230419-yellowgreen)



	本项目目前已获得部分作者授权：
	                        悬剑团队团长、7kbstorm、御剑、wgpsec团队、4ra1n、精灵、奶茶、V1ll4n 、Beichen，因部分作者实在是联系不上后续如果有其他作者可以给到授权，万分感谢。

**`关于工具`**

	    本软件提供的所有软件和资料均为软件作者提供及网友推荐发布，不得用于任何商业用途。用户可以自由选择是否使用本产品提供的软件。如果用户下载、安装、使用本产品中所提供的软件，即表明用户信任该软件作者，项目组对任何原因在使用本产品中提供的软件时可能对用户自己或他人造成的任何形式的损失和伤害不承担责任。
	
	  任何单位或个人认为通过本产品提供的软件可能涉嫌侵犯其合法权益，应该及时向项目组书面反馈，并提供身份证明、权属证明及详细侵权情况证明，在收到上述法律文件后，将会尽快移除被控侵权软件。本产品中的部分软件来源于互联网，由于某些不可抗力因素我们没能联系上软件作者，如果软件作者对使用本集成的系统提供下载、更新有任何异议，都欢迎与我们联系沟通。项目组将在规定时间内给予删除等相关处理。

**`天启安全系统下载地址`**

	    OVF版    https://www.123pan.com/s/DfdZVv-CjhNH.html
	    VMware版 https://www.123pan.com/s/DfdZVv-WjhNH.html

**`所有镜像包含AV环境以及纯净系统环境`**

	    https://www.123pan.com/s/DfdZVv-NjhNH.html
	    纯净系统（PureServer）：
	       CentOS764Bit root/Jinitaimei.1
	       Server_2008
	       Server_2012
	       Server_2016
	       Server_2019
	       ubuntu-22.10-desktop-amd64     apocalypse/Jinitaimei.1
	       ubuntu-22.10-live-server-amd64 apocalypse/Jinitaimei.1
	       Win_7
	       Win_8
	       Win_10
	     杀软环境（AV）:
	     Apocalypse360AV
	     ApocalypseDFAV
	     ApocalypseHRAV

**`系统简介`**

    - 基于Windows 10 企业版2021 LTSC 21H2 Build 19044.2486镜像制作；
    - 简版WSL Kali Linux 2022.1，并配置图形化模式；
    - 精简系统自带软件，适度优化；
    - 镜像容量84.5G，使用单磁盘文件存储，提升性能；
    - 建议运行环境：
      * vmware：16.0
      * 运行内存：8G
      * 固态硬盘：100G

**`制作声明：`**

    1. 所有的安装类软件均下载自软件对应的官方网站；
    2. 所有的绿色类软件均下载自果核剥壳。（https://www.ghxi.com/）；
    3. 部分授权类工具（破解版）及优秀的渗透工具来自pwn3rzs以及GitHub上各大优秀项目
    4. 本项目制作的初衷是快速搭建工作环境，工欲善其事，必先利其器；
    5. 本项目由于后期调试原因可能会遗留部分本人的信息，请直接忽视；
    6. 本项目坚决不接受也从未曾接受任何形式的赞助。

**`免责声明：`**

    1. 本镜像仅面向合法授权的企业安全建设行为，如您需要测试本镜像的可用性，请自行搭建靶机环境；
    2. 在使用本镜像进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权；
    3. 如您在使用本镜像的过程中存在任何非法行为，您需自行承担相应后果，作者将不承担任何法律及连带责任。

## `工具介绍：`

**`1. 漏洞扫描：`**
    **`C:\Penetration\ScanTools`**

    - Acunetix   V15.5.230326230     账号Apocalypse@admin.com 密码 hJPa1.wfe!
    - Nessus     V10.5.0 插件202303241005 账号 Apocalypse      密码hJPa1.wfe!
    - Appscan    V10.1.0(28223)
    - Invicti    V23.2
    - Goby       V2.0.5 beta
    - Xray       V1.9.4 COMMUNITY-ADVANCED
    - SuperXray  V1.6
    - Nuclei     V2.9
    - gorailgun  V1.4.6               密码三个空格
    - SqlMap     V1.7.1.5#dev
    - Metasploit V6.3.2-dev            账号 Apocalypse      密码hJPa1.wfe!

**`2. 信息收集：`**

​    **`C:\Penetration\CollectMessage`**

    - OneForAll子域名扫描    V0.4.5 #dev
    - subfinder子域名扫描    V2.5.5
    - JSFinder子域名扫描     
    - Maltego              V4.3.1
    - Spiderfoot情报查询    V4.0.0
    - Enscan企业信息查询     V0.0.5 
    - Fofa Viewer          V1.1.11
    - URL采集器             
    - Rad                  -V0.4
    - crawlergo            -V0.4.4
    - Waf识别               -V2.1.0
    - Kscan
    - WebRobot             -V1.8.2 
    - 御剑WEB指纹识别系统     -V1.0
    - 御剑端口扫描           -V0.95
    - RouterScan路由扫描    -V2.6
    - Namp                -V7.93
    - CDN查找           
    - DNSX                -V1.1.1
    - HttpX               -V1.2.6
    - WEB批量请求器         -V1.0
    - web站点发现           -V1.0
    - 7kbscan             -V1.6.2
    - dirSearch           - v0.4.2

**`3. 流量代理：`**

**`C:\Penetration\ProxyTraffic`**

    - Yakit      -V1.1.9-SP4
    - BurpSuite  -V2022.5.1
    - Charles    -V4.6.3
    - Proxifier  -V3.29
    - Fiddler    -V5.0
    - Wireshark  -V4.0.4
    - Clash      -V0.18.2
    - SSR        -V4.9.2
    - OpenVPN    -V11.38.0
    - v2rayN     -V5.34
    - Tor浏览器
    - 嗅探欺骗
              ArpChecker_1.0
              dsniff-2.3
              ettercap-0.8.3
              NetFuke
              NetFuke_1.07

**`4. 代码审计：`**

​    **`C:\Penetration\CodeAuditTools`**

    - FortifySca  -V22.2.2
    - MySQL实时监控工具 V1.1
    - Seay源代码审计系统  -V2.1

**`5. EXP利用:`**
     **`C:\Penetration\ExpolitTools`**

    - GitHack
    - svnExploit
    - Thinkphp利用
    - shiro
    - SpringBootExploit-1.3漏洞利用
    - Struts 2_v19.02_全版本过waf版
    - weblogic利用
    - OA综合
    - Gr33k漏洞利用工具
    - 漏洞库

**`6. 编程调试（含逆向）：`**
    **`C:\Penetration\DevTools`**

    - Idea
    - CLion
    - goland
    - WebStorm
    - PhpStorm
    - Microsoft VS Code
    - He3
    - IE调试工具
    - ida  7.7
    - x64dbg
    - PEID
    - C32Asm
    - Apifox
    - 吾爱破解专用版Ollydbg
    - Cheat Engine 
    - GIT
    - 脱壳脚本
    - JDK8-11-17版本切换

**`7. 权限维持:`**
     **`C:\Penetration\PostExploitation`**

    - Kali Linux 2022.1 WSL  账号 Apocalypse      密码Apocalypse
    - 中国蚁剑   -V2.1.15
    - 冰蝎      -V4.0
    - CobaltStrike  -V3.14-4.7全版本
    - GBByPass过阿里云盾
    - 哥斯拉    -V4.0.1
    - webshell免杀生成器

**`8. 内网漫游:`**
    **`C:\Penetration\IntranetTools`**

    - ABPTTS         内网穿透工具
    - AddUser        添加用户工具
    - NC             监听工具
    - ADExplorer     ldap工具
    - FScan          内网扫描工具
    - appinfo        内网扫描工具
    - BloodHound     域渗透分析工具
    - DefeatDefender 关闭defender工具
    - DomainTools    域渗透工具
    - EarthWorm      内网穿透工具
    - EasyPen-main   图形化安全扫描工具
    - ew             内网穿透工具
    - FRP            内网穿透工具
    - Neo-reGeorg    加密传输
    - nps代理工具      内网穿透工具
    - 端口转发
    - OTHER

**`9. 移动安全:`**
    **`C:\Penetration\AndroidTools`**

    - AndroidKiller
    - apktool
    - Apktool_Box
    - dex2jar
    - jadx-gui
    - jdGUI
    - QtAdb-beta1.6
    - 安卓逆向-小工具集

**` 10. 暴力破解:`**
    **`C:\Penetration\PasswordAttacks`**

    - Bruter口令爆破
    - crack常见服务弱口令爆破工具
    - phpMyAdmin暴力破解v1.3
    - Shell爆破
    - 超级弱口令爆破
    - 伏宸验证码识别
    - hydra
    - Access密码破解工具
    - fuzzDicts
    - pentestDicts
    - PWD密码生成
    - 品轩字典生成器V0.5
    - 正则匹配
    - 密码转换器
    - 二维码解码器
    - other

**` 11. 免杀工具:`**
    **`C:\Penetration\AntivirusTools`**

    - AniYa
    - 掩日
    - Darkarmour
    - 签名工具
    - UPX加壳
    - 虚拟机检测
    - 加壳工具
    - 遮天
    - 安装包制作工具
    - 绿化卸载制作工具

**`12. 应急响应:`**
    **`C:\Penetration\EmergencyResponse`**

    - BlueTeamTools
    - 电子取证
    - 日志分析
    - 流量分析

**`13. 远程连接:`**
      **`C:\Penetration\ConnectTools`**

    - AnyDesk
    - FileZilla
    - finalshell
    - MobaXterm
    - 穿山甲
    - WindTerm_2.5.0
    - 数据库跨平台利用工具
    - Navicat

**`14. 编辑工具:`**
     **`C:\Penetration\EditTools`**

    - Notepad--
    - 010Editor打开大文件
    - Typora
    - AllDup文件去重
    - 文件批量重命名
    - 文件对比
    - 字符串查找
    - 福昕高级PDF编辑器专业版
    - Json视图
    - Sublime
    - WinHex
    - XMind
    - copyq

**`15. 办公软件：`**
     

    - Microsoft Office Word
    - Microsoft Office Excel
    - Microsoft Office PowerPoint
    - Microsoft Office Visio
    - Microsoft Office Outlook
    - Microsoft Office Project
    - Skype for Business
    - 7Zip
    - 有道字典
    - CHROME

**`16. 系统导航：`**

    - Everything
    - Maye

**`17. 媒体播放`**
    

    - MirillisAction录屏
    - PotPlayer视频播放
    - 视频格式工厂
    - Snipaste截图
    - BT下载

**`系统安全`**
    

    - 火绒





**`系统预览：`**

<img src="images\ApocalypseSecSystem1.png" style="zoom:75%;" />

<img src="images\ApocalypseSecSystem2.png" style="zoom:75%;" />

<img src="images\ApocalypseSecSystem3.png" style="zoom:75%;" />

<img src="images\ApocalypseSecSystem4.png" style="zoom:75%;" />

<img src="images\ApocalypseSecSystem5.png" style="zoom:75%;" />

<img src="images\ApocalypseSecSystem6.png" style="zoom:75%;" />

<img src="images\ApocalypseSecSystem7.png" style="zoom:75%;" />

<img src="images\ApocalypseSecSystem8.png" style="zoom:75%;" />

<img src="images\ApocalypseSecSystem9.png" style="zoom:75%;" />

<img src="images\ApocalypseSecSystem10.png" style="zoom:75%;" />

<img src="images\ApocalypseSecSystem11.png" style="zoom:75%;" />
