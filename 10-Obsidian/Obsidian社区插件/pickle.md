---
uid: 1780392511992000
title: 'Obsidian 插件：Pickle'
tags: ['任务管理', '数据处理', '效率工具', '自动化与AI', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它是一个本地优先、基于文件的代理收件箱，用于处理输入的请求和回复。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Pickle

> [!Note] 插件名片
> - 插件名称：Pickle
> - 插件作者：callumalpass
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它是一个本地优先、基于文件的代理收件箱，用于处理输入的请求和回复。
> - 插件分类：['任务管理', '数据处理', '效率工具', '自动化与AI', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/callumalpass/pickle-obsidian)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?pickle)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/callumalpass/pickle-obsidian/master/README.md)



## 概述

### 主要功能
Pickle是一个本地优先、基于文件的Obsidian收件箱，用于处理类型化的代理请求和结构化的人类响应。它能将普通Markdown文件夹转变为轻量级收件箱，代理在`_pickle/requests/`下创建请求文件，用户在Obsidian Bases中审核请求，通过模式驱动的模态框作出响应，响应文件会写入`_pickle/responses/`，同时保留请求和响应文件作为审计跟踪。

### 适用场景
适用于本地自动化中的人工检查点，当代理或定时任务在改变状态、发表评论、关闭问题、部署内容或应用生成计划前需要人工决策时使用。

### 核心特色
维护默认的`_pickle`集合布局，创建多种类型文件和默认的`Pickle Requests.base`文件，添加自定义Bases视图，可直接从基础视图或活动请求文件打开响应模态框，支持嵌套响应模式和响应附件，根据响应链接推导请求状态。

### 使用建议
下游自动化应读取响应文件并复制决策到自身工作流状态，同时保持Pickle文件完整。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


