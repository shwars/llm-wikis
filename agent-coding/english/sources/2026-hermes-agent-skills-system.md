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
lang: english
---
# Hermes Agent skills system docs snapshot

## Summary

The Hermes skills docs clarify the token economics and trust model of skills. Skills are not giant always-on instructions; they are on-demand knowledge packages with registries, trust levels, and reusable invocation surfaces.

## Structure Map

- `[[#Summary]]`: what Hermes means by skills and why that matters.
- `[[#Key Claims]]`: the core mechanics and trust claims.
- `[[#Notable Practices]]`: the reusable design lessons.
- `[[#Related Pages]]`: where this source should link into the wiki.

## Key Claims

- Progressive disclosure is a key reason skills scale better than giant static instruction files.
- A good skills system needs provenance and trust tiers, not only installability.
- Slash-command invocation and natural-language invocation can coexist on one skill substrate.

## Notable Practices

- Use registries and provenance metadata for reusable skill catalogs.
- Separate bundled trust from community trust for third-party skills.
- Load only the skill body or reference files that are relevant to the current task.

## Related Pages

- [[english/concepts/Agent Skills]]
- [[english/analyses/Useful Skills for Coding Agents]]
- [[english/themes/Context Management and Agent Memory]]
