---
uid: 2026060213561309
title: 'Obsidian 插件：Copy Embed Code'
tags: ['图片与PDF', '编辑工具', '自定义命令', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的手动审核哈。它能在图片的右键菜单里添加一个“复制嵌入代码”的选项。在实时预览模式和阅读模式下都能用，嵌套嵌入的图片也没问题。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Copy Embed Code

> [!Note] 插件名片
> - 插件名称：Copy Embed Code
> - 插件作者：dustinho
> - 插件说明：这个插件还没经过Obsidian官方人员的手动审核哈。它能在图片的右键菜单里添加一个“复制嵌入代码”的选项。在实时预览模式和阅读模式下都能用，嵌套嵌入的图片也没问题。
> - 插件分类：['图片与PDF', '编辑工具', '自定义命令', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/dustinho/obsidian-copy-embed-code)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?copy-embed-url)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/dustinho/obsidian-copy-embed-code/master/README.md)



## 概述

### 主要功能
为图片的右键上下文菜单添加“复制嵌入代码”选项，支持在实时预览、阅读模式及嵌套嵌入场景下使用，能复制本地图片的维基链接格式 `![[filename.png]]` 和外部图片的 Markdown 格式 `![](url)`。

### 适用场景
适用于需要复制图片嵌入代码的场景，无论是本地图片还是外部图片，在各种编辑和阅读模式下都能使用。

### 核心特色
- 不受光标位置限制，采用基于 DOM 的检测方式，能处理多层嵌套的图片。
- 采用双注入策略，在编辑模式下通过钩子进入编辑器菜单事件，在阅读模式和嵌套嵌入中直接注入 DOM 元素。

### 使用建议
手动安装时，从发布版本下载 `main.js` 和 `manifest.json`，创建对应文件夹并复制文件，最后在 Obsidian 设置中启用插件；也可从源代码构建。使用时，在 Obsidian 中右键点击图片，选择“复制嵌入代码”，然后粘贴到需要的地方。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


