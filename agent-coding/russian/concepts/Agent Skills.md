---
type: concept
topic: agent-coding
lang: russian
status: active
updated: 2026-04-22
source_keys:
  - 2026-openclaw-skills-docs
  - 2026-hermes-agent-skills-system
  - 2026-anthropic-claude-code-skills
  - 2026-openai-skills-catalog
  - 2026-agent-skills-overview
aliases:
  - skills
  - agent skills
related:
  - "[[russian/analyses/MCP vs Agent Skills]]"
  - "[[russian/analyses/Useful Skills for Coding Agents]]"
  - "[[russian/themes/Context Management and Agent Memory]]"
---
# Agent Skills

## Кратко

Переносимые папки из instructions, resources, scripts и metadata, которые агент может discover-ить и загружать по требованию как reusable procedural knowledge.

## Текущий синтез

Agent Skills — это procedural memory packages для агентов. В отличие от root instruction-file, который загружается в каждой сессии, skill обычно активируется только тогда, когда действительно релевантна. Это держит горячий контекст небольшим, но все равно делает большие playbooks, helper-scripts, examples и policies доступными в нужный момент. Skills могут быть personal, project-local, workspace-local или catalog-installed и все чаще следуют открытым форматам, работающим между продуктами.

## Поддерживающие источники

- [[russian/sources/2026-openclaw-skills-docs#Сводка]]
- [[russian/sources/2026-hermes-agent-skills-system#Сводка]]
- [[russian/sources/2026-anthropic-claude-code-skills#Сводка]]
- [[russian/sources/2026-agent-skills-overview#Сводка]]

## Связанные страницы

- [[russian/analyses/MCP vs Agent Skills]]
- [[russian/analyses/Useful Skills for Coding Agents]]
- [[russian/themes/Context Management and Agent Memory]]
