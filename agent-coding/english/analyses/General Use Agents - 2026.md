---
type: analysis
topic: agent-coding
lang: english
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
  - "[[english/index]]"
  - "[[english/themes/Tooling Landscape]]"
  - "[[english/themes/Beyond Coding Tasks]]"
---
# General Use Agents - 2026

## English Abstract

This note maps the growing product family of agents that are useful well beyond coding, while still intersecting with coding workflows.

## Current Synthesis

The landscape is splitting into two adjacent clusters. `Always-On Personal Agents` are long-lived, multi-channel systems such as [[english/tools/OpenClaw|OpenClaw]], [[english/tools/Hermes Agent|Hermes Agent]], [[english/tools/OpenCrust|OpenCrust]], and [[english/tools/Memoh|Memoh]] that stay online, accumulate state, and route work over time. `Desktop and Local General-Purpose Agents` are tools such as [[english/tools/Goose|Goose]], [[english/tools/Claude Desktop|Claude Desktop]], [[english/tools/Codex|Codex]], or [[english/tools/Gemini CLI|Gemini CLI]] that may not be messaging-native or always-on, but still span coding, research, automation, and operations from one local or app-based surface. The convergence point is obvious: memory, [[english/concepts/Computer Use|computer use]], schedules, [[english/concepts/Model Context Protocol|MCP]], and [[english/concepts/Agent Skills|skills]] are pulling coding agents and general-use agents toward the same harness shape.

## Always-On Personal Agents

This cluster emphasizes persistent identity, channels, schedules, and long-lived background work. The agent is closer to a personal operating layer than to a one-shot coding copilot. [[english/tools/OpenClaw|OpenClaw]] and [[english/tools/Hermes Agent|Hermes Agent]] are the strongest anchors here, with [[english/tools/OpenCrust|OpenCrust]] and [[english/tools/Memoh|Memoh]] representing security-first and multi-bot platform variants. See [[english/sources/2026-openclaw-overview#Summary|OpenClaw overview]], [[english/sources/2026-hermes-agent-overview#Summary|Hermes Agent overview]], [[english/sources/2026-opencrust-overview#Summary|OpenCrust overview]], and [[english/sources/2026-memoh-overview#Summary|Memoh overview]].

## Desktop and Local General-Purpose Agents

This cluster emphasizes local agency across many tasks rather than always-on messaging presence. [[english/tools/Goose|Goose]] is the clearest open-source example in the current corpus, while boundary references like [[english/tools/Codex|Codex]], [[english/tools/Claude Desktop|Claude Desktop]], and [[english/tools/Gemini CLI|Gemini CLI]] show the same direction from more coding-adjacent surfaces. See [[english/sources/2026-goose-overview#Summary|Goose overview]], [[english/sources/2025-google-gemini-cli#Summary|Gemini CLI]], [[english/sources/2026-openai-introducing-the-codex-app#Summary|Introducing the Codex app]], and [[english/sources/2026-anthropic-claude-desktop#Summary|Install Claude Desktop]].

## Comparison Table

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

## Supporting Evidence

- [[english/sources/2026-openclaw-overview#Summary|OpenClaw overview]]
- [[english/sources/2026-hermes-agent-overview#Summary|Hermes Agent overview]]
- [[english/sources/2026-opencrust-overview#Summary|OpenCrust overview]]
- [[english/sources/2026-memoh-overview#Summary|Memoh overview]]
- [[english/sources/2026-goose-overview#Summary|Goose overview]]
- [[english/sources/2025-google-gemini-cli#Summary|Gemini CLI]]
- [[english/sources/2026-openai-introducing-the-codex-app#Summary|Introducing the Codex app]]
- [[english/sources/2026-anthropic-claude-desktop#Summary|Install Claude Desktop]]

## Related Pages

- [[english/index|Index]]
- [[english/themes/Tooling Landscape|Tooling Landscape]]
- [[english/themes/Beyond Coding Tasks|Beyond Coding Tasks]]
- [[english/tools/OpenClaw|OpenClaw]]
- [[english/tools/Hermes Agent|Hermes Agent]]
- [[english/tools/Claude Desktop|Claude Desktop]]
