# Windows ARM上超棒的原生应用

<h3 align="center"> <a href='./README.md'>English</a> | 简体中文</h3>

Windows on ARM 原生软件集合。（仍在完善中）

## 目录

- [其他参阅](#其他参阅)
- [主要列表](#主要列表)
  - [Windows 功能](#windows-功能)
  - [应用程序](#应用程序)
  - [编程相关](#编程相关)
- [贡献](#贡献)

## 其他参阅

[arminask/windows-arm-apps](https://github.com/arminask/windows-arm-apps) 也在维护一个类似的列表。

目前，这两个仓库中所列举的应用程序之间存在一些差异，两个仓库中可能都有一些各自没有记录到的应用。如果你尝试在一个仓库中没有找到需要的，请务必检查另一个仓库的列表。

在将来，我会尝试合并这两个列表。

## 主要列表

此主列表只包含已经正式发布的软件。

此外，这里还有一个第三方构建或移植的软件列表：[3rd-party.md](3rd-party.md)

### Windows 功能

| 名称 | 说明 |
| - | - |
| 媒体播放器 | |
| 适用于 Android 的 Windows 子系统（WSA）| |
| 适用于 Linux 的 Windows 子系统（WSL）| WSLg 也已可用 |
| Windows 沙盒 | 需要 Windows 11 内部版本 22483 或更高 |
| Hyper-V | 需要专业版、企业版或教育版 |



### 应用程序

| 名称 | 类别 | 免费/付费/开源 | 说明 |
| - | - | - | - |
| [Chrome](https://www.google.com/chrome) | 浏览器 | 免费 |                |
| [Microsoft Edge](https://www.microsoft.com/zh-cn/edge) | 浏览器 | 免费 | 由 Microsoft 提供 |
| [Firefox](https://www.mozilla.org/zh-CN/firefox/new/) | 浏览器 | 开源 | |
| [MS Office Suite](https://www.office.com/) (Word, PowerPoint, Excel) | Office | 付费 | 由 Microsoft 提供 |
| [OneNote](https://www.onenote.com/) | 记笔记 | 免费 | 由 Microsoft 提供 |
| [Microsoft 日记](https://www.microsoft.com/en-us/garage/profiles/journal/) | 记笔记              | 免费                  |                             由 Microsoft 提供                                                              |
| [Microsoft To Do](https://todo.microsoft.com/) | 待办列表 | 免费 | 由 Microsoft 提供 |
| [OneDrive](https://onedrive.live.com/) | 云存储 | 免费 | 由 Microsoft 提供，需要加入 Windows 预览体验计划 |
| [GIMP](https://www.gimp.org/) | 图片编辑器 | 开源 | |
| [Spotify](https://open.spotify.com/) | 音乐 | 免费（客户端） | |
| [7-zip](https://www.7-zip.org/) | 文件解压缩工具 | 开源 | |
| [NanaZip](https://apps.microsoft.com/detail/9N8G7TSCL18R) | 文件解压缩工具 | 开源 | 支持Win11右键菜单 |
| [Zoom](https://zoom.us/) | 会议 | 免费 | |
| [Dropbox](https://www.dropbox.com/) | 云存储 | 免费 | |
| [Unigram](https://github.com/UnigramDev/Unigram) \* | 即时消息 | 开源 | 由于[此错误](https://github.com/UnigramDev/Unigram/issues/3010#issuecomment-1528811672)而暂时不可用 |
| [Typora](https://typora.io/) | Markdown 编辑器 | 付费 | |
| [Obsidian](https://obsidian.md/) | Markdown 编辑器，记笔记 | 免费 | |
| [Notepad++](https://notepad-plus-plus.org/) | 文本编辑器 | 开源 | |
| [PowerToys](https://github.com/microsoft/PowerToys) | 实用工具 | 开源 | 由 Microsoft 提供 |
| [Sandboxie-Plus](https://github.com/sandboxie-plus/Sandboxie) | 软件隔离工具 | 开源 | |
| [Xodo](https://xodo.com/) | PDF 查看、编辑器 | 免费 | 从 Microsoft Store 获取 |
| [Drawboard PDF](https://www.drawboard.com/) | PDF 查看、编辑器 | 免费 | 从 Microsoft Store 获取 |
| [Sumatra PDF (Preview)](https://www.sumatrapdfreader.org/free-pdf-reader) | PDF 查看器 | 开源 | 预览版 |
| [PDF-XChange Editor](https://pdf-xchange.eu/DL/pdf-xchange-editor.htm) | PDF viewer & editor       | free / paid        |                                             |
| [VLC](https://www.videolan.org/vlc/) | 媒体播放器 | 开源 | |
| [Everything](https://www.voidtools.com/) | 文件搜索 | 免费 | |
| [APK Installer](https://github.com/Paving-Base/APK-Installer) | WSA 工具 | 开源 | |
| [Files](https://files.community/) | 文件管理器 | 开源 | |
| [Rufus](https://rufus.ie/) | 制作 USB 启动盘 | 开源 | |
| [Pot](https://github.com/pot-app/pot-desktop) | OCR、翻译 | 开源 | |
| [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) | 实用工具 | 免费 | |
| [能源之星X](https://apps.microsoft.com/detail/energy-star-x/9NF7JTB3B17P) | 进程控制 省电 | 免费 | 优化CPU调度,提升续航 |
| [WsaExTool](https://apps.microsoft.com/store/detail/XPFFTJKNCD8SB5) | WSA 部署工具 | 免费 | 一键部署安卓子系统,方便安装安卓应用 |
| [哔哩哔哩](https://app.bilibili.com/) | 哔哩哔哩客户端 | 免费 | |
| [爱奇艺](https://apps.microsoft.com/detail/%e7%88%b1%e5%a5%87%e8%89%ba/9NBLGGH5WXNW) | 爱奇艺客户端 | 免费 | |


### 编程相关

| Name | Comment |
| - | - |
| [VS Code](https://code.visualstudio.com/) | |
| [JetBrains IDEs](https://www.jetbrains.com/) | |
| [Visual Studio](https://visualstudio.microsoft.com/) | |
| [Github Desktop (Beta)](https://desktop.github.com/beta/) | Beta 版 |
| [LLVM](https://llvm.org/) | |
| [CMake](https://cmake.org/) | |
| [Python](https://www.python.org/) | 自 2022-10-24 发布的 v3.11 起  |
| [OpenJDK (Microsoft Build)](https://www.microsoft.com/openjdk) | 由 Microsoft 构建的 OpenJDK |
| [Go Language](https://go.dev/) | |
| [Node.js](https://nodejs.org/) | 自 2023-04-10 发布的 v19.9.0 起 |
| [Rust](https://www.rust-lang.org/) | 自 2023-04-25 发布的 v1.26.0 起 |
| [OpenSSL for Windows](https://slproweb.com/products/Win32OpenSSL.html) | 自 v3.0.13 起（实验性）|



## 贡献

随时欢迎开启问题或提交PRs。
