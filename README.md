# Powering Colossus — xAI Energy & Emissions (UNU INWEH)

A single-page research visualization. `index.html` is fully self-contained (only Chart.js is loaded from a CDN), so GitHub Pages can serve it as-is.

## Deploy on GitHub Pages

### Option A — web browser, no command line
1. Go to https://github.com/new and create a repository, e.g. `xai-colossus-brief` (Public).
2. On the new repo page, click **uploading an existing file**.
3. Drag in `index.html` (and this `README.md` if you like). Commit.
4. Go to **Settings → Pages**.
5. Under **Build and deployment → Source**, choose **Deploy from a branch**.
6. Set branch to `main` and folder to `/ (root)`. Save.
7. Wait ~1 minute. Your link appears at the top of the Pages settings:
   `https://<your-username>.github.io/xai-colossus-brief/`

### Option B — command line
```bash
cd "xai-report-site"
git init
git add index.html README.md
git commit -m "Add xAI Colossus energy & emissions brief"
git branch -M main
git remote add origin https://github.com/<your-username>/xai-colossus-brief.git
git push -u origin main
```
Then enable Pages via **Settings → Pages** as in steps 4–7 above.

That `github.io` URL is what you paste into your email.
