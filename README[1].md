# Ndihma.al - Vite project (bilingual)

This is a lightweight Vite project for **Ndihma.al** (Albanian + English). It includes an automatic language detector (defaults to Albanian) and a manual toggle that persists the user's choice in `localStorage`.

## Local development

```bash
# 1. Install dependencies
npm install

# 2. Run dev server
npm run dev
# open http://localhost:5173
```

## Build for production

```bash
npm run build
# preview locally
npm run preview
```

## Deploy to Netlify

1. Create a GitHub repository and push this project.
2. In Netlify, click "New site from Git" and connect your GitHub repo.
3. Set build command: `npm run build` and publish directory: `dist`
4. Deploy — Netlify will auto-deploy on each push.

Optionally, point your domain `ndihma.al` to Netlify following Netlify docs (add CNAME / A records).
