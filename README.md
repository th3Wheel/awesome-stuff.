# Awesome Stuff

A personal, awesome-style collection point for useful tools, ideas, and references found online.

This repo is organized so you can:
- keep a **baseline** list aligned with original sources as they evolve,
- keep **personalized** notes, ratings, and tags,
- update baseline entries later without losing your personal context.

## Repository pattern

Use two layers for each topic:

1. **Baseline entry**: source-truth details copied from upstream lists/pages.
2. **Personal overlay**: your notes and curation about that baseline item.

Store entries in this format inside this README (or future topic files):

```md
- [Resource Name](https://example.com)
  - Source: [Awesome Source](https://example.com/awesome), checked: YYYY-MM-DD
  - Baseline summary: short neutral summary of what it is
  - Personal notes: why it matters to you
  - Tags: #language #tooling #learning
  - Status: active | testing | archived
```

## Starter collection

### Utilities

- [ripgrep](https://github.com/BurntSushi/ripgrep)
  - Source: [awesome-rust](https://github.com/rust-unofficial/awesome-rust), checked: 2026-04-16
  - Baseline summary: Fast line-oriented search tool.
  - Personal notes: Great default grep replacement for large repos.
  - Tags: #cli #search #productivity
  - Status: active

### Ideas

- [Second Brain / PARA method](https://fortelabs.com/blog/para/)
  - Source: [fortelabs.com](https://fortelabs.com/blog/para/), checked: 2026-04-16
  - Baseline summary: Organizing knowledge into Projects, Areas, Resources, Archives.
  - Personal notes: Useful structure for managing learning references.
  - Tags: #knowledge-management #workflow
  - Status: testing

## Keeping baseline updated over time

When revisiting a source:
1. Re-check the source URL.
2. Update **Baseline summary** and **checked** date.
3. Keep **Personal notes/tags/status** unless your opinion changed.
4. If an item is removed upstream, keep it with `Status: archived` and note why.

This keeps your list personal while still tracking upstream change.
