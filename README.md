# gridline.group

Holding page for **GRIDLINE POLAND Sp. z o.o.** — static, single file, no build step.

- `index.html` — the whole page (CSS + JS inline)
- `fonts/` — Aeonik Pro Regular/Medium and JetBrains Mono Medium, subset to Latin + Latin-Ext, woff2
- `og.png`, `favicon.svg`, `apple-touch-icon.png` — generated from the brand assets
- `CNAME` — custom domain for GitHub Pages

## Brand rules baked in
Palette, type scale, shape radii (R = N/4) and the generative container pattern follow the
Gridline Brand Book. Only Aeonik Medium/Regular and JetBrains Mono Medium are used; mono is
uppercase and reserved for tags and labels.

## Contact form
`FORM_ENDPOINT` in `index.html` is empty, so the form composes an email to
office@gridline.group instead of posting. Set it to a Formspree / Apps Script URL to receive
submissions in the background — nothing else needs to change.

## Deploy
Push to `main`. GitHub Pages serves the root of the branch.
