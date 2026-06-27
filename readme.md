# awesome-smartisanOS

收集与 **SmartisanOS**（锤子科技操作系统）相关的优质 GitHub 项目、工具、资源和文章汇总。

## 官方组织

### [SmartisanTech](https://github.com/SmartisanTech)

锤子科技官方 GitHub 组织，托管了 SmartisanOS 相关的开源代码。包含 24 个仓库，涵盖 Android 系统源码、内核源码、特色功能应用、开发工具和 SDK 等。

## 特色功能

### [BigBang（大爆炸）](https://github.com/SmartisanTech/packages_apps_BigBang)

SmartisanOS 的「大爆炸」功能——通过长按屏幕识别并炸开文字，让用户可以精准地选择、复制、搜索或分享任意文字片段。Java 实现，Apache-2.0 许可。

### [OneStep（一步）](https://github.com/SmartisanTech/packages_apps_OneStep)

SmartisanOS 的「一步」功能——在屏幕侧边栏展示最近应用和常用联系人，支持快速拖拽分享文件、文字和图片，大幅提升多任务操作效率。Java 实现，Apache-2.0 许可。

## 内核源码

### [SmartisanOS Kernel Source](https://github.com/SmartisanTech/SmartisanOS_Kernel_Source)

SmartisanOS 开源内核源码合集，包含以下机型的内核：
- **T1** - 坚果手机一代
- **T2** - 坚果手机二代
- **U1（坚果）** - 坚果手机
- **M1 / M1L** - 锤子 M1 系列
- **U2 Pro（坚果 Pro）** - 坚果 Pro

基于 Linux Kernel 3.x，C 语言编写，GPL-2.0 许可。

## ROM 与内核

### [锤学研究 (Smartisan ROM 下载)](https://github.com/xingrz/smartisan)

SmartisanOS 官方系统包（OTA 全量包 / 线刷包）下载地址获取工具，支持所有锤子机型的历史版本检索。在线访问：[sm.cashewteam.top](https://sm.cashewteam.top/)（原站点已归档）。HTML/JavaScript 实现，Unlicense 许可。

### [Smartisax](https://github.com/intpfx/Smartisax)

面向坚果 R2（Smartisan OS 8.5.3 / Android 11）的 hard-ROM 深度定制工作区，支持分区镜像编辑、super 构建、APatch 免 Root 方案、TNT 远程串流等功能。Shell/Python 实现，Apache-2.0 许可。

### [LineageOS for Smartisan R1（trident）](https://github.com/LineageOS/android_device_smartisan_trident)

LineageOS 官方为坚果 R1（代号 trident，骁龙 845）提供的设备树配置，包含音频、显示、传感器、指纹、GPS 等硬件适配。C++/Makefile 实现。

### [LineageOS Kernel for Smartisan sdm845](https://github.com/rtx4d/android_kernel_smartisan_sdm845)

用于 LineageOS 的坚果 R1 内核源码（基于 Linux 4.9），支持骁龙 845 平台。C 实现。

### [Smartisan Trident Vendor](https://github.com/rtx4d/proprietary_vendor_smartisan_trident)

坚果 R1 专有 vendor 闭源二进制文件的 LineageOS 构建集成配置。Makefile 实现。

### [Smartisan sdm845 Kernel (Ephemera42)](https://github.com/Ephemera42/android_kernel_smartisan_sdm845)

坚果 R1 的 Android 内核源码（基于 Linux 4.9，Android 8.1 基线），包含骁龙 845 平台驱动。C 实现。

## 系统功能增强

### [TNT Anywhere](https://github.com/CashewTeam/TNT-Anywhere)

让 Smartisan TNT 桌面不再受限于固定硬件，可在更多设备和连接场景中被投屏、启动和运行。基于 Shizuku、VirtualDisplay、MediaCodec 和 Moonlight 串流协议实现免 Root 远程桌面。C/Java 实现，GPL-3.0 许可。

## 迁移与重构

### [BigBang NovaText](https://github.com/CashewTeam/BigBang_NovaText)

SmartisanOS 经典「大爆炸」功能的 Android 原生迁移项目。目标是将原版 BigBang 从 Smartisan 私有 ROM 解耦，迁移到标准 Android 平台，采用本地分词（cppjieba）、开源 OCR、Jetpack Compose 等现代技术栈。Java/C++ 实现，Apache-2.0 许可。

### [SmartisanOS APP Port](https://github.com/People-11/SmartisanOS_APP_Port)

SmartisanOS 应用移植计划，提供可直接在非锤子设备上安装运行的系统应用 APK，包括计算器、日历、时钟、指南针、邮件、短信、音乐、便签、录音机、视频播放器和天气等。

### [ArtisanMusic（锤子音乐播放器）](https://github.com/1900Star/MusicPlayer-Smartisan)

仿照 SmartisanOS 原生音乐播放器的本地音乐播放器，支持黑胶唱盘界面、歌词滚动、收藏、网络专辑图片、锁屏显示等功能。Java/Kotlin 实现。

### [Smartisan Music Revived（锤子音乐复刻）](https://github.com/wowohut/SmartisanMusic-Revived)

逆向复活 SmartisanOS 原生音乐播放器，使用 Kotlin + Media3 + legacy View 壳重写，1:1 还原黑胶唱盘、唱针拖拽、搓碟等经典交互，并新增网易云音乐登录、在线歌单、歌词缓存等能力。Kotlin 实现。

### [SmartisanNote (Unofficial)](https://github.com/johncaijing/SmartisanNote)

非官方的 SmartisanOS 便签 Android 复刻版，使用 Kotlin 语言开发，由知名开发者 drakeet 创作。

### [Smartisan Calculator Mod](https://github.com/chrdev/smartisan-calc)

锤子计算器 8.1.0 增强修改版。在原版基础上增加了长按复制结果、双击粘贴算式、抛掷手势切换横竖屏、按键音调节等实用功能。Smali 实现。

### [BigBang（独立实现）](https://github.com/baoyongzhang/BigBang)

SmartisanOS 「大爆炸」功能的独立 Android 实现。支持剪切板监听、本地分词（内置 jieba/jcseg/ik 多引擎）、微信内使用（Xposed / 无障碍模式），曾上架 Google Play。Java 实现，MIT 许可。

### [Smartisan Launcher Original Port](https://github.com/RANH-F/Smartisan-original-launcher)

基于坚果 Pro 3 原版桌面的移植工程，适配更多 Android 手机。支持 12/20 宫格、主题切换、翻页动画、图标包、页面锁、应用分身、自绘搜索页、在线更新等能力。Smali 实现。

### [Smartisan Launcher Maintained（锤子桌面维护版）](https://github.com/rianlu/smartisan-launcher-maintained)

面向 Android 12~16 的锤子桌面非官方维护版。基于 apktool 反编译工程持续修复兼容性问题，包括图标包适配、搜索修复、手势导航、主题在线源切换、桌面下拉通知栏等大量改进。Smali 实现。

## 桌面工具

### [HandShaker Android Maintained](https://github.com/rianlu/handshaker-android-maintained)

面向新版 Android 的 HandShaker（锤子手机助手）非官方维护版。通过 apktool 反编译修复了新版 Android 上的启动、权限、USB 连接和媒体访问兼容问题，并解锁了非锤子设备上的剪切板同步功能。Smali 实现。

### [HandShaker Mac Maintained](https://github.com/rianlu/handshaker-mac-maintained)

面向现代 macOS（Apple Silicon / Rosetta 2）的 HandShaker 非官方维护版。通过二进制补丁修复了原版在 macOS 15 上连接手机后卡死、内存暴涨的问题，恢复文件管理、图片预览等核心功能。Shell 脚本构建。

### [Smartisan Desktop Apps (Unofficial)](https://github.com/trojanyao/Smartisan-Desktop-Apps-Unofficial)

锤子科技非官方 Mac/Windows 桌面应用合集。基于 Nativefier 打包，包含锤子便签和子弹短信（聊天宝）的桌面版，支持消息推送和 Dock 角标。Nativefier 构建。

### [Smartisan Notes Downloader](https://github.com/wintertee/Smartisan-notes-downloader)

锤子便签云端数据导出工具。通过 Selenium WebDriver 自动化登录欢喜云，批量下载所有便签内容。Python 实现，Unlicense 许可。

## 开发组件

### [SmartisanPull（锤子下拉）](https://github.com/hougr6/SmartisanPull)

模仿「锤子阅读」下拉刷新效果的 Android 自定义控件。包含优雅的线段过渡圆弧动画和摩擦系数渐变的交互体验，支持 ListView/RecyclerView。Java 实现，MIT 许可。

### [SmartisanDialog](https://github.com/liying2008/SmartisanDialog)

Smartisan 风格对话框 Android 库。提供普通对话框、多选项对话框、警告对话框、单选列表、选项列表等丰富样式，完全自定义 UI。Java 实现，Apache-2.0 许可。

### [OneStepDemo](https://github.com/codeccc/OneStepDemo)

SmartisanOS「一步」功能的 Android 开发集成 Demo。展示如何通过 SmartisanOS SDK 在应用中实现文字、链接、单图、多图和文件的拖拽分享。Java 实现，MIT 许可。

### [Smartisan Watchface](https://github.com/betroy/smartisan_watchface)

基于 Android Wear 系统开发的仿锤子时钟表盘，支持白天/夜晚模式切换。Java 实现。

Smartisan 风格对话框 Android 库。提供普通对话框、多选项对话框、警告对话框、单选列表、选项列表等丰富样式，完全自定义 UI。Java 实现，Apache-2.0 许可。

## Web 项目

### [Poker Search](https://github.com/VecHK/poker-search)

### [Vue Smartisan Shop](https://github.com/helloforrestworld/Vue-smartisan-shop-)

基于 Vue 全家桶（Vue + Vue Router + Vuex）构建的锤子科技商城前端复刻，实现从商品浏览、加入购物车到下单支付的完整购物流程。Vue 实现。

### [t.tt](https://github.com/JieLiuRiver/t.tt)

仿锤子科技移动端官网的 Vue2 WebApp，包含首页展示、商品分类、登录注册等模块。Vue 实现。

### [Smartisan Notes Export（油猴版）](https://github.com/anyuxurl/smartisan-notes-export)

锤子便签云端导出助手（Tampermonkey/Violentmonkey 油猴脚本）。支持 ZIP 打包 / 单 Markdown / 多文件三种导出模式，零外部依赖。JavaScript 实现，MIT 许可。

### [Poker Search](https://github.com/VecHK/poker-search)

一款灵感来源于 Smartisan TNT「发牌手」的 Chrome 扩展插件。输入关键词后可同时在多个网站中搜索，以多窗口平铺方式展示搜索结果，支持自定义站点管理。TypeScript 实现，MIT 许可。

### [smartisanBlog（锤子博客）](https://github.com/itorr/smartisanBlog)

基于锤子便签的博客程序。将锤子便签中加星标的文章通过 API 或定时任务同步生成静态博客，支持 GitHub Pages 部署。JavaScript 实现，Apache-2.0 许可。

## 图标资源

### [smartisan-icon](https://github.com/ali-pay/smartisan-icon)

SmartisanOS 图标下载与浏览工具。提供 Go 编写的图标下载器和 Vue 构建的 Web 在线预览页面，方便开发者获取和查阅所有锤子系统图标。Go/Vue 实现。

### [Smartisan Yaru Blue Dark](https://github.com/Attenna/Smartisan-Yaru-blue-dark)

基于 Ubuntu Yaru 主题深度定制的 Linux 桌面图标包，融合 Smartisan 设计风格，重绘了 QQ、微信、Firefox、应用中心等常见应用图标。Shell 实现。

### [Smartisan Footprint Wallpapers](https://github.com/tianrunhe/smartisan-footprint-wallpapers)

SmartisanOS「足迹」系列壁纸完整收藏。包含开普勒、自然杂志、悉尼歌剧院、大英百科全书、人类登月、Google 生日等历史事件主题的高清壁纸。

## iOS 相关

### [SmartisanPlayer](https://github.com/Magic-Unique/SmartisanPlayer)

高仿 SmartisanOS 音乐播放器 UI 的 iOS 版音乐播放器。UI 素材从原版 APK 解包获取，支持在线音乐搜索和播放。Objective-C 实现。

### [Snowboard IconPack for Smartisan OS](https://github.com/Sunbelife/Snowboard-IconPack-for-Smartisan-OS)

为 iOS 越狱设备提供的 Smartisan OS 风格图标包，配合 Snowboard 主题引擎使用。包含大量从 SmartisanOS 提取或重新绘制的应用图标。Python 实现。

## 贡献

欢迎提交 PR 补充更多项目。

## 许可

MIT
