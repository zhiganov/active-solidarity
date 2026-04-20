# site

Static landing page for active-solidarity.

## Preview

```bash
python -m http.server 8000 --directory site
# then open http://localhost:8000
```

No build step. One HTML file, one CSS file.

## Deploy

Hostable anywhere. For GitHub Pages: Settings → Pages → Source: deploy from branch `main`, folder `/site`. Saves to `https://zhiganov.github.io/active-solidarity/`.

## Design notes

Plaintext-in-terminal. System monospace, single weight, uniform size, black on white, no animation, no colour beyond inverted-on-hover links. Signals working material, not a product.
