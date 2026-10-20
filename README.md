# DRMD – Digital Reference Material Document

Landing page for the Digital Reference Material Document (DRMD): an XML format for reference material certificates and product information sheets, aligned with ISO 33401:2024.

**Website:** <https://punitharumilli.github.io/DRMD/>

---

## Resources

| Resource | Link |
|---|---|
| Schema (XML Schema and Schematron business rules) | <https://github.com/punitharumilli/Schema> |
| Guidance document | <https://punitharumilli.github.io/BestPracticeDocs/> |
| AI-powered generator | <https://punitharumilli.github.io/DRMD_Generator/> |
| Video guides | <https://punitharumilli.github.io/DRMD_Videos/> |

---

## Contents of this repository

```
index.html                     the page
assets/
├── bam-logo.png               BAM logo
├── drmd-logo.png              DRMD logo
├── favicon-32.png, favicon-64.png, apple-touch-icon.png
└── fonts/                     Inter typeface (WOFF2) and its licence
.github/workflows/pages.yml    publishes the page on GitHub Pages
```

The page has no external dependencies. Fonts and images are served from this repository, so no requests are made to other servers when the page is opened.

---

## Publishing

The page is published with GitHub Actions.

1. In the repository, open **Settings → Pages** and set **Source** to **GitHub Actions**.
2. Push a change to `index.html` or `assets/` on the `main` branch. The workflow publishes it within about a minute.

A publication can also be started by hand: **Actions → Publish on GitHub Pages → Run workflow**.

---

## Changing a link

All links are in `index.html`. When a resource moves, for example to another GitHub organisation, search the file for the old address and replace each occurrence:

- `https://github.com/punitharumilli/Schema`
- `https://punitharumilli.github.io/BestPracticeDocs/`
- `https://punitharumilli.github.io/DRMD_Generator/`
- `https://punitharumilli.github.io/DRMD_Videos/`

The displayed addresses below each resource (`github.com/punitharumilli/Schema` and similar) are in the same file.

---

## Licences

- **Inter** typeface: SIL Open Font License 1.1, see `assets/fonts/LICENSE.txt`.
- The **BAM** name and logo belong to the Bundesanstalt für Materialforschung und -prüfung (BAM).

---

## Contact

drmd@bam.de

© 2026 [Bundesanstalt für Materialforschung und -prüfung (BAM)](https://bam.de/en/)
