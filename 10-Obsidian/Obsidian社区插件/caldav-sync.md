---
uid: 1780392510982000
title: 'Obsidian 插件：CalDAV Task Sync'
tags: ['第三方工具集成', '任务管理', '日历与时间', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能让标记了#caldav的Markdown任务与CalDAV服务器进行双向同步。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：CalDAV Task Sync

> [!Note] 插件名片
> - 插件名称：CalDAV Task Sync
> - 插件作者：speze88
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能让标记了#caldav的Markdown任务与CalDAV服务器进行双向同步。
> - 插件分类：['第三方工具集成', '任务管理', '日历与时间', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/speze88/obsidian-caldav-sync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?caldav-sync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/speze88/obsidian-caldav-sync/master/README.md)



## 概述

### 主要功能
CalDAV Task Sync 是一款 Obsidian 插件，可实现标记了特定标签（如 #caldav、#work 等）的 Markdown 任务与 CalDAV 服务器的双向同步。支持将任务完成状态推送到服务器，拉取远程任务标题和状态的更改。

### 适用场景
适用于需要在 Obsidian 笔记中管理任务，并与 CalDAV 服务器（如 mailcow、SOGo、Nextcloud 等）同步任务的用户。

### 核心特色
- 可将多个 CalDAV 日历映射到不同标签。
- 文件保存时自动同步，无需后台轮询。
- 任务 UID 存储在不可见的 HTML 注释中，不影响笔记可读性。

### 使用建议
- 手动安装时，需下载或构建 `main.js` 和 `manifest.json`，放入指定插件文件夹并在 Obsidian 中启用。也可从源码构建。
- 配置时，在设置中添加日历映射，包括日历名称、服务器 URL、用户名、密码和标签等信息。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


