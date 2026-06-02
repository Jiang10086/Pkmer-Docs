---
uid: 1780392511285001
title: 'Obsidian 插件：Mockup Viewer'
tags: ['界面优化', '效率工具', '第三方工具集成', '编程与脚本', 'obsidian插件']
description: '你可以在仓库里预览HTML模型，插件的CSS样式会被注入到一个独立的iframe中，方便在设计阶段进行UI原型设计。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Mockup Viewer

> [!Note] 插件名片
> - 插件名称：Mockup Viewer
> - 插件作者：Russell
> - 插件说明：你可以在仓库里预览HTML模型，插件的CSS样式会被注入到一个独立的iframe中，方便在设计阶段进行UI原型设计。
> - 插件分类：['界面优化', '效率工具', '第三方工具集成', '编程与脚本', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/twrusstw/mockup-viewer)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?mockup-viewer)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/twrusstw/mockup-viewer/master/README.md)



## 概述

### Mockup Viewer插件总结
1. **主要功能**：用于预览Vault中的HTML原型，将Obsidian的`app.css`、当前主题及插件CSS注入隔离的iframe中进行渲染，实现设计时UI原型制作。
2. **适用场景**：适用于插件开发者在设计阶段进行UI原型迭代，如尝试不同模态布局、测试移动UI、查看设计师或AI提供的HTML原型等。
3. **核心特色**：
    - 即时预览：将HTML文件保存到`Mockup/`目录，预览立即出现。
    - 隔离渲染：iframe边界防止特定类影响Obsidian界面。
    - 视觉一致：注入Obsidian和插件的样式，视觉效果与真实插件几乎一致。
    - 热更新：编辑自动热更新，切换主题也会重新渲染。
4. **使用建议**：由于该插件会执行HTML中的`<script>`，仅打开信任的原型文件。目前未在Obsidian社区插件列表中，可通过BRAT或手动方式安装。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


