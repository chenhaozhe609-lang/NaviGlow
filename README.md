# Navigrow Workspace

这个仓库用于管理 2026 Roland Berger x L'Oreal China Case Competition 初赛工作材料。

## 当前状态

- 当前阶段：初赛。
- 当前品牌选择：YSL Beauty，已锁定。
- 当前战略定位：YSL Beauty as China's Gen Z high-end self-expression co-creator。
- 当前正文结构：8 页 PPT 主体。
- 当前远端仓库：`https://github.com/chenhaozhe609-lang/NaviGlow.git`。
- 当前核心原则：把 AI 作为品牌关系基础设施，而不是单点产品功能。

## 最重要入口

- `rounds/preliminary/README.md`：初赛总控台，下一次对话优先读这里。
- `rounds/preliminary/task-files/analysis/competition-context.md`：赛题要求、评审标准、提交要求。
- `rounds/preliminary/meeting-notes/meeting-summaries/official-livestream-problem-solving-guide-2026-07-03.md`：官方破题指南整理。
- `rounds/preliminary/decision-records/strategy-direction/decision-brand-positioning-ysl-beauty.md`：选择 YSL Beauty 的决策记录。
- `rounds/preliminary/decision-records/strategy-direction/decision-slide-structure-standard-8-pages.md`：8 页结构决策记录。
- `rounds/preliminary/slides/information-architecture/ysl-slide-information-architecture-zh.md`：当前 slide story 和信息架构。
- `rounds/preliminary/slides/deliverables/current/ysl-slide-02-03-current.html`：当前已采用的 Slide 2-3 HTML 原型。

## 目录规则

- `rounds/`：所有比赛轮次材料。
- `.agents/`：项目本地 skills，用于复用工作流。
- `.codex/`：本地 Codex 状态，已忽略，不进入 Git。
- `rounds/**/temporary/`：临时脚本、浏览器缓存、中间截图，已忽略，不作为正式上下文。

## 工作方式

1. 新对话先读本文件，再读 `rounds/preliminary/README.md`。
2. 需要理解赛题时，读 `competition-context.md`。
3. 需要校准方向时，读官方破题指南和 decision records。
4. 需要改 PPT 时，先读 `slides/README.md` 和 `slides/information-architecture/`。
5. 重要方向变化要写入 `decision-records/`，不要只留在聊天记录里。
6. 每次完成一组可复用成果后，提交 Git；需要同步时推送到 `origin/main`。

## 给下一次 Codex 的接力提示

这是一个比赛策略工作区，不是产品代码仓库。回答和修改前应优先尊重本地材料中的赛题要求、官方指南、决策记录和现有 slide 结构。品牌已锁定为 YSL Beauty，候选品牌扫描已经归档；除非用户明确要求重新开题，不要再回到品牌选择问题。当前最重要的评审口径是：避免产品思维，用 consulting 逻辑解释为什么做、在哪个消费者旅程节点做、创造什么商业价值、为什么只有 YSL Beauty 适合这样做。
