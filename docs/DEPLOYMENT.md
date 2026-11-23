# Deployment

The portfolio is a static site deployed on **Vercel**:

- **Live URL:** https://javid-ahmadi-portfolio.vercel.app
- **Source of truth:** `index.html` (single self-contained page) + `og-image.jpg` for social previews.
- **Deploy:** the project folder is deployed to Vercel as a static site; every update is verified live (desktop + mobile rendering, all pages and links) before the link is shared.
- **SEO/social:** page title and Open Graph/Twitter metadata point at the live URL and `og-image.jpg`; `robots.txt` and `sitemap.xml` are included in this repo for reference.

No build step and no environment secrets are required — the site is fully static.
