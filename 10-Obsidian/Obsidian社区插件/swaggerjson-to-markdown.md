---
uid: 1780392512093001
title: 'Obsidian 插件：Swagger JSON to Markdown'
tags: ['数据处理', '第三方工具集成', '编辑工具', '文字处理', '发布工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员手动审核哦。它能把Swagger/OpenAPI的JSON文件转换成Swagger风格的Markdown文件。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Swagger JSON to Markdown

> [!Note] 插件名片
> - 插件名称：Swagger JSON to Markdown
> - 插件作者：Oscar Gonzalez Tur
> - 插件说明：这个插件还没经过Obsidian官方人员手动审核哦。它能把Swagger/OpenAPI的JSON文件转换成Swagger风格的Markdown文件。
> - 插件分类：['数据处理', '第三方工具集成', '编辑工具', '文字处理', '发布工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/krontur/obsidian-swaggerjson-to-markdown)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?swaggerjson-to-markdown)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/krontur/obsidian-swaggerjson-to-markdown/master/README.md)



## 概述

### 插件名称
Swagger JSON to Markdown

### 主要功能
将 Swagger 2.0 和 OpenAPI 3.x 的 JSON 文件转换为 Swagger 风格的静态 Markdown 文件。

### 适用场景
适用于需要在 Obsidian 笔记中生成接近 Swagger UI 效果的 API 文档，以及将文档导出为 PDF 的场景。

### 核心特色
1. 支持多种转换模式，如完整文档的 `full` 模式和可复用片段的 `fragment` 模式。
2. 可通过上下文菜单或命令进行转换，转换前有选项模态框。
3. 能按 `tags` 分组操作，可根据 `tag`、`operationId` 等过滤输出。
4. 采用真实 Markdown 标题，支持 Obsidian 大纲和 PDF 书签，也可禁用使用 HTML 标题块。
5. 生成 API 各部分详细信息，处理 HTML 描述字段，渲染示例，解析 `$ref` 并报告引用警告。

### 使用建议
手动安装时，将 `main.js`、`manifest.json`、`styles.css` 复制到 `VaultFolder/.obsidian/plugins/swaggerjson-to-markdown/` 目录，然后启用插件即可使用。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


