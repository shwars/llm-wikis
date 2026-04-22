---
type: concept
topic: agent-coding
lang: english
status: active
updated: 2026-04-21
source_keys:
  - 2024-anthropic-building-effective-agents
  - 2025-anthropic-claude-code-best-practices
  - 2026-openai-harness-engineering
aliases:
  - evaluator-optimizer pattern
related:
  - "[[english/themes/Verification, Testing, and Automatic Debugging]]"
  - "[[english/concepts/Automatic Debugging Loop]]"
---
# Evaluator-Optimizer Pattern

## English Abstract

A feedback pattern where one process proposes changes and another judges quality or failure before retry.

## Current Synthesis

Software agents improve dramatically when they have an explicit judge. Tests, linters, browser checks, screenshots, and quality scores all instantiate evaluator-optimizer logic. The more objective the evaluator, the stronger the automatic debugging loop.

## Supporting Evidence

- [[english/sources/2024-anthropic-building-effective-agents#Summary]]
- [[english/sources/2025-anthropic-claude-code-best-practices#Summary]]
- [[english/sources/2026-openai-harness-engineering#Summary]]

## Related Pages

- [[english/themes/Verification, Testing, and Automatic Debugging]]
- [[english/concepts/Automatic Debugging Loop]]
