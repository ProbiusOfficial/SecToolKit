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

|                         项目名称                         |                           项目简介                           |                  项目地址                  |                   项目文档                   |
| :------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------: | :------------------------------------------: |
|       [Maye Lite](https://github.com/25H/MayeLite)       |   专注于文件快速启动的简洁、轻量级工具<img src="./src/windows.svg" width="17" height="17" />   |      https://github.com/25H/MayeLite       |        https://t.arae.cc/p/25804.html        |
|                [uTools](https://u.tools/)                | 一个极简、插件化的现代桌面软件。<br />通过自由选配丰富的插件，打造得心应手的工具集合<br /><img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> |              https://u.tools/              | https://u.tools/docs/guide/about-uTools.html |
| [Everything](https://www.voidtools.com/zh-cn/downloads/) |     一款强大的本地文件索引和搜索工具<img src="./src/windows.svg" width="17" height="17" />     | https://www.voidtools.com/zh-cn/downloads/ |                      /                       |

欢迎在issue中推荐更多的效率工具，但是请注意，适合自己的工具才是最好的，您并不需要下载所有的工具，请勿持有 ALL IN 思想。

## 🏴 CTF 工具合集

### 🪐  环境基础

| 工具名称     | Usage                                                        | 项目地址                                        | 使用文档 |
| ------------ | ------------------------------------------------------------ | ----------------------------------------------- | -------- |
| Vscode       | 最好用 最轻量的 文本编辑器 依靠扩展可实现包括但不限于 IDE 各种功能<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | https://code.visualstudio.com/                  |          |
| PyCharm      | Python 集成开发环境(IDE)<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | https://www.jetbrains.com/zh-cn/pycharm/        |          |
| PHPStorm     | PHP 集成开发环境(IDE)<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | https://www.jetbrains.com/zh-cn/phpstorm/       |          |
| Phpstudy     | Web环境 (Apache / Nginx + FTP + MySQL) 快速部署 <img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" />  <br />常用于 Web初学阶段的一些本地web页面的搭建 | https://www.xp.cn/download.html                 |          |
| Docker       | 容器服务 CTF动态题目的根基<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /><br />常用于 题目本地搭建测试 漏洞本地复现环境搭建 靶场环境搭建等 <br />最重要的是 容器具有高强度的安全性 | https://www.docker.com/                         |          |
| Navicat      | 优秀的数据库 管理 操作 调试 以及 可视化软件<a href="https://www.ghxi.com/navicat16.html"><img src="./src/windows.svg" width="17" height="17" /></a><img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | https://navicat.com.cn/download/navicat-premium |          |
| IDEA         | Java 集成开发环境(IDE)<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | https://www.jetbrains.com/zh-cn/idea/           |          |
| Watt Toolkit | Github Discord 部分谷歌服务 页面元素CDN 访问加速 \| <br />不是用来让你打游戏的啊喂(#`O′)！<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | https://github.com/BeyondDimension/SteamTools   |          |
| Clash        | 部分服务访问加速 \| 我也只能说这么多<img src="./src/windows.svg" width="17" height="17" /> <img src="./src/linux.svg" width="17" height="17" /> <img src="./src/apple.svg" width="17" height="17" /> | https://github.com/Dreamacro/clash              |          |
|              |                                                              |                                                 |          |
|              |                                                              |                                                 |          |



### 🌐  Web

| 工具名称           |      |      |      |      |
| :----------------- | ---- | ---- | ---- | ---- |
| hackbar            |      |      |      |      |
| Proxy SwitchyOmega |      |      |      |      |
| Wappalyzer         |      |      |      |      |
| Burp Suite         |      |      |      |      |
| Antsword           |      |      |      |      |
| dirsearch          |      |      |      |      |
| JD-GUI             |      |      |      |      |
|                    |      |      |      |      |
|                    |      |      |      |      |



### 🕸   MISC
### 🔑 Crypto
### 💫 Reverse
### 💥 PWN
###   ⚔   AWD 
