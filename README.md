# dotRead — website

Marketing + support landing page for **dotRead**, a native macOS Markdown reader.
Static single-page site, hosted with **GitHub Pages**.

- `index.html` — the whole site (inline CSS, no build step)
- `assets/` — app icon + screenshots

## Publish with GitHub Pages

1. Create a new GitHub repo (e.g. `dotread-site`), push this folder to `main`.
2. Repo **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** / **/(root)** → Save.
3. The site goes live at `https://<user>.github.io/dotread-site/` within a minute.

Use that URL for the App Store Connect **Support URL**, **Marketing URL**, and
**Privacy Policy URL**.

## Before launch — fill these placeholders in `index.html`

- `id="appstore"` link → your Mac App Store URL (`https://apps.apple.com/app/idXXXXXXXXX`)
- The support **email** (or remove the line and keep GitHub Issues only)
- The **source repo** links if you rename the code repo
- Swap the text App Store button for Apple's official badge once live
  (see Apple's marketing/identity guidelines)
