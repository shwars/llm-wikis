---
type: concept
topic: agent-coding
lang: english
status: active
updated: 2026-04-21
source_keys:
  - 2024-anthropic-building-effective-agents
  - 2025-anthropic-effective-context-engineering
  - 2026-openai-harness-engineering
aliases:
  - orchestrator-worker pattern
related:
  - "[[english/themes/Agent Harnesses and Execution Loops]]"
  - "[[english/concepts/Subagents]]"
---
# Orchestrator-Worker Pattern

## English Abstract

A control pattern where a lead agent delegates bounded tasks to worker agents and integrates the results.

## Current Synthesis

This pattern appears across agent research systems and coding tools because it matches the shape of real work: some part of the process defines scope and quality, while other parts explore, fetch context, or implement slices. It is a natural fit for repo-scale changes and research synthesis.

## Supporting Evidence

- [[english/sources/2024-anthropic-building-effective-agents#Summary]]
- [[english/sources/2025-anthropic-effective-context-engineering#Summary]]
- [[english/sources/2026-openai-harness-engineering#Summary]]

## Related Pages

- [[english/themes/Agent Harnesses and Execution Loops]]
- [[english/concepts/Subagents]]
