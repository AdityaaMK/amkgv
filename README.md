# AMK Global Ventures

Minimal one-page landing site for `amkgv.com`.

## Stack

- Static `index.html`
- React 18 via CDN
- Tailwind CSS via CDN

## Local preview

Open `index.html` directly in a browser, or serve the folder with a simple static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages deployment

This repo includes a GitHub Actions workflow that deploys the site to GitHub Pages.

### Required repository settings

1. In GitHub, open `Settings` -> `Pages`.
2. Set `Source` to `GitHub Actions`.
3. If you want the custom domain, keep the included `CNAME` file as `amkgv.com`.

### DNS for `amkgv.com`

Point your domain to GitHub Pages using your DNS provider:

- `A` records for apex domain:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- `CNAME` record for `www`:
  - `AdityaaMK.github.io`

After DNS propagates, enable the custom domain in the repository Pages settings if GitHub prompts for it.
