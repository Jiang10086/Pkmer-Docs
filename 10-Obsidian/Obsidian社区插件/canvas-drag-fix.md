---
uid: 1780392510990000
title: 'Obsidian 插件：Canvas Drag Fix'
tags: ['界面优化', '效率工具', '编辑工具', 'obsidian插件']
description: '这个插件还没有经过Obsidian工作人员的人工审核。它修复了在Linux系统上，当Chromium误将鼠标识别为笔设备时，Canvas元素的拖放问题。这种鼠标误识别情况在VMware/VirtualBox虚拟机、ChromeOS Crostini环境以及一些Wayland配置中很常见。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Canvas Drag Fix

> [!Note] 插件名片
> - 插件名称：Canvas Drag Fix
> - 插件作者：an2io
> - 插件说明：这个插件还没有经过Obsidian工作人员的人工审核。它修复了在Linux系统上，当Chromium误将鼠标识别为笔设备时，Canvas元素的拖放问题。这种鼠标误识别情况在VMware/VirtualBox虚拟机、ChromeOS Crostini环境以及一些Wayland配置中很常见。
> - 插件分类：['界面优化', '效率工具', '编辑工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/an2io/obsidian-canvas-drag-fix)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?canvas-drag-fix)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/an2io/obsidian-canvas-drag-fix/master/README.md)



## 概述

### Canvas Drag Fix 插件总结
1. **主要功能**：修复在 Linux 系统下，当 Chromium/Electron 将普通鼠标误分类为笔设备时，Obsidian 画布的拖放问题。
2. **适用场景**：适用于 VMware、VirtualBox 中的 Linux 虚拟机，ChromeOS Crostini Linux 容器，部分 Wayland 配置以及一些具有特殊 XInput2 设备拓扑的裸机 Linux 系统。
3. **核心特色**：精准针对鼠标被误识别导致的画布拖放问题，不影响点击、双击、键盘箭头移动和角调整等操作。
4. **使用建议**：若遇到画布卡片无法点击拖动、无法从侧面调整卡片大小、无法点击拖动选择画布区域、无法从卡片手柄绘制箭头连接等问题，可通过打开 Obsidian 开发者工具（`Ctrl + Shift + I`），在控制台运行特定代码验证是否为该问题。若日志显示普通鼠标的 `pointerType` 为 `pen`，使用此插件即可修复。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


