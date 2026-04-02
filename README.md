# Quipu API v1 Documentation

API reference documentation for the Quipu API v1, rendered with [Scalar](https://scalar.com).

## How it works

- `openapi.yaml` — the OpenAPI 3.1 specification
- `index.html` — single-page app that renders the spec using Scalar
- Deployed automatically to GitHub Pages on push to `main`

## Local development

Just open `index.html` in a browser, or serve it locally:

```bash
npx serve .
```

## Updating the documentation

Edit `openapi.yaml` and push to `main`. The docs will be deployed automatically.

## Future improvements

- Auto-generate `openapi.yaml` from request specs using `rspec-openapi`
- Add `starlight-openapi` plugin if migrating to Astro/Starlight
