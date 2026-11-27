# Owerri Ladies Picnic 7.0 — GitHub Pages Deployment

This is a static website and can be deployed directly with GitHub Pages.

## Files
- `index.html` — website entry point
- `assets/images/` — optimised WebP images loaded as separate files

## Deploy
1. Create a GitHub repository.
2. Upload the contents of this folder to the repository root (ensure `index.html` is at the root).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.

No build step or Node.js installation is required.

## Image performance
Images are stored as separate WebP assets rather than embedded in the HTML. Below-the-fold images use lazy loading and asynchronous decoding; the opening visual is prioritised. Keep the `assets/images/` folder alongside `index.html` when uploading.
