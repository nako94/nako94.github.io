# Aerospace Systems Engineering Portfolio

A bilingual (EN/KO), responsive static site for GitHub Pages. No backend or build tools needed.

## Local preview

Open `index.html`, or for a local server:

```bash
python -m http.server 8000
```

Then open http://localhost:8000 .

## Deploy to GitHub Pages

1. Create a **new public repository** for the portfolio, e.g. `nako94.github.io` (user site) or `aerospace-portfolio` (project site).
2. Upload `index.html`, `styles.css`, `script.js`, and `.nojekyll` to the repo root.
3. In **Settings → Pages**, set **Deploy from a branch**, `main` / `/ (root)`.
4. View the site at `https://nako94.github.io/` for a user site, or `https://nako94.github.io/aerospace-portfolio/` for a project site.

## Publication checklist — IMPORTANT

- Draft copy is intentionally high-level; get employer authorization before publishing any defense-project descriptions or related images.
- No internal diagrams, message schemas, operational test procedures, images, customer data, or files taken from work systems.
- Avoid unpublished research data or claims of journal acceptance.
- Confirm contact / identity preferences; this template deliberately omits personal email and employer names.
- Confirm each performance claim and ensure public citation where applicable.

## Customize

- Update navigation, copy and localized text in `index.html` via `data-en`, `data-ko`.
- Brand name/logo and accent colors are in `index.html` and `styles.css`.
- The HTML is entirely static and works with a GitHub Pages subpath.
