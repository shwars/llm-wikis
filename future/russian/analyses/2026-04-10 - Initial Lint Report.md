---
type: analysis
topic: future
lang: russian
status: active
updated: 2026-04-21
source_keys: []
aliases:
  - lint report
  - отчёт lint
related:
  - "[[russian/log]]"
  - "[[russian/index]]"
---

# 2026-04-10 - Первый lint-отчет

## Кратко

Первый структурный аудит seeded-версии `future`-вики. Проверка оценивает, соблюдается ли контракт вики, а не истинность самих источников.

## Текущий синтез

Стартовый каркас проходит базовый контракт v1: seeded-страницы достижимы из [[russian/index]], долговечные страницы несут frontmatter, а главные синтетические заметки ссылаются на source-summary notes, а не на raw-файлы. После перестройки в `english/` и `russian/` появился дополнительный класс риска - parity drift между языковыми деревьями, поэтому lint теперь должен проверять и синхронность структуры.

## Подтверждающие источники

- В текущем состоянии не должно быть orphan pages вне индекса языка.
- Ключевые страницы должны ссылаться на source-summary notes, а не на raw-файлы напрямую.
- Навигационные страницы должны существовать и в `english/`, и в `russian/`.
- Устойчивый query-output уже существует в [[russian/analyses/Amodei vs Yudkowsky - Major Disagreements]].
- Открытые вопросы явно вынесены в [[russian/open_questions]].

## Разногласия и неопределенности

- Риск thin-page по-прежнему остается на [[russian/people/Nate Soares]], потому что стартовый корпус содержит мало самостоятельного материала о нем.
- Будущий stale-synthesis риск заметен на [[russian/themes/Mental Health and Neuroscience]], так как там доминирует один источник.
- Главное живое противоречие - guarded continuation против stop-the-race стратегий - должно оставаться явно surfaced.

## Связанные страницы

- [[russian/log]]
- [[russian/index]]
- [[russian/open_questions]]
