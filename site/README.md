# site

Static landing page for active-solidarity.

## Preview locally

```bash
python -m http.server 8000 --directory site
# then open http://localhost:8000
```

Or any other static file server — there is no build step.

## Deploy

This is plain HTML + CSS, hostable anywhere. Easiest: GitHub Pages.

1. Repo **Settings → Pages**.
2. Source: deploy from branch `main`, folder `/site`.
3. Save. The page publishes at `https://zhiganov.github.io/active-solidarity/`.

## Design notes

- **Direction:** editorial manifesto — warm paper ground, oxide-red ink accent, Instrument Serif italic display against Fraunces body, IBM Plex Mono metadata.
- **Fonts** (Google Fonts): Instrument Serif, Fraunces, IBM Plex Mono.
- **No framework, no build, no JS** — the only asset is `styles.css`.
- **Accessibility:** honours `prefers-reduced-motion`; semantic landmarks; contrast checked against the paper ground.
