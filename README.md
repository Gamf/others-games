# Others' Games — a Gamf genre

A curated catalog of **open-source games by other developers**, forked to the
Gamf account and hosted here, grouped by category. Published at
<https://gamf.github.io/others-games/>.

- `games.json` — the catalog. Each entry: `{slug, title, path, icon, dims, tags,
  category, license, author, source}`. `path` points at the forked game's live
  URL (e.g. `/2048/`); `source` links to the fork on GitHub.
- `index.html` — categorized catalog page (reads `games.json`).

Every game keeps its **original author and license**. This repo only catalogs
and links to the forks — it does not relicense or claim authorship. See each
fork's own `LICENSE` for terms.

## Adding another
1. Fork the game to the Gamf account, enable GitHub Pages, confirm it loads.
2. Add an entry to `games.json` with its category, author, license, and the
   working play URL as `path`.
