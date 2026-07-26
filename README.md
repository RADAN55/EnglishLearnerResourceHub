# Midnight Executive · EL Publishing

Free curriculum, compliance manuals, and professional development for teachers of English learners.

**Read it here → https://radan55.github.io/elpublishing/**

**Richard A. Daniel, M.Ed.** · ENL/EL Specialist · Laurel High School, Mississippi
*Many Voices · One Storm*

---

## What's here

`index.html` contains three sections: **Home** (the catalog, with search and filters), **The Manual** (*The Red Line*, sixteen parts on Mississippi LSP accommodations), and **The Module** (the companion 90-minute faculty PD session).

No build step, no framework, nothing to install.

## Publishing

Upload `index.html` and `README.md`, then **Settings → Pages** → Deploy from a branch → `main` → `/ (root)` → Save.

---

## Adding documents

**Drag the file in. That's it.** The page checks what's actually in this repository and shows only those cards. Upload a file and its card appears; delete it and the card disappears. You never edit `index.html`.

Cards for files you never upload simply never appear — so there is no penalty for this list being longer than what you publish.

### Web pages are preferred over PDFs

Each entry looks for an `.html` version **first**, then falls back to the PDF. A web page opens instantly on a phone, is searchable, can be linked to a specific section, and prints to PDF on demand. A PDF can only be downloaded.

If both exist, the web page wins.

| Document | Filenames it recognizes, in order of preference |
|---|---|
| ELPA21 ASCENT — Teacher Edition | `ELPA21-ASCENT-Teacher-Edition.pdf` · `ASCENT-Teacher-Edition.pdf` · `ELPA21-ASCENT-Teacher-Edition-566pp.pdf` · `ELPA21-Ascent-Teacher-Edition.pdf` |
| ELPA21 ASCENT — Student Workbook | `ELPA21-ASCENT-Student-Workbook.pdf` · `ASCENT-Student-Workbook.pdf` · `ELPA21-Ascent-Student-Workbook.pdf` |
| The Classroom Shelf — Complete Series II | `Mississippi-EL-Library-Series-II.pdf` · `The-Classroom-Shelf.pdf` · `Classroom-Shelf.pdf` |
| The 90-Minute Block: A Conductor's Guide | `volume-06-conductors-guide.html` · `The-90-Minute-Block-Conductors-Guide.pdf` · `Conductors-Guide.pdf` · `The-90-Minute-Block.pdf` · `Volume-VI-Conductors-Guide.pdf` |
| The Standards Ascent | `volume-07-standards-ascent.html` · `The-Standards-Ascent.pdf` · `Standards-Ascent.pdf` · `Volume-VII-Standards-Ascent.pdf` |
| Standards Ascent — Lessons & Resources Companion | `volume-08-lessons-companion.html` · `Standards-Ascent-Lessons-Resources-Companion.pdf` · `Lessons-Resources-Companion.pdf` · `Standards-Ascent-Companion.pdf` |
| The Domain & Level Handbook | `volume-09-domain-level-handbook.html` · `The-Domain-Level-Handbook.pdf` · `Domain-Level-Handbook.pdf` · `Domain-and-Level-Handbook.pdf` |
| The EL Specialist's Field Book | `volume-10-field-book.html` · `EL-Specialists-Field-Book.pdf` · `The-EL-Specialists-Field-Book.pdf` · `Field-Book.pdf` |
| The Flexible Block Guide | `volume-11-flexible-block-guide.html` · `The-Flexible-Block-Guide.pdf` · `Flexible-Block-Guide.pdf` |
| The Summit Workbook — Year Edition | `Summit-Workbook-Year-Edition.pdf` · `The-Summit-Workbook.pdf` · `Summit-Workbook.pdf` |
| EL Program Design & Scope | `EL-Program-Design-Scope.pdf` · `EL-Program-Design-and-Scope.pdf` · `Program-Design-Scope.pdf` |
| EL Classroom Wall Pack | `EL-Classroom-Wall-Pack.pdf` · `Classroom-Wall-Pack.pdf` · `Wall-Pack.pdf` |
| Emergency Sub Kit | `Emergency-Sub-Kit.pdf` · `Sub-Kit.pdf` |
| NBCT Portfolio Crosswalk Memo | `NBCT-Portfolio-Crosswalk-Memo.pdf` · `NBCT-Crosswalk.pdf` · `NBCT-Portfolio-Crosswalk.pdf` |
| Leveled Readables — Emerging | `187_Readables_Emerging_Gr9-12.pdf` · `Leveled-Readables-Emerging.pdf` · `Emerging-Readables.pdf` |
| Leveled Readables — Progressing | `187_Readables_Progressing_Gr9-12.pdf` · `Leveled-Readables-Progressing.pdf` · `Progressing-Readables.pdf` |
| Reading Foundations for Multilingual Learners | `Reading-Foundations-Manual.pdf` · `Reading-Foundations.pdf` · `Science-of-Reading-EL.pdf` |
| World Geography for English Learners | `World-Geography-EL-Unit.pdf` · `World-Geography-Unit.pdf` · `World-Geography-for-English-Learners.pdf` |
| ELL Strategies for Mainstreamed Students | `ELL-Strategies-Mainstreamed.pdf` · `ELL-Strategies-for-Mainstreamed-Students.pdf` · `EL-Strategies-Mainstreamed.pdf` |
| Making Them Count | `Making-Them-Count.pdf` · `Making-Them-Count-Book.pdf` |
**If a card doesn't appear** after upload, the filename isn't on the list. Either rename the file, or open `index.html`, find the entry, and add your filename to `target` separated by a `|`:

```js
target:"Your-Actual-Name.pdf|The-Flexible-Block-Guide.pdf"
```

### Filenames

Hyphens or underscores. No spaces, no parentheses — spaces become `%20` and look broken when shared.

### Adding something new

Copy an entry in the `ITEMS` list and change the fields:

```js
{ grp:"Curriculum & Instruction", fmt:"Manual", tags:["curriculum"],
  name:"The title readers should see",
  desc:"A sentence or two on what it is and who it's for.",
  action:"file", target:"exact-file-name.html", label:"Read it" },
```

`grp` must match one of: Compliance & Program Operation · The Classroom Shelf · Series II · Curriculum & Instruction · Professional Development · Publications
`tags` drive the filter buttons: `compliance` · `curriculum` · `pd`

### One quirk worth knowing

File detection needs a web server, so it only works on the live site. Double-clicking `index.html` on your computer hides every document card and looks broken. It isn't — check the live URL.

---

## Deep links

| | |
|---|---|
| The Manual | `…/elpublishing/#manual` |
| The Module | `…/elpublishing/#module` |
| The prohibition matrix | `…/elpublishing/#p9` |
| The forms bank | `…/elpublishing/#p15` |

Manual sections run `#p1` through `#p16`.

## Printing

Open the Manual or the Module and click **Print / PDF**. Only the visible section prints, so administrators can get the manual without the facilitator answer keys.

## Verify before each testing cycle

Manual Parts 7 through 9 are aligned to the Mississippi Testing Accommodations Manual revised **February 19, 2026**. Codes and allowability notes get revised. Reconcile against the current MTAM before every testing window.

---

© 2026 Midnight Executive · EL Publishing, Mississippi.
Free for classroom, school, and district professional development use.
Field guides, not policy. Where these materials and current MDE guidance differ, **MDE guidance governs.**
