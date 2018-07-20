---
title: "Note With Notes Archetype"
date: 2018-07-19T12:06:24-03:00
draft: false
---

When creating new content with `hugo new`, if there is an archetype with the same name of the directory that the content is being inserted, the matching archetype will be used instead of `archetypes/default.md`

To fix ideas, this note was created with

```
hugo new notes/note-with-notes-archetype.md
```

Because there is an archetype `archetypes/notes.md` that matches the directory of the new content, it will be used instead of `archetypes/default.md`.
