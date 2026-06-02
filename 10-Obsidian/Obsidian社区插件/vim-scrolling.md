---
uid: 1780392512202001
title: 'Obsidian 插件：Vim Scrolling'
tags: ['快捷键', '编辑工具', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。在启用Vim键位绑定后，它能在阅读模式下添加Vim风格的滚动操作（j/k、Ctrl+D/U、gg、G）。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Vim Scrolling

> [!Note] 插件名片
> - 插件名称：Vim Scrolling
> - 插件作者：xlongfeng
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。在启用Vim键位绑定后，它能在阅读模式下添加Vim风格的滚动操作（j/k、Ctrl+D/U、gg、G）。
> - 插件分类：['快捷键', '编辑工具', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/xlongfeng/obsidian-vim-scrolling)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?vim-scrolling)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/xlongfeng/obsidian-vim-scrolling/master/README.md)



## 概述

### 主要功能
在Obsidian启用Vim键位绑定后，为阅读模式添加Vim风格的滚动操作，如 `j/k` 逐行滚动、`Ctrl+D/U` 半页滚动、`gg` 到文档顶部、`G` 到文档底部。

### 适用场景
适用于习惯Vim操作，且在Obsidian阅读模式下希望延续Vim滚动操作习惯的用户。

### 核心特色
- 填补阅读模式下Vim导航键无响应的空白，让用户无论在何种模式下都能保持一致的Vim操作记忆。
- 解决阅读模式滚动后切换回源模式时光标位置与阅读内容不匹配的问题。
- 滚动无动画，避免动画队列延迟，且与源模式Vim操作行为一致。
- 按键重复时平滑滚动，无防抖或速率限制。
- `gg` 命令通过在500ms内按两次 `g` 触发。

### 使用建议
确保当前视图处于阅读模式，且在Obsidian设置中启用Vim键位绑定，即可使用这些滚动操作。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


