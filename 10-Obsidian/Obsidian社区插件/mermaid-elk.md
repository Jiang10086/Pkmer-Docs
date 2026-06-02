---
uid: 1780392511275000
title: 'Obsidian 插件：Mermaid ELK'
tags: ['图表与可视化', '第三方工具集成', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能恢复用于渲染Mermaid图表的elk（Eclipse布局内核）渲染器。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Mermaid ELK

> [!Note] 插件名片
> - 插件名称：Mermaid ELK
> - 插件作者：keksnet
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能恢复用于渲染Mermaid图表的elk（Eclipse布局内核）渲染器。
> - 插件分类：['图表与可视化', '第三方工具集成', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/keksnet/obsidian-mermaid-elk)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?mermaid-elk)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/keksnet/obsidian-mermaid-elk/master/README.md)



## 概述

### Mermaid ELK插件总结
1. **主要功能**：为mermaidJS恢复elk（Eclipse Layout Kernel）渲染器支持，让用户可以使用elk渲染器来绘制mermaid图表。
2. **适用场景**：适用于需要绘制mermaid图表，且希望使用elk渲染器来优化图表布局的场景，如绘制流程图、组织结构图等。
3. **核心特色**：重新引入elk渲染器，为mermaid图表提供了新的布局方式，可能带来更美观、合理的图表展示效果。
4. **使用建议**：若要切换到elk渲染器，只需在mermaid图表代码前添加以下代码：
```yml
---
config:
  layout: "elk"
---
%% Your mermaid code here...
```
该插件依赖于[@mermaid-js/layout-elk](https://github.com/mermaid-js/mermaid)，若喜欢可支持该项目。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


