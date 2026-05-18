# DODDS STORE 🇩🇿

Manga & Anime e-commerce — Batna, Algeria.

## Setup

```bash
npm install
npm run dev
```

## Deploy to Netlify

1. Push to GitHub or drag-drop the folder on Netlify
2. Build command: `npm run build`
3. Publish directory: `dist`
4. Add environment variables in Netlify dashboard:

```
VITE_ADMIN_PASSWORD=dodds2025
VITE_CLOUDINARY_CLOUD_NAME=dbv1sewwf
VITE_CLOUDINARY_API_KEY=lsl8azZwPzgqawQ7pejUdUiCnyk
```

## Admin Access

Go to `/admin` → click the ADMIN button in the footer.
Password: set via `VITE_ADMIN_PASSWORD` env variable (default: `dodds2025`)

## Cloudinary Setup

1. Go to Cloudinary Dashboard → Settings → Upload → Upload Presets
2. Create unsigned preset named: `dodds_store`
3. Set folder to: `dodds_store/products`
