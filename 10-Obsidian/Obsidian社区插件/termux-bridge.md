---
uid: 1780392512129002
title: 'Obsidian 插件：Termux Bridge'
tags: ['第三方工具集成', '编程与脚本', '自定义命令', '效率工具', 'obsidian插件']
description: '可以通过本地HTTP桥直接执行Termux命令。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Termux Bridge

> [!Note] 插件名片
> - 插件名称：Termux Bridge
> - 插件作者：abduznik
> - 插件说明：可以通过本地HTTP桥直接执行Termux命令。
> - 插件分类：['第三方工具集成', '编程与脚本', '自定义命令', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/abduznik/obsidian-shell-termux)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?termux-bridge)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/abduznik/obsidian-shell-termux/master/README.md)



## 概述

### Termux Bridge插件总结
1. **主要功能**：通过本地HTTP桥接将Obsidian与Termux连接，绕过安卓Intent限制，可直接在Obsidian中运行安卓设备的shell命令。
2. **适用场景**：适用于需要在Obsidian中便捷执行安卓设备shell命令的场景，如开发者进行代码操作、自动化脚本执行等。
3. **核心特色**：
    - 可靠：使用标准TCP/IP网络（本地主机）进行稳定通信。
    - 静默：在后台运行，无需打开Termux窗口。
    - 双向：能立即发送命令并获取输出。
    - 安全：使用生成的安全令牌防止未经授权的访问。
    - 便捷：包含自动脚本，便于设置和移除。
4. **使用建议**：
    - 推荐使用一键安装，在Termux中运行指定脚本自动完成环境设置、服务器下载和安全令牌生成。
    - 安装完成后，将生成的安全令牌复制到Obsidian插件设置中。
    - 确保Obsidian插件设置中的服务器端口与Python脚本中的端口一致。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


