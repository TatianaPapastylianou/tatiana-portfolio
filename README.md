# Tatiana Papastylianou — Portfolio

Personal portfolio site for Tatiana Papastylianou, senior product designer based in Nicosia, Cyprus.

## Tech stack

HTML, CSS, JS. No framework, no build step.

## Local preview

Open `index.html` directly in a browser. No server required.

For an optional local server:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Deployed via Netlify. The repository is connected to Netlify with the following settings:

- Publish directory: `.`
- Build command: none

Security headers and caching are configured in `netlify.toml`.

## Before launch

Replace these placeholders in `index.html`:

1. **Form endpoint.** Either remove the `action` attribute on `#applyForm` to use Netlify Forms, or replace `YOUR_ID_HERE` in the Formspree URL.
2. **Favicon** at `/favicon.ico`.
3. **Open Graph image** at `/og-image.jpg`.
4. **LinkedIn URL** inside the JSON-LD `sameAs` array.
5. **Canonical URL and og:url** once the final Netlify subdomain is set. Also update `sitemap.xml` and `robots.txt`.

## Forms

The application form is wired for both Netlify Forms and Formspree. See the comment block above the form in `index.html` for details. Enable Netlify Forms in site settings to receive submissions without a third-party service.

## Files

- `index.html` — the single-page site.
- `robots.txt` — crawler directives.
- `sitemap.xml` — one-page sitemap.
- `netlify.toml` — Netlify publish and header configuration.
- `.gitignore` — standard ignores.
