---
type: theme
topic: agent-coding
lang: russian
status: active
updated: 2026-04-22
source_keys:
  - 2025-anthropic-effective-context-engineering
  - 2025-anthropic-claude-code-best-practices
  - 2026-openai-harness-engineering
  - 2026-karpathy-llm-knowledge-bases-snippet
  - 2026-karpathy-idea-file-llm-wiki-snippet
aliases:
  - context management and agent memory
  - управление контекстом и память агентов
related:
  - "[[russian/index]]"
  - "[[russian/concepts/Repository as System of Record]]"
  - "[[russian/concepts/Idea File]]"
  - "[[russian/concepts/LLM Wiki]]"
  - "[[russian/concepts/Subagents]]"
---
# Управление контекстом и память агентов

## Кратко

Эта тема отслеживает переход от prompt engineering к структурированному context engineering и долговечным артефактам памяти.

## Текущий синтез

Современный AI-Assisted Software Development зависит от управления attention budget, а не только от изобретательных промптов. Frontier-паттерн состоит в том, чтобы хранить стабильное знание о репозитории в файлах типа AGENTS.md или CLAUDE.md, переносить долго живущее design- или domain-knowledge в markdown-документы, compact-ить сессии при разрастании и запускать изолированных subagents, когда exploration иначе отравит основной контекст. Паттерны LLM Wiki и idea file у Карпати распространяют ту же логику на research и knowledge work. Skills добавляют поверх этого слой progressive disclosure: reusable procedural context, который загружается только по мере надобности. MCP добавляет комплементарный слой live context: внешние системы, которые можно спрашивать и дергать без copy-paste их содержимого в transcript. Skills добавляют поверх этого слой progressive disclosure: reusable procedural context, который загружается только по мере надобности. MCP добавляет комплементарный слой live context: внешние системы, которые можно спрашивать и дергать без copy-paste их содержимого в transcript. Skills добавляют поверх этого слой progressive disclosure: reusable procedural context, который загружается только по мере надобности. MCP добавляет комплементарный слой live context: внешние системы, которые можно спрашивать и дергать без copy-paste их содержимого в transcript. Skills добавляют поверх этого слой progressive disclosure: reusable procedural context, который загружается только по мере надобности. MCP добавляет комплементарный слой live context: внешние системы, которые можно спрашивать и дергать без copy-paste их содержимого в transcript. Skills добавляют поверх этого слой progressive disclosure: reusable procedural context, который загружается только по мере надобности. MCP добавляет комплементарный слой live context: внешние системы, которые можно спрашивать и дергать без copy-paste их содержимого в transcript.

## Поддерживающие источники

- [[russian/sources/2025-anthropic-effective-context-engineering#Summary]]
- [[russian/sources/2025-anthropic-claude-code-best-practices#Summary]]
- [[russian/sources/2026-openai-harness-engineering#Summary]]
- [[russian/sources/2026-karpathy-llm-knowledge-bases-snippet#Summary]]
- [[russian/sources/2026-karpathy-idea-file-llm-wiki-snippet#Summary]]

## Связанные страницы

- [[russian/index]]
- [[russian/concepts/Repository as System of Record]]
- [[russian/concepts/Idea File]]
- [[russian/concepts/LLM Wiki]]
- [[russian/concepts/Subagents]]
- [[russian/concepts/Agent Skills]]
- [[russian/concepts/Model Context Protocol]]
- [[russian/concepts/Agent Skills]]
- [[russian/concepts/Model Context Protocol]]
- [[russian/concepts/Agent Skills]]
- [[russian/concepts/Model Context Protocol]]
- [[russian/concepts/Agent Skills]]
- [[russian/concepts/Model Context Protocol]]
- [[russian/concepts/Agent Skills]]
- [[russian/concepts/Model Context Protocol]]
