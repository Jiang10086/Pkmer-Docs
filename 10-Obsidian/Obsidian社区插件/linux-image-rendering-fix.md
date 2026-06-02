---
uid: 1780392511233001
title: 'Obsidian 插件：Linux Image Rendering Fix'
tags: ['图片与PDF', '界面优化', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能修复Linux系统上的图片渲染问题，确保图片在Ubuntu及其他Linux发行版上正常显示。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Linux Image Rendering Fix

> [!Note] 插件名片
> - 插件名称：Linux Image Rendering Fix
> - 插件作者：evgene-kopylov
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能修复Linux系统上的图片渲染问题，确保图片在Ubuntu及其他Linux发行版上正常显示。
> - 插件分类：['图片与PDF', '界面优化', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/evgene-kopylov/linux-image-rendering-fix)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?linux-image-rendering-fix)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/evgene-kopylov/linux-image-rendering-fix/master/README.md)



## 概述

### 主要功能
该插件用于修复 Linux（特别是 Ubuntu 及其衍生系统）上 Obsidian 的图片渲染问题，确保本地图片能正确显示。

### 适用场景
适用于在 Linux 系统（如 Ubuntu、Pop!_OS、Linux Mint 等）使用 Obsidian 的用户，尤其是遇到本地图片无法显示问题的用户，涵盖 Snap、Flatpak、DEB 等包，ARM 系统也适用。

### 核心特色
- 绕过有问题的 `app://` 协议加载图片。
- 支持多种图片格式，包括 png、jpg、gif、webp、svg、bmp。
- 打开页面时自动处理图片。

### 使用建议
- 开发时推荐使用符号链接方式安装：`ln -s "$PWD" /home/death/Documents/TEST-VAULT-3/.obsidian/plugins/linux-image-rendering-fix` 。
- 也可将 `main.js`、`manifest.json`、`styles.css` 复制到插件目录 `<Vault>/.obsidian/plugins/linux-image-rendering-fix/` 。若遇到问题或有功能需求，可前往 https://github.com/Evgene-Kopylov/linux-image-rendering-fix/issues 反馈。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


