# Agent Coding Wiki Guide

This topic wiki studies the history and current state of AI-Assisted Software Development, with `vibe coding` treated as one cultural style inside the broader field of agent-assisted software development.

## Scope

Center the wiki on:

- history of coding assistance, from code completion to multi-agent software work
- core AI-Assisted Software Development components: problem specification, context management, agent management, and automatic debugging loops
- current best practices for harnesses, repository memory, design artifacts, verification, and delegation
- tool landscape comparisons across CLI, IDE, background, design-oriented systems, and general-use agents
- extension layers such as MCP and Agent Skills
- extension of coding-agent harnesses into non-coding technical and knowledge-work tasks

Keep adjacent material only when it helps explain how agents actually get useful work done.

## Topic contract

- `agent-coding/raw/` is the shared immutable corpus.
- `agent-coding/english/` and `agent-coding/russian/` are synchronized mirrors of the same wiki.
- Every wiki article must exist in both language trees at the same relative path and with the same English filename.
- English notes use `lang: english` and link only within `agent-coding/english/`.
- Russian notes use `lang: russian` and link only within `agent-coding/russian/`.
- Changes to article inventory, citations, and related-page topology must be mirrored in both language trees in the same pass when feasible.
- Preserve disagreement and uncertainty where current tool claims outrun solid evidence.

## Language subtree layout

Each language tree contains:

- `sources/`: source summaries keyed to raw captures
- `concepts/`: reusable terms and operating patterns
- `tools/`: product and tool pages for this topic when one tool needs a durable article
- `people/`: notable individuals shaping the field
- `organizations/`: tool builders and research groups
- `themes/`: durable topic pages
- `analyses/`: cross-source syntheses and matrices
- `home.md`, `index.md`, `theses.md`, `open_questions.md`, `log.md`: operating pages

## Note types

- `tool` is a valid enduring-page type for this topic.
- Tool pages use the same enduring-page frontmatter contract as concept, theme, analysis, and organization pages.

## Link formatting

- Use aliased wikilinks such as `[[english/concepts/Model Context Protocol|Model Context Protocol]]` in normal prose, bullets, and navigation sections.
- Use Markdown links inside Markdown tables, because the `|` in aliased wikilinks breaks table parsing.
- In English table cells, prefer relative links such as `[Model Context Protocol](<../concepts/Model Context Protocol.md>)` when linking from a note in `analyses/` or `themes/`.
- In Russian table cells, use the same table-safe Markdown-link pattern with paths relative to the Russian note location.
- Keep source-summary citations as wikilinks outside tables unless the citation itself must appear in a table cell.

## Seed themes

- `Agentic Coding and Vibe Coding`
- `Context Management and Agent Memory`
- `Design, Specification, and Intent Artifacts`
- `Agent Harnesses and Execution Loops`
- `Verification, Testing, and Automatic Debugging`
- `Tooling Landscape`
- `Beyond Coding Tasks`
- `Labor, Roles, and Team Structure`

## Durable questions for this wiki

- Which parts of AI-Assisted Software Development are hype, and which parts are durable operating practice?
- What does a good agent harness actually need besides a strong model?
- How should teams manage context and memory as sessions get longer and more parallel?
- Which tools are best understood as pair programmers, which as background agents, and which as design or computer-use systems?
- Which non-coding tasks share the same harness shape as coding agents?
- How are general-use agents and coding agents converging through memory, skills, MCP, and computer use?

## Source key policy

Use `YYYY-author-short-title` where possible. For docs snapshots and snippet captures, prefer the date of the captured or published artifact that anchors the source.

## Ingest rules for this corpus

- Be explicit when a raw capture is a snippet, excerpt, or secondary summary instead of a full-text capture.
- Keep the difference between official product docs, benchmark notes, and social-media pattern formation visible.
- When a source contains product claims that exceed public evidence, surface that uncertainty in synthesis pages instead of flattening it away.
- When a note is added to one language tree, create or update its counterpart in the other tree before closing the task.
