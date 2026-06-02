---
uid: 1780392511261001
title: 'Obsidian 插件：Marp Inline Preview'
tags: ['编辑工具', '图表与可视化', '发布工具', '第三方工具集成', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能在编辑模式下内联渲染Marp幻灯片，在阅读模式下以完整HTML形式渲染。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Marp Inline Preview

> [!Note] 插件名片
> - 插件名称：Marp Inline Preview
> - 插件作者：Sotetsu Koyamada
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能在编辑模式下内联渲染Marp幻灯片，在阅读模式下以完整HTML形式渲染。
> - 插件分类：['编辑工具', '图表与可视化', '发布工具', '第三方工具集成', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/sotetsuk/obsidian-marp-inline-preview-plugin)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?marp-inline-preview)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/sotetsuk/obsidian-marp-inline-preview-plugin/master/README.md)



## 概述

### Marp Inline Preview插件总结
1. **主要功能**：在Obsidian中直接渲染Marp幻灯片。编辑模式下，在每个`---`分隔符下方内联显示渲染的幻灯片；阅读模式下，整个页面显示完整的渲染幻灯片。
2. **适用场景**：适用于需要在Obsidian中创建和预览Marp幻灯片的用户，无论是在桌面端还是移动端都能使用。
3. **核心特色**：采用Marp Core 4渲染器，与官方工具相同且支持移动端；支持通过`.marprc.yml`自定义主题；集成KaTeX数学公式，无需网络；Marp的每幻灯片CSS封装在Shadow DOM中，不影响Obsidian UI；可在设置中灵活开关编辑和阅读模式预览、数学支持及调整防抖间隔。
4. **使用建议**：在文件的YAML前置元数据中添加`marp: true`以启用插件功能。可在编辑和阅读模式间切换查看预览。若要使用自定义主题，可在保险库根目录或幻灯片文件旁放置`.marprc.yml`进行配置。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


