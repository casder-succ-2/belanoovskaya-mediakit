# Mediakit — Даша Белановская

Static one-page mediakit (HTML + CSS + images). No build step, no framework.

## Structure

```
index.html    # page content
styles.css    # styles
public/       # images (hero, cases, stats screenshots, favicon)
```

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
npx --yes serve .
```

Then open the URL shown in the terminal (usually `http://localhost:3000`).

## Edit content

- Copy and links: edit `index.html`
- Look and layout: edit `styles.css`
- Photos and screenshots: replace files under `public/`

## Deploy

Upload the project root (`index.html`, `styles.css`, `public/`) to any static host:

- Cloudflare Pages
- GitHub Pages
- Netlify
- Any static file hosting

See [DEPLOY-INSTRUCTIONS.md](./DEPLOY-INSTRUCTIONS.md).
