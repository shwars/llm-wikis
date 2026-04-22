---
type: log
topic: agent-coding
lang: english
status: active
updated: 2026-04-21
source_keys:
  []
aliases:
  - log
related:
  - "[[english/index]]"
  - "[[english/home]]"
  - "[[english/theses]]"
---
# Log

## English Abstract

Append-only operational record for ingest, query, and lint work in the `agent-coding` wiki.

## Current Synthesis

The initial build seeds a bilingual AI-Assisted Software Development topic with raw captures, source summaries, enduring pages, a tool matrix, a history note, and a best-practices playbook.

## Related Pages

- [[english/home]]
- [[english/index]]
- [[english/theses]]
- [[english/open_questions]]

## [2026-04-21] scaffold | Create the agent-coding topic

- Created the shared `raw/`, `english/`, and `russian/` trees plus the topic-level guide.
- Seeded the standard subtree and mirrored the article inventory across both languages.

## [2026-04-21] ingest | Historical, theory, tooling, and snippet corpus

- Added 31 raw captures and matching source-summary notes in both language trees.
- Covered milestones from Copilot and ChatGPT through Codex, Claude Code practices, Antigravity, design agents, and knowledge-base patterns.
- Explicitly labeled snippet and secondary-summary captures where full raw social posts were not accessible.

## [2026-04-21] query | Build enduring synthesis pages

- Added theme, concept, people, and organization pages for the initial AI-Assisted Software Development map.
- Added durable analyses: historical roadmap, tool matrix, concept graph, and best-practices playbook.
- Linked all enduring pages back into both language-local indexes.

## [2026-04-21] query | Rename the umbrella term and sharpen the history framing

- Renamed the core umbrella term to `AI-Assisted Software Development` across the bilingual wiki layer without changing the immutable `raw/` corpus.
- Renamed the history, tool-matrix, best-practices, and umbrella-concept pages to use the explicit term instead of the acronym.
- Added a new staged history section that starts with browser-based LLM use, then code completion, and then agent coding and multi-agent delegation.

## [2026-04-21] lint | Initial structural audit

- Checked for orphan pages, uncited major claims, missing backlinks from navigation pages, and English/Russian parity drift.
- Confirmed that the standard page inventory exists in both language trees and that every enduring page is reachable from `index.md`.

## [2026-04-22] ingest | General-use agents, MCP, and skills corpus

- Added raw captures and mirrored source summaries for OpenClaw, Hermes Agent, OpenCrust, Memoh, Goose, MCP docs, Claude Code MCP/skills docs, the OpenAI skills catalog, and the Agent Skills standard.
- Added the topic-specific `tools/` subtree in both language trees.

## [2026-04-22] query | Add general-use agents and extensibility pages

- Added durable tool pages for OpenClaw, Hermes Agent, OpenCrust, Memoh, and Goose.
- Added new concept and analysis pages for Model Context Protocol, Agent Skills, their differences, and curated coding-oriented catalogs.
- Updated home, theses, themes, the tool matrix, and the concept graph to connect the new cluster back into the existing wiki.

## [2026-04-22] lint | Structural and linkage audit after schema extension

- Re-checked reachability from `index.md`, parity between `english/` and `russian/`, and cross-link density for the new tools, concepts, and analyses.
- Flagged third-party skill and MCP trust as a durable open question rather than flattening the risk away.

## [2026-04-22] ingest | Coding-tools source expansion

- Added raw captures and mirrored source summaries for Claude Code overview, Claude Desktop, Gemini Code Assist overview, and GigaCode's inline-assistant and CodeChat docs.
- Used current official or primary documentation to support the new coding-tools catalog rather than relying only on secondary synthesis.

## [2026-04-22] query | Readability and coding-tools catalog refresh

- Reworked high-traffic pages to use aliased wikilinks and added more in-text links so concepts, tools, and analyses are woven into the prose instead of living only in `Related Pages`.
- Added durable tool pages for the major coding tools now covered by the corpus and added the new `Coding Tools by Style and Maturity - 2026` analysis.
- Cleaned duplicated sections in `home.md`, `theses.md`, `Tooling Landscape.md`, the existing tool matrix, and synced the Russian history Mermaid to the edited English version.

## [2026-04-22] lint | Link readability, parity, and duplication pass

- Re-checked English/Russian parity after the expanded `tools/` catalog and the new source notes.
- Verified that targeted high-traffic pages now use readable aliased wikilinks and that the duplicated synthesis blocks were removed.

## [2026-04-22] lint | Table-link rendering repair

- Added a topic-specific rule to `agent-coding/AGENTS.md`: use aliased wikilinks in prose, but use Markdown links inside Markdown tables.
- Repaired all current tool-comparison tables in both language trees and rebuilt the malformed Russian `General Use Agents - 2026` table with table-safe links.
- Re-checked table rows for aliased wikilinks, malformed pipe splits, parity drift, and accidental cross-language links.
