---
type: analysis
topic: agent-coding
lang: english
status: active
updated: 2026-04-22
source_keys:
  - 2025-anthropic-effective-context-engineering
  - 2026-openai-harness-engineering
  - 2026-karpathy-llm-knowledge-bases-snippet
  - 2026-karpathy-idea-file-llm-wiki-snippet
  - 2025-anthropic-claude-code-best-practices
aliases:
  - concept graph - agentic coding
related:
  - "[[english/index]]"
  - "[[english/theses]]"
  - "[[english/themes/Context Management and Agent Memory]]"
  - "[[english/themes/Agent Harnesses and Execution Loops]]"
---
# Concept Graph - Agentic Coding

## English Abstract

This note makes the central AI-Assisted Software Development concept graph explicit instead of leaving the ideas as isolated pages.

## Current Synthesis

Three clusters dominate the current corpus. The first is repository intelligence: AGENTS.md, DESIGN.md, repo references, machine-readable intent, and on-demand procedural context through skills. The second is execution architecture: orchestrators, workers, subagents, worktrees, evaluator loops, and live external systems connected through MCP. The third is outward expansion: LLM wikis, idea files, computer use, general-use agents, and design systems that move the same harness pattern beyond source-code editing.

## Graph

```mermaid
flowchart LR
  Field["AI-Assisted Software Development"] --> CE["Context Engineering"]
  Field --> AH["Agent Harnesses"]
  Field --> VC["Vibe Coding"]
  Field --> MCP["Model Context Protocol"]
  Field --> SK["Agent Skills"]
  CE --> RSR["Repository as System of Record"]
  CE --> IW["LLM Wiki"]
  CE --> IF["Idea File"]
  CE --> SK
  AH --> OW["Orchestrator-Worker Pattern"]
  AH --> EO["Evaluator-Optimizer Pattern"]
  AH --> ADL["Automatic Debugging Loop"]
  AH --> SA["Subagents"]
  AH --> MCP
  SA --> WT["Worktrees"]
  RSR --> DSM["Design System Markdown"]
  IF --> DSM
  IW --> BCT["Beyond Coding Tasks"]
  MCP --> BCT
  MCP --> CU["Computer Use"]
  SK --> BCT
  SK --> RSR
  ADL --> AL["Agent Legibility"]
  CU --> GUA["General Use Agents"]
  VC --> AH
```

## Supporting Evidence

- [[english/sources/2025-anthropic-effective-context-engineering#Summary]]
- [[english/sources/2026-openai-harness-engineering#Summary]]
- [[english/sources/2025-anthropic-claude-code-best-practices#Summary]]
- [[english/sources/2026-karpathy-llm-knowledge-bases-snippet#Summary]]
- [[english/sources/2026-karpathy-idea-file-llm-wiki-snippet#Summary]]

## Related Pages

- [[english/index]]
- [[english/theses]]
- [[english/themes/Context Management and Agent Memory]]
- [[english/themes/Agent Harnesses and Execution Loops]]
- [[english/concepts/Model Context Protocol]]
- [[english/concepts/Agent Skills]]
- [[english/concepts/Model Context Protocol]]
- [[english/concepts/Agent Skills]]
- [[english/concepts/Model Context Protocol]]
- [[english/concepts/Agent Skills]]
