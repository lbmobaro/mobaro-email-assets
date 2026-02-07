# mobaro-email-assets

This repo holds public, CDN-served assets for Mobaro emails (product updates, newsletters, etc.).

## Recommended workflow
1. Add new images under `emails/product-updates/YYYY-MM/`
2. Create a GitHub Release tag like `email-YYYY-MM`
3. Use jsDelivr URLs pinned to that tag in your email HTML

## jsDelivr URL format
https://cdn.jsdelivr.net/gh/<OWNER>/<REPO>@<TAG>/<PATH>

Example:
https://cdn.jsdelivr.net/gh/mobaro/mobaro-email-assets@email-2026-02/emails/product-updates/2026-02/header.png
