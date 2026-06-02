---
uid: 2026060213561313
title: 'Obsidian 插件：Copy Linked File'
tags: ['文件管理', '模板与链接处理', '效率工具', '编辑工具', 'obsidian插件']
description: '把链接或文件菜单项后面的仓库文件或本地文件的URL复制到Windows剪贴板。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Copy Linked File

> [!Note] 插件名片
> - 插件名称：Copy Linked File
> - 插件作者：flutterspike
> - 插件说明：把链接或文件菜单项后面的仓库文件或本地文件的URL复制到Windows剪贴板。
> - 插件分类：['文件管理', '模板与链接处理', '效率工具', '编辑工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/flutterspike/obsidian-copy-linked-file)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?copy-linked-file)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/flutterspike/obsidian-copy-linked-file/master/README.md)



## 概述

### 插件名称
Copy Linked File

### 主要功能
为Obsidian添加右键操作，可将内部链接、本地文件URL、嵌入内容或文件菜单项背后的真实文件复制到Windows剪贴板。

### 适用场景
当笔记中包含文件链接，如`[[paper.pdf]]`、`![[data.xlsx]]`等格式时适用。可将复制的文件粘贴到文件资源管理器、邮件、聊天应用或浏览器上传控件中。

### 核心特色
仅适用于Windows桌面版Obsidian，利用Node.js和Windows剪贴板API。不进行网络请求、无遥测数据、无需账户、不修改笔记或附件，仅读取复制所需的目标库文件路径。编码文件路径以处理特殊字符。

### 使用建议
需确保Obsidian桌面版、Windows系统且`powershell.exe`可用。右键点击Obsidian文件资源管理器中的库文件、编辑器内的内部维基链接或嵌入内容、指向本地`file:///` URL的Markdown链接等目标，选择“Copy linked file”即可复制。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


