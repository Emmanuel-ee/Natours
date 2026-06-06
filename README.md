# Natours

Landing page project for Natours.

## Live URL

After the workflow runs, the site will be available at:

`https://emmanuel-ee.github.io/Natours/`

## Deployment

This repository includes a GitHub Actions workflow at
`.github/workflows/deploy-pages.yml`.

On every push to `main`, it deploys the static site to GitHub Pages.

### One-time GitHub setup

If deployment fails with a Pages API permission error, enable Pages once in the
repository settings:

1. Go to **Settings → Pages** in the `Natours` repository.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Re-run the latest failed workflow (or push a new commit).
