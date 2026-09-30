# paulkubala.com

Self-hosted copy of the Squarespace homepage: plain HTML + CSS, no build step.

## Files
- `index.html` — bio, work experience, photo, social links.
- `styles.css` — the layout (a recreation of the Squarespace 24-column grid), fonts and film-grain effect.
- `images/paul.jpg` — **add this**: download your photo from Squarespace and save it here. Until it exists
  the page falls back to the Squarespace-hosted copy, which will go away when you cancel.

## Preview locally
    python3 -m http.server 8000   # then open http://localhost:8000

## Hosting (free)
- **GitHub Pages**: repo Settings → Pages → deploy from branch `main`, folder `/`. Add a `CNAME` file containing `www.paulkubala.com`.
- **Cloudflare Pages / Netlify**: connect this repo, no build command, output directory `/`.

Then point your domain's DNS at the host (e.g. `www` CNAME → `kubalaj.github.io`) and cancel Squarespace once it's live.
