---
type: source
source_key: 2026-openclaw-skills-docs
title: "OpenClaw skills docs snapshot"
author: OpenClaw
year: 2026
original_language: en
raw_path: agent-coding/raw/OpenClaw - Skills Docs - 2026.md
status: seeded
updated: 2026-04-22
tags:
  - ai-assisted-software-development
  - openclaw
  - skills
  - extensions
lang: russian
---
# OpenClaw skills docs snapshot

## Сводка

Docs по skills в OpenClaw делают механизм навыков очень конкретным: versioned skill folders, порядок precedence, per-agent allowlists и environment injection. Это один из самых ясных продуктовых текстов о том, почему skills — не просто prompts, а операционные workflow packages.

## Карта заметки

- `[[#Сводка]]`: что такое skill-system и почему он важен.
- `[[#Ключевые тезисы]]`: главные продуктовые и операционные тезисы.
- `[[#Практики и уроки]]`: что команды могут переиспользовать из этого дизайна.
- `[[#Связанные страницы]]`: какие страницы должен обновить источник.

## Ключевые тезисы

- Skills — это переносимые procedural packages, а не только inline-инструкции.
- Видимость skills, precedence и allowlisting — это разные контрольные слои.
- Workspace-local и agent-local skills важны для изоляции multi-agent workflows.

## Практики и уроки

- Используйте явные правила precedence, когда одна и та же skill может существовать в нескольких копиях.
- Разделяйте discovery skills и permissioning skills.
- Для чувствительных или очень локальных процедур предпочитайте workspace- и project-scope.

## Связанные страницы

- [[russian/concepts/Agent Skills]]
- [[russian/analyses/MCP vs Agent Skills]]
- [[russian/analyses/Useful Skills for Coding Agents]]
