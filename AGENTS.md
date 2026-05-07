# Agent Instructions — GitHub for ADO Developers Demo

## Project Purpose

This repo contains a single-file demo script ([README.md](README.md)) for a **90-minute live workshop** that onboards Azure DevOps (ADO) developers to GitHub. There is no application code, build system, or test suite.

## Repository Structure

```
README.md   # The complete demo script (the only file that matters)
AGENTS.md   # This file
```

## Content Conventions

- **ADO comparisons are mandatory**: every GitHub feature shown must include a "Compare: In ADO this is…" callout. Never remove or weaken these comparisons.
- **Key callouts** use the `**Key callout**:` prefix and highlight what's unique or surprising vs. ADO.
- **Section structure**: Sections are numbered (1.1, 1.2, …). Each has a **Goal**, numbered steps, and optional sub-bullets.
- **Presenter attribution**: Each demo block is tagged `(Presenter A, N min)` or `(Presenter B, N min)` or `(Both, N min)`. Keep timing totals consistent with the Timing Guide table at the end of the README.
- **Markdown code blocks** inside the script represent files the presenter will create or display (e.g., PR templates, CODEOWNERS). Use triple-backtick fences with the appropriate language tag.

## Key Facts

- **Total duration**: 90 minutes (see the Timing Guide table in README.md).
- **Demo repo**: hosted at `github.com/yortch/` — referenced URLs in the script are examples for presenters to adapt.
- **ADO reference**: `https://dev.azure.com/octodemo-msft/msft-common-demos-adogh-crispy-carnival/`
- **Audience**: ADO users who are new to GitHub — assume familiarity with ADO concepts (Repos, Pipelines, Boards, PRs, Policies) but no GitHub knowledge.

## Editing Guidelines

- When adding a new demo step, follow the existing numbered-list format and include an ADO comparison.
- When adding a new section, update the **Timing Guide table** with the correct duration and presenter column.
- Do not add application code, CI workflows, or other files unless the user explicitly requests them.
- External documentation should be **linked, not copied** (see the Resources section at the bottom of README.md for the canonical links).
