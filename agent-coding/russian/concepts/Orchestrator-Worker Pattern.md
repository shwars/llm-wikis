---
type: concept
topic: agent-coding
lang: russian
status: active
updated: 2026-04-21
source_keys:
  - 2024-anthropic-building-effective-agents
  - 2025-anthropic-effective-context-engineering
  - 2026-openai-harness-engineering
aliases:
  - orchestrator-worker pattern
  - orchestrator-worker pattern
related:
  - "[[russian/themes/Agent Harnesses and Execution Loops]]"
  - "[[russian/concepts/Subagents]]"
---
# Orchestrator-worker pattern

## Кратко

Паттерн управления, при котором ведущий агент делегирует ограниченные задачи worker-агентам и интегрирует результаты.

## Текущий синтез

Этот паттерн появляется в research-systems и coding-tools, потому что совпадает с формой реальной работы: одна часть процесса определяет scope и quality, а другие исследуют, подтягивают контекст или реализуют slices. Это естественный fit для repo-scale changes и research synthesis.

## Поддерживающие источники

- [[russian/sources/2024-anthropic-building-effective-agents#Summary]]
- [[russian/sources/2025-anthropic-effective-context-engineering#Summary]]
- [[russian/sources/2026-openai-harness-engineering#Summary]]

## Связанные страницы

- [[russian/themes/Agent Harnesses and Execution Loops]]
- [[russian/concepts/Subagents]]
