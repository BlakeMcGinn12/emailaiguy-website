# EmailAIguy Website

Simple landing page for [@EmailAIguy](https://x.com/EmailAIguy) — copy a prompt to install [Email Swipe](https://github.com/EmailGuy42069/email-swipe), plus thesis + consultation CTA.

## Local preview

```bash
python3 -m http.server 8080
```

Open http://localhost:8080

## Deploy

Static site — deploy the repo root to any static host (Render static site, GitHub Pages, Cloudflare Pages, etc.). No build step.

- **Publish directory:** `/` (root)
- **Index:** `index.html`

## Structure

```
emailaiguy-website/
├── index.html
├── styles.css
└── assets/
    ├── header.png   # Twitter banner
    └── profile.png  # Twitter profile photo
```
