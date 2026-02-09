# Max — Music Website (GitHub Pages)

A modern, minimal **music artist** website built as a simple static site (no build tools).  
It uses your photo and is ready to deploy on **GitHub Pages**.

## Files
- `index.html`
- `styles.css`
- `script.js`
- `assets/max.jpg`
- `assets/favicon.svg`

## Customize (most important)
Open `index.html` and replace:
- Platform links (Spotify / Apple Music / YouTube / etc.)
- “Your Track Name”, dates, venues
- Contact email: `you@example.com`

## Run locally
```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Deploy on GitHub Pages
1. Create a new repo (example: `max-music`)
2. Upload these files to the repo root
3. Settings → Pages → Deploy from branch → `main` → `/ (root)` → Save

## Optional
There’s a small “Side project” disclosure for your Cardano pool (MAXC).  
If you don’t want it, delete that `<details>` block in the Contact section.
