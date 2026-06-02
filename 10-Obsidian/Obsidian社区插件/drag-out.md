---
uid: 1780392511055000
title: 'Obsidian 插件：Drag Out'
tags: ['文件管理', '效率工具', '第三方工具集成', 'obsidian插件']
description: '可以直接用系统自带的拖拽操作，把文件从文件管理器拖到其他应用程序（比如本地文件系统、浏览器上传界面、邮件附件等），而不用通过应用程序的统一资源标识符（URI）来操作。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Drag Out

> [!Note] 插件名片
> - 插件名称：Drag Out
> - 插件作者：xwberry
> - 插件说明：可以直接用系统自带的拖拽操作，把文件从文件管理器拖到其他应用程序（比如本地文件系统、浏览器上传界面、邮件附件等），而不用通过应用程序的统一资源标识符（URI）来操作。
> - 插件分类：['文件管理', '效率工具', '第三方工具集成', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/xwberry/obsidian-drag-out)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?drag-out)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/xwberry/obsidian-drag-out/master/README.md)



## 概述

### 插件总结

#### 1. 主要功能
Drag Out 插件允许用户从 Obsidian 的文件资源管理器中，使用原生操作系统的拖放功能将文件拖到其他应用程序，而非拖放 `obsidian://` 链接。

#### 2. 适用场景
适用于浏览器上传文件、添加邮件附件、聊天应用发送文件、文件管理等需要从系统文件中获取实际文件的场景。

#### 3. 核心特色
该插件通过拦截文件树拖动操作，在按住配置的修饰键时，利用 Electron 的 `webContents.startDrag` API 暴露真实的磁盘文件路径，不按修饰键时则保留 Obsidian 默认的拖动行为。

#### 4. 使用建议
此插件目前处于实验阶段，仅支持桌面端，主要在 Windows 系统测试过。安装需手动下载 `main.js` 和 `manifest.json` 等文件到指定文件夹。使用时，在从 Obsidian 左侧边栏文件资源管理器拖动文件或文件夹到其他应用时按住修饰键，默认 Windows 和 Linux 为 Ctrl，macOS 为 Option/Alt，可在设置中更改。支持多选文件。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


