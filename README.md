# Authentic UW Prototype

Single-file HTML prototype of the underwriter workflow built on top of the
Authentic design system. Includes:

- Home / Growth / Submission detail pages
- BDE Florida submission with editable Loss Run + live indication math
- New Submission flow with real CSV / XLSX / PDF parsing (PapaParse, SheetJS, PDF.js)
- Quote tab with sticky summary and live Selected Premium
- Mobile-friendly: hamburger nav, stacking layouts, slide-in activity drawer

## Live

GitHub Pages: <https://YOUR-USER.github.io/REPO-NAME/>

## Run locally

Open `index.html` in a browser. Or for the cleanest experience:

```sh
python3 -m http.server 8000
# then open http://localhost:8000/
```

## Contents

- `index.html` — the entire app in one file
- `vendor/`    — PapaParse, SheetJS, PDF.js (bundled so the prototype works offline)
- `bde-files/` — sample broker submission files (PDFs, XLSX, ZIP)
