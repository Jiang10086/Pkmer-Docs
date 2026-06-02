---
uid: 2026060213561466
title: 'Obsidian 插件：Redirect HTTPS to Local'
tags: ['第三方工具集成', '模板与链接处理', '效率工具', 'obsidian插件']
description: '把重定向的HTTPS链接转换为本地重定向URL，以便与外部平台更好地兼容。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Redirect HTTPS to Local

> [!Note] 插件名片
> - 插件名称：Redirect HTTPS to Local
> - 插件作者：iamjjanga-ouo
> - 插件说明：把重定向的HTTPS链接转换为本地重定向URL，以便与外部平台更好地兼容。
> - 插件分类：['第三方工具集成', '模板与链接处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/iamjjanga-ouo/obsidian-link)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?redirect-link-https-to-local)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/iamjjanga-ouo/obsidian-link/master/README.md)

![Redirect HTTPS to Local](https://cdn.pkmer.cn/covers/redirect-link-https-to-local_internal_0.png!pkmer)

## 概述

### 主要功能
将 Obsidian 原生的 `obsidian://` 链接转换为 HTTPS 重定向 URL，方便在外部平台分享 Obsidian 笔记链接。具体流程为：从当前活动文件生成 `obsidian://` 链接，通过可配置的重定向服务将其转换为 HTTPS 链接，并复制到剪贴板。

### 适用场景
适用于在 Slack、Notion、网络论坛等外部平台分享 Obsidian 笔记链接，解决这些平台不识别 `obsidian://` 链接的问题。

### 核心特色
- 一键生成链接：通过命令面板可快速复制可分享链接。
- 可自定义重定向 URL：能配置自己的域名。
- 跨平台支持：在桌面和移动设备上均可使用。
- 正确的 URL 编码：处理文件名和库名中的特殊字符。
- 可视化反馈：复制成功有提示。

### 使用建议
若要复制当前文件链接，打开笔记后通过命令面板运行“Obsidian Link: Copy Link”；若要配置重定向服务，可前往设置操作。安装可通过社区插件（即将支持）或手动下载文件完成。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


