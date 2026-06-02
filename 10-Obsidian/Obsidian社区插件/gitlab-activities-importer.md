---
uid: 1780392511132001
title: 'Obsidian 插件：GitLab Activities Importer'
tags: ['第三方工具集成', '数据处理', '效率工具', 'obsidian插件']
description: '它能把GitLab的日常活动导入到当前的每日笔记里。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：GitLab Activities Importer

> [!Note] 插件名片
> - 插件名称：GitLab Activities Importer
> - 插件作者：anindyaspaul
> - 插件说明：它能把GitLab的日常活动导入到当前的每日笔记里。
> - 插件分类：['第三方工具集成', '数据处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/anindyaspaul/obsidian-gitlab-activities-importer)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?gitlab-activities-importer)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/anindyaspaul/obsidian-gitlab-activities-importer/master/README.md)



## 概述

### 主要功能
借助 GitLab REST API，将 GitLab 日常活动导入当前打开的每日笔记中，可导入笔记日期当天的活动。

### 适用场景
适用于使用 GitLab 进行项目管理，且习惯用 Obsidian 记录每日工作的用户，方便将 GitLab 活动整合到每日笔记里。

### 核心特色
- 支持 GitLab.com 和自建 GitLab 实例。
- 每次运行会替换笔记中指定部分，操作幂等。
- 导入时若有推送信息，会包含分支、提交数量和最新提交标题等元数据。

### 使用建议
- 每日笔记文件名需包含 `YYYY-MM-DD` 或 `YYYYMMDD` 格式的日期。
- 准备好 GitLab 个人访问令牌（最小范围为 `read_user`）。
- 按步骤安装依赖、构建插件，在 Obsidian 中配置 GitLab 基础 URL、访问令牌等信息。
- 打开要导入的日期的每日笔记，通过命令面板执行导入操作。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


