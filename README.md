# EmailAIguy Website

Simple landing page for [@EmailAIguy](https://x.com/EmailAIguy) — copy a prompt to install [Email Swipe](https://github.com/EmailGuy42069/email-swipe), plus thesis + consultation CTA.

## Local preview

```bash
python3 -m http.server 8080
```

Open http://localhost:8080

## Deploy (Render)

Connected repo: **BlakeMcGinn12/emailaiguy-website**

- **Service:** `emailaiguy-website` (static site)
- **Publish directory:** `.` (repo root)
- **Build command:** `echo "Static site — no build"` (or leave blank)
- **Live URLs:** https://emailaiguy.com · https://www.emailaiguy.com · https://emailaiguy-website.onrender.com

`render.yaml` in this repo documents the Render config. Pushes to `main` auto-deploy when connected in the Render dashboard.

### Manual deploy trigger

Render Dashboard → **emailaiguy-website** → **Manual Deploy** → Deploy latest commit.

## Structure

```
emailaiguy-website/
├── index.html
├── styles.css
└── assets/
    ├── header.png   # Twitter banner
    └── profile.png  # Twitter profile photo
```
