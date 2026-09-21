# Raúl Ducret — Portfolio

Static site, no build step. 6 pages, 1 shared stylesheet.

- `index.html` — Home
- `about.html` — About
- `case-direct-response.html` — AI-Assisted Direct Response (Touchbase)
- `case-design-system.html` — AI-Ready Design Systems (Mood)
- `case-quick-add.html` — Quick Add Modal Redesign
- `case-quiz.html` — Quiz UX Improvements (Happy Mammoth)
- `styles.css` — shared design tokens, layout, and responsive rules

## Push to GitHub

```bash
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```

## Deploy on Vercel

1. vercel.com → New Project → Import the GitHub repo above.
2. Framework preset: **Other** (static site, no build command needed).
3. Deploy. Every future `git push` redeploys automatically.
