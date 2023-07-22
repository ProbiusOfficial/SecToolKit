<div align="center">  
    <img src="https://nssctf.wdf.ink//img/WDTJ/202306170145878.png" width="300px">
    <h3>Cyb3r-工具仓库</h3>
    <a href="#-ctf-工具合集">    CTF工具    </a>|<a href="#渗透工具">    渗透工具    </a> 
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

如果您要转载本项目，转载时请注明原作者和项目源地址:https://github.com/ProbiusOfficial/SecTool

为了方便您分享该项目，可使用短链接 http://tool.ctf.dog/ 进行分享。

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

| 项目名称           | Usage                                                        | 项目地址                                                     | 使用文档 |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | :------: |
| Vscode             | 最好用 最轻量的 文本编辑器 依靠扩展可实现包括但不限于 IDE 各种功能<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://code.visualstudio.com/)                       |    /     |
| Vmware Workstation | 虚拟机软件<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.vmware.com/products/workstation-pro/workstation-pro-evaluation.html) |    /     |
| PyCharm            | Python 集成开发环境(IDE)<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.jetbrains.com/zh-cn/pycharm/)             |    /     |
| IDEA               | Java 集成开发环境(IDE)<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.jetbrains.com/zh-cn/idea/)                |    /     |
| PHPStorm           | PHP 集成开发环境(IDE)<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.jetbrains.com/zh-cn/phpstorm/)            |    /     |
| Phpstudy           | Web环境 (Apache / Nginx + FTP + MySQL) 快速部署 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" />  <br />常用于 Web初学阶段的一些本地web页面的搭建 | [官网](https://www.xp.cn/download.html)                      |    /     |
| Docker             | 容器服务 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /><br />常用于 题目本地搭建测试  靶场环境，漏洞复现环境搭建等 <br /> 除了静态附件题目，几乎所有的CTF题目都依赖Docker | [官网](https://www.docker.com/)                              |    /     |
| Navicat            | 优秀的数据库 管理 操作 调试 以及 可视化软件<a href="https://www.ghxi.com/navicat16.html"><img src="./src/windows.svg" width="17" height="17" /></a><img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://navicat.com.cn/download/navicat-premium)      |    /     |
| Watt Toolkit       | Github Discord 部分谷歌服务 页面元素CDN 访问加速 \| <br />不是用来让你打游戏的啊喂(#`O′)！<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/BeyondDimension/SteamTools)      |    /     |
| Clash              | 部分服务访问加速 \| 我也只能说这么多<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/Dreamacro/clash)                 |    /     |

---

### 🌐  Web | Web安全

- 注意 工具包含 应用程序<img src="./src/application.svg" width="19" height="13" /> 和 浏览器插件<img src="./src/chrome.svg" width="19" height="13" />
- 以下为Web常用工具或者说基础工具，一些漏洞利用程序将不会被归纳到这，您可以 点击此处 查看后方的CTF项目归档来查找更多工具。

| 项目名称                                                     | Usage                                                        | 项目地址                                                     | 使用文档 | 其他 |
| :----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- | ---- |
| hackbar <img src="./src/chrome.svg" width="19" height="13" /> | 浏览器插件，能够在页面上直接完成 请求/响应内容编辑，完成各种包括但是不限于伪造的工作。 | [谷歌商店](https://chrome.google.com/webstore/detail/ginpbkfigcoaokgflihfhhmglmbchinc)<br />[Github](https://github.com/Mr-xn/hackbar2.1.3) | /        | /    |
| Proxy SwitchyOmega <img src="./src/chrome.svg" width="19" height="13" /> | 代理管理软件，方便一个浏览器多个代理端口的切换。             | [Github](https://github.com/FelisCatus/SwitchyOmega)         | /        | /    |
| Heimdallr <img src="./src/chrome.svg" width="19" height="13" /> | 被动嗅探浏览器流量，用于提示漏洞框架指纹、告警拦截蜜罐请求、对抗浏览器特征追踪的Chrome插件             | [Github](https://github.com/Ghr07h/Heimdallr)         | /        | /    |
| Wappalyzer <img src="./src/chrome.svg" width="19" height="13" /> | 页面技术识别软件，方便快速定位页面的框架技术等信息           | [官网](https://www.wappalyzer.com/)                          | /        | /    |
| Burp Suite <img src="./src/application.svg" width="19" height="13" /> | 代理抓包软件，用于Web应用程序的渗透测试和攻击<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://portswigger.net/burp)                         | /        | /    |
| Antsword <img src="./src/application.svg" width="19" height="13" /> | 开源Webshell管理工具<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/AntSwordProject/antSword)        | /        | /    |
| dirsearch <img src="./src/application.svg" width="19" height="13" /> | 目录扫描工具<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/maurosoria/dirsearch)            | /        | /    |
| SQLMap<img src="./src/application.svg" width="19" height="13" /> | 自动化的SQL注入利用工具<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/sqlmapproject/sqlmap)            | /        | /    |
| JD-GUI <img src="./src/application.svg" width="19" height="13" /> | Jar包反编译工具 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/java-decompiler/jd-gui)          | /        | /    |
| Ysoserial<img src="./src/application.svg" width="19" height="13" /> | Java 反序列漏洞利用工具 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/frohoff/ysoserial)               | /        | /    |

---

### 🕸  MISC | 杂项

#### ❆ 基础工具

- **基础语言 | 模块**

| 项目名称 | Usage                      | 项目地址                        | 文档 |
| -------- | -------------------------- | ------------------------------- | ---- |
| Python   | MISC方向中用途最广的语言。 | [官网](https://www.python.org/) | /    |

- **编码 / 解码 / 解密 工具**

| 项目名称      | Usage                                                        | 项目地址                                                     | 文档 |
  | ------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---- |
  | CyberChef     | 近乎全能的编码解码工具。<img src="./src/chrome.svg" width="19" height="13" /> | [官网](https://cyberchef.org/)<br />[国内中文镜像站](https://ctf.mzy0.com/CyberChef3/) | /    |
  | Ciphey        | 自动化解密工具。                                             | [Github](https://github.com/Ciphey/Ciphey)                   |      |
  | CTFCrackTools | 国内首个CTF工具框架,内涵多个主流密码加解密，支持添加支持Python编写的插件。 | [Github](https://github.com/0Chencc/CTFCrackTools)           | /    |

- **文本 / Hex 编辑 | 文件工具**	

| 项目名称   | Usage                                                        | 项目地址                                        | 文档 |
  | ---------- | ------------------------------------------------------------ | ----------------------------------------------- | ---- |
  | 010 Editor | 专业的文本编辑器和16进制编辑器，可通过加载模块脚本，解析文件结构。<img src="./src/windows.svg" width="17" height="17" /><img src="./src/linux.svg" width="17" height="17" /> | [官网](http://www.010editor.com/)               | /    |
  | lmHex      | 开源的16进制编辑器。 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/WerWolv/ImHex)      |      |
  | WinHex     | 16 进制编辑器为核心的数据处理软件。<img src="./src/windows.svg" width="17" height="17" /> | [官网](https://www.x-ways.net/winhex/)          | /    |
  | Binwalk    | 可识别文件分离提取工具，常用于从文件中提取隐写到其中的其他文件。<img src="./src/linux.svg" width="17" height="17" /> | [Github](https://github.com/ReFirmLabs/binwalk) | /    |
  | Foremost   | 用于提取一个文件中包含的多个文件。<img src="./src/linux.svg" width="17" height="17" /> | /                                               | /    |

- **隐写工具 | 图像 / 音频**

| 项目名称                                                     | Usage                                                        | 项目地址                                                     | 文档                                                       |
  | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------------------------- |
  | Qrazybox<img src="./src/chrome.svg" width="19" height="13" /> | 二维码分析和恢复<img src="./src/chrome.svg" width="19" height="13" /> | [Github](https://github.com/Merricx/qrazybox)<br />[Usagepage](https://merri.cx/qrazybox/) |                                                            |
  | QR Research                                                  | 专业的二维码扫描识别软件，支持多个纠错等级，掩码选项(已停止维护)。<img src="./src/windows.svg" width="17" height="17" /> | /                                                            | /                                                          |
  | UleadGIFAnimator                                             | 高级GIF编辑器<img src="./src/windows.svg" width="17" height="17" /> | /                                                            | [吾爱论坛](https://www.52pojie.cn/thread-1276299-1-1.html) |
  | **-----图像类**                                              |                                                              |                                                              |                                                            |
  | Stegsolve                                                    | 图像分析工具。 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/Giotino/stegsolve)               | /                                                          |
  | TweakPNG                                                     | 用于检查和修改PNG图像文件 \|类似于010的Png Template功能 <img src="./src/windows.svg" width="17" height="17" /> | [官网](https://entropymine.com/jason/tweakpng/)              | /                                                          |
  | BlindWaterMark(python)                                       | 基于 python 的图像盲水印                                     | [Github](https://github.com/ww23/BlindWatermark)             | /                                                          |
  | BlindWatermark(java)                                         | 基于 java 的图像盲水印                                       | [Github](https://github.com/ww23/BlindWatermark)             | /                                                          |
  | WaterMark(隐藏水印)                                          | 图像隐写工具，在频域添加数字水印 <img src="./src/windows.svg" width="17" height="17" /> | /                                                            | [吾爱论坛](https://www.52pojie.cn/thread-709668-1-1.html)  |
  | WaterMarkH                                                   | 单图盲水印(频域隐写)工具                                     | /                                                            | /                                                          |
  | zsteg                                                        | PNG 和 BMP 图片隐写                                          | [Github](https://github.com/zed-0xff/zsteg)                  | /                                                          |
  | StegoVeritas                                                 | 隐写工具                                                     | [Github](https://github.com/bannsec/stegoVeritas)            | /                                                          |
  | Stegdetect                                                   | 检测jpeg图像隐写工具，搭配stegbreak食用更佳                  | [Github](https://github.com/abeluck/stegdetect)              | /                                                          |
  | **-----音频类**                                              |                                                              |                                                              |                                                            |
  | Steghide                                                     | 将文件隐藏到**图片或音频**中的工具 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> | [官网](https://steghide.sourceforge.net/)                    | /                                                          |
  | Audacity                                                     | 多轨音频处理软件。<img src="./src/windows.svg" width="17" height="17" /> | [Github](https://github.com/audacity/audacity)               | /                                                          |
  | Mp3stego                                                     | 音频隐写提取工具<img src="./src/windows.svg" width="17" height="17" /> | [官网](https://www.petitcolas.net/steganography/mp3stego/)   | /                                                          |
  | Silenteye                                                    | 音频/图像隐写工具 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://achorein.github.io/silenteye/)                | /                                                          |
  | DeepSound                                                    | 可以将文件加密保存到一段声音文件中<img src="./src/windows.svg" width="17" height="17" /> | [官网](https://jpinsoft.net/deepsound/documentation.aspx)    | /                                                          |
  | Mp3tag                                                       | 音频文件元资料编辑器 <img src="./src/windows.svg" width="17" height="17" /><img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.mp3tag.de/en/)                            | /                                                          |

- **取证工具**

| 项目名称                | Usage                                                        | 项目地址                                                     | 文档                                                         |
  | ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | Forensics-Wiki          | 取证综合资料库<img src="./src/chrome.svg" width="19" height="13" /> | [官网](https://www.forensics-wiki.com/)                      | /                                                            |
  | **-----密码爆破**       |                                                              |                                                              |                                                              |
  | ZipCenOp                | 伪加密加/解密工具 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/442048209as/ZipCenOp)            | /                                                            |
  | ARCHPR                  | 压缩文件密码暴力破解工具。<img src="./src/windows.svg" width="17" height="17" /> | /                                                            | /                                                            |
  | Ziperello               | zip压缩包密码恢复软件。<img src="./src/windows.svg" width="17" height="17" /> | /                                                            | /                                                            |
  | Aopr                    | Office文件密码暴力破解工具。<img src="./src/windows.svg" width="17" height="17" /> | /                                                            | /                                                            |
  | Passware Kit Forensic   | 十分强大的解密工具，各类文件/磁盘密码爆破，密钥搜索等        | /                                                            | - [依依的汉化包](https://blog.csdn.net/u010418732/article/details/120189354)<br />- [汉化版](https://www.mzy0.com/archives/82/) |
  | Hashcat                 | 高性能，GPU/CPU 兼容的本地密码破解，支持多种不同格式         | [Github](https://github.com/hashcat/hashcat)                 | /                                                            |
  | John the Ripper         | 简单易用的离线破解                                           | [Github](https://github.com/openwall/john)                   | /                                                            |
  | Hydra                   | 远程或在线密码的并行暴力破解。                               | [Github](https://github.com/vanhauser-thc/thc-hydra)         | /                                                            |
  | **-----流量分析**       |                                                              |                                                              |                                                              |
  | Wireshark               | 流量分析取证软件。 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.wireshark.org/)                           | /                                                            |
  | **-----内存 磁盘 取证** |                                                              |                                                              |                                                              |
  | Volatility              | 内存分析取证软件。 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.volatilityfoundation.org/)<br />[Github](https://github.com/volatilityfoundation) | /                                                            |
  | MemProcFS               | 新型内存取证框架<img src="./src/windows.svg" width="17" height="17" /> | [Github](https://github.com/ufrisk/MemProcFS)                | /                                                            |
  | NtfsStreamsEditor       | NTFS流分析<img src="./src/windows.svg" width="17" height="17" /> | [官网](https://www.nirsoft.net/utils/alternate_data_streams.html) | /                                                            |
  | R-Studio                | 内存取证tick+磁盘文件恢复分析<img src="./src/windows.svg" width="17" height="17" /> | [官网](https://www.r-studio.com/zhcn/data-recovery-software) | /                                                            |
  | AutoPsy                 | 用来分析磁盘映像和恢复文件的开源取证工具<img src="./src/windows.svg" width="17" height="17" /> | [官网](https://www.autopsy.com/)                             | /                                                            |
  | RegistryExplorer        | 注册表文件分析器<img src="./src/windows.svg" width="17" height="17" /> | [官网](http://www.regxplor.com/download.html)                | /                                                            |
  | PowerToy                | 注册表文件分析器<img src="./src/windows.svg" width="17" height="17" /> | [Github](https://github.com/microsoft/PowerToys)             | /                                                            |

#### ❆ 解题工具

⚠请不要过分依赖下面工具！！！

- MISC是一个对编程能力要求比较高的方向，不过大多数考点的固定衍生出比较多的"轮子"，当然轮子减少手动操作，确实是好东西，但是容易产生一些弊端，因为跳过了手动操作所以不懂原理也能梭题目，可能会导致选手略过本来应该学的原理，手动会做之后再碰到了用工具减少操作是完全没问题的，即便没有这些整合工具，用现成脚本说到底本质也是一样的。

  ```
  使用工具获取便利的同时 请不要忽略对原理的学习！
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
| 文件反转、倒置、导出工具          | [Github](https://github.com/AabyssZG/FileReverse-Tools)      | [AabyssZG (曾哥) )](https://github.com/AabyssZG) |
| CRC碰撞全自动化脚本               | [Github](https://github.com/AabyssZG/CRC32-Tools)            | [AabyssZG (曾哥) )](https://github.com/AabyssZG) |
| 自动化内存取证_GUI版本            | [Github](https://github.com/Tokeii0/VolatilityPro)           | [Tokeii0 (猫捉鱼) ](https://github.com/Tokeii0)  |

---

### 🔑 Crypto | 密码学

| 项目名称                                                     | Usage                                                        | 项目地址                                                     | 其它                                                      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------------------------------- |
| ---**语言 \| 模块**                                          |                                                              |                                                              |                                                           |
| Python                                                       | CTF密码学中离不开的语言x                                     | [官网](https://www.python.org/)                              | /                                                         |
| Crypto 包<img src="./src/python.svg" width="17" height="17" /> | 密码学工具库，用于在Python中实现各种加密、解密和哈希算法。   | [Github](https://github.com/Legrandin/pycryptodome)          | /                                                         |
| gmpy2 包<img src="./src/python.svg" width="17" height="17" /> | 包含了许多常用的数论函数和算法，适配各种大整数情况，算法效率高于原生库。 | [Github](https://github.com/aleaxit/gmpy)                    | /                                                         |
| numpy 包<img src="./src/python.svg" width="17" height="17" /> | 基于C代码实现了底层数据结构和计算函数优化，适用于处理大型数据集和高性能计算，在密码学中常用于矩阵类运算。 | [Github](https://github.com/numpy/numpy)<br />[官网](https://numpy.org/) | /                                                         |
| ---**应用程序**                                              |                                                              |                                                              |                                                           |
| Sagemath                                                     | 开源的数学软件系统,整合了许多开源Python包。 <img src="./src/linux.svg" width="17" height="17" /><img src="./src/apple.svg" width="17" height="17" /> | [官网](https://www.sagemath.org/)<br />[Github](https://github.com/sagemath) | [Sage 中文文档](https://www.osgeo.cn/sagemath/index.html) |
| Yafu                                                         | 本地的因数分解程序                                           | [官网](https://sourceforge.net/projects/yafu/)               | /                                                         |
| Factordb                                                     | 在线的因数分解网站                                           | [官网](http://factordb.com/)                                 | /                                                         |
| z3                                                           | 开源的约束求解器，针对约束求解题型                           | [Github](https://github.com/Z3Prover/z3/)                    | /                                                         |

---

### 💫 Reverse | 逆向

#### 基础工具

| 项目名称       | Usage | 项目地址 | 其他 |
| ------------   | ----- | -------- | -------- |
| 微步沙箱 | 文件敏感操作检查<img src="./src/chrome.svg" width="19" height="13" /> | [UsagePage](https://s.threatbook.com) | / |
| Binaryai             | 基于开源项目代码匹配度在线反编译工具<img src="./src/chrome.svg" width="19" height="13" /> | [UsagePage](https://www.binaryai.cn/)                        | /                                                            |
| IDA            | 最常用的静态逆向工具 | [官网](https://hex-rays.com/ida-pro/)        |  [ida pro权威指南](https://github.com/Coldwave96/WebSecurity/blob/master/IDA%20Pro%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97%EF%BC%88%E7%AC%AC%E4%BA%8C%E7%89%88%EF%BC%89.pdf)        |
| Ghidra         | 开源的静态逆向工具，和IDA作用相同      | [官网](https://ghidra-sre.org/)         | / |
| Ollydbg        | 同为反汇编调试器(官方已经停止维护)     | [官网](https://www.ollydbg.de/)         | /         |
| x64dbg / x32dbg | 在windows上使用的开源 x64 / x32 调试器  | [官网](https://x64dbg.com/)         | / |
| DIE            | 查壳工具，拿到程序第一件事就是分析文件类型，是否有壳   | [Github](https://github.com/horsicq/Detect-It-Easy)   | [Github](https://github.com/horsicq/Detect-It-Easy)  |
| Exeinfope      | 同为查壳工具      | [官网](http://www.exeinfo.byethost18.com)    | /         |
| Cheat Engine   | 对程序的内存数据进行扫描和调试。 | [官网](https://www.cheatengine.org/)   |  /        |
| GDB         | 一般用于ELF的动态调试，配合插件(如pwngdb，gdb-peda)使用更佳   | 使用包管理工具安装      | [Sourceware](https://www.sourceware.org/gdb/documentation/)   |
| z3                   | 开源的约束求解器，针对约束求解题型                           | [Github](https://github.com/Z3Prover/z3/)                    | /                                                            |
| dnSpy                | 强大的.NET调试、修改和反编译的工具(已停止维护)               | [Github](https://github.com/dnSpy/dnSpy)                     | /                                                            |
| ----**Java反编译**   |                                                              |                                                              |                                                              |
| JADX                 | 开源 更好的代码可读性 自动恢复丢失的类和方法、变量和方法名称、可以将反编译结果导出为 Eclipse 或 IDEA 项目 | [Github](https://github.com/skylot/jadx)                     | /                                                            |
| JD-GUI               | 更好的代码可读性 可导出为 Java 文件或 Jar 包                 | [Github](http://java-decompiler.github.io/)                  | /                                                            |
| JEB                  | 支持wasm 可交叉引用、可看字节码、反编译结果纯粹              | [官网](https://www.pnfsoftware.com/)                         | /                                                            |
| GDA                  | 支持apk, dex, odex, oat, jar, class, aar文件的反编译， 支持python及java脚本自动化分析 | [官网](http://www.gda.wiki:9090/)                            | /                                                            |
| Fernflower           | IDEA 采用的反编译工具,支持Jar包反编译。                      | [Github](https://github.com/fesh0r/fernflower)               | /                                                            |
| ----**Python反编译** |                                                              |                                                              |                                                              |
| pycdc                | pyc反编译,对高版本有不错兼容性。                       | [Github](https://github.com/zrax/pycdc)                      | /                                                            |
| Unpy2exe             | 对py2exe打包的python程序提取字节码文件  **(.pyc)**。         | [Github](https://github.com/matiasb/unpy2exe)               | /                                                            |
| Pyinstxtractor       | 对pyInstaller打包的python程序提取字节码文件  **(.pyc)**。    | [Github](https://github.com/extremecoders-re/pyinstxtractor) | /                                                            |
| [Python]uncompyle    | 用于对Python字节码文件 **(.pyc)** 的反汇编，将其变成python源代码。 | [官网](https://pypi.org/project/uncompyle6/)                 | /                                                            |

<div>  
    <!-- 拿到一个文件，先分析它是什么类型的文件，可以在Linux下使用flie来查看他是什么类型的文件(一般是一个可执行文件)，分析后查看它是否有壳，有的话先脱壳，脱壳后针对文件类型来使用逆向工具，如Jar包我们就用jd-gui，.NET文件我们就使用dnSpy，IDA一般是万金油，不知道用什么的话就先用IDA静态分析。在了解程序大概结构后，我们可以对程序关键部分下断点进行动态调试，但在这之前，我们或许还会遇到需要解决混淆和反调试保护等问题......本文注重工具的介绍，这里不再对题型过多赘述。 -->
</div> 

---

### 💥 PWN | 二进制
| 项目名称       | Usage | 项目地址 | 其他 |
| ------------   | ----- | -------- | -------- |
| GDB       | 一般用于ELF的动态调试，配合插件(如pwngdb，gdb-peda)使用更佳。    | [Sourceware](https://www.sourceware.org/gdb/documentation/)  | /  |
| Pwntools    | 用于编写EXP。    | [Github](https://github.com/Gallopsled/pwntools)     | /   |
| Pwncli | 一款简单、易用的`pwn`题调试与攻击工具，帮助你快速编写`pwn`题攻击脚本，并实现本地调试和远程攻击的便捷切换，提高你在`CTF`比赛中调试`pwn`题脚本的速度与效率。 | [Github](https://github.com/RoderickChan/pwncli) | / |
| Checksec    | 查看二进制文件开启了哪些保护机制。  | [Github](https://github.com/slimm609/checksec.sh)  | /        |
| ROPgadget   | 编写ROP的EXP时需要用到，可以帮助你寻找合适的gadgets。    | [Github](https://github.com/JonathanSalwan/ROPgadget) | /        |
| objdump     | 反汇编工具，查看文件的一些表信息，如got表。  | /                                                           | /                                                           |
| radare2 | UNIX-like reverse engineering framework and command-line toolset. | [Github](https://github.com/radareorg/radare2) | / |
| windbg | Window 内核模式和用户模式代码调试。 | [Microsoft Learn](https://learn.microsoft.com/zh-cn/windows-hardware/drivers/debugger/debugger-download-tools) | /    |

<div>  
    <!-- Pwn的解题过程与Reverse差不多，我们拿到文件需要先分析文件类型，然后再对文件开启的保护机制分析，反汇编出它的源代码，对源代码的逻辑分析，找出漏洞，编写EXP,在编写EXP的过程中，我们可以使用gdb在本地动态调试，一步一步修改我们的EXP,Pwn掉这题！ -->
</div> 

---

###   🛡   AWD  / AWDP



## 🗡渗透工具

### <img src="./src/chrome.svg" width="19" height="13" />浏览器插件

| 插件名称                                                     | Usage                                                        | 项目地址                                                     | 其他 |
| :----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---- |
| hackbar <img src="./src/chrome.svg" width="19" height="13" /> | 浏览器插件，能够在页面上直接完成 请求/响应内容编辑，完成各种包括但是不限于伪造的工作。 | [谷歌商店](https://chrome.google.com/webstore/detail/ginpbkfigcoaokgflihfhhmglmbchinc)<br />[Github](https://github.com/Mr-xn/hackbar2.1.3) | /    |
| Proxy SwitchyOmega <img src="./src/chrome.svg" width="19" height="13" /> | 代理管理软件，方便一个浏览器多个代理端口的切换。             | [Github](https://github.com/FelisCatus/SwitchyOmega)         | /    |
| Wappalyzer <img src="./src/chrome.svg" width="19" height="13" /> | 页面技术识别软件，方便快速定位页面的框架技术等信息           | [官网](https://www.wappalyzer.com/)                          | /    |

### 📡信息收集

- 资产搜索 / 测绘

| 名称                                                         | 关于                                                 | Usage                                                  |
| ------------------------------------------------------------ | ---------------------------------------------------- | ------------------------------------------------------ |
| ----**在线工具**                                             |                                                      |                                                        |
| Fofa<img src="./src/chrome.svg" width="19" height="13" />    | [Fofa_viewer](https://github.com/wgpsec/fofa_viewer) | [UsagePage](https://fofa.info/)                        |
| 360Quake<img src="./src/chrome.svg" width="19" height="13" /> | /                                                    | [UsagePage](https://quake.360.net/quake)               |
| 钟馗之眼<img src="./src/chrome.svg" width="19" height="13" /> | /                                                    | [UsagePage](https://www.zoomeye.org/)                  |
| 鹰图平台<img src="./src/chrome.svg" width="19" height="13" /> | /                                                    | [UsagePage](https://hunter.qianxin.com/)               |
| 谛听<img src="./src/chrome.svg" width="19" height="13" />    | 工控安全的搜索引擎                                   | [UsagePage](https://www.ditecting.com/)                |
| VirusTotal<img src="./src/chrome.svg" width="19" height="13" /> | /                                                    | [UsagePage](https://www.virustotal.com/)               |
| Shodan<img src="./src/chrome.svg" width="19" height="13" />  | /                                                    | [UsagePage](www.shodan.io)                             |
| Google<img src="./src/chrome.svg" width="19" height="13" />  | [GoogleHackingTool](https://ght.se7ensec.cn/)        | [UsagePage](www.google.com)                            |
| SecurityTrails<img src="./src/chrome.svg" width="19" height="13" /> | /                                                    | [UsagePage](https://securitytrails.com/)               |
| ----**应用程序**                                             |                                                      |                                                        |
| Full-Scanner<img src="./src/application.svg" width="19" height="13" /> | 信息收集整合工具                                     | [Github](https://github.com/Zhao-sai-sai/Full-Scanner) |
| 灯塔(ARL)<img src="./src/application.svg" width="19" height="13" /> | 关联资产收集工具                                     | [Github](https://github.com/TophantTechnology/ARL)     |
| OneForAll<img src="./src/application.svg" width="19" height="13" /> | 功能强大的子域收集工具                               | [Github](https://github.com/shmilylty/OneForAll/)      |
| SiteScan<img src="./src/application.svg" width="19" height="13" /> | 一站化解决渗透测试信息收集任务                       | [Github](https://github.com/kracer127/SiteScan)        |

- 指纹识别

| 名称                                                         | UsagePage                     | 其他 |
| ------------------------------------------------------------ | ----------------------------- | ---- |
| 云悉指纹<img src="./src/chrome.svg" width="19" height="13" /> | http://www.yunsee.cn/         | /    |
| WhatCMS<img src="./src/chrome.svg" width="19" height="13" /> | https://whatcms.org/          | /    |
| 360 Finger-P<img src="./src/chrome.svg" width="19" height="13" /> | https://fp.shuziguanxing.com/ | /    |

- 实体信息收集

| 项目名称         | Usage                                                        | 项目地址                                               | 其他 |
  | ---------------- | ------------------------------------------------------------ | ------------------------------------------------------ | ---- |
  | Web-SurvivalScan | Web资产 快速存活验证。                                       | [Github](https://github.com/AabyssZG/Web-SurvivalScan) |      |
  | FileScan         | 敏感文件扫描 / 二次判断降低误报率 / 扫描内容规则化 / 多目录扫描。 | [Github](https://github.com/Mosuan/FileScan)           | /    |
  | Ffuf             | Go语言编写的Web Fuzz工具。                                   | [Github](https://github.com/ffuf/ffuf)                 | /    |
  | Dirsearch        | 目录扫描。                                                   | [Github](https://github.com/maurosoria/dirsearch)      | /    |
  | Gobuster         | 目录扫描。                                                   | [Github](https://github.com/OJ/gobuster)               | /    |
  | JSFinder         | JS信息收集。                                                 | [Github](https://github.com/Threezh1/JSFinder)         | /    |
  | Linkfinder       | JS中链接以及敏感参数扫描。                                   | [Github](https://github.com/GerbenJavado/LinkFinder)   | /    |
  | Phonebook        | 域名邮箱收集。                                               | [UsagePage](https://phonebook.cz/)                     | /    |
  | LaZagne          | 密码凭证收集。                                               | [Github](https://github.com/AlessandroZ/LaZagne)       | /    |

### 🚪端口扫描

| 项目名称 | Usage                                             | 项目地址                                           | 其他                                               |
| :------- | ------------------------------------------------- | -------------------------------------------------- | -------------------------------------------------- |
| Scaninfo | 开源、轻量、快速、跨平台 的红队内外网打点扫描器。 | [Github](https://github.com/redtoolskobe/scaninfo) | /                                                  |
| Nmap     | 最常用的端口扫描工具                              | [官网](https://nmap.org)                           | [官方中文文档](https://nmap.org/man/zh/index.html) |
| Zenmap   | Nmap_GUI                                          | [官网](https://nmap.org/zenmap/)                   | /                                                  |
| 御剑     | 御剑端口扫描工具                                  | [Github](https://github.com/foryujian/yjdirscan)   | /                                                  |

### 🧶代理抓包

| 项目名称   | Usage                                                        | 项目地址                                         | 其他                                               |
| :--------- | ------------------------------------------------------------ | ------------------------------------------------ | -------------------------------------------------- |
| Burp Suite | 代理抓包软件，用于Web应用程序的渗透测试和攻击<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [官网](https://portswigger.net/burp)             | /                                                  |
| Yakit      | 高度集成化的渗透测试平台。                                   | [Github](https://github.com/yaklang)             | [官方文档](https://www.yaklang.io/products/intro/) |
| Mitmproxy  | HTTP代理                                                     | [Github](https://github.com/mitmproxy/mitmproxy) | /                                                  |
| Proxifier  | 重定向应用程序到代理端口。                                   | [官网](https://www.proxifier.com/)               | /                                                  |

### 🤖Webshell管理

| 项目名称         | Usage                                                        | 项目地址                                                     | 其他 |
| ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---- |
| 蚁剑(antSword)   | 开源的跨平台Webshell管理工具。                               | [Github](https://github.com/AntSwordProject/antSword)        | /    |
| 冰蝎(Behinder)   | 具有优秀的加密传输特性的Webshell管理工具。                   | [Github](https://github.com/rebeyond/Behinder)               | /    |
| 哥斯拉(Godzilla) | 支持对载荷进行AES等各种加密，支持自定义Http头，支持内存shell，提供丰富的Webshell功能。 | [Github](https://github.com/BeichenDream/Godzilla)           | /    |
| Weevely3         | 基于python编写，集webshell生成和连接于一身，采用c/s模式构建。 | [Github](https://github.com/epinna/weevely3)                 | /    |
| 天蝎权限管理工具 | 基于冰蝎加密流量进行WebShell通信管理的原理，目前实现了jsp、aspx、php、asp端的常用操作功能，做出了许多优化。**(已停止外部更新)** | [Github](https://github.com/shack2/skyscorpion)              | /    |
| 中国菜刀         | PHP、ASP、ASPX webshell管理工具 对一些古老站点有奇效。**(已停止维护)** | [Github](https://github.com/raddyfiy/caidao-official-version) | /    |

### 🎯漏洞探测&利用

| 项目名称                                                     | Usage                                                        | 项目地址                                                     | 其他                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------- |
| Goby                                                         | 集资产测绘和漏洞扫描 以及多样化功能插件于一身的扫描器。      | [官网](https://gobysec.net/)                                 | /                                     |
| Xray                                                         | 一款功能强大的安全评估工具。<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/chaitin/xray)                    | [官方文档](https://docs.xray.cool/#/) |
| SuperXray                                                    | Xray扫描器的GUI版本。<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/4ra1n/super-xray)                | /                                     |
| Vscan                                                        | 开源、轻量、快速、跨平台 的网站漏洞扫描工具。                | [Github](https://github.com/veo/vscan)                       | /                                     |
| Afrog                                                        | 高性能的漏洞扫描器。                                         | [Github](https://github.com/zan8in/afrog)                    | /                                     |
| Scaninfo                                                     | 开源、轻量、快速、跨平台 的红队内外网打点扫描器。            | [Github](https://github.com/redtoolskobe/scaninfo)           | /                                     |
| OSV-Scanner                                                  | 谷歌开源漏洞扫描器                                           | [Github](https://github.com/google/osv-scanner)              | /                                     |
| Wpscan                                                       | Wordpress漏洞扫描器                                          | [Github](https://github.com/wpscanteam/wpscan)               |                                       |
| Nuclei                                                       | 一款注重于可配置性、可扩展性和易用性的基于模板的快速漏洞扫描器,可通过yaml构建模板 | [Github](https://github.com/projectdiscovery/nuclei/tree/main) | /                                     |
| OA-EXPTOOL                                                   | OA综合利用工具，集合将近20款OA漏洞批量扫描                   | [Github](https://github.com/LittleBear4/OA-EXPTOOL)          | /                                     |
| Apt_t00ls                                                    | 高危漏洞利用工具                                             | [Github](https://github.com/White-hua/Apt_t00ls)             | /                                     |
| Railgun                                                      | 具有GUI界面的渗透工具，集成了端口扫描、端口爆破、web指纹扫描、漏洞扫描、漏洞利用以及编码转换功能 | [Github](https://github.com/lz520520/railgun)                | /                                     |
| ----**Database**                                             |                                                              |                                                              |                                       |
| SQLMap<img src="./src/application.svg" width="19" height="13" /> | 自动化的SQL注入利用工具<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/sqlmapproject/sqlmap)            | /                                     |
| SuperSQLInjectionV1                                          | C#开发的SQL注入辅助工具                                      | [Github](https://github.com/shack2/SuperSQLInjectionV1)      |                                       |
| ----**JavaWeb**                                              |                                                              |                                                              |                                       |
| Log4j2Scan                                                   | Log4j漏洞探测                                                | [Github](https://github.com/whwlsfb/Log4j2Scan)              | /                                     |
| Ysoserial<img src="./src/application.svg" width="19" height="13" /> | Java 反序列漏洞利用工具 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | [Github](https://github.com/frohoff/ysoserial)               | /                                     |
| Ysomap                                                       | Java 反序列漏洞利用工具                                      | [Github](https://github.com/wh1t3p1g/ysomap)                 | /                                     |
| SB-Scan(错乱                                                 | 针对Spring Boot的开源渗透框架，主要用作扫描敏感信息泄露端点，可直接测试Spring的相关高危漏洞。 | [Github](https://github.com/AabyssZG/SpringBoot-Scan)        | /                                     |
| SpringBootExploit                                            | SpringBoot综合利用工具                                       | [Github](https://github.com/0x727/SpringBootExploit)         | /                                     |
| ShiroAttack2                                                 | Shiro框架漏洞利用工具                                        | [Github](https://github.com/SummerSec/ShiroAttack2)          | /                                     |
| Fastjson                                                     | Fastjson扫描器，可识别版本、依赖库、autoType状态等           | [Github](https://github.com/a1phaboy/FastjsonScan)           | /                                     |
| WeblogicTool                                                 | WeblogicTool，GUI漏洞利用工具，支持漏洞检测、命令执行、内存马注入、密码解密等 | [Github](https://github.com/KimJun1010/WeblogicTool)         | /                                     |
| Struts2-Scan                                                 | Struts2漏洞利用扫描工具                                      | [Github](https://github.com/HatBoy/Struts2-Scan)             | /                                     |
| JNDIExploit                                                  | JNDI多功能利用工具                                           | [Github](https://github.com/qi4L/JNDIExploit)                | /                                     |
| ----**PHPWeb**                                               |                                                              |                                                              |                                       |
| Thinkphp_gui_tools                                           | ThinkPHP漏洞综合利用工具                                     | [Github](https://github.com/bewhale/thinkphp_gui_tools)      | /                                     |
| ThinkLog                                                     | Tk3,5,6 日志泄漏批量下载                                     | [Github](https://github.com/Lotus6/ThinkLog)                 | /                                     |
| ----**XSS**                                                  |                                                              |                                                              |                                       |
| XSStrike                                                     | XSS扫描器                                                    | [Github](https://github.com/s0md3v/XSStrike)                 | /                                     |
| PwnXSS                                                       | XSS漏洞扫描利用工具                                          | [Github](https://github.com/pwn0sec/PwnXSS)                  | /                                     |
| Dalfox                                                       | xss漏洞扫描器                                                | [Github](https://github.com/hahwul/dalfox)                   | /                                     |
| ----**Other**                                                |                                                              |                                                              |                                       |
| Commix                                                       | All-in-One的自动化命令注入利用工具                           | [Github](https://github.com/commixproject/commix)            | /                                     |
| LFISuite                                                     | 本地文件包含利用工具                                         | [Github](https://github.com/D35m0nd142/LFISuite)             | /                                     |
| XXEinjector                                                  | XXE利用工具                                                  | [Github](https://github.com/enjoiz/XXEinjector)              | /                                     |
| Fuxploider                                                   | 文件上传利用工具                                             | [Github](https://github.com/almandin/fuxploider)             | /                                     |

### 📢提权辅助

- 免杀辅助

| 项目名称        | Usage                              | 项目地址                                             | 其他 |
| --------------- | ---------------------------------- | ---------------------------------------------------- | ---- |
| BypassAntiVirus | 免杀相关文献资料。                 | [Github](https://github.com/TideSec/BypassAntiVirus) | /    |
| AV_Evasion_Tool | 掩日 - 适用于红队的综合免杀工具。  | [Github](https://github.com/1y0n/AV_Evasion_Tool)    | /    |
| MateuszEx       | bypass AV生成工具，可过火绒 360 。 | [Github](https://github.com/sairson/MateuszEx)       | /    |
| ShellCodeLoader | Windows平台的shellcode免杀加载器。 | [Github](https://github.com/knownsec/shellcodeloade) | /    |

- 💻LOLBins

```
LOLBins(Living Off The Land Binaries) 
```

| 项目名称                                                     | Usage                     | 项目地址                                       | 其他 |
| ------------------------------------------------------------ | :------------------------ | ---------------------------------------------- | ---- |
| [GTFOBins](https://github.com/GTFOBins/GTFOBins.github.io)   | 类unix渗透-二进制文件列表 | [UsagePage](https://gtfobins.github.io/)       | /    |
| [LOLBAS](https://github.com/LOLBAS-Project/LOLBAS)           | Windows 渗透-程序         | [UsagePage](https://lolbas-project.github.io/) | /    |
| [LOLDrivers](https://github.com/magicsword-io/LOLDrivers)    | Windows 渗透-驱动         | [UsagePage](https://www.loldrivers.io/)        | /    |
| [LOOBins](https://github.com/infosecB/LOOBins)               | MacOS 渗透-程序           | [UsagePage](https://www.loobins.io/)           | /    |
| [reverse-shell-generator](https://github.com/0dayCTF/reverse-shell-generator) | 反弹shell辅助页面         | [UsagePage](https://www.revshells.com/)        | /    |

- 其他

| 项目名称                                                     | Usage             | 项目地址                                | 其他 |
| ------------------------------------------------------------ | :---------------- | --------------------------------------- | ---- |
| [reverse-shell-generator](https://github.com/0dayCTF/reverse-shell-generator) | 反弹shell辅助页面 | [UsagePage](https://www.revshells.com/) | /    |

### ⚙内网工具

| 项目名称      | Usage        | 项目地址                                             | 其他 |
| ------------- | ------------ | ---------------------------------------------------- | ---- |
| Fscan         | 内网扫描     | [Github](https://github.com/shadow1ng/fscan)         | /    |
| Stowaway      | 内网穿透     | [Github](https://github.com/ph4ntonn/Stowaway)       | /    |
| SharpHostInfo | 内网主机探测 | [Github](https://github.com/shmilylty/SharpHostInfo) | /    |
| LadonGo       | 内网渗透扫描 | [Github](https://github.com/k8gege/LadonGo)          | /    |
| Neo-reGeorg   | 代理工具     | [Github](https://github.com/L-codes/Neo-reGeorg)     | /    |

### ↪端口转发

| 项目名称 | Usage                                                        | 项目地址                                      | 其他 |
| -------- | ------------------------------------------------------------ | --------------------------------------------- | ---- |
| Openvpn  | 开源VPN连接工具。                                            | [Github](https://github.com/OpenVPN/openvpn)  | /    |
| Frp      | 专注于内网穿透的高性能的反向代理应用，支持 TCP、UDP、HTTP、HTTPS 等多种协议。可以将内网服务以安全、便捷的方式通过具有公网 IP 节点的中转暴露到公网。 | [Github](https://github.com/fatedier/frp)     | /    |
| Erfrp    | frp二开项目,相比于原项目，更加适配攻击队。                   | [Github](https://github.com/Goqi/Erfrp)       | /    |
| Frps     | 基于 [fatedier/frp](https://github.com/fatedier/frp) 原版 frp 内网穿透服务端 frps 的一键安装卸载脚本和 docker 镜像.支持 Linux 服务器和 docker 等多种环境安装部署。 | [Github](https://github.com/stilleshan/frps)  | /    |
| NPS      | 带有功能强大的web管理端，支持tcp、udp、socks5、http等几乎所有流量转发。 | [Github](https://github.com/ehang-io/nps)     | /    |
| GoProxy  | Go语言开发，多功能，支持多种协议，跨平台的代理服务。         | [Github](https://github.com/snail007/goproxy) | /    |

### 🔑密码攻击

| 项目名称           | Usage                                                | 项目地址                                             | 其他 |
| ------------------ | ---------------------------------------------------- | ---------------------------------------------------- | ---- |
| Hashcat            | 高性能，GPU/CPU 兼容的本地密码破解，支持多种不同格式 | [Github](https://github.com/hashcat/hashcat)         | /    |
| John the Ripper    | 简单易用的离线破解                                   | [Github](https://github.com/openwall/john)           | /    |
| Johnny             | John the Ripper GUI                                  | [Github](https://github.com/openwall/johnny)         | /    |
| Hydra              | 远程或在线密码的并行暴力破解。                       | [Github](https://github.com/vanhauser-thc/thc-hydra) | /    |
| 超级弱口令检查工具 | Windows平台的弱口令审计工具，支持批量多线程检查。    | [Github](https://github.com/shack2/SNETCracker)      | /    |

### ⚔ 渗透框架

| 项目名称     | Usage | 项目地址 | 其他 |
| ------------ | ----- | -------- | ---- |
| Metasploit   | MSF，综合渗透框架      | [Github](https://github.com/rapid7/metasploit-framework)         | /     |
| Yakit        | Yakit，国产框架，覆盖渗透全过程      | [Github](https://github.com/yaklang/yakit)         | /     |

### ⚔ C&C框架

| 项目名称     | Usage | 项目地址 | 其他 |
| ------------ | ----- | -------- | ---- |
| Metasploit   | MSF，支持多种C2功能      | [Github](https://github.com/rapid7/metasploit-framework)         | /     |
| Cobaltstrike | CS，业界最受欢迎、最成熟的的C2，但是其为付费工具      | [UsagePage](https://www.cobaltstrike.com/)         | /     |
| Sliver       | 开源、跨平台的C2，支持HTTP(S)和DNS等多种协议      | [Github](https://github.com/BishopFox/sliver)         | /     |
| Manjusaka    | 具有中文Web界面、支持一键部署启动的C2，且规避能力较强      | [Github](https://github.com/YDHCUI/manjusaka)         | /     |
| Havoc        | 开源、正在开发中的C2，界面和功能类似于CS      | [Github](https://github.com/HavocFramework/Havoc)         | /     |
| Empire       | 基于powershell的C2框架 **(已停止维护)**      | [Github](https://github.com/EmpireProject/Empire)         | /     |

###  🔍漏洞情报

| 名称 | 简介                   | 地址 |
| ---- | ---------------------- | ---- |
| OSV  | Google开源的在线漏洞库 | [UsagePage](https://osv.dev/) |
| Vulmon | 漏洞搜索引擎                       | [UsagePage](https://vulmon.com/)     |
|      |                        |      |
