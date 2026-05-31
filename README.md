# Music Notes

Personal music notes organized as an [Obsidian](https://obsidian.md/) vault.

The vault is built as a graph of musical periods, genres, composers, musicians, works, and reference pages. The main goal is to understand how musical traditions connect: European classical history, American blues/jazz/rock roots, film music, and individual musicians.

## How to Open

1. Install Obsidian.
2. Open Obsidian.
3. Choose **Open folder as vault**.
4. Select this folder:

```text
G:\My Drive\notes
```

Obsidian should load the vault settings from `.obsidian/`.

## Folder Structure

```text
pages/      Notes and graph nodes
assets/     Images and media used by notes
.obsidian/  Obsidian vault settings
```

## How to Use

- Open **Graph View** to see connections between periods, genres, and people.
- Open any page in `pages/` to read or edit a note.
- Use `[[Page Name]]` wikilinks to connect notes.
- Use normal Markdown links for external resources and YouTube videos.
- Keep pages connected to the graph unless a page is intentionally only a reference page.

## Metadata

Some pages use YAML frontmatter for filtering:

```yaml
type: person
branch: european
country: Germany
tags:
  - person
  - musician
  - composer
  - european
```

Useful graph/search filters:

```text
[branch:european]
[branch:american]
[type:person]
[type:direction]
tag:#person
tag:#direction
```

## Graph Rules

- Avoid orphan pages.
- Every normal note should have at least one meaningful wikilink.
- People pages should stay simple: metadata plus `Part of`.
- Periods, genres, and movements can contain `Key ideas`, `Participants`, `Prev`, `Next`, `Inspired by`, and `Related`.
- Avoid filenames that are awkward on Windows or Obsidian, especially `:`, `/`, `\`, `|`, `?`, `*`, `<`, `>`, and `"`.

## GitHub

Repository:

https://github.com/lokehoke/music-notes
