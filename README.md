# ArthLens

Evidence-first personal finance dashboard.

## GitHub Pages deployment

1. Create a GitHub repository named `arthlens`.
2. Upload the contents of this folder to the repository.
3. Push to the `main` branch.
4. GitHub Actions will deploy the site automatically.
5. Open **Settings → Pages** to see the published URL.

The workflow uses GitHub Pages and requires no paid hosting.

## Current capabilities

- Investor profile
- Financial goals
- Manual portfolio entry
- CSV import/export
- ICICI Direct-style portfolio fields
- Browser-local persistence
- Portfolio value / gain calculations
- Allocation and diversification
- Manual company metric analysis

## Important

This GitHub Pages version is a static front-end prototype. It does **not** yet contain production live market-data credentials, server-side web research, or a secure recommendation backend.

Do not put API keys/secrets in `index.html` or any frontend JavaScript. The next production step should add a server/API layer for live data and research.
