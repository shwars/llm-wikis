---
type: source
source_key: 2025-anthropic-claude-code-best-practices
title: Claude Code best practices
author: Anthropic
year: 2025
original_language: en
raw_path: agent-coding/raw/Anthropic - Claude Code Best Practices - 2025.md
status: seeded
updated: 2026-04-21
tags:
  - lasd
  - best-practices
  - claude-code
  - anthropic
lang: russian
---
# Claude Code best practices

## Сводка

Руководство по best practices для Claude Code превращает agentic coding из расплывчатого обещания в рабочий метод: verification first, отделение исследования от исполнения, хранение переиспользуемого знания о репозитории, контроль разрешений и агрессивное управление контекстом. Это практический blueprint для высокосигнальных AI-Assisted Software Development-сессий.

## Карта заметки

- `[[#Сводка]]`: что это за источник и почему он важен для AI-Assisted Software Development.
- `[[#Ключевые тезисы]]`: главные исторические, продуктовые или теоретические тезисы.
- `[[#Практики и уроки]]`: переиспользуемые операционные уроки.
- `[[#Связанные страницы]]`: какие концепты, инструменты и темы обновляет источник.

## Ключевые тезисы

- Verification — самый сильный множитель качества.
- Explore-plan-code безопаснее, чем сразу редактировать нетривиальные задачи.
- Локальные инструкции и переиспользуемые workflows внутри репозитория накапливают ценность со временем.

## Практики и уроки

- Давайте агенту тесты, скриншоты или явные команды успеха.
- Используйте CLAUDE.md, hooks и skills как инфраструктуру управления контекстом.
- Используйте subagents и параллельные сессии, чтобы сохранять контекст и масштабировать работу.

## Связанные страницы

- [[russian/analyses/Best Practices Playbook - AI-Assisted Software Development]]
- [[russian/themes/Verification, Testing, and Automatic Debugging]]
- [[russian/themes/Context Management and Agent Memory]]
- [[russian/concepts/Agent Legibility]]
