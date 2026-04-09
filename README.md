# GitHub Pages Starter for Repository Catalog

This repository is a starter for a GitHub Pages website built with **MkDocs** and **Material for MkDocs**.

It includes:
- Homepage
- Repository catalog section
- Category pages
- First repository page for **Telegram-Tools**
- GitHub Actions workflow for deployment to GitHub Pages

## Local setup

```bash
python -m venv .venv
source .venv/bin/activate   # Linux/macOS
# .venv\Scripts\activate    # Windows PowerShell
pip install mkdocs-material
mkdocs serve
```

Then open the local URL printed by MkDocs.

## Build

```bash
mkdocs build
```

## Deploy

Push to GitHub. The workflow in `.github/workflows/deploy.yml` will build and publish the site.
