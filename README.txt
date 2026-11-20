PIXELFORGE — IVAN PRODUCTIONS
PUBLIC WEBSITE DEPLOYMENT
================================

This folder contains the static website. No backend or server-side code is required.

PUBLISH WITH GITHUB PAGES (FREE FOR PUBLIC REPOSITORIES)
1. Sign in to https://github.com/ (create an account if needed).
2. Create a NEW PUBLIC repository named: pixelforge
3. Upload all files from this folder to the repository root. Make sure index.html is at the root.
4. Open the repository Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select branch main and folder /(root), then Save.
7. GitHub will publish the site at: https://YOUR-GITHUB-USERNAME.github.io/pixelforge/
   Replace YOUR-GITHUB-USERNAME with your actual GitHub username.

SEARCH ENGINE DISCOVERY (AFTER THE WEBSITE IS PUBLIC)
1. Open Google Search Console: https://search.google.com/search-console/
2. Add the exact published URL as a URL-prefix property and complete ownership verification.
3. Replace YOUR-GITHUB-USERNAME in sitemap-template.xml with your GitHub username.
4. Rename sitemap-template.xml to sitemap.xml and upload it to the repository root.
5. Submit https://YOUR-GITHUB-USERNAME.github.io/pixelforge/sitemap.xml in Search Console.
6. Use URL Inspection to test the home page and request indexing.

IMPORTANT
- Publishing makes the site publicly accessible. Do not upload private information or secrets.
- A public URL does not guarantee instant Google results. Google may take days or weeks to crawl/index a new site, and indexing is not guaranteed.
- The app processes images locally in each visitor's browser; there is no image upload server.
- GitHub Pages setup requires signing into your own GitHub account. This package does not publish itself.

Developer: Ivan Productions
Project: PixelForge
