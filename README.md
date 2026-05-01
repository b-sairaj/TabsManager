# Tabs Manager - Support Website

A standalone static website (separate from the extension codebase) used for Chrome Web Store listing links.

## Pages

| File | Purpose |
|---|---|
| `index.html` | "How to Use" guide — full feature walkthrough, loads by default |
| `support.html` | Support page — linked as the Web Store **Support URL** |
| `privacy-policy.html` | Privacy policy — linked as the Web Store **Privacy Policy URL** |

## Styles

All CSS lives in `styles.css` — no inline styles in any HTML file.

- **Shared styles** (top of file): body, `.page`, `.hero` (scoped to `.page .hero`), `.nav`, `.panel`, `.note`, footer, etc.
- **Index-page styles** (bottom of file, under the `Index page — How to Use` comment): hero, TOC, section cards, mockups, steps, features, tip boxes, tables, and responsive overrides.

## Navigation

Every page includes a nav bar inside the hero with links to all three pages:

- How to Use → `index.html`
- Support → `support.html`
- Privacy Policy → `privacy-policy.html`

## Assets

| File | Description |
|---|---|
| `assets/favicon.svg` | Site favicon used on all pages |

## Publish Options

- GitHub Pages
- Netlify
- Vercel
- Any static web host

The root `index.html` loads by default on all platforms.

## Recommended Web Store URLs

- **Support URL:** `https://<your-domain>/support.html`
- **Privacy Policy URL:** `https://<your-domain>/privacy-policy.html`
