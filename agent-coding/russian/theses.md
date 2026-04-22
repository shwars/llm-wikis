---
type: theses
topic: agent-coding
lang: russian
status: active
updated: 2026-04-22
source_keys:
  - 2025-anthropic-claude-code-best-practices
  - 2025-anthropic-effective-context-engineering
  - 2026-openai-harness-engineering
  - 2026-karpathy-idea-file-llm-wiki-snippet
  - 2026-metr-productivity-transcripts
  - 2026-metr-time-horizons
  - 2026-hermes-agent-overview
  - 2026-openclaw-overview
aliases:
  - claims
  - theses
  - тезисы
related:
  - "[[russian/home]]"
  - "[[russian/index]]"
  - "[[russian/open_questions]]"
---
# Тезисы

## Кратко

Это самые устойчивые межисточниковые утверждения в текущем корпусе AI-Assisted Software Development.

- Verification — самый сильный рычаг качества в современном AI-Assisted Software Development, сильнее одной только изобретательности prompt-ов. См. [[russian/sources/2025-anthropic-claude-code-best-practices#Практики и уроки|Claude Code best practices]] и [[russian/sources/2025-openai-introducing-codex#Ключевые тезисы|Introducing Codex]].
- Структурированное repo-local knowledge побеждает гигантские одноразовые instruction blobs. См. [[russian/sources/2025-anthropic-effective-context-engineering#Ключевые тезисы|Effective context engineering]] и [[russian/sources/2026-openai-harness-engineering#Ключевые тезисы|Harness engineering]].
- Дизайн-артефакты становятся machine-readable control surfaces, а не только handoff-документами. См. [[russian/sources/2026-openai-harness-engineering#Сводка|Harness engineering]], [[russian/sources/2026-google-stitch-vibe-design#Сводка|Stitch]] и [[russian/sources/2026-anthropic-claude-design#Сводка|Claude Design]].
- Multi-agent parallelism зависит от изоляции, границ ownership и аккуратной merge-дисциплины. См. [[russian/sources/2026-bcherny-worktrees-snippet#Сводка|Boris Cherny on worktrees]] и [[russian/sources/2026-openai-introducing-the-codex-app#Ключевые тезисы|Introducing the Codex app]].
- Лучшие современные harnesses рассматривают репозиторий как [[russian/concepts/Repository as System of Record|system of record]] для планов, ограничений и workflows. См. [[russian/sources/2026-openai-harness-engineering#Сводка|Harness engineering]] и [[russian/sources/2026-opencode-docs#Сводка|OpenCode docs]].
- Coding agents уже обобщаются на не-кодинговые задачи: deep research, note-taking, release briefs, issue triage и visual QA. См. [[russian/sources/2025-anthropic-building-agents-with-claude-agent-sdk#Сводка|Claude Agent SDK]] и [[russian/sources/2026-openai-introducing-the-codex-app#Сводка|Introducing the Codex app]].
- Vibe coding реален и продуктивен, но это лишь один low-friction стиль внутри более широкого поля. См. [[russian/sources/2025-karpathy-vibe-coding-snippet#Сводка|Karpathy on vibe coding]] и [[russian/themes/Agentic Coding and Vibe Coding|Agentic Coding and Vibe Coding]].
- Task slicing и явные done conditions стали универсальным требованием для high-autonomy tools вроде [[russian/tools/Devin|Devin]], [[russian/tools/Codex|Codex]] и [[russian/tools/GitHub Copilot Coding Agent|GitHub Copilot Coding Agent]]. См. [[russian/sources/2026-devin-intro#Практики и уроки|Introducing Devin]], [[russian/sources/2025-github-copilot-coding-agent-ga#Практики и уроки|Copilot coding agent GA]] и [[russian/sources/2025-openai-introducing-codex#Практики и уроки|Introducing Codex]].
- State of the art улучшается на более длинных задачах, но надежность по-прежнему важнее benchmark theater. См. [[russian/sources/2026-metr-time-horizons#Сводка|METR time horizons]] и [[russian/sources/2026-metr-productivity-transcripts#Сводка|METR productivity transcripts]].
- Долгосрочное направление — это agentic software creation плюс поддержка knowledge systems, а не только лучшее autocomplete. См. [[russian/sources/2026-karpathy-llm-knowledge-bases-snippet#Сводка|Karpathy on LLM Knowledge Bases]] и [[russian/sources/2026-openai-codex-for-almost-everything#Сводка|Codex for (almost) everything]].
- Coding agents и [[russian/analyses/General Use Agents - 2026|general-use agents]] сближаются через memory, schedules, [[russian/concepts/Computer Use|computer use]], [[russian/concepts/Agent Skills|skills]] и live integrations. См. [[russian/sources/2026-hermes-agent-overview#Сводка|Hermes Agent overview]], [[russian/sources/2026-openclaw-overview#Сводка|OpenClaw overview]] и [[russian/analyses/General Use Agents - 2026|General Use Agents - 2026]].
- [[russian/concepts/Model Context Protocol|MCP]] и [[russian/concepts/Agent Skills|Agent Skills]] — взаимодополняющие extension-layers: один приносит live systems, другой упаковывает reusable procedures. См. [[russian/sources/2026-mcp-what-is-mcp#Сводка|What is MCP?]], [[russian/sources/2026-anthropic-claude-code-skills#Сводка|Claude Code skills]] и [[russian/analyses/MCP vs Agent Skills|MCP vs Agent Skills]].

## Связанные страницы

- [[russian/home|Home]]
- [[russian/index|Index]]
- [[russian/open_questions|Open Questions]]
- [[russian/analyses/Best Practices Playbook - AI-Assisted Software Development|Best Practices Playbook - AI-Assisted Software Development]]
- [[russian/analyses/General Use Agents - 2026|General Use Agents - 2026]]
- [[russian/analyses/MCP vs Agent Skills|MCP vs Agent Skills]]
