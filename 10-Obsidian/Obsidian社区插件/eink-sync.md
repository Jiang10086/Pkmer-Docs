---
uid: 1780392511068001
title: 'Obsidian 插件：E-Ink Sync'
tags: ['第三方工具集成', '图片与PDF', '数据处理', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能在reMarkable平板和Obsidian之间搭建本地优先的桥梁。无需依赖云端，就能把PDF里的高亮内容提取成Markdown格式。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：E-Ink Sync

> [!Note] 插件名片
> - 插件名称：E-Ink Sync
> - 插件作者：hwangso595
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能在reMarkable平板和Obsidian之间搭建本地优先的桥梁。无需依赖云端，就能把PDF里的高亮内容提取成Markdown格式。
> - 插件分类：['第三方工具集成', '图片与PDF', '数据处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/hwangso595/eink-sync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?eink-sync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/hwangso595/eink-sync/master/README.md)



## 概述

### E-Ink Sync插件总结
1. **主要功能**：实现reMarkable平板电脑与Obsidian的本地连接，包括将平板电脑文档文件通过Syncthing同步到电脑；从PDF中提取文本高亮内容到Obsidian的Markdown笔记并添加反向链接；将手写笔触注释渲染为PNG图像嵌入笔记；可在Obsidian侧边栏管理平板电脑文档库，进行浏览、搜索、存档和删除操作。
2. **适用场景**：适合使用reMarkable平板电脑阅读和批注PDF文件，且希望将批注内容整理到Obsidian笔记中的用户。
3. **核心特色**：本地优先，无需云端和订阅，数据不离开本地网络；支持reMarkable 1和2，兼容多种固件版本。
4. **使用建议**：需安装Obsidian 1.5.0+、Python 3.8+、rmscene、PyMuPDF和Syncthing。使用`pip install rmscene PyMuPDF`安装Python依赖。插件仅在触发同步或提取时调用Python，若未安装Python，插件会在设置向导中显示明确错误信息。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


