# Midnight Executive · EL Publishing

Free curriculum, compliance manuals, and professional development for teachers of English learners.

**Read it here → https://radan55.github.io/elpublishing/**

**Richard A. Daniel, M.Ed.** · ENL/EL Specialist · Laurel High School, Mississippi
*Many Voices · One Storm*

---

## Files in this repository

| File | What it is |
|---|---|
| `index.html` | The site — Home catalog, *The Red Line* manual, and the 90-minute faculty module |
| `classroom-shelf.html` | The Classroom Shelf, Series II, Volumes VI–XI |
| `README.md` | This file |

No build step, no framework, nothing to install.

## Publishing

Upload all three files, then **Settings → Pages** → Deploy from a branch → `main` → `/ (root)` → Save.

---

## Sites this catalog links out to

These live in their own repositories. **Click each one after publishing** — if any 404s, that repo's Pages setting needs turning on.

| Resource | URL |
|---|---|
| ELPA21 Practice Suite | `radan55.github.io/elpa21/` |
| ELPA21 All-Bands Practice, K–12 | `radan55.github.io/elpa21/k12.html` |
| ELPA21 Blueprint Simulation, 9–12 | `radan55.github.io/elpa21/hs.html` |
| ELPA21 Growth Manual | `radan55.github.io/elpa21growthmanual/` |
| Every Teacher Is a Language Teacher — Interactive Module | `radan55.github.io/el-pd/` |
| Every Teacher Is a Language Teacher — Guide + SIOP | `radan55.github.io/freeenglishlanguagelearnerpd/` |
| The Vocabulary Engine | `radan55.github.io/elvocabularycurriculumengine/` |

To fix or remove a link, open `index.html`, find the entry in `ITEMS`, and edit `target`.

---

## Adding documents

**Drag the file in. That's it.** The page checks what's actually in this repository and shows only those cards. Upload a file and its card appears; delete it and the card disappears. You never edit `index.html`.

Cards for files you never upload simply never appear — so there's no penalty for the list being longer than what you publish.

### Web pages beat PDFs

Each entry looks for an `.html` version **first**, then falls back to a PDF. A web page opens instantly on a phone, is searchable, links to a specific section, and prints to PDF on demand. A PDF can only be downloaded — and can go missing.

If both exist, the web page wins.

### If a card doesn't appear

The filename isn't on the recognized list. Open `index.html`, find the entry, and add your filename to `target` separated by a `|`:

```js
target:"Your-Actual-Name.pdf|The-Flexible-Block-Guide.pdf"
```

Hyphens or underscores. No spaces, no parentheses — spaces become `%20` and look broken when shared.

---

## Deep links

| | |
|---|---|
| The Red Line manual | `…/elpublishing/#manual` |
| The faculty module | `…/elpublishing/#module` |
| The prohibition matrix | `…/elpublishing/#p9` |
| The forms bank | `…/elpublishing/#p15` |
| Series II, Volume X (Field Book) | `…/elpublishing/classroom-shelf.html#v10` |

Manual sections run `#p1`–`#p16`. Shelf volumes run `#v6`–`#v11`.

## Printing

Open any manual or volume and click **Print**. Only the visible section prints — administrators get the manual without the facilitator answer keys, and a teacher can print one volume instead of ninety-three pages.

## Verify before each testing cycle

*The Red Line* Parts 7–9 are aligned to the Mississippi Testing Accommodations Manual revised **February 19, 2026**. Codes and allowability notes get revised. Reconcile against the current MTAM before every testing window.

---

© 2026 Midnight Executive · EL Publishing, Mississippi.
Free for classroom, school, and district professional development use.
Field guides, not policy. Where these materials and current MDE guidance differ, **MDE guidance governs.**
