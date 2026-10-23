# Amethyst Void

The Amethyst Void Foot Modeling storefront — a single static page with the full
Harley Angel library.

Source: shared Muse space (`amethyst-void-yh6xhxy4axosao`), mirrored here as a
plain static site so it can be hosted on GitHub Pages.

## Contents

- `index.html` — the whole site, CSS and JS inline
- `assets/` — 124 WebP frames plus the site icon and social preview card

Gallery breakdown:

| Section | Frames |
| --- | --- |
| The Work (rotating gallery) | 14 |
| Bedroom Set | 56 (46 portraits, 8 specials, 2 whipped-cream studies) |
| Harley After Midnight (Halloween) | 51 (20 graveyard, 20 pumpkin fog, 11 ghost bride) |
| Hero / portrait | 3 |

Total: 124 images, about 50 MB.

## Run it locally

Open `index.html` in a browser. No build step, no dependencies — the only
external resource is Google Fonts.

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
