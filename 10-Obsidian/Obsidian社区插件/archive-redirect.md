---
uid: 2026060213561269
title: 'Obsidian 插件：Archive Redirect'
tags: ['文件管理', '数据处理', '效率工具', 'obsidian插件']
description: '它能把Markdown里的远程链接存档到本地，渲染时从本地缓存读取内容。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Archive Redirect

> [!Note] 插件名片
> - 插件名称：Archive Redirect
> - 插件作者：semsevens
> - 插件说明：它能把Markdown里的远程链接存档到本地，渲染时从本地缓存读取内容。
> - 插件分类：['文件管理', '数据处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/semsevens/obsidian-archive-redirect)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?archive-redirect)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/semsevens/obsidian-archive-redirect/master/README.md)



## 概述

### Archive Redirect插件总结
1. **主要功能**：将Markdown中引用的远程URL文件存档到本地缓存，在渲染笔记时透明地使用本地缓存，且不修改Markdown文件内容。
2. **适用场景**：适用于引用文章、推文、研究等富媒体内容的笔记场景，防止因原资源失效导致笔记中的嵌入内容无法显示。
3. **核心特色**：一是不修改Markdown文件，原远程URL可作为备用；二是按URL哈希存储，同一URL在多个笔记中只需存储一次，节省空间。
4. **使用建议**：在使用前可根据需求设置存档策略，如指定存档的域名规则和媒体文件扩展名。插件会自动扫描提取URL，下载文件到本地并在渲染时替换为本地路径，若本地无缓存则仍使用远程URL。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


