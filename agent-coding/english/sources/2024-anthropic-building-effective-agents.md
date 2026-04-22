---
type: source
source_key: 2024-anthropic-building-effective-agents
title: Building effective agents
author: Anthropic
year: 2024
original_language: en
raw_path: agent-coding/raw/Anthropic - Building Effective Agents - 2024.md
status: seeded
updated: 2026-04-21
tags:
  - lasd
  - theory
  - agents
  - anthropic
lang: english
---
# Building effective agents

## Summary

Anthropic's agent essay provides a compact theory of effective agent systems: keep the core loop simple, use composable patterns, and only add autonomy where the task benefits from it. For AI-Assisted Software Development, it is one of the clearest bridges between generic agent theory and practical software-building harnesses.

## Structure Map

- `[[#Summary]]`: what the source is and why it matters for AI-Assisted Software Development.
- `[[#Key Claims]]`: the main historical, product, or theoretical claims.
- `[[#Notable Practices]]`: the reusable operational lessons.
- `[[#Related Pages]]`: the concepts, tools, and themes this source updates.

## Key Claims

- Simple agent patterns usually outperform overbuilt frameworks.
- Parallelization, routing, and evaluator loops are reusable primitives.
- The right level of autonomy depends on task structure.

## Notable Practices

- Start from the smallest loop that can verify progress.
- Use explicit evaluator stages when quality matters.
- Reserve autonomy for exploration-heavy or long-horizon work.

## Related Pages

- [[english/themes/Agent Harnesses and Execution Loops]]
- [[english/concepts/Orchestrator-Worker Pattern]]
- [[english/concepts/Evaluator-Optimizer Pattern]]
- [[english/organizations/Anthropic]]
