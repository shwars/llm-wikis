# llm-wikis

LLM-authored, Obsidian-friendly wikis on multiple topics.

## Current wikis

- [[future/english/home|future]]: research notebook on the future of AI
- [[future/russian/home|future (Russian)]]: synchronized Russian mirror of the same wiki

## Repo shape

- `AGENTS.md`: global workflow, schema, and maintenance rules
- `<topic>/AGENTS.md`: topic-specific taxonomy and ingest guidance shared by both language trees
- `<topic>/raw/`: immutable source captures
- `<topic>/english/`: English wiki tree
- `<topic>/russian/`: Russian wiki tree
- `<topic>/<language>/sources/`: source summary notes keyed to raw files
- `<topic>/<language>/concepts/`, `people/`, `organizations/`, `themes/`, `analyses/`: enduring wiki pages
- `<topic>/<language>/home.md`, `index.md`, `theses.md`, `open_questions.md`, `log.md`: core navigation and maintenance pages

## Bilingual contract

- English and Russian trees use the same English filenames and the same relative paths.
- Every article that exists in one language tree must exist in the other.
- Links stay within their local language tree so each wiki is independently navigable in Obsidian.
- Raw files remain shared at the topic root.
