---
type: concept
topic: agent-coding
lang: english
status: active
updated: 2026-04-22
source_keys:
  - 2026-mcp-what-is-mcp
  - 2026-mcp-server-concepts
  - 2026-mcp-registry-about
  - 2026-mcp-example-servers
  - 2026-anthropic-claude-code-mcp
  - 2026-hermes-agent-mcp
aliases:
  - mcp
  - model context protocol
related:
  - "[[english/analyses/MCP vs Agent Skills]]"
  - "[[english/analyses/Useful MCP Servers for Coding]]"
  - "[[english/themes/Agent Harnesses and Execution Loops]]"
---
# Model Context Protocol

## English Abstract

An open protocol that lets AI applications connect to external tools, resources, prompts, and systems through standardized client-server boundaries.

## Current Synthesis

Model Context Protocol is best understood as integration plumbing for agents. It defines how hosts, clients, and servers exchange external capabilities. Tools let the model act, resources expose contextual data, and prompts provide reusable entrypoints. Local and remote servers can both participate, while registries and metadata make discovery and trust manageable. In coding workflows, MCP matters because it turns issue trackers, databases, design systems, docs, and observability into live context instead of copy-pasted background text.

## Supporting Evidence

- [[english/sources/2026-mcp-what-is-mcp#Summary]]
- [[english/sources/2026-mcp-server-concepts#Summary]]
- [[english/sources/2026-mcp-registry-about#Summary]]
- [[english/sources/2026-anthropic-claude-code-mcp#Summary]]

## Related Pages

- [[english/analyses/MCP vs Agent Skills]]
- [[english/analyses/Useful MCP Servers for Coding]]
- [[english/themes/Agent Harnesses and Execution Loops]]
