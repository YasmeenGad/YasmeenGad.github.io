# Yasmeen Gad · Flutter Developer Portfolio

Live: https://yasmeengad.github.io

A static, dependency-free portfolio (HTML, CSS and vanilla JS) hosted on GitHub Pages.

## Structure
- `index.html`: the whole site. Project data (`PROJECTS`), skills, experience and contact settings live in the `<script>` block.
- `assets/img/`: optimized WebP screenshots, all taken from the real apps.
- `assets/og.jpg`: social sharing image.
- `404.html`, `robots.txt`, `sitemap.xml`, `favicon.svg`.

## Configuration
- **Contact form:** set `web3formsKey` in the `CONTACT` object in `index.html` to a free [Web3Forms](https://web3forms.com) access key to deliver messages to your inbox. The key is designed to be public. Without a key, the form opens the visitor's email app with the message pre-filled.
- **CV download:** add `Yasmeen-Gad-CV.pdf` to the repository root (already set via `cv` in the `CONTACT` object). Replace the file to update the CV.

## Run locally
```
python -m http.server 8000
```
Then open http://localhost:8000.
