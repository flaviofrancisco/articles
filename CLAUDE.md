# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repo purpose

This is a personal collection of long-form articles/essays (architecture, software development, open science topics), written in Markdown. There is no code, build, test, or lint pipeline — just prose and supporting images.

## Structure

Each article lives in its own top-level directory containing a `README.md` and an `images/` folder for diagrams/screenshots referenced from it.

## Writing conventions

When drafting or editing an article, match the style used in existing ones (see `lets-be-fair-with-open-science/README.md`):
- Title with a relevant emoji, a bolded one-line thesis statement as a blockquote, and a `**Topics:**` line of backtick-separated tags.
- A `> [!NOTE]` disclaimer that opinions are the author's own, not their employer's.
- A `## Contents` section with anchor links to each heading.
- Tables for structured comparisons (e.g., principles, pros/cons).
- Mermaid `flowchart` diagrams for workflows/architecture where helpful.
- A `## References` section with external links.

## License

Content is released under CC0 1.0 Universal (public domain dedication) — see `LICENSE`.

## Stray files

Files named `._*` (e.g., `._README.md`) are macOS AppleDouble metadata artifacts from copying off an external drive, not real content. Ignore them; don't edit or treat them as article content.
