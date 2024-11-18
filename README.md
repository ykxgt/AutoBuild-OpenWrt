# 自动编译lede的OpenWrt
[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat&logo=github&label=LICENSE)](https://github.com/esirplayground/AutoBuild-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/esirplayground/AutoBuild-OpenWrt.svg?style=flat&logo=appveyor&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/esirplayground/AutoBuild-OpenWrt.svg?style=flat&logo=appveyor&label=Forks&logo=github)
![GitHub last commit](https://img.shields.io/github/last-commit/esirplayground/AutoBuild-OpenWrt?label=Latest%20Commit&logo=github)

I18N: [English](README_EN.md) | [简体中文](README.md)

使用github actions 编译lede的OpenWrt [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)   

在此感谢P3TERX的出色工作：https://github.com/P3TERX/Actions-OpenWrt/  

在此感谢KFERMercer的出色工作：https://github.com/KFERMercer/OpenWrt-CI  

## 用法

🔥🔥[视频教程(国语)](https://youtu.be/9YO7nxNry-4)📺🎉

**1. 前提**
  - 登陆 [GitHub Actions](https://github.com/features/actions/signup)
  - Fork [这个仓库](https://github.com/esirplayground/AutoBuild-OpenWrt)
    
**2. 编译固件**
  - 点击repo顶部的 `[.github/workflows]`文件夹，您可以看到几个工作流文件，每个文件对应一个特定架构的设备。
  - ***`UPDATED`*** 点击菜单上的“run workflow”，点击左侧您要编译的设备，然后转到右侧的“run workflow”按钮，点击下拉菜单上的绿色按钮“运行工作流“就行了！！！

  - 构建将自动启动。可以在“Actions”页面上查看进度。

  - 构建完成后，单击“Artifacts”页面右上角的“Actions”按钮下载二进制文件。

  - 默认Web管理员IP:`192.168.5.1`，用户名`root`，无登录密码