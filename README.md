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

This folder is already a git repo (branch `main`) with the SSH remote set to
`git@github.com:pandeyso-data/pandeyso-data.github.io.git`.

1. Create the repo on GitHub: **New repository → name `pandeyso-data.github.io`**,
   public, **do not** add a README or .gitignore (keep it empty).
2. Push:

   ```bash
   git -C D:/github_project/pandeyso-data.github.io push -u origin main
   ```

3. On GitHub: **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`**.

Live at `https://pandeyso-data.github.io` within a minute or two. Being a
`<user>.github.io` repo, Pages is often enabled automatically on first push.

## Updating content

All copy lives in `index.html`. Placeholders to revisit are listed at the bottom of
`SPEC.md` (employment dates, public email, exact IISc program title).
