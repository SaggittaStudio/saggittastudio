# Saggitta Studio — NeoCyber Images Edition

Static single-page client-rendered website for Saggitta Studio. Minimal dark crimson, image-first presentation, no video and no illustrated SVG assets.

## Run
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

Webpack source maps disabled (`devtool: false`). Images are local WebP files in `public/media`. Supports Spanish, English, French.

## GitHub Pages
Push to `main`, then set **Settings → Pages → Build and deployment → GitHub Actions**. Workflow in `.github/workflows/deploy.yml` publishes `dist/`.
