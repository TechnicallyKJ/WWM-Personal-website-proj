# Where Winds Meet — Fan Landing Page

A cinematic, wuxia-styled game landing page inspired by *Where Winds Meet* by NetEase Games / Everstone Studio.

Built with pure HTML, CSS, and Three.js (no build tools required).

## 🚀 Deploy to GitHub Pages

### Option A — GitHub Web UI (easiest)

1. Create a new repository on [github.com](https://github.com/new)
2. Name it anything — e.g. `where-winds-meet`
3. Upload `index.html` via **Add file → Upload files**
4. Go to **Settings → Pages**
5. Under **Source**, select `main` branch and `/ (root)` folder
6. Click **Save** — your site will be live at:
   `https://YOUR-USERNAME.github.io/where-winds-meet/`

### Option B — Git CLI

```bash
# 1. Clone or init your repo
git init
git remote add origin https://github.com/YOUR-USERNAME/where-winds-meet.git

# 2. Add the file
cp index.html .
git add index.html README.md
git commit -m "Initial commit — Where Winds Meet landing page"

# 3. Push
git branch -M main
git push -u origin main

# 4. Enable GitHub Pages in repo Settings → Pages → Source: main / root
```

Your site will go live within ~60 seconds at:
`https://YOUR-USERNAME.github.io/where-winds-meet/`

## 📁 File Structure

```
index.html   ← Everything is self-contained in this one file
README.md    ← This file
```

All fonts load from Google Fonts CDN.  
Three.js loads from cdnjs CDN.  
No npm, no build step, no dependencies to install.

## ✨ Features

- Cinematic 3D scroll animation (Three.js) — layered mountains, floating sword, petals, particles
- Wuxia ink-wash aesthetic with gold accents
- Fully responsive (mobile + desktop)
- Animated hero with mountain silhouettes
- Sections: Story, Features, Combat, World Regions, Reviews, Pre-Register CTA
- Smooth scroll-reveal animations throughout

## 📝 Customisation Tips

| What to change | Where in `index.html` |
|---|---|
| Game title / copy | Search for the visible text strings |
| Gold colour | Change `--gold: #c8913a` in `:root` |
| Hero subtitle | Find `.hero-subtitle` paragraph |
| Stats (80M+ players etc.) | Find `intro-stat` divs |
| Email form action | Add `action=""` to `.email-form` or wire up a service like Formspree |
| Add a video background | Replace the hero SVG mountains with a `<video>` element |

## ⚖️ Disclaimer

This is a fan-made concept page. All game IP belongs to NetEase Games / Everstone Studio.
