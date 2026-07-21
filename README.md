# GRAPEJS — JAYABINA Visual Editor

Standalone GrapesJS 0.23.2 visual HTML editor for JAYABINA.

## Deploy

Cloudflare Pages — auto-deploys from root directory on push to `master`.

- **Custom domain:** `grapejs.jayabina.com`
- **Password:** `jaya2026`
- **Config:** `config.json`

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main editor (GrapesJS 0.23.2, 17 plugins) |
| `vendor/` | Bundled JS/CSS assets |
| `config.json` | Sites registry for cloud editor mode |
| `test.html` | Test page |
| `favicon.svg` | "J" icon |

## Build

```bash
npm run build:grapes-editor
```

Outputs `vendor/grapes-editor.bundle.js` (esbuild IIFE bundle, ~1.4MB).
