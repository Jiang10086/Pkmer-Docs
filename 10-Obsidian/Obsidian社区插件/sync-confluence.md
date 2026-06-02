---
uid: 1780392512094000
title: 'Obsidian 插件：Sync Confluence'
tags: ['第三方工具集成', '自动化与AI', '发布工具', '效率工具', 'obsidian插件']
description: '它可以按照设定的时间安排将笔记同步到Confluence页面，同步规则由笔记前置元数据里的confluence_url字段来约束。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Sync Confluence

> [!Note] 插件名片
> - 插件名称：Sync Confluence
> - 插件作者：duanzhang
> - 插件说明：它可以按照设定的时间安排将笔记同步到Confluence页面，同步规则由笔记前置元数据里的confluence_url字段来约束。
> - 插件分类：['第三方工具集成', '自动化与AI', '发布工具', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/dzplus/obsidian-sync-confluence)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?sync-confluence)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/dzplus/obsidian-sync-confluence/master/README.md)



## 概述

### 主要功能
Sync Confluence 插件可按计划将 Obsidian 笔记同步到 Confluence 页面，通过笔记前置元数据中的 `confluence_url` 绑定对应页面。

### 适用场景
适用于需要将 Obsidian 笔记定期同步到 Confluence 平台的用户，无论是使用 Atlassian Cloud 还是本地部署的 Confluence Server / Data Center 均可。

### 核心特色
- 基于前置元数据绑定，无需额外配置。
- 采用内容哈希跳过机制，避免重复推送未修改笔记。
- 支持上传本地附件。
- 可自动创建子页面。
- 能对 Mermaid 和可选的 PlantUML 代码块进行预渲染。
- 提供多种触发同步方式。

### 使用建议
1. 在笔记前置元数据中添加 `confluence_url`。
2. 在插件设置里填写基础 URL、认证凭证和 API 令牌。
3. 可通过多种方式触发同步，也可设置定时同步。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


