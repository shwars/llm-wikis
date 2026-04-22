---
type: source
source_key: 2026-hermes-agent-skills-system
title: "Hermes Agent skills system docs snapshot"
author: Nous Research
year: 2026
original_language: en
raw_path: agent-coding/raw/Hermes Agent - Skills System - 2026.md
status: seeded
updated: 2026-04-22
tags:
  - ai-assisted-software-development
  - hermes-agent
  - skills
  - progressive-disclosure
lang: russian
---
# Hermes Agent skills system docs snapshot

## Сводка

Docs по skills в Hermes проясняют token economics и trust-модель навыков. Skills здесь — не giant always-on instructions, а on-demand knowledge packages с registries, trust levels и переиспользуемыми поверхностями вызова.

## Карта заметки

- `[[#Сводка]]`: что Hermes называет skills и почему это важно.
- `[[#Ключевые тезисы]]`: главные механики и trust-тезисы.
- `[[#Практики и уроки]]`: переиспользуемые уроки дизайна.
- `[[#Связанные страницы]]`: куда в вики должен ссылаться этот источник.

## Ключевые тезисы

- Progressive disclosure — одна из главных причин, почему skills масштабируются лучше, чем гигантские статические instruction files.
- Хорошая skill-system требует provenance и trust-tiers, а не только installability.
- Slash-command invocation и natural-language invocation могут жить на одной и той же skill-подложке.

## Практики и уроки

- Используйте registries и provenance-metadata для переиспользуемых skill-catalogs.
- Разделяйте bundled trust и community trust для third-party skills.
- Загружайте только body skill или reference-files, которые нужны текущей задаче.

## Связанные страницы

- [[russian/concepts/Agent Skills]]
- [[russian/analyses/Useful Skills for Coding Agents]]
- [[russian/themes/Context Management and Agent Memory]]
