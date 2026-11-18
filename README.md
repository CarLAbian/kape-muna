# Kape Muna

Kape Muna is a Shopify theme-development learning project: a warm, welcoming concept storefront for coffee, brewing gear, and café comforts.

## Storefront concept

- Homepage hero: **“A little café, wherever you brew.”**
- Coffee-pouring hero image with a **Shop all** call to action.
- Featured products section.
- Announcement bar describing the coffee and brewing range.
- Warm cream and coffee-brown colors, with Noto Serif headings and Assistant body text.

## What this project demonstrates

This is the owner's first mostly independent Shopify theme customization attempt, based on [Shopify Dawn](https://github.com/Shopify/dawn). The current project changes Dawn's theme-editor configuration and existing sections in:

- `config/settings_data.json`
- `sections/header-group.json`
- `templates/index.json`

These settings configure existing Dawn features. The current changes do not add a custom Liquid section, Shopify app, or external integration. The README describes the current local code, not features that might exist only in the Shopify Admin.

## Preview locally

Requirements: Node.js 22.12 or newer, Git 2.28.0 or newer, Shopify CLI, and access to a Shopify development store.

From this theme directory, run:

```powershell
shopify theme dev --store your-store.myshopify.com
```

Sign in in the browser if the CLI requests it. Open the local preview URL printed by the command (usually `http://127.0.0.1:9292`) in Google Chrome while the command remains running. The command creates a temporary development theme; it does not publish the theme.

## Project scope

This is a learning storefront, not client or production work. Product/catalog data and media configured in Shopify Admin may not be included in this repository. No app development, app integration, or headless storefront work is included.

Do not commit Shopify passwords, access tokens, `.env` files, or CLI login data. Dawn is distributed under the MIT License; see [`LICENSE.md`](LICENSE.md).
