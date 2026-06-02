---
uid: 1780392512137002
title: 'Obsidian 插件：Thoth'
tags: ['第三方工具集成', '备份与恢复', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能通过兼容S3的对象存储实现轻量级仓库同步。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Thoth

> [!Note] 插件名片
> - 插件名称：Thoth
> - 插件作者：Mac Ahmed
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能通过兼容S3的对象存储实现轻量级仓库同步。
> - 插件分类：['第三方工具集成', '备份与恢复', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/macahmed/obsidian-thoth)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?thoth-sync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/macahmed/obsidian-thoth/master/README.md)



## 概述

### Thoth插件总结
1. **主要功能**：借助S3兼容对象存储（如Cloudflare R2、AWS S3等）实现Obsidian库的轻量级同步，支持三方同步、并行传输、冲突处理等，可在移动设备使用。
2. **适用场景**：适用于需要跨设备同步Obsidian笔记库的场景，无论是电脑还是iOS、安卓移动设备均可使用。
3. **核心特色**：通过本地同步历史检测离线删除、修改和冲突；支持20个并发上传/下载实现快速初始同步；缓存文件哈希，快速启动；模块化存储后端，易于添加新后端；冲突处理时保留两个版本。
4. **使用建议**：先创建S3兼容存储桶，在Obsidian中安装Thoth插件，在设置中输入端点、访问密钥等信息并测试连接，同步会自动开始。可使用“Thoth: Push changes now”和“Thoth: Pull changes now”命令强制推送或拉取更改。还可通过显示二维码、复制编码设置字符串等方式在设备间转移设置。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


