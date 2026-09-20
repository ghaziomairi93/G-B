# archive/ — specimens gathered 2026-09-20

Trunk-and-specimens cleanup of `our day/` (see `00_System/AI_Brain/TRUNK-SPECIMENS-AUDIT-2026-09-20.md`).
Nothing was deleted — every file here is a preserved earlier version or duplicate.

- `childish-flowers/` — the 2026-07-04 v1–v5 design series: `pdf-v1-gold` → `pdf-v5-garden` HTML
  layouts plus their rendered PDFs (`Ghazi_Bayan_*.pdf`). These are the specimens the Version
  Dashboard reviewed.
- `elegant-flowers/` — the parallel elegant series (`01_Sage_Gold_Botanical` → `05_Pressed_Flower`,
  `invite-v1` → `invite-v5`).
- `loose/` — root-level specimens gathered from the project root: the duplicate `pdf-v*.html`
  copies (byte-identical to the `childish-flowers/` originals, hash-verified), the extra
  `Ghazi_Bayan_*.pdf` copies, the two distinct monogram variants (`monogram.pdf`,
  `Ghazi_Bayan_Monogram.pdf`), and `test.pdf` (a render test).

Trunk keeps: `new-style/` (current generation — `invite-*.html`, PNG exports, `export-png.js`),
the three final deliverables (`Ghazi & Bayan — Engagement (Lavender Jewel / Rose Garden / Sunset
Peach).pdf`), `index.html`, `README.html`, the Arabic saved page, and the Version Dashboard
(its links were updated to point here).

Tracked files were moved with `git mv` (staged renames, not committed); untracked files were
moved with plain rename. Move script: `.staging/move-our-day.mjs` (dry-run mode available).
