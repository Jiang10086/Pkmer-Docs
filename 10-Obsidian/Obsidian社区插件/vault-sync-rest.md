---
uid: 1780392512188001
title: 'Obsidian 插件：Vault Sync (REST)'
tags: ['第三方工具集成', '备份与恢复', '移动端优化', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核哈。它能通过REST API和GitHub仓库进行双向同步呢。在iOS系统上，不管仓库大小，包括里面有图片啥的，它都能正常工作，不像那些基于git协议的插件，会因为WebView内存限制而崩溃。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Vault Sync (REST)

> [!Note] 插件名片
> - 插件名称：Vault Sync (REST)
> - 插件作者：andrewboldi
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核哈。它能通过REST API和GitHub仓库进行双向同步呢。在iOS系统上，不管仓库大小，包括里面有图片啥的，它都能正常工作，不像那些基于git协议的插件，会因为WebView内存限制而崩溃。
> - 插件分类：['第三方工具集成', '备份与恢复', '移动端优化', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/andrewboldi/obsidian-vault-sync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?vault-sync-rest)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/andrewboldi/obsidian-vault-sync/master/README.md)



## 概述

### 1. 插件主要功能
Vault Sync (REST) 是一款能实现 Obsidian 库与 GitHub 仓库双向同步的插件。支持初始下载（Seed）、拉取（Pull）、推送（Push）操作，还具备自动同步功能，可按设定时间间隔执行拉取和推送。

### 2. 适用场景
适用于在 iOS 设备上使用 Obsidian 的用户，尤其是拥有包含图片等大文件的库，使用传统基于 git 协议的插件会因 WebView 内存限制而崩溃的情况。

### 3. 核心特色
不使用 git 的有线协议，而是通过 GitHub 的 REST API 进行同步，每次仅获取一个文件，内存使用由最大单个文件决定，而非整个库的大小，避免了 iOS 上的内存问题，能稳定同步任意大小的库。

### 4. 使用建议
若在 iOS 设备上使用 Obsidian 且遇到基于 git 协议插件的内存问题，可尝试使用此插件。设置好自动同步的时间间隔，让其自动完成同步，减少手动操作。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


