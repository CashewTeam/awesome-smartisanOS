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

### [Smartisan Launcher Maintained（锤子桌面维护版）](https://github.com/rianlu/smartisan-launcher-maintained)

面向 Android 12~16 的锤子桌面非官方维护版。基于 apktool 反编译工程持续修复兼容性问题，包括图标包适配、搜索修复、手势导航、主题在线源切换、桌面下拉通知栏等大量改进。Smali 实现。

## 桌面工具

### [HandShaker Android Maintained](https://github.com/rianlu/handshaker-android-maintained)

面向新版 Android 的 HandShaker（锤子手机助手）非官方维护版。通过 apktool 反编译修复了新版 Android 上的启动、权限、USB 连接和媒体访问兼容问题，并解锁了非锤子设备上的剪切板同步功能。Smali 实现。

### [HandShaker Mac Maintained](https://github.com/rianlu/handshaker-mac-maintained)

面向现代 macOS（Apple Silicon / Rosetta 2）的 HandShaker 非官方维护版。通过二进制补丁修复了原版在 macOS 15 上连接手机后卡死、内存暴涨的问题，恢复文件管理、图片预览等核心功能。Shell 脚本构建。

## Web 项目

### [smartisanBlog（锤子博客）](https://github.com/itorr/smartisanBlog)

基于锤子便签的博客程序。将锤子便签中加星标的文章通过 API 或定时任务同步生成静态博客，支持 GitHub Pages 部署。JavaScript 实现，Apache-2.0 许可。

## 图标资源

### [smartisan-icon](https://github.com/ali-pay/smartisan-icon)

SmartisanOS 图标下载与浏览工具。提供 Go 编写的图标下载器和 Vue 构建的 Web 在线预览页面，方便开发者获取和查阅所有锤子系统图标。Go/Vue 实现。

### [Snowboard IconPack for Smartisan OS](https://github.com/Sunbelife/Snowboard-IconPack-for-Smartisan-OS)

为 iOS 越狱设备提供的 Smartisan OS 风格图标包，配合 Snowboard 主题引擎使用。包含大量从 SmartisanOS 提取或重新绘制的应用图标。Python 实现。

## 贡献

欢迎提交 PR 补充更多项目。

## 许可

MIT
