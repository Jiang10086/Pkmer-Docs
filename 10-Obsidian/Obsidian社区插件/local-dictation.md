---
uid: 1780392511242001
title: 'Obsidian 插件：Local Dictation'
tags: ['自动化与AI', '文字处理', '第三方工具集成', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核哦。你可以用Whisper或者Cohere Transcribe来语音记录笔记，再用本地的Ollama模型进行整理。这是专为Obsidian打造的私密的、设备端语音转文字工具。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Local Dictation

> [!Note] 插件名片
> - 插件名称：Local Dictation
> - 插件作者：Alexander Brittain
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核哦。你可以用Whisper或者Cohere Transcribe来语音记录笔记，再用本地的Ollama模型进行整理。这是专为Obsidian打造的私密的、设备端语音转文字工具。
> - 插件分类：['自动化与AI', '文字处理', '第三方工具集成', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/brittain9/local-dictation-obsidian-plugin)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?local-dictation)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/brittain9/local-dictation-obsidian-plugin/master/README.md)



## 概述

### Local Dictation插件总结
1. **主要功能**：为Obsidian提供本地语音转文字功能，支持使用Whisper或Cohere Transcribe进行语音记录，还能用本地Ollama模型清理文本。
2. **适用场景**：适用于需要快速记录笔记，且注重隐私，希望在本地完成语音转录的场景。
3. **核心特色**：
    - 采用排名靠前的Cohere Transcribe和成熟的Whisper转录引擎。
    - 具备Silero v6 VAD实时语音边界检测。
    - 可选择用本地LLM清理文本。
    - 支持一键管理模型。
    - 有硬件加速，如macOS的Metal、Linux/Windows的CUDA。
    - 隐私性强，转录在本地完成，无需云服务、遥测和账户，仅模型下载需网络。
4. **使用建议**：若设备有Turing及以上NVIDIA GPU，可开启CUDA加速提升转录速度；CPU也能使用，无额外依赖；Flatpak安装的Linux系统需进行GPU设置；Windows系统使用CUDA需进行相应设置。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


