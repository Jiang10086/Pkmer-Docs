---
uid: 1780392511999000
title: 'Obsidian 插件：Right-Click Tools'
tags: ['文件管理', '自定义命令', '效率工具', '日历与时间', 'obsidian插件']
description: '这个插件还未经Obsidian官方人员手动审核。它能在资源管理器中添加右键操作，还会在侧边栏添加一个按钮，可用来创建当天日期的文件夹或笔记，并且能把选中的内容移动到可设置的文件夹里。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Right-Click Tools

> [!Note] 插件名片
> - 插件名称：Right-Click Tools
> - 插件作者：z0lw
> - 插件说明：这个插件还未经Obsidian官方人员手动审核。它能在资源管理器中添加右键操作，还会在侧边栏添加一个按钮，可用来创建当天日期的文件夹或笔记，并且能把选中的内容移动到可设置的文件夹里。
> - 插件分类：['文件管理', '自定义命令', '效率工具', '日历与时间', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/z0lw/obsidian-right-click-tools)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?right-click-tools)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/z0lw/obsidian-right-click-tools/master/README.md)



## 概述

### 插件名称
Right - Click Tools

### 主要功能
- 创建今日日期文件夹（格式为 `YYYY - MM - DD`，若已存在则自动递增编号）。
- 创建今日日期笔记（格式为 `YYYY - MM - DD.md`，若已存在则自动递增编号），可从配置模板创建每日笔记。
- 将选定的文件或文件夹移动到可配置的目标文件夹。
- 可添加可选的功能区按钮，用于在配置文件夹中创建今日日期笔记。

### 适用场景
适用于需要快速创建日期相关文件夹或笔记，以及对文件和文件夹进行移动整理的Obsidian用户。

### 核心特色
轻量级插件，增强文件资源管理器的右键菜单功能，不进行网络访问、遥测，也不向外部服务发送数据。

### 使用建议
- 安装时，将 `main.js`、`manifest.json`、`styles.css` 三个文件放在 `/<Your Vault>/.obsidian/plugins/obsidian - right - click - tools/` 目录下，然后在Obsidian的社区插件中启用。
- 需使用Obsidian v1.5.0及以上版本。配置每日笔记模板时，在设置标签的“日期笔记模板”指定模板笔记路径，模板内的 `{{date}}`、`{{time}}`、`{{title}}` 会在创建时替换。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


