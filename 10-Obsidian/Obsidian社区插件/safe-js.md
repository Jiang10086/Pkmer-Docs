---
uid: 1780392512007000
title: 'Obsidian 插件：Safe JS'
tags: ['编程与脚本', '安全与隐私', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它通过沙盒化的Web Worker和有限的远程过程调用（RPC）接口来运行由笔记拥有的JavaScript代码。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Safe JS

> [!Note] 插件名片
> - 插件名称：Safe JS
> - 插件作者：Moritz Jung
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它通过沙盒化的Web Worker和有限的远程过程调用（RPC）接口来运行由笔记拥有的JavaScript代码。
> - 插件分类：['编程与脚本', '安全与隐私', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/mprojectscode/obsidian-safe-js-plugin)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?safe-js)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/mprojectscode/obsidian-safe-js-plugin/master/README.md)



## 概述

### Safe JS插件总结
1. **主要功能**：通过沙盒化Web Workers和有限的主机API运行JavaScript代码。可运行笔记中的`safe-js`代码块、执行配置的vault `.js`文件、在工作区布局就绪后运行选定脚本，还支持调试、查看权限提示、存储数据等。
2. **适用场景**：适用于需要在Obsidian中安全运行JavaScript代码的场景，如自动化操作、数据处理等。
3. **核心特色**：代码运行在沙盒环境，不直接访问DOM、Node.js等；脚本通过声明权限和调用`api.*`函数与Obsidian交互；能记住脚本批准信息。
4. **使用建议**：该插件处于高度实验阶段，功能和API不稳定。使用时需谨慎，可通过`safe-js`代码块执行正常代码，开启调试功能时用`safe-js-debug`。运行脚本前仔细审查权限提示，可在插件设置中查看和清除存储的批准信息和脚本数据。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


