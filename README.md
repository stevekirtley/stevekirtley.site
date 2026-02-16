# SJK Holding Page (GitHub Pages)

This is a single-file static holding page.

## Quick start (local)

Just open `index.html` in your browser.

## Deploy on GitHub Pages

### Option A — `username.github.io` (recommended)
1. Create a new repository named **`<your-username>.github.io`** (must match exactly).
2. Upload/commit `index.html` to the **root** of the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or `master`) / **/(root)**
5. Your site will be live at: `https://<your-username>.github.io/`

### Option B — project repo (e.g. `sjk-holding-page`)
1. Create a repo, commit `index.html` (and this README) to the root.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / **/(root)**
4. Your site will be live at: `https://<your-username>.github.io/<repo-name>/`

> Tip: In Option B, keep links absolute (like mailto/LinkedIn) — which this page already does.

## Custom domain (optional)
In **Settings → Pages**, add your custom domain and follow GitHub's DNS instructions.
