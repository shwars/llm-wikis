# LLM Wikis Repository Guide

This repository is a monorepo of topic-specific LLM Wikis. Each top-level topic folder must be independently operable as an Obsidian-friendly wiki.

## Core contract

- Every topic folder is self-contained.
- Every topic folder contains shared raw material plus two synchronized language wikis: `english/` and `russian/`.
- `raw/` is immutable source material. Do not edit, rewrite, normalize, or delete raw files during ingest.
- The wiki layer is LLM-maintained Markdown that synthesizes, links, and cites the raw corpus.
- Navigation must work in plain Obsidian without external services.
- Every generated note must be reachable from the language-local `index.md`.
- `english/` and `russian/` must keep the same folder inventory, the same file inventory, and the same relative paths.

## Standard topic structure

Each topic folder should contain:

- `raw/`
- `english/`
- `russian/`
- `AGENTS.md`

Each language subtree should contain:

- `sources/`
- `concepts/`
- `people/`
- `organizations/`
- `themes/`
- `analyses/`
- `home.md`
- `index.md`
- `theses.md`
- `open_questions.md`
- `log.md`

## Note types

- `source`: one note per raw file; the stable bridge between raw material and the rest of the wiki
- `concept`: reusable ideas, models, terms, and hypotheses
- `person`: individuals whose views shape the topic
- `organization`: labs, institutions, governments, or projects
- `theme`: enduring cross-source topic pages
- `analysis`: durable answers to recurring multi-source questions
- `home`, `index`, `theses`, `open_questions`, `log`: topic operating pages

## Frontmatter rules

Source notes must include:

- `type`
- `source_key`
- `title`
- `author`
- `year`
- `original_language`
- `raw_path`
- `status`
- `updated`
- `tags`
- `lang`

Enduring pages must include:

- `type`
- `topic`
- `lang`
- `status`
- `updated`
- `source_keys`
- `aliases`
- `related`

## Naming and language

- Use English canonical file names and English slugs in both language trees.
- `future/english/.../Some Note.md` and `future/russian/.../Some Note.md` should refer to the same wiki article.
- English notes should use `lang: english`.
- Russian notes should use `lang: russian`.
- Russian identity belongs in titles, prose, and `aliases`, not in translated filenames.
- Keep language trees synchronized whenever an article is created, renamed, moved, or deleted.

## Linking and citation rules

- Notes inside `english/` should link only within the English tree.
- Notes inside `russian/` should link only within the Russian tree.
- Cross-language links are optional and should never be required for navigation.
- Cite with Obsidian wikilinks to source-summary pages and section anchors.
- Do not leave important claims uncited.
- For essays and transcripts, cite section headings where possible.
- For books, cite chapter-level anchors or explicitly named subsections.
- Prefer citations that point to a stable summary note instead of directly to raw files.
- `raw_path` should always point to the shared topic root raw file, for example `future/raw/...`.

## Operating workflow

### Ingest

Ingest is guided and source-by-source.

For each new source:

1. Leave the raw file untouched.
2. Create or update exactly one source-summary note in `english/sources/` and the matching note in `russian/sources/`.
3. Update only the concept, person, organization, or theme pages materially changed by that source, and apply the update to both language trees.
4. Update both language-local `index.md` files.
5. Append matching entries to both language-local `log.md` files.
6. Add or sharpen open questions only when the source genuinely changes the research frontier, and mirror the change in both languages.

### Query

- Answer from the wiki first.
- If the answer is durable and likely to recur, create or update matching `analyses/` notes in both language trees.
- Link the analysis back into the relevant enduring pages and both language-local indexes where appropriate.
- Append matching query entries to both language-local logs.

### Lint

Lint checks should look for:

- orphan pages
- uncited claims
- stale synthesis pages superseded by newer evidence
- contradictory claims that have not been surfaced explicitly
- missing backlinks from high-value pages
- open questions that now have enough evidence to deserve their own page
- parity drift between `english/` and `russian/`

Record lint passes in both language-local logs and, when helpful, add a durable report in both `analyses/` trees.

## Creating a new topic wiki

When adding a new topic:

1. Create `raw/`, `english/`, `russian/`, and a topic-level `AGENTS.md`.
2. Seed the standard subtree inside both language folders.
3. Ingest raw sources into `english/sources/` and `russian/sources/` before creating a large number of downstream pages.
4. Keep the first version narrow, navigable, citation-heavy, and synchronized across both languages.
