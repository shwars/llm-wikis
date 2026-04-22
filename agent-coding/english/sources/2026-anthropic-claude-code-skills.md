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
lang: english
---
# Extend Claude with skills

## Summary

The Claude Code skills docs are one of the strongest explanations of why skills matter to coding agents: they keep procedures, reference material, and helper scripts out of the hot context until needed. This is the key conceptual bridge between skills and context engineering.

## Structure Map

- `[[#Summary]]`: what Claude Code means by skills and why that matters.
- `[[#Key Claims]]`: the main conceptual and product claims.
- `[[#Notable Practices]]`: the operational lessons for coding teams.
- `[[#Related Pages]]`: which wiki pages it should update.

## Key Claims

- Skills solve a different problem than CLAUDE.md or AGENTS.md by loading on demand.
- Skills can include instructions, helper files, scripts, and invocation policies in one portable package.
- Subagent execution and allowed-tools policies make skills part of execution design, not only prompt design.

## Notable Practices

- Move repeatable procedures out of giant root instruction files into skills.
- Keep skill entrypoints short and defer heavy reference material to supporting files.
- Use explicit invocation control for side-effectful skills such as deploy or commit flows.

## Related Pages

- [[english/concepts/Agent Skills]]
- [[english/analyses/MCP vs Agent Skills]]
- [[english/analyses/Useful Skills for Coding Agents]]
