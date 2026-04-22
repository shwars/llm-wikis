---
type: source
source_key: 2026-mcp-what-is-mcp
title: "What is the Model Context Protocol (MCP)?"
author: Model Context Protocol
year: 2026
original_language: en
raw_path: agent-coding/raw/MCP - What is MCP - 2026.md
status: seeded
updated: 2026-04-22
tags:
  - ai-assisted-software-development
  - mcp
  - protocol
  - extensions
lang: english
---
# What is the Model Context Protocol (MCP)?

## Summary

The MCP intro is the canonical umbrella definition: an open protocol that connects AI applications to external systems such as data sources, tools, and workflows. It matters because it explains why MCP is a portability layer across clients rather than a vendor-specific plugin system.

## Structure Map

- `[[#Summary]]`: the core definition of MCP and why it matters.
- `[[#Key Claims]]`: the principal conceptual claims.
- `[[#Notable Practices]]`: the main lessons for agent builders.
- `[[#Related Pages]]`: the pages that depend on this source.

## Key Claims

- MCP is infrastructure for interoperability across AI clients and external systems.
- The protocol is about connection surfaces, not about one specific model or app.
- MCP spans tools, data, and workflow surfaces rather than only RPC-style function calls.

## Notable Practices

- Use MCP when you want portability across agent clients.
- Think of MCP as integration plumbing, not as procedural workflow memory.
- Separate protocol concerns from application-specific prompt behavior.

## Related Pages

- [[english/concepts/Model Context Protocol]]
- [[english/analyses/MCP vs Agent Skills]]
- [[english/analyses/Useful MCP Servers for Coding]]
