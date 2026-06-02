# AGENTS.md

Guidance for AI agents (any harness) working in this repository.

## What this repo is
This repo **is the owner's public CV / personal website** — a Jekyll site (Academic Pages template) auto-deployed by GitHub Pages at `tomrannosaurus.github.io`. It is a living professional record, so accuracy and restraint matter more than in a typical codebase.

## Commits & deployment
- **Do not add any AI/assistant attribution to commits** — no `Co-Authored-By: Claude`/Anthropic trailer, and no self-reference in commit messages or PR bodies. Commits are authored by the owner alone.
- `master` is the **live** branch: pushing publishes the site. This is a single-author repo, so commit directly to `master`.
- **Only commit or push when the owner asks.**

## Where the CV lives
- `_pages/about.md` — the CV itself (permalink `/`). Sections, in order: Education · Current Employment · Past Employment · Publications · Presentations · Professional Service · Honors & Awards.
- Infrastructure — don't break: `_config.yml`, `_data/`, `_includes/`, `_layouts/`, `_sass/`, and the YAML front matter (the `---` block atop each page; it sets the permalink/redirects and drives the build). `_drafts/` is unpublished template content.
- Local preview: `bundle exec jekyll serve` (see `Gemfile`; a `Dockerfile` is also provided).

## Editing the CV — accurate and honest
- **Never fabricate.** Don't invent dates, titles, descriptions, or research details — ask the owner.
- Mirror the existing bullet/indentation style of the section you edit.
- **Current Employment = currently-held roles only.** When a role ends, move it to Past Employment and close the date. List roles reverse-chronologically.
- State roles **honestly** — e.g., reviewing delegated by a program-committee member is "Sub-reviewer," not "Reviewer"/"PC member."

## Domain note
"**POTS**" is ambiguous here: in the owner's ML/time-series research it means **partially observed time series**; he *also* researches medical **postural orthostatic tachycardia syndrome** (also abbreviated "POTS"). Disambiguate by context, and prefer spelling out the intended meaning on the CV.
