<div align="center">

# MizuhokagaSoftwareList-Windows
<!-- prettier-ignore-start -->
<!-- markdownlint-disable-next-line MD036 -->
_✨ mizuhokaga 软件清单-Windows部分  ✨_
<!-- prettier-ignore-end -->
</div>

## C-commSoftware

### 基础必装软件

- [maple-font](https://github.com/subframe7536/maple-font) [maple-UI](https://github.com/subframe7536/maple-font/blob/other-resources/cn-resource/maple-ui/Maple%20UI.ttf) : 带连字和圆角的等宽字体、控制台字体和 UI 字体, 用于替换[Sarasa Gothic](https://github.com/be5invis/Sarasa-Gothic) 等宽字体,
- aio-runtimes : dll 一键全装工具,一键解决 ddl/c++运行库问题
- [シスター・クレア -SisterClaire- 鼠标皮肤](https://www.youtube.com/@Sister_Claire) : 修女克蕾雅的鼠标皮肤，用了很久了，喜欢克蕾雅也很久了

<!-- markdownlint-disable MD033 MD041 -->
<div align="center">
  <img alt="シスター・クレア" src="https://yt3.googleusercontent.com/ytc/AIdro_kuGBdAOZWF4REr8TTdcocOy65d69x50g2a2bowJ1hX5mM=s160-c-k-c0x00ffffff-no-rj" width="128" height="128"/>
  <p>シスター・クレア</p>
</div>

### 常用必装软件

- [StartAllBack](https://lizhi.shop/site/products/id/233) : Win 开始菜单任务栏增强工具，为了解决目前 win11 任务栏不能置于左侧的问题,已在数码荔枝入正
- [Listary Pro](https://lizhi.shop/site/products/id/58) : 本地文件搜索工具,软件快捷启动器,已在数码荔枝入正
- [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/all/#product-desktop-release) : 日常习惯使用的浏览器,定制浏览器工具栏的功能是刚需,插件列表见附录 1
- [Chrome](https://www.google.com/intl/en_sg/chrome/) : 谷歌浏览器,用于访问特定网站,确保与 Firefox 的浏览记录隔离,相比无痕浏览我更喜欢软件层面隔离
- [PixPin](https://pixpinapp.com/) : 带 OCR 的截图/贴图工具,用于替换 [Snipaste](https://www.snipaste.com/)
- [7-zip](https://7-zip.org/) | ([BandZip](https://www.bandisoft.com/bandizip/)) : 解压缩软件,BandZip 虽然有广告但是习惯了,7-zip 习惯专用于.7z 格式
- [图吧工具箱](https://www.tbtool.cn/) :内置了 Everthing、AIDA64、水晶雫 DiskInfo 等大量实用工具
- [PowerToys](https://github.com/microsoft/PowerToys/) : 微软官方的小工具合集,一般用于快捷键重新映射
- [TrafficMonitor](https://github.com/zhongyang219/TrafficMonitor) : 显示当前网速、CPU 及内存利用率的桌面悬浮窗软件，也支持任务栏显示
- 在人间 : VPN
- [百度网盘](https://pan.baidu.com/) : 备份、下载资源,目前买了年费会员
- 2345 看图王 : 习惯使用的照片查看软件,用的是网上修改的去广告版
- 软媒魔方 Docker : 实现 Mac 软件坞效果的小巧软件,美观易用
- [Steam](https://store.steampowered.com/) : 游戏分发平台
- Wallpaper Engine : 动态壁纸软件,多屏养眼神器

### 图书管理

- [koodo-reader](https://calibre-ebook.com/) : 习惯使用的开源电子书管理工具,界面漂亮!一般用来看技术 PDF 和轻小说
- [calibre](https://calibre-ebook.com/) : 也是电子书管理工具,我一般作为转换图书格式、解决 EPUB 格式在 koodo 读取失败的工具
- [Sumatra PDF](https://www.sumatrapdfreader.org/free-pdf-reader) : 小巧的阅读器,之前用过,之后被 koodo 替代

### 视频音频

- [PotPlayer](https://potplayer.tv/) : 习惯使用的视频播放器

### 聊天通讯

- [TIM](https://office.qq.com/) : 习惯使用,最开始使用是为了替换冗余的 QQ
- [微信](https://weixin.qq.com/) : 基本用于工作交流

### 办公软件

- [WPS Office](https://www.wps.cn/): 免费使用,所以替代 Office，安装后 win+s 搜`配置工具`关闭广告
- [腾讯会议](https://meeting.tencent.com/) : 工作交流远程开会

### 系统重装

- [傲梅分区助手](https://www.disktool.cn/): 无损分区工具
- [Windows 11 安装助手](https://www.microsoft.com/zh-cn/software-download/windows11/): 微软官方的 Windows 11 安装/重装软件.[win10 是这个](https://www.microsoft.com/zh-cn/software-download/windows10%20),Win10 密钥可以试试：W269N-WFGWX-YVC9B-4J6C9-T83GX

### 暂未分类

- [向日葵远程控制](https://sunlogin.oray.com/download) : 习惯的远程控制软件

## D-devSoftware

### 基础工具

- [vfox](https://github.com/version-fox/vfox) : 跨平台版本管理器,支持 Windows(非 WSL),[文档地址](https://vfox.lhan.me/zh-hans/guides/quick-start.html)
  - 挂载 vfox 到 powershell 时,以管理员身份打开终端,`set-ExecutionPolicy RemoteSigned`
- [Git](https://www.git-scm.com/) : 拉取/推送代码
  - git config --global user.name "yourName"
  - git config --global user.email "yourEmail"
  - git config --list
  - ssh-keygen
- node | npm | yarn : 前端基础组件,现已用 vfox 管理版本
- java : 使用 zulu 的 openJDK,[Zulu OpenJDK](https://www.azul.com/downloads/#zulu)
- [python](https://www.python.org/): python SDK
- [VS code](https://code.visualstudio.com/): 主力前端开发 IDE 兼 高级剪贴板,配置通过 GitHub 账号同步
- [Sublime Text](https://www.sublimetext.com/) : 高级剪贴板,但由于快捷键和 vs code 大相径庭,只是偶尔用用
- [Typora](https://typora.io/) : 写 Markdown ,已入正 ,激活码在 Gmail 中搜 Typora
  - [DrakeTyporaTheme](https://github.com/liangjingkanji/DrakeTyporaTheme) : Typora 主题

### 前端编程

- [WebStorm](https://www.jetbrains.com/webstorm/) : Jetbrains 全家桶之一,之前主力的前端开发 IDE,目前逐渐转向 VS code
- [微信开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html) ： 开发微信小程序
- [HBuilder X](https://www.dcloud.io/hbuilderx.html) ：开发 uniapp

### 后端编程

- Windows Terminal : Windows11 新终端好看好用了不少,Microsoft store 更新最新版后参 [视频](https://www.bilibili.com/video/BV1Ae411v798/) 配置

- Maven : Java 项目依赖下载管理,现已用 vfox 管理版本

- [Jetbrains](https://www.jetbrains.com/) 全家桶,配置使用谷歌账号登录 Jetbrains 来配置同步，已入正
  - [IntelliJ](https://www.jetbrains.com/idea/) IDEA : Java 开发
  - [PyCharm](https://www.jetbrains.com/pycharm/) : 写 py 脚本简化某些操作
- [PostMan](https://www.postman.com/) | [Apifox](https://www.apifox.cn/) : 接口测试工具 ,目前逐渐转向 Apifox
- [Docker Desktop](https://www.docker.com/products/docker-desktop/) : Windows 环境下安装容器快速部署服务,一般用于安装本地开发的数据库
  - [docker 安装 mysql](https://blog.csdn.net/qq_44831907/article/details/136336729)
  - [docker 安装 postgres](https://blog.csdn.net/qq_44831907/article/details/139595743)

### 数据库

- [DBeaver](https://dbeaver.io/download/) : 开源数据库可视化工具,支持的数据库比 navicat 多
- [Navicat](https://github.com/yrmatou/Navicat-Premium-15) : mysql 的数据库导入导出功能比 DBeaver 好用
- [Redis for Windows](https://github.com/zkteco-home/redis-windows) ： 非官方版本 win redis,clone 下来以管理员权限执行`install_redis.cmd`.repo: https://github.com/zkteco-home/redis-windows
- [AnotherRedisDesktopManager](https://github.com/qishibo/AnotherRedisDesktopManager) ： Redis 桌面(GUI)管理客户端

### 远程连接

- [XTerminal](https://terminal.icu/) | [MobaXterm](https://mobaxterm.mobatek.net/) : 终端工具,XTerminal 收费但小功能细节比 MobaXterm 好用,目前逐渐转向 XTerminal
- Cisco Secure Client : 连接公司内网的 VPN 工具

---

#### 附录 1 FireFox 插件清单

- 篡改猴 : 编写脚本增强网上冲浪体验,脚本备份在 GoogleDrive
- 浮图秀 : 鼠标悬浮图片上放大图片,主要用于查看视频网站封面、头像等
- BiliMini : Bilibili 通知工具
- Custom Scrollbars : 个性化滚动条,滚动条颜色设置 #e03997
- Inifinity 新标签页 : 自定义新标签页,配置使用 QQ 账号登录后云端同步
- Stylus : 自定义页面样式管理器,自定义样式备份在 GoogleDrive
- Vimium C : 全键盘操作浏览器的工具
- SingleFile : 将页面保存未单个 HTML 文件
- OneTab : 标签页存储器
- AdBlocker : 广告屏蔽

- Sleeping Hatsune Miku Animated : miku 动态主题

#### 附录 2 篡改猴脚本清单

- [AC-baidu-重定向优化百度搜狗谷歌必应搜索*favicon*双列](https://greasyfork.org/zh-TW/scripts/14178-ac-baidu-%E9%87%8D%E5%AE%9A%E5%90%91%E4%BC%98%E5%8C%96%E7%99%BE%E5%BA%A6%E6%90%9C%E7%8B%97%E8%B0%B7%E6%AD%8C%E5%BF%85%E5%BA%94%E6%90%9C%E7%B4%A2-favicon-%E5%8F%8C%E5%88%97)
- Bilibili Evolved
- CSDN 去广告沉浸阅读模式
- 本地 YouTube 下載器
- 知乎增强
- 知乎美化
- Pixiv 增强
- 贴吧全能助手(第三方修改)
- 网盘自动填写访问码【威力加强版】

#### 附录 3 Vimium C - 全键盘操作浏览器 自定义快捷键

```base
map w scrollUp
map s scrollDown
map a scrollLeft
map d scrollRight
map h scrollPageDown
map g scrollPageUp
map v scrollToTop
map b scrollToBottom
map rr goBack
map cc goForward
map qq previousTab
map ee nextTab
map z reloadTab
map o Vomnibar.activateInNewTab
```

#### 附录 4 VPN

使用 UU 在线工具-[在线文本加密工具](https://uutool.cn/txt-encrypt/)加密，
解密使用[在线文本解密工具](https://uutool.cn/txt-decrypt/)，密钥是真真（我相信你你不会忘记对应的谜底）

- 国内 : R5uSNB5Cbh6gbuicFMKvdO5mLMjh5MnKBNSwXgjy+2Q=
