# Gold-and-Oil-Stock-Data-Analysis
VSTE gold and oil stock analysis from 2016-present day 

## Deploy to GitHub Pages (Voici)

This repository includes a workflow at [.github/workflows/deploy-pages.yml](.github/workflows/deploy-pages.yml) that builds and deploys the notebook as a static Voici site.

1. Push this repository to GitHub.
2. In GitHub, open Settings > Pages.
3. Under Build and deployment, set Source to GitHub Actions.
4. Push to `main` or `master` (or run the workflow manually from Actions).

After the workflow succeeds, the site will be available at:

`https://<your-github-username>.github.io/<your-repo-name>/`

## If Pages Shows Only README

If your deployed page shows only the repository README, GitHub Pages is usually still serving from the branch instead of the Actions artifact.

1. Open repository Settings > Pages.
2. Under Build and deployment, set Source to GitHub Actions.
3. Re-run the Deploy Voici Site to GitHub Pages workflow from the Actions tab.
4. Open the deployment URL shown by the job (Environment: github-pages), not the repository URL.
