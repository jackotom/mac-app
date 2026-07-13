# 浮光 macOS

浮光是一款 macOS 效率工具，提供截图、长截图、录屏、贴图、OCR、剪贴板、图片处理、Markdown 等常用功能。

## 离线版 0.2（推荐）

下载：[FuGuang-0.2-offline.dmg](https://github.com/jackotom/mac-app/releases/download/v0.2/FuGuang-0.2-offline.dmg)

版本：`0.2`，基于官方 `4.0.1` 修改。

这个版本已经：

- 移除联网能力，截图等数据不能发送到网络。
- 关闭自动检查和自动安装更新。
- 移除更新下载组件。
- 清除本机个人签名信息。

SHA-256：

```text
4c8d8425c96298ad9a9d2f502f1ea41961ded10ca288ec35d7a138364b6a8c17
```

### 安装

1. 打开安装包，把“浮光.app”拖入“Applications”。
2. 首次截图时，在系统设置中允许“屏幕与系统音频录制”。
3. 如果 macOS 提示无法验证，请打开终端运行：

```bash
xattr -dr com.apple.quarantine /Applications/浮光.app
```

离线版不是原厂签名版本。在线公告、节假日刷新等联网功能将不可用。

## 旧版本（保留）

### 离线版 4.0.1

下载：[FuGuang-4.0.1-offline.dmg](https://github.com/jackotom/mac-app/raw/refs/heads/main/FuGuang-4.0.1-offline.dmg)

```text
61aa725542fa0bcbf4db8f4742817ef8041c2314cd66c5404ad71c2c124801f0
```

### 官方原版 4.0.1

下载：[FuGuang-4.0.1.dmg](https://github.com/jackotom/mac-app/raw/refs/heads/main/FuGuang-4.0.1.dmg)

```text
811bb56766e5a44c8af1f1e6ce6f24f91cc8fb48c586a2d696ae375ff3d21ffa
```

系统要求：macOS 14 或更高版本，支持 Apple 芯片和 Intel 芯片。

官方网站：[fg.vkr.me](https://fg.vkr.me)
