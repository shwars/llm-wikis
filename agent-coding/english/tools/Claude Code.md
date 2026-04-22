---
type: tool
topic: agent-coding
lang: english
status: active
updated: 2026-04-22
source_keys:
  - 2026-anthropic-claude-code-overview
  - 2025-anthropic-claude-code-best-practices
  - 2026-anthropic-claude-code-mcp
  - 2026-anthropic-claude-code-skills
aliases:
  - claude code
related:
  - "[[english/themes/Tooling Landscape]]"
  - "[[english/analyses/Best Practices Playbook - AI-Assisted Software Development]]"
  - "[[english/concepts/Model Context Protocol]]"
---
# Claude Code

## English Abstract

Anthropic's terminal-first coding agent for planning, editing, verifying, and automating engineering work.

## Current Synthesis

[[english/tools/Claude Code|Claude Code]] is one of the clearest flagship examples of [[english/themes/Agent Harnesses and Execution Loops|agentic development]] in the terminal. Its core pattern is a tight loop of repository inspection, code changes, command execution, verification, and optional extension through [[english/concepts/Model Context Protocol|MCP]] and [[english/concepts/Agent Skills|Agent Skills]].

## Tool Profile

- `Primary surface`: CLI / terminal.
- `Maturity stage`: Agentic development.
- `Autonomy model`: interactive agent with tool use, subagents, and verification loops.
- `Strengths`: repo navigation, direct action, scriptability, MCP, skills, and strong operational guidance.
- `Limits`: still demands explicit supervision, good task slicing, and careful permission boundaries.

## Supporting Evidence

- [[english/sources/2026-anthropic-claude-code-overview#Summary|Claude Code overview]]
- [[english/sources/2025-anthropic-claude-code-best-practices#Summary|Claude Code best practices]]
- [[english/sources/2026-anthropic-claude-code-mcp#Summary|Claude Code MCP]]
- [[english/sources/2026-anthropic-claude-code-skills#Summary|Claude Code skills]]

## Related Pages

- [[english/themes/Tooling Landscape|Tooling Landscape]]
- [[english/analyses/Best Practices Playbook - AI-Assisted Software Development|Best Practices Playbook - AI-Assisted Software Development]]
- [[english/concepts/Model Context Protocol|Model Context Protocol]]
- [[english/concepts/Agent Skills|Agent Skills]]
