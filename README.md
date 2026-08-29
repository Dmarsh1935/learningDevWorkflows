# CI/CD Pipeline Lab

A minimal static site used to study how a GitHub Actions build/deploy
pipeline works end-to-end, from an incident-response/security angle.

- `index.html` / `style.css` — the site itself, including a short
  "what the pipeline does" summary rendered on the page.
- `.github/workflows/deploy.yml` — builds the site and deploys it to
  GitHub Pages on every push to `main`, using the OIDC-based
  `actions/deploy-pages` flow (no stored deploy secret).
