---
uid: 1780392511282000
title: 'Obsidian 插件：Mirror'
tags: ['编辑工具', '模板与链接处理', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的手动审核。它能把块引用转化为实时镜像嵌入内容，还带有内联预览和编辑功能。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Mirror

> [!Note] 插件名片
> - 插件名称：Mirror
> - 插件作者：Jonathan Simcoe
> - 插件说明：这个插件还没经过Obsidian官方人员的手动审核。它能把块引用转化为实时镜像嵌入内容，还带有内联预览和编辑功能。
> - 插件分类：['编辑工具', '模板与链接处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/jdsimcoe/obsidian-mirror)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?mirror)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/jdsimcoe/obsidian-mirror/master/README.md)

![Mirror](https://cdn.pkmer.cn/covers/mirror_internal_1.png!pkmer)

## 概述

### 主要功能
- 把全量块嵌入如 `![[Some note#^block-id]]` 转化为更实用的嵌入体验，在实时预览中变为可编辑的实时镜像块，阅读视图中呈现简化版本。
- 为反向链接侧边栏的链接提及添加复制按钮，能快速复制嵌入引用。
- 支持 `@mention` 搜索，可在编辑器中跨库查找匹配文本并转化为块引用。

### 适用场景
适合需要在笔记中频繁引用和编辑其他笔记内容，保持内容同步的场景。

### 核心特色
使引用内容不再静态，嵌入块与源内容实时关联，编辑一处即更新底层内容，避免内容不同步。能快速将已有链接提及转化为可复用的嵌入内容，无需手动查找块 ID。

### 使用建议
若从源码安装，需依次执行 `npm install`、`npm run build`，再将 `main.js`、`manifest.json` 和 `styles.css` 复制到 `<Vault>/.obsidian/plugins/mirror/` 目录，最后在设置的社区插件中启用。日常使用可善用复制按钮和 `@mention` 搜索功能提高效率。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


