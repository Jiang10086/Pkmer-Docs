---
uid: 2026060213561274
title: 'Obsidian 插件：Artifact Embed'
tags: ['第三方工具集成', '多媒体', '效率工具', 'obsidian插件']
description: '你可以在笔记中嵌入交互式HTML文件、URL链接，或者以内联HTML的形式嵌入，将其呈现为Claude风格的沙盒化工件卡片。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Artifact Embed

> [!Note] 插件名片
> - 插件名称：Artifact Embed
> - 插件作者：LeonYew-Ley
> - 插件说明：你可以在笔记中嵌入交互式HTML文件、URL链接，或者以内联HTML的形式嵌入，将其呈现为Claude风格的沙盒化工件卡片。
> - 插件分类：['第三方工具集成', '多媒体', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/leonyew-ley/obsidian-artifact-embed)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?artifact-embed)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/leonyew-ley/obsidian-artifact-embed/master/README.md)



## 概述

### Artifact Embed插件总结
1. **主要功能**：可将交互式HTML文件、URL或内联HTML以Claude风格的沙盒化工件卡片形式嵌入Obsidian笔记中。每个工件在沙盒iframe中运行，还配备小工具栏用于重新加载、外部打开或复制源。
2. **适用场景**：当需要在笔记中添加如标签式速查表、图表小部件或独立迷你工具等内容时适用。
3. **核心特色**：
    - 统一语法，使用单一的```artifact```代码块自动检测内容是路径、URL还是内联HTML。
    - 默认沙盒化，在`<iframe sandbox="allow - scripts">`中运行，无同源访问，iframe的JS无法访问保险库、cookie或`window.parent`。
    - 支持主题感知，Obsidian的CSS自定义属性会注入iframe。
4. **使用建议**：若要在笔记中嵌入交互式HTML内容，可使用```artifact```代码块添加相应内容，享受沙盒化和主题适配的便利。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


