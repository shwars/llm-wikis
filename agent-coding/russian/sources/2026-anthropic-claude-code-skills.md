---
type: source
source_key: 2026-anthropic-claude-code-skills
title: "Extend Claude with skills"
author: Anthropic
year: 2026
original_language: en
raw_path: agent-coding/raw/Anthropic - Claude Code Skills - 2026.md
status: seeded
updated: 2026-04-22
tags:
  - ai-assisted-software-development
  - anthropic
  - claude-code
  - skills
lang: russian
---
# Extend Claude with skills

## Сводка

Docs по Claude Code skills — одно из лучших объяснений того, зачем coding agents вообще нужны навыки: они выносят процедуры, reference-material и helper-scripts из горячего контекста до тех пор, пока они не понадобятся. Это ключевой концептуальный мост между skills и context engineering.

## Карта заметки

- `[[#Сводка]]`: что Claude Code называет skills и почему это важно.
- `[[#Ключевые тезисы]]`: главные концептуальные и продуктовые тезисы.
- `[[#Практики и уроки]]`: операционные уроки для coding-команд.
- `[[#Связанные страницы]]`: какие страницы вики это должно обновить.

## Ключевые тезисы

- Skills решают другую проблему, чем CLAUDE.md или AGENTS.md, потому что загружаются только по мере необходимости.
- Skill может объединять instructions, helper-files, scripts и invocation-policies в одном переносимом пакете.
- Subagent execution и allowed-tools policies делают skills частью execution-design, а не только prompt-design.

## Практики и уроки

- Выносите повторяемые процедуры из гигантских root instruction-files в skills.
- Держите entrypoint skill коротким, а тяжелый reference-material переносите в supporting-files.
- Используйте явный invocation-control для side-effectful skills вроде deploy- или commit-flows.

## Связанные страницы

- [[russian/concepts/Agent Skills]]
- [[russian/analyses/MCP vs Agent Skills]]
- [[russian/analyses/Useful Skills for Coding Agents]]
