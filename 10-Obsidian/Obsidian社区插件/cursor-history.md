---
uid: 2026060213561338
title: 'Obsidian 插件：Cursor History'
tags: ['编辑工具', '导航与状态栏', '效率工具', 'obsidian插件']
description: '它能让你像在VS Code里一样，在不同文件间通过光标位置历史记录进行前后导航。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Cursor History

> [!Note] 插件名片
> - 插件名称：Cursor History
> - 插件作者：abdelrahmanhafez
> - 插件说明：它能让你像在VS Code里一样，在不同文件间通过光标位置历史记录进行前后导航。
> - 插件分类：['编辑工具', '导航与状态栏', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/abdelrahmanhafez/obsidian-cursor-history)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?cursor-history)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/abdelrahmanhafez/obsidian-cursor-history/master/README.md)



## 概述

### 插件名称
Cursor History

### 主要功能
该插件可跨文件跟踪光标位置历史，支持像VS Code一样进行前后导航。

### 适用场景
适用于在Obsidian中频繁切换文件、需要快速定位之前光标位置的场景，提高编辑效率。

### 核心特色
1. 以10行为阈值跟踪光标位置，小移动更新当前记录，大跳跃创建新记录。
2. 采用浏览器式堆栈，后退后前往新位置会清除前进历史。
3. 基于会话，最多保存50条记录。

### 使用建议
1. 可通过Obsidian社区插件或手动方式安装。
2. 首次安装会自动设置默认快捷键，可在“设置 - 热键”中修改。
3. 了解其位置判断规则，如同一行、10行内更新当前记录，10行以上或不同文件创建新记录。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


