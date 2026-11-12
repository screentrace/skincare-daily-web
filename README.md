# Skincare Daily website

Static site for **Skincare Daily** (formerly PeauTrace), served by GitHub Pages at
https://www.peautrace.com (see `CNAME`).

## Pages
- `index.html`: landing page
- `support/`: contact and FAQ, including `#delete-account` (the account-deletion URL for Google Play)
- `privacy/`, `terms/`: rendered from `docs/privacy-policy.md` and `docs/TERMS_OF_SERVICE.md` in the app repo
- `app-ads.txt`: AdMob seller verification (do not remove)

## Look
Matches the app: sand canvas `#FAF7F2`, deep teal `#2F7F7A`, terracotta accent `#C8836B`,
Fraunces for headings and Plus Jakarta Sans for text. Tailwind is loaded from its CDN;
custom styles are in `css/style.css`.

## Images
`assets/images/phone-*.webp`, `og-image.png` and the logo come from the app's store-screenshot
helpers (`scripts/make_store_shots.py` in the app repo).

## Local preview
```bash
python -m http.server 8080
```
