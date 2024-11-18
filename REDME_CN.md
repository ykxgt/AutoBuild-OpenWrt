# 自动构建LEDE的OpenWrt
[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat&logo=github&label=LICENSE)](https://github.com/esirplayground/AutoBuild-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/esirplayground/AutoBuild-OpenWrt.svg?style=flat&logo=appveyor&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/esirplayground/AutoBuild-OpenWrt.svg?style=flat&logo=appveyor&label=Forks&logo=github)
![GitHub last commit](https://img.shields.io/github/last-commit/esirplayground/AutoBuild-OpenWrt?label=Latest%20Commit&logo=github)


构建OpenWrt框架[Lean的OpenWrt](https://github.com/coolsnowwolf/lede)使用GitHub操作
在此感谢P3TERX的出色工作：https://github.com/P3TERX/Actions-OpenWrt/  
在此感谢KFERMercer的出色工作：https://github.com/KFERMercer/OpenWrt-CI  
您可以编辑并启用“同步代码”YAML文件，让您的分叉仓库保持更新。
##使用方法
[视频教程（Mandrin）|视频教程（国语）](https://youtu.be/9YO7nxNry-4)
1.先决条件**
-注册[GitHub操作](https://github.com/features/actions/signup)
-Fork[这个GitHub仓库](https://github.com/esirplayground/AutoBuild-OpenWrt)
2.编译固件**
-点击repo顶部的[.github/works]文件夹，您可以看到几个工作流文件，每个文件对应一个特定的架构（设备）。
-***`UPDATED`***点击菜单上的“操作”，点击左侧您最喜欢的设备，然后转到右侧的“运行工作流”按钮，点击下拉菜单上的绿色按钮“运行工作流“，就是这样！！
-构建将自动启动。可以在“操作”页面上查看进度。
-构建完成后，单击“操作”页面右上角的“工件”按钮下载二进制文件。
-默认Web管理员IP:`192.168.10.1`，用户名`root`，无登录密码
3.同步代码**
-在**“On”**部分下取消注释“push-branches-master”3行，并提交更改，让脚本为您同步一次代码。
-取消**“On”**部分下的“schedule-cron”2行注释，并提交更改，让脚本每天凌晨3点[UTC+8]同步代码