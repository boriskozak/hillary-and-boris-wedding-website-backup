# Hillary & Boris wedding site

Static rebuild of the Squarespace site for GitHub Pages. No build step, no Jekyll.

## Deploy

1. Create a repo (for a `username.github.io` URL, name it exactly that; otherwise it publishes at `username.github.io/repo-name`).
2. Copy everything in this folder into the repo root and push to `main`.
3. Repo Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. Wait a minute, then open the URL shown on that page.

For a custom domain, add a `CNAME` file containing the bare domain and point DNS at GitHub per their docs.

## Files

- `index.html`, `registry.html`, `rsvp.html`: the three pages
- `style.css`: all styling
- ``: monogram and hotel photos recovered from the backup
- `.nojekyll`: tells Pages to serve files as-is
