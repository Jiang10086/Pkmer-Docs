---
uid: 1780392510945000
title: 'Obsidian 插件：Base Settings'
tags: ['模板与链接处理', '数据处理', '效率工具', '自动化与AI', 'obsidian插件']
description: '通过将模板JSON文件深度合并到配置文件中，可在多用户仓库中强制应用共享的基础设置。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Base Settings

> [!Note] 插件名片
> - 插件名称：Base Settings
> - 插件作者：jaidetree
> - 插件说明：通过将模板JSON文件深度合并到配置文件中，可在多用户仓库中强制应用共享的基础设置。
> - 插件分类：['模板与链接处理', '数据处理', '效率工具', '自动化与AI', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/jaidetree/obsidian-base-settings)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?base-settings)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/jaidetree/obsidian-base-settings/master/README.md)



## 概述

### Base Settings插件总结
1. **主要功能**：在多用户的Obsidian库中强制执行共享的基础设置。通过将模板JSON文件深度合并到配置文件中，确保共享设置生效。
2. **适用场景**：适用于有多个贡献者的团队或项目。将基础模板文件文件夹提交到版本控制，用户打开库时，插件自动合并模板到本地 `.obsidian` 配置，在不覆盖用户已有配置的前提下，强制执行所需插件、共享快捷键等设置。
3. **核心特色**：基础模板值在冲突时优先，既保证共享设置的实施，又让用户能添加自定义内容。支持使用合并指令，可自定义特定键的合并策略，如对数组采用拼接操作。
4. **使用建议**：先在 `.obsidian` 内创建文件夹存放基础模板，添加与 `.obsidian` 配置文件同名的部分JSON文件，在插件设置中设置文件夹路径。若目标配置文件不存在，模板会在文件创建后的下次同步时应用。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


