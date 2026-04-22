---
type: theme
topic: agent-coding
lang: russian
status: active
updated: 2026-04-22
source_keys:
  - 2024-anthropic-building-effective-agents
  - 2025-openai-introducing-codex
  - 2026-openai-harness-engineering
  - 2026-bcherny-worktrees-snippet
  - 2025-google-gemini-3-antigravity
aliases:
  - agent harnesses and execution loops
  - agent harnesses и execution loops
related:
  - "[[russian/index]]"
  - "[[russian/concepts/Orchestrator-Worker Pattern]]"
  - "[[russian/concepts/Evaluator-Optimizer Pattern]]"
  - "[[russian/concepts/Worktrees]]"
  - "[[russian/concepts/Subagents]]"
---
# Agent harnesses и execution loops

## Кратко

Эта тема фокусируется на scaffolding, который превращает сырую модель в надежного software worker.

## Текущий синтез

Современный AI-Assisted Software Development harness — это система, а не промпт. Он включает repo instructions, декомпозицию задач, tool permissions, worktree isolation, evaluator-stages, feedback loops и supervision interfaces. Во всех источниках Anthropic, OpenAI, GitHub и Google повторяется один и тот же выигрышный паттерн: цикл должен быть достаточно простым, чтобы его можно было отлаживать, и достаточно богатым, чтобы он умел проверять себя и восстанавливаться. Теперь в эту картину явно входят и MCP, и Agent Skills: MCP приносит в цикл live external systems, а skills упаковывают reusable procedures так, чтобы цикл оставался legible и дешевым по контексту. Теперь в эту картину явно входят и MCP, и Agent Skills: MCP приносит в цикл live external systems, а skills упаковывают reusable procedures так, чтобы цикл оставался legible и дешевым по контексту. Теперь в эту картину явно входят и MCP, и Agent Skills: MCP приносит в цикл live external systems, а skills упаковывают reusable procedures так, чтобы цикл оставался legible и дешевым по контексту. Теперь в эту картину явно входят и MCP, и Agent Skills: MCP приносит в цикл live external systems, а skills упаковывают reusable procedures так, чтобы цикл оставался legible и дешевым по контексту. Теперь в эту картину явно входят и MCP, и Agent Skills: MCP приносит в цикл live external systems, а skills упаковывают reusable procedures так, чтобы цикл оставался legible и дешевым по контексту.

## Поддерживающие источники

- [[russian/sources/2024-anthropic-building-effective-agents#Summary]]
- [[russian/sources/2025-openai-introducing-codex#Summary]]
- [[russian/sources/2026-openai-harness-engineering#Summary]]
- [[russian/sources/2026-bcherny-worktrees-snippet#Summary]]
- [[russian/sources/2025-google-gemini-3-antigravity#Summary]]

## Связанные страницы

- [[russian/index]]
- [[russian/concepts/Orchestrator-Worker Pattern]]
- [[russian/concepts/Evaluator-Optimizer Pattern]]
- [[russian/concepts/Worktrees]]
- [[russian/concepts/Subagents]]
- [[russian/concepts/Model Context Protocol]]
- [[russian/concepts/Agent Skills]]
- [[russian/concepts/Model Context Protocol]]
- [[russian/concepts/Agent Skills]]
- [[russian/concepts/Model Context Protocol]]
- [[russian/concepts/Agent Skills]]
- [[russian/concepts/Model Context Protocol]]
- [[russian/concepts/Agent Skills]]
- [[russian/concepts/Model Context Protocol]]
- [[russian/concepts/Agent Skills]]
