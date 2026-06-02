---
uid: 1780392510970000
title: 'Obsidian 插件：Bookmark API'
tags: ['文件管理', '编程与脚本', '自定义命令', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它提供了全局书签功能，可通过编程方式将文件添加到书签组。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Bookmark API

> [!Note] 插件名片
> - 插件名称：Bookmark API
> - 插件作者：niko-drossos
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它提供了全局书签功能，可通过编程方式将文件添加到书签组。
> - 插件分类：['文件管理', '编程与脚本', '自定义命令', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/niko-drossos/bookmarks-API)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?bookmark-api)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/niko-drossos/bookmarks-API/master/README.md)



## 概述

### 主要功能
Bookmark API 是一款 Obsidian 插件，可通过编程方式管理书签，提供添加、移除、移动书签及删除书签组等功能。

### 适用场景
适用于与 Templater、Dataview 等工具结合，或在 Obsidian 内运行的脚本中使用。

### 核心特色
- 提供全局函数，可直接调用。
- 支持对指定文件或当前活动文件进行书签操作。
- 可自动处理无 `.md` 扩展名的文件路径。
- 若添加书签时组不存在会自动创建，且会跳过重复项。

### 使用建议
- 需先启用 Obsidian 内置的“Bookmarks”核心插件。
- 按 `npm install` 和 `npm run build` 命令构建，将 `main.js` 和 `manifest.json` 复制到指定目录后在社区插件设置中启用。
- 调用 API 时，`filePath` 参数可选，省略则默认使用当前活动文件；`addBookmark` 可设置自定义显示名称。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


