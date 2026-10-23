# WPB — Wealth, Psychology & Business

A responsive static website starter designed for GitHub and Render.

## Included
- Premium navy, champagne-gold, ivory, and emerald brand styling.
- Mobile-responsive navigation and hamburger menu.
- Homepage, video library with search/category filters, wealth/psychology/business topic pages, article index and three article pages.
- Books/resources page. The Quiet Wealth checkout URL is included as supplied; other purchase URLs are intentionally blank until verified.
- Rumble profile link: https://rumble.com/user/EMMANUEL1320
- About, contact, privacy, terms, disclaimer, and 404 pages.
- Social share controls, SVG logo/brand mark and social-preview artwork.
- Basic page metadata, robots.txt, sitemap placeholder, and Render static-site configuration.

## Upload to GitHub
1. Download and extract this ZIP.
2. Open the `wpb-media-website` repository.
3. Upload the **contents** of this folder to the repository root, not the enclosing folder itself.
4. Commit the files to the default branch.

## Deploy on Render
1. Create a new **Static Site** in Render.
2. Connect the `wpb-media-website` GitHub repository.
3. Leave Build Command blank.
4. Set Publish Directory to `.` (repository root).
5. Deploy. Check the home page, every navigation link, video library, article pages, and book buttons on both mobile and desktop.

## Before public launch
- Update `robots.txt` and `sitemap.xml` with your actual deployed domain.
- Add exact verified video URLs in `assets/js/config.js`. No video URL has been invented.
- Add the exact Selar checkout URLs for the other books in `assets/js/config.js`.
- Add an approved public contact address to `pages/contact.html`.
- Review privacy policy, terms, and disclaimer to reflect the actual site and legal requirements.
- The `og:image` metadata currently points to an SVG social card. Some social networks may require a PNG/JPG image; create a raster social card if a platform does not display the SVG.
- For custom-domain canonical URLs, analytics, newsletter forms, and Meta Pixel, configure only after the actual domain, provider, and IDs are confirmed.

## Honest scope note
This is a public-facing static website. It does **not** include a secure administrator dashboard or backend content-management system. Adding a protected dashboard requires an authentication and storage service, secure access policies, and project-specific configuration. A dashboard mock-up is intentionally not presented as functional.

## Editing content
- Main site content: `index.html` and files under `pages/` and `articles/`.
- Video and book records: `assets/js/config.js`.
- Styles: `assets/css/style.css`.
- No passwords or secret tokens belong in the front-end configuration.
