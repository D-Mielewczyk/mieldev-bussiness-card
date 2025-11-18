# mieldev-bussiness-card

[![Netlify Status](https://api.netlify.com/api/v1/badges/716b5c24-470c-4f6b-ae3b-4ef27c553081/deploy-status)](https://app.netlify.com/projects/mieldev/deploys)

A minimal static website acting as a business card for my single-person data engineering business.

## Tech stack

- HTML + Tailwind CSS (via CDN)
- Vanilla JavaScript (smooth scrolling, email copy-to-clipboard)
- No build step, no backend

## Project structure

- `index.html` - main page layout and content
- Inline `<script>` - small profile config (name, email, phone) and UI behaviour
- `netlify.toml` - Netlify configuration for static deployment

You can update contact details and titles in the `profile` object at the bottom of `index.html`.

## Running locally

Just open `index.html` in your browser, or serve the directory with any static server, for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

The site is a plain static bundle and can be deployed to any static hosting such as Netlify, GitHub Pages, Vercel or an S3 static website.

This repository is currently deployed via **Netlify** at:

- [https://mieldev.netlify.app](https://mieldev.netlify.app)
- [https://mieldev.com](https://mieldev.com)
