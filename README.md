<div align="center">  
    <img src="https://nssctf.wdf.ink//img/WDTJ/202306170145878.png" width="300px">
    <h3>Cyb3r-工具仓库</h3>
    <p> Cybersecurity tool repository.</p>
    <p>收录常用 / 前沿 的安全工具以及其文档，覆盖CTF和实战渗透领域，努力的尝试清除信息差。</p>
</div> 

## ☁ 关于本项目 & 声明

其实目前做工具合集的优秀开源项目很多，所以我们的目的不是单纯的提供工具合集，这个项目虽然取名叫做工具仓库，但其实它可能更像是一个工具的wiki——学习中有一个很大的误区 “收藏” == “学会”，而工具也是，很多时候，工具不具备其本身的意义，当它被下载下来后，更像是一件....“收藏品”。本项目将尝试修正这样的思维误区，做到真正意义上的去使用工具，而不是做一个工具收藏家。

对于每个工具 都会有其对应的基本要素：**名称** **来源** **分类** **适用平台** **用途** **用法**  **使用教程** **其他相关文档**

本项目将以两个大类分类：CTF工具 和 渗透工具，两者分别与 "[CTF-QuickStart](https://github.com/ProbiusOfficial/CTF-QuickStart)" 和 "[Cybersecurity-StartGuide](https://github.com/ProbiusOfficial/Cybersecurity-StartGuide)" 的工具内容同步，两大类工具存在工具重叠属于正常现象，所以这里约定，在收录时，两者互相独立。

- 对于 CTF 工具，主要收集基础工具。当然也会收录一些 轮子 集合工具，以及所谓的 "做题工具" ，该部分的要求为开源工具，目的主要是用于学习，该部分工具将会被标记，我们希望这些工具能带给您一些启发而不是单纯用来解题。
- 对于 渗透 工具，以常用工具为主。也会同步收集更新一些前沿工具或者项目，同样要求为开源项目，如果项目长久失修，或者其他异常，我们会添加对应标记。  
- 注意，本项目中所有工具和技术，**仅用于安全技术研究讨论**，请勿进行任何非授权渗透行为，否则请自行承担责任。

若本项目对您有所帮助，请在页面右上角点个 Star :star: 支持一下，谢谢！

## 💻常用软件

- 该栏目提供的工具只为提高效率，可能与项目核心有一定偏差。
- 项目Release提供封装好的基础工具箱，工具箱将基于 [Maye Lite](https://github.com/25H/MayeLite) 进行相对路径封装，以便于解决路径问题，做到开箱即用。

| 项目名称                                                 | 项目简介                                                     | 项目地址                                           | 项目文档                                     |
| :------------------------------------------------------- | :----------------------------------------------------------- | :------------------------------------------------- | :------------------------------------------- |
| [Maye Lite](https://github.com/25H/MayeLite)             | 专注于文件快速启动的简洁、轻量级工具<img src="./src/windows.svg" width="17" height="17" /> | [Github](https://github.com/25H/MayeLite)          | https://t.arae.cc/p/25804.html               |
| [uTools](https://u.tools/)                               | 一个极简、插件化的现代桌面软件。<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://u.tools/)                           | https://u.tools/docs/guide/about-uTools.html |
| [Everything](https://www.voidtools.com/zh-cn/downloads/) | 一款强大的本地文件索引和搜索工具<img src="./src/windows.svg" width="17" height="17" /> | [官网](https://www.voidtools.com/zh-cn/downloads/) | /                                            |

欢迎在issue中推荐更多的效率工具，但是请注意，适合自己的工具才是最好的，您并不需要下载所有的工具，请勿持有 ALL IN 思想。

## 🏴 CTF 工具合集

### 🪐  环境基础

| 项目名称     | Usage                                                        | 项目地址                                                | 使用文档 |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------- | :------: |
| Vscode       | 最好用 最轻量的 文本编辑器 依靠扩展可实现包括但不限于 IDE 各种功能<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://code.visualstudio.com/)                  |    /     |
| PyCharm      | Python 集成开发环境(IDE)<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.jetbrains.com/zh-cn/pycharm/)        |    /     |
| IDEA         | Java 集成开发环境(IDE)<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.jetbrains.com/zh-cn/idea/)           |    /     |
| PHPStorm     | PHP 集成开发环境(IDE)<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.jetbrains.com/zh-cn/phpstorm/)       |    /     |
| Phpstudy     | Web环境 (Apache / Nginx + FTP + MySQL) 快速部署 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" />  <br />常用于 Web初学阶段的一些本地web页面的搭建 | [官网](https://www.xp.cn/download.html)                 |    /     |
| Docker       | 容器服务 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /><br />常用于 题目本地搭建测试  靶场环境，漏洞复现环境搭建等 <br /> 除了静态附件题目，几乎所有的CTF题目都依赖Docker | [官网](https://www.docker.com/)                         |    /     |
| Navicat      | 优秀的数据库 管理 操作 调试 以及 可视化软件<a href="https://www.ghxi.com/navicat16.html"><img src="./src/windows.svg" width="17" height="17" /></a><img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://navicat.com.cn/download/navicat-premium) |    /     |
| Watt Toolkit | Github Discord 部分谷歌服务 页面元素CDN 访问加速 \| <br />不是用来让你打游戏的啊喂(#`O′)！<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/BeyondDimension/SteamTools) |    /     |
| Clash        | 部分服务访问加速 \| 我也只能说这么多<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/Dreamacro/clash)            |    /     |



### 🌐  Web

- 注意 工具包含 应用程序<img src="./src/application.svg" width="19" height="13" /> 和 浏览器插件<img src="./src/chrome.svg" width="19" height="13" />
- 以下为Web常用工具或者说基础工具，一些漏洞利用程序将不会被归纳到这，您可以 点击此处 查看后方的CTF项目归档来查找更多工具。

| 项目名称                                                     | Usage                                                        | 项目地址                                                     | 使用文档 | 其他 |
| :----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- | ---- |
| hackbar <img src="./src/chrome.svg" width="19" height="13" /> | 浏览器插件，能够在页面上直接完成 请求/响应内容编辑，完成各种包括但是不限于伪造的工作。 | [谷歌商店](https://chrome.google.com/webstore/detail/ginpbkfigcoaokgflihfhhmglmbchinc)<br />[Github](https://github.com/Mr-xn/hackbar2.1.3) | /        | /    |
| Proxy SwitchyOmega <img src="./src/chrome.svg" width="19" height="13" /> | 代理管理软件，方便一个浏览器多个代理端口的切换。             | [Github](https://github.com/FelisCatus/SwitchyOmega)         | /        | /    |
| Wappalyzer <img src="./src/chrome.svg" width="19" height="13" /> | 页面技术识别软件，方便快速定位页面的框架技术等信息           | [官网](https://www.wappalyzer.com/)                          | /        | /    |
| Burp Suite <img src="./src/application.svg" width="19" height="13" /> | 代理抓包软件，用于Web应用程序的渗透测试和攻击<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://portswigger.net/burp)                         | /        | /    |
| Antsword <img src="./src/application.svg" width="19" height="13" /> | 开源Webshell管理工具<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/AntSwordProject/antSword)        | /        | /    |
| dirsearch <img src="./src/application.svg" width="19" height="13" /> | 目录扫描工具<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/maurosoria/dirsearch)            | /        | /    |
| SQLMap<img src="./src/application.svg" width="19" height="13" /> | 自动化的SQL注入利用工具<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/sqlmapproject/sqlmap)            | /        | /    |
| JD-GUI <img src="./src/application.svg" width="19" height="13" /> | Jar包反编译工具 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/java-decompiler/jd-gui)          | /        | /    |
| Ysoserial<img src="./src/application.svg" width="19" height="13" /> | Java 反序列漏洞利用工具 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/frohoff/ysoserial)               | /        | /    |

### 🕸  MISC

#### ❆ 基础工具

| 项目名称              | Usage                                                        | 项目地址                                                     | 文档 |
| --------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---- |
| Python                | MISC方向中用途最广的语言。                                   | [官网](https://www.python.org/)                              | /    |
| CyberChef             | 近乎全能的编码解码工具。<img src="./src/chrome.svg" width="19" height="13" /> | [官网](https://cyberchef.org/)<br />[国内中文镜像站](https://ctf.mzy0.com/CyberChef3/) | /    |
| 010 Editor            | 专业的文本编辑器和16进制编辑器，可通过加载模块脚本，解析文件结构。<img src="./src/windows.svg" width="17" height="17" /><img src="./src/linux.svg" width="17" height="17" /> | [官网](http://www.010editor.com/)                            | /    |
| lmHex                 | 开源的16进制编辑器。 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/WerWolv/ImHex)                   |      |
| WinHex                | 16 进制编辑器为核心的数据处理软件。<img src="./src/windows.svg" width="17" height="17" /> | [官网](https://www.x-ways.net/winhex/)                       | /    |
| QR Research           | 专业的二维码扫描识别软件，支持多个纠错等级，掩码选项。<img src="./src/windows.svg" width="17" height="17" /> | /                                                            | /    |
| Stegsolve             | 图像分析工具。 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/Giotino/stegsolve)               | /    |
| Binwalk               | 可识别文件分离提取工具，常用于从文件中提取隐写到其中的其他文件。<img src="./src/linux.svg" width="17" height="17" /> | [Github](https://github.com/ReFirmLabs/binwalk)              | /    |
| Foremost              | 用于提取一个文件中包含的多个文件。<img src="./src/linux.svg" width="17" height="17" /> | /                                                            | /    |
| ARCHPR                | 压缩文件密码暴力破解工具。<img src="./src/windows.svg" width="17" height="17" /> | /                                                            | /    |
| Ziperello             | zip压缩包密码恢复软件。<img src="./src/windows.svg" width="17" height="17" /> | /                                                            | /    |
| Aopr                  | Office文件密码暴力破解工具。<img src="./src/windows.svg" width="17" height="17" /> | /                                                            | /    |
| Audacity              | 多轨音频处理软件。<img src="./src/windows.svg" width="17" height="17" /> | [Github](https://github.com/audacity/audacity)               | /    |
| Mp3stego              | 音频隐写提取工具<img src="./src/windows.svg" width="17" height="17" /> | [官网](https://www.petitcolas.net/steganography/mp3stego/)   |      |
| Wireshark             | 流量分析取证软件。 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.wireshark.org/)                           | /    |
| Volatility            | 内存分析取证软件。 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.volatilityfoundation.org/)<br />[Github](https://github.com/volatilityfoundation) | /    |
| Passware Kit Forensic | 十分强大的解密工具，各类文件/磁盘密码爆破，密钥搜索等        | /                                                            | /    |
| Forensics-Wiki        | 取证综合资料库<img src="./src/chrome.svg" width="19" height="13" /> | [官网](https://www.forensics-wiki.com/)                      | /    |
| AutoPsy        | 用来分析磁盘映像和恢复文件的开源取证工具  | [官网](https://www.autopsy.com/)         |          |
|                       |                                                              |                                                              |      |

#### ❆ 其他工具	

#### ❆ 解题工具

⚠请不要过分依赖下面工具！！！

```
其实在工具出来之前，MISC对所谓工具题的考点应该是脚本编写，MISC本身工具题目很少，只是造轮子的师傅多了也便有了工具题x 
所以这里要告诚各位 入门之后如果你要做一名MISC手 请一定不要抛弃原理做题 不要依赖工具 也不要停止学习.
```

| 项目名称     | Usage                                                    | 相关地址                           |
| ------------ | -------------------------------------------------------- | ---------------------------------- |
| 随波逐流     | 离线加密解密，字符编码进行转换，文件隐写查看等多项功能。 | [官网](http://1o1o.xyz/index.html) |
| PuzzleSolver | MISC 综合解题工具，由Byxs20开发。                        | [神秘数字](761594154)              |

#### ❆ 开源脚本

🔔MISC是一个十分注重编程能力 ~~和 脑洞~~ 的方向，希望你能从下面的开源脚本中获得启发，也欢迎pr投稿你的开源脚本x

| 项目名称                          | 项目地址                                                     | 项目作者                                         |
| --------------------------------- | ------------------------------------------------------------ | ------------------------------------------------ |
| 自动爆破PNG图片宽高并一键修复工具 | [Github](https://github.com/AabyssZG/Deformed-Image-Restorer) | [AabyssZG (曾哥) )](https://github.com/AabyssZG) |
| 文件反转、倒置、导出工具          | [Gihub](https://github.com/AabyssZG/FileReverse-Tools)       | [AabyssZG (曾哥) )](https://github.com/AabyssZG)                               |

### 🔑 Crypto

| 项目名称         | Usage                                                        | 项目地址                                       | 其它 |
| ---------------- | ------------------------------------------------------------ | ---------------------------------------------- | ---- |
| Python           | CTF密码学中离不开的语言x                                     | [官网](https://www.python.org/)                | /    |
| Factordb         | 在线的因数分解网站，可将n分解为p q两个素数                   | [官网](http://factordb.com/)                   | /    |
| Yafu             | 本地的因数分解程序，可将n分解为p q两个素数，通常用于n比较小的情况 | [官网](https://sourceforge.net/projects/yafu/) | /    |
| [Python]Crypto包 | pip install pycryptodom \| import Crypto \| from Crypto.Util.number import * | /                                              | /    |
| [Python]gmpy2包  | 在 [Releases](https://github.com/aleaxit/gmpy/releases) 中下载相应版本 \| pip3 install gmpy2-2.xx-cpxx-xxxxxx.whl \| import gmpy2 | [Github](https://github.com/aleaxit/gmpy)      | /    |
|                  |                                                              |                                                |      |

### 💫 Reverse
#### 解题工具
| 项目名称       | Usage | 项目地址 | 项目文档 |
| ------------   | ----- | -------- | -------- |
| IDA            | 最常用的静态逆向工具 | [官网](https://hex-rays.com/ida-pro/)        |  [ida pro权威指南](https://github.com/Coldwave96/WebSecurity/blob/master/IDA%20Pro%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97%EF%BC%88%E7%AC%AC%E4%BA%8C%E7%89%88%EF%BC%89.pdf)        |
| Cheat Engine   | 对程序的内存数据进行扫描和调试，十分强大，但是用得不多 | [官网](https://www.cheatengine.org/)   |  /        |
| DIE            | 查壳工具，拿到程序第一件事就是分析文件类型，是否有壳   | [github](https://github.com/horsicq/Detect-It-Easy)   | [github](https://github.com/horsicq/Detect-It-Easy)  |
| Exeinfope      | 同为查壳工具      | [官网](http://www.exeinfo.byethost18.com)    | /         |
| Ghidra         | 开源的静态逆向工具，和IDA作用相同      | [官网](https://ghidra-sre.org/)         |          |
| JEB            | 强大的APK逆向工具，针对Mobile类型的逆向题目    |          ||
| Ollydbg        | 同为反汇编调试器(官方已经停止维护)     | [官网](https://www.ollydbg.de/)         | /         |
| jd-gui         | 逆向Jar包 |[github](http://java-decompiler.github.io/)     | /      |
| x64dbg/x32dbg  | 在windows上使用的开源x64/x32调试器      | [官网](https://x64dbg.com/)         | [官网](https://x64dbg.com/)          |
| unpy2exe       | 对py2exe打包的python程序提取字节码文件  **（.pyc）**      | [github](https://github.com/matiasb/unpy2exe)         | [github](https://github.com/matiasb/unpy2exe)         |
| pyinstxtractor | 对pyInstaller打包的python程序提取字节码文件  **（.pyc）**      | [github](https://github.com/extremecoders-re/pyinstxtractor)         | [github](https://github.com/extremecoders-re/pyinstxtractor)          |
| [python]uncompyle | 用于对Python字节码文件 **（.pyc）** 的反汇编，将其变成python源代码      | [官网](https://pypi.org/project/uncompyle6/)         | [官网](https://pypi.org/project/uncompyle6/)          |
| gdb            | 一般用于ELF的动态调试，配合插件(如pwngdb，gdb-peda)使用更佳   | 使用包管理工具安装      | [Sourceware](https://www.sourceware.org/gdb/documentation/)   |
| z3             | 开源的约束求解器，针对约束求解题型    | [github](https://github.com/Z3Prover/z3/)     | [github](https://github.com/Z3Prover/z3/)         |
| dnSpy          | 强大的.NET调试、修改和反编译的工具(已停止维护)    | [github](https://github.com/dnSpy/dnSpy)     | [github](https://github.com/dnSpy/dnSpy)          |

#### 使用流程
拿到一个文件，先分析它是什么类型的文件，可以在Linux下使用flie来查看他是什么类型的文件（一般是一个可执行文件），分析后查看它是否有壳，有的话先脱壳，脱壳后针对文件类型来使用逆向工具，如Jar包我们就用jd-gui，.NET文件我们就使用dnSpy，IDA一般是万金油，不知道用什么的话就先用IDA静态分析。在了解程序大概结构后，我们可以对程序关键部分下断点进行动态调试，但在这之前，我们或许还会遇到需要解决混淆和反调试保护等问题......本文注重工具的介绍，这里不再对题型过多赘述。

### 💥 PWN
| 项目名称       | Usage | 项目地址 | 项目文档 |
| ------------   | ----- | -------- | -------- |
| gdb         | 一般用于ELF的动态调试，配合插件(如pwngdb，gdb-peda)使用更佳     | [Sourceware](https://www.sourceware.org/gdb/documentation/)  | [Sourceware](https://www.sourceware.org/gdb/documentation/)   |
| checksec    | 查看二进制文件开启了哪些保护机制   | [github](https://github.com/slimm609/checksec.sh)  | [github](https://github.com/slimm609/checksec.sh)         |
| ROPgadget   | 编写ROP的EXP时需要用到，可以帮助你寻找合适的gadgets     | [github](https://github.com/JonathanSalwan/ROPgadget) | [github](https://github.com/JonathanSalwan/ROPgadget)         |
| pwntools    | 用于编写EXP     | [github](https://github.com/Gallopsled/pwntools)     | [github](https://github.com/Gallopsled/pwntools)    |
| objdump     | 反汇编工具，查看文件的一些表信息，如got表   | /                                                           | /                                                           |

#### 使用流程
Pwn的解题过程与Reverse差不多，我们拿到文件需要先分析文件类型，然后再对文件开启的保护机制分析，反汇编出它的源代码，对源代码的逻辑分析，找出漏洞，编写EXP,在编写EXP的过程中，我们可以使用gdb在本地动态调试，一步一步修改我们的EXP,Pwn掉这题！
###   ⚔   AWD 