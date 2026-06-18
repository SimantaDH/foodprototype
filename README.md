# Mapping Memory, Mapping Meals

An interactive ethnographic archive mapping tribal food knowledge across West Bengal, India — built as a single-page, dependency-free website.

🔗 **Live demo (after enabling Pages, see below):** `https://<your-username>.github.io/<repo-name>/`

## What's inside

- An animated SVG map of West Bengal with 7 clickable region nodes
- A 7-layer filter system (District/Ecology, Tribal Community, Ethnobotanical, Culinary Technology, Temporal Context, Cultural Memory, Archival Sources)
- A sticky detail panel with full layer-by-layer breakdowns per region
- A complete archive card grid, a folklore timeline, and a food-scarcity data section
- Custom cursor, scroll-reveal animations, all in pure HTML/CSS/JS

No build step, no framework, no npm install — just one HTML file.

## Run locally

Just open `index.html` in any browser. Or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Push this repo to GitHub (instructions below).
2. Go to your repo on GitHub → **Settings** → **Pages**.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`.
4. Set **Branch** to `main` (or `master`) and folder to `/ (root)`.
5. Click **Save**. GitHub will give you a live URL within a minute or two.

## Pushing this folder to GitHub

```bash
cd mapping-memory-meals
git init
git add .
git commit -m "Initial commit: Mapping Memory, Mapping Meals"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Credits

Data source: *Mapping Memory, Mapping Meals — Complete 7-Layer Archive (Including Web Sources)*, a tribal food ethnography dataset covering Toto, Oraon, Rajbanshi, Santal, Adivasi (multi-tribe), Kheria Sabar, and pan-West Bengal communities.
