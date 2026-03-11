## EgoLink Challenge Website

This repository hosts a static website for the **EgoLink: Egocentric Language‑Vision Interactive Network Knowledge Challenge**, summarizing the OpenReview paper description and providing a landing page for the challenge resources.

### Structure

- `index.html` – main single-page site.
- `styles.css` – page styling.

### Local Preview

You can open `index.html` directly in a browser, or use any simple HTTP server, e.g.:

```bash
cd ego-link-website
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

### Deploying to GitHub Pages

1. Create a new repository on GitHub (for example `challenge2026`).
2. Initialize git and push:

```bash
cd ego-link-website
git init
git add .
git commit -m "Init EgoLink website"
git branch -M main
git remote add origin <your_repo_url>
git push -u origin main
```

3. On GitHub, go to **Settings → Pages**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` and `/ (root)`

GitHub will build and publish the site at `https://<your-name>.github.io/<repo-name>/`.

