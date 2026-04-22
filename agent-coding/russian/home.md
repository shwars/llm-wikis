---
type: home
topic: agent-coding
lang: russian
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
  - "[[russian/index]]"
  - "[[russian/theses]]"
  - "[[russian/open_questions]]"
  - "[[russian/analyses/Best Practices Playbook - AI-Assisted Software Development]]"
---
# Agent Coding and AI-Assisted Software Development

## Кратко

Эта вики фиксирует состояние AI-Assisted Software Development на 2026 год: как программирование сместилось от browser chat и inline completion к [[russian/concepts/Context Engineering|context engineering]], [[russian/themes/Agent Harnesses and Execution Loops|agent harnesses]], multi-agent execution и репозиториям, которые работают как долговечная память.

## Текущий синтез

Самый сильный паттерн в корпусе — сдвиг от одной только формулировки prompt-а к явной операционной структуре. High-signal workflows сочетают [[russian/concepts/Context Engineering|context engineering]], [[russian/concepts/Repository as System of Record|репозиторий как system of record]], [[russian/concepts/Automatic Debugging Loop|automatic debugging loops]] и аккуратную supervision таких инструментов, как [[russian/tools/Claude Code|Claude Code]], [[russian/tools/Codex|Codex]], [[russian/tools/Cursor|Cursor]] или [[russian/tools/Gemini CLI|Gemini CLI]]. Второй паттерн — convergence: coding agents, [[russian/analyses/General Use Agents - 2026|general-use agents]] и design-adjacent tools все чаще используют одни и те же extension-layers через [[russian/concepts/Model Context Protocol|MCP]], [[russian/concepts/Agent Skills|skills]], schedules и [[russian/concepts/Computer Use|computer use]]. Лучшие обзорные страницы для этого сближения — [[russian/analyses/AI-Assisted Software Development Tool Matrix - 2026|матрица автономности и поверхностей]] и [[russian/analyses/Coding Tools by Style and Maturity - 2026|карта style-and-maturity]].

## История AI-Assisted Software Development

Здесь важны две хронологии. В продуктовой хронологии [[russian/tools/GitHub Copilot|GitHub Copilot]] появился раньше browser chat. В пользовательской практике многие впервые почувствовали AI-assisted coding через browser-based chat после запуска ChatGPT 30 ноября 2022 года. Практическая stage-map в этой вики выглядит так:

- `Browser-based LLM use`: вставка кода в browser chat ради explanation, debugging и one-off generation.
- `LLM code completion`: использование inline suggestions в инструментах вроде [[russian/tools/GitHub Copilot|GitHub Copilot]].
- `Prompt-review-edit workflows`: запрос к IDE-инструментам вроде [[russian/tools/Cursor|Cursor]], [[russian/tools/Gemini Code Assist|Gemini Code Assist]] или [[russian/tools/GigaCode|GigaCode]] на multi-file edits и reviewable changes.
- `Agent coding`: передача терминальным инструментам вроде [[russian/tools/Claude Code|Claude Code]], [[russian/tools/OpenCode|OpenCode]] или [[russian/tools/Qwen Code|Qwen Code]] права искать по репозиторию, редактировать, запускать команды и проверять результат.
- `Background and multi-agent coding`: делегирование bounded work системам вроде [[russian/tools/Codex|Codex]], [[russian/tools/OpenHands|OpenHands]], [[russian/tools/Devin|Devin]] или [[russian/tools/Antigravity|Antigravity]].

Полная staged-model и Mermaid timeline находятся в [[russian/analyses/History of AI-Assisted Software Development|History of AI-Assisted Software Development]].

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

## Поддерживающие источники

- [[russian/sources/2025-anthropic-claude-code-best-practices#Сводка|Claude Code best practices]]
- [[russian/sources/2025-anthropic-effective-context-engineering#Сводка|Effective context engineering]]
- [[russian/sources/2026-openai-harness-engineering#Сводка|Harness engineering]]
- [[russian/sources/2026-openai-introducing-the-codex-app#Сводка|Introducing the Codex app]]
- [[russian/sources/2026-karpathy-llm-knowledge-bases-snippet#Сводка|Karpathy on LLM Knowledge Bases]]
- [[russian/sources/2026-karpathy-idea-file-llm-wiki-snippet#Сводка|Karpathy on the idea file and LLM Wiki]]

## Связанные страницы

- [[russian/index|Index]]
- [[russian/theses|Theses]]
- [[russian/open_questions|Open Questions]]
- [[russian/analyses/History of AI-Assisted Software Development|History of AI-Assisted Software Development]]
- [[russian/analyses/AI-Assisted Software Development Tool Matrix - 2026|AI-Assisted Software Development Tool Matrix - 2026]]
- [[russian/analyses/Coding Tools by Style and Maturity - 2026|Coding Tools by Style and Maturity - 2026]]
- [[russian/analyses/General Use Agents - 2026|General Use Agents - 2026]]
- [[russian/analyses/MCP vs Agent Skills|MCP vs Agent Skills]]
- [[russian/concepts/Model Context Protocol|Model Context Protocol]]
- [[russian/concepts/Agent Skills|Agent Skills]]
