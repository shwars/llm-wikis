---
type: concept
topic: agent-coding
lang: russian
status: active
updated: 2026-04-21
source_keys:
  - 2024-anthropic-building-effective-agents
  - 2025-anthropic-claude-code-best-practices
  - 2026-openai-harness-engineering
aliases:
  - evaluator-optimizer pattern
  - evaluator-optimizer pattern
related:
  - "[[russian/themes/Verification, Testing, and Automatic Debugging]]"
  - "[[russian/concepts/Automatic Debugging Loop]]"
---
# Evaluator-optimizer pattern

## Кратко

Feedback-паттерн, при котором один процесс предлагает изменения, а другой оценивает качество или failure перед следующей попыткой.

## Текущий синтез

Software agents резко улучшаются, когда у них есть явный judge. Tests, linters, browser checks, screenshots и quality scores — все это воплощения evaluator-optimizer logic. Чем объективнее evaluator, тем сильнее automatic debugging loop.

## Поддерживающие источники

- [[russian/sources/2024-anthropic-building-effective-agents#Summary]]
- [[russian/sources/2025-anthropic-claude-code-best-practices#Summary]]
- [[russian/sources/2026-openai-harness-engineering#Summary]]

## Связанные страницы

- [[russian/themes/Verification, Testing, and Automatic Debugging]]
- [[russian/concepts/Automatic Debugging Loop]]
