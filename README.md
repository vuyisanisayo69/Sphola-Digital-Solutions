# Sphola Digital Solutions website

Static site: `index.html` plus the `assets/` folder. No build step.

## Deploy on Cloudflare Pages
1. Push these files to a GitHub repo (keep `index.html` and `assets/` in the repo root).
2. Cloudflare dashboard > Workers & Pages > Create > Pages > Connect to Git, then choose the repo.
3. Build command: leave empty. Build output directory: leave empty (or `/`). Save and Deploy.
4. In the project, open Custom domains > Set up a custom domain, and add your domain.

## Editing
Open `index.html`. Text, services and contact details are plain HTML. Images live in `assets/`.
Last updated: 21 October 2026
