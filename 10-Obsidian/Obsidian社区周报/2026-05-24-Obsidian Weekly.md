---
uid: 20260526134724
title: Obsidian Weekly 2026-05-24：AI 深度渗透&自动化工作流构建
tags: [Weekly, Obsidian]
description: Obsidian Weekly 2026-05-24：AI 深度渗透&自动化工作流构建
author: 淡水鱼,熊猫别熬夜,PKMer
type: other
draft: false
editable: false
modified: 20260526151924
---

# Obsidian Weekly 2026-05-24：AI 深度渗透&自动化工作流构建

> [!Abstract]
> **统计时间**：2026-05-17 21:00 ~ 2026-05-24 21:00
> **声明**：本栏目灵感来源于 _Eleanor Konik_ 女士于 2021 年 4 月至 2023 年 6 月期间写作发表的一系列 [Obsidian Roundup](https://www.eleanorkonik.com/tag/roundup/) 文章，如有兴趣可关注原作者的个人网站 [Obsidian Iceberg](https://www.eleanorkonik.com/)；内容来源于 Obsidian 官方 Discord 频道和相应项目在 Github 或其独立网站上的信息。描述中可能存在基于个人理解进行的修改，如有错谬欢迎指正。感谢 Obsidian 团队为我们带来如此优秀的软件。

## 插件新闻

### 社区插件

#### 新增

> [!Tip]
> 由于 AI 审核的引入，近期上架插件数量出现爆炸式增长，编者目前精力有限，故仅能选择性收录并简单介绍，详情可前往新版插件页面 [Obsidian Community](https://community.obsidian.md/) 获取。

##### 🤖 AI 与智能助手

- [Vault Knowledge Base](obsidian://show-plugin?id=okb) By _dgalichet_

> 通过本地 obsidian-kb 语义索引搜索当前库。

- [AskVault](obsidian://show-plugin?id=ask-vault) By _sourit2001_

> 使用本地 Codex CLI 对当前笔记或整个库提问。

- [Open Bridge AI](obsidian://show-plugin?id=open-bridge-ai) By _xiaoyihuang0503-cyber_

> 一个上下文 AI 工作区，连接笔记、选区、文件、AI 回复以及本地或云端模型后端。

- [Morning OS](obsidian://show-plugin?id=morning-os) By _satyagalla_

> 每日简报仪表盘，从 Obsidian 库中展示任务、目标和 AI 洞察。

- [Busy Goblins](obsidian://show-plugin?id=busy-goblins) By _roseygoblin_

> 在笔记上构建可复用的 AI 操作链。使用本地 Ollama 模型处理、编写和重写 Markdown 文件，然后将工作流保存为预设，一键运行。

- [Vault Chat Agent](obsidian://show-plugin?id=vault-chat-agent) By _redzumi_

> 与能搜索库、检查笔记并准备待审核编辑的 AI 助手对话。

- [ExcaVelo](obsidian://show-plugin?id=excavelo) By _biblecode21_

> 使用 Claude 将原始备忘录转换为结构化笔记（会议纪要、1 对 1 沟通、日报）。支持 Claude Code 订阅或 Anthropic API 密钥。

- [AI Browser Chat](obsidian://show-plugin?id=aibrowser-chat) By _thanshi26_

> 在侧边栏中嵌入 ChatGPT、Claude、Gemini、Grok、DeepSeek 和 Perplexity。可将库笔记和选中文本直接发送至 AI 对话。

- [AI-Vault](obsidian://show-plugin?id=ai-vault) By _jamjan05_

> 直接在笔记内与 GPT 和 Claude 对话——支持来自库的 RAG、历史记录、项目和智能模式。

- [Token Count](obsidian://show-plugin?id=token-count) By _lemondepat_

> 在状态栏中统计当前笔记的 Token 数量（GPT、Claude、Gemini），显示在字数旁边。

- [Notebrain](obsidian://show-plugin?id=notebrain) By _kiluahh_

> 笔记内的 AI 代理。按 Mod+Shift+Enter 即可在任何笔记中直接与 DeepSeek 对话。

- [Claude Code IDE Pro](obsidian://show-plugin?id=claude-code-ide-pro) By _mevkh, transept-ai_

> 帮助 Claude Code 查看活动笔记、标签页和选区，打开文件，并通过并排差异视图提出编辑建议。

- [Claude Vault Citations](obsidian://show-plugin?id=claude-vault-citations) By _nord342_

> 向库提问，获取带有精确笔记和段落引用的答案，由 Claude 原生 Citations API 驱动。

- [Feynman - AI research assistant](obsidian://show-plugin?id=feynman-research-agent) By _icarian-systems_

>库的研究代理。使用你自己的 Anthropic API 密钥在 Docker 中本地运行。

##### ✅ 任务与项目管理

- [CEvent Planner Extra](obsidian://show-plugin?id=cevent-planner-extra) By _abdur-nur-porag_

> CEvent-Planner 的附加插件。

- [Vault Time Tracker](obsidian://show-plugin?id=vault-time-tracker) By _rafaelmehdiyev_

> 追踪在笔记上花费的时间。即使 Obsidian 在后台运行，计时器也会持续计时。

- [Personal Kanban](obsidian://show-plugin?id=personal-kanban) By _jesuspinarte_

> 一个简单的插件，用看板管理个人项目。

![Personal Kanban](https://raw.githubusercontent.com/jesuspinarte/obsidian-personal-kanban/master/images/demo-v0.1.0.gif)

- [CEvent-Planner](obsidian://show-plugin?id=cevent-planner) By _abdur-nur-porag_

> 交互式事件和任务管理仪表盘，包含现代日历、列表和时间线视图，支持实时子任务跟踪和系统提醒。

- [Daily Checklist](obsidian://show-plugin?id=daily-checklist) By _mattmaiorana_

> 一个极简的侧边栏日常清单，可选择同步到日记。

- [Todoist Bridge](obsidian://show-plugin?id=todoist-bridge) By _rodrigolourencofarinha_

> 将 Todoist 任务与标记了 `#todoist` 的 Obsidian Markdown 任务同步。

- [Daily Checkbox Focus](obsidian://show-plugin?id=daily-checkbox-focus) By _geokhv_

> 打开日记时自动聚焦到第一个空白复选框。

- [Task Project Tree](obsidian://show-plugin?id=task-project-tree) By _toustifer_

> 将文件夹转化为带有概览笔记和树状进度的任务项目。右键任意文件夹即可设为项目，在文件资源管理器中实时查看任务完成徽章。

- [Operon](obsidian://show-plugin?id=operon) By _hasanyilmaz_

> 面向人类和代理的任务管理系统，支持行内任务、文件任务、过滤器、管道、置顶任务、日历视图、看板视图、重复任务和时间跟踪。

##### 📅 日历与时间管理

- [Simple Timestamp](obsidian://show-plugin?id=simple-timestamp) By _mkauto_

> 每次创建或保存笔记时，自动将当前日期/时间写入 frontmatter 属性。

- [Meetings Plus](obsidian://show-plugin?id=meetings-plus) By _jabaho9523_

> 订阅日历，一键创建预填充的会议笔记。无需拖拽，无需 Outlook。基于 ICS，隐私优先。

- [Schedule Calendar](obsidian://show-plugin?id=schedule-calendar) By _seonggoos_

> 可视化的拖拽式日历，用于管理日记和周记安排。

- [Created Daily Note Sync](obsidian://show-plugin?id=created-daily-note-sync) By _zgfdada_

> 根据笔记 frontmatter 中的创建日期，自动生成对应的 Obsidian 日记。

##### ✍️ 写作与编辑

- [Freewrite](obsidian://show-plugin?id=freewrite) By _astroneeor_

> 基于定时的无干扰写作会话，保存为 Markdown 笔记。

- [Slash Inserter](obsidian://show-plugin?id=slash-commands) By _jimmy-web169_

> Notion 风格的 / 斜杠菜单，可快速插入标题、列表、标注、代码块、链接卡片等。

- [Clean Copy](obsidian://show-plugin?id=clean-copy) By _rafaelmehdiyev_

> 将笔记复制到剪贴板时，去除 YAML、wiki 链接、标签、块 ID 和标注语法。

![Clean Copy](https://raw.githubusercontent.com/rafaelmehdiyev/obsidian-clean-copy/master/docs/readme/image.png)

- [Side Comments origin](obsidian://show-plugin?id=side-comments-origin) By _jepicaju862-lab_

> 侧边栏批注和评论，支持文本高亮、悬停预览、Markdown 评论、图片支持、侧边栏管理、导出和备份。

- [Easy Wikilink](obsidian://show-plugin?id=easy-wikilink) By _rockorolla_

> 类似 Ctrl+K，但用于内部 wiki 链接。选中文本，选取页面，生成 `[[页面|选中的文本]]`。

- [Auto Spacer](obsidian://show-plugin?id=auto-spacer) By _fanthus_

> 将混合英文片段用行内代码包裹，并在中英文之间插入适当的空格。

- [Markdown Table to LaTeX](obsidian://show-plugin?id=md-table-to-latex) By _pengivy1990_

> 将 Markdown 表格转换为 LaTeX 的 array/tabular 环境。

- [写作的标注](obsidian://show-plugin?id=writing-annotations) By _hornatx_

> 批注和脚注。

- [禅(专注模式)](obsidian://show-plugin?id=super-zen) By _hornatx_

> 一个极简、干净的禅模式，用于专注写作。

- [Workflowy-Style Outline](obsidian://show-plugin?id=workflowy-style-outline) By _springrain1_

> 将笔记转换为 Workflowy 风格的大纲编辑器，支持块级编辑。

- [Redline](obsidian://show-plugin?id=redline) By _nicolasassi_

> 添加锚定到特定段落、标题、图片、代码块和表格的 PR 风格审阅评论。评论保存在同名的 .review.md 侧车文件中，保持源文档整洁。

- [Deep Research Formatter](obsidian://show-plugin?id=deep-research-formatter) By _zhanglongx_

> 清理 ChatGPT Deep Research 导出的 Markdown，移除不可读的行内标记。

- [Semoi — Proof of Writing](obsidian://show-plugin?id=semoi) By _gjtorikian_

> 在写作时捕获按键证据，并通过 semoi.net 铸造加密的写作证明证书。

- [Copy as Rich URL](obsidian://show-plugin?id=copy-as-rich-url) By _brianling_

> 将当前笔记作为富文本超链接复制到剪贴板。粘贴到 FuseBase、Notion、Confluence 等富文本编辑器中，显示为单个可点击链接。

##### 📊 可视化与图表

- [Fluorite](obsidian://show-plugin?id=fluorite) By _telehakke_

> 在浮动面板上显示图片或笔记。

![Fluorite](https://raw.githubusercontent.com/telehakke/fluorite/master/readmeAssets/demo02.png)

- [Graph Heatmap](obsidian://show-plugin?id=graph-heatmap) By _mafgin_

> 根据最近修改时间、连接度、字数或文件大小对图谱节点着色。专注模式可隔离孤立/枢纽/陈旧笔记。内置调色板和图谱内控制面板。

- [MapTheMind (Mouse)](obsidian://show-plugin?id=neuro-mindmap-mouse) By _cosmakes_

> 基于 Allen Mouse Brain Atlas (CCFv3) 构建的小鼠神经科学数据层级可视化数据库。

- [Better Embedded Canvas](obsidian://show-plugin?id=better-embedded-canvas) By _kotaindah55_

> 让嵌入的白板拥有更好的显示效果和交互性。

![Better Embedded Canvas](https://raw.githubusercontent.com/kotaindah55/better-embedded-canvas/master/assests/embedded-canvas-2.png)

- [Mermaid Next](obsidian://show-plugin?id=mermaid-next) By _dacrystal_

> 使用最新版本渲染 Mermaid 图表，不依赖 Obsidian 内置的捆绑版本。

- [Beauty Diagram](obsidian://show-plugin?id=beauty-diagram) By _beauty-diagram_

> 用 9 种精美主题美化 Mermaid 和 PlantUML 图表。兼容暗色模式，支持逐块主题覆盖，可移植图像输出，无需配置。

- [SimpleDraw](obsidian://show-plugin?id=simple-draw) By _whiteandgrey_

> 一个轻量级的绘图插件，用于绘制简单流程图。

- [Canvas SVG Export](obsidian://show-plugin?id=canvas-svg-export) By _hesprs_

> 将画布导出为干净的 SVG 图像。

- [comshit](obsidian://show-plugin?id=comshit) By _comwhore_

> 扩展 Canvas，增加思维导图快捷键、配对的 Markdown 同步、OSINT 子节点和嵌入的 .sheet 电子表格。

- [Lite Tabs](obsidian://show-plugin?id=lite-tabs) By _azona77_

> 轻量级的标签面板，支持垂直和卡片布局。性能优先。
![Lite Tabs](https://raw.githubusercontent.com/azona77/lite-tabs/master/lite-tabs-screenshot.png)

- [Better Kanban Bases View](obsidian://show-plugin?id=bases-kanban-view-ttvl) By _ttvl_

> 为 Obsidian 数据库添加专注的看板视图，支持可拖拽卡片、键盘排序、笔记预览和保存布局。

![Better Kanban Bases View](https://raw.githubusercontent.com/totocaster/kanban-base-view-obsidian/master/.github/assets/bases-kanban-view-screenshot.png)

- [Charts for Bases](obsidian://show-plugin?id=charts) By _zobweyt_

> 为数据库添加图表布局，可将笔记显示为交互式柱状图、折线图或饼图。

- [Simple ProgressBar](obsidian://show-plugin?id=simple-progressbar) By _isragdd12_

> 创建独立、高度可定制和交互式的进度条。

- [Wheel Picker](obsidian://show-plugin?id=wheel-picker) By _ezra-dvlpr_

> 显示一个转盘，点击后从转盘中随机选择一个项目。

- [Graph Source Color](obsidian://show-plugin?id=graph-source-color) By _karl-cn_

> 根据源点笔记动态着色图谱节点。

##### 🔁 同步与备份

- [Osync (Self-Hosted)](obsidian://show-plugin?id=osync) By _korthomasjeong_

> 自托管、端到端加密的库同步。运行自己的服务器（Docker）。

- [Shouji Diannao](obsidian://show-plugin?id=shoujidiannao) By _beijing-bijitongbu_

> 一款便捷、快速、安全的 Obsidian 笔记多端同步插件。通过动态码连接设备即可立即开始同步。

- [Git Sync](obsidian://show-plugin?id=git-obsi-sync) By _livan116_

> 使用你自己的 GitHub 账户在所有设备上同步库，永久免费。

- [Easy Git](obsidian://show-plugin?id=easy-git) By _saiki77_

> 一种安全、即插即用的方式，将库中的单个文件夹或区域与 GitHub 同步。支持私有仓库、多文件夹映射、双向同步和冲突解决。

- [Agentic Git Sync](obsidian://show-plugin?id=agentic-git-sync) By _leweii_

>库及子模块与 GitHub 的代理式双向同步。AI 可自主解决冲突和 Git 错误。

- [Live-Cursor](obsidian://show-plugin?id=live-cursor) By _panospds, live-cursor_

> 一个免费、开源、隐私优先的协作同步插件。

- [Easy Push](obsidian://show-plugin?id=easy-push) By _artursbridaks_

> 无需终端即可审查更改并推送。

##### 📥 导入与导出

- [Starred News Sync](obsidian://show-plugin?id=starred-news-sync) By _jmiba_

> 将 RSS 阅读器中收藏的文章导入为带 YAML frontmatter 的笔记。

- [AnyContent Vault Importer](obsidian://show-plugin?id=anycontent-vault-importer) By _vancoder4-cyber_

> 粘贴抖音 / TikTok / 微信公众号 / YouTube 链接，自动转录/提取/OCR 成 Markdown 并写入库。单一插件覆盖多平台，输出 AI-readable 文本。

- [Document Weaver](obsidian://show-plugin?id=document-weaver) By _gs-ax_

> 将本地文档（Word、PDF、PowerPoint、HWP、Excel）转换为 Markdown 并保存到 Obsidian 库。

![Document Weaver](https://raw.githubusercontent.com/gs-ax/doc-weaver/master/docs/menu.PNG)

- [导出 PDF（图片压缩）/ Export PDF (+ Image Compress)](obsidian://show-plugin?id=pdf-export-compress) By _hunter00zb_

> 将 Markdown 导出为 PDF，支持图片自动压缩。Python（reportlab + Pillow）渲染，支持 CJK。
![导出 PDF（图片压缩）/ Export PDF (+ Image Compress)](https://raw.githubusercontent.com/hunter00zb/pdf-export-compress/master/image.png)

- [Context Pack for NotebookLM](obsidian://show-plugin?id=context-pack-for-notebooklm) By _kojiman_

> 从 Obsidian 库构建适用于 NotebookLM 的干净上下文包。

- [Confluence Weaver](obsidian://show-plugin?id=confluence-weaver) By _gs-ax_

> 将 Confluence 页面同步到库。

- [WeChat Inbox Sync](obsidian://show-plugin?id=wechat-inbox-sync) By _mingjuner123-spec_

> 将微信小程序的收件箱中的文本、网页、音频和文件同步到库。

- [Biji Tongbu](obsidian://show-plugin?id=bijitongbu) By _beijing-bijitongbu_

> 从微信公众号、小红书、得到、元宝和知乎采集内容。轻松保存聊天记录、图片和文件。

- [Wechat Messenger](obsidian://show-plugin?id=wechat-messenger) By _beijing-bijitongbu_

> 从微信公众号、小红书、得到、元宝和知乎采集内容。轻松保存聊天记录、图片和文件。

- [Google Docs Paste](obsidian://show-plugin?id=google-docs-paste) By _bfgpollara_

> 将 Google Docs 中的内容粘贴到 Obsidian，保留粗体、斜体、标题、列表、链接、表格和图片，而非压扁为纯文本。

- [Link Extractor](obsidian://show-plugin?id=link-extractor) By _andym-dc_

> 扫描当前笔记中的所有外部链接并将其复制为列表。

- [Vault Clone](obsidian://show-plugin?id=vault-clone) By _ezra-y_

> 通过克隆另一个库的主题和配置来创建新库。

- [pdf-to-md](obsidian://show-plugin?id=pdf-to-md) By _kkbin505_

> 使用 AI（OpenAI GPT 或阿里 Qwen）将手写 PDF 转换为包含 LaTeX 公式的 Markdown。

##### 🗂️ 文件与附件管理

- [Trans Vault](obsidian://show-plugin?id=transvault) By _fozi_

> 在本地桌面库之间复制或移动笔记、文件夹、附件以及经审核的直接笔记依赖项。

- [EzImage](obsidian://show-plugin?id=ezimage) By _keepwonder_

> 上传图片到云存储（R2/S3）并自动压缩。粘贴或拖拽图片即可立即获取 Markdown 链接。
![EzImage](https://raw.githubusercontent.com/keepwonder/ezimage-obsidian/master/url)

- [HEIC Viewer](obsidian://show-plugin?id=heic-viewer) By _kiaraorq_

> 允许在 Obsidian 中查看 .heic 和 .heif 图片，即时转换格式。

- [docxidian](obsidian://show-plugin?id=docxidian) By _kpaede_

> 打开、编辑和嵌入 DOCX 文档。

- [Fit PDF](obsidian://show-plugin?id=fit-pdf) By _t0masgutierrez_

> 默认按高度适配打开 PDF，而非按宽度适配。

##### 🎓 学术与研究

- [Research Paper](obsidian://show-plugin?id=research-paper) By _je-bh91_

> 搜索学术数据库，使用 AI 生成 APA 7 格式论文。支持 7 个大模型提供商和 10 个研究领域。

- [Paper Flow](obsidian://show-plugin?id=paper-flow) By _soantifragile_

> 检测 Markdown 笔记中的论文 URL，下载 PDF，维护元数据和引用计数，并生成 Mermaid 文献图谱。

- [Scholar Quest](obsidian://show-plugin?id=scholar-quest) By _zhao-jun-yong_

> 用经验值和等级游戏化你的学术工作流。

##### 🧠 知识管理

- [Zettelkasten Core](obsidian://show-plugin?id=zettelkasten-core) By _wesswart77_

> 一套完整的 Zettelkasten 第二大脑系统：闪念笔记、文献笔记、永久原子笔记、Zettel ID、收件箱处理和链接思考。

- [Linkosaurus](obsidian://show-plugin?id=autolink-keywords) By _polygonhunter_

> 在你输入时自动将关键词转换为 Obsidian wiki 链接。

- [QuickClip Organize](obsidian://show-plugin?id=quickclip-organize) By _vipsyvipul_

> 一个基于 Portent 的仪表盘，用于分类、连接和跟踪每个笔记的生命周期——从原始捕捉到组织化的知识。适用于任何笔记；搭配 QuickClip 扩展效果更佳。

- [数据库增强](obsidian://show-plugin?id=base-view-switcher) By _hornatx_

> 为 Base 数据库标题栏添加自定义视图切换按钮。

- [Definitions detector](obsidian://show-plugin?id=definitions-detector) By _rapphcd_

> 自动检测文本中所有的定义并创建链接。

- [Minder Nexus](obsidian://show-plugin?id=minder-nexus) By _ksawl_

> 用双向链接和自定义本体构建语义知识图谱。

- [Note Database](obsidian://show-plugin?id=note-database) By _pangy_

> 笔记的数据库视图，支持表格、看板、画廊、公式、过滤器和行内编辑。

- [Tagser](obsidian://show-plugin?id=tagser) By _caorol_

> 编辑 `tags` 属性的值。

- [Forge](obsidian://show-plugin?id=forge) By _joshua-walls_

> 定义库应有的结构，然后让 Forge 强制执行。检查偏移、标准化元数据，并安心地执行可审计的批量更改。

- [Brief](obsidian://show-plugin?id=brief) By _stephanteig_

> Obsidian 客户工作区管理器。切换客户空间，创建带有 frontmatter 的结构化笔记，并自动生成客户仪表盘。

- [Smart Tabs](obsidian://show-plugin?id=smart-tabs) By _ksawl_

> 默认在新标签页中打开文件，并智能去重标签。

- [Version View](obsidian://show-plugin?id=version-view) By _maoqingwei_

> 一个简单的 Obsidian 版本控制插件。通过直观的界面保存、管理、比较和恢复文件版本。

##### 🎨 界面与美化

- [Colorful Files](obsidian://show-plugin?id=colourfulfiles) By _sysadmin17_

> 用一个紧凑的 24 色水平网格调色板改造文件资源管理器侧边栏，支持悬停提示、自定义十六进制颜色代码和级联文件夹高亮。

- [File Recency Star](obsidian://show-plugin?id=file-recency-star) By _songkeeh_

> 为 1 天内创建的文件添加绿色星标，为 1 天内修改的文件添加黄色星标。

- [Note Reading Progress](obsidian://show-plugin?id=note-reading-progress) By _keithwithai_

> 在编辑和阅读模式下显示当前笔记的剩余阅读时间和滚动进度。

- [插件命名和管理](obsidian://show-plugin?id=plugin-setting-renamer) By _hornatx_

> 自定义左侧边栏设置中其他插件的名称，支持一键重命名为中文。

- [记录阅读位置](obsidian://show-plugin?id=simply-scroll) By _hornatx_

> 仅记录文件的滚动位置，不记录光标位置。无闪烁，无跳动。

- [Click to Edit](obsidian://show-plugin?id=click-to-edit) By _alpppine_

> 以阅读模式打开笔记，单击任意位置即可切换到编辑模式，光标定位到笔记末尾。

- [Vault Palette](obsidian://show-plugin?id=vault-palette) By _dejandj79_

> 自定义文件夹、文件和标签的颜色。

- [Iconik](obsidian://show-plugin?id=iconik) By _creagleone_

> 自定义图标和文本颜色。

- [Ultra Zen Mode](obsidian://show-plugin?id=ultra-zen-mode) By _marckfp_

> 进入无干扰的禅模式，隐藏侧边栏、属性、标题和状态栏。支持桌面和移动端。

- [Note Age Highlighter](obsidian://show-plugin?id=note-age-highlighter) By _memineoff_

> 当笔记在一定天数内未被修改时，在文件资源管理器中高亮显示。

- [material-icon-theme-for-vault](obsidian://show-plugin?id=material-icon-theme-for-vault) By _j4charlie_

> 为 Obsidian 文件资源管理器添加 Material 风格的文件和文件夹图标。

- [Snippet Commander](obsidian://show-plugin?id=snippet-commander) By _memineoff_

> 通过命令面板快速切换 CSS 代码片段。

- [Image Alignment](obsidian://show-plugin?id=image-alignment) By _ydd0729_

> 在图片右键菜单和命令中添加快速图片对齐控件。

- [Simple Pinned Files](obsidian://show-plugin?id=simple-pinned-files) By _mattmaiorana_

> 一个简单、独立的 Obsidian 固定文件视图。

##### 💻 代码与开发

- [Mockup Viewer](obsidian://show-plugin?id=mockup-viewer) By _twrusstw_

> 从库预览 HTML 模型，将插件的 CSS 注入到隔离的 iframe 中，用于设计时 UI 原型制作。

- [GitHub PR Autocomplete](obsidian://show-plugin?id=github-pr-autocomplete) By _andrewyx_

> 建议并自动补全 GitHub Issues 和 Pull Requests。

- [ABAL Language highlighter](obsidian://show-plugin?id=abal-lang) By _etudes-informatiques-et-services35_

> 在代码块中为 ABAL 语言提供语法高亮。

- [Brunet](obsidian://show-plugin?id=brunet) By _msyaifullah_

> 支持 Bruno API 格式，可在库中查看、编辑和运行 .bru HTTP 请求。

##### 🎵 多媒体

- [GemmaNotes](obsidian://show-plugin?id=gemmanotes) By _sarath_

> 通过按住说话创建语音笔记，使用 Gemma 4 在设备端转录。

##### 🌐 语言与翻译

- [Language Learn](obsidian://show-plugin?id=language-learn) By _mizu1_

> 基于 AI 的语言学习，支持单词分析、关系图谱、悬停提示和结构化笔记。

##### 🔒 安全与加密

- [Encrypted Datasafe Notes](obsidian://show-plugin?id=encrypted-datasafe-notes) By _xauravww_

> 使用 AES 加密 Markdown 笔记，支持锁定/解锁库、自动锁定计时器、右键加密/解密、损坏恢复、搜索解密、状态栏指示器、文件资源管理器装饰和密码更改。

- [Secret Placeholders](obsidian://show-plugin?id=secret-placeholders) By _lai2301_

> 将密码管理器中的秘密以占位符形式嵌入笔记，这样 .md 文件永远不会包含实际凭证。支持 OpenBao/Vault、1Password Connect 和 Bitwarden/Vaultwarden。

##### 🔗 特定集成与服务

- [Note to Public](obsidian://show-plugin?id=note-to-public) By _greedyhao_

> 一键发布 Obsidian 笔记到微信公众号等平台。

- [Ghost Publish](obsidian://show-plugin?id=ghost-publish) By _dsebastien_

> 将库内笔记发布到 Ghost 博客，可配置标签、新闻简报和 frontmatter 预设。

- [Memos Card View](obsidian://show-plugin?id=memos-card-view) By _adoom2017_

> 连接到 Memos 并以卡片视图管理备忘录记录。

- [Tag and Tally](obsidian://show-plugin?id=tag-and-tally) By _matalina_

> 在库中运行 Tag and Tally 桌面角色扮演游戏——掷骰子、库内规则书、NPC 生成器、随机表和卡组。

- [Miniflux RSS View](obsidian://show-plugin?id=miniflux-rss-view) By _adoom2017_

> 阅读 Miniflux RSS 条目，并在 Obsidian Web 查看器中打开文章。

- [MovieLog](obsidian://show-plugin?id=movielog) By _zzditto_

> 通过 TMDB 集成记录电影和电视剧的观看历史。

- [Search Movies and TV Shows TMDB](obsidian://show-plugin?id=search-movies-tv-tmdb) By _bernardonogueira8_

> 在 TMDB 上搜索电影和电视剧，并自动创建带有评分的笔记。

- [Live Data Hub](obsidian://show-plugin?id=live-data-hub) By _chefrocker_

> 直接在笔记中显示实时 MQTT 和 REST API 数据。

##### 📌 其他实用工具

- [TLP Classification](obsidian://show-plugin?id=tlp-classification) By _rafamss_

> 使用交通灯协议 (TLP) 对文档进行分类。在属性面板中提供可视化选择器、状态栏指示器，并可自动为 Better Export PDF 生成 PDF 页眉/页脚标记。

- [Extensions-Activity](obsidian://show-plugin?id=plugins-activity) By _yunz93_

> Extensions-Activity 帮助你了解自己实际如何使用第三方社区扩展。

#### 更新

[Weread](obsidian://show-plugin?id=obsidian-weread-plugin) By _zhaohongxuan_

> - **1.6.0** (2025-10-04)：
>   - 新增：
>     - 阅读统计面板：新增 WereadReadingStatsView，点击书架工具栏图标打开，包含本周/本月/本年/全部多维度 Tab，Tab 选中状态使用强调色浅背景高亮；
>     - 用户信息卡片：顶部展示圆形头像、用户名、个性签名，右侧提供导出图片按钮；
>     - KPI 卡片：展示阅读时长、阅读天数、日均时长（附环比徽章）、读过、读完、笔记数，数字字号放大，单位保持正常大小；
>     - SVG 柱状图：按天/月/年粒度展示阅读时长，月视图补全当月所有日期（含未来日期）；
>     - 年度热力图：GitHub 风格，自适应宽度无横向滚动条，图例尺寸修复；
>     - Top 书单：展示封面、作者、标签、Mini 进度条、阅读时长排行；
>     - 偏好分析：分类偏好条形图、偏好作者列表、24 小时阅读时段分布；
>     - 导出图片：点击导出按钮显示 Loading 提示，生成完成后弹出预览 Modal，预览 Modal 提供保存到库/ 保存到本地 / 复制到剪贴板三个操作，文件名附加时间戳（精确到分钟）。
>   - 修复：
>     - 缓存机制修复：修复 loadDailyCache() 缓存永远未命中的 Bug（根因：隐藏目录 .weread-cache/ 不在 Obsidian 库索引中，getAbstractFileByPath 始终返回 null），改用 vault.adapter.exists/read，全部/年度 Tab 首次加载速度大幅提升；
>     - 截图偏移修复：修复非分屏模式下导出图片只显示右半部分的问题；
>     - 导出闪烁修复：修复点击导出时界面闪烁跳动的问题。
>   - 变更：
>     - 新增 WeRead Agent API：callAgentGateway() / getReadingStats() / getUserInfo()；
>     - 新增设置项：API Key 输入，Key 可通过微信读书官方 Skill 页面获取；
>     - 移除废弃设置项：「阅读统计保存位置」和「同步阅读统计」。

[Notebook Navigator](obsidian://show-plugin?id=notebook-navigator) By _johansan_

> - **3.0.0**：
>   - 新增：
>     - 手动排序：列表窗格新增手动排序模式，可按任意顺序排列笔记，位置保存为 frontmatter 数字索引；
>     - 手动排序操作：选中笔记后按 Cmd/Ctrl + 方向键上下调整顺序，或从排序菜单进入拖拽排序视图；
>     - 手动排序设置：列表 > 手动排序 > 新笔记位置，可选顶部、底部、所选笔记下方或未排序；
>     - 自定义分组标题：列表窗格右键文件可创建或编辑分组标题；
>     - 字数目标：自定义分组标题可显示总字数和目标字数进度；
>     - 分组折叠：点击分组标题旁的箭头可折叠/展开分组；
>     - 最近文件拖拽：可将最近文件拖入快捷方式、文件夹、标签和属性；
>     - 日历设置：日历 > 日历集成 > 周期性笔记区域设置，控制笔记路径使用日历区域还是 Obsidian 区域。
>   - 改进：
>     - 列表窗格：字数显示支持标题位置、属性位置、目标字数和目标百分比显示。
>   - 变更：
>     - 设置：排序属性 " 更名为 " 要排序的属性 "，支持逗号分隔的多个属性，每个属性作为独立排序选项。
>   - 修复：
>     - 命令：删除文件命令现在仅删除所选文件，不再误删文件夹；
>     - 快捷方式：跨设备同步时，不同路径大小写不再导致快捷方式失效；
>     - 列表窗格：隐藏日期时修正了图片行的多余间距，以及粘性分组标题上方的微小间隙。

 [Decks](obsidian://show-plugin?id=decks) By _dscherdi_

> - **1.12.7**：
>   - 修复：
>     - 移动端标签模式顶部留白：修复了移动端标签模式下顶部出现多余留白的问题，原因为安全区域顶部内边距被无条件应用，现已限定仅在模态模式下生效。

 [Easy Typing](obsidian://show-plugin?id=easy-typing-obsidian) By _Yaozhuwa_

> - **6.0.8**：
>   - 自动格式化改进：
>     - 支持穿透 Markdown 格式标记（`**、*、~~`）检测语言对边界并插入空格；
>     - 修复前缀词典在中文语境下失效，导致 L1、n8n 等词被错误添加空格；
>     - 修复中文标点符号未被识别为 CJK 上下文，导致 token 切分不准确；
>     - 修复 Markdown 格式标记被合并到相邻英文 token 导致前缀词典保护失效。
>   - Bug 修复：
>     - 修复选中包裹符号时，内容含花括号导致闭合位置错误。

### PKMer 出品

> [!INFO]
> **PKMer**（[PKMer.cn](https://pkmer.cn/)、[PKMer.net](https://pkmer.net/)）旨在打造东半球强大的知识管理社区。Personal Knowledge Management (PKM) + "er"，其中 "er" 表示人，专注、喜爱个人知识管理工作、追求效率的人们，都可以划入这个行列，希望社区凝聚更多这样的人。

#### Media Extended 更新至 [v4.2.5](https://github.com/aidenlx/media-extended/releases/tag/4.2.5)

- 修复了与异步修补 `openLinkText` 的插件（如 Recipe Grabber）的兼容性问题。当 Media Extended 的链接处理器未匹配到媒体链接、回退至默认处理器时，它之前是同步调用回退逻辑的——导致下游补丁以 Promise 形式返回的所有异步工作均被丢弃。如今回退逻辑已正确使用 `await`，从而确保其他插件的异步处理器能完整执行完毕。

## PKM 相关知识推荐

> [!INFO]
> 欢迎收藏 [PKMer 导航页](https://pkmer.cn/link/)，一键直通 PKMer 各社交平台账号，与热爱分享与知识管理的同好们交流，第一时间获取行业新鲜资讯！

### [Ob 原生搜索优化，给你文献检索般的便捷体验](https://www.xiaohongshu.com/discovery/item/6a0acf2c00000000070251c5?source=webshare&xhsshare=pc_web&xsec_token=ABGfWhne5c33JSd6UL-QaSY2SPSVPuCVESpZCx1i0Juww=&xsec_source=pc_share)

在原生搜索页面的基础上加上了直观的高级检索图形界面，一键设置布尔逻辑，并可使用快速选择器，杜绝拼写错误。另有悬浮面板小窗、关系图谱归纳等功能，大大加强搜索体验。

![Weekly-2026-05-24-Pasted image 20260526002650|650](https://cdn.pkmer.cn/images/Weekly-2026-05-24-Pasted%20image%2020260526002650.png!pkmer)

> [!Warning] 声明
> 本栏目致力于为广大 Obsidian 中文用户汇总全面的官方资讯与插件、外观动态。为了保持信息的全面性，我们的**收录并不等同于推荐**，还请各位用户知悉并理解，根据自身需求进行判断和选择。
