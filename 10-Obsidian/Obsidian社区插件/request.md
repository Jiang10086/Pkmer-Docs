---
uid: 2026060213561483
title: 'Obsidian 插件：Request'
tags: ['编程与脚本', '第三方工具集成', '效率工具', '数据处理', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。你可以通过代码块发起网络请求，然后在笔记里使用请求结果。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Request

> [!Note] 插件名片
> - 插件名称：Request
> - 插件作者：joepetrakovich
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。你可以通过代码块发起网络请求，然后在笔记里使用请求结果。
> - 插件分类：['编程与脚本', '第三方工具集成', '效率工具', '数据处理', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/joepetrakovich/obsidian-request)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?request)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/joepetrakovich/obsidian-request/master/README.md)



## 概述

### 插件名称
Request

### 主要功能
该插件可让用户在Obsidian笔记中添加网络请求，通过代码块进行配置并使用请求结果。

### 适用场景
适用于需要在笔记中嵌入网络数据的场景，如获取API数据展示在笔记里。

### 核心特色
1. 采用简单且容错性高的Markdown代码块进行配置。
2. 支持使用JSONPath精准定位响应中的值。
3. 借助Handlebars进行结果模板化。
4. 具备请求链功能，可利用前一个请求的响应数据发起新请求。

### 使用建议
在配置代码块时，`url` 字段为必填项，指定请求的HTTP/HTTPS端点；其他字段如 `method`、`headers` 等按需填写。可参考 [完整文档](https://joepetrakovich.github.io/obsidian-request/) 进行更深入的配置和使用。示例代码可帮助快速上手，如获取NASA每日天文图片并展示在笔记中。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


