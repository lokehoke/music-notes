# Music Notes

Personal music notes organized as an [Obsidian](https://obsidian.md/) vault.

The vault is built as a graph of musical periods, genres, composers, musicians, works, and reference pages. The main goal is to understand how musical traditions connect: European classical history, American blues/jazz/rock roots, film music, and individual musicians.

## How to Open

1. Install Obsidian.
2. Open Obsidian.
3. Choose **Open folder as vault**.
4. Select this folder:

```text
G:\My Drive\life\music_conspect
```

Obsidian should load the vault settings from `.obsidian/`.

## Folder Structure

```text
00 Index/      Vault-level indexes and TODOs
10 Periods/    Period, movement, and genre pages
20 People/     Composer and musician pages
30 Works/      Individual work pages, grouped by composer when useful
40 Topics/     Concept pages and future topic notes
50 Courses/    Course notes and study paths
60 Resources/  Books, websites, playlists, and reference pages
assets/        Scores, books, and images used by notes
.obsidian/     Obsidian vault settings
```

## How to Use

- Open **Graph View** to see connections between periods, genres, and people.
- Open any Markdown page to read or edit a note.
- Use Obsidian wikilinks to connect notes.
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
