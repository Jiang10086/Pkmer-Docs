---
uid: 1780392511131001
title: 'Obsidian 插件：GitHub PR Autocomplete'
tags: ['第三方工具集成', '自动化与AI', '效率工具', '编辑工具', 'obsidian插件']
description: '它可以对GitHub上的问题和拉取请求给出建议并自动补全。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：GitHub PR Autocomplete

> [!Note] 插件名片
> - 插件名称：GitHub PR Autocomplete
> - 插件作者：Andrew Mao
> - 插件说明：它可以对GitHub上的问题和拉取请求给出建议并自动补全。
> - 插件分类：['第三方工具集成', '自动化与AI', '效率工具', '编辑工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/andrewyx/Github-PR-Autocomplete)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?github-pr-autocomplete)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/andrewyx/Github-PR-Autocomplete/master/README.md)



## 概述

### 插件名称
GitHub PR Autocomplete

### 主要功能
在Obsidian编辑器中，当输入触发字符（默认`@`）时，可自动搜索并提示GitHub仓库的开放问题和拉取请求，支持直接将其链接插入笔记。

### 适用场景
适用于在Obsidian中记录与GitHub项目相关内容的场景，方便引用项目中的问题和PR。

### 核心特色
1. 支持搜索开放问题和PR，便于快速引用。
2. 支持私有仓库，通过链接GitHub个人访问令牌（PAT）访问。
3. 采用Obsidian的`SecretStorage` API安全存储令牌。
4. 可管理多个命名令牌，并在设置中显示其有效性状态。
5. 触发字符可自定义，避免与其他插件冲突。

### 使用建议
1. 在插件设置中按`owner/repo`格式配置GitHub仓库。
2. 建议创建具有`repo`权限的GitHub个人访问令牌，并在设置中添加，插件会验证其有效性。
3. 在Markdown文件中输入`@`及搜索词或问题编号，从列表中选择项目插入Markdown链接。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


