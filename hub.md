---
schema: 1
type: note
name: "Book tracker"
tagline: "Obsidian book tracker built using Dataview"
description: |
  Obsidian book tracker built using Dataview.

  Includes views for currently reading, want to read, finished this year, and reading stats.
author: Maws7140
categories:
  - dashboard
tags:
  - note-template
  - tracker
  - dataview
  - reading
  - books
plugins:
  - id: dataview
    name: Dataview
    version: 0.5.68
environment:
  obsidian_version: "unknown"
  theme: default
  os: Win32
files:
  - path: Book Tracker.md
    type: md
    size: 608
---

# Book tracker

Obsidian book tracker built using Dataview.

## Features

- **Currently Reading**: Shows books with `status: reading`, sorted by start date
- **Want to Read**: Backlog of books with `status: want-to-read`
- **Finished This Year**: Books completed in 2026 with ratings
- **Stats**: Inline Dataview count of total finished books

## Required Plugins

- [Dataview](https://github.com/blacksmithgu/obsidian-dataview) for all query blocks and inline queries

## Setup

1. Create a `Books/` folder in your vault.
2. Add book notes with properties for `author`, `status`, `rating`, `started`, `finished`, and `genre`.
3. Open `Book Tracker.md`.

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

## Files

- `Book Tracker.md`
