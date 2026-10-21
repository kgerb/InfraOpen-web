# InfraOpen website

The public website of [InfraOpen](https://kgerb.github.io/InfraOpen-web/), a free, non-profit map of drinking water, toilets, parking and overnight spots in Germany, built from public data and kept fresh by the community.

InfraOpen is just getting started. The Android app is in a closed beta.

- **Join the beta:** [open a beta request](../../issues/new?template=beta.yml)
- **Suggest a data source:** [tell us about it](../../issues/new?template=data-source.yml)
- **Ideas and feedback:** [GitHub Issues](../../issues)

## This repository

A single static page, published to GitHub Pages by `.github/workflows/pages.yml` on every push to `main`.

- `index.html` holds the whole page, styles included.
- `assets/fonts/` holds Figtree, served from this site so no third-party font service sees visitors. Figtree is licensed under the SIL Open Font License 1.1 (`assets/fonts/OFL.txt`).

To preview locally, open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

## Licence

The text and graphics of this website are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Data shown or named on the site keeps the licence of its source.
