URLPluck — COMPLETE SEO TUTORIAL PACKAGE | November 13, 2026

INCLUDED PAGES
index.html — existing homepage, PageSpeed fixes preserved; updated 3-guide cards
how-to-extract-links-from-webpage.html — 5-step extraction walkthrough
how-to-export-webpage-links-to-csv.html — CSV, Excel and Google Sheets workflow
how-to-copy-all-links-in-chrome.html — bulk copy, filters, duplicates, collections

SHARED FILES
assets/ — original optimized screenshots and favicon, referenced by the HTML
robots.txt — allows crawlers and points to sitemap
sitemap.xml — all 4 URLs (homepage and 3 tutorial pages)

DEPLOY TO CLOUDFLARE WORKERS STATIC ASSETS
1. Extract the ZIP and deploy ALL files and folders together, preserving the root structure.
2. index.html must be at the website root; not inside another folder.
3. Preserve assets/ and its images. Pages use absolute /assets/... image paths.
4. Confirm the exact pages load as HTML (not a 404 or SPA fallback) and screenshots display:
   https://urlpluck.zelvori-studio.workers.dev/
   https://urlpluck.zelvori-studio.workers.dev/how-to-extract-links-from-webpage.html
   https://urlpluck.zelvori-studio.workers.dev/how-to-export-webpage-links-to-csv.html
   https://urlpluck.zelvori-studio.workers.dev/how-to-copy-all-links-in-chrome.html
   https://urlpluck.zelvori-studio.workers.dev/sitemap.xml
5. Each guide has unique title/description, canonical and Article structured data.
6. Inspect the 3 new/updated guide URLs in Search Console, use Test Live URL and request indexing once per URL.
7. If sitemap status says Couldn't fetch, recheck Google's live fetch and monitor; repeated resubmissions are not a substitute for troubleshooting.

IMPORTANT
- URLPluck extracts hyperlinks from the open webpage; it is NOT a whole-domain crawler.
- CSV opens in Excel/Sheets; URLPluck does NOT create native XLSX workbooks.
- The supplied HTML files are static. Do not modify the canonical domain without updating all internal absolute URLs.
- Lighthouse 100 scores from earlier builds are not a guarantee for this new build; retest after deployment.
- Google rankings or indexing cannot be guaranteed; these are user-focused topical pages.
- If you already host privacy/legal files outside this ZIP, do not delete them when deploying.
