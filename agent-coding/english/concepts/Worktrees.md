---
type: concept
topic: agent-coding
lang: english
status: active
updated: 2026-04-21
source_keys:
  - 2026-bcherny-worktrees-snippet
  - 2026-openai-introducing-the-codex-app
  - 2026-windsurf-docs
aliases:
  - worktrees
related:
  - "[[english/themes/Agent Harnesses and Execution Loops]]"
  - "[[english/concepts/Subagents]]"
---
# Worktrees

## English Abstract

Isolated working directories tied to branches that let multiple agents work on the same repo safely in parallel.

## Current Synthesis

Worktrees solve a concrete systems problem in multi-agent coding: shared state interference. By giving each agent isolated filesystem and branch state, teams can compare implementations, avoid collisions, and merge only verified slices back into the main line.

## Supporting Evidence

- [[english/sources/2026-bcherny-worktrees-snippet#Summary]]
- [[english/sources/2026-openai-introducing-the-codex-app#Summary]]
- [[english/sources/2026-windsurf-docs#Summary]]

## Related Pages

- [[english/themes/Agent Harnesses and Execution Loops]]
- [[english/concepts/Subagents]]
