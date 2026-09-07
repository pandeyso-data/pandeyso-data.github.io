# Sonal Pandey — Personal Portfolio

A single-page, static personal portfolio. No build step.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole site — inline CSS and JS, Google Fonts via `<link>` |
| `SPEC.md` | Spec-driven brief: professional story, structure, content rules |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

Serve at `https://pandeyso-data.github.io` using a user site repo:

```bash
cd portfolio
git init
git add .
git commit -m "Add personal portfolio"
git branch -M main
git remote add origin https://github.com/pandeyso-data/pandeyso-data.github.io.git
git push -u origin main
```

Then on GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
branch `main`, folder `/ (root)`. The site is live within a minute or two.

To use a project repo instead (served at `https://pandeyso-data.github.io/<repo>`), push
to that repo and enable Pages the same way.

## Updating content

All copy lives in `index.html`. Placeholders to revisit are listed at the bottom of
`SPEC.md` (employment dates, public email, exact IISc program title).
