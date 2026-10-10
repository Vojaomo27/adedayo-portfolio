# Adedayo Ojaomo | Portfolio

A personal portfolio focused on data quality, practical automation, cybersecurity, and digital forensics.

## Contents

- `Landing_Page.html` - the editable portfolio page.
- `assets/adedayo-headshot.png` - portrait used by the page.
- `.github/workflows/deploy-pages.yml` - publishes the page with GitHub Pages.

The Pages workflow copies `Landing_Page.html` to `index.html` in its deployment artifact, so the source file keeps its current name while the site opens at the repository URL.

## Preview locally

Open `Landing_Page.html` in a browser, or run a local static server from this folder:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000/Landing_Page.html`.

## Publish

Create a public repository named `adedayo-portfolio` under `Vojaomo27`, push the `main` branch, and set **Settings > Pages > Build and deployment > Source** to **GitHub Actions**. The workflow deploys the page on each push to `main`.

Expected site URL: <https://vojaomo27.github.io/adedayo-portfolio/>

The repository should contain only this portfolio site and its assets. Do not add the parent Codebase folder, workbooks, local environments, or generated build folders.