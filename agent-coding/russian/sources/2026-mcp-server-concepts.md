---
type: source
source_key: 2026-mcp-server-concepts
title: "Understanding MCP servers"
author: Model Context Protocol
year: 2026
original_language: en
raw_path: agent-coding/raw/MCP - Server Concepts - 2026.md
status: seeded
updated: 2026-04-22
tags:
  - ai-assisted-software-development
  - mcp
  - servers
  - tools
lang: russian
---
# Understanding MCP servers

## Сводка

Страница о server concepts объясняет внутреннюю грамматику MCP: tools, resources и prompts, у каждого из которых своя модель контроля. Это важно, потому что многие путаницы вокруг MCP исчезают, если различать эти три примитива.

## Карта заметки

- `[[#Сводка]]`: что такое MCP server и почему он важен.
- `[[#Ключевые тезисы]]`: главные концептуальные тезисы.
- `[[#Практики и уроки]]`: операционные уроки для создателей агентов.
- `[[#Связанные страницы]]`: какие страницы должны сюда ссылаться.

## Ключевые тезисы

- MCP servers — это не только tool endpoints; они могут также отдавать resources и prompts.
- Tools управляются моделью, тогда как resources часто управляются клиентом или приложением.
- Уже сегодня coding-relevant классы серверов включают filesystem, database, GitHub и Slack.

## Практики и уроки

- Явно моделируйте extension-surface: tools для действий, resources для контекста, prompts для reusable entrypoints.
- Используйте минимальный примитив, который чисто решает задачу.
- Не превращайте каждую внешнюю capability в tool-call, если resource будет безопаснее или дешевле.

## Связанные страницы

- [[russian/concepts/Model Context Protocol]]
- [[russian/analyses/Useful MCP Servers for Coding]]
- [[russian/themes/Agent Harnesses and Execution Loops]]
