---
uid: 1780392511233000
title: 'Obsidian 插件：LinkVault'
tags: ['自动化与AI', '第三方工具集成', '模板与链接处理', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。可以用人工智能把链接保存并分类到你的知识库中。支持Claude、Ollama和OpenRouter。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：LinkVault

> [!Note] 插件名片
> - 插件名称：LinkVault
> - 插件作者：calghar
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。可以用人工智能把链接保存并分类到你的知识库中。支持Claude、Ollama和OpenRouter。
> - 插件分类：['自动化与AI', '第三方工具集成', '模板与链接处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/calghar/LinkVault)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?linkvault)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/calghar/LinkVault/master/README.md)



## 概述

### LinkVault插件总结
1. **主要功能**：将网页剪辑的链接保存到知识库里。通过AI提取标题和摘要，选择合适的知识库文件和章节，插入表格行。
2. **适用场景**：适用于需要整理网页链接，将其有序存于知识体系中的场景，如知识管理、信息收集等。
3. **核心特色**：支持Anthropic（Claude）、Ollama（本地/免费）和OpenRouter；采用三层模糊匹配，确保链接有处可放；若现有文件不匹配内容，可创建新的知识库文件；所有提示可通过模板变量自定义；能对瞬时错误（如速率限制、5xx错误）进行指数退避重试；有调试模式可检查大语言模型原始响应。
4. **使用建议**：先通过Obsidian Web Clipper等方式将网页剪辑到收件箱文件夹，打开剪辑笔记后，从命令面板运行“LinkVault: Process Link to KB”。推荐从社区插件安装，依次点击“设置→社区插件→浏览”，搜索“LinkVault”进行安装和启用。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


