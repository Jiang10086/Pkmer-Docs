---
uid: 2026060213561318
title: 'Obsidian 插件：Copy Text Protocol'
tags: ['模板与链接处理', '编辑工具', '效率工具', '自定义命令', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。用它能创建可点击的链接，能让你瞬间把文本片段、命令或者模板复制到剪贴板，还有实时悬停预览功能呢。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Copy Text Protocol

> [!Note] 插件名片
> - 插件名称：Copy Text Protocol
> - 插件作者：jldiaz
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。用它能创建可点击的链接，能让你瞬间把文本片段、命令或者模板复制到剪贴板，还有实时悬停预览功能呢。
> - 插件分类：['模板与链接处理', '编辑工具', '效率工具', '自定义命令', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/jldiaz/copy-protocol-plugin)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?copy-text-protocol)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/jldiaz/copy-protocol-plugin/master/README.md)

![Copy Text Protocol](https://cdn.pkmer.cn/covers/copy-text-protocol_internal_0.gif!pkmer)

## 概述

### 插件名称
Copy Text Protocol

### 主要功能
创建可点击的链接，点击后能将文本片段、命令或模板自动复制到剪贴板，且有实时悬停预览。

### 适用场景
- 制作含命令、密码或模板的“速查表”笔记，点击链接即可复制粘贴。
- 收集代码片段，方便粘贴到终端。
- 存储常用文本，如邮件签名、样板文本、地址等，可从任意笔记访问。
- 生成查询字符串，粘贴到其他应用。

### 核心特色
注册自定义 `obsidian://copy` 协议，点击链接时，URL 中的文本会无声复制到剪贴板，仅显示小确认通知，无弹窗和外部应用干扰。

### 使用建议
- 手动创建链接：按 `[Click to copy](obsidian://copy?text=Your-text-here)` 格式编写，含空格的文本需用尖括号包裹。
- 用快捷键创建链接：使用“Copy Protocol: Paste clipboard as copy-protocol link”命令，可自动读取剪贴板内容并插入 Markdown 链接，还能为该命令设置快捷键。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


