---
type: source
source_key: 2026-anthropic-claude-code-mcp
title: "Connect Claude Code to tools via MCP"
author: Anthropic
year: 2026
original_language: en
raw_path: agent-coding/raw/Anthropic - Claude Code MCP - 2026.md
status: seeded
updated: 2026-04-22
tags:
  - ai-assisted-software-development
  - anthropic
  - claude-code
  - mcp
lang: english
---
# Connect Claude Code to tools via MCP

## Summary

The Claude Code MCP docs are a practical bridge between the MCP protocol and daily engineering work. They show why coding teams care: issue trackers, monitoring, databases, Figma, Slack, and workflow automation all become reachable in the same agent loop.

## Structure Map

- `[[#Summary]]`: what the docs cover and why they matter.
- `[[#Key Claims]]`: the main claims about MCP in coding workflows.
- `[[#Notable Practices]]`: the practical lessons.
- `[[#Related Pages]]`: the relevant wiki pages.

## Key Claims

- MCP is no longer peripheral to coding agents; it is a main route to engineering context and action.
- The most valuable coding use cases often cross issue trackers, docs, monitoring, design, and communication systems.
- Third-party MCP servers are powerful enough to require explicit trust and review.

## Notable Practices

- Use MCP to pull live engineering context instead of copy-pasting stale data into chat.
- Prefer bounded, high-signal servers rather than exposing everything at once.
- Review third-party MCP servers like code dependencies, not like harmless prompt snippets.

## Related Pages

- [[english/concepts/Model Context Protocol]]
- [[english/analyses/Useful MCP Servers for Coding]]
- [[english/themes/Tooling Landscape]]
