# Repository Instructions

This repository is an Obsidian vault for music notes.

## Obsidian Graph Rules

- Do not create detached/orphan pages unless the user explicitly asks for a temporary isolated page.
- Every new page must be connected to the graph through at least one meaningful Obsidian wikilink.
- Prefer two-way context when adding important pages:
  - the new page links to its parent genre, period, person, project, or topic;
  - an existing parent/index/timeline page links back to the new page.
- Keep Obsidian global graph settings with unresolved links and orphan pages hidden.
- Use Obsidian YAML frontmatter for graph metadata when the user asks for tags:
  - `type`: `person`, `direction`, `project`, `work`, `branch`, or `resource`;
  - `branch`: `european` or `american` when relevant;
  - `country`: for musicians/people;
  - `tags`: include `person` or `direction`, plus `european` or `american` when relevant.
- Avoid page titles that are unsafe or confusing on Windows/Obsidian, especially `:`, `/`, `\`, `|`, `?`, `*`, `<`, `>`, and `"`.
- Prefer Obsidian-safe names such as `Roots - African + Work Songs + Spirituals` and `Post-bop and Modal jazz`.
- When renaming a page, update all `[[page]]` references and rely on Obsidian-safe filenames.
- Before finishing graph edits, check for:
  - missing page targets;
  - old page titles left after rename;
  - empty bullets;
  - isolated pages with no incoming or outgoing links.
- Do not update the notes unless the user explicitly asks what to add or change.
- Use normal Markdown links for external videos in Obsidian.
