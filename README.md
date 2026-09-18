# Praise Always — website

A single-page site. Everything it needs is in this folder; there is no build step.

## Publish on GitHub Pages

1. Create a new repository on GitHub (for example `praise-always`). Public repositories get Pages for free.
2. Upload the **contents** of this folder to the root of the repository: `index.html`, `.nojekyll`, `README.md`, and the `assets` folder. (On github.com: **Add file → Upload files**, then drag everything in. The `.nojekyll` file is hidden on most computers; if it doesn't upload, it's optional.)
3. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io/praise-always/`.

## Use your own domain (once you own it)

1. In **Settings → Pages → Custom domain**, enter the domain (for example `praisealways.com`) and save. GitHub adds a `CNAME` file to the repo.
2. At your domain registrar, point the domain to GitHub Pages as described in GitHub's "Managing a custom domain" guide.
3. Tick **Enforce HTTPS** once it becomes available.
4. In `index.html`, change `og:image` to the full address, for example `https://praisealways.com/assets/og-image.png`, and add `<meta property="og:url" content="https://praisealways.com/">`. Link previews on social media need full addresses to show the image.

## Files

- `index.html` — the page, including the scroll-driven logo story
- `assets/favicon.svg`, `assets/favicon-32.png` — browser tab icon
- `assets/apple-touch-icon.png` — icon when saved to an iPhone home screen
- `assets/icon-512.png` — large icon
- `assets/og-image.png` — preview image when the link is shared

## Before launch

- Confirm the ESV notice in the footer with Crossway's current permissions for your use.
- Fonts (Cormorant Garamond, Jost) load from Google Fonts; nothing to install.
