---
type: source
source_key: 2025-anthropic-effective-context-engineering
title: Effective context engineering for AI agents
author: Anthropic
year: 2025
original_language: en
raw_path: agent-coding/raw/Anthropic - Effective Context Engineering - 2025.md
status: seeded
updated: 2026-04-21
tags:
  - lasd
  - context
  - anthropic
  - theory
lang: russian
---
# Effective context engineering for AI agents

## Сводка

Это эссе переопределяет ключевую инженерную проблему вокруг агентов: задача уже не только в формулировке промптов, а в подборе правильного рабочего состояния во времени. Для AI-Assisted Software Development это означает относиться к контексту как к дефицитному капиталу и осознанно проектировать память, retrieval, compaction и decomposition.

## Карта заметки

- `[[#Сводка]]`: что это за источник и почему он важен для AI-Assisted Software Development.
- `[[#Ключевые тезисы]]`: главные исторические, продуктовые или теоретические тезисы.
- `[[#Практики и уроки]]`: переиспользуемые операционные уроки.
- `[[#Связанные страницы]]`: какие концепты, инструменты и темы обновляет источник.

## Ключевые тезисы

- Context engineering стал важнее, чем простая формулировка промптов.
- Больше токенов не значит лучше автоматически; качество контекста важнее объема.
- Длинногоризонтные задачи требуют явных стратегий pruning, summarizing и параллелизации контекста.

## Практики и уроки

- Предпочитайте небольшие high-signal instruction files вместо гигантских prompt blobs.
- Разделяйте поиск и синтез между несколькими агентами, когда exploration широкое.
- Используйте compaction, note files и явные memory artifacts до того, как контекст начнет гнить.

## Связанные страницы

- [[russian/themes/Context Management and Agent Memory]]
- [[russian/concepts/Repository as System of Record]]
- [[russian/concepts/LLM Wiki]]
- [[russian/concepts/Idea File]]
