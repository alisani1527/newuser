# Elyth Wear — Cloudflare-ready

This package preserves the original Stitch project and adds the minimal Cloudflare Workers static-assets configuration.

## Deploy

Use the existing deploy command:

    npx wrangler deploy

Wrangler will serve `public/index.html` as the site root.

## Important

The original Stitch files are preserved under `original/` and were not rewritten or deleted.
The page itself is copied byte-for-byte from the original `code.html` to `public/index.html`.

The page currently references several externally hosted Google/AIDA image URLs, just as the original did. The local PNG files are preserved in `original/`.
