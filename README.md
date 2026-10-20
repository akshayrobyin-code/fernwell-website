# Fernwell – demo plant shop

A static, single-page ecommerce demo (HTML, CSS, JavaScript). No build step.

## Structure
- `public/index.html` – the whole site
- `wrangler.jsonc` – tells Cloudflare to serve the `public` folder

## Deploy on Cloudflare (Git connection)
- Build command: leave empty
- Deploy command: `npx wrangler deploy`
- The `name` in `wrangler.jsonc` must match your Cloudflare project name.
