# Offline Notes Lab

A beginner-friendly offline-first Progressive Web App (PWA) built with React, TypeScript, and Vite. Create notes that persist in the browser, work offline, and can be installed as a standalone app.

## Node.js version

v24.18.0

## Run locally

```bash
npm install
npm run dev
```

## Verify the build

```bash
npm run check
npm run build
npm run preview
```

## PWA test

1. Open the production preview (`npm run preview`)
2. Open Developer Tools → Application → Manifest and confirm the manifest loads with no errors
3. Confirm both icons (192px and 512px) return status 200
4. Confirm the service worker is registered and active under Application → Service Workers
5. Switch Network to **Offline**
6. Reload the page — the app shell should load from cache
7. Create a note — it should save and persist after refresh

## Submission checklist

- Source code (`src/`)
- `package.json`
- `public/manifest.webmanifest`
- `public/sw.js`
- `public/icon-192.png` and `public/icon-512.png`
- This README
