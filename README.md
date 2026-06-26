# astiq.net

Website for **ASTIQ**, a studio that designs and builds custom mobile and web apps.
The site is a company landing page with a sub-page per product.

Static site (no build step) deployed on Vercel.

| Path | File | Purpose |
|---|---|---|
| `/` | `index.html` | ASTIQ studio landing page |
| `/cryptogram` | `cryptogram/index.html` | ASTIQ Cryptogram product page |
| `/cryptogram/privacy` | `cryptogram/privacy.html` | Privacy policy for the game (Google Play requirement) |
| `/app-ads.txt` | `app-ads.txt` | AdMob authorized sellers (fill in after AdMob account exists) |

`vercel.json` enables clean URLs, so `cryptogram/privacy.html` is served at `/cryptogram/privacy`.

## Adding a new product
Create a folder `productname/` with an `index.html` (and any sub-pages), then link
it from the "Work" section of the root `index.html`.

Contact: alnahash@gmail.com
