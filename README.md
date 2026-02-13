# codex

A simple to-do web app built with plain HTML, CSS, and JavaScript.

## Run locally

Use any static server. For example:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy to GitHub Pages

This repository includes `.github/workflows/static.yml` to deploy the site from the `main` branch.

If the workflow fails with `Get Pages site failed` or `HttpError: Not Found`, enable Pages once in repository settings:

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Re-run the workflow (or push a new commit to `main`).

After that, the app will be published at:

`https://<your-username>.github.io/<your-repo>/`
