<!-- PROJECT LOGO -->
<br />

<p align="center">
  <a href="https://github.com/Zitann/HarmonyOS-Haps">
    <img src="https://www.harmonyos.com/resource/image/release2/home/harmonyOS_logo.png" alt="Logo" height="80">
  </a>

  <h3 align="center">鸿蒙Next Hap安装包合集</h3>
  <p align="center">
    欢迎来到鸿蒙Next HAP安装包合集仓库！本仓库汇集了各类适用于鸿蒙Next系统的HAP安装包，旨在为用户提供便捷的应用下载和更新资源。
  </p>

</p>

<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

## 目录

- [上手指南](#上手指南)
  - [开发前的配置要求](#开发前的配置要求)
  - [安装步骤](#安装步骤)
- [文件目录说明](#文件目录说明)
- [开发的架构](#开发的架构)
- [部署](#部署)
- [使用到的框架](#使用到的框架)
- [贡献者](#贡献者)
  - [如何参与开源项目](#如何参与开源项目)
- [版本控制](#版本控制)
- [作者](#作者)
- [鸣谢](#鸣谢)

### 声明

本仓库的所有内容仅供学习交流使用。如果您认为该内容侵犯了您的权益，请在 issue 中与我们联系，我们将立即删除相关内容。

### Hap安装包列表

| 软件                | 下载链接 | 仓库                                                         | 作者                                                  | 描述                                                         |
| ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------------------------------------------- | ------------------------------------------------------------ |
| 电脑端安装器        | [点击下载](https://github.com/likuai2010/auto-installer/releases/download/1.2.4/AutoInstaller.Setup.1.2.4.exe) | [Link](https://github.com/likuai2010/auto-installer/releases) | [likuai2010 (xiaobai)](https://github.com/likuai2010) | Auto-Installer是基于开源OpenHarmony项目的Hdc工具。该项目致力于为简化开发调试体验。我们正在积极开发中，以满足鸿蒙开发者随时调试应用需求。 |
| 鸿蒙调试助手        | [点击下载](https://github.com/likuai2010/auto-installer/releases/download/1.4.0/auto-installer.hap) | [Link](https://github.com/likuai2010/auto-installer/releases) | [likuai2010 (xiaobai)](https://github.com/likuai2010) | Auto-Installer是基于开源OpenHarmony项目的Hdc工具。该项目致力于为简化开发调试体验。我们正在积极开发中，以满足鸿蒙开发者随时调试应用需求。 |
| Clash for HarmonyOS | [点击下载](https://github.com/likuai2010/ClashMeta/releases/download/1.2.2/ClashForHarmonyOS-default-unsigned.hap) | [Link](https://github.com/likuai2010/ClashMeta/releases)     | [likuai2010 (xiaobai)](https://github.com/likuai2010) | HarmonyOS Next 首款GoLang开源移植应用 仅学习使用             |
| 网易云音乐社区版    | [点击下载](https://github.com/Zitann/HarmonyOS-Haps/raw/refs/heads/main/haps/NetEase-community-default-unsigned.hap) | 暂无                                                         | [襟江带海](https://space.bilibili.com/1022963781)     | 因为想听Dota2音乐，做了鸿蒙Next版的网易云客户端              |
| 开源阅读            | [点击下载](https://github.com/mgz0227/legado-Harmony/releases/download/Beta1028/Legado-unsigned.hap) | [Link](https://github.com/mgz0227/legado-Harmony/releases)   | [mgz0227 (miaogongzi)](https://github.com/mgz0227)    | 开源阅读鸿蒙版仓库                                           |
| Web-Telegram        | [点击下载](https://github.com/XHXYT/Web-Telegram-for-OpenHarmony/releases/download/1.3.5/Web-Telegram-for-HarmonyOS-NEXT_1.3.5-unsigned.hap) | [Link](https://github.com/XHXYT/Web-Telegram-for-OpenHarmony/releases) | [XHXYT (XHXYT)](https://github.com/XHXYT)             | 使用网页版电报封装的一个OpenHarmony平台应用，支持文件的下载与上传等功能。绝赞开发中(≧∇≦)/ |
| ppsspp              | [点击下载](https://github.com/likuai2010/auto-installer/releases/download/0.0.0/ppsspp-default-unsigned.hap) | [Link](https://github.com/likuai2010/auto-installer/releases) | [likuai2010 (xiaobai)](https://github.com/likuai2010) | PPSSPP是一个自由、开源、跨平台的相较于JPCSP等其他同类模拟器，PPSSPP更专注性能与可移植性的提升。 |
| RetroArch           | [点击下载](https://github.com/likuai2010/auto-installer/releases/download/0.0.0/RetroArch-default-unsigned.hap) | [Link](https://github.com/likuai2010/auto-installer/releases) | [likuai2010 (xiaobai)](https://github.com/likuai2010) | RetroArch，原名为SSNES是libretro API前端的实现，也是libretro项目重要的项目之一，是自由软件，开放源码采用GNU通用公共许可证。它支持多种平台，包含许多游戏主机，也能透过第三方固件破解后安装在诸多游戏主机上。 |

### 使用教程

开启手机开发者模式，并打开无限调试，使用[电脑端安装器](https://github.com/likuai2010/auto-installer/releases/download/1.2.4/AutoInstaller.Setup.1.2.4.exe)安装hap包，[点击查看教程](https://www.bilibili.com/video/BV1jM1QYbEb4/)

使用电脑端安装器安装鸿蒙调试助手后，可以直接在手机上安装hap包，[点击查看教程](https://www.bilibili.com/video/BV17YSLYgECd/)

### 反馈

如果您在使用过程中遇到无法使用的HAP安装包，或者发现有其他有用的HAP安装包，欢迎在issue中进行说明。我们将尽快处理您的反馈，确保资源的有效性和更新。同时，我们非常感谢您的贡献，帮助我们不断改进和丰富本仓库的内容。

### 鸣谢


- [likuai2010 (xiaobai)](https://github.com/likuai2010)
- [襟江带海](https://space.bilibili.com/1022963781)
- [mgz0227 (miaogongzi)](https://github.com/mgz0227)
- [XHXYT (XHXYT)](https://github.com/XHXYT)

<!-- links -->

[your-project-path]:Zitann/HarmonyOS-Haps
[contributors-shield]: https://img.shields.io/github/contributors/Zitann/HarmonyOS-Haps.svg?style=flat-square
[contributors-url]: https://github.com/Zitann/HarmonyOS-Haps/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Zitann/HarmonyOS-Haps.svg?style=flat-square
[forks-url]: https://github.com/Zitann/HarmonyOS-Haps/network/members
[stars-shield]: https://img.shields.io/github/stars/Zitann/HarmonyOS-Haps.svg?style=flat-square
[stars-url]: https://github.com/Zitann/HarmonyOS-Haps/stargazers
[issues-shield]: https://img.shields.io/github/issues/Zitann/HarmonyOS-Haps.svg?style=flat-square
[issues-url]: https://img.shields.io/github/issues/Zitann/HarmonyOS-Haps.svg