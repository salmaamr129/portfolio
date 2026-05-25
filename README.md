# salmaamr129.github.io

Personal portfolio site, deployed at **<https://salmaamr129.github.io>**.

Static HTML + Tailwind (loaded from CDN). No build step — GitHub Pages
serves the files in this repo directly. Push to `main` and the live site
updates within ~1 minute.

## Layout

```
index.html         Single-page portfolio (hero, about, skills, experience,
                   projects, blog teaser, contact)
blog/index.html    Blog landing page (stub for now)
assets/            Images embedded in the page (project screenshots, etc.)
README.md          This file
```

## Edit + preview locally

No install needed. From the repo root:

```bash
python3 -m http.server 8765
```

Then open <http://127.0.0.1:8765/>. Edit `index.html`, refresh the page.

## Deploy

Pushing to `main` is the deploy. GitHub Pages picks up the change
automatically. To check the build status:

```
github.com/salmaamr129/salmaamr129.github.io/deployments
```

## Things to add over time

- Real screenshots for the LibraryManagementSystem and Price List API project cards
- First blog post (topic list is in the placeholder cards under `#blog`)
- Custom domain (optional) — buy a domain, add a `CNAME` file with the
  domain on a single line, and configure DNS as
  [GitHub docs describe](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
