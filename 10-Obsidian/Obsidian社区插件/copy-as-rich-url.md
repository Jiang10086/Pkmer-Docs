---
uid: 2026060213561308
title: 'Obsidian 插件：Copy as Rich URL'
tags: ['编辑工具', '模板与链接处理', '效率工具', '第三方工具集成', 'obsidian插件']
description: '将当前笔记以富超链接的形式复制到剪贴板。在FuseBase、Notion和Confluence这类富文本编辑器里，粘贴出来就是一个可点击的链接。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Copy as Rich URL

> [!Note] 插件名片
> - 插件名称：Copy as Rich URL
> - 插件作者：brianling
> - 插件说明：将当前笔记以富超链接的形式复制到剪贴板。在FuseBase、Notion和Confluence这类富文本编辑器里，粘贴出来就是一个可点击的链接。
> - 插件分类：['编辑工具', '模板与链接处理', '效率工具', '第三方工具集成', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/brianling/obsidian-copy-as-rich-url)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?copy-as-rich-url)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/brianling/obsidian-copy-as-rich-url/master/README.md)



## 概述

### Copy as Rich URL插件总结
1. **主要功能**：将当前笔记以富超链接（标题 + `obsidian://` URL）形式复制到系统剪贴板，在富文本编辑器中粘贴时呈现为可点击的链接。
2. **适用场景**：适用于需要在FuseBase、Notion、Confluence、Slack、Gmail等富文本编辑器中分享Obsidian笔记链接的场景。
3. **核心特色**：区别于Obsidian内置的“Copy Obsidian URL”，该插件同时写入 `text/html` 和 `text/plain` 到剪贴板，避免在富文本编辑器中出现难看的 `obsidian://...` 字符串，能渲染出干净的可点击链接。
4. **使用建议**：打开要链接的笔记，可通过点击左侧功能区的“🔗 Copy as Rich URL”图标、运行命令面板命令或绑定热键来复制链接，在富文本编辑器粘贴为超链接，在纯文本编辑器粘贴为“标题\nURL”。安装可选择手动下载文件放入指定目录或使用BRAT插件添加仓库URL。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


