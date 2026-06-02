---
uid: 1780392511060000
title: 'Obsidian 插件：DuckDB and MotherDuck'
tags: ['数据处理', '第三方工具集成', '数据分析', '编程与脚本', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。你可以在笔记里用DuckDB SQL查询文件和云数据，还能把查询结果以Markdown格式直接固定在笔记里。要是想用云算力的话，还能选MotherDuck。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：DuckDB and MotherDuck

> [!Note] 插件名片
> - 插件名称：DuckDB and MotherDuck
> - 插件作者：Mehdi Ouazza
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。你可以在笔记里用DuckDB SQL查询文件和云数据，还能把查询结果以Markdown格式直接固定在笔记里。要是想用云算力的话，还能选MotherDuck。
> - 插件分类：['数据处理', '第三方工具集成', '数据分析', '编程与脚本', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/motherduckdb/obsidian-duckdb-motherduck)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?duckdb-motherduck)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/motherduckdb/obsidian-duckdb-motherduck/master/README.md)

![DuckDB and MotherDuck](https://cdn.pkmer.cn/covers/duckdb-motherduck_internal_0.png!pkmer)

## 概述

### DuckDB and MotherDuck 插件总结
1. **主要功能**：通过 DuckDB SQL 将外部数据引入 Obsidian 笔记，可查询本地或远程文件（如 Parquet、CSV 等）；将查询结果以 Markdown 表格形式内联缓存；支持按日或按周为笔记设置查询自动刷新；添加 MotherDuck 令牌可查询云数据和进行云计算。
2. **适用场景**：适用于需要在 Obsidian 中处理和展示数据的场景，如数据分析、数据可视化等。
3. **核心特色**：可离线使用本地 DuckDB WASM 进行查询；查询结果以 Markdown 形式缓存，使笔记成为自包含文档，便于在任何编辑器中阅读；支持自动刷新查询结果；可选择使用 MotherDuck 进行云计算。
4. **使用建议**：通过社区插件安装该插件，在笔记中粘贴 SQL 查询代码块，在阅读模式下使用“Run”“Freeze”“Clear freeze”按钮操作。若要查询云数据，需在设置中添加 MotherDuck 令牌。可参考 [demo 页面](https://github.com/motherduckdb/obsidian-duckdb-motherduck/blob/main/docs/demo.md) 获取更多示例。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


