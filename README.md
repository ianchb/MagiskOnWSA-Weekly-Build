# Magisk on WSA Weekly Build

## 介绍

不会用Actions又或者没有耐心？没问题！我提供了 MagiskOnWSA 的每周构建，保证随时都有新版本！

## 如何使用？

下载很简单！你只需在右下角的 Release 点击一下，看到了那个 WSA-with-magisk-GApps-pico_xxx.zip 了吗？点下去！下载完成后，只需要解压到一个空间足够的地方，然后运行里面的 Install.ps1 ，就可以了！就是这么方便！

## 显示“在此系统上禁止运行脚本”

在管理员权限的 PowerShell 里输入 set-executionpolicy remotesigned 并回车。

## 发布的配置是什么？

默认为x86 64位 insider fast 通道，删除亚马逊应用商店，Pico版Gapps，使用 debug 版 Magisk。

## TODO
- 上传到其他网络存储（如 OneDrive）

## 致谢

- [LSPosed](https://github.com/LSPosed/): MagiskOnWSA 作者
- [StoreLib](https://github.com/StoreDev/StoreLib): 下载 WSA 使用的API作者
- [Magisk](https://github.com/topjohnwu/Magisk): Magisk 项目仓库
- [The Open GApps Project](https://opengapps.org): Gapps 来源
- [WSA-Kernel-SU](https://github.com/LSPosed/WSA-Kernel-SU): 安装 Magisk 方案的仓库
- [WSAGAScript](https://github.com/ADeltaX/WSAGAScript): 整合 Gapps 方案的仓库
- [ChatGPT](https://chat.openai.com/): Bug 查找
- [Destroy-God/MagiskOnWSA-Weekly-Build](https://github.com/Destroy-God/MagiskOnWSA-Weekly-Build): Fork 来源
