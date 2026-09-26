# yuyudhn.github.io

Personal single-page **whoami** for Yudha P. — Cyber Security Consultant.

Static site (plain HTML + CSS), no build step. Deployed to GitHub Pages via
GitHub Actions (`.github/workflows/deploy.yml`).

## Structure

```
index.html            # the whole page
assets/css/style.css  # styling
*.png / *.ico / *.svg # favicons & app icons
site.webmanifest      # web app manifest
certificate/          # certificate files
```

## Local preview

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

> The previous Jekyll blog (CVE write-ups & posts) was archived outside this repo.
