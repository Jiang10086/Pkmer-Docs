---
uid: 1780392512202002
title: 'Obsidian 插件：Vim Wikilink Suggest Navigation'
tags: ['快捷键', '导航与状态栏', '模板与链接处理', '编辑工具', '效率工具', 'obsidian插件']
description: '可以用Vim风格的Ctrl + N / Ctrl + P来浏览内联维基链接建议（[[ ... ]]）；仅在弹出窗口打开时屏蔽全局热键。仅适用于桌面端。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Vim Wikilink Suggest Navigation

> [!Note] 插件名片
> - 插件名称：Vim Wikilink Suggest Navigation
> - 插件作者：noxx
> - 插件说明：可以用Vim风格的Ctrl + N / Ctrl + P来浏览内联维基链接建议（[[ ... ]]）；仅在弹出窗口打开时屏蔽全局热键。仅适用于桌面端。
> - 插件分类：['快捷键', '导航与状态栏', '模板与链接处理', '编辑工具', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/noxx/vim-wikilink-nav)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?vim-wikilink-nav)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/noxx/vim-wikilink-nav/master/README.md)



## 概述

### Vim Wikilink Suggest Navigation插件总结
1. **主要功能**：在Obsidian的`[[ wikilink ]]`建议弹窗打开时，支持使用Vim风格的Ctrl+N和Ctrl+P移动选择项，按Enter或Ctrl+Enter确认选择。
2. **适用场景**：适用于使用Vim模式的Obsidian用户，在输入`[[`触发链接建议弹窗时，可更便捷地进行选择操作。
3. **核心特色**：功能范围窄，仅针对链接建议弹窗，不影响快速切换器、命令面板和标签建议等功能；在弹窗打开时会屏蔽全局Ctrl+N热键，关闭后恢复。
4. **使用建议**：该插件仅支持桌面端（Windows / Linux），需Obsidian 1.4.0及以上版本。若已被纳入社区插件列表，可直接安装；否则需手动复制`manifest.json`和`main.js`到指定目录并在设置中启用。若出现未预期创建新笔记的情况，可反馈问题。需注意，若Obsidian未来更改相关DOM类，插件可能失效，修复只需更换一行选择器。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


