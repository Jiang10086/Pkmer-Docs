---
uid: 20260518122311
title: Obsidian Weekly 2026-05-17：全新社区插件页面上线！
tags: [Weekly, Obsidian]
description: Obsidian Weekly 2026-05-17：全新社区插件页面上线！超多新插件上架！
author: 淡水鱼,熊猫别熬夜,PKMer
type: other
draft: false
editable: false
modified: 20260518122327
---

# Obsidian Weekly 2026-05-17：全新社区插件页面上线！超多新插件上架！

> [!Abstract]
> **统计时间**：2026-04-25 21:00 ~ 2026-05-17 21:00
> **声明**：本栏目灵感来源于 _Eleanor Konik_ 女士于 2021 年 4 月至 2023 年 6 月期间写作发表的一系列 [Obsidian Roundup](https://www.eleanorkonik.com/tag/roundup/) 文章，如有兴趣可关注原作者的个人网站 [Obsidian Iceberg](https://www.eleanorkonik.com/)；内容来源于 Obsidian 官方 Discord 频道和相应项目在 Github 或其独立网站上的信息。描述中可能存在基于个人理解进行的修改，如有错谬欢迎指正。感谢 Obsidian 团队为我们带来如此优秀的软件。

## 官方资讯

### Cure53 和 Trail of Bits 对 Obsidian Sync 的审计

Obsidian 定期与独立研究机构进行 [安全审计](https://obsidian.md/security)，以确保我们的代码和流程符合最高安全标准。此前，我们曾于 [2024 年 1 月](https://obsidian.md/blog/cure53-security-audit/) 和 [2024 年 12 月](https://obsidian.md/blog/cure53-second-client-audit/) 分享了针对 Obsidian 桌面端和移动端应用的审计报告。

现在，我们的 [安全](https://obsidian.md/security) 页面上新增了两份审计报告，评估了 [Obsidian Sync](https://obsidian.md/sync) 的 API、服务器和加密机制。这两项审计分别由 [Cure53](https://cure53.de/)（2024 年 10 月完成）和 [Trail of Bits](https://www.trailofbits.com/)（2025 年 12 月完成）执行。

我们很高兴地宣布，这些报告中的所有发现均已完成修复和披露，并得到了相应审计方的验证。

#### 背景

自 2020 年服务推出以来，Obsidian Sync 的加密代码基本未变。最显著的变化是 [2025 年 8 月 22 日](https://obsidian.md/changelog/2025-08-22-sync/) 随 [Obsidian 1.9.11](https://obsidian.md/changelog/2025-08-22-desktop-v1.9.11/) 一起发布的一次小幅加密升级。当时我们还发布了更新版的 [如何验证 Obsidian Sync 端到端加密](https://obsidian.md/blog/verify-obsidian-sync-encryption/) 的说明。

#### Cure53 对 Obsidian Sync 的审计

我们委托了总部位于柏林的安全公司 [Cure53](https://cure53.de/) 对 Obsidian Sync 服务（包括 API、服务器和加密机制）进行审计。

欢迎阅读 [调查结果摘要](https://obsidian.md/files/security/2024-Obsidian-Cure53-Sync-Audit-Summary.pdf) 和 [完整报告](https://obsidian.md/files/security/2024-Obsidian-Cure53-Sync-Audit-Full.pdf)。

报告发现了四个低优先级问题和一个中优先级问题。我们自豪地报告，Cure53 团队已审查了这些修复方案，并确认他们的建议得到了妥善落实：

> 必须肯定 Obsidian 团队在审计结束后迅速采取行动，解决了若干已发现的漏洞。这一积极主动的做法凸显了 Obsidian 团队对保护用户体验的坚定承诺。

##### 加密升级

在本次审计中，Cure53 验证了我们于 [2025 年 8 月](https://obsidian.md/changelog/2025-08-22-sync/) 提出的加密升级方案，并表示：

> Cure53 对最新版 Obsidian Sync 软件中增强的后端安全功能印象深刻。与此前版本相比，Obsidian 在强化其加密机制方面取得了显著进步。

##### 将“托管加密”重命名为“标准加密”

Cure53 发现了编号为 DYL-04-005 的问题，描述为“托管保管库加密模式中的密钥管理混淆”。该问题指出，应用和文档未明确说明不选择 Sync 默认的端到端加密选项所带来的风险。

自推出以来，Obsidian Sync 始终提供两种加密选项：端到端加密（默认）和“托管加密”（可选，后更名为“标准加密”）。

根据此次审计结果，应用和帮助站点已于 2024 年 10 月通过提交 [d18640c](https://github.com/obsidianmd/obsidian-help/commit/d18640c6d3010d73354e75853a4e3dde86c2bd52) 更新，以说明 [选择标准加密的风险](https://obsidian.md/help/sync/security)。

#### Trail of Bits 对 Obsidian Sync 的审计

在 2025 年 8 月的 Sync 加密升级完成后，我们邀请了总部位于纽约的 [Trail of Bits](https://www.trailofbits.com/) 公司，对 Sync 的 API、服务器和加密机制进行了一次新的审计。

我们的目标是更深入地排查 Obsidian Sync 中的潜在漏洞。欢迎阅读 [完整报告](https://raw.githubusercontent.com/trailofbits/publications/refs/heads/master/reviews/2025.12-obsidiansync-securityreview.pdf)。

此次审计共发现 11 个问题。修复措施均已实施，并由 Trail of Bits 验证。报告中提到了三个未解决的问题，我们将在下文中说明。其中后两个问题已于 2025 年 11 月通过提交 [ec32a5c](https://github.com/obsidianmd/obsidian-help/commit/ec32a5c) 记录在我们的 [Sync 安全页面](https://obsidian.md/help/sync/security) 上。

##### 删除非活跃订阅的保管库

Trail of Bits 发现了 TOB-OBSYNC-2 问题：“已注销的客户端可查找并触发删除订阅不活跃的保管库”：

> 使用 Obsidian Sync 需要订阅，保管库所有者的订阅到期 30 天后，服务器端的同步保管库副本可被删除。[…] 由于这仅适用于那些已到待删除期限的保管库，因此似乎不会产生任何安全问题。

目前，我们决定保留此端点，以便 Sync 服务器在宽限期后能够清理数据。未来，我们将考虑如何通过计划任务来处理此操作。

##### 确定性文件哈希加密

Trail of Bits 发现了 TOB-OBSYNC-9 问题：文件哈希的确定性加密危及文件机密性。

针对此报告，我们在 [Sync 安全页面](https://obsidian.md/help/sync/security) 新增了一个“局限性”章节，用以解释我们为实现快速、可靠的同步以及设备间的高效存储而做出的权衡。

> 我们采用确定性方式加密文件哈希：相同的文件内容，使用相同的加密密钥和盐值，在服务器上始终生成相同的加密哈希。这有助于 Sync 检测重复数据，避免重新上传或重复存储相同数据，从而节省带宽和远程存储空间，尤其在版本历史记录或大文件重复出现时效果显著。
>
> 然而，如果攻击者入侵了 Sync 服务器，并且有另外的途径能强制用户上传其选定的文件，那么攻击者便可强制用户上传特定文件，并判断该文件是否与用户此前上传的某个文件匹配。

##### 路径与内容之间缺乏加密绑定

Trail of Bits 发现了 TOB-OBSYNC-10 问题：文件内容与元数据之间普遍缺乏加密绑定。与上述问题一样，我们在 Sync 安全页面添加了以下详细说明：

> 部分元数据未经端到端加密：例如哪个设备上传或删除了文件、上传时间，以及加密文件路径与加密内容之间的映射关系。服务器可读取这些数据，以便传递变更、确定文件的版本历史记录并保持各设备同步。
>
> 如果 Sync 服务器遭到入侵，攻击者可能会篡改此映射关系，导致某个加密文件的内容以不同的文件路径被交付。这并不会泄露你的明文数据，数据依旧处于加密状态。

#### 结论

我们衷心感谢 Cure53 和 Trail of Bits 在这些审计中的协作。他们深厚的专业能力进一步增强了我们对 Obsidian Sync 安全性的信心。

我们打造 Obsidian，是为了捕捉自己的私密想法和创意，我们也希望你能同样放心地这么做。我们将继续与业界领先的安全公司合作开展审计，为这一承诺提供全面的覆盖和透明度。

原文链接：[Obsidian Sync audits by Cure53 and Trail of Bits - Obsidian](https://obsidian.md/zh/blog/cure53-tob-sync-audits/)

## 插件新闻

### 社区插件

#### 新增

> [!Tip]
> 由于 AI 审核的引入，近期上架插件数量出现爆炸式增长，编者目前精力有限，故仅能选择性收录并简单介绍，详情可前往新版插件页面 [Obsidian Community](https://community.obsidian.md/) 获取。

##### 🤖 AI 与智能助手

- [Write More / 不写就会死](obsidian://show-plugin?id=write-or-die) by _xuexue61_

> 帮助写作者追踪每日写作量，并利用 DeepSeek 生成中文小说写作练习。

- [OpenCode](obsidian://show-plugin?id=opencode) by _kriss-spy_

> 无需离开库即可启动 OpenCode CLI 终端会话，并浏览对话历史，将 AI 编码融入笔记环境。

- [English Text Interpreter](obsidian://show-plugin?id=english-text-interpreter) by _julioagh_

> 基于本地大模型 (Ollama) 对选中英文文本进行语境解读，阐释含义、语气、文化背景与意图。

- [Codex AI Agent](obsidian://show-plugin?id=codex-ai-agent) by _j4charlie_

> 深度集成 Codex CLI 的笔记型 AI 代理，在 Obsidian 内支持上下文审批与文件修改。

- [Meeting Notes](obsidian://show-plugin?id=meeting-notes) by _junxi-liu_

> 利用 OpenAI 转录录音或总结 Markdown 转录稿，并将进度、转录稿及可选摘要写入新笔记。

- [LLM Auto Tagger](obsidian://show-plugin?id=llm-auto-tagger) by _matbo1_

> 通过配置的大模型 API 自动为笔记添加库中已有的标签，实现智能标签管理。

- [Knowledge AI](obsidian://show-plugin?id=notebook-ai) by _david46liu_

> 为库提供全面的 AI 能力：带引文的 RAG 聊天、混合检索、多格式索引、OCR 与产物生成。

- [Knowledge Overview](obsidian://show-plugin?id=knowledge-overview) by _lingji-yidong_

> 利用 AI 生成结构化的学科概览，帮助梳理知识脉络。

- [Synod](obsidian://show-plugin?id=synod) by _slaymish_

> 在日记上运行一组大模型价值代理，揭示你尚未做出的决策，本地优先，支持多种 API。

- [OpenAgent Canvas](obsidian://show-plugin?id=openagent-canvas) by _openagentmarket_

> 通过本地 Codex 服务与桌面应用，从 Obsidian Canvas 运行 OpenAgent 自动化任务。

- [Lumen](obsidian://show-plugin?id=lumen-ai-assistant) by _chinoryunqin_

> 为 Obsidian 笔记点亮 AI 之光。支持多种大模型，提供总结、翻译、续写、润色等快捷操作，结果可直接写回笔记。

- [AskMate](obsidian://show-plugin?id=askmate) by _codewithbehnam_

> 就当前笔记或选中文本向 AI 提问，并支持图片上下文。

- [Manex Brain](obsidian://show-plugin?id=manex-brain) by _krcnow_

> 本地 AI 大脑，索引全部笔记并使用 Apple Silicon MLX 模型私密作答，无需联网。

- [VoxNote — Meeting Transcription & AI Summary](obsidian://show-plugin?id=voxnote) by _moonjuun_

> 通过 Deepgram 转录会议录音，再利用 Gemini 生成基于模板的 AI 摘要。

- [Tegaki](obsidian://show-plugin?id=tegaki) by _sdesuyo_

> 使用 AI 视觉 API 将手写笔记与图片转为可搜索文本（图片会发送至外部 API）。

- [AI Tag Curator](obsidian://show-plugin?id=ai-tag-curator) by _qmkcamel_

> 对 Obsidian 库进行 AI 标签管理与治理，保持标签体系健康有序。

- [Mindo](obsidian://show-plugin?id=mindo) by _therofli_

> 通过本地语音、RAG、Wiki 记忆与安全编辑，与你的库对话。

- [Note Mate](obsidian://show-plugin?id=ai-note-mate) by _ialex32x_

> 智能 AI 笔记助手，轻松创建笔记、拓展想法并从库中获取洞察。

- [Vault AI Buddy](obsidian://show-plugin?id=vault-ai-buddy) by _enygma_

> AI 驱动的库助手，用于全面检查、内省你的所有笔记。

- [PiChat](obsidian://show-plugin?id=pi-chat) by _gengyabc_

> 在本地与 Pi 编程代理聊天，直接在 Obsidian 内获取编码辅助。

- [Superpower Inside](obsidian://show-plugin?id=superpower-inside) by _magnitus99_

> 桌面 AI 副驾驶，提供大模型聊天、RAG、MCP 工具与源码感知上下文。

- [Claude Sync](obsidian://show-plugin?id=claude-sync) by _gbanjos_

> 自动将监视文件夹中的 Claude 聊天导出文件导入 Vault。

- [English Write Checker](obsidian://show-plugin?id=english-write-checker) by _julioagh_

> 借助本地大模型提供实时英语写作建议，助你达到 C1-C2 级表达水平。

- [Zulu Agent](obsidian://show-plugin?id=zulu-agent) by _foundlegacy_

> 完全原生的代理式 AI，无需终端或外部工具即可在 Obsidian 内驱动智能操作。

- [ConceptLens](obsidian://show-plugin?id=conceptlens) by _jade367_

> 将选中术语捕获为 AI 生成的概念笔记，附有语境解释、翻译与扩展。

- [Porygon](obsidian://show-plugin?id=porygon) by _iuga_

> 将你的笔记变成对话，与 AI 讨论你的知识库。

- [Bragi Canvas](obsidian://show-plugin?id=bragi-canvas) by _nextbound_

> 将 Obsidian Canvas 变为节点式的 AI 生成流水线，用于图像、视频、文本和音频创作。

- [Pi Agent](obsidian://show-plugin?id=pi-agent) by _christianlempa_

> 结合笔记上下文、链接、反向链接和标签，与 Pi 编程助手进行深度对话。

- [Claude Panel](obsidian://show-plugin?id=claude-panel-ryukyuhub) by _ryukyuhub_

> 由 Claude Code 驱动的右侧边栏聊天面板，以当前库为工作目录运行 CLI。

- [Horme](obsidian://show-plugin?id=horme) by _ducktapekiller_

> 多功能的 AI 助手，支持聊天、右键操作、全库 RAG 与可扩展技能系统。

- [AI Sidebar](obsidian://show-plugin?id=ai-sidebar) by _acxtrilla_

> 类似 Cursor 的 AI 侧边栏，将本地 CLI 代理与库上下文连接。

- [Meeting Scribe AI](obsidian://show-plugin?id=meeting-scribe-ai) by _chinoryunqin_

> 录制音频，通过豆包语音转文字并润色，生成会议纪要。

- [Codex库Agent](obsidian://show-plugin?id=codex-vault-agent) by _hendrikhuwy-lgtm_

> 收集库中经审查的证据，借助本地 Codex CLI 合成查询报告、仪表板与审计文档。

- [HangarX](obsidian://show-plugin?id=hangarx) by _3-elements-design_

> 为库提供共享 AI 记忆，Claude、Cursor 等 MCP 代理可通过知识图谱查询与更新笔记。

- [Implicit Macros](obsidian://show-plugin?id=implicit-macros) by _eriskii_

> 行内 AI 宏：键入 `!!提示词!` 即可通过 OpenAI 兼容端点行内展开。

- [MCP库Bridge](obsidian://show-plugin?id=mcp-vault-bridge) by _allexcd_

> 基于排除项的只读本地桥接，便于通过 MCP 客户端使用库笔记。

- [Research Agent](obsidian://show-plugin?id=research-agent) by _0126-hash_

> 对话式研究助手，用于引导研究工作流、证据审查、事实核查并生成 Markdown 交付物。

- [Karpathy LLM Wiki](obsidian://show-plugin?id=karpathywiki) by _green-dalii_

> Karpathy 的大模型 Wiki 实现，支持多页面知识生成、实体/概念页面与对话式查询。

- [Smart Note Agent](obsidian://show-plugin?id=smart-note-agent) by _binhong87_

> 代理式 AI 助手，用于读取和编辑库笔记。

- [Parallel Reader](obsidian://show-plugin?id=parallel-reader) by _fancive_

> AI 驱动的分屏阅读：左侧显示原文，右侧显示大模型生成的摘要卡片，并支持滚动同步高亮。

- [Chatting with AI](obsidian://show-plugin?id=chatting-with-ai) by _o1xhack_

> 代理式 AI 聊天助手，能通过自然对话读取、编辑和创建笔记，支持多种大模型。

- [Codex Panel](obsidian://show-plugin?id=codex-panel) by _murashit_

> 在侧边栏中集成 Codex，随时随地与本地 AI 代理交互。

- [Codex Bridge](obsidian://show-plugin?id=codex-bridge) by _ranjugao_

> 本地桥接器，用于将库笔记与 Codex 联动并导入 AI 回复。

- [Codex Workflow](obsidian://show-plugin?id=codex-workflow) by _yifu-tian_

> 使用 Codex 管理个人知识库，通过命令与侧边栏整合工作流。

- [Codeian](obsidian://show-plugin?id=codeian) by _wdblink_

> 在侧边栏中直接使用 Codex，将 AI 能力整合进日常笔记流。

- [AssetWeaver](obsidian://show-plugin?id=asset-weaver) by _0xkz1_

> 借助本地视觉语言模型自动为图片生成 Markdown 附属说明文件。

- [Researcher](obsidian://show-plugin?id=researcher) by _slaymish_

> 为 Obsidian 笔记提供异步研究工作流，方便在侧边栏中整合 AI 辅助研究。

- [FormulaR](obsidian://show-plugin?id=formula-r) by _danieldaidai_

> 自动验证与补全 LaTeX 数学推导，检测 {align} 块错误并建议下一步步骤。(AI 辅助数学推导)

- [QMD Semantic Search](obsidian://show-plugin?id=qmd-semantic-search) by _winboost_

> 利用 QMD 语义与关键词在库中进行本地搜索。(语义搜索)

##### ✅ 任务与项目管理

- [To-Do → Done Mover](obsidian://show-plugin?id=todo-done-mover) by _donnervs_

> 将已完成的任务（含子任务）移至「Done」区域，支持右键、命令或自动触发。

- [Markr](obsidian://show-plugin?id=markr) by _visua1hue_

> 基于触发器的列表与任务标记器，为外观和图标提供多样化选择。

- [Sync Todoist](obsidian://show-plugin?id=sync-todoist) by _o1xhack_

> 与 Todoist 双向同步任务，支持子任务、项目、标签及已完成任务查询。

- [Digital Garden Timer](obsidian://show-plugin?id=digital-garden-timer) by _lucidalpha_

> 将专注分钟转化为数字花园积分的计时器，让深度工作有所积累。

- [Inbox Zero](obsidian://show-plugin?id=inbox-zero) by _yuzameone_

> 用标签标记文件并以复选框形式管理，支持一键永久删除与拖拽排序，保持库清爽。

- [Jira Weaver](obsidian://show-plugin?id=jira-weaver) by _gs-ax_

> 将 Jira 问题同步至 Vault，通过 Wiki 链接、Frontmatter 与 Dataview 织入知识图谱。

- [Kanban Sync](obsidian://show-plugin?id=kanban-sync) by _jcacdc_

> 将看板的状态同步写入笔记的笔记属性，实现数据双向互通。

- [Reminder Telegram](obsidian://show-plugin?id=reminder-telegram) by _lukather_

> 当任务到达截止时间时，通过 Telegram 发送通知提醒。

- [Emrald](obsidian://show-plugin?id=emrald) by _admiral9k_

> 追踪工作成本：记录努力程度、心流状态、精力消耗与倦怠风险。

- [Rollover Daily Todos with Context](obsidian://show-plugin?id=rollover-daily-todos-with-context) by _mjparker_

> 将昨天日记中未勾选的任务滚动至今日日记，并保留上下文信息。

- [Rollover Daily Todos Helper](obsidian://show-plugin?id=rollover-daily-todos-helper) by _eugenschmalz_

> [Rollover Daily Todos](obsidian://show-plugin?id=obsidian-rollover-daily-todos) 的伴侣插件 ，通过延迟启动确保滚动任务在桌面与移动端可靠运行。

- [Time Manager](obsidian://show-plugin?id=time-manager) by _najeong-kim_

> 将每日任务可视化为时间线，并按类别追踪完成进度。

- [Cadence](obsidian://show-plugin?id=cadence-planner) by _wesswart77_

> 工作生活一体化工作区：主控中心、CRM、计划器与报表，以纯 Markdown 为数据源。

- [Marvis](obsidian://show-plugin?id=marvis) by _mahdi-massahi_

> AI 驱动的多视图项目计划器与习惯追踪器，集看板、时间线、日历于一体。

- [Worklog](obsidian://show-plugin?id=worklog) by _352662115-hub_

> 月度工作日志追踪器，管理任务、工时与日历，数据存储在本地 JSON 文件中。

- [OmniFocus Task Sync](obsidian://show-plugin?id=omnifocus-task-sync) by _jimmitchell_

> 将当前笔记中的未完成任务发送至 OmniFocus 收件箱，并在编辑器内标记完成。

- [GTDown](obsidian://show-plugin?id=gtdown) by _jonny_

> 专为 .gtd 文件打造的 TaskPaper 风格待办事项编辑器。

- [Automatic Shopping List Reorder](obsidian://show-plugin?id=shopping-list-automatic-reorder) by _joysimple_

> 自动将已购买的物品移至其所在分类的底部，方便购物清单管理。

- [MyWorld Task Manager](obsidian://show-plugin?id=myworld-task-manager) by _kjh-portfolio_

> 为 MyWorld 工作区提供集成式任务与项目管理。

- [KAI Command Center](obsidian://show-plugin?id=kai-command-center) by _jayp89_

> 为 KAI Obsidian OS 设计的本地运行仪表盘，集成任务、日历与可视化。(含任务模块)

##### 📅 日历与时间管理

- [30-Day Energy Log](obsidian://show-plugin?id=energy-tracker) by _minus1min_

> 在 30 天内追踪你每天 6 个时段的精力水平与活动，数据本地存储于 Vault，支持中英双语。

- [Japanese Calendar](obsidian://show-plugin?id=japanese-calendar) by _kojiman55_

> 支持日本节假日与补休的日历，点击日期自动创建日记，并能够显示和历与六曜。

- [Calendar Plus](obsidian://show-plugin?id=calendar-plus) by _mattmaiorana_

> 集成日记、周记、月记、季度笔记与年记的日历视图，全面概览时间轴。

- [Odaily](obsidian://show-plugin?id=odaily) by _guchang_

> 一款专注于日程的插件，用于捕捉想法、管理笔记与任务，提升个人效率。

- [Daily Note Plus](obsidian://show-plugin?id=daily-note-plus) by _o1xhack_

> 自动创建缺失的日记，确保每日记录不会断档。

- [Knox Timeline](obsidian://show-plugin?id=knox-timeline) by _cwagner223355_

> 在侧边栏以时间线视图展示 Fastmail 日历，支持一键创建关联会议笔记。

- [Yori Dashboard](obsidian://show-plugin?id=yori-dashboard) by _yorigo77_

> 集事件、任务、签到与月计划于一体的每日仪表盘，适配桌面与移动端。

- [Life Calendar](obsidian://show-plugin?id=life-calendar) by _paulobsf_

> 渲染人生周历 (Memento Mori)，划分工作、生活等阶段，并标记关键事件。

##### ✍️ 写作与编辑

- [Convert case](obsidian://show-plugin?id=convert-case) by _rymoio_

> 通过轻量、无依赖的命令集，将选中文本转换为常用的大小写风格。

- [Daily Saying KR](obsidian://show-plugin?id=daily-saying-kr) by _randonneurs_

> 向当前笔记中随机插入一句韩语谚语，为每日记录增添文化元素。

- [Better Footnote](obsidian://show-plugin?id=better-footnote) by _alcatrazyu_

> 为学术 Markdown 笔记提供专注于写作的脚注侧边栏，便于编辑、导航并保持上下文连贯。

- [Highlighter Plus](obsidian://show-plugin?id=highlighter-plus) by _creesee_

> 创建多色自定义高亮与下划线，支持独立的亮/暗主题配置、透明度控制和快捷键切换。

- [Preserve Blank Lines](obsidian://show-plugin?id=preserve-blank-lines) by _ivanohe_

> 在阅读模式中保留连续空行，与源码格式保持 1:1 一致。

- [Review Comments](obsidian://show-plugin?id=review-comments) by _shotashirai1719_

> 以 CriticMarkup 格式存储 Notion 风格的审阅批注，对 AI 辅助编辑十分友好。

- [Copy Highlighter](obsidian://show-plugin?id=copy-highlighter) by _nymbo_

> 高亮标记被复制的文本，让编辑过程中的文字变动一目了然。

- [Expandomatic](obsidian://show-plugin?id=expandomatic) by _onsi_

> 像 VSCode 一样将选区从单词向外逐步扩展至句子、段落乃至全文。

- [Track Changes](obsidian://show-plugin?id=track-changes) by _philphilphil_

> 在侧边面板中审阅 CriticMarkup 修改建议，支持接受、拒绝或回复。

- [Smart Punctuation on Rendering](obsidian://show-plugin?id=smart-punctuation-on-rendering) by _ile-24556_

> 在阅读视图中自动将 ASCII 标点渲染为印刷体形式，提升排版美感。

- [Notion block](obsidian://show-plugin?id=notion-block) by _bcs_

> 为实时预览模式带来类似 Notion 的块交互体验，提升编辑手感。

- [SimpleMerge](obsidian://show-plugin?id=simple-merge) by _mss051_

> 将相互链接的笔记合并为一个文档，并保持内容同步与格式统一。

- [Writing Studio](obsidian://show-plugin?id=writing-studio) by _writerp-777_

> 专业写作环境，提供专注模式、写作活页夹、冲刺计时器以及 WordPress 发布功能。

- [Structure Commander](obsidian://show-plugin?id=structure-commander) by _akudlay-ru_

> 以树状结构管理 Markdown，可移动分支、更改标题层级、折叠章节、重编号大纲。

- [Memoria](obsidian://show-plugin?id=memoria) by _i-iooi-i_

> 瀑布流备忘录，类似 flomo 的碎碎念记录，纯 Markdown 存储。

- [Owen Editor](obsidian://show-plugin?id=owen-editor) by _towishy_

> Markdown 编辑工具栏，附带 Owen Graphite 报告与表格辅助功能。

- [Alignment](obsidian://show-plugin?id=alignment) by _kool-ankit-raj_

> 将文本居中或右对齐，轻松调整笔记排版。

- [CJK Academic Count](obsidian://show-plugin?id=cjk-academic-count) by _alcatrazyu_

> 专为中、日、韩人文学术写作设计的字数统计，支持全文与选中文本计数。

- [yeelen-Murmur](obsidian://show-plugin?id=yeelen-murmur) by _fanxiaofang_

> 复古终端风格的内心独白记录器，将日常碎碎念转化为能量碎片。

##### 📊 可视化与图表

- [linkmind](obsidian://show-plugin?id=linkmind) by _qiuos_

> 以干净、对键盘友好的思维导图方式编辑 Markdown，将大纲与可视化相结合。

- [Three D Graph View](obsidian://show-plugin?id=three-d-graph-view) by _roasted-nz_

> 提供可在三维空间中旋转的图谱视图，用立体视角探索笔记关联。

- [Canvas Node Linker](obsidian://show-plugin?id=canvas-node-linker) by _mvstro_

> 在 Canvas 节点上右键即可一键复制其 Wiki 链接，快速构建连接。

- [Marp TikZ Plus](obsidian://show-plugin?id=marp-tikz-plus) by _kevinyuan_

> 支持 TikZ 图表与完整的 Marp 演示，提供幻灯片导航、演讲者备注及 PPTX 导出。

- [ObDrawIO](obsidian://show-plugin?id=obdrawio) by _hanzhichao_

> 在 Obsidian 内部直接编辑和管理 draw.io 图表，原生支持 .drawio 与 .dio 文件。

- [MermaidMaker](obsidian://show-plugin?id=mermaid-maker) by _akitaroh_

> 提供 Mermaid 图表的 GUI 行内编辑器，节点内支持 Wiki 链接、标签、数学公式与富文本。

- [MindCanvas](obsidian://show-plugin?id=mindcanvas) by _gengyabc_

> 真正的思维投影，将思维导图以地图形式呈现，让知识网络清晰可见。

- [Markdown Minimap](obsidian://show-plugin?id=markdown-minimap) by _nymbo_

> 为 Markdown 笔记添加缩略小地图，便于在长文档中快速导航。

- [svgeditor](obsidian://show-plugin?id=svgeditor) by _kpaede_

> 直接在 Obsidian 内编辑 SVG 矢量图形文件。

- [Beautiful Mermaid Renderer](obsidian://show-plugin?id=beautiful-mermaid-renderer) by _qiaoborui_

> 利用 beautiful-mermaid SVG 输出与主题变量，渲染更精美的 Mermaid 图表。

- [Corkboard](obsidian://show-plugin?id=corkboard) by _nighteye841228_

> 类似 Scrivener 的软木板视图，每个文件夹生成对应卡片，直观展示笔记。

- [Overboard](obsidian://show-plugin?id=overboard) by _alona-iaig_

> 嵌入 overboard.studio 的 AI 白板，支持手绘、AI 文生图与实时协作。

- [DocFlow](obsidian://show-plugin?id=docflow) by _gs-ax_

> 通过类型感知视图渲染 IT 项目工件，如 ER 图、API 规范、WBS 与架构图。

- [Pumler Diagrams](obsidian://show-plugin?id=pumler) by _pumler_

> 从代码块渲染 PlantUML、Structurizr 和 Mermaid 图表。

- [Canvas Drag Fix](obsidian://show-plugin?id=canvas-drag-fix) by _an2io_

> 修复 Linux 下因鼠标被误识别为笔设备导致的 Canvas 拖放问题。

- [Light Mindmap](obsidian://show-plugin?id=light-mindmap) by _ninglg_

> 自动将 Markdown 标题渲染为多彩、交互式思维导图，无需额外语法。

- [Canvas Cover Overlay](obsidian://show-plugin?id=canvas-cover-overlay) by _llaori1_

> 为每个 Canvas 自定义嵌入式缩略图和背景，增添视觉个性。

- [Model Weave](obsidian://show-plugin?id=model-weave) by _nejimakibird_

> 在 Markdown 中管理文本优先的模型、关系与图表，并支持导出。

- [iso.me Maps](obsidian://show-plugin?id=iso-me-maps) by _codybontecou_

> 从 iso.me 导出数据渲染交互式 Leaflet 地图，支持多种地理位置格式。

##### 🔁 同步与备份

- [Vaultbox](obsidian://show-plugin?id=vaultbox) by _grumpydev_

> 将库与指定的 Dropbox 文件夹直接同步，支持桌面端与移动端。

- [Octosync](obsidian://show-plugin?id=octosync) by _grumpydev_

> 通过 GitHub API 在桌面和移动端直接同步 Vault，实现基于 Git 的版本控制与多端同步。

- [Smart库Sync](obsidian://show-plugin?id=smart-vault-sync) by _leweii_

> 基于 AI 提交信息的智能双向同步，将库及子模块与 GitHub 连接。

- [NoX Sync](obsidian://show-plugin?id=nox-sync) by _mapherez_

> 手动自托管的库同步方案，需自行搭建 NoX Sync 后端。

- [ExcaliDash sync](obsidian://show-plugin?id=excalidash-sync) by _siredvin_

> 将库 Frontmatter 中的 Excalidraw 绘图同步至 ExcaliDash。

- [Second Brain Sync](obsidian://show-plugin?id=second-brain-sync) by _rahilp_

> 将笔记同步到 Cloudflare Workers 上自托管的 Second Brain MCP 服务器，在 Obsidian 内搜索第二大脑。

- [Blog Bridge](obsidian://show-plugin?id=blog-bridge) by _merrier_

> 将笔记同步至基于 GitHub 的 Markdown 静态博客，支持图片处理与发布状态追踪。

- [XGKB Sync](obsidian://show-plugin?id=cms-xgkb-sync) by _xgjk_

> 将笔记与玄关知识库进行同步。

- [GitHub Wiki](obsidian://show-plugin?id=github-wiki-sync) by _benpm_

> 用 Obsidian 编辑 GitHub Wiki 页面，实现双向同步与备份。

- [Vault Share](obsidian://show-plugin?id=vault-share) by _bobhy_

> 通过 Google Drive 在设备与用户间共享 Obsidian Vault。

- [IMA Sync](obsidian://show-plugin?id=ima-sync) by _cmzhangxin_

> 通过官方 OpenAPI 将笔记同步至腾讯 IMA 知识库。

- [Memos AI Sync+](obsidian://show-plugin?id=memos-ai-sync-plus) by _erbanku_

> 同步 Memos（v0.21 及更早版本）笔记，并可选 AI 增强。

- [Vault Sync (REST)](obsidian://show-plugin?id=vault-sync-rest) by _andrewboldi_

> 通过 REST API 与 GitHub 仓库双向同步，适用于 iOS 上因内存限制而无法使用 Git 协议的大型 Vault。

- [Vault Bridge SFTP](obsidian://show-plugin?id=vault-bridge-sftp) by _andrewkopylev_

> 通过自建的 SSH/SFTP 服务器在多设备间桥接 Vault，支持双向同步与冲突解决。

- [WiseMindAI Sync](obsidian://show-plugin?id=wisemindai-sync) by _chris_

> 在本地知识库与 WiseMindAI 之间双向导入并同步笔记、文档与知识库内容。

- [LJ OS](obsidian://show-plugin?id=lj-os) by _ljrobinson_

> 为日记生成独立的本地 Git 活动快照，用版本记录追踪每日变化。(Git 快照)

##### 📥 导入与导出

- [D&D Beyond Importer](obsidian://show-plugin?id=dndbeyond-importer) by _jktaisa_

> 将 D&D Beyond 的公开角色导入为排版精美的 Obsidian 笔记，适用于 TRPG 跑团。

- [Document Exporter](obsidian://show-plugin?id=document-exporter) by _rogerdigital_

> 将笔记、文件夹与查询结果导出为 Markdown 包、HTML 文档以及适合打印的格式。

- [DocDrop](obsidian://show-plugin?id=docdrop) by _flatulentfowl_

> 将文档、电子表格、图片等拖入库并自动转换为干净、可用的 Markdown 文件。

- [Import Fixer](obsidian://show-plugin?id=import-fixer) by _tonylee2016_

> 清理网页剪藏笔记，修复失效的资源链接并缩小过大的头像、图标。

- [Micro.blog Publisher](obsidian://show-plugin?id=microblog-publisher) by _bradbarrish_

> 通过 Micropub API 将笔记发布到 Micro.blog，支持草稿、分类与图片上传。

- [Xiaohongshu Importer Plus](obsidian://show-plugin?id=xhs-importer) by _lxl448080113_

> 导入小红书笔记，可配置默认文件夹、Frontmatter 字段、本地图片与视频链接。

- [Press PDF Export](obsidian://show-plugin?id=press-pdf-export) by _taylorchen_

> 基于 Pandoc 的高保真 PDF 导出，支持多种引擎、Mermaid 图表、自定义 CSS 与批量导出。

- [GetNote Importer](obsidian://show-plugin?id=getnote-importer) by _andyzhengyan_

> 将 GetNote 中的笔记、链接、录音与 AI 摘要同步到本地 Vault。

- [Book Exporter](obsidian://show-plugin?id=book-exporter) by _dsebastien_

> 将一个清单笔记及链接的章节笔记通过 Pandoc 导出为 EPUB 和 PDF。

- [Cross-App Notes Bridge](obsidian://show-plugin?id=advanced-import-export) by _cheng_

> 将笔记复制为可移植的 Markdown，并桥接至 Bear、WPS 云笔记、有道云笔记。

- [KOHi](obsidian://show-plugin?id=kohi) by _chiahsien_

> 将 KOReader 的高亮与笔记导入到库中。

##### 🗂️ 文件与附件管理

- [Agent File Pane](obsidian://show-plugin?id=agent-file-pane) by _philphilphil_

> 从文件资源管理器中隐藏 AGENTS.md 和 CLAUDE.md，并在专用侧边面板中集中列出，方便管理 AI 代理文件。

- [Linux Image Rendering Fix](obsidian://show-plugin?id=linux-image-rendering-fix) by _evgene-kopylov_

> 修复 Linux 下的图片渲染问题，确保 Ubuntu 等发行版中图片能够正确显示。

- [Vault Cleanup Dashboard](obsidian://show-plugin?id=wlunan-vault-cleaner) by _wlunan_

> 通过可视化仪表盘智能清理孤立文件与附件，支持定时自动清理和文件保护。

- [Show All Hidden Files](obsidian://show-plugin?id=show-all-hidden-files) by _anatoliykmetyuk_

> 在文件资源管理器中显示所有以点开头的隐藏文件与文件夹，一览无余。

- [Image To Lskypro Enhanced](obsidian://show-plugin?id=lskypro-auto-upload-enhanced) by _zgfdada_

> 将笔记中的本地与远程图片上传至 Lsky Pro，支持下载、右键菜单与进度展示。

- [Archive Redirect](obsidian://show-plugin?id=archive-redirect) by _semsevens_

> 将 Markdown 中的远程 URL 归档到本地，渲染时自动从缓存加载，保护链接资源。

- [Vault Inspector](obsidian://show-plugin?id=vault-inspector) by _rogerdigital_

> 扫描库中的断链、孤立附件、重复文件、Frontmatter 不一致等问题，充当库管家。

- [Smart Explorer](obsidian://show-plugin?id=smart-explorer) by _rogerdigital_

> 替代原生文件资源管理器，支持自定义排序、分组、过滤与轻量级预览。

- [Image Renamer](obsidian://show-plugin?id=image-renamer) by _kuioma_

> 根据可自定义模板和笔记属性，自动重命名粘贴的图片。

- [Copy Linked File](obsidian://show-plugin?id=copy-linked-file) by _flutterspike_

> 将链接或文件菜单项背后的实际文件路径/URL 复制到 Windows 剪贴板。

- [Copy Notes to Vault](obsidian://show-plugin?id=copy-notes-to-vault) by _rgomezjnr_

> 将笔记及其附件从一个库复制到另一个 Vault，方便多库迁移。

- [Smart Folder View](obsidian://show-plugin?id=smart-folder-view) by _sixtarocyan_

> 交互式文件夹仪表盘，提供时间线、看板视图与过滤、排序功能。

- [Recent Edits](obsidian://show-plugin?id=recent-edits) by _cwagner223355_

> 按天分组显示最近修改的文件，并标注由文件系统写入产生的编辑。

- [MiYo Hakobi](obsidian://show-plugin?id=miyo-hakobi) by _mmomm-org_

> 定时执行库与本地文件系统之间的导入/导出，自动搬运语音备忘等文件。

- [Copy Image Hotkey](obsidian://show-plugin?id=copy-image-hotkey) by _aliir74_

> 在源码模式下选中图片嵌入时，Cmd+C 直接复制实际图片文件。

- [Johnny.Decimal Manager](obsidian://show-plugin?id=johnny-decimal-manager) by _rzrabbi_

> 创建并管理 Johnny.Decimal 条目，在文件资源管理器中提供清晰的组织视图。

- [Copy Selected Name](obsidian://show-plugin?id=copy-selected-name) by _mikeddy_

> 将选中文件或文件夹复制为可编辑的 @提及，支持追加模式、历史记录与链接转换。

- [Image Hoist](obsidian://show-plugin?id=image-hoist) by _jcmexdev_

> 自动将库本地图片上传至 ImgBB，并替换为远程链接以优化仓库体积。

- [Folder Pin](obsidian://show-plugin?id=folder-pin) by _42milesz_

> 在默认文件资源管理器中将文件夹固定为标签页，方便快速访问。

- [Auto Refresh Explorer](obsidian://show-plugin?id=auto-refresh-explorer) by _mathieubonvaletpro-commits_

> 当外部同步工具在库中创建新文件时，自动刷新文件资源管理器。

- [Clear Unused Images Plus](obsidian://show-plugin?id=clear-unused-images-plus) by _puhhh_

> 清除库中未使用的图片，释放存储空间，是原有插件的增强分支。

##### 🎓 学术与研究

- [Pseudonymizer Tool](obsidian://show-plugin?id=pseudonymizer-tool) by _core-hn_

> 专为语言学与对话分析研究者设计，对互动转录稿进行匿名化与校正处理。

- [Scholar Sidekick — Cite from any identifier](obsidian://show-plugin?id=scholar-sidekick) by _mlava_

> 粘贴 DOI、ISBN 等标识符即自动替换为格式化引文，支持 10000+ 引文样式。

- [Scholia](obsidian://show-plugin?id=scholia) by _shashanyu_

> 导入学术 PDF，并预计算上下文感知的悬停术语解释。

- [Zotero Citations](obsidian://show-plugin?id=zotero-citations) by _westerngua_

> Zotero 引文管理，并支持通过 Pandoc 导出 Word 文档。

- [LineRef Copier](obsidian://show-plugin?id=lineref-copier) by _neves007_

> 复制适合 AI 阅读的 Markdown 位置索引，格式为文件路径加行号。

##### 🧠 知识管理

- [BP-Wiki Starter](obsidian://show-plugin?id=bp-wiki-starter) by _michael-uplive021_

> 创建双语入门级知识工作 Vault，内含 12 个模板、设置指南以及可选的升级路径。

- [OpenCode Links Graph](obsidian://show-plugin?id=opencode-links-graph) by _wlankasper_

> 将 @.opencode/... 引用视为 Obsidian 内部链接，在原生图谱中展示这些关联。

- [Outline for All Files](obsidian://show-plugin?id=all-outline) by _cemtan_

> 统一的侧边栏大纲面板，同时支持 Markdown 笔记与 PDF 文档。

- [Note Type](obsidian://show-plugin?id=note-type) by _koishiiko_

> 为笔记分配类型属性，并能在不同类型间快速切换。

- [New Note Title](obsidian://show-plugin?id=new-note-title) by _jessyco_

> 自定义新建笔记的默认文件名格式，融入日期、模板等变量。

- [Relations](obsidian://show-plugin?id=relations) by _obsidian-ttrpg-community, obsidian-ttrpg-community2_

> 可视化笔记之间的关系，适用于世界构建、小说、TRPG 战役、家谱等需要理清关联的项目。

- [Properties Filename](obsidian://show-plugin?id=properties-filename) by _gilles6_

> 当笔记属性变化时，自动据此重命名笔记文件名。

- [Thought Navigator](obsidian://show-plugin?id=thought-navigator) by _qingxuanlin-s_

> 可视化知识处理工作区，将卡片盒笔记法的思考编织为可导航的思维地图。

- [Harness Noting](obsidian://show-plugin?id=harness-noting) by _textcat_

> 创建作用域笔记规则，校验必需的属性、标题、文件名模式与文件夹结构。

- [Depends](obsidian://show-plugin?id=depends) by _aru_

> 管理跨文件依赖关系，并在原生图谱视图中直观展示。

- [Note Loom](obsidian://show-plugin?id=note-loom) by _pingzi-crypto_

> 将自由形式的笔记编织成具有自定义模板、字段、表格与清单的结构化笔记。

- [Graph Filter Builder](obsidian://show-plugin?id=graph-filter-builder) by _thalikbussacro_

> 通过结构化的包含/排除行构建图谱过滤器，支持标签、路径和文件名的自动补全。

- [File tag picker](obsidian://show-plugin?id=file-tag-picker) by _sameerbajaj_

> 在文件资源管理器右键菜单中管理标签，支持最近使用优先与多文件操作。

- [Contact Note](obsidian://show-plugin?id=contact-note) by _jalad_

> 将被指定为联系人的笔记属性转换为可视化名片，支持侧边栏浏览和数据库视图。

- [Daily Note Linker](obsidian://show-plugin?id=daily-note-linker) by _nhomble_

> 自动将每个新建的笔记链接到当天的日记。

- [Navigate Headings](obsidian://show-plugin?id=navigate-headings) by _rumcajsev_

> 在文件资源管理器中直接导航 Markdown 文件的标题及其结构。

- [Nodian](obsidian://show-plugin?id=nodian) by _akisantin_

> YAML 双向关系同步，自动在属性 字段中维护反向链接。

##### 🎨 界面与美化

- [Chancli Font Size Resizer](obsidian://show-plugin?id=chancli-font-size-resizer) by _mateosantosdev_

> 在状态栏快速增大或减小编辑器字体大小，方便调整阅读舒适度。

- [Folder Accents](obsidian://show-plugin?id=folder-accents) by _wrongvibe_

> 根据笔记所在文件夹自动变换主题强调色，用颜色区分不同知识区域。

- [SnipDock](obsidian://show-plugin?id=snipdock) by _joeraad_

> 通过状态栏菜单快速切换、创建、重命名或重载 CSS 代码片段，简化样式调试。

- [Hide Sidebars](obsidian://show-plugin?id=hide-sidebars) by _hasanyilmaz_

> 增强的侧边栏控制，支持自动隐藏模式、专用切换图标，可独立控制左右侧边栏。

- [Unique Tab Labels](obsidian://show-plugin?id=unique-tab-labels) by _stephencarboni_

> 通过在文件名前添加父文件夹名，让标签页的标题具有唯一性。

- [Colorful StickyNotes](obsidian://show-plugin?id=colorful-stickynotes) by _pandanocturne_

> 在库中创建彩色浮动便利贴，记录一闪而过的灵感。

- [Image Zoom](obsidian://show-plugin?id=image-zoom) by _liominsb_

> 轻量级图片查看增强，支持滚轮缩放与鼠标拖拽平移。

- [Kian's Tweaks](obsidian://show-plugin?id=kian-tweaks) by _dodgydave_

> 提供标题特效、矩阵风格锁屏与库编辑通知等个性化调整。

- [Unread Dot](obsidian://show-plugin?id=unread-dot) by _denmojo_

> 在文件资源管理器中为未读笔记标记蓝点，笔记打开后自动消失。

- [Notekeeper](obsidian://show-plugin?id=notekeeper) by _philemonchiro_

> 以 Google Keep 风格的卡片墙浏览 Vault，支持快速捕捉、置顶、着色与标签过滤。

- [Miku Hybrid](obsidian://show-plugin?id=miku-plugin-hybrid) by _bucknatt_

> 切换初音未来风格的主题模式与可选仪表盘小部件，内置混搭样式。

- [Default View Mode](obsidian://show-plugin?id=default-view-mode) by _co3mos_

> 通过笔记属性为每个笔记单独设置默认的视图模式（阅读或编辑）。

##### 💻 代码与开发

- [Custom Code Highlight](obsidian://show-plugin?id=custom-code-highlight) by _ydd0729_

> 为自定义或缺失的代码块语言提供可扩展的语法高亮，增强代码可读性。

- [LeetCode](obsidian://show-plugin?id=leetcode) by _likesundaylikerain_

> 在库内浏览、解答 LeetCode 题目并做笔记，将刷题与知识管理融为一体。

- [Live Preview](obsidian://show-plugin?id=live-preview) by _hxwguang_

> 通过本地 HTTP 服务器提供类似 VSCode 的实时 HTML 预览，并支持自动重载。

- [Scratchblocks](obsidian://show-plugin?id=scratchblocks) by _hayribakici_

> 渲染 Scratchblocks 代码块，将积木式编程的可视化效果带入笔记。

- [Safe JS](obsidian://show-plugin?id=safe-js) by _moritz-jung_

> 在沙盒化 Web Worker 中运行笔记自有的 JavaScript，兼顾可编程性与安全性。

- [Swagger JSON to Markdown](obsidian://show-plugin?id=swaggerjson-to-markdown) by _krontur_

> 将 Swagger/OpenAPI JSON 文件转换为 Swagger 风格的 Markdown，方便 API 文档记录。

- [HTML Docs](obsidian://show-plugin?id=html-docs) by _smcllns_

> 零依赖的极简插件，让 Obsidian 能够直接显示 HTML 文档。

- [Code View](obsidian://show-plugin?id=code-view) by _casualbot_

> 为源代码及开发者常用文件提供只读查看器，基于 Prism 实现语法高亮。

- [HTML Viewer](obsidian://show-plugin?id=html-viewer) by _jialinzhang24_

> 在沙盒视图中渲染 .html 文件，可开启脚本运行游戏、可视化或交互文档。

- [QuackBlocks](obsidian://show-plugin?id=quackblocks) by _yllucsyeoj_

> 基于 DuckDB WASM 的可执行 SQL 代码块，直接查询数据并行内渲染表格与图表。

- [Open in Zed](obsidian://show-plugin?id=open-in-zed) by _hauntedhost_

> 一键在 Zed 编辑器中打开当前 Vault、文件夹或笔记。

- [Concrete](obsidian://show-plugin?id=concrete) by _apokaliptics_

> 为 Markdown 笔记提供响应式变量系统，简化动态内容管理。

- [Vim Scrolling](obsidian://show-plugin?id=vim-scrolling) by _xlongfeng_

> 开启 Vim 模式后，为阅读视图增加 j/k、Ctrl+D/U、gg、G 等 Vim 风格滚动。

- [More Vim](obsidian://show-plugin?id=more-vim) by _colinlienard_

> 补充缺失的 Vim 功能，如环绕、多光标、scrolloff、gd、gx 等。

##### 🎵 多媒体

- [Audio Transcript](obsidian://show-plugin?id=audio-transcript) by _je-bh91_

> 使用 Gladia、Deepgram 或 AssemblyAI 将音频转录为带说话人识别的文本。

- [Recording Transcript Player](obsidian://show-plugin?id=recording-transcript-player) by _galeas_

> 播放录音时同步显示 SRT、VTT 和 DOTe 字幕转录稿，实现音文同步。

- [Smart Media Notes](obsidian://show-plugin?id=smart-media-notes) by _nchuyj_

> 集成时间戳、字幕导入、录音与媒体浏览器的智能媒体笔记，强化音视频管理。

- [OK Standby Jukebox](obsidian://show-plugin?id=ok-standby-jukebox) by _aul-dox_

> 将音乐源 URL 与资源导入歌曲笔记，在库里建立专属点唱机。

- [手写笔记](obsidian://show-plugin?id=handwriting-notes) by _jasonsting622-netizen_

> 类似 Apple Notes 的手写体验，支持触控笔与手指书写。

- [Lyrio - Song Helper](obsidian://show-plugin?id=lyrio) by _whitte-h_

> 自动同步歌曲段落（如副歌、主歌、桥段等）到整个笔记。

##### 🌐 语言与翻译

- [Nodte Translator](obsidian://show-plugin?id=nodte-translator) by _nodevcg_

> 一款实用的笔记翻译工具，直接在编辑器中翻译内容。

- [Mouse Tooltip Translator](obsidian://show-plugin?id=mouse-tooltip-translator) by _toki1703_

> 灵感源于同名 Chrome 扩展，鼠标悬停即可翻译文本，结合 AI 与侧边栏提升阅读体验。

- [Custom Translate](obsidian://show-plugin?id=custom-translate) by _liwbcraft_

> 通过本地 API 翻译选中文本，并管理个人专属词汇库。

- [Fingertip Translation](obsidian://show-plugin?id=fingertip-translation) by _amos_

> 选中即译，支持必应词典、有道、MyMemory 及内置发音，指尖完成翻译。

- [L10n.dev - AI Translator](obsidian://show-plugin?id=note-ai-translator) by _antonovanton, l10n-dev_

> 使用 AI 将笔记翻译为 165 种语言，保留 Markdown 格式与结构。

- [CJK Cross-Script Search](obsidian://show-plugin?id=cjk-cross-search) by _sai1047976_

> 利用 OpenCC 扩展简繁中文查询，输入“萬維鋼”也能搜到“万维钢”。

##### 🔒 安全与加密

- [PhantomCipher](obsidian://show-plugin?id=phantom-cipher) by _lumingtianze_

> 基于 Argon2id + AES-GCM 的高性能透明全数据库加密方案，保护文件安全。

- [Cloud KMS Encryption](obsidian://show-plugin?id=cloud-kms-encryption) by _viktoruj_

> 使用 AWS KMS 对秘密块与二进制文件进行透明加密，磁盘上不留明文。

- [Folder Crypto](obsidian://show-plugin?id=folder-crypto) by _jasonsting622-netizen_

> 锁定文件夹并可选择性地加密其中的 Markdown 文件，保护隐私。

- [Password Manager](obsidian://show-plugin?id=password-manager) by _pandanocturne_

> 轻量级本地密码管理器，支持加密、备份、回收站及导入/导出。

##### 🔍 搜索与导航

- [Embedded-Omnisearch](obsidian://show-plugin?id=embedded-omnisearch) by _fozi_

> 基于 Omnisearch 的行内搜索界面，可自定义高亮颜色与透明度。

- [Tag Fuzzy Find](obsidian://show-plugin?id=tag-fuzzy-find) by _etaiso_

> 快速模糊搜索库中的标签，并跳转到使用该标签的笔记。

##### 📚 学习与记忆

- [Simple Flashcards](obsidian://show-plugin?id=simple-flashcards) by _clancyj11_

> 提供类似 RemNote 的行内抽认卡语法，并支持可选的间隔重复复习。

- [Chess Puzzles](obsidian://show-plugin?id=chess-puzzles) by _yan-vieira_

> 在 Markdown 中编写国际象棋谜题，并用间隔重复进行复习。

- [Lexophile - Personal Dictionary](obsidian://show-plugin?id=lexophile) by _bryanmanio_

> 逐词构建个人词典，可手动添加或通过 Chrome 扩展、Kobo 导入器即时抓取。

- [Caissa](obsidian://show-plugin?id=caissa) by _ekrizdis367_

> 在库中研究国际象棋，嵌入棋局、开局、残局，并探索 Lichess 数据。

- [Chess Vault](obsidian://show-plugin?id=chess-vault) by _dun8_

> 将 Lichess 对局同步到库中。

##### 🔗 特定集成与服务

- [bangumi](obsidian://show-plugin?id=bangumi-note) by _kuanphough_

> 将 Bangumi 的收藏与剧集进度同步到笔记中，方便追番记录。

- [Multimuse Tracker](obsidian://show-plugin?id=multimuse-tracker) by _teaos_

> 配合 Discord 中的 MultiMuse 机器人，实现角色扮演数据的同步与导入。

- [Sherlockeye OSINT](obsidian://show-plugin?id=sherlockeye-osint) by _p1ngul1n0_

> 集成 Sherlockeye OSINT API，在 Obsidian 内进行自动化情报收集。

- [Spotify Sorter](obsidian://show-plugin?id=spotify-sorter) by _fleker_

> 找出未被歌单收录的“红心”歌曲并保存为笔记，整理 Spotify 音乐库。

- [Sync Trakt](obsidian://show-plugin?id=sync-trakt) by _o1xhack_

> 将 Trakt.tv 的观看清单、历史、收藏与评分同步为 Markdown 笔记，包含详细时间戳。

- [Chronicle](obsidian://show-plugin?id=chronicle) by _cubiclewar_

> 通过你看过的影视和读过的书籍来编年记录生活。

- [Anotum](obsidian://show-plugin?id=anotum) by _anotum_

> 将 Anotum 中的高亮与笔记同步到 Obsidian 中。

- [MTG Deck](obsidian://show-plugin?id=mtg-deck) by _sboulema_

> 在笔记中展示你的万智牌套牌与牌表。

- [WatchLog](obsidian://show-plugin?id=watchlog) by _shynkro_

> 追踪动漫、电影和电视剧，支持剧集跟踪、进度统计、上新提醒与嵌入式小组件。

- [Wallet Blockies](obsidian://show-plugin?id=wallet-blockies) by _geeknees_

> 为以太坊钱包地址显示行内的 blockie 身份图标。

##### ☯️ 易学与玄学

- [子平](obsidian://show-plugin?id=ziping) by _dyse-sofqi_

> 子平八字排盘插件，在 Obsidian 中展示生辰八字信息。

- [Liuyao](obsidian://show-plugin?id=liuyao) by _kasukabe-tsumugi_

> 从围栏代码块中渲染六爻卦象，为易学笔记提供可视化支持。

##### 📌 其他实用工具

- [Ballistics](obsidian://show-plugin?id=ballistics) by _jheddings_

> 在笔记中嵌入弹道数据表格，满足专业领域的科学记录需求。

- [Copy Text Protocol](obsidian://show-plugin?id=copy-text-protocol) by _jldiaz_

> 通过自定义协议将文本复制到剪贴板，丰富链接与自动化的可能性。

- [UniRate Currency](obsidian://show-plugin?id=unirate-currency) by _unirate-api_

> 行内显示实时与历史汇率，支持 170+ 法币与加密货币的直接换算。

- [cashlog](obsidian://show-plugin?id=cashlog) by _uuq007_

> 个人财务管理插件，支持多账户、转账、预算、目标设定与图表可视化。

- [Kaper](obsidian://show-plugin?id=kaper) by _nikoneex_

> 以行内结构块编辑和预览 Kaper 食谱，方便烹饪记录。

#### 更新

[Easy Copy](obsidian://show-plugin?id=easy-copy) By _Moy_

> - **1.6.4**：仅用于重新触发插件审查，无实质功能更新。
> - **1.6.3** (2026-05-15)：
>   - 维护：移除 `builtin-modules` 和 `dotenv` 依赖后同步更新 pnpm lockfile。
> - **1.6.2** (2026-05-15)：
>   - 维护：为 `main.js` 和 `styles.css` 发布产物添加 GitHub Artifact Attestation 加密溯源证明；
>   - 修复所有 Obsidian 插件 linter 警告。
> - **1.6.1** (2026-05-12)：
>   - 新增：
>     - 代码块复制：光标位于代码块内时，智能复制命令直接复制代码块内容，不再误触发块 ID 生成；
>     - 代码块复制行为设置：新增“Code Block”设置分组，可选择：
>       - 复制纯文本（默认）：仅复制代码内容，不含围栏行；
>       - 复制代码块（含围栏）：复制完整代码块，包括开头的 ` ```lang` 和结尾的 ` ``` ` 行；
>       - 生成块链接：沿用原有块 ID 生成逻辑；
>       - 禁用：跳过代码块检测。
> - **1.6.0** (2026-05-09)：
>   - 新增：
>     - 粘贴时链接路径解析：启用“Resolve link path on paste”后，粘贴时根据目标文件位置重新生成链接路径：
>       - 跟随 Obsidian 设置时，使用仓库配置的路径风格（最短/相对/绝对）；
>       - 使用明确的 Wiki/Markdown 格式时，仅使用最短唯一路径；
>       - 同文件内粘贴标题自动简化（如 `[[#Setup]]` 而非 `[[MyProject#Setup]]`）。
>   - 修复：
>     - `simplifiedHeadingToNoteLink` 设置现在正确控制链接简化逻辑。
>   - 变更：
>     - 提取 `copyMetadata.ts` 和 `pasteResolution.ts` 为纯函数模块，完整测试覆盖；
>     - 新增 98 个测试（总计 184 个）。

[Decks](obsidian://show-plugin?id=decks) By _dscherdi_

> - 1.6.4（2026-04-26）
>   - 备份恢复新增支持卡组配置与标签映射关系
>   - 新增卡组进度重置功能，可清空复习记录并恢复为新卡片状态
>   - 增加重置操作二次确认弹窗
> - 1.7.0（2026-04-27）
>   - 新增自定义卡组功能，支持手动选卡、规则自动生成两类卡组
>   - 全新卡片管理器，支持跨卡组模糊搜索、标签分组筛选
>   - 标签分组支持子标签自动纳入复习范围
>   - 界面全面适配 Obsidian 原生设计风格
>   - 修复分栏复习模式进度条显示异常问题
> - 1.7.1（2026-04-28）
>   - 修复复习模式快捷键抢占其他面板输入焦点的问题
> - 1.7.2（2026-04-28）
>   - 整体复习界面 UI 改版，优化文字对比度与按钮配色
>   - 窄屏设备自动适配 2×2 评分按钮布局
>   - 优化卡片内外边距、分割线样式，适配明暗主题
>   - 修复长列表、代码链接等内容换行异常问题
>   - 修复弹窗关闭按钮被卡片内容遮挡问题
> - 1.7.3（2026-04-29）
>   - 浏览模式新增搜索快捷切换器，支持模糊匹配卡片正反面
>   - 全局搜索统一采用 Obsidian 原生模糊算法，减少误匹配
>   - 移除内置自定义检索逻辑，提升性能与一致性
> - 1.7.4（2026-04-29）
>   - 支持为单张卡片添加独立标签，标签自动同步至 Obsidian 标签面板
>   - 标题/表格/反向卡片均自动继承上级标签
>   - 仅修改标签不会重置卡片复习进度
>   - 筛选器新增卡片标签条件，支持精准标签匹配建卡组
>   - 卡片管理器新增标签列与标签筛选功能
>   - 数据库升级新增卡片标签字段，兼容新旧备份恢复
> - 1.7.5（2026-04-30）
>   - 侧边栏搜索栏默认折叠，点击图标展开
>   - 输入框自动聚焦，ESC 键可一键清空并收起
>   - 保留历史搜索关键词，折叠后不丢失
>   - 移除标签下拉联想框，采用原生简约样式
> - 1.7.6（2026-05-02）
>   - 新增复习撤销按钮，支持快捷键 Ctrl/Cmd+Z 回退评分
>   - 撤销可精准恢复卡片所有 FSRS 复习参数
>   - 支持连续多次撤销，仅限定当前复习会话
> - 1.7.7（2026-05-04）
>   - 全面对齐 FSRS-6 官方算法公式
>   - 修复卡片答错后稳定性异常增高问题
>   - 修复难度均值回归计算偏差
>   - 算法校准误差控制在 1% 以内，不改动现有卡片数据
> - 1.8.0（2026-05-07）
>   - 新增个性化 FSRS 参数训练，基于个人复习记录生成专属记忆曲线
>   - 训练全程本地离线，无需服务器与数据上传
>   - 支持训练前后效果对比，可应用或放弃参数
>   - 每个卡组配置可独立选择标准/强化/训练三种 FSRS 模式
>   - 底层优化训练算法，匹配官方开源实现
> - 1.8.1（2026-05-09）
>   - 新增卡片健康状态检测，识别遗忘过多、内容过长卡片
>   - 可配置遗忘阈值、文字长度阈值，支持筛选专用卡组
>   - 卡片管理器与复习弹窗展示健康状态标识
>   - 重构卡片管理器，改用表头点击排序、全新筛选器
>   - 支持直接在管理器内编辑自定义卡组规则与卡片
>   - 优化筛选标签样式、弹窗高度自适应
> - 1.9.0（2026-05-13）
>   - 重构跨设备增量同步机制，引入 mtime 时间戳校验
>   - 基于 HLC 逻辑与同步日志实现多设备状态一致
>   - 支持自定义数据库、备份、同步文件存储路径
>   - 新增数据库手动恢复入口，优化备份服务
>   - 清理实验性功能配置，精简设置面板
> - 1.9.1（2026-05-13）
>   - 补齐多设备同步短板
>   - 复习撤销操作跨设备实时同步
>   - 卡组进度重置全设备统一生效
>   - 自定义卡组批量移除卡片支持跨设备同步
>   - 修复时间戳赋值错误导致同步覆盖冲突
> - 1.9.2（2026-05-14）
>   - 全面优化卡组列表加载速度，打开无延迟
>   - 后台静默同步，不阻塞界面操作
>   - 复习返回无需全量刷新，实时展示本地进度
>   - 同步中按钮旋转提示状态，直观可见
>   - 复习热力图实时更新，无需重载面板
>   - 列表渐入动画、数值局部刷新，减少闪烁
>   - 并行计算卡组统计，大幅提升大库加载速度
> - 1.9.3（2026-05-14）
>   - 修复标题带标签时跳转定位异常问题
> - 1.9.4（2026-05-14）
>   - 支持置顶任意卡组/卡组分组，跨设备同步
>   - 置顶分组独立排序，不打乱原有列表顺序
>   - 表格卡片精准定位源文件，修复同文本匹配错误
>   - 复习跳转适配阅读/实时预览双模式滚动接口
>   - 重构源文件导航模块，增加单元测试覆盖
> - 1.9.5（2026-05-15）
>   - 更换卡组配置后自动重新解析卡片规则
>   - 修复仅调度生效、规则不刷新的历史遗留问题
>   - 新增行为通知默认关闭，可手动开启
> - 1.9.6（2026-05-15）
>   - 卡组列表表头支持点击升降序排序
>   - 新增低数量卡组自动隐藏配置，支持置顶豁免
>   - 排序规则、隐藏配置跟随设备同步
>   - 优化表头点击高亮、列表文字对齐细节
> - 1.9.7（2026-05-15）
>   - 重构入门引导笔记，优化使用说明可读性
> - 1.9.8（2026-05-17）
>   - 卡片自动继承上级标题所有标签，自动去重合并
>   - 面包屑导航自动剔除标签符号，界面更整洁
>   - 修复复习后自定义卡组消失、计数错乱问题
> - 1.9.9（2026-05-17）
>   - 卡片管理器支持在新标签页打开，可自由拖拽分栏/弹窗
>   - 编辑自定义卡组时，已选卡片固定置顶
>   - 分组内保留表头排序规则，搜索不打乱布局
>   - 编辑时锁定置顶分组，避免卡片光标跳动当前文件内容过长，豆包只阅读了前 90%。

[Any Block](obsidian://show-plugin?id=any-block) By _any-block_

> - 3.4.9 (2026-05-16)
>   - 功能优化
>     - 进一步精简最低适配版本，压缩整体体积
>     - 优化 Obsidian 应用评分相关配置
>   - 问题修复
>     - 修复 Obsidian 实时模式无法正常渲染内容的问题
> - 3.4.8 (2026-05-16)
>   - 项目维护
>     - 优化 Obsidian 应用评分相关配置
>     - 修复核心模块拆分后，自动审查无法识别核心模块类型的问题
> - 3.4.5 (2026-05-14)
>   - 问题修复
>     - 修复 mdit 选择器在文档首行失效的问题
>   - 文档调整
>     - 修正多处文档内容错误
>     - 搭建在线浏览环境方便查阅文档，该环境暂不支持图片加载
>   - 代码重构
>     - 升级别名系统，支持专业版别名功能
>     - 重构 mdit 模块，严格区分 Node 端独立资源
>     - 将国际化模块从主程序迁移至核心模块

[YOLO](obsidian://show-plugin?id=yolo) By _lapis0x0_

> 1.5.7 | 2025-05-03：焦点同步；PDF 图像读取、模态按需切换、自动去图、区域截图、选区同步；Quick Ask 与侧边栏 Chat 功能对齐，修复上下文注入、引用弹窗问题；新增智谱 AI，统一网页抓取器，聊天工具过滤改为黑名单；输出 Token 上限 384K，标题优化，服务商排序修复，Cursor Chat 闪烁修复。
>
> 1.5.7.1 | 2025-05-04：新增外部 Agent 派遣工具；移除默认超时，实时显示终端日志；优化 Claude Code 流式输出；支持异步派遣；修复工作目录问题，重设计工具卡片；修复历史对话自动置顶、启动性能、新标签页入口无响应问题。
>
> 1.5.7.2 | 2025-05-06：重写配置持久化，同步并入 Obsidian 原生；修复自定义嵌入维度；修复 MCP 超时/崩溃、开关竞态问题；新增 Windows 外部 Agent 支持；延迟知识库加载，优化工具调用动画，新增用户消息悬浮操作栏。
>
> 1.5.7.3 | 2025-05-06：优化用户消息悬浮操作栏（悬浮显示，不撑开布局，无滚动抖动）。
>
> 1.5.7.4 | 2025-05-06：Agent 编辑器工具分组“全部启用/停用”快捷按钮；Token 成本可视化；模块级 Token 缓存；修复弹窗布局；优化工具页 UI，修复开关样式。
>
> 1.5.7.5 | 2025-05-10：Gemini/Claude 原生 PDF 输入；修复 PDF Token 估算；PDF 文本持久缓存；取消消息历史截断；自动匹配 MessageAdapter；优化全量上下文提示；Tab 补全视觉反馈、退格键修复，移除标签页标题开关。
>
> 1.5.8 | 2025-05-12：项目指令、任务清单、主动提问工具；Agent 运行时消息排队；合并发送/停止按钮；修复消息列表遮挡；“工具类型”重命名，修复 PDF 降级、OpenRouter 嵌入列表问题；新增 Tab 补全推理强度；清理历史命名。
>
> 1.5.8.1 | 2025-05-13：扩展 Provider 内置工具；修复 Gemini MCP 400 错误、标题生成问题；新增配置导入导出、技能批量导入删除、嵌入并发限制；优化提问工具，默认 Agent 模式，重设计助手切换器；修复输入模态提示。
>
> 1.5.8.2 | 2025-05-14：重设计添加 Provider 面板；重构 Gemini 传输层，修复 400 错误；桌面端 Auto 传输优先 Node Fetch；优化提问工具；视觉优化助手切换器、模型选择弹窗；Cursor Chat 命令注册为 Obsidian 原生命令。
>
> 1.5.8.3 | 2025-05-15：Agent 多轮 Token 累计统计；重设计 Token 用量面板；聊天输入分层菜单、快捷指令管理；Cursor Chat 命令单独指定助手；修复选区高亮；新增小米 MiMo 渠道。

## PKMer 出品

> [!INFO]
> **PKMer**（[PKMer.cn](https://pkmer.cn/)、[PKMer.net](https://pkmer.net/)）旨在打造东半球强大的知识管理社区。Personal Knowledge Management (PKM) + "er"，其中 "er" 表示人，专注、喜爱个人知识管理工作、追求效率的人们，都可以划入这个行列，希望社区凝聚更多这样的人。

### Editing Toolbar 更新至 [v4.0.8](https://github.com/PKM-er/obsidian-editing-toolbar/releases/tag/4.0.8)

- 国际化部分字段，ai 能力全面放开
- 白板输入面板支持双链

### Media Extended 更新至 [v4.2.4](https://github.com/aidenlx/media-extended/releases/tag/4.2.4)

- v4.2.4
  - 新增功能
    - 命令面板快捷复制时间戳
      - 此前版本推出的时间戳复制子菜单，现已独立为命令面板专属快捷指令，涵盖全部常用格式，可自定义快捷键实现一键复制
      - 支持为笔记库内文件、本地外部文件生成附带时间节点的跳转链接，适配桌面端与移动端使用场景
      - 新增媒体库专属链接格式，凭借媒体库唯一标识生成链接，源文件移动、重命名后链接依旧有效
      - 系统会自动屏蔽当前媒体类型无法适配的时间戳格式选项
    - 链接协议功能优化
      - 通用文件打开链接新增时间定位与哈希定位参数，点击可直接跳转至媒体指定播放位置，非媒体文件不受改动影响
      - 媒体专属打开链接新增多项自定义参数，可指定目标笔记库、窗口打开形式、强制锁定播放时间点
      - 可组合参数制作深度跳转链接，精准实现指定媒体在指定位置、指定窗格定位播放
    - 媒体笔记命名规则调整
      - 媒体笔记优先读取视频元数据、音频标签、文件名称作为笔记名，无有效标题则使用默认命名格式
      - 出现同名媒体笔记时，采用专属后缀区分，摒弃传统数字序号递增命名方式
    - 视频逐帧播放控制
      - 新增单步上一帧、单步下一帧操作指令
      - 支持绑定快捷键，长按按键可持续逐帧切换视频画面
      - 适配本地播放器以及主流网页视频播放平台
      - 通过微调播放时间实现近似逐帧切换，适配浏览器原生播放限制
    - 播放器快速唤起媒体笔记
      - 内嵌播放器右键菜单增加媒体笔记入口，可直接跳转已有笔记，也可一键新建空白笔记，无需退出播放界面
  - 问题修复
    - 修复哔哩哔哩分集视频，无法展示对应分集专属标题，统一显示原始总视频标题的错误
- v4.2.3
  - 新增功能
    - 媒体库配置项新增封面图导入开关，关闭后新增媒体资源时，不再自动保存内嵌封面图与网络缩略图，手动截取画面设置封面不受限制
  - 问题修复
    - 修复关闭播放至视频末尾功能后，时间戳编辑栏结束时间显示乱码异常，无原始结束时间可自动归零重置
    - 修复格式错误的本地文件链接无法正常加载播放，现已交由软件默认链接规则处理
- v4.2.2
  - 新增功能
    - 完成简体中文界面本地化适配
  - 问题修复
    - 修复文稿纯文本复制出现大量多余空行的问题，同段落内容连贯排版，仅用单行空行区分不同段落
    - 修复文稿搜索无法定位视野外首个匹配内容，优化跳转逻辑，搜索结果可瞬间精准定位并取消多余动效
- v4.2.1
  - 问题修复
    - 优化低传输速率设备的网页视频播放器适配性，解决初始化通信异常中断问题，大幅改善哔哩哔哩冷启动加载稳定性
    - 修复时间戳插入、截图保存错误写入无关媒体笔记，或是直接被拦截阻断的问题，自动筛选匹配笔记并正常创建打开目标笔记
    - 修复暂停状态下网页视频点击时间戳链接仅定位画面、无法自动播放的问题，同步本地播放器播放逻辑，可添加参数关闭自动播放
    - 修复本地媒体标准格式链接触发地址无效报错，无协议本地链接统一走内部链接解析通道
    - 修复清空媒体文件夹路径设置后，截图保存、字幕下载功能失效，空白路径默认自动指向笔记库根目录
    - 修复浏览器跨域权限拦截远程媒体资源后，无法读取音频标签、视频基础元数据的故障

### Thino 更新至 [v3.0.12](https://github.com/Quorafind/Obsidian-Thino/releases/tag/3.0.12)

- 修复：ios 剪贴板复制的问题
- 修复：Focus 主题下的样式问题

### Zotlit 更新至 [v1.1.12](https://github.com/aidenlx/zotlit/releases/tag/1.1.12)

- 感谢！支持 Zotero 8+ 的原生 CiteKey。
- 支持最新版本的 Obsidian 安装程序以及未来最高至 Electron 41 的版本。

## PKM 相关知识推荐

> [!INFO]
> 欢迎收藏 [PKMer 导航页](https://pkmer.cn/link/)，一键直通 PKMer 各社交平台账号，与热爱分享与知识管理的同好们交流，第一时间获取行业新鲜资讯！

[PKMer_Dataviewjs 交互式文件夹层级导航 by AnyBlock]( https://pkmer.cn/show/20260504232013 )

> 通过 **Dataviewjs** 结合 **AnyBlock 插件**，实现了一个**交互式的文件夹层级导航系统**。可以在 Obsidian 中以多种视图模式浏览、切换和探索整个知识库的文件夹结构。

![260504_Dataviewjs：交互式文件夹层级导航 by AnyBlock](https://cdn.pkmer.cn/images/File-20260504101705835.gif)

> [!Warning] 声明
> 本栏目致力于为广大 Obsidian 中文用户汇总全面的官方资讯与插件、外观动态。为了保持信息的全面性，我们的**收录并不等同于推荐**，还请各位用户知悉并理解，根据自身需求进行判断和选择。
