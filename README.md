# Racik Gifts — Christmas Collection 2026 (website)

One-page website, Bahasa Indonesia (default) + English.
Plain HTML/CSS/JS: no build step, no install needed.

## Files
- `index.html` — the whole website (content, styles, script)
- `assets/` — logos, favicon

## Where to edit things (all inside `index.html`, in the <script> part at the bottom)
- WhatsApp number → `WHATSAPP_NUMBER` (format 62..., without + or 0)
- Package names, prices, contents → `PACKAGES`
- All website text in both languages → `I18N` (`id` = Indonesia, `en` = English)
  Remember to change the text in BOTH `id` and `en`.

English version link: `https://your-domain/?lang=en`

## Deploy to Vercel
Option A — drag & drop (easiest)
1. Go to https://vercel.com/new and sign in.
2. Upload / drag the `racik-gifts-website` folder.
3. Framework preset: **Other**. Leave build settings empty. Click **Deploy**.

Option B — Vercel CLI
```
npm i -g vercel
cd racik-gifts-website
vercel          # preview
vercel --prod   # production
```

## Later: real product photos
Each package card currently uses an illustrated gift box.
When photos are ready, send them over and they can replace the illustrations.
