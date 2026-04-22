---
type: concept
topic: agent-coding
lang: russian
status: active
updated: 2026-04-22
source_keys:
  - 2026-mcp-what-is-mcp
  - 2026-mcp-server-concepts
  - 2026-mcp-registry-about
  - 2026-mcp-example-servers
  - 2026-anthropic-claude-code-mcp
  - 2026-hermes-agent-mcp
aliases:
  - mcp
  - model context protocol
related:
  - "[[russian/analyses/MCP vs Agent Skills]]"
  - "[[russian/analyses/Useful MCP Servers for Coding]]"
  - "[[russian/themes/Agent Harnesses and Execution Loops]]"
---
# Model Context Protocol

## Кратко

Открытый протокол, который позволяет AI-приложениям подключаться к внешним tools, resources, prompts и системам через стандартизованные client-server boundaries.

## Текущий синтез

Model Context Protocol лучше всего понимать как integration plumbing для агентов. Он определяет, как hosts, clients и servers обмениваются внешними capabilities. Tools позволяют модели действовать, resources отдают contextual data, а prompts дают reusable entrypoints. Участвовать могут и local-, и remote-servers, а registries и metadata делают discovery и trust управляемыми. В coding-workflows MCP важен потому, что превращает issue trackers, databases, design systems, docs и observability в live context вместо copy-paste фонового текста.

## Поддерживающие источники

- [[russian/sources/2026-mcp-what-is-mcp#Сводка]]
- [[russian/sources/2026-mcp-server-concepts#Сводка]]
- [[russian/sources/2026-mcp-registry-about#Сводка]]
- [[russian/sources/2026-anthropic-claude-code-mcp#Сводка]]

## Связанные страницы

- [[russian/analyses/MCP vs Agent Skills]]
- [[russian/analyses/Useful MCP Servers for Coding]]
- [[russian/themes/Agent Harnesses and Execution Loops]]
