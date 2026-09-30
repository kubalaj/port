# paulkubala.com

Static, self-hosted replacement for the Squarespace portfolio. Plain HTML + CSS, no build step.

## Editing
- `index.html` — all page content (reel, film credits, experience, contact).
- `styles.css` — colors live at the top in `:root`.
- `images/` — drop poster/still images here (`inside-out-2.jpg`, `elemental.jpg`, `turning-red.jpg`).
- `resume.pdf` — add to the repo root for the "Download Resume" button.
- Demo reel — uncomment the `<iframe>` in `index.html` and paste your Vimeo/YouTube embed URL.

## Preview locally
    python3 -m http.server 8000   # then open http://localhost:8000

## Hosting (free)
- **GitHub Pages**: repo Settings → Pages → deploy from branch `main`, folder `/`. Add a `CNAME` file containing `www.paulkubala.com`.
- **Cloudflare Pages / Netlify**: connect this repo, no build command, output dir `/`.

Then point your domain's DNS at the host (e.g. `www` CNAME → `kubalaj.github.io`) and cancel Squarespace once it's live.
