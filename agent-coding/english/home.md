---
type: home
topic: agent-coding
lang: english
status: seeded
updated: 2026-04-22
source_keys:
  - 2025-anthropic-claude-code-best-practices
  - 2025-anthropic-effective-context-engineering
  - 2026-openai-harness-engineering
  - 2026-openai-introducing-the-codex-app
  - 2026-karpathy-llm-knowledge-bases-snippet
  - 2026-karpathy-idea-file-llm-wiki-snippet
  - 2026-anthropic-claude-code-overview
  - 2026-google-gemini-code-assist-overview
aliases:
  - ai-assisted software development wiki
  - agent coding wiki
related:
  - "[[english/index]]"
  - "[[english/theses]]"
  - "[[english/open_questions]]"
  - "[[english/analyses/Best Practices Playbook - AI-Assisted Software Development]]"
---
# Agent Coding and AI-Assisted Software Development

## English Abstract

This wiki is a 2026 snapshot of AI-Assisted Software Development: how coding moved from browser chat and inline completion toward [[english/concepts/Context Engineering|context engineering]], [[english/themes/Agent Harnesses and Execution Loops|agent harnesses]], multi-agent execution, and repositories that function as durable working memory.

## Current Synthesis

The strongest pattern in the corpus is a shift away from prompt wording alone and toward explicit operating structure. High-signal workflows combine [[english/concepts/Context Engineering|context engineering]], a [[english/concepts/Repository as System of Record|repository as system of record]], [[english/concepts/Automatic Debugging Loop|automatic debugging loops]], and careful supervision of tools like [[english/tools/Claude Code|Claude Code]], [[english/tools/Codex|Codex]], [[english/tools/Cursor|Cursor]], or [[english/tools/Gemini CLI|Gemini CLI]]. A second pattern is convergence: coding agents, [[english/analyses/General Use Agents - 2026|general-use agents]], and design-adjacent tools increasingly share the same extension layers through [[english/concepts/Model Context Protocol|MCP]], [[english/concepts/Agent Skills|skills]], schedules, and [[english/concepts/Computer Use|computer use]]. The best overview pages for that convergence are [[english/analyses/AI-Assisted Software Development Tool Matrix - 2026|the autonomy-and-surface matrix]] and [[english/analyses/Coding Tools by Style and Maturity - 2026|the style-and-maturity map]].

## History of AI-Assisted Software Development

Two timelines matter. In product chronology, [[english/tools/GitHub Copilot|GitHub Copilot]] arrived before browser chat. In everyday adoption, many people first experienced AI-assisted coding through browser-based chat after ChatGPT launched on November 30, 2022. The practical stage map used in this wiki is:

- `Browser-based LLM use`: copy-paste code into browser chat for explanation, debugging, and one-off generation.
- `LLM code completion`: use inline suggestions in tools like [[english/tools/GitHub Copilot|GitHub Copilot]].
- `Prompt-review-edit workflows`: ask IDE tools such as [[english/tools/Cursor|Cursor]], [[english/tools/Gemini Code Assist|Gemini Code Assist]], or [[english/tools/GigaCode|GigaCode]] for multi-file edits and reviewable changes.
- `Agent coding`: give terminal tools like [[english/tools/Claude Code|Claude Code]], [[english/tools/OpenCode|OpenCode]], or [[english/tools/Qwen Code|Qwen Code]] the ability to search, edit, run commands, and verify.
- `Background and multi-agent coding`: delegate bounded work to systems like [[english/tools/Codex|Codex]], [[english/tools/OpenHands|OpenHands]], [[english/tools/Devin|Devin]], or [[english/tools/Antigravity|Antigravity]].

For the full staged model and Mermaid timeline, see [[english/analyses/History of AI-Assisted Software Development|History of AI-Assisted Software Development]].

## Optional Markmap

```markmap
# AI-Assisted Software Development
## History
### Browser chat
### Code completion
### Prompt-review-edit
### Agent coding
### Background and multi-agent work
## Core components
### Problem specification
### Context engineering
### Agent management
### Verification loops
## Durable artifacts
### AGENTS.md / CLAUDE.md
### DESIGN.md
### Idea file
### LLM Wiki
## Extension layers
### MCP
### Agent Skills
## Beyond coding
### Research
### Triage and briefs
### Visual QA
### Spreadsheet and docs work
```

## Supporting Evidence

- [[english/sources/2025-anthropic-claude-code-best-practices#Summary|Claude Code best practices]]
- [[english/sources/2025-anthropic-effective-context-engineering#Summary|Effective context engineering]]
- [[english/sources/2026-openai-harness-engineering#Summary|Harness engineering]]
- [[english/sources/2026-openai-introducing-the-codex-app#Summary|Introducing the Codex app]]
- [[english/sources/2026-karpathy-llm-knowledge-bases-snippet#Summary|Karpathy on LLM Knowledge Bases]]
- [[english/sources/2026-karpathy-idea-file-llm-wiki-snippet#Summary|Karpathy on the idea file and LLM Wiki]]

## Related Pages

- [[english/index|Index]]
- [[english/theses|Theses]]
- [[english/open_questions|Open Questions]]
- [[english/analyses/History of AI-Assisted Software Development|History of AI-Assisted Software Development]]
- [[english/analyses/AI-Assisted Software Development Tool Matrix - 2026|AI-Assisted Software Development Tool Matrix - 2026]]
- [[english/analyses/Coding Tools by Style and Maturity - 2026|Coding Tools by Style and Maturity - 2026]]
- [[english/analyses/General Use Agents - 2026|General Use Agents - 2026]]
- [[english/analyses/MCP vs Agent Skills|MCP vs Agent Skills]]
- [[english/concepts/Model Context Protocol|Model Context Protocol]]
- [[english/concepts/Agent Skills|Agent Skills]]
