---
type: concept
topic: agent-coding
lang: english
status: active
updated: 2026-04-21
source_keys:
  - 2026-openai-harness-engineering
  - 2025-openai-introducing-codex
  - 2025-anthropic-effective-context-engineering
  - 2026-opencode-docs
aliases:
  - repository as system of record
related:
  - "[[english/themes/Context Management and Agent Memory]]"
  - "[[english/themes/Design, Specification, and Intent Artifacts]]"
---
# Repository as System of Record

## English Abstract

The pattern of storing instructions, specs, plans, and references directly in the repo so agents can use them reliably.

## Current Synthesis

The repository is no longer only where code lives; it is where the agent's durable operating context lives. AGENTS.md, CLAUDE.md, DESIGN.md, references, and structured docs let the repo act as a shared memory and supervision surface for both humans and agents.

## Supporting Evidence

- [[english/sources/2026-openai-harness-engineering#Summary]]
- [[english/sources/2025-openai-introducing-codex#Summary]]
- [[english/sources/2025-anthropic-effective-context-engineering#Summary]]
- [[english/sources/2026-opencode-docs#Summary]]

## Related Pages

- [[english/themes/Context Management and Agent Memory]]
- [[english/themes/Design, Specification, and Intent Artifacts]]
