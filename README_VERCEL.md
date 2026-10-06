# Aura Lens — Vercel Ready

## Deploy on Vercel

1. Extract this ZIP.
2. Upload the project contents to a GitHub repository.
3. Import the repository in Vercel.
4. Vercel should detect Vite automatically.
5. Build command: `npm run build`
6. Output directory: `dist`
7. Deploy.

The included `vercel.json` configures the Vite build and SPA fallback.

## Local

```bash
npm install
npm run dev
```

Camera access requires HTTPS in production (Vercel provides this) or localhost during local development.

## MediaPipe

The application loads the MediaPipe Hands runtime/model assets from jsDelivr. A network connection is required when the vision runtime is initialized.
