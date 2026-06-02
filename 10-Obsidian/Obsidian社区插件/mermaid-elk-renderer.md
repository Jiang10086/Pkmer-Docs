---
uid: 1780392511274001
title: 'Obsidian 插件：Mermaid ELK Renderer'
tags: ['图表与可视化', '第三方工具集成', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能重新启用用于Mermaid图表的ELK（Eclipse布局内核）渲染器。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Mermaid ELK Renderer

> [!Note] 插件名片
> - 插件名称：Mermaid ELK Renderer
> - 插件作者：smolblackhole
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能重新启用用于Mermaid图表的ELK（Eclipse布局内核）渲染器。
> - 插件分类：['图表与可视化', '第三方工具集成', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/smolblackhole/mermaid-elk-renderer)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?mermaid-elk-renderer)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/smolblackhole/mermaid-elk-renderer/master/README.md)



## 概述

### Mermaid ELK Renderer插件总结
1. **主要功能**：重新启用Obsidian中Mermaid图表的ELK（Eclipse Layout Kernel）渲染器，支持通过`@mermaid-js/layout-elk`注册ELK布局，可选择使用捆绑的Mermaid 11版本进行渲染，保留现有图表前元数据，处理Mermaid标签边缘情况。
2. **适用场景**：适用于对Mermaid图表布局有更多需求，希望使用ELK布局引擎，或在官方Mermaid文档示例在Obsidian中无法正常显示时使用。
3. **核心特色**：仅在有`%% elk %%`标识处启用ELK，可选择使用较新的Mermaid 11版本，不影响现有前元数据设置。
4. **使用建议**：多数情况下，只需在想使用ELK渲染的Mermaid代码块顶部添加`%% elk %%`。若需更多控制，可查看高级设置指南。安装可通过社区插件搜索安装，也可手动下载文件到指定文件夹后启用。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


