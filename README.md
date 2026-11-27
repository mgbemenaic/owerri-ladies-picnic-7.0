# Owerri Ladies Picnic 7.0 Website

## Deploy to GitHub / Vercel
1. Upload `index.html` and the complete `assets/` folder to the repository root.
2. Commit and push to GitHub.
3. Vercel will redeploy from the repository.

## Image-loading changes
- All embedded WebP images have been extracted into `assets/images/` as separate static files.
- All 57 image elements use `loading="eager"` and `decoding="async"`.
- The first hero-carousel image is preloaded with high fetch priority.
- No image uses browser lazy loading.

Keep the `assets/images/` folder beside `index.html`; do not upload only the HTML file.
