---
type: concept
topic: agent-coding
lang: russian
status: active
updated: 2026-04-21
source_keys:
  - 2026-bcherny-worktrees-snippet
  - 2026-openai-introducing-the-codex-app
  - 2026-windsurf-docs
aliases:
  - worktrees
  - worktrees
related:
  - "[[russian/themes/Agent Harnesses and Execution Loops]]"
  - "[[russian/concepts/Subagents]]"
---
# Worktrees

## Кратко

Изолированные working directories, привязанные к веткам, которые позволяют нескольким агентам безопасно работать над одним репозиторием параллельно.

## Текущий синтез

Worktrees решают конкретную системную проблему multi-agent coding: interference общего состояния. Давая каждому агенту изолированное состояние файловой системы и ветки, команды могут сравнивать реализации, избегать столкновений и мержить обратно в main line только проверенные slices.

## Поддерживающие источники

- [[russian/sources/2026-bcherny-worktrees-snippet#Summary]]
- [[russian/sources/2026-openai-introducing-the-codex-app#Summary]]
- [[russian/sources/2026-windsurf-docs#Summary]]

## Связанные страницы

- [[russian/themes/Agent Harnesses and Execution Loops]]
- [[russian/concepts/Subagents]]
