---
uid: 1780392512142000
title: 'Obsidian 插件：TikToken Tokenizer'
tags: ['编辑工具', '导航与状态栏', '数据处理', '效率工具', 'obsidian插件']
description: '它会使用TikToken在状态栏显示当前激活笔记的令牌数量。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：TikToken Tokenizer

> [!Note] 插件名片
> - 插件名称：TikToken Tokenizer
> - 插件作者：s3ga1ov
> - 插件说明：它会使用TikToken在状态栏显示当前激活笔记的令牌数量。
> - 插件分类：['编辑工具', '导航与状态栏', '数据处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/s3ga1ov/obsidian-tiktoken-tokenizer)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?tiktoken-tokenizer)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/s3ga1ov/obsidian-tiktoken-tokenizer/master/README.md)

![TikToken Tokenizer](https://cdn.pkmer.cn/covers/tiktoken-tokenizer_internal_0.png!pkmer)

## 概述

### 主要功能
在Obsidian状态栏显示当前活动笔记的令牌数量，使用js - tiktoken库进行计算。

### 适用场景
适用于使用Obsidian记录内容，且需要了解笔记令牌数量的场景，特别是与OpenAI或Claude等大模型交互时，可帮助用户预估使用成本和判断上下文长度。

### 核心特色
- 提供两种令牌计算模式：“GPT - 4o / GPT - 5 (exact)”使用`o200k_base`编码，计数精确；“Claude (approximate)”为Claude提供近似计数，采用`cl100k_base`编码并加15%安全余量。
- 计算全在JavaScript中进行，无WebAssembly或网络调用，支持桌面和移动设备。
- 有150ms防抖机制，保证输入时Obsidian响应流畅。

### 使用建议
- 若使用GPT - 4o或GPT - 5，选择“GPT - 4o / GPT - 5 (exact)”模式获取精确计数。
- 若使用Claude，可选用“Claude (approximate)”模式大致估算令牌数量。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


