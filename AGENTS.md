# Repository Instructions

This repository is an Obsidian vault for music notes.

## Structure

- `00 Index/` stores vault-level indexes and TODOs.
- `10 Periods/` stores period, movement, and genre pages.
- `20 People/` stores composer and musician pages.
- `30 Works/` stores individual work pages, grouped by composer when useful.
- `40 Topics/` stores concept pages and future topic notes.
- `50 Courses/` stores course notes and study paths.
- `60 Resources/` stores books, websites, playlists, and reference pages.
- `assets/` stores scores, books, and images used by notes.

## Obsidian Graph Rules

- Do not create detached/orphan pages unless the user explicitly asks for a temporary isolated page.
- Every new page must be connected to the graph through at least one meaningful Obsidian wikilink.
- Prefer two-way context when adding important pages:
  - the new note links to its parent genre, period, person, project, or topic;
  - an existing parent/index/timeline note links back to the new note.
- Keep Obsidian global graph settings with unresolved links and orphan pages hidden.
- Use Obsidian YAML frontmatter for graph metadata when the user asks for tags:
  - `type`: `person`, `direction`, `project`, `work`, `branch`, or `resource`;
  - `branch`: `european` or `american` when relevant;
  - `country`: for musicians/people;
  - `tags`: include `person` or `direction`, plus `european` or `american` when relevant.
- Avoid page titles that are unsafe or confusing on Windows/Obsidian, especially `:`, `/`, `\`, `|`, `?`, `*`, `<`, `>`, and `"`.
- Prefer Obsidian-safe names such as `Roots - African + Work Songs + Spirituals` and `Post-bop and Modal jazz`.
- When renaming a page, update all Obsidian wikilink references and rely on Obsidian-safe filenames.
- Before finishing graph edits, check for:
  - missing page targets;
  - old page titles left after rename;
  - empty bullets;
  - isolated pages with no incoming or outgoing links.
- Do not update the notes unless the user explicitly asks what to add or change.
- Use normal Markdown links for external videos in Obsidian.
