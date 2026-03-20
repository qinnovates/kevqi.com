# kevqi.com — Portfolio Site

## Repository
- **Repo:** `github.com/qinnovates/kevqi.com` (public)
- **Site:** `kevqi.com` (GitHub Pages)
- **Working directory:** `/Users/mac/Documents/PROJECTS/kevqi.com/`

## Architecture
Static HTML/CSS. No framework. No build step. No dependencies.

```
kevqi.com/
├── index.html          # Single page, all content
├── css/
│   └── style.css       # All styles, CSS custom properties
├── assets/
│   ├── video/          # Demo videos (future)
│   └── img/            # Images (future)
├── _headers            # Security headers (Cloudflare Pages compatible)
├── CNAME               # Custom domain config
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Pages deployment
```

## Design
- Dark theme: deep space (#060810)
- Glass materials: rgba white with backdrop blur
- Colors: cyan (#00E5FF), purple (#8B5CF6), orange (#F59E0B)
- Fonts: Inter (body), JetBrains Mono (code/data)
- Star field: JS-generated, CSS animated

## Rules
- No frameworks. No npm. No build step. Pure HTML/CSS/JS.
- Security headers on every response
- No tracking, no analytics, no cookies
- Accessible: semantic HTML, proper contrast, keyboard navigable
- Mobile responsive (600px breakpoint)
- Keep it simple. This is a portfolio, not a web app.

## Deploy
Push to main → GitHub Actions deploys automatically.
