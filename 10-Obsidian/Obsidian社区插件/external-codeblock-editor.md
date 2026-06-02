---
uid: 1780392511092000
title: 'Obsidian 插件：External Codeblock Editor'
tags: ['编辑工具', '第三方工具集成', '编程与脚本', '效率工具', 'obsidian插件']
description: '这个插件还没有经过Obsidian官方人员的手动审核。你可以用外部编辑器编辑Markdown文档的代码块，这样就能享受你喜欢的编辑器（比如Neovim、VSCode等）的自动补全、缩进以及语言服务器协议（LSP）功能啦。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：External Codeblock Editor

> [!Note] 插件名片
> - 插件名称：External Codeblock Editor
> - 插件作者：glebglazov
> - 插件说明：这个插件还没有经过Obsidian官方人员的手动审核。你可以用外部编辑器编辑Markdown文档的代码块，这样就能享受你喜欢的编辑器（比如Neovim、VSCode等）的自动补全、缩进以及语言服务器协议（LSP）功能啦。
> - 插件分类：['编辑工具', '第三方工具集成', '编程与脚本', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/glebglazov/obsidian-external-codeblock-editor)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?external-codeblock-editor)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/glebglazov/obsidian-external-codeblock-editor/master/README.md)



## 概述

### 插件名称
External Codeblock Editor

### 主要功能
允许用户将Markdown文档中的代码块发送到外部编辑器（如Neovim、VSCode）进行编辑，支持30+种编程语言，编辑完成后自动同步回Obsidian笔记。

### 适用场景
当需要编写多行代码，且希望利用外部编辑器的自动补全、自动缩进、LSP等功能时使用。

### 核心特色
- 集成外部编辑器，可在偏好的编辑器中编辑代码块。
- 自动检测代码块语言，创建合适扩展名的临时文件。
- 实现无缝同步，外部编辑器的更改自动同步回Obsidian。
- 终端命令可配置，能匹配个人设置。

### 使用建议
手动安装时，下载文件放至指定目录后重启Obsidian并在社区插件中启用；开发安装则需克隆仓库、安装依赖、编译插件后启用。使用时，将光标置于代码块内，通过命令面板选择“Edit codeblock in external editor”，在外部编辑器编辑保存后，更改会自动同步。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


