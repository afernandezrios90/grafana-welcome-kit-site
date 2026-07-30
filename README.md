# Grafana Cloud Welcome Kit

A single-page welcome guide for new Grafana Cloud customers — how to meet your
account team, complete onboarding, deploy your first stack, contact support,
understand billing, and find learning resources.

**Live page:** `https://<your-username>.github.io/<repo-name>/`

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Contents

- `index.html` — the welcome kit page (responsive; supports print / "Save as PDF")
- `fonts/`, `images/`, `grafana-labs-logo-white.png` — page assets (self-contained, no CDN)
- `welcome-kit-sub100.pdf` — downloadable PDF version

## Publishing with GitHub Pages

1. Push this folder's contents to the root of a **public** repository.
2. In the repo: **Settings → Pages → Build and deployment → Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then save.
4. Your page goes live at `https://<your-username>.github.io/<repo-name>/`.

The `.nojekyll` file ensures GitHub Pages serves every asset as-is.
