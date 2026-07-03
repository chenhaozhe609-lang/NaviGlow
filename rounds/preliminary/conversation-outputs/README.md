# Conversation Outputs

这个目录记录重要 Codex 对话批次的产出，方便后续线程不依赖聊天历史也能接上。

## 当前状态

- 已有 `batch-2026-06-28-ppt-ia-polish`，记录 Slide 2-3 信息架构和 consulting-style HTML deck polish。
- 新增跨文件工作、重要 deck 修改、研究整理或提交前整合时，应补一个 batch handoff。

## Folder Convention

Use one folder per major conversation batch:

```text
batch-YYYY-MM-DD-topic/
```

Each batch folder should include:

- `handoff.md`: what was produced, where the files are, what decisions were made, and where to continue.
- Optional supporting files if needed, such as screenshots, exported drafts, or notes.

## What To Record

For each batch, record:

1. Main deliverables created or edited.
2. Current strategic or design decisions.
3. Known issues or unresolved questions.
4. Recommended next step.
5. A short prompt that can start the next conversation.

## Current Batches

- `batch-2026-06-28-ppt-ia-polish`: Slide 2 and Slide 3 information architecture and consulting-style HTML deck polish.

## 使用规则

- 不是每次对话都需要记录，只有产生可复用成果或重要方向变化时记录。
- `handoff.md` 要写清楚改了什么、文件在哪里、当前判断、未解决问题和下一步建议。
- 如果内容属于正式方向选择，应同时写入 `decision-records/`。

## 给下一次 Codex 的接力提示

如果新对话需要理解“上一轮到底做到了哪”，先看最新 batch 的 `handoff.md`，再看对应文件本体。不要把 conversation outputs 当作唯一事实来源，它只是接力摘要。
