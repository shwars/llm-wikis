# Future Wiki Guide

This topic wiki studies the future of AI as a research notebook, not as a generic encyclopedia.

## Scope

Center the wiki on:

- timelines and takeoff
- alignment and control
- upside and downside scenarios
- governance and state capacity
- economic and labor disruption
- biology, neuroscience, and human flourishing claims
- worldview disagreements between major AI thinkers

Keep adjacent material only when it informs those questions.

## Topic contract

- `future/raw/` is the shared immutable corpus.
- `future/english/` and `future/russian/` are synchronized mirrors of the same wiki.
- Every wiki article must exist in both language trees at the same relative path and with the same English filename.
- English notes use `lang: english` and link only within `future/english/`.
- Russian notes use `lang: russian` and link only within `future/russian/`.
- Changes to article inventory, structure, citations, and related-page topology must be applied to both language trees in the same edit pass when feasible.
- The synthesis should preserve disagreement rather than flattening it.

## Language subtree layout

Each language tree contains:

- `sources/`: source summaries keyed to raw material
- `concepts/`: reusable ideas such as instrumental convergence or Constitutional AI
- `people/`: thinker pages
- `organizations/`: labs and institutes
- `themes/`: durable topic pages
- `analyses/`: multi-source answers and audits
- `home.md`, `index.md`, `theses.md`, `open_questions.md`, `log.md`: operating pages

## Seed themes

- `Optimism vs Doom`
- `Alignment and Control`
- `Timelines and Takeoff`
- `Governance and State Capacity`
- `Economic Disruption`
- `Biological Upside`
- `Mental Health and Neuroscience`
- `Human Values and Preference Drift`

## Seed people

- `Dario Amodei`
- `Nick Bostrom`
- `Eliezer Yudkowsky`
- `Nate Soares`

## Initial ingest order

1. `Dario Amodei - Machines of Loving Grace.md`
2. `Dario Amodei - The Adolescence of Technology.md`
3. `Yudkowsky, Soares - If Anyone Builds It, Everyone Dies.md`
4. `Eliezer Yudkowsky - Dwarkesh Podcast.md`
5. `Юдковский - интервью хабр.md`
6. `Nick Bostrom - Superintelligence (2014).md`

## Source key policy

Use `YYYY-author-short-title` where possible. Use `undated-...` only when a year cannot be confidently inferred from the raw file.

## Ingest rules for this corpus

- Do not pretend the corpus is internally consistent.
- Preserve the distinction between essays, transcripts, interviews, and books.
- For transcripts, retain speaker attribution in the summary.
- For translated or secondary-language materials, capture both the original-language framing and the wiki's local-language framing.
- When a source is highly adversarial or highly certain, add an explicit uncertainty or disagreement section on affected pages.
- When a note is added to one language tree, create or update its counterpart in the other tree before closing the task.

## Durable questions for this wiki

- How quickly could AI move from strong models to transformative systems?
- Which claimed upside pathways depend on alignment success?
- Where do Amodei and Yudkowsky most strongly disagree?
- Which claims rely on empirical extrapolation versus conceptual arguments?
- What governance interventions appear inside the sources, and what assumptions do they require?
