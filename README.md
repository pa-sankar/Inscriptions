# Inscriptions

Static, searchable HTML tables of South Indian epigraphic records — a
public snapshot published from a private project building queryable
databases of the *South Indian Inscriptions* (SII) series and the
*Annual Report on [South] Indian Epigraphy* (ARE).

**Live pages** (once GitHub Pages is enabled on this repo — see below):

- `index.html` — landing page, links to both public tables
- `SII-Inscriptions.html` / `ARE-Inscriptions.html` — public, simple
  search tables (basic details only — place, dynasty, king, date,
  language, remarks, citation ID)
- `Sources.html` — every volume/report used, linked to its original
  scan on the Internet Archive

`Sanjay/` holds the original full-featured pages (every filter and
tag) — a public URL, but not linked from the pages above.

## What's here

Each table is a flat, searchable list with a search box (whole-page or
one column), a few filter dropdowns, and click-to-copy stable IDs for
citing a specific record. The actual row data lives in `data/*.json`
(fetched by the page at load, not embedded — both the public and
`Sanjay/` pages share the same data file, so the real record text is
never duplicated between them). Regenerated from the source project's
database — not hand-edited, and not a live query: treat the timestamp
of the last commit as this snapshot's "as of" date.

## Enabling the live URL

This repo's own GitHub Pages isn't turned on automatically by a push —
one-time setup, in the GitHub UI:

**Settings → Pages → Build and deployment → Source: "Deploy from a
branch" → Branch: `main`, folder `/ (root)` → Save.**

A few minutes after that, the site is live at
`https://pa-sankar.github.io/Inscriptions/`.

## Feedback

Issues and comments welcome — this is an early snapshot, published
specifically to gather feedback before the underlying corpus is
complete.
