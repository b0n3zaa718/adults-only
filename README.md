# The Hub — Adults-Only Dating

This repo contains the static landing page for **The Hub**. It is a simple HTML/CSS site with no build step.

## Local preview

From the project root:

```bash
python -m http.server 8000
```

Then open: <http://localhost:8000>

## Deploy setup (GitHub Pages)

A GitHub Actions workflow is included at `.github/workflows/deploy.yml` to publish the site to **GitHub Pages**.

### One-time repository configuration

1. Go to **Settings → Pages** in your GitHub repo.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push to `main`, `master`, or `work` to trigger the deploy.

After the workflow finishes, the site URL will appear in the workflow summary.

## Files

- `index.html` — page content
- `styles.css` — styling
