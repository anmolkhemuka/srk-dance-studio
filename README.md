# SRK Dance Studio

A responsive static website for SRK Dance Studio in Seoni. It uses plain HTML, CSS, and a small inline script for scroll reveals, image parallax, and the footer year. Motion respects reduced-motion preferences.

## Preview locally

Open `index.html` in a browser, or serve this folder with any static file server. For example:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000/srk-dance-studio/` if serving from the parent directory, or `http://localhost:8000/` if serving this folder directly.

## Deploy to GitHub Pages

The included `.github/workflows/pages.yml` deploys the site whenever changes are pushed to `main`. Create a GitHub repository, push this folder to its `main` branch, then in **Settings → Pages** set the build and deployment source to **GitHub Actions**. The workflow publishes the site. All local references are relative, so it works from a project subpath.

## Before launch

- WhatsApp links are set to `https://wa.me/918827658424` using the supplied number `8827658424` and India country code.
- The hero, About panel, and gallery use locally stored, compressed photos in `assets/photos/`; no external photo URLs are used. Replace these files and update `index.html` if the studio selects different images. The photos were supplied for this site by the owner.
