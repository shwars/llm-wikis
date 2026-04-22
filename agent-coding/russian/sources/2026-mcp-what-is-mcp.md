---
type: source
source_key: 2026-mcp-what-is-mcp
title: "What is the Model Context Protocol (MCP)?"
author: Model Context Protocol
year: 2026
original_language: en
raw_path: agent-coding/raw/MCP - What is MCP - 2026.md
status: seeded
updated: 2026-04-22
tags:
  - ai-assisted-software-development
  - mcp
  - protocol
  - extensions
lang: russian
---
# What is the Model Context Protocol (MCP)?

## Сводка

Введение в MCP — это каноническое определение протокола: открытый стандарт, который соединяет AI-приложения с внешними системами, источниками данных, tools и workflows. Он важен тем, что показывает MCP как слой переносимости между клиентами, а не как vendor-specific plugin-system.

## Карта заметки

- `[[#Сводка]]`: базовое определение MCP и почему оно важно.
- `[[#Ключевые тезисы]]`: главные концептуальные тезисы.
- `[[#Практики и уроки]]`: основные уроки для создателей агентов.
- `[[#Связанные страницы]]`: страницы, зависящие от этого источника.

## Ключевые тезисы

- MCP — это инфраструктура для interoperability между AI-clients и внешними системами.
- Протокол описывает connection-surfaces, а не одну конкретную модель или app.
- MCP охватывает tools, data и workflows, а не только function-calling в узком смысле.

## Практики и уроки

- Используйте MCP, когда нужна переносимость между разными agent-clients.
- Думайте о MCP как об integration plumbing, а не как о procedural workflow memory.
- Разделяйте concerns протокола и application-specific prompt behavior.

## Связанные страницы

- [[russian/concepts/Model Context Protocol]]
- [[russian/analyses/MCP vs Agent Skills]]
- [[russian/analyses/Useful MCP Servers for Coding]]
