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
| 文件反转、倒置、导出工具          | [Gihub](https://github.com/AabyssZG/FileReverse-Tools)       | AabyssZG (曾哥) )                                |

### 🔑 Crypto

| 项目名称           | Usage                                                        | 项目地址                                       | 其它 |
| ------------------ | ------------------------------------------------------------ | ---------------------------------------------- | ---- |
| Python             | CTF密码学中离不开的语言x                                     | [官网](https://www.python.org/)                | /    |
| Factordb           | 在线的因数分解网站，可将n分解为p q两个素数                   | [官网](http://factordb.com/)                   | /    |
| Yafu               | 本地的因数分解程序，可将n分解为p q两个素数，通常用于n比较小的情况 | [官网](https://sourceforge.net/projects/yafu/) | /    |
| 【Python】Crypto包 | pip install pycryptodom \| import Crypto \| from Crypto.Util.number import * | /                                              | /    |
| 【Python】gmpy2包  | 在 [Releases](https://github.com/aleaxit/gmpy/releases) 中下载相应版本 \| pip3 install gmpy2-2.xx-cpxx-xxxxxx.whl \| import gmpy2 | [Github](https://github.com/aleaxit/gmpy)      | /    |
|                    |                                                              |                                                |      |

### 💫 Reverse

| 项目名称     | Usage | 项目地址 | 项目文档 |
| ------------ | ----- | -------- | -------- |
| IDA          |       |          |          |
| Cheat Engine |       |          |          |
| DIE          |       |          |          |
| DIEL         |       |          |          |
|              |       |          |          |
|              |       |          |          |
|              |       |          |          |



### 💥 PWN
###   ⚔   AWD 
