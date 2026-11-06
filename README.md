# Zilin He — personal website

Primary address: https://zilinhe.com/

Static HTML and CSS, published with GitHub Pages from `main` at the repository root. No build step is required. Each project has its own HTML page, so direct links and refreshes work without hash routing.

## Update the website

Edit the relevant HTML file and commit to `main`. Keep project status and personal/AI contribution descriptions accurate. Update `sitemap.xml` when adding or removing pages. Keep `.nojekyll` and `CNAME` in the repository root.

## Custom domain

The primary domain is `zilinhe.com`; `www.zilinhe.com` is its redirecting alias. Cloudflare DNS must point the four apex A records to GitHub Pages and `www` to `summer114514-hub.github.io`, with DNS Only selected. Domain resolution and HTTPS are usable only after DNS and GitHub certificate provisioning complete.

Canonical URLs, Open Graph URLs, structured data, robots.txt and sitemap.xml use the primary domain. Preserve the CNAME file when updating the site. GitHub manages the HTTPS certificate once the DNS check passes.

## Current release

Updated from `zilinhe-site_1.zip` on November 6, 2026. The refreshed design includes a simulated price-path chart and a persistent light/dark theme control. Previously confirmed project contribution descriptions are retained. The existing custom domain and HTTPS configuration remain in use.
