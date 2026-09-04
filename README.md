# Nguyen Minh Quan — Portfolio

A static portfolio site for sharing with the Claude Campus Ambassador application.

## Preview locally

Open `index.html` in a browser, or serve the repository root with any static file server. The root `index.html` redirects to this portfolio.

## Publish

- **GitHub Pages:** publish this repository root as a Pages site. The portfolio and its downloadable CV are self-contained.
- **Vercel / Netlify:** deploy the repository root as a static site.

Before publishing:
1. Replace the portfolio URL in the application form with the deployed HTTPS address.
2. Update `og:url` and `<link rel="canonical">` in `index.html` (currently placeholder `https://mingquanjp.github.io/portfolio/`) to match the real deployed URL.
3. Confirm `main.pdf` is committed in this repository. The CV link is `./main.pdf`.

## Files

- `index.html` — page markup, SEO/social meta tags, and Person structured data (JSON-LD)
- `styles.css` — all styling, including the mobile nav and responsive layout
- `script.js` — footer year, mobile menu toggle
- `og-image.png` — social share preview image (1200×630, used by `og:image` / `twitter:image`)

## Notes

- The "Learning" quick-fact on the hero (JLPT N2 · July 2026) is now in the past relative to today — update it or remove the date once that milestone has passed.
- Mobile view now includes a hamburger menu (previously navigation and the contact link were hidden entirely below 720px with no replacement).
