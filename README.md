# Heat Mobility — Heat Equity Research

Interactive research project by Villanova University and IBM Research Africa.

- `index.html`: autoplay research presentation.
- `dashboard.html`: complete seven-page research dashboard.

The original research content, embedded data, charts, and author credits are preserved. The deployment version adds links between the presentation and dashboard and updates page metadata.

## GitHub Pages

- Presentation: https://villanova-transportation.github.io/heat-mobility/
- Dashboard: https://villanova-transportation.github.io/heat-mobility/dashboard.html
- Repository: https://github.com/villanova-transportation/heat-mobility

Upload these files to the root of the `main` branch. In repository Settings → Pages, select **Deploy from a branch**, **main**, **/(root)**, then Save. The expected project URL is `https://villanova-transportation.github.io/heat-mobility/` when the repository is named `heat-mobility`. No custom domain or paid service is required.

All visualization assets and data are embedded in the two HTML files; no build step, API key, backend, or external CDN is required. `.nojekyll` disables Jekyll processing.

## Local preview

Run `python3 -m http.server 8765` from this directory, then open `http://localhost:8765/`.

Research authorship and source/library notices remain in the supplied HTML documents. No additional license is asserted by this deployment package.
