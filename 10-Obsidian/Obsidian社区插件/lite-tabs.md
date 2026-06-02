---
uid: 1780392511235000
title: 'Obsidian 插件：Lite Tabs'
tags: ['界面优化', '效率工具', '样式与美化', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。这是一个轻量级的标签页面板，支持垂直、卡片和砖石式布局，以性能优先。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Lite Tabs

> [!Note] 插件名片
> - 插件名称：Lite Tabs
> - 插件作者：Azona77
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。这是一个轻量级的标签页面板，支持垂直、卡片和砖石式布局，以性能优先。
> - 插件分类：['界面优化', '效率工具', '样式与美化', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/azona77/lite-tabs)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?lite-tabs)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/azona77/lite-tabs/master/README.md)

![Lite Tabs](https://cdn.pkmer.cn/covers/lite-tabs_internal_0.png!pkmer)

## 概述

### 主要功能
Lite Tabs是一款轻量级Obsidian插件，可在独立侧边栏面板显示编辑器区域当前打开的标签页，支持垂直、卡片和砖石式布局，具备标签本地标题过滤、点击激活、中键或点击关闭、拖动排序等操作，还有隐藏文件图标、工具栏或非活动标签等显示选项，且样式可自定义。

### 适用场景
适用于需要快速切换标签页、管理多个打开文件的场景，能提高文件操作效率。

### 核心特色
性能优先，采用事件驱动更新，无轮询；使用`requestAnimationFrame`批量刷新；尽可能复用现有DOM元素；仅更新活动标签状态类；砖石布局使用测量的CSS网格跨度和批量刷新；不维护大型持久缓存或同步自定义组标题。且安全性高，不访问网络、不读写剪贴板、不操作库文件。

### 使用建议
从发布版下载相关文件放入指定路径，重启Obsidian并在社区插件中启用。可使用“Open Lite Tabs”打开面板，“Refresh Lite Tabs panel”根据当前工作区状态重建面板。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


