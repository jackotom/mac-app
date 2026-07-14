# macOS 好用软件收藏

这里收录我在 Mac 上实际使用过、确认有用的软件。自制工具提供本仓库下载；第三方软件优先指向官方页面，避免安装包被篡改，也方便获得最新版。

## 软件总览

| 软件 | 主要用途 | 本机版本 | 下载 |
| --- | --- | --- | --- |
| 浮光 | 截图、录屏、OCR、贴图和图片处理 | 4.0.1 离线版 | [下载离线版](https://github.com/jackotom/mac-app/raw/refs/heads/main/FuGuang-0.2-offline.dmg) |
| 重启隔空投送 | 一键修复隔空投送异常 | 1.0 | [下载](https://github.com/jackotom/mac-app/releases/download/v0.3/Restart-AirDrop-1.0.dmg) |
| CC Switch | 管理和切换 AI 编程工具配置 | 3.16.5 | [官方下载](https://github.com/farion1231/cc-switch/releases/latest) |
| DockDoor | 给 Dock 增加窗口预览和快速切换 | 1.39.4 | [官方下载](https://github.com/ejbills/DockDoor/releases/latest) |
| Stats | 在菜单栏查看电脑运行状态 | 3.0.7 | [官方下载](https://github.com/exelban/stats/releases/latest) |
| LinearMouse | 调整鼠标滚动、速度和按键 | 0.11.2 | [官方下载](https://github.com/linearmouse/linearmouse/releases/latest) |
| IINA | 简洁好用的 macOS 视频播放器 | 1.4.4 | [官方下载](https://iina.io/download/) |
| OmniZip | 压缩和解压常见文件格式 | 2.4.1 | [App Store](https://apps.apple.com/app/omnizip/id1537056818) |
| ClipGrab | 下载并转换网络视频 | 3.9.16 | [官方下载](https://clipgrab.org/faqs/howto-download-clipgrab/) |
| Neat Download Manager | 管理和加速文件下载 | 1.3 | [官方下载](https://www.neatdownloadmanager.com/index.php/en/) |
| Chatbox 去广告版 | 去掉推广内容的个人修改版 | 1.21.1-adfree.1 | 暂不公开安装包 |

## 软件介绍

### 浮光

一款功能完整的截图工具，支持截图、长截图、录屏、贴图、文字识别、剪贴板和图片处理。

- **适合**：经常截图、标注图片、提取文字和录屏的人。
- **当前版本**：离线版 0.2，基于官方 4.0.1 修改。
- **特点**：移除联网、自动更新和更新下载组件。
- **安装**：打开 DMG，把“浮光.app”拖入“应用程序”。首次使用时允许屏幕录制权限。
- **来源**：[浮光官网](https://fg.vkr.me/)
- **SHA-256**：`4c8d8425c96298ad9a9d2f502f1ea41961ded10ca288ec35d7a138364b6a8c17`

### 重启隔空投送

一个很小的自制工具。隔空投送搜索不到设备、一直等待或传输异常时，双击即可重启相关服务。

- **适合**：经常遇到隔空投送失灵，又不想重启整台 Mac 的人。
- **当前版本**：1.0。
- **安装**：打开 DMG，把“重启隔空投送.app”拖入“应用程序”。
- **注意**：运行时可能要求输入本机管理员密码，用于重启系统服务。
- **下载**：[Restart-AirDrop-1.0.dmg](https://github.com/jackotom/mac-app/releases/download/v0.3/Restart-AirDrop-1.0.dmg)
- **SHA-256**：`4ff79c772f4eaba43fae5d41d523afefdbe173b5e63dba4918dd308058d5605f`

### CC Switch

集中管理 Claude Code、Codex、OpenCode 等工具的服务商配置，并快速切换不同配置。

- **适合**：同时使用多个 AI 编程工具或多个服务商的人。
- **当前本机版本**：3.16.5。
- **安装**：从官方 Release 下载 DMG，安装后按需要导入配置。
- **来源**：[官方项目](https://github.com/farion1231/cc-switch)

### DockDoor

把 Windows 风格的窗口预览带到 macOS Dock，并提供更直观的窗口切换。

- **适合**：经常同时打开很多窗口的人。
- **当前本机版本**：1.39.4。
- **权限**：窗口预览需要辅助功能和屏幕录制权限。
- **来源**：[官方项目](https://github.com/ejbills/DockDoor)

### Stats

在菜单栏实时显示 CPU、内存、硬盘、网络、电池、温度和风扇状态。

- **适合**：想随时了解 Mac 运行状态的人。
- **当前本机版本**：3.0.7。
- **特点**：免费开源，显示项目可以自由开关。
- **来源**：[官方项目](https://github.com/exelban/stats)

### LinearMouse

独立调整鼠标和触控板的滚动方向、指针速度、加速度和按键行为。

- **适合**：外接鼠标手感不舒服，或需要鼠标与触控板分别设置的人。
- **当前本机版本**：0.11.2。
- **权限**：自定义按键时需要辅助功能权限。
- **来源**：[官方项目](https://github.com/linearmouse/linearmouse)

### IINA

专门为 macOS 设计的视频播放器，界面简洁，支持大量视频和字幕格式。

- **适合**：想要一个比系统播放器支持格式更多、又保持原生体验的人。
- **当前本机版本**：1.4.4。
- **特点**：支持画中画、在线字幕、播放列表和丰富快捷键。
- **来源**：[IINA 官网](https://iina.io/)

### OmniZip

用于打开和创建 ZIP、7Z、RAR 等常见压缩文件。

- **适合**：希望用图形界面处理压缩包的人。
- **当前本机版本**：2.4.1。
- **安全说明**：本机现有副本来源无法可靠确认，因此不提供镜像，只保留 App Store 正版入口。
- **来源**：[Mac App Store](https://apps.apple.com/app/omnizip/id1537056818)

### ClipGrab

下载网络视频并转换成常见视频或音频格式。

- **适合**：保存自己有权下载的视频素材。
- **当前本机版本**：3.9.16。
- **安全说明**：本机副本运行后内容发生过变化，因此不重新打包，只提供官方入口。
- **来源**：[ClipGrab 官网](https://clipgrab.org/)

### Neat Download Manager

管理浏览器下载任务，支持暂停、继续和多段下载。

- **适合**：经常下载大文件，希望断点续传和集中管理任务的人。
- **当前本机版本**：1.3。
- **说明**：软件不允许第三方随意复制分发，本仓库只提供官方入口。
- **来源**：[官方网站](https://www.neatdownloadmanager.com/index.php/en/)

### Chatbox 去广告版

基于 Chatbox 制作的个人使用版本，移除了界面中的推广内容。

- **适合**：希望界面更干净的 Chatbox 用户。
- **当前本机版本**：1.21.1-adfree.1。
- **说明**：这是非官方修改版。目前没有把完整对应源码和许可文件一起公开，因此暂不提供安装包。
- **原项目**：[Chatbox](https://github.com/chatboxai/chatbox)

## 安全说明

- 第三方软件只保留官方入口，不上传来历不明或不允许转载的安装包。
- 安装前请确认下载域名和开发者信息。
- 需要屏幕录制、辅助功能等高权限的软件，只从官方来源安装。
- 本仓库不会上传个人配置、账号数据、下载记录或缓存。

## 浮光旧版本

- [离线版 4.0.1](https://github.com/jackotom/mac-app/raw/refs/heads/main/FuGuang-4.0.1-offline.dmg)，SHA-256：`61aa725542fa0bcbf4db8f4742817ef8041c2314cd66c5404ad71c2c124801f0`
- [官方原版 4.0.1](https://github.com/jackotom/mac-app/raw/refs/heads/main/FuGuang-4.0.1.dmg)，SHA-256：`811bb56766e5a44c8af1f1e6ce6f24f91cc8fb48c586a2d696ae375ff3d21ffa`
