# Furnace Repair Spring TX — Astro Site

Static Astro site for **furnacerepairspringtx.com**, optimized for Cloudflare Pages.

## Features
- Responsive, mobile-first design
- Deep navy + orange color theme (changed from original teal)
- OpenStreetMap embed for 19504 Wied Rd b, Spring, TX 77388
- SEO: meta tags, canonical, JSON-LD HVACBusiness schema, sitemap, robots.txt
- Markdown blog with content collections
- Fast static build for Google indexing
- Cloudflare Pages ready (static output, no adapter needed)

## Phone number
Placeholder: **(281) 555-0199** — search/replace `2815550199` and `555-0199` with your real number.

## Deploy to Cloudflare Pages
1. Push this folder to a GitHub/GitLab repo.
2. In Cloudflare Dashboard → Workers & Pages → Create → Connect to Git.
3. Build settings:
   - **Framework preset:** Astro
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. Add custom domain `furnacerepairspringtx.com`.
5. Submit `https://furnacerepairspringtx.com/sitemap-index.xml` in Google Search Console.

## Local development
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```
Output is in `dist/`.

## Notes
- Site is fully static — ideal for Pages and SEO.
- `@astrojs/sitemap` generates `/sitemap-index.xml` at build time.
- `public/robots.txt` points crawlers to the sitemap.
- Blog posts live in `src/content/blog/*.md`.
- Some service/problem pages may still reference original structure; customize as needed.
