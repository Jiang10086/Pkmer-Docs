---
uid: 1780392512212001
title: 'Obsidian 插件：Webhooks Server'
tags: ['第三方工具集成', '自动化与AI', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。你可以通过一个自建服务器接收来自外部服务的网络钩子（webhook），并在你的仓库里实时创建笔记。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Webhooks Server

> [!Note] 插件名片
> - 插件名称：Webhooks Server
> - 插件作者：khabaroff-studio
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。你可以通过一个自建服务器接收来自外部服务的网络钩子（webhook），并在你的仓库里实时创建笔记。
> - 插件分类：['第三方工具集成', '自动化与AI', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/khabaroff-studio/obsidian-webhooks-server)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?webhooks-server)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/khabaroff-studio/obsidian-webhooks-server/master/README.md)

![Webhooks Server](https://cdn.pkmer.cn/covers/webhooks-server_internal_0.png!pkmer)

## 概述

### 主要功能
Webhooks Server 插件可接收来自 Zapier、Make 等外部服务的 Webhook，通过自托管服务器将外部事件转化为 Obsidian 保险库中的笔记，支持实时推送。

### 适用场景
适用于需要将外部服务事件快速记录到 Obsidian 中的场景，如自动化工作流、AI 交互等。

### 核心特色
- **实时交付**：采用 Server-Sent Events 技术，有轮询备用方案。
- **精确一次保证**：ACK 系统防止重复记录。
- **数据加密**：使用 AES - 256 - GCM 加密所有事件数据。
- **无密码认证**：通过邮件魔法链接认证。
- **自托管**：完全掌控数据，无第三方介入。
- **生产就绪**：具备速率限制、自动清理、健康检查等功能。

### 使用建议
先克隆项目，配置 `.env` 文件，用 Docker 启动服务。在浏览器打开 `http://localhost:8081` 注册，点击邮件中的魔法链接。安装插件后，在设置中输入客户端密钥和服务器 URL。使用 `curl` 命令发送第一个 Webhook 进行测试。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


