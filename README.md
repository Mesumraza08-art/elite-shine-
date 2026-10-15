# Elite Shine Cleaning Services

Static single-page website for Elite Shine Cleaning Services LLC (Utah County, UT).

## Deploying to Hostinger

**Option A: Git deploy (recommended)**
1. hPanel → Websites → Manage → Advanced → **GIT**.
2. Repository: `https://github.com/Mesumraza08-art/elite-shine-.git`, branch `main`, install path left empty (deploys to `public_html`).
3. Click **Create**, then **Deploy**. Enable auto-deployment to redeploy on every push.

**Option B: File Manager upload**
Upload `index.html`, `.htaccess`, `robots.txt` and `sitemap.xml` into `public_html`.

## Notes
- All images are embedded in `index.html`; no other assets are required.
- `.htaccess` forces HTTPS + `www`, enables compression and basic security headers. Enable the free SSL certificate in hPanel first.
- The quote/contact forms are currently front-end only (validation, no sending).
