---
uid: 1780392510935002
title: 'Obsidian 插件：Auto Refresh Explorer'
tags: ['文件管理', '自动化与AI', '效率工具', '第三方工具集成', 'obsidian插件']
description: '当外部同步工具在仓库里创建新文件时，它能自动刷新文件资源管理器。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Auto Refresh Explorer

> [!Note] 插件名片
> - 插件名称：Auto Refresh Explorer
> - 插件作者：mathieubonvaletpro-commits
> - 插件说明：当外部同步工具在仓库里创建新文件时，它能自动刷新文件资源管理器。
> - 插件分类：['文件管理', '自动化与AI', '效率工具', '第三方工具集成', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/mathieubonvaletpro-commits/auto-refresh-explorer)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?auto-refresh-explorer)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/mathieubonvaletpro-commits/auto-refresh-explorer/master/README.md)



## 概述

### 插件名称
Auto Refresh Explorer

### 主要功能
当外部同步工具（如 Syncthing、Dropbox 等）在 Obsidian 库中创建新文件时，自动刷新文件资源管理器。

### 适用场景
适用于使用外部同步工具同步文件到 Obsidian 库的场景，尤其在 Windows 系统下，Obsidian 内置文件监控有时无法及时检测到外部同步工具创建的文件。

### 核心特色
能在约 3 秒内检测到文件变化，直接将新文件注入 Obsidian 索引，无需手动重新加载库。通过低成本的 `adapter.stat()` 调用轮询监控文件夹，检测文件夹修改时间变化，找出缺失文件，创建 `TFile` 对象并触发更新。

### 使用建议
可手动安装，下载 `main.js` 和 `manifest.json` 复制到库内 `.obsidian/plugins/auto-refresh-explorer/` 文件夹并在社区插件中启用；也可等插件通过审核后在社区插件中搜索安装。目前无设置界面，可编辑 `main.js` 顶部常量修改监控文件夹和轮询间隔。兼容多系统和多种同步工具。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


