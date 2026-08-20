# Wolfarth School Trade — Landing Page

A cinematic, 3D-animated landing page for a trading education brand. Built as a single static HTML page with Tailwind CSS (via CDN) and a Three.js particle/shape background in the hero section.

- `index.html` — the full landing page (this is what gets deployed)
- `three-background-demo.html` — the Three.js hero background in isolation, useful for tweaking the animation on its own
- `docs/DESIGN.md` — the design system reference (colors, type scale, spacing, components)
- `docs/preview.png` — a full-page screenshot of the design

No build step, no dependencies to install — it's plain HTML/CSS/JS that pulls Tailwind, Google Fonts, and Three.js from public CDNs at page load.

## Put it on GitHub

1. Create a new repo on GitHub (don't initialize it with a README, since you already have one).
2. From this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Wolfarth School Trade landing page"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

## Deploy on Vercel

**Option A — Vercel dashboard (easiest)**
1. Go to https://vercel.com/new and import the GitHub repo you just pushed.
2. Framework preset: choose **Other** (it's a static site — no build command, no install command, no output directory needed).
3. Click **Deploy**. Vercel will serve `index.html` at your project's root URL.

**Option B — Vercel CLI**
```bash
npm i -g vercel
vercel login
vercel        # deploys a preview
vercel --prod # deploys to production
```
Run this from inside the project folder; the CLI will detect it as a static project automatically.

Either way, once deployed your site is live at `https://<your-project>.vercel.app`, and every push to `main` will trigger a new deployment automatically if you used Option A.

## Notes / things worth knowing before you go live

- **Tailwind via CDN is fine for a prototype but not ideal for production** — it compiles styles in the browser on every page load, which adds a small delay and a console warning. For a real production launch, consider installing Tailwind properly (`npm install -D tailwindcss`) and building a static CSS file instead. Happy to set that up if you want.
- All buttons ("GET THE PACK", "join telegram vip", "best school", etc.) are currently non-functional placeholders — they don't link anywhere yet. Let me know what they should point to (a Stripe checkout, a Telegram link, a signup form) and I can wire them up.
- The hero image and any external image URLs are pulled from a temporary Google-hosted asset link — for production you'll want to host your own images (e.g. in an `/assets` folder in this repo) rather than relying on that URL staying alive.
- The language switcher (French/Arabic) in the nav is currently decorative — it doesn't yet change page content.
