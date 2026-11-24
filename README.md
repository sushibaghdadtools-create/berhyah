# Berhyah | برحية — Landing Page

Static landing page for Berhyah (برحية), Iraqi Barhi dates.

## Structure

```
index.html            Page (Arabic RTL, with EN toggle)
assets/               Images, logo and fonts
assets/vendor/        Runtime + React 18.3.1 (self-hosted, no CDN needed)
```

## Run locally

The page must be served over HTTP (not opened as `file://`):

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy on GitHub Pages

1. Push this folder to a repository.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / root.
3. The site will be live at `https://<user>.github.io/<repo>/`.

Works the same on Netlify, Vercel or Cloudflare Pages (no build step).
