---
type: source
source_key: 2025-anthropic-effective-context-engineering
title: Effective context engineering for AI agents
author: Anthropic
year: 2025
original_language: en
raw_path: agent-coding/raw/Anthropic - Effective Context Engineering - 2025.md
status: seeded
updated: 2026-04-21
tags:
  - lasd
  - context
  - anthropic
  - theory
lang: english
---
# Effective context engineering for AI agents

## Summary

This essay reframes the core engineering problem around agents: the challenge is no longer just phrasing prompts, but curating the right working state over time. For AI-Assisted Software Development, that means treating context as scarce capital and designing memory, retrieval, compaction, and decomposition deliberately.

## Structure Map

- `[[#Summary]]`: what the source is and why it matters for AI-Assisted Software Development.
- `[[#Key Claims]]`: the main historical, product, or theoretical claims.
- `[[#Notable Practices]]`: the reusable operational lessons.
- `[[#Related Pages]]`: the concepts, tools, and themes this source updates.

## Key Claims

- Context engineering has become more important than prompt phrasing alone.
- More tokens are not automatically better; context quality matters more than volume.
- Long-horizon tasks need explicit strategies for pruning, summarizing, and parallelizing context.

## Notable Practices

- Prefer small, high-signal instruction files over giant prompt blobs.
- Split search and synthesis across multiple agents when exploration is broad.
- Use compaction, note files, and explicit memory artifacts before the context rots.

## Related Pages

- [[english/themes/Context Management and Agent Memory]]
- [[english/concepts/Repository as System of Record]]
- [[english/concepts/LLM Wiki]]
- [[english/concepts/Idea File]]
