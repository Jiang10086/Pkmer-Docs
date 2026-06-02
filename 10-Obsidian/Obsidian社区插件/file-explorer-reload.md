---
uid: 1780392511097001
title: 'Obsidian 插件：File Explorer Reload'
tags: ['文件管理', '界面优化', '效率工具', 'obsidian插件']
description: '这个插件还未经Obsidian官方人员手动审核。它可以重新加载文件资源管理器面板。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：File Explorer Reload

> [!Note] 插件名片
> - 插件名称：File Explorer Reload
> - 插件作者：mnaoumov
> - 插件说明：这个插件还未经Obsidian官方人员手动审核。它可以重新加载文件资源管理器面板。
> - 插件分类：['文件管理', '界面优化', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/mnaoumov/obsidian-file-explorer-reload)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?file-explorer-reload)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/mnaoumov/obsidian-file-explorer-reload/master/README.md)



## 概述

### 插件名称
File Explorer Reload

### 主要功能
为 Obsidian 提供重新加载文件资源管理器文件列表的功能，添加了“Reload File Explorer”命令以及“Reload Folder”和“Reload Folder with Subfolders”上下文菜单项，还支持编程调用。

### 适用场景
当在 Obsidian 打开的同时，在外部进行批量文件操作（复制、移动、删除），而文件资源管理器面板未及时反映这些更改时使用，避免出现面板显示与实际文件系统不一致的情况。

### 核心特色
相比常规解决文件显示不一致问题的方法（关闭并重新打开 Obsidian 或执行“Reload app without saving”命令），此插件能避免大库加载时不必要的等待时间。

### 使用建议
可直接在官方社区插件仓库安装该插件。若想安装最新的测试版，可按特定步骤操作。遇到文件显示问题时，可使用插件提供的命令或上下文菜单项进行文件列表的重新加载。也可通过编程调用 `reloadDirectory` 方法实现功能。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


