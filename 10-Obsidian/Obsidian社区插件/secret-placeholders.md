---
uid: 1780392512021000
title: 'Obsidian 插件：Secret Placeholders'
tags: ['第三方工具集成', '安全与隐私', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。你可以把密码管理器里的机密信息以占位符的形式嵌入笔记中，这样.md文件里就不会包含实际的凭证信息啦。它支持OpenBao/仓库、1Password Connect，还有Bitwarden/Vaultwarden。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Secret Placeholders

> [!Note] 插件名片
> - 插件名称：Secret Placeholders
> - 插件作者：lai2301
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。你可以把密码管理器里的机密信息以占位符的形式嵌入笔记中，这样.md文件里就不会包含实际的凭证信息啦。它支持OpenBao/仓库、1Password Connect，还有Bitwarden/Vaultwarden。
> - 插件分类：['第三方工具集成', '安全与隐私', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/lai2301/obsidian-secret-placeholders)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?secret-placeholders)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/lai2301/obsidian-secret-placeholders/master/README.md)

![Secret Placeholders](https://cdn.pkmer.cn/covers/secret-placeholders_internal_0.gif!pkmer)

## 概述

### Secret Placeholders插件总结
1. **主要功能**：在Obsidian笔记中嵌入密码管理器的机密信息占位符，笔记仅存储占位符，真实值从密码管理器获取，仅在Obsidian内显示，不写入`.md`文件。支持自动补全、保存新机密、编辑机密值。
2. **适用场景**：适用于需要在笔记中引用机密信息，但又不想将真实凭据存储在笔记中的场景，尤其在使用LLM管理笔记库时，可避免机密信息泄露。
3. **核心特色**：将机密信息与笔记分离，仅在Obsidian内显示真实值，LLM、Git历史和备份等只能看到占位符；支持多种密码管理器后端，每个后端有独立占位符前缀，可按需启用。
4. **使用建议**：根据自身需求选择合适的密码管理器后端并完成认证设置；使用自动补全功能快速插入占位符；在编辑机密值时，通过插件更新后端，笔记内容不受影响。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


