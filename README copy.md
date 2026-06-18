# Executive Edge Private Security — Website

One-page, mobile-responsive marketing site. Static HTML, no build step. Ready for **Cloudflare Pages**.

## Files
- `index.html` — the entire site (HTML + CSS + JS inline)
- `favicon.ico` — multi-size icon (16–256px)
- `assets/logo.png` — transparent logo (used for icon/OG)
- `assets/og-image.png` — social share preview (1200×630)
- `assets/team.jpg` — **add your guard team photo here** (referenced in the "Why Us" section; shows a placeholder until added)
- `robots.txt`, `sitemap.xml` — SEO/AEO crawler config (welcomes Google, Bing, GPTBot, ClaudeBot, PerplexityBot, etc.)
- `_headers` — Cloudflare Pages security + cache headers

## Deploy to Cloudflare Pages
1. Push this folder to a GitHub/GitLab repo **or** use direct upload.
2. Cloudflare dashboard → **Workers & Pages → Create → Pages**.
3. Direct upload: drag this folder in. Git: connect the repo, set **Build command: (none)** and **Output directory: /**.
4. Deploy, then add your custom domain `eepsecurity.com` under **Custom domains**.

## Swap in the real logo / photo
- Replace `assets/logo.png` with your transparent-background logo (square works best).
- Regenerate `favicon.ico` from it, or ask me to.
- Drop your team photo in as `assets/team.jpg`.
- The header/footer currently show a clean SVG badge version of the logo so nothing ever looks broken — you can switch it to the photo logo anytime.

## Features
- SEO + AEO + GEO: meta tags, geo targeting, Open Graph/Twitter cards, `SecurityService` + `FAQPage` JSON-LD structured data, AI-crawler allow tags.
- Light/Dark theme switcher (remembers choice).
- Fully mobile-responsive.
- Contact + quick-quote forms wired to Web3Forms (AJAX, no page reload).
- Navy / yellow / black brand palette.

## Contact details baked in
Phone (628) 225-8016 · eepsecurity@gmail.com · Licensed statewide CA · PPO16771 / PI25275
