# Deploy instructions

This site is static. Deploy the project root as-is — no `npm install` or build command.

## What to upload

- `index.html`
- `styles.css`
- `public/` (all files and subfolders)

Do not omit `public/`; image paths in the HTML point there.

## Cloudflare Pages

1. Create a new Pages project from this repository (or upload the folder).
2. Build settings:
   - Build command: leave empty
   - Output directory: `/` (project root)
3. Deploy.

## Other hosts

Same idea: publish the folder contents as the website root. No Node runtime required.
