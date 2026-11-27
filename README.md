# iBlooming × Alfagift Mini App – Prototype

Static, single-file prototype. No build step, no dependencies.

## Deploy

**Option A – Vercel dashboard**
1. vercel.com → Add New → Project → drag this whole folder in (or push it to a Git repo and import it).
2. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
3. Deploy.

**Option B – Vercel CLI**
```
npm i -g vercel
cd ibl-alfagift
vercel          # preview
vercel --prod   # production
```

## Notes
- `index.html` (~14 MB) holds all images and code inline; only Google Fonts load from the web.
- Search engines are told not to index it (meta tag + `X-Robots-Tag` header).
- Best viewed on desktop (phone frame + jump panel) or on an iPhone (full-screen app view).
- To share only with your team, turn on Vercel Deployment Protection (Project → Settings → Deployment Protection).
