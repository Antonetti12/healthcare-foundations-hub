# Healthcare Foundations Study Hub

A self-hosted static site (HTML, CSS, and JavaScript only). No build step.

## Run locally

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080/`.

## GitHub Pages

This folder is the site root. All links are relative, so it also works under a project-site subpath such as `https://username.github.io/repo-name/`.

The site is public but is not meant to be easy to find: every page has a `noindex, nofollow, noarchive` robots meta tag, and `robots.txt` disallows all crawlers.

## Customize the name

Edit `js/config.js` and set `ownerName` (and optionally `title`).

Chapter review guides will be added under Review Guides as they are finished. Downloads will appear in the Downloads section.
