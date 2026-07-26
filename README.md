# The EL Publishing Library

Free curriculum, manuals, and professional development for teachers of English learners.

**Browse it → https://radan55.github.io/elpublishing/**

**Richard A. Daniel, M.Ed.** · ENL/EL Specialist · Laurel High School, Mississippi
Midnight Executive · EL Publishing · *Many Voices · One Storm*

---

## How this repository works

One repo. Every document lives here. Drag a PDF in and it gets a public URL automatically:

```
https://radan55.github.io/elpublishing/YOUR-FILE-NAME.pdf
```

`index.html` is the browsable front end — search, filters, and a card per document.

## Adding a document

1. **Add file → Upload files**, drag in the PDF, commit.
2. Open `index.html`, find the `DOCS` list, add one line:

```js
{ grp:"Curriculum & Instruction", fmt:"Manual · PDF", tags:["curriculum"],
  name:"The title as readers should see it",
  desc:"One or two sentences on what it is and who it's for.",
  file:"Exact-File-Name.pdf", size:"" },
```

3. Commit. Live in about a minute.

`file` must match the uploaded filename exactly, including capitals and the extension.

## Removing a document

Delete the file **and** its line in `DOCS`. A card with no file behind it is a dead link — worse on a public resource page than a missing entry.

## Filenames

Use hyphens, no spaces, no parentheses. `Reading-Foundations-Manual.pdf`, not `reading foundations (1).pdf`. Spaces become `%20` in the URL and look broken when shared.

## Fields

| Field | Notes |
|---|---|
| `grp` | Must match one of the four names in the `ORDER` array |
| `fmt` | Small label above the title — "Manual · PDF", "Workbook · PDF" |
| `tags` | Any of `curriculum`, `compliance`, `pd`, `student` — these drive the filter buttons |
| `file` | Filename only, exactly as uploaded |
| `size` | Optional, e.g. `"4.2 MB · 88 pages"`. Leave `""` to hide |

## The list ships pre-filled

`DOCS` already contains entries for the full catalog. **Delete any line for a file you don't upload.** Every remaining card must have a matching file in this repository.

## Publishing

Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.

---

© 2026 Midnight Executive · EL Publishing, Mississippi.
Free for classroom, school, and district professional development use.
Materials are field guides, not policy. Verify compliance guidance against current MDE publications.
