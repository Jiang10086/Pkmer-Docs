---
uid: 2026060213561498
title: 'Obsidian 插件：Rich Link Resolver'
tags: ['模板与链接处理', '编辑工具', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能把粘贴或选中的网址转换成带有网站图标和标题的Markdown富链接。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Rich Link Resolver

> [!Note] 插件名片
> - 插件名称：Rich Link Resolver
> - 插件作者：Almeida
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能把粘贴或选中的网址转换成带有网站图标和标题的Markdown富链接。
> - 插件分类：['模板与链接处理', '编辑工具', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/almeidazs/rich-link-obsidian)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?rich-link-resolver)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/almeidazs/rich-link-obsidian/master/README.md)



## 概述

### 1. 主要功能
Rich Link Resolver是一款Obsidian插件，能将粘贴或选中的URL转换为包含网站标题和图标（favicon）的Markdown富链接。支持自动处理粘贴的单个URL，也可通过命令或右键菜单处理选中的URL。

### 2. 适用场景
适用于在Obsidian笔记中插入网页链接的场景，可让链接展示更丰富。

### 3. 核心特色
- 自动解析粘贴的URL，获取网站标题和图标。
- 加载元数据时显示“Loading URL...”占位符。
- 直接使用网页图标URL，以16x16大小显示。
- 若无法解析图标，退化为普通Markdown链接。
- 可选择图标显示在标题前后。
- 能将解析后的URL渲染为预览卡片。
- 可忽略特定域名和精确URL的自动粘贴转换。

### 4. 使用建议
按照README中的步骤进行本地测试和开发。安装依赖、构建插件并复制到Obsidian库中，在设置里启用该插件。开发时使用`npm run dev`进入监听模式，每次重建后重新复制插件文件。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


