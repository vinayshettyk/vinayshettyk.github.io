YadhviIT Services — website
===========================

TO PUBLISH
Upload every file in this folder to your host, keeping them in the same
directory. index.html expects the images to sit alongside it.

Easiest options (all free, HTTPS included):
  - Cloudflare Pages or Netlify: drag this folder onto their dashboard.
  - GitHub Pages: commit the folder, enable Pages in repo settings.
Then point yadhviit.com at the host with the DNS record they give you.

FILES
  index.html              The site. Self-contained apart from the images.
  favicon.png             Browser tab icon.
  logo-mark.png           The swoosh on its own. Used as the hero graphic.
  logo-lockup-light.png   Compact horizontal logo, for DARK backgrounds.
                          Used in the header and footer.
  logo-lockup.png         Same lockup, for LIGHT backgrounds.
  logo-full.png           Your original logo, unmodified.
  logo-light.png          Your original logo recoloured for dark backgrounds.

NOTE ON THE LOGO
All images here are derived from the 878x456 PNG supplied. That is fine at
current sizes, but if you have the original vector file (.ai, .eps or .svg),
use it instead — it will stay sharp on any screen and at any size.

EDITING COPY
All text is in index.html. Search for the sentence you want to change.
The four process stages under "How we work" were drafted, not supplied —
check they match how you actually run an engagement.


SEO — WHAT IS SET UP
  - Title tag, meta description, canonical URL
  - Open Graph + Twitter card tags (og-image.jpg, 1200x630)
  - Organization structured data (JSON-LD) with services, people, contacts
  - robots.txt and sitemap.xml
  - One H1, section H2s, alt text on all images, mobile-responsive

BEFORE YOU PUBLISH — CHANGE THESE
  1. Every SEO URL is hardcoded to https://yadhviit.com/ — in index.html
     (canonical, og:url, og:image, JSON-LD), robots.txt and sitemap.xml.
     If you use www.yadhviit.com instead, find-and-replace all of them.
     Pick one and redirect the other, or you split your ranking.
  2. sitemap.xml <lastmod> is 2026-09-11. Update when you change the page.
  3. No city is set anywhere. See below.

AFTER YOU PUBLISH
  1. Google Search Console — verify the domain, submit sitemap.xml.
  2. Google Business Profile — create one with your real address. For an
     Indian IT firm this drives more enquiries than anything on this page.
  3. Bing Webmaster Tools — same, takes five minutes.
  4. Get your LinkedIn company page live and link it from the site; then
     add its URL to the "sameAs" field in the JSON-LD block.
