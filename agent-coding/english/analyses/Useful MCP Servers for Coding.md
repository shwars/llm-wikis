---
type: analysis
topic: agent-coding
lang: english
status: active
updated: 2026-04-22
source_keys:
  - 2026-mcp-server-concepts
  - 2026-mcp-example-servers
  - 2026-mcp-registry-about
  - 2026-anthropic-claude-code-mcp
  - 2026-hermes-agent-mcp
aliases:
  - useful mcp servers
related:
  - "[[english/concepts/Model Context Protocol]]"
  - "[[english/themes/Tooling Landscape]]"
  - "[[english/index]]"
---
# Useful MCP Servers for Coding

## English Abstract

A curated list of MCP server categories and representative server patterns that are especially useful in coding workflows.

## Current Synthesis

The highest-value MCP servers in coding scenarios are the ones that collapse stale copy-paste loops. Instead of pasting issue text, dashboard screenshots, or database snippets into chat, the agent can fetch or act on the live systems directly. The curated list below favors servers that shorten the path from intent to verified engineering action.

## Repo, Filesystem, and Git

- `Filesystem server`: read and manipulate files with explicit roots. Good for local repo work and artifact handling. See [[english/sources/2026-mcp-example-servers#Summary]].
- `Git server`: inspect and manipulate repository history, diffs, and repo metadata. See [[english/sources/2026-mcp-example-servers#Summary]].
- `Fetch server`: bring web documentation or remote text into a usable form for the model. See [[english/sources/2026-mcp-example-servers#Summary]].

## Issue and Project Systems

- `GitHub server`: useful for issues, pull requests, code review, and repo-adjacent workflows. See [[english/sources/2026-mcp-server-concepts#Key Claims]].
- `Jira or Linear server`: useful when the coding workflow begins in tickets rather than in code. Anthropic explicitly highlights issue-tracker examples. See [[english/sources/2026-anthropic-claude-code-mcp#Summary]].

## Docs and Knowledge Bases

- `Docs or drive server`: good for design docs, specs, architecture notes, and company references. See [[english/sources/2026-anthropic-claude-code-mcp#Summary]].
- `Memory server`: useful when the client wants persistent externalized state rather than only repo-local markdown. See [[english/sources/2026-mcp-example-servers#Summary]].

## Databases

- `Postgres or database server`: high leverage for debugging, feature analysis, migrations, and user sampling. See [[english/sources/2026-mcp-server-concepts#Key Claims]] and [[english/sources/2026-anthropic-claude-code-mcp#Summary]].

## Browser, QA, and Design

- `Browser or automation server`: valuable for frontend testing, QA, and web flows when the agent needs live page access.
- `Figma or design server`: valuable for pulling design context and assets into implementation loops. See [[english/sources/2026-anthropic-claude-code-mcp#Summary]].

## Observability and Incidents

- `Monitoring or Sentry-style server`: useful for inspecting errors, feature health, and regressions while fixing bugs. Anthropic highlights monitoring examples directly. See [[english/sources/2026-anthropic-claude-code-mcp#Summary]].
- `Slack server`: useful when incident context and engineering coordination already live in team chat. See [[english/sources/2026-mcp-server-concepts#Key Claims]].

## Deployment and Cloud

- `Cloud provider or deployment server`: useful when the same agent should inspect configs, deploy changes, or query runtime state.
- `Hermes as an MCP server`: useful as a bridge when a coding agent needs to read or send messages through Hermes-managed channels. See [[english/sources/2026-hermes-agent-mcp#Summary]].

## Selection Rules

- Prefer bounded, high-signal servers over giant tool surfaces.
- Review server provenance, metadata, and execution instructions before trusting it.
- Use MCP where freshness matters most: issue state, docs, dashboards, databases, design assets, or cloud state.

## Related Pages

- [[english/concepts/Model Context Protocol]]
- [[english/analyses/MCP vs Agent Skills]]
- [[english/themes/Tooling Landscape]]
