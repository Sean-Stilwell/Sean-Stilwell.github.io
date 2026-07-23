# Sean Stilwell - Personal Website

![MIT License](https://img.shields.io/github/license/Sean-Stilwell/Sean-Stilwell.github.io) ![Accessibility check](https://img.shields.io/github/actions/workflow/status/Sean-Stilwell/Sean-Stilwell.github.io/.github%2Fworkflows%2Fa11y.yml?label=a11y) ![Lighthouse test](https://img.shields.io/github/actions/workflow/status/Sean-Stilwell/Sean-Stilwell.github.io/.github%2Fworkflows%2Flighthouse.yml?label=lighthouse) ![GitHub Release](https://img.shields.io/github/v/release/Sean-Stilwell/Sean-Stilwell.github.io)

Static personal site built with the **GC Design System** and deployed via **GitHub Pages**.

- **Live site:** https://seanstilwell.ca
- **Repository:** this repo (`Sean-Stilwell.github.io`) serves Pages directly from the default branch.

## Features

- Built with the **GC Design System** for consistent, accessible, bilingual-ready UI
- **Bilingual pages**: English (`index.html`) and French (`index-fr.html`)
- **Custom domain** via `CNAME`
- **Search-friendly** with `sitemap.xml` / `sitemap.txt`
- **Custom 404** page

## Project structure

```
├─ .github/       # GitHub configuration
├─ assets/        # Images, styles, scripts (static)
├─ 404.html       # Custom not-found page
├─ CNAME          # Custom domain for GitHub Pages
├─ LICENSE        # MIT License file
├─ google*.html   # Search Console site verification
├─ index.html     # English homepage
├─ index-fr.html  # French homepage
└─ preview.png    # README/Marketplace preview image
├─ sitemap.xml    # XML sitemap
├─ sitemap.txt    # Plain-text sitemap
```

## Local setup

No framework or build tools required.

1. **Clone**
   ```bash
   git clone https://github.com/Sean-Stilwell/Sean-Stilwell.github.io.git
   cd Sean-Stilwell.github.io
   ```

2. **Serve locally**

Just open the `index.html` or `index-fr.html` files to get started.

* Using Python 3:
   ```bash
   python3 -m http.server 8000
   ```
   Open your browser to `http://localhost:8000`

* Using Node.js (with `http-server`):
   ```bash
   npx http-server -p 8000
   ```
   Open your browser to `http://localhost:8000`

## Deployment

This is a user site (<username>.github.io), so GitHub Pages serves from the repository’s default branch root. After pushing to master/main, Pages will update automatically.

* **Custom domain:** managed via the CNAME file. Update its contents to change the domain.
* **HTTPS:** enable/verify in Repo → Settings → Pages.

## Accessibility & GC Design System

I've built this site using the [GC Design System](https://design.canada.ca/) to ensure accessibility and consistent design.

Helpful links:

* [GC Design System](https://design-system.alpha.canada.ca/)
* [Components](https://design-system.alpha.canada.ca/en/components/)

## Licence

This project is licensed under the [MIT License](LICENSE).