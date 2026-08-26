# Archviz Damian — Portfolio Website

Static personal portfolio website for Damijan Koprivc / Archviz Damian.

## What is included

- Responsive single-page portfolio
- Selected Behance projects
- About, process, video and contact sections
- Direct links to Behance, Facebook, YouTube and Pinterest
- SEO/meta basics
- No framework or build step required

## Preview locally

Open `index.html` in a browser.

For the most accurate preview, run a simple local server from this directory, for example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub + Cloudflare Pages

1. Create a new GitHub repository, e.g. `archviz-damian`.
2. Upload all files from this folder to the repository root.
3. In Cloudflare Pages choose **Connect to Git** and select the repository.
4. Framework preset: **None**.
5. Build command: leave empty.
6. Build output directory: `/` or leave as the default root for a static site.
7. Deploy.

## Images

This first version uses public Behance project thumbnail URLs. For a final production version, replace them with Damijan's original optimized images stored locally under `assets/images/` (WebP/AVIF recommended).

## Contact

The current contact link uses the public email shown in the Behance portfolio.
