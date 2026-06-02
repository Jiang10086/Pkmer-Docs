---
uid: 1780392511020002
title: 'Obsidian 插件：CleanShot Embed'
tags: ['第三方工具集成', '图片与PDF', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能在渲染时获取新的签名链接，把CleanShot共享链接渲染成内联图片。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：CleanShot Embed

> [!Note] 插件名片
> - 插件名称：CleanShot Embed
> - 插件作者：janacm
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能在渲染时获取新的签名链接，把CleanShot共享链接渲染成内联图片。
> - 插件分类：['第三方工具集成', '图片与PDF', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/janacm/cleanshot-embed-obsidian)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?cleanshot-embed)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/janacm/cleanshot-embed-obsidian/master/README.md)



## 概述

### CleanShot Embed插件总结
1. **主要功能**：将CleanShot分享链接（如`cln.sh/XXX`）在Obsidian阅读视图中渲染为内联图片，通过在渲染时获取新的签名URL来展示图片。
2. **适用场景**：适用于在Obsidian笔记中引用CleanShot分享的图片，避免将图片下载到本地浪费Obsidian Sync存储空间。
3. **核心特色**：
    - 无需将图片存储在保险库中，不占用Obsidian Sync存储配额。
    - 采用内存缓存避免重复获取相同URL，卸载插件时缓存清除。
    - 若获取失败，会优雅回退，将原URL显示为可点击链接。
4. **使用建议**：
    - 复制CleanShot分享链接到笔记，切换到阅读视图即可看到图片。
    - 点击图片可在浏览器中打开原始分享页面。
    - 该插件仅支持桌面端，因移动端无法绕过`requestUrl`的CORS限制。可通过社区插件搜索安装，也可手动复制文件安装。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


