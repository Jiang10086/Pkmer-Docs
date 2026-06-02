---
uid: 1780392511044001
title: 'Obsidian 插件：Confluence Reader'
tags: ['第三方工具集成', '数据处理', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能把Confluence Server页面以Markdown格式只读同步到你的仓库里。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Confluence Reader

> [!Note] 插件名片
> - 插件名称：Confluence Reader
> - 插件作者：keonyrus
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能把Confluence Server页面以Markdown格式只读同步到你的仓库里。
> - 插件分类：['第三方工具集成', '数据处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/keonyrus/obsidian-confluence-sync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?confluence-reader)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/keonyrus/obsidian-confluence-sync/master/README.md)



## 概述

### 主要功能
Confluence Reader 插件可将 Confluence Server 页面以 Markdown 格式只读同步到 Obsidian 库中。支持按 URL、ID 或标题拉取单页，递归拉取页面及其子页面，内容更新时重新拉取，还能进行 Confluence 到 Markdown 的转换，包括代码块、宏、链接、图片等处理，支持版本跟踪和附件下载。

### 适用场景
适用于需要在 Obsidian 中查看和使用 Confluence 页面内容，且无需对 Confluence 内容进行修改的场景。

### 核心特色
- 支持多种拉取方式，可递归拉取页面树。
- 转换功能丰富，能处理多种 Confluence 元素。
- 具备版本跟踪，跳过未更改页面。
- 每个同步文件有 `confluence-*` YAML 字段。

### 使用建议
先安装插件，在设置中输入 Confluence 基础 URL 和个人访问令牌，测试连接后设置同步文件夹。使用命令或点击 ribbon 图标进行页面拉取操作。若使用自签名证书，需在设置中启用跳过 SSL 验证并重启 Obsidian。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


