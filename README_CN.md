# Open In Other Application

- [English](/README.md)
- 中文版

> 支持在 Windows 系统上的 Chromium 内核浏览器中使用其他应用程序打开网址。

可以实现在 Chromium 内核浏览器中打开匹配网址后，自动运行其他应用程序并传递网址等信息的操作；或者可选的启用右键菜单在网页选择在其他应用程序打开网址。

仅支持 Widnows 系统。

## 安装方法

需要 2 个文件，可前往 [Releases](https://github.com/LightAPIs/open-in-other-application/releases/latest) 下载：

1. 用于在本机上运行的程序: `host.zip`。解压 `zip` 文件至本地磁盘上即可。
2. 浏览器扩展程序: `open-in-other-application_manifest-vx.crx`。若 Chromium 版本小于 88 时需要下载 `manifest-v2` 版本的扩展程序。将 `crx` 文件拖动至 `chrome://extensions/` 页面即可安装扩展程序。

## 使用方法

### 首次使用

初次使用时，需要先执行以下步骤:

1. 进入扩展程序选项，点击页面右上角复制按钮复制扩展程序 ID。
2. 运行之前解压至本地磁盘上的 `HostRegistrar.exe`，填写所复制的扩展程序 ID，点击注册按钮，等待提示操作完成后即可关闭程序。(_该程序目录及文件需要保留，不可删除。_)

### 常规使用

可以在扩展程序选项中添加需要运行的其他应用程序，以及编写需要打开某些网址的自动操作规则，同时还可以在右上角设置中开启显示网页右键菜单。

其次点击扩展程序图标可以切换自动规则的启用状态。
