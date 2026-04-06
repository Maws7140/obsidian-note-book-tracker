# Book tracker 

Obsdian book tracker built using dataview 

## Description

# Obsdian book tracker built using dataview 

## Features

- **Currently Reading** — Shows books with `status: reading`, sorted by start date
- **Want to Read** — Backlog of books with `status: want-to-read`
- **Finished This Year** — Books completed in 2026 with ratings
- **Stats** — Inline Dataview count of total finished books

## Required Plugins

- [Dataview](https://github.com/blacksmithgu/obsidian-dataview) — for all query blocks and inline queries

## Setup

1. Create a `Books/` folder in your vault
2. Add book notes with frontmatter: `author`, `status` (reading/want-to-read/finished), `rating`, `started`, `finished`, `genre`
3. Open `Notes/Book Tracker.md`

## Example Book Note

```yaml
---
author: Cal Newport
status: reading
genre: productivity
rating: 
started: 2026-03-15
finished: 
---
```

## File

- `Notes/Book Tracker.md`

## Tags

`#note-template` `#tracker` `#dataview` `#reading` `#books`


## Required Plugins

| Plugin | Version | Link |
|--------|---------|------|
| Dataview | 0.5.68 | [GitHub](https://github.com/search?q=Dataview%20obsidian) |

## Installation

1. Download the `.md` file(s) from this repo
2. Place them in your vault
3. Install the required plugins listed above

---
*Published via [Vault Hub](https://vaulthub.dev)*
