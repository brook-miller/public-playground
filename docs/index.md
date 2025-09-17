---
title: Public Playground Catalog
---

# Public Playground — Project Catalog

Welcome! This page catalogs minor projects and artifacts in this repository and provides links to live demos (when hosted in `docs/`) and to source files in the repository.

> Note: GitHub Pages ("GitHub Docs") serves content from the `docs/` directory by default. Items outside `docs/` are linked to their source in the repo.

## Live Demos (served from `docs/`)

- Sunburst Chart Demo
  - Live: [docs/sunburst.html](./sunburst.html)
  - Source: [`docs/sunburst.html`](https://github.com/your-username/public-playground/blob/main/docs/sunburst.html)
  - Related research: NBER Working Paper No. 34255, “Do LLMs Complement Humans? Evidence from Millions of Knowledge Workers,” studies how large language models shift productivity and task composition for knowledge workers. The authors leverage firm-wide deployment data and find substantial output gains alongside reallocation across task types—patterns reflected in the categories shown in this sunburst. Read: https://www.nber.org/system/files/working_papers/w34255/w34255.pdf

## Repository Artifacts (not served by Pages)

- ChatGPT Usage Sunburst Project
  - Notebook: [`chatgpt-usage-sunburst/analysis.ipynb`](https://github.com/your-username/public-playground/blob/main/chatgpt-usage-sunburst/analysis.ipynb)
    - nbviewer: https://nbviewer.org/github/your-username/public-playground/blob/main/chatgpt-usage-sunburst/analysis.ipynb
  - Data: [`chatgpt-usage-sunburst/data.csv`](https://github.com/your-username/public-playground/blob/main/chatgpt-usage-sunburst/data.csv)

## Contributing / Adding a New Mini-Project

1. Place any HTML/CSS/JS assets you want to be publicly hosted into the `docs/` directory.
2. Add a short entry in this file under the appropriate section.
3. Commit and push. GitHub Pages will serve `docs/` at: `https://<org-or-username>.github.io/public-playground/`.

## Repository Map

- `docs/`
  - `index.md` — This catalog page.
  - `sunburst.html` — Sunburst visualization demo.
- `chatgpt-usage-sunburst/`
  - `analysis.ipynb` — Notebook for the sunburst usage analysis.
  - `data.csv` — Supporting dataset for the notebook.

---
