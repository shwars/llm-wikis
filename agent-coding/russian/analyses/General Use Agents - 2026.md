---
type: analysis
topic: agent-coding
lang: russian
status: active
updated: 2026-04-22
source_keys:
  - 2026-openclaw-overview
  - 2026-openclaw-skills-docs
  - 2026-hermes-agent-overview
  - 2026-hermes-agent-skills-system
  - 2026-hermes-agent-mcp
  - 2026-opencrust-overview
  - 2026-memoh-overview
  - 2026-goose-overview
  - 2025-google-gemini-cli
  - 2026-openai-introducing-the-codex-app
  - 2026-anthropic-claude-desktop
aliases:
  - general use agents
  - general-use agents - 2026
related:
  - "[[russian/index]]"
  - "[[russian/themes/Tooling Landscape]]"
  - "[[russian/themes/Beyond Coding Tasks]]"
---
# General Use Agents - 2026

## Кратко

Эта заметка картирует растущее семейство агентов, полезных далеко за пределами coding, но все еще пересекающихся с coding workflows.

## Текущий синтез

Ландшафт распадается на два соседних кластера. `Always-On Personal Agents` — это долгоживущие multi-channel systems вроде [[russian/tools/OpenClaw|OpenClaw]], [[russian/tools/Hermes Agent|Hermes Agent]], [[russian/tools/OpenCrust|OpenCrust]] и [[russian/tools/Memoh|Memoh]], которые остаются онлайн, накапливают state и маршрутизируют работу во времени. `Desktop and Local General-Purpose Agents` — это инструменты вроде [[russian/tools/Goose|Goose]], [[russian/tools/Claude Desktop|Claude Desktop]], [[russian/tools/Codex|Codex]] или [[russian/tools/Gemini CLI|Gemini CLI]], которые могут не быть messaging-native или always-on, но все равно охватывают coding, research, automation и operations с одной локальной или app-based surface. Точка схождения очевидна: memory, [[russian/concepts/Computer Use|computer use]], schedules, [[russian/concepts/Model Context Protocol|MCP]] и [[russian/concepts/Agent Skills|skills]] тянут coding agents и general-use agents к одной harness-shape.

## Always-On Personal Agents

Этот кластер делает акцент на persistent identity, channels, schedules и long-lived background work. Агент ближе к personal operating layer, чем к one-shot coding copilot. [[russian/tools/OpenClaw|OpenClaw]] и [[russian/tools/Hermes Agent|Hermes Agent]] — самые сильные anchors здесь, а [[russian/tools/OpenCrust|OpenCrust]] и [[russian/tools/Memoh|Memoh]] представляют security-first и multi-bot platform variants. См. [[russian/sources/2026-openclaw-overview#Сводка|OpenClaw overview]], [[russian/sources/2026-hermes-agent-overview#Сводка|Hermes Agent overview]], [[russian/sources/2026-opencrust-overview#Сводка|OpenCrust overview]] и [[russian/sources/2026-memoh-overview#Сводка|Memoh overview]].

## Desktop and Local General-Purpose Agents

Этот кластер делает акцент на local agency across many tasks, а не на always-on messaging presence. [[russian/tools/Goose|Goose]] — самый ясный open-source пример в текущем корпусе, а граничные references вроде [[russian/tools/Codex|Codex]], [[russian/tools/Claude Desktop|Claude Desktop]] и [[russian/tools/Gemini CLI|Gemini CLI]] показывают тот же вектор из более coding-adjacent surfaces. См. [[russian/sources/2026-goose-overview#Сводка|Goose overview]], [[russian/sources/2025-google-gemini-cli#Сводка|Gemini CLI]], [[russian/sources/2026-openai-introducing-the-codex-app#Сводка|Introducing the Codex app]] и [[russian/sources/2026-anthropic-claude-desktop#Сводка|Install Claude Desktop]].

## Сравнительная таблица

| Product | Cluster | Surface | Persistence | Memory | Multi-channel | Coding relevance | MCP | Skills / extensions | Self-hosting / local-first |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [OpenClaw](<../tools/OpenClaw.md>) | Always-On Personal Agents | Gateway + messaging + CLI | High | Persistent sessions | Strong | Medium | Partial / adjacent | OpenClaw skills | Strong local-first |
| [Hermes Agent](<../tools/Hermes Agent.md>) | Always-On Personal Agents | CLI + messaging + schedules | High | Strong persistent memory | Strong | High | Yes | Skills + hubs | Self-hosted |
| [OpenCrust](<../tools/OpenCrust.md>) | Always-On Personal Agents | Local binary + channels | High | Persistent agent state | Medium | Medium | Yes | Tool / framework extensions | Strong local-first |
| [Memoh](<../tools/Memoh.md>) | Always-On Personal Agents | Web UI + containers + channels | High | Persistent per-bot memory | Strong | Medium | Yes | Skills + slash commands | Self-hosted containers |
| [Goose](<../tools/Goose.md>) | Desktop and Local General-Purpose Agents | Desktop + CLI + API | Medium | Local runtime context | Weak | High | Yes | MCP extensions | Local-first |
| [Claude Desktop](<../tools/Claude Desktop.md>) | Desktop and Local General-Purpose Agents | Desktop app | Medium | App and session memory | Weak | Medium | Yes | Extensions and local MCP | Local app |
| [Codex](<../tools/Codex.md>) | Desktop and Local General-Purpose Agents | App + cloud + worktrees | Medium to high | Projects, skills, automations | Weak | High | Indirect / growing | Skills + automations | Mixed local/cloud |
| [Gemini CLI](<../tools/Gemini CLI.md>) | Desktop and Local General-Purpose Agents | CLI | Medium | Session and tool context | Weak | High | Yes | MCP + scriptability | Local-first |

## Поддерживающие источники

- [[russian/sources/2026-openclaw-overview#Сводка|OpenClaw overview]]
- [[russian/sources/2026-hermes-agent-overview#Сводка|Hermes Agent overview]]
- [[russian/sources/2026-opencrust-overview#Сводка|OpenCrust overview]]
- [[russian/sources/2026-memoh-overview#Сводка|Memoh overview]]
- [[russian/sources/2026-goose-overview#Сводка|Goose overview]]
- [[russian/sources/2025-google-gemini-cli#Сводка|Gemini CLI]]
- [[russian/sources/2026-openai-introducing-the-codex-app#Сводка|Introducing the Codex app]]
- [[russian/sources/2026-anthropic-claude-desktop#Сводка|Install Claude Desktop]]

## Связанные страницы

- [[russian/index|Index]]
- [[russian/themes/Tooling Landscape|Tooling Landscape]]
- [[russian/themes/Beyond Coding Tasks|Beyond Coding Tasks]]
- [[russian/tools/OpenClaw|OpenClaw]]
- [[russian/tools/Hermes Agent|Hermes Agent]]
- [[russian/tools/Claude Desktop|Claude Desktop]]
