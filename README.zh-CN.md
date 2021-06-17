<p align="center">
  <img src="https://up.sofianehamlaoui.fr/lockdoor/lockdoor_small.png">
</p>
<h1 align="center"> Lockdoor Pentesting Framework</h1>

# 目录

-   [目录](#table-of-contents)
-   [更新日志📌：](#changelog---)
-   [徽章📌 :](#badges--)
-   [支持我💰 :](#support-me--)
-   [贡献者⭐：](#contributors--)
-   [版本](#versions)
    -   [06/2021 : 2.3](#062021--23)
    -   [03/2020 : 2.2.3](#032020--223)
-   [博客和文章📰：](#blogs--articles--)
-   [简介📙：](#overview--)
-   [特点📙：](#features--)
    -   [渗透测试工具选择📙：](#pentesting-tools-selection--)
    -   [资源和备忘单📙：](#resources-and-cheatsheets--)
-   [截图💻：](#screenshots--)
-   [演示💻 :](#demos--)
-   [安装🛠️：](#installation-%EF%B8%8F-)
-   [锁门工具内容🛠️：](#lockdoor-tools-contents-%EF%B8%8F-)
    -   [**信息收集**:mag_right: :](#information-gathering-mag_right-)
    -   [**网络黑客**🌐 :](#web-hacking--)
    -   [**权限提升**⚠️ :](#privilege-escalation-%EF%B8%8F-)
    -   [**逆向工程**⚡:](#reverse-engineering-)
    -   [**手术**❗:](#exploitation-)
    -   [**贝壳**🐚:](#shells-)
    -   [**密码攻击**✳️:](#password-attacks-%EF%B8%8F)
    -   [**加密 - 解密**🛡️:](#encryption---decryption-%EF%B8%8F)
    -   [**社会工程学**🎭:](#social-engineering-)
-   [锁门资源内容📚：](#lockdoor-resources-contents--)
    -   [**信息收集**:mag_right: :](#information-gathering-mag_right-)
    -   [**加密**🛡️:](#crypto-%EF%B8%8F)
    -   [**手术**❗:](#exploitation-)
    -   [**联网**🖧 :](#networking--)
    -   [**密码攻击**✳️:](#password-attacks-%EF%B8%8F-1)
    -   [**后开发**❗❗:](#post-exploitation-)
    -   [**权限提升**⚠️:](#privilege-escalation-%EF%B8%8F)
    -   [**渗透测试和安全评估结果报告模板**📝 :](#pentesting--security-assessment-findings-report-templates--)
    -   [**逆向工程**⚡ :](#reverse-engineering--)
    -   [**社会工程学**🎭:](#social-engineering-)
    -   [**穿行**🚶 :](#walk-throughs--)
    -   [**网络黑客**🌐 :](#web-hacking--)
    -   [**其他**📚 :](#other--)
-   [**贡献**:](#contributing-)

# 更新日志📌：

#### 版本 v2.3 出来了！！

        - Fixing some CI 

        - making a more stable version 

        - new docker iaage build

        - adding packages for each supported distros

# 徽章📌 :

![made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)![Twitter](https://badgen.net/twitter/follow/S0fianeHamlaoui)![GitHub](https://badgen.net/github/release/SofianeHamlaoui/Lockdoor-Framework)![License](https://badgen.net/pypi/license/lockdoor)![TestedON](https://img.shields.io/badge/Tested%20on%20%20-Linux%20%26%20Windows-blue)

# 支持我💰 :

-   在贝宝上：[HTTPS://呜呜呜.PayPal.com/PayPal么2/Sofia呢ham老UI](https://www.paypal.com/paypalme2/SofianeHamlaoui)
-   桶地址：1

# 贡献者⭐：

![commits](https://badges.pufler.dev/contributors/SofianeHamlaoui/Lockdoor-Framework)

# 版本

#### 06/2021 : 2.3

-   配置文件检查。
-   更新工具。
-   通过 -v arg 显示 Lockdoor 的当前版本。
-   检查版本并要求可能的更新。
-   使定制变得更容易。
-   暂时没有添加工具。
-   修复 docker 错误配置，docker 版本现在可以完美运行。

    -   信息收集工具 (21)
    -   网络黑客工具(15)
    -   逆向工程工具 (15)
    -   开发工具 (6)
    -   渗透测试和安全评估结果报告模板 (6)
    -   密码攻击工具 (4)
    -   Shell 工具 + Blackarch 的 Webshel​​ls 合集 (4)
    -   演练和 Pentest 处理助手 (3)
    -   加解密工具 (2)
    -   社会工程工具 (1)
    -   权限提升脚本和漏洞利用所需的一切

#### 03/2020 : 2.2.3

-   信息收集工具 (21)
-   网络黑客工具(15)
-   逆向工程工具 (15)
-   开发工具 (6)
-   渗透测试和安全评估结果报告模板 (6)
-   密码攻击工具 (4)
-   Shell 工具 + Blackarch 的 Webshel​​ls 合集 (4)
-   演练和 Pentest 处理助手 (3)
-   加解密工具 (2)
-   社会工程工具 (1)
-   权限提升脚本和漏洞利用所需的一切
-   在 Kali、Ubuntu、Arch、Fedora、Opensuse 和 Windows (Cygwin) 上工作

#### 优酷视频：[关联](https://www.youtube.com/watch?v=_agvb29FQrs)

![Youtube](https://img.youtube.com/vi/_agvb29FQrs/maxresdefault.jpg)

# 博客和文章📰：

      * Reddit : https://www.reddit.com/r/cybersecurity/comments/d4hthh/lockdoor_a_penetration_testing_framework_with/
      * Medium.com : https://medium.com/@SofianeHamlaoui/lockdoor-framework-a-penetration-testing-framework-with-cyber-security-resources-sofiane-22fbb7942378
      * Xploit Lab : https://xploitlab.com/lockdoor-framework-penetration-testing-framework-with-cyber-security-resources/
      * Station X : https://www.stationx.net/threat-intelligence-17th-september/
      * Kelvin Security : https://blog.kelvinsecurity.com/2019/09/12/lookdoor-framework-a-penetration-testing-framework-with-cyber-security-resources/
      * All About hacking : https://www.allabouthack.com/2019/09/lookdoor-framework-penetration-testing.html
      * Wired Intel : http://wiredintel.bravehost.com/wired/2019/09/15/%F0%9F%94%90-lockdoor-a-penetration-testing-framework-with-cyber-security-resources

            * Social networks :
                  * LinkedIn :
                        * By Nermin S. : https://www.linkedin.com/posts/nsmajic_sofianehamlaouilockdoor-framework-activity-6578952540564529152-B-0P
                  * Twitter :
                        * By Me :D : https://twitter.com/S0fianeHamlaoui/status/1173079963567820801
                        * National Cyber Security Services : https://twitter.com/NationalCyberS1/status/1173917454151475202
                        * Xploit Lab : https://twitter.com/xploit_lab/status/1173990273644261376
                        * More : https://twitter.com/search?q=Lockdoor%20Framework
                        * More : https://twitter.com/search?q=Lookdoor%20Framework
                  * Facebook :
                        * By ME :D : https://www.facebook.com/S0fianeHamlaoui/posts/678704759315090
                        * National Cyber Security Services : https://www.facebook.com/ncybersec/posts/1273735519463836
                        * Xploit Lab : https://www.facebook.com/XploitLab/posts/2098443780463126
                        * Root Developers : https://www.facebook.com/root.deve/posts/1181412315364265
                        * More : https://www.facebook.com/search/top/?q=Lockdoor%20Framework
            * Youtube :
                  * My youtube video : https://www.youtube.com/watch?v=_agvb29FQrs
                  * The Shadow Brokers video : https://www.youtube.com/watch?v=6njKRrKQtow

# 简介📙：

_锁门_是一个框架，旨在**帮助渗透测试人员、漏洞赏金猎人和网络安全工程师**.
该工具专为基于 Debian/Ubuntu/ArchLinux 的发行版而设计，旨在为渗透测试创建类似且熟悉的发行版。但包含渗透测试人员最喜欢和最常用的工具。
作为渗透测试者，我们大多数人都有他个人的“ /pentest/ ”目录，所以这个框架正在帮助你构建一个完美的框架。
有了这一切！它使渗透测试过程自动化，以帮助您更快、更准确地完成工作
容易地。

# 特点📙：

## 渗透测试工具选择📙：

-   **工具**:**锁门**不包含所有的渗透测试工具，老实说！谁使用过您在所有渗透测试发行版中找到的所有工具？ Lockdoor 只包含渗透测试人员最喜欢和最常用的工具。


-   **什么工具**: 工具包含**锁门**是 Kali、Parrot Os 和 BlackArch 上最好工具的集合。还有一些来自其他黑客团队的私人工具，如 InurlBr、iran-cyber。别忘了我在 Github 上发现的一些非常棒的工具，这些工具是由一些完美的人制作的。


-   **轻松定制**：轻松添加/删除工具。

-   **安装**：您可以使用 installer.sh 自动安装该工具，手动或通过运行 Docker 映像。

## 资源和备忘单📙：

-   **资源**: 这就是**锁门**, Lockdoor 不只包含工具！ Pentesing 和安全评估结果报告模板、Pentesting 演练示例和模板等。


-   **备忘单**: 每个人都可能会忘记一些关于加工或工具使用的东西，甚至一些技巧。 Cheatsheets 角色来了！有关于所有内容、框架上的每个工具以及任何枚举、利用和后利用技术的备忘单。

# 截图💻：

| ![](https://sofianehamlaoui.github.io/junk/lockdoor/screenshots/installation-dir-1.png) | ![](https://sofianehamlaoui.github.io/junk/lockdoor/screenshots/verbosemode.png) | ![](https://sofianehamlaoui.github.io/junk/lockdoor/screenshots/RootMenu.png) | ![](https://sofianehamlaoui.github.io/junk/lockdoor/screenshots/infogath.png) | ![](https://sofianehamlaoui.github.io/junk/lockdoor/screenshots/webhack.png) | ![](https://sofianehamlaoui.github.io/junk/lockdoor/screenshots/exploitation.png) | ![](https://sofianehamlaoui.github.io/junk/lockdoor/screenshots/about.png) |
| --------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |

# 演示💻 :

| ![](https://sofianehamlaoui.github.io/junk/lockdoor/gifs/kali.gif) | ![](https://sofianehamlaoui.github.io/junk/lockdoor/gifs/ubuntu.gif) | ![](https://sofianehamlaoui.github.io/junk/lockdoor/gifs/archlinux.gif) | ![](https://sofianehamlaoui.github.io/junk/lockdoor/gifs/fedora.gif) | ![](https://sofianehamlaoui.github.io/junk/lockdoor/gifs/opensuse.gif) | ![](https://sofianehamlaoui.github.io/junk/lockdoor/gifs/windows.gif) |
| ------------------------------------------------------------------ | -------------------------------------------------------------------- | ----------------------------------------------------------------------- | -------------------------------------------------------------------- | ---------------------------------------------------------------------- | --------------------------------------------------------------------- |

# 安装🛠️：

> **推荐的使用 Lockdoor 的方法是拉取 Docker 镜像，这样你就不会
> 担心依赖问题。**

> -   **Docker Hub 上有一个 Docker 镜像，每次更新时都会自动重新构建：[HTTPS://湖北.docker.com/日/Sofia呢ham老UI/lock door](https://hub.docker.com/r/sofianehamlaoui/lockdoor).它最初是基于官方的 debian docker 镜像 (debian)。**

-   Docker 安装

    -   安装要求
        ```bash
               sudo apt install docker < Debian-based distributions
               sudo dnf install docker < RPM-based distributions
               sudo pacman -S docker < Arch-based distributions
               sudo zypper install docker < OS-based distributions
               sudo yum install docker < RH-based distributions
        ```
    -   运行容器

        ```bash
               1. *Pull lockdoor Docker Image:*
                    sudo docker pull sofianehamlaoui/lockdoor

        ```

        ```bash
               2. *Run fresh Docker container:*
                    sudo docker run -it --name lockdoor-container -w /Lockdoor-Framework --net=host sofianehamlaoui/lockdoor

        ```

        ```bash
               3. *Run Lockdoor Framework*
                    sudo lockdoor

        ```

        ```bash
               4. *To re-run a stopped container:*
                    sudo docker start -i sofianehamlaoui/lockdoor
        ```

        ```bash
               5. *To open multiple shells inside the container:*
                    sudo docker exec -it lockdoor-container bash
        ```
-   使用 LockAller - Lockdoor Installer

    > **使用脚本安装它可能需要一些时间，具体取决于系统上已安装的软件包。**在这里，您可以在没有预安装软件包的新 debian 发行版上找到全新安装：[11分钟]![](https://i.imgur.com/2yvXOYm.png)
    >
    > ```bash
    > git clone https://github.com/SofianeHamlaoui/Lockdoor-Framework.git && cd Lockdoor-Framework && chmod +x ./install.sh && ./install.sh 
    > ```

# 锁门工具内容🛠️：

## **信息收集**:mag_right: :

-   工具：
    -   dirsearch ：Web 路径扫描器
    -   brut3k1t：面向安全的暴力破解框架
    -   gobuster：用 Go 编写的 DNS 和 VHost 破坏工具
    -   Enyx : 一个 SNMP IPv6 枚举工具
    -   谷歌：针对目标域发起谷歌黑客查询
    -   Nasnum : NAS 枚举器
    -   Sublist3r：渗透测试人员的快速子域枚举工具
    -   wafw00f : 识别和指纹 Web 应用防火墙
    -   Photon：为 OSINT 设计的令人难以置信的快速爬虫。
    -   Raccoon：用于侦察和漏洞扫描的攻击性安全工具
    -   DnsRecon : DNS 枚举脚本
    -   Nmap：著名的安全扫描器、端口扫描器和网络探索工具
    -   sherlock : 在社交网络上查找用户名
    -   snmpwn：SNMPv3 用户枚举器和攻击工具
    -   Striker：攻击性信息和漏洞扫描器。
    -   theHarvester : 电子邮件、子域和名称 Harvester
    -   URLextractor : 信息收集和网站侦察
    -   denumerator.py ：枚举子域列表
    -   其他：我在某处收集的其他信息收集、侦察和枚举脚本。
-   构架：
    -   ReconDog : 侦察瑞士军刀
    -   RED_HAWK：用于信息收集、漏洞扫描和爬网的多合一工具
    -   Dracnmap：信息收集框架

## **网络黑客**🌐 :

-   工具：
    -   Spaghetti : Spaghetti - Web 应用程序安全扫描器
    -   CMSmap : CMS 扫描仪
    -   BruteXSS : BruteXSS 是一种在 Web 应用程序中查找 XSS 漏洞的工具
    -   J-dorker：来自 Bing 的网站列表抓取器
    -   droopescan：扫描仪、识别、CMS、Drupal、Silverstripe。
    -   Optiva：Web 应用程序扫描
    -   V3n0M：Python3.6 中针对 SQLi/XSS/LFI/RFI 和其他 Vulns 的 Pentesting 扫描器
    -   AtScan：高级 dork 搜索和大规模利用扫描器
    -   WPSeku：Wordpress 安全扫描器
    -   Wpscan ：一个用 python 编写的简单 Wordpress 扫描仪
    -   XSStrike：最先进的 XSS 扫描器。
    -   Sqlmap：自动SQL注入和数据库接管工具
    -   WhatWeb：下一代网络扫描仪
    -   joomscan：Joomla 漏洞扫描器项目
-   构架：
    -   Dzjecter：服务器检查工具

## **权限提升**⚠️ :

-   工具：
    -   Linux 🐧 :
        -   脚本：
            -   Linux_check Sec.是
            -   Linux_enum.是
            -   Linux_gather_files.是
            -   Linux_kernel_exploiter.评论
            -   Linux_PRI VE市场.朋友
            -   Linux_PRI VE市场.是
            -   linux_security_test
        -   Linux_exploits 文件夹
    -   窗户|窗户| ：
        -   Windows-PRI VE市场-check.朋友
        -   windows-privesc-check.exe
    -   数据库：
        -   猛禽\_udf.c
        -   猛禽\_udf2.c

## **逆向工程**⚡:

-   Radare2：类Unix逆向工程框架
-   VirusTotal : VirusTotal 工具
-   Miasm：逆向工程框架
-   镜像：反转文件的字节
-   DnSpy：.NET 调试器和程序集
-   AngrIo：用于分析二进制文件的 Python 框架（由 @Hamz-a 推荐）
-   DLLRunner ：用于沙盒系统中恶意软件分析的智能 DLL 执行脚本。
-   Fuzzy Server：一个使用预制 Spike 脚本攻击 VulnServer 的程序。
-   yara ：旨在帮助恶意软件研究人员识别和分类恶意软件样本的工具
-   Spike：协议模糊器创建工具包+审计
-   other : 其他地方收集的其他脚本

## **手术**❗:

-   Findsploit：立即在本地和在线数据库中查找漏洞
-   Pompem：漏洞利用和漏洞查找器
-   rfix ：帮助 RFI 开发的 Python 工具。
-   InUrlBr：搜索引擎中的高级搜索
-   Burpsuite：用于安全测试和扫描的 Burp 套件。
-   linux-exploit-suggester2：下一代 Linux 内核漏洞利用建议
-   其他：我在某处收集的其他脚本。

## **贝壳**🐚:

-   WebShells : BlackArch 的 Webshel​​ls 集合
-   ShellSum : 一种防御工具 - 检测本地目录中的 web shell
-   Weevely : 武器化的 web shell
-   python-pty-shells：Python PTY 后门

## **密码攻击**✳️:

-   crunch : 一个词表生成器
-   CeWL：自定义单词列表生成器
-   patator ：多用途暴力破解器，模块化设计，使用灵活

## **加密 - 解密**🛡️:

-   Codetective：确定所使用的加密/编码算法的工具
-   findmyhash：使用在线服务破解哈希的 Python 脚本

## **社会工程学**🎭:

-   scythe ：帐户枚举器

# 锁门资源内容📚：

## **信息收集**:mag_right: :

> -   [备忘单\_SMB 枚举](ToolsResources/INFO-GATH/CHEATSHEETS/Cheatsheet_SMBEnumeration.txt)
> -   [配置\_管理](ToolsResources/INFO-GATH/CHEATSHEETS/configuration_management.md)
> -   [域名解析\_枚举](ToolsResources/INFO-GATH/CHEATSHEETS/dns_enumeration.md)
> -   [文件\_枚举](ToolsResources/INFO-GATH/CHEATSHEETS/file_enumeration.md)
> -   [http\_枚举](ToolsResources/INFO-GATH/CHEATSHEETS/http_enumeration.md)
> -   [信息\_搜集\_卵泡\_指导](ToolsResources/INFO-GATH/CHEATSHEETS/information_gathering_owasp_guide.md)
> -   [迷你服务\_网络管理员\_枚举](ToolsResources/INFO-GATH/CHEATSHEETS/miniserv_webmin_enumeration.md)
> -   [小姐\_sql\_服务器\_枚举](ToolsResources/INFO-GATH/CHEATSHEETS/ms_sql_server_enumeration.md)
> -   [相同的\_枚举](ToolsResources/INFO-GATH/CHEATSHEETS/nfs_enumeration.md)
> -   [奥斯汀\_侦察\_ng](ToolsResources/INFO-GATH/CHEATSHEETS/osint_recon_ng.md)
> -   [被动的\_信息\_搜集](ToolsResources/INFO-GATH/CHEATSHEETS/passive_information_gathering.md)
> -   [流行音乐3\_枚举](ToolsResources/INFO-GATH/CHEATSHEETS/pop3_enumeration.md)
> -   [港口\_枚举](ToolsResources/INFO-GATH/CHEATSHEETS/ports_emumeration.md)
> -   [程序\_枚举](ToolsResources/INFO-GATH/CHEATSHEETS/rpc_enumeration.md)
> -   [扫描](ToolsResources/INFO-GATH/CHEATSHEETS/scanning.md)
> -   [中小企业\_枚举](ToolsResources/INFO-GATH/CHEATSHEETS/smb_enumeration.md)
> -   [smtp\_枚举](ToolsResources/INFO-GATH/CHEATSHEETS/smtp_enumeration.md)
> -   [smb\_枚举](ToolsResources/INFO-GATH/CHEATSHEETS/snmb_enumeration.md)
> -   [脆弱性\_扫描](ToolsResources/INFO-GATH/CHEATSHEETS/vulnerability_scanning.md)

## **加密**🛡️:

> -   [Crypto101.pdf](ToolsResources/ENCRYPTION/CHEATSHEETS/Crypto101.pdf)

## **手术**❗:

> -   [电脑\_网络\_漏洞利用](ToolsResources/EXPLOITATION/CHEATSHEETS/computer_network_exploits.md)
> -   [文件\_包容\_漏洞](ToolsResources/EXPLOITATION/CHEATSHEETS/file_inclusion_vulnerabilities.md)
> -   [文件\_转移](ToolsResources/EXPLOITATION/CHEATSHEETS/File_Transfers.md)
> -   [数控\_转移](ToolsResources/EXPLOITATION/CHEATSHEETS/nc_transfers.txt)
> -   [联网\_旋转\_和\_隧道](ToolsResources/EXPLOITATION/CHEATSHEETS/networking_pivoting_and_tunneling.md)
> -   [网络\_旋转\_技术](ToolsResources/EXPLOITATION/CHEATSHEETS/network_pivoting_techniques.md)
> -   [旋转](ToolsResources/EXPLOITATION/CHEATSHEETS/pivoting.md)
> -   [旋转\_](ToolsResources/EXPLOITATION/CHEATSHEETS/pivoting_.md)
> -   [上市
>     漏洞利用](ToolsResources/EXPLOITATION/CHEATSHEETS/Public%20Exploits.md)
> -   [撤销\_壳\_和\_毒液](ToolsResources/EXPLOITATION/CHEATSHEETS/reverse_shell_with_msfvenom.md)

## **联网**🖧 :

> -   [bpf\_句法](ToolsResources/NETWORKING/bpf_syntax.md)
> -   [备忘单\_联网](ToolsResources/NETWORKING/Cheatsheet_Networking.txt)
> -   [备忘单\_甲骨文](ToolsResources/NETWORKING/Cheatsheet_Oracle.txt)
> -   [联网\_概念](ToolsResources/NETWORKING/networking_concept.md)
> -   [映射\_快的\_参考\_指导](ToolsResources/NETWORKING/nmap_quick_reference_guide.pdf)
> -   [转储](ToolsResources/NETWORKING/tcpdump.pdf)

## **密码攻击**✳️:

> -   [密码\_攻击](ToolsResources/PASSWORD/CHEATSHEETS/password_attacks.md)
> -   [一些链接到词表](ToolsResources/PASSWORD/CHEATSHEETS/Some-Links-To-Wordlists.txt)

## **后开发**❗❗:

> -   [备忘单\_AV旁路](ToolsResources/POST-EXPL/CHEATSHEETS/Cheatsheet_AVBypass.txt)
> -   [备忘单\_建筑评论](ToolsResources/POST-EXPL/CHEATSHEETS/Cheatsheet_BuildReviews.txt)
> -   [代码执行反向外壳命令](ToolsResources/POST-EXPL/CHEATSHEETS/code-execution-reverse-shell-commands.txt)

## **权限提升**⚠️:

> -   [备忘单\_Linux 权限退出](ToolsResources/PrivEsc/CHEATSHEETS/Cheatsheet_LinuxPrivilegeEsc.txt)
> -   [linux\_枚举](ToolsResources/PrivEsc/CHEATSHEETS/linux_enumeration.md)
> -   [视窗\_枚举](ToolsResources/PrivEsc/CHEATSHEETS/windows_enumeration.md)
> -   [视窗\_私人\_升级](ToolsResources/PrivEsc/CHEATSHEETS/windows_priv_escalation.md)
> -   [视窗\_私人\_升级\_实际的](ToolsResources/PrivEsc/CHEATSHEETS/windows_priv_escalation_practical.md)

## **渗透测试和安全评估结果报告模板**📝 :

> -   [演示公司 - 安全评估结果报告.docx](ToolsResources/REPORT/TEMPLATES/Demo-Company-Security-Asses-Findings-Report.docx)
> -   [Linux-template.面对](ToolsResources/REPORT/TEMPLATES/linux-template.md)
> -   [PWKv1-REPORT.doc](ToolsResources/REPORT/TEMPLATES/PWKv1-REPORT.doc)
> -   [pwkv1\_报告.doc](ToolsResources/REPORT/TEMPLATES/pwkv1_report.doc)
> -   [模板渗透测试报告-v03.pdf](ToolsResources/REPORT/TEMPLATES/template-penetration-testing-report-v03.pdf)
> -   [Windows-template.面对](ToolsResources/REPORT/TEMPLATES/windows-template.md)
> -   [OSCP-OS-XXXXX-Lab-Report\_模板3.2.docx](ToolsResources/REPORT/TEMPLATES/OSCP-OS-XXXXX-Lab-Report_Template3.2.docx)
> -   [OSCP-OS-XXXXX-考试报告\_模板3.2.docx](ToolsResources/REPORT/TEMPLATES/OSCP-OS-XXXXX-Exam-Report_Template3.2.docx)
> -   [樱桃树\_模板.ctb](ToolsResources/REPORT/TEMPLATES/CherryTree_template.ctb)
> -   [eventory-sample-pentest-report.pdf](ToolsResources/REPORT/TEMPLATES/eventory-sample-pentest-report.pdf)

## **逆向工程**⚡ :

> -   [缓冲\_溢出\_开发](ToolsResources/REVERSE/CHEATSHEETS/Buffer_Overflow_Exploit.md)
> -   [缓冲\_溢出](ToolsResources/REVERSE/CHEATSHEETS/buffer_overflows.md)
> -   [数据库\_欺骗\_床单](ToolsResources/REVERSE/CHEATSHEETS/gdb_cheat_sheet.pdf)
> -   [r2\_备忘单](ToolsResources/REVERSE/CHEATSHEETS/r2_cheatsheet.pdf)
> -   [和呱呱\_缓冲\_溢出\_开发](ToolsResources/REVERSE/CHEATSHEETS/win32_buffer_overflow_exploitation.md)
> -   [64\_他\_32_jmp\_指示](ToolsResources/REVERSE/CHEATSHEETS/assembly/64_ia_32_jmp_instructions.pdf)
> -   [课程\_笔记](ToolsResources/REVERSE/CHEATSHEETS/assembly/course_notes.md)
> -   [调试](ToolsResources/REVERSE/CHEATSHEETS/assembly/debuging.md)
> -   [英特尔代码表\_x86](ToolsResources/REVERSE/CHEATSHEETS/assembly/IntelCodeTable_x86.pdf)
> -   [Radare2 备忘单](ToolsResources/REVERSE/CHEATSHEETS/assembly/Radare2%20cheat%20sheet.txt)
> -   [x86\_集会\_x86\_建筑学](ToolsResources/REVERSE/CHEATSHEETS/assembly/x86_assembly_x86_architecture.pdf)
> -   [x86\_操作码\_结构体\_和\_操作说明\_概述](ToolsResources/REVERSE/CHEATSHEETS/assembly/x86_opcode_structure_and_instruction_overview.png)

## **社会工程学**🎭:

> -   [社会的\_工程](ToolsResources/SOCIAL_ENGINEERING/CHEATSHEETS/social_engineering.md)

## **穿行**🚶 :

> -   [备忘单\_渗透测试.txt](ToolsResources/WALK/Cheatsheet_PenTesting.txt)
> -   [OWASP 测试指南 v4](ToolsResources/WALK/OTGv4.pdf)
> -   [OWASPv4\_清单.xlsx](ToolsResources/WALK/OWASPv4_Checklist.xlsx)

## **网络黑客**🌐 :

> -   [辅助的\_info.面对](ToolsResources/WEB/CHEATSHEETS/auxiliary_info.md)
> -   [备忘单\_阿帕奇SSL](ToolsResources/WEB/CHEATSHEETS/Cheatsheet_ApacheSSL.txt)
> -   [备忘单\_攻击MSSQL](ToolsResources/WEB/CHEATSHEETS/Cheatsheet_AttackingMSSQL.txt)
> -   [备忘单\_域管理员利用](ToolsResources/WEB/CHEATSHEETS/Cheatsheet_DomainAdminExploitation.txt)
> -   [备忘单\_SQL注入](ToolsResources/WEB/CHEATSHEETS/Cheatsheet_SQLInjection.txt)
> -   [备忘单\_漏洞验证.txt](ToolsResources/WEB/CHEATSHEETS/Cheatsheet_VulnVerify.txt)
> -   [代码执行反向外壳命令](ToolsResources/WEB/CHEATSHEETS/code-execution-reverse-shell-commands.txt)
> -   [文件\_upload.面对](ToolsResources/WEB/CHEATSHEETS/file_upload.md)
> -   [html5\_欺骗\_床单](ToolsResources/WEB/CHEATSHEETS/html5_cheat_sheet.pdf)
> -   [查询\_欺骗\_床单\_1.3.2](ToolsResources/WEB/CHEATSHEETS/jquery_cheat_sheet_1.3.2.pdf)
> -   [坐下](ToolsResources/WEB/CHEATSHEETS/sqli.md)
> -   [坐下\_备忘单](ToolsResources/WEB/CHEATSHEETS/sqli_cheatsheet.md)
> -   [sql查询](ToolsResources/WEB/CHEATSHEETS/sqli-quries.txt)
> -   [提示](ToolsResources/WEB/CHEATSHEETS/sqli-tips.txt)
> -   [网络\_应用程序\_安全](ToolsResources/WEB/CHEATSHEETS/web_app_security.md)
> -   [网络\_应用程序\_伤口\_阿拉伯](ToolsResources/WEB/CHEATSHEETS/web_app_vulns_Arabic.md)
> -   [XSS_1](ToolsResources/WEB/CHEATSHEETS/xss.md)
> -   [XSS_2](ToolsResources/WEB/CHEATSHEETS/xss.png)
> -   [xss\_动作脚本](ToolsResources/WEB/CHEATSHEETS/xss_actionscript)
> -   [第二十](ToolsResources/WEB/CHEATSHEETS/xxe.md)

## **其他**📚 :

> -   [有史以来最好的收藏](https://collection.sofianehamlaoui.fr)
>
> -   [图片（我会让你发现）](ToolsResources/IMAGES/)
>
> -   [谷歌黑客数据库](ToolsResources/GHDB.pdf)
>
> -   [Google F U](ToolsResources/GoogleFu.pdf)

# **贡献**:

0.  读[贡献](https://github.com/SofianeHamlaoui/Lockdoor-Framework/blob/master/docs/CONTRIBUTING.md),[行为准则](https://github.com/SofianeHamlaoui/Lockdoor-Framework/blob/master/docs/CODE_OF_CONDUCT.md)和[拉取请求模板](https://github.com/SofianeHamlaoui/Lockdoor-Framework/blob/master/docs/pull_request_template.md)
1.  分叉它（[HTTPS://GitHub.com/Sofia呢ham老UI/lock door-framework/fork](https://github.com/SofianeHamlaoui/Lockdoor-Framework/fork))
2.  创建您的功能分支
3.  提交您的更改
4.  推送到分支
5.  创建一个新的拉取请求
