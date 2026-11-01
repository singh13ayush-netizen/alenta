# Alenta Lifesciences — website

Upload the CONTENTS of this folder to your web root (public_html / dist / site root).

- index.html           the page (minified)
- assets/              images (WebP) and the hero video (original MP4, untouched)
- favicon.png, apple-touch-icon.png
- robots.txt, sitemap.xml
- .htaccess            Apache hosting: compression, caching, security headers
- _headers             Netlify / Cloudflare Pages: same caching and headers

Before launch
1. The domain is set to alenta.in; if it ever changes, replace it in index.html (og:image, JSON-LD),
   robots.txt and sitemap.xml.
2. Serve over HTTPS.
3. Keep the folder structure as is: index.html must sit next to the assets/ folder.

Do not open index.html by double-clicking to test the video in every browser;
use any local server (e.g. `python3 -m http.server`) or the live host.
