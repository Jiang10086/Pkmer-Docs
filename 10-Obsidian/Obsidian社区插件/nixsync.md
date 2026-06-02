---
uid: 1780392511306001
title: 'Obsidian 插件：Nixsync'
tags: ['第三方工具集成', '备份与恢复', '编程与脚本', '效率工具', 'obsidian插件']
description: '可以将仓库设置和插件以Nix格式导出和导入。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Nixsync

> [!Note] 插件名片
> - 插件名称：Nixsync
> - 插件作者：rowmayne
> - 插件说明：可以将仓库设置和插件以Nix格式导出和导入。
> - 插件分类：['第三方工具集成', '备份与恢复', '编程与脚本', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/rowmayne/nixsync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?nixsync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/rowmayne/nixsync/master/README.md)



## 概述

### Nixsync插件总结
1. **主要功能**：可将Obsidian的保险库设置和插件以Nix格式导出为单个`.nix`文件，也能从`.nix`文件导入设置并写入`.obsidian/`目录。
2. **适用场景**：适用于需要备份Obsidian设置和插件配置，或在不同设备间同步设置的用户。
3. **核心特色**：支持灵活配置导出内容，可选择导出应用配置、外观、热键等多项设置；能去除临时工作区字段，避免导出特定于机器的信息；还可生成NixOS集成文件。
4. **使用建议**：在命令面板中使用“Export settings as Nix file”导出设置到保险库根目录，使用“Import settings from Nix file”导入设置，导入后需重新加载Obsidian。若使用NixOS，可启用“Generate NixOS integration files”选项，通过执行`obsidian-activate.sh`脚本恢复设置。注意，插件JS文件不会包含在导出内容中，Obsidian仍需自行下载插件。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


