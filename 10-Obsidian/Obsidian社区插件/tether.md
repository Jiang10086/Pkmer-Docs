---
uid: 1780392512131000
title: 'Obsidian 插件：Tether'
tags: ['第三方工具集成', '备份与恢复', '效率工具', 'obsidian插件']
description: '这个插件还未经Obsidian官方人员手动审核。你可以用自己的谷歌云凭证将仓库与谷歌云端硬盘进行同步。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Tether

> [!Note] 插件名片
> - 插件名称：Tether
> - 插件作者：llewellyn500
> - 插件说明：这个插件还未经Obsidian官方人员手动审核。你可以用自己的谷歌云凭证将仓库与谷歌云端硬盘进行同步。
> - 插件分类：['第三方工具集成', '备份与恢复', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/llewellyn500/obsidian-tether)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?tether)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/llewellyn500/obsidian-tether/master/README.md)



## 概述

### Tether插件总结
1. **主要功能**：这是一款用于Obsidian的Google Drive同步插件，可借助用户自己的Google Cloud项目和账户，实现整个Obsidian库（包括笔记、附件、嵌套文件夹和`.obsidian`文件夹）与Google Drive的同步。
2. **适用场景**：适用于希望在桌面和移动设备上自主管理Obsidian库同步，且不想依赖共享凭证的用户。
3. **核心特色**：
    - 全库同步，涵盖各类文件和文件夹。
    - 支持定向同步，可分别执行拉取和推送操作。
    - 使用用户自己的Google Cloud OAuth客户端，保障隐私。
    - 对移动设备友好，利用Obsidian的`requestUrl` API进行认证和请求。
    - 内置设置流程，包含引导、登录、文件夹选择和同步状态侧边栏。
    - 支持自动同步，启动时拉取，按设定间隔推送。
4. **使用建议**：先创建自己的Google Cloud OAuth应用，利用Tether的托管设置页面配置相关信息，将客户端ID和密钥粘贴到Tether中，在Obsidian内用Google账户登录，选择Google Drive文件夹，即可实现同步。可通过社区插件或手动方式安装。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


