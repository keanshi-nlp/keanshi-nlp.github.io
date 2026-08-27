# Academic Homepage

A simple, fast, dependency-free academic homepage. Plain HTML + CSS — no build step required.

## Customize

All content lives in `index.html`. Search for and replace:

- **Name & title** — the `<title>` tag and the hero bento tiles
- **Bio** — the paragraphs in the `#about` section
- **News** — the list items in `#news`
- **Publications** — the `.pub` entries in `#research`
- **Path** — the experience/education items in `#path`
- **Links** — email, Google Scholar, and GitHub URLs
- **Photo & logos** — images live in `assets/img/` (`me.jpg`, `icon.png`, `company/`, `research/`)

Colors are CSS variables at the top of `style.css`. The body font
(Montserrat Alternates) is self-hosted from `fonts/`; the display font
(Fraunces) loads from Google Fonts.

## Deploy to GitHub Pages

1. Create a repository named `<your-username>.github.io` on GitHub
   (or any repo name, if you prefer a project page).
2. Push this folder:

   ```bash
   git init
   git add .
   git commit -m "Add academic homepage"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo>.git
   git push -u origin main
   ```

3. On GitHub: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / (root)**.
4. Your site will be live at `https://<your-username>.github.io/` (or `/<repo>/` for project pages).

The `.nojekyll` file tells GitHub Pages to serve the files as-is without Jekyll processing.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000
