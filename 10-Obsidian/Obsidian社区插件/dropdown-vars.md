---
uid: 1780392511059001
title: 'Obsidian 插件：Dropdown Vars'
tags: ['编辑工具', '数据处理', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。在阅读模式和实时预览模式下都有下拉菜单；可同步到前置元数据或内联Dataview。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Dropdown Vars

> [!Note] 插件名片
> - 插件名称：Dropdown Vars
> - 插件作者：majid-khonji
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。在阅读模式和实时预览模式下都有下拉菜单；可同步到前置元数据或内联Dataview。
> - 插件分类：['编辑工具', '数据处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/majid-khonji/obsidian-dropdown-vars)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?dropdown-vars)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/majid-khonji/obsidian-dropdown-vars/master/README.md)



## 概述

### Dropdown Vars插件总结
1. **主要功能**：可在笔记中轻松创建交互式下拉菜单，支持使用特定语法 `{Status: A | B | ^C}` 创建，点击可选择值，插入符号 `^` 标记选中项。还能将选择结果同步到Dataview内联字段，如 `(Status::C)`。
2. **适用场景**：适用于需要在笔记中进行交互选择并记录选择结果，同时希望利用Dataview进行数据查询和展示的场景。
3. **核心特色**：支持在阅读和实时预览模式下使用，下拉菜单语法简洁；与Dataview查询兼容，可方便地使用 `= this.Status` 进行查询；每次选择后，内联字段会实时更新。
4. **使用建议**：先在笔记中写入下拉菜单标记，如 `{Status: Todo | ^In Progress | Done}`；若要同步选择结果，可在插件设置中启用“Persist to inline Dataview”；之后可使用Dataview内联查询展示结果，如 `Status: `= this.Status``。也可根据需求选择将选择结果保存到YAML前置元数据。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


