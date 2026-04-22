---
type: source
source_key: 2026-mcp-server-concepts
title: "Understanding MCP servers"
author: Model Context Protocol
year: 2026
original_language: en
raw_path: agent-coding/raw/MCP - Server Concepts - 2026.md
status: seeded
updated: 2026-04-22
tags:
  - ai-assisted-software-development
  - mcp
  - servers
  - tools
lang: english
---
# Understanding MCP servers

## Summary

The server concepts page explains the internal grammar of MCP: tools, resources, and prompts, each with a different control model. It matters because many confusions about MCP disappear once those three primitives are distinguished.

## Structure Map

- `[[#Summary]]`: what an MCP server is and why it matters.
- `[[#Key Claims]]`: the main conceptual claims.
- `[[#Notable Practices]]`: the operational lessons for agent builders.
- `[[#Related Pages]]`: which pages should link here.

## Key Claims

- MCP servers are not only tool endpoints; they can also expose resources and prompts.
- Tools are model-controlled, while resources are often client- or application-controlled.
- Coding-relevant server classes already include filesystem, database, GitHub, and Slack examples.

## Notable Practices

- Model the extension surface explicitly: tools for action, resources for context, prompts for reusable entrypoints.
- Use the smallest primitive that solves the problem cleanly.
- Do not treat every external capability as a tool call when a resource would be safer or cheaper.

## Related Pages

- [[english/concepts/Model Context Protocol]]
- [[english/analyses/Useful MCP Servers for Coding]]
- [[english/themes/Agent Harnesses and Execution Loops]]
