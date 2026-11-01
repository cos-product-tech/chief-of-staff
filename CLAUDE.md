
## Standing rule: pages must not be indexable
Every HTML page, site or artifact built for Eric must include, right after `<head>`:
`<meta name="robots" content="noindex, nofollow, noarchive">`
Keep `robots.txt` (Disallow: /) and the `X-Robots-Tag` / `Referrer-Policy` headers in `vercel.json`. Never add a sitemap or public links to these pages.
