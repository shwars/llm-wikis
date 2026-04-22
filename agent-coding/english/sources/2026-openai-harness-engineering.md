---
type: source
source_key: 2026-openai-harness-engineering
title: "Harness engineering: leveraging Codex in an agent-first world"
author: OpenAI
year: 2026
original_language: en
raw_path: agent-coding/raw/OpenAI - Harness Engineering - 2026.md
status: seeded
updated: 2026-04-21
tags:
  - lasd
  - openai
  - harness
  - best-practices
lang: english
---
# Harness engineering: leveraging Codex in an agent-first world

## Summary

Harness engineering is a strong statement that the key scarce skill in AI-Assisted Software Development is shifting from directly writing code toward designing the environment in which agents can reliably write code. The repo becomes a control plane: specs, plans, quality bars, and safety constraints are machine-readable artifacts the agent can act on.

## Structure Map

- `[[#Summary]]`: what the source is and why it matters for AI-Assisted Software Development.
- `[[#Key Claims]]`: the main historical, product, or theoretical claims.
- `[[#Notable Practices]]`: the reusable operational lessons.
- `[[#Related Pages]]`: the concepts, tools, and themes this source updates.

## Key Claims

- Humans steer; agents execute.
- Structured repo knowledge is a core leverage point in agent-first engineering.
- Design, reliability, and security docs should be explicit first-class inputs.

## Notable Practices

- Treat the repository as a knowledge system, not just a code bucket.
- Write DESIGN.md, plan docs, and quality docs for agents as well as humans.
- Build feedback loops so agents can self-correct before a human intervenes.

## Related Pages

- [[english/analyses/Best Practices Playbook - AI-Assisted Software Development]]
- [[english/themes/Design, Specification, and Intent Artifacts]]
- [[english/concepts/Repository as System of Record]]
- [[english/concepts/Design System Markdown]]
