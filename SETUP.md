# 🗺️ Trip Site — Setup Guide

## Your file structure
```
your-repo/
├── index.html              ← Homepage (all trips)
└── thousand-islands/
    └── index.html          ← Thousand Islands trip page
```

## Step 1 — Create a GitHub account
Go to https://github.com and sign up (free).

## Step 2 — Create a new repository
1. Click the **+** icon → "New repository"
2. Name it `trips` (or `adventures`, `crew-trips`, etc.)
3. Set it to **Public** (required for free GitHub Pages)
4. Click **Create repository**

## Step 3 — Upload your files
**Option A — Browser (easiest):**
1. Click "uploading an existing file" on your new repo page
2. Drag both files: `index.html` and `thousand-islands/index.html`
3. Commit the files

**Option B — GitHub Desktop app:**
1. Download GitHub Desktop at https://desktop.github.com
2. Clone your repo, copy the files in, commit & push

## Step 4 — Enable GitHub Pages
1. Go to repo **Settings** → **Pages** (left sidebar)
2. Under "Branch", select `main` → `/ (root)` → **Save**
3. Wait ~2 minutes
4. Your site is live at: `https://yourusername.github.io/trips/`

## Step 5 — Share with friends for planning
For friends to add notes/edits:
- **Easy:** Share the GitHub repo link → they can edit files directly in the browser
- **Easier for non-tech friends:** Copy the itinerary to a Notion page, then you paste changes back

## Step 6 — Add Giscus comments (after the trip)
1. Go to https://giscus.app
2. Enter your GitHub repo name
3. Enable GitHub Discussions in your repo (Settings → Features → Discussions ✓)
4. Copy the `<script>` snippet from giscus.app
5. Paste it into the comments section of the published view

## Updating the trip page after the trip
1. Write your recap in the `<!-- Published view -->` section of `thousand-islands/index.html`
2. Add photo links (upload photos to Google Photos → get share link, or use Imgur)
3. Commit & push → site updates automatically in ~1 minute

## Your live URLs will be:
- Homepage: `https://yourusername.github.io/trips/`
- Thousand Islands: `https://yourusername.github.io/trips/thousand-islands/`

---
*Want a custom domain like `ourtrips.netlify.app`? Sign up at netlify.com (free), drag your folder in, and you get a nicer URL instantly.*
