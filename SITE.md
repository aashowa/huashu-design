# Static site for Huashu Design

This folder intentionally stays dependency-free. The homepage is a single `index.html` file at the repository root so it can run on GitHub Pages without a build step.

## Local preview

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173.

## Design notes

- Editorial, portfolio-style presentation instead of a generic AI/SaaS landing page.
- Uses existing repository showcase screenshots and links to their source HTML.
- No external fonts, JS frameworks, analytics, or generated imagery.
- GitHub Pages deploys the root directory through `.github/workflows/pages.yml`.
