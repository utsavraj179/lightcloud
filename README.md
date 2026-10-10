# ☁️ LightCloud – Minecraft Hosting Website

A 3D moon-and-stars website for **LightCloud** Minecraft hosting. Plain HTML + CSS + JavaScript, with [Three.js](https://threejs.org/) for the 3D background. No build step needed.

## Pages

| File | Page |
|------|------|
| `index.html` | Home: hero, features, plan preview |
| `plans.html` | All Light Cloud plans, RAM filters, comparison table |
| `terms.html` | Terms of Service, Acceptable Use, Payments & Refunds, Privacy, Uptime & Support |

## Links

- **Dashboard:** https://lightcloud.fitfillo.qzz.io/
- **Discord:** https://discord.gg/fwXGrVaDeS

## Plans (Ryzen 7 Budget)

| Plan | RAM | CPU | Disk | Price |
|------|-----|-----|------|-------|
| MINI | 1GB | 1 vCPU | 10GB | ₹10 |
| STARTER | 2GB | 150 | 15GB | ₹20 |
| BASIC | 4GB | 200 | 25GB | ₹40 |
| PLUS | 6GB | 250 | 40GB | ₹70 |
| PRO | 8GB | 300 | 50GB | ₹130 |
| ULTRA | 12GB | 350 | 70GB | ₹160 |
| ADVANCED | 16GB | 400 | 90GB | ₹200 |
| TITAN | 24GB | 450 | 120GB | ₹250 |
| EXTREME | 32GB | 500 | 160GB | ₹450 |
| GOD | 48GB | 600 | 200GB | ₹590 |
| GOD PLUS | 64GB | 800 | 250GB | ₹699 |

All plans include AMD Ryzen 7, NVMe SSD, DDoS Protection, AetherPanel and High Performance.

## Editing

- **Plans:** edit the `PLANS` array in the `<script>` of `plans.html` (and `index.html`).
- **Features:** edit the `FEATURES` array in `index.html`.
- **Policy text:** edit the `SECTIONS` array in `terms.html`.
- **Brand / links:** search for `LightCloud`, the Discord invite and the dashboard URL.

## Deploy (Vercel)

1. Put `index.html`, `plans.html` and `terms.html` in one folder or GitHub repo.
2. Import the repo in [Vercel](https://vercel.com/) (framework: **Other**, no build command).
3. Deploy, then connect your custom domain.
4. Change the links between pages from the preview URLs to `/plans.html` and `/terms.html`.

## Tech

- HTML, CSS, vanilla JS
- Three.js r128 (loaded from cdnjs)

## TODO

- [ ] Payment Methods page
- [ ] Downloadable files page
- [ ] "Buy Now" buttons linked to Discord tickets

© LightCloud
