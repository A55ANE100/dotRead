# dotRead — website

Marketing + support landing page for **dotRead**, a native macOS Markdown reader.
Static single-page site, hosted with **GitHub Pages**.

## ⚠️ Which repo is which

| Repo | Purpose |
|------|---------|
| **[A55ANE100/dotRead](https://github.com/A55ANE100/dotRead)** | **This repo** — the **website only** (source for the App Store Support / Marketing / Privacy URLs). |
| **[A55ANE100/Markview](https://github.com/A55ANE100/Markview)** | The **app's source code** (the SwiftUI app, MarkdownKit, Quick Look extensions). |

## Contents

- `index.html` — the whole site (inline CSS + a tiny scroll-reveal script, no build step)
- `assets/` — app icon + screenshots

## Publish with GitHub Pages

1. Push this folder to `main` (this repo).
2. Repo **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** / **/(root)** → Save.
3. Live within a minute at **`https://a55ane100.github.io/dotRead/`**.

Use that URL for the App Store Connect **Support URL**, **Marketing URL**, and
**Privacy Policy URL** (the page's Privacy section satisfies all three).

## Before launch — fill these placeholders in `index.html`

- `id="appstore"` link → your Mac App Store URL (`https://apps.apple.com/app/idXXXXXXXXX`)
- Swap the text App Store button for Apple's official badge once live
  (see Apple's marketing/identity guidelines)

## Design notes

Restrained, accessible craft: SVG icons (no emoji), 200–300ms transitions, a
scroll-reveal that's **disabled under `prefers-reduced-motion`**, visible
`:focus-visible` states, and a single brand accent matched to the app icon.
