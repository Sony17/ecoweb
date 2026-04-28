# Ecoweb — Ecosyz Landing Site

The marketing landing site for **Ecosyz Core Solution Ltd.** — home of **Open Idea** and **ORAA**.

Plain-static HTML, no build step. Drop into any web host or deploy to Vercel.

## Local preview

Open `index.html` directly in your browser, or run a tiny server:

```bash
python3 -m http.server 5173
# or
npx serve
```

## Deploy to Vercel

```bash
npm i -g vercel
vercel login
vercel --prod
```

The repo includes `vercel.json` (cache headers, no build step) and `.vercelignore`.

## What's inside

- `index.html` — the entire single-page site (HTML + CSS + JS)
- Image assets — `openidea.jpg`, `oraa.png`, `dpiit.png`, `start-in-up.png`, `gbu.png`
- Certificate PDFs — `dpiit-certificate.pdf`, `start-in-up-certificate.pdf`, `udyam-openidea-certificate.pdf`
- `vercel.json` — Vercel deployment config
- `.vercelignore` — excludes `ecosyz-app/` and `node_modules/` from deploys

## Sections

1. Hero — Three.js neural network bg, Ecosyz wordmark, typewriter headline
2. About — Mission, Vision, 5 Core Principles (flip cards with photos)
3. Projects — Open Idea (openidea.world) and ORAA cards with logos
4. Company Credentials — CIN, Founder, DPIIT recognition + 4 partner badges (clickable PDFs)
5. Footer — Legal block with CIN, registered office address

## Brand

- Domain: [ecosyz.com](https://ecosyz.com)
- LinkedIn: [linkedin.com/company/110214398](https://www.linkedin.com/company/110214398/)
- WhatsApp: +91 78388 32332
- Email: info@openidea.world

— Built by Sony Yadav · Ecosyz Core Solution Ltd. · 2024
