# Inscriptions

Static, searchable HTML tables of South Indian epigraphic records — a
public snapshot published from [The Hero Search](https://github.com/pa-sankar/HeroSearch),
a private project building a queryable database of hero-stone and
sati-stone inscriptions from the *South Indian Inscriptions* (SII) series
and the *Annual Report on [South] Indian Epigraphy* (ARE).

**Live pages** (once GitHub Pages is enabled on this repo — see below):

- `index.html` — landing page, links to both tables
- `SII-Inscriptions.html` — every South Indian Inscriptions record from
  volumes at 100% high-quality OCR
- `ARE-Inscriptions.html` — every Annual Report on Indian Epigraphy
  appendix record read so far

Both are self-contained single HTML files (no build step, no server) —
open them directly, or serve the whole folder as-is.

## What's here

Each page is a flat table with search (whole-corpus or one column),
filter dropdowns (including type-to-search volume/year filters), and
click-to-copy stable IDs for citing a specific record. Regenerated from
the source project's database — not hand-edited, and not a live query:
treat the timestamp of the last commit as this snapshot's "as of" date.

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
