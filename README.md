# descry-website

Marketing site for [Descry](https://github.com/meshde/erudite-x) — a desktop app that turns a diff
into a navigable, flow-based walkthrough.

Plain static HTML/CSS, no build step. Pages:

- `index.html` — landing page
- `features.html` — feature breakdown
- `getting-started.html` — install + first walkthrough, both review paths

Theme (colors, radius, font) is copied verbatim from the app's own
`app/src/styles.css` dark-mode tokens in the main `erudite-x` repo, so the
site matches the product.

Deploy anywhere that serves static files (GitHub Pages, Cloudflare Pages,
Netlify, Vercel) — nothing here needs a build.
