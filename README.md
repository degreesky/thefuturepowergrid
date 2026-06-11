# The Future Power Grid

Single-page website for the white-paper series on risk-based grid operation,
plus a 2-page decision brief for grid and energy-policy leadership.

## Deploy to GitHub Pages
1. Create a new public repository (e.g. `power-grid-future`).
2. Upload the entire contents of this folder (index.html, the /papers folder, .nojekyll).
3. Go to **Settings → Pages**, set Source = "Deploy from a branch", Branch = `main` / root.
4. Your site goes live at `https://<username>.github.io/power-grid-future/`.

## Structure
- `index.html` — the whole site (self-contained; fonts loaded from Google Fonts)
- `papers/` — all linked PDFs:
  - `the-future-power-grid-brief.pdf` — 2-page decision brief (linked from the hero + top of Publications)
  - `whitepaper-1-unlocking-grid.pdf`
  - `whitepaper-2-virtual-n1.pdf`
  - `iea-electricity-2026.pdf`
- `.nojekyll` — tells GitHub Pages to serve files as-is

## To edit
Open `index.html` in any text editor. All copy and the PDF links are in plain HTML.
