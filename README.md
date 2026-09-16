# Uzbekly — Uzbek Language Learning App

## Vercel deployment
1. Import this repository into Vercel.
2. Framework preset: Vite (or let Vercel detect it).
3. Build command: `npm run build`
4. Output directory: `dist`
5. Add Environment Variable:
   `ANTHROPIC_API_KEY` = your Anthropic API key
6. Redeploy.

The React app calls `/api/claude`; the Anthropic secret stays server-side.

## Local
npm install
npm run dev
