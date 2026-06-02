---
uid: 1780392512173000
title: 'Obsidian 插件：URL Name Extractor'
tags: ['编辑工具', '模板与链接处理', '效率工具', '自动化与AI', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员手动审核。它能自动抓取网页标题，把纯网址转换成Markdown链接。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：URL Name Extractor

> [!Note] 插件名片
> - 插件名称：URL Name Extractor
> - 插件作者：valenzine
> - 插件说明：这个插件还没经过Obsidian官方人员手动审核。它能自动抓取网页标题，把纯网址转换成Markdown链接。
> - 插件分类：['编辑工具', '模板与链接处理', '效率工具', '自动化与AI', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/valenzine/obsidian-url-name-extractor)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?url-name-extractor)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/valenzine/obsidian-url-name-extractor/master/README.md)

![URL Name Extractor](https://cdn.pkmer.cn/covers/url-name-extractor_internal_0.gif!pkmer)

## 概述

### 插件名称
URL Name Extractor

### 主要功能
将纯URL自动转换为Markdown链接，通过抓取网页标题为链接命名。

### 适用场景
在Obsidian中撰写笔记时，需要将大量纯URL转换为带标题的Markdown链接的场景。

### 核心特色
1. 改进URL检测：能处理各类有效URL，包括不同顶级域名、DOI链接和学术文章URL。
2. 渐进式复杂度：采用智能请求策略，先尝试简单方法，避免触发反爬虫机制。
3. 可配置URL正则：可在插件设置中自定义URL匹配模式。
4. 特定网站标题提取：能为非标准HTML网站定义自定义标题正则模式。
5. 多 fallback 方法：支持 Archive.org 和 Microlink API，应对受保护网站。
6. 更好的错误处理：提供清晰错误信息和优雅降级。

### 使用建议
1. 一次选择少量URL进行命名。
2. URL请求时，在命令完成前不要更改文本选择或内容，以免结果乱序。
3. 可将命令绑定到快捷键，操作更便捷。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


