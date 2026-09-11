# Candidate Dinner at Claud — dossier

One file makes the site: `index.html` (page, styles, and the full text — no build step, no server). The `research/` folder holds the eight raw research dossiers (markdown) that the page's appendix is generated from; they are the source record, with every URL and confidence tag, and are not needed to serve the page.

## Publish
- GitHub Pages: enable Pages on this repo (Settings → Pages → Deploy from a branch → `main`, `/ (root)`). The page is then at `https://winslowbrown.github.io/candidate_dinner/`.
- Anywhere else: copy `index.html` to any static host.

The only external dependency is Google Fonts (Cormorant, IBM Plex Sans, IBM Plex Mono); without it the page falls back to Georgia / system sans / Menlo.

## What it is
A reference dossier for a Confrérie des Chevaliers du Tastevin candidate dinner at Claud, New York, 26 October 2026: thirteen Burgundies in two acts — a Meursault investigation in white (Leflaive, Roulot, Coche-Dury, Lafon, Ente) and a whole-cluster study in red (Dujac, Rousseau, Mugnier, Roumier, DRC, Liger-Belair). Each wine has a fiche (climat, parcel, farming, cellar, vintage, critics, JancisRobinson.com), a short narrative, and an Established / Unresolved box. Every non-trivial claim carries a confidence tag; "NOT FOUND" means it was looked for and not sourced.

Researched 5–11 September 2026. Sources: 757 URLs listed in the appendix dossiers, plus ~120 JancisRobinson.com reviews read with a subscriber login.
