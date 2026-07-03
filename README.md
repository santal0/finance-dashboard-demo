# Finance Dashboard Demo

This repository is a static GitHub Pages site. The page entry is `index.html` in the repository root.

## Deploy With GitHub Actions

1. Push this folder to a GitHub repository.
2. In GitHub, open `Settings` -> `Pages`.
3. Under `Build and deployment`, set `Source` to `GitHub Actions`.
4. Push to the `main` or `master` branch, or run the workflow manually from `Actions` -> `Deploy index.html to GitHub Pages`.
5. After the workflow succeeds, open the Pages URL shown in the workflow summary or in `Settings` -> `Pages`.

The workflow is defined in `.github/workflows/deploy-pages.yml`. It uploads the repository root as a static site, so `index.html` is deployed directly without any build step.
