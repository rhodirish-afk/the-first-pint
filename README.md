# The First Pint

Static multi-page campaign site for **The First Pint** — real ale for 18–30s, and anyone who has never tried it. A third of a pint. No lecture.

Live URL: [https://rhodirish-afk.github.io/the-first-pint/](https://rhodirish-afk.github.io/the-first-pint/)

Source campaign copy: [roryhanrahan.co.uk/first-pint.html](https://roryhanrahan.co.uk/first-pint.html)

## Pages

- `index.html` — home / pitch / CTA with handpump hero
- `about.html` — what it is (feature cards) + why now
- `pubs.html` — how a pub can join in + chalkboard
- `camra.html` — what we ask of CAMRA
- `join.html` — contact and invites
- `css/styles.css` — shared warm alehouse styles
- `assets/` — original SVG illustrations, `favicon.svg`, and the social share image: `og-image.svg` (source) and `og-image.png` (1200×630, rendered from the SVG; this is what `og:image` points to)

All internal links are relative so project Pages at `/the-first-pint/` works. Canonical, `og:url` and `sitemap.xml` use the absolute project URL.

### Regenerating the share image

Edit `assets/og-image.svg`, then render it to a 1200×630 PNG (for example: open the SVG in Chrome at 1200×630 and screenshot, or `rsvg-convert -w 1200 -h 630 assets/og-image.svg -o assets/og-image.png`). Upload the PNG as a binary file — the GitHub web uploader or `git push` both work; text-only API pushes corrupt it.

## Artwork

Illustrations in `assets/` (handpump, third-pint glass, cask, chalkboard, favicon, OG art) are **original SVG** drawn for this campaign. No stock photos.

## Enable GitHub Pages

1. Open the repo on GitHub: **Settings → Pages**
2. Under **Build and deployment → Source**, choose **Deploy from a branch**
3. Branch: **main** · Folder: **/ (root)**
4. Save — the site should appear at https://rhodirish-afk.github.io/the-first-pint/ after a short build

Contact: myone_ie@hotmail.co.uk · 07752 144777 · The Vine Inn, 11 Abingdon Road, Cumnor
