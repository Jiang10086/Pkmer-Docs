---
uid: 1780392511144001
title: 'Obsidian 插件：GTC Sync'
tags: ['第三方工具集成', '效率工具', '自动化与AI', 'obsidian插件']
description: '正在与GTC同步笔记。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：GTC Sync

> [!Note] 插件名片
> - 插件名称：GTC Sync
> - 插件作者：Etudes Informatiques et Services
> - 插件说明：正在与GTC同步笔记。
> - 插件分类：['第三方工具集成', '效率工具', '自动化与AI', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/etudes-informatiques-et-services35/gtc-sync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?gtc-sync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/etudes-informatiques-et-services35/gtc-sync/master/README.md)



## 概述

### 主要功能
GTC Sync 是一款用于 Obsidian 的插件，借助 WebSocket 实现 Obsidian 笔记与 GTC（Etudes Informatiques et Services 开发的 ERP）的双向同步。仅 YAML 前置元数据中有 `IdNote` 字段的笔记参与同步。

### 适用场景
适用于需要在 Obsidian 与 GTC 之间同步笔记的场景，如团队协作中在 ERP 系统与笔记软件间共享信息。

### 核心特色
 - 双向同步：本地笔记修改会推送到服务器，服务器也能远程控制 Obsidian 库。
 - 精准触发：仅活动文件修改或重命名时触发同步，且 Obsidian Sync 来自其他设备的更改不传播。
 - 关联同步：重命名文件时，引用该文件的笔记也会同步更新。
 - 丰富指令：服务器可发送多种 JSON 命令对笔记进行操作。

### 使用建议
使用前确保笔记 YAML 前置元数据中有 `IdNote` 字段，配置好认证 token。修改笔记后等待 1 秒，插件会自动同步。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


