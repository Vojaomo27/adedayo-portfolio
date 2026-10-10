# Adedayo Ojaomo | Portfolio

A personal portfolio focused on data quality, practical automation, cybersecurity, and digital forensics.

## Contents

- `Landing_Page.html` - the editable portfolio page.
- `assets/adedayo-headshot.jpg` - optimized portrait used by the page.
- `.github/workflows/deploy-pages.yml` - publishes the page with GitHub Pages.

The Pages workflow copies `Landing_Page.html` to `index.html` in its deployment artifact, so the source file keeps its current name while the site opens at the repository URL.

## Preview locally

Open `Landing_Page.html` in a browser, or run a local static server from this folder:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000/Landing_Page.html`.

## Publish

This site is deployed from the public [`Vojaomo27/adedayo-portfolio`](https://github.com/Vojaomo27/adedayo-portfolio) repository. GitHub Actions deploys the page on each push to `main`.

Live site: <https://vojaomo27.github.io/adedayo-portfolio/>

Keep the repository limited to this portfolio site and its assets. Do not add the parent Codebase folder, workbooks, local environments, or generated build folders.
