# kururupepe.github.io

Personal site — a minimal terminal-style page. Plain static HTML/CSS, no build step.

## Deploy

Served by GitHub Pages from the `main` branch root. Push to `main` and the site
updates at <https://kururupepe.github.io/> within a minute.

Locally, just open `index.html` in a browser (or `python -m http.server`).

## Editing

- **Name / title art** — `.art--title` block in `index.html`
- **Frog** — `.art--frog` block inside the `.frog-link` anchor; the art itself is
  decorative (hidden from screen readers), the link is labelled and opens
  `pepe-truecolor.html`
- **Truecolor page** — `pepe-truecolor.html`, a `▀` character grid that types itself
  in on load (skipped when `prefers-reduced-motion` is set)
- **Contact** — the `cat contact.txt` section
- **Projects** — the `ls projects/` section
