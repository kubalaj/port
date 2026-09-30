# paulkubala.com

Self-hosted copy of the Squarespace homepage: plain HTML + CSS, no build step.

## Files
- `index.html` — bio, work experience, photo placeholder, social links.
- `styles.css` — the layout (a recreation of the Squarespace 24-column grid) and fonts. Colors are the
  variables at the top: `--bg` (vanilla background), `--text`, and `--block` (the grey photo placeholder).

## Preview locally
    python3 -m http.server 8000   # then open http://localhost:8000

## Hosting (free)
- **GitHub Pages**: repo Settings → Pages → deploy from branch `main`, folder `/`. Add a `CNAME` file containing `www.paulkubala.com`.
- **Cloudflare Pages / Netlify**: connect this repo, no build command, output directory `/`.

Then point your domain's DNS at the host (e.g. `www` CNAME → `kubalaj.github.io`) and cancel Squarespace once it's live.
