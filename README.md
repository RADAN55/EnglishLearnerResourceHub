# Midnight Executive · EL Publishing

The front door to a catalog of free instructional, compliance, and professional development resources for teachers of English learners.

**Richard A. Daniel, M.Ed.** — ENL/EL Specialist, Laurel High School, Laurel City School District, Mississippi.
*Many Voices · One Storm*

---

## What this repository is

One file — `index.html` — that indexes every published resource and links out to it. Each resource keeps its own repository. This page only points at them, so updating a resource never breaks this site, and updating this site never touches a resource.

## Publishing it

1. Create a **public** repository named exactly `radan55.github.io`
2. Upload `index.html` (and this README)
3. **Settings → Pages** → Deploy from a branch → `main` → `/ (root)` → Save

Live in one to two minutes at **https://radan55.github.io/** — no folder in the URL, because the repo name matches the account name.

## Adding a title

Open `index.html`, scroll to the `CATALOG` array near the bottom, and add one entry:

```js
{
  shelf:  "Manuals & Field Guides",
  kind:   "Manual",
  name:   "The Red Line",
  desc:   "One sentence on what it is and who it's for.",
  repo:   "red-line",
  tags:   ["compliance","pd"],
  status: "live"
},
```

Re-upload `index.html`. That's the entire workflow — the layout, search, filters, and counts all regenerate from the list.

### Fields

| Field | Notes |
|---|---|
| `shelf` | Must match one of the five section names in the `SHELVES` array |
| `kind` | Small label above the title — "Manual", "Progressive Web App", "Curriculum" |
| `repo` | Repository name only. The URL is built as `radan55.github.io/REPO/` |
| `url` | Optional. Use only if the resource lives somewhere other than a Pages repo |
| `tags` | Any of: `apps`, `compliance`, `curriculum`, `pd` — these drive the filter buttons |
| `status` | `live`, `deploy`, or `archive` |

### The three statuses

- **`live`** — you have clicked the URL yourself and it loaded. Only these render as clickable links.
- **`deploy`** — the files are built and on your computer, waiting for a repository.
- **`archive`** — the resource exists as a document but isn't hosted yet.

Nothing is presented to visitors as available until you mark it `live`. A dead link on a public resource site costs more credibility than a missing one.

## Changing the GitHub handle

One line, near the top of the script block:

```js
const USER = "radan55";
```

Every repository URL on the page is derived from it.

## Dependencies

None, beyond Google Fonts (Fraunces, Inter, IBM Plex Mono) loaded over the network. No build step, no framework, no package manager. The page works offline apart from font rendering.

---

Resources are free for classroom, school, and district professional development use. Materials are field guides, not policy — verify all compliance guidance against current Mississippi Department of Education publications.
