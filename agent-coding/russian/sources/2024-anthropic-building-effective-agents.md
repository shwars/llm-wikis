---
type: source
source_key: 2024-anthropic-building-effective-agents
title: Building effective agents
author: Anthropic
year: 2024
original_language: en
raw_path: agent-coding/raw/Anthropic - Building Effective Agents - 2024.md
status: seeded
updated: 2026-04-21
tags:
  - lasd
  - theory
  - agents
  - anthropic
lang: russian
---
# Building effective agents

## Сводка

Эссе Anthropic об агентах дает компактную теорию эффективных агентных систем: держать базовый цикл простым, использовать composable patterns и добавлять автономию только там, где задача действительно выигрывает от нее. Для AI-Assisted Software Development это один из самых понятных мостов между общей теорией агентов и практическими harnesses для разработки ПО.

## Карта заметки

- `[[#Сводка]]`: что это за источник и почему он важен для AI-Assisted Software Development.
- `[[#Ключевые тезисы]]`: главные исторические, продуктовые или теоретические тезисы.
- `[[#Практики и уроки]]`: переиспользуемые операционные уроки.
- `[[#Связанные страницы]]`: какие концепты, инструменты и темы обновляет источник.

## Ключевые тезисы

- Простые агентные паттерны обычно превосходят переусложненные фреймворки.
- Параллелизация, routing и evaluator-loops являются повторно используемыми примитивами.
- Правильный уровень автономии зависит от структуры задачи.

## Практики и уроки

- Начинайте с минимального цикла, который умеет проверять прогресс.
- Используйте явные evaluator-stage там, где важно качество.
- Оставляйте высокую автономию задачам с большим исследованием и длинным горизонтом.

## Связанные страницы

- [[russian/themes/Agent Harnesses and Execution Loops]]
- [[russian/concepts/Orchestrator-Worker Pattern]]
- [[russian/concepts/Evaluator-Optimizer Pattern]]
- [[russian/organizations/Anthropic]]
