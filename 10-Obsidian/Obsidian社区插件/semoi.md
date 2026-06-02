---
uid: 1780392512026001
title: 'Obsidian 插件：Semoi'
tags: ['编辑工具', '第三方工具集成', '安全与隐私', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。在你写作时记录按键操作证据，并通过semoi.net生成加密的写作证明证书。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Semoi

> [!Note] 插件名片
> - 插件名称：Semoi
> - 插件作者：gjtorikian
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。在你写作时记录按键操作证据，并通过semoi.net生成加密的写作证明证书。
> - 插件分类：['编辑工具', '第三方工具集成', '安全与隐私', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/gjtorikian/semoi-obsidian)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?semoi)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/gjtorikian/semoi-obsidian/master/README.md)



## 概述

### 主要功能
Semoi 是一款 Obsidian 插件，在写作时捕获按键证据，通过 semoi.net 生成写作的加密证明证书。证明会被写入笔记的前置元数据，同时提供公开验证页面的链接。

### 适用场景
适用于需要证明写作过程和时间的场景，如学术写作、创作竞赛等，可作为创作过程的有效证明。

### 核心特色
- 仅记录编辑活动的类型（插入、删除、替换）、字符数量和相对时间戳，不记录具体输入字符，保护隐私。
- 以文件编辑为会话单位，记录会话开始和结束时间以及实际活跃打字时间。

### 使用建议
- 写作过程中插件会自动记录编辑活动，当需要生成证明时，运行“Mint proof for current note”命令。
- 注意会话在手动生成证明或重置前一直保留在内存中，无自动生成机制。若删除文件，内存中的会话会被清除；重命名文件，会话会延续到新路径。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


