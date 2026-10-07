<div align="center">

# daily-repos

每日优质仓库 · Notable repositories

惊霓日录 · Jingni Daily

[最新 Latest](#最新--latest) · [关于 About](#关于--about) · [怎么读 How to read](#怎么读--how-to-read) · [目录 Index](#目录--index) · [同系列 The series](#同系列--the-series)

</div>

## 最新 · Latest

## 2026-10-07

- [morluto/rea](https://github.com/morluto/rea)
  - 中文：缺证据记 unknown、不算通过；重建检查把证据、限制、未知分开交回
  - English: Missing evidence is unknown and does not pass; reconstruction checks return evidence, limits, and unknowns separately.

- [AgentMemoryRepo/agentmemoryrepo](https://github.com/AgentMemoryRepo/agentmemoryrepo)
  - 中文：Cognition 的 Agent Memory Repo 规范：git 管记忆，每条带 source（不并 claude-mem）
  - English: Cognition's Agent Memory Repo spec: git-managed memory with a source on each entry (not merged with claude-mem).

- [elstongun/leviathan](https://github.com/elstongun/leviathan)
  - 中文：大数据集检索记忆；比每问 token 和最坏情况，组名不清就退出码 3
  - English: Retrieval memory for large datasets; compare per-query tokens and worst case; unclear group names exit with code 3.

- [StayLameBro/backburner](https://github.com/StayLameBro/backburner)
  - 中文：iPhone 帮 Mac 跑本地 27B；验收是贪心输出逐 token 一致
  - English: iPhone helps a Mac run a local 27B; acceptance is greedy output matching token-by-token.

- [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)
  - 中文：模型只写内容、skill 渲染 HTML；自报重配置下省钱有限
  - English: The model writes content only; a skill renders HTML—self-reported savings under reconfiguration are limited.

- [storytold/photocraft](https://github.com/storytold/photocraft)
  - 中文：命令表统一供 CLI/JSON/MCP；自称 early alpha，不当成熟产品
  - English: One command table for CLI/JSON/MCP; self-described early alpha, not a mature product.

- [OpSafari/hypoarena](https://github.com/OpSafari/hypoarena)
  - 中文：先用埋答案数据验证评测流水线本身（个人项目，不当基准）
  - English: Validate the eval pipeline itself on planted-answer data first (personal project, not a benchmark).

- [deepseek-ai/DeepGEMM](https://github.com/deepseek-ai/DeepGEMM)
  - 中文：张量核实现；训练侧判断归 Mira
  - English: A tensor-core implementation; training-side judgment belongs to Mira.

- [alchaincyf/huashu-art-motion](https://github.com/alchaincyf/huashu-art-motion)
  - 中文：动画 skill：能写代码的部分用代码，人物才用生成帧（AIGC·动画）
  - English: Animation skill: use code where possible; generative frames only for characters (AIGC·animation).


## 2026-10-05

- [tester-army/e2e](https://github.com/tester-army/e2e)
  - 中文：agent 驱动 e2e，断言通过后录制、零模型回放。
  - English: Agent-driven e2e: record after assertions pass, then replay with zero model calls.

- [pingdotgg/t3code](https://github.com/pingdotgg/t3code)
  - 中文：统一遥控本机多家 agent CLI 的控制面（不并 paperclip）。
  - English: A control plane that remotes many local agent CLIs (not merged with paperclip).

- [garrytan/gstack](https://github.com/garrytan/gstack)
  - 中文：角色化 Claude Code skill 套件样本（生产力数字是自报）。
  - English: A role-based Claude Code skill suite sample (productivity numbers are self-reported).

- [zai-org/ZCode](https://github.com/zai-org/ZCode)
  - 中文：Z.ai 官方开源编程 harness，可读运行时结构。
  - English: Z.ai's official open coding harness with a readable runtime structure.

- [browser-use/jev-ultrafast](https://github.com/browser-use/jev-ultrafast)
  - 中文：缩小动作空间的快浏览器 agent（依赖托管 API）。
  - English: A fast browser agent with a shrunk action space (depends on a hosted API).

- [antirez/ds4](https://github.com/antirez/ds4)
  - 中文：antirez 的窄而深本地推理引擎，带 agent 与评测。
  - English: antirez's narrow-and-deep local inference engine, with agents and evals.

- [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)
  - 中文：出可制造 CAD 文件的 Skills 库（AIGC·3D）。
  - English: A Skills library that emits manufacturable CAD files (AIGC·3D).

- [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
  - 中文：先选管线再调工具的视频 agent（AIGC·视频）。
  - English: A video agent that picks the pipeline first, then tools (AIGC·video).

- [microsoft/thinkingbox](https://github.com/microsoft/thinkingbox)
  - 中文：按后端终态判分的 agent 评测框架（不并 e2e，不并 IBM 过程级评测，不并 Raven）。
  - English: An agent eval framework scored on backend final state (not e2e, not IBM process-level eval, not Raven).

- [microsoft/thinkingbox-data](https://github.com/microsoft/thinkingbox-data)
  - 中文：ThinkingBox 的场景和工具服务数据，许可证不是标准 SPDX。
  - English: ThinkingBox scenario and tool-service data; the license is not standard SPDX.

- [huggingface/OpenEnv · thinkingbox_env](https://github.com/huggingface/OpenEnv/tree/main/envs/thinkingbox_env)
  - 中文：跑 ThinkingBox 的环境，不把整个 OpenEnv 当新方法。
  - English: The env that runs ThinkingBox—do not treat all of OpenEnv as a new method.

- [google-research/rrsi](https://github.com/google-research/rrsi)
  - 中文：自改进时防背测试的可装对照（论文数字归 Mira，不闭合自进化）。
  - English: An installable control against backtesting during self-improvement (paper numbers belong to Mira; it does not close self-evolution).

- [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness)
  - 中文：DeepSeek 官方插件式 harness（不并 ZCode，内部组件仓不单收）。
  - English: DeepSeek's official plugin-style harness (not ZCode; internal component repos are not filed alone).

- [Niko1221/Strata](https://github.com/Niko1221/Strata)
  - 中文：消费级卡上的本地推理引擎（不并 ds4）。
  - English: A local inference engine for consumer GPUs (not merged with ds4).

## 关于 · About

可装的仓库、Agent Skill 和 Harness 放这里。星数核对过再入。

Installable repositories, agent skills, and harnesses. Star counts are checked before filing.

**不收 Left out.** 教程和路线去 daily-guides。论文、资讯、访谈不进这本。 Tutorials and learning paths go to daily-guides. Papers, news, and interviews stay out.

## 怎么读 · How to read

首页只做目录，当天的条目在 [years/](years) 里，新的日期在上面。一条里，标题就是链接，下面各一句中文和英文。

The front page is the index. A day's entries live in [years/](years), newest date first. The title is the link. Under it, one sentence in Chinese and one in English.

版式长这样。下面不是一条真记录。

The shape looks like this. The block below is not a real entry.

> **2026-01-01**
>
> - [标题放这里 Title goes here](#怎么读--how-to-read)
>   - 中文一句，只说为什么留。
>   - One English sentence on why it stays.

同一天同一个链接只留一次。

The same link is kept once on a given day.

## 目录 · Index

| 年 Year | 档案 File |
| --- | --- |
| 2026 | [years/2026.md](years/2026.md) |

## 同系列 · The series

| 仓库 Repo | 中文 | English |
| --- | --- | --- |
| [daily-papers](https://github.com/Walksu/daily-papers) | 论文精选 | Papers |
| [daily-repos](https://github.com/Walksu/daily-repos) | 优质仓库 | Repositories |
| [daily-guides](https://github.com/Walksu/daily-guides) | 教程与路线 | Guides |
| [daily-brief](https://github.com/Walksu/daily-brief) | 资讯 | Briefing |
| [daily-voices](https://github.com/Walksu/daily-voices) | 访谈与播客 | Voices |
| [daily-essays](https://github.com/Walksu/daily-essays) | 本人博客 | Essays |
| [daily-signals](https://github.com/Walksu/daily-signals) | 机构与学者信号 | Signals |
