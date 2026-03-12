# Stock Brief Pages

This repo hosts the mobile stock brief for GitHub Pages.

## URL
After GitHub Pages is enabled, open:

https://yunzheli.github.io/stock-brief-pages/latest-mobile.html

## Update workflow
From local workspace:

```bash
bash '/Users/yunzheli/Documents/Personal Life/scripts/publish_mobile_pages.sh'
```

This will:
1. Copy the latest `reports/stock-brief-mobile-*.html` to `latest-mobile.html` and `index.html`.
2. Commit changes.
3. Push to `main` (if `origin` is configured).
