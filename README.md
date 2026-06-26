# Apoorve Goyal — HackerRank Farewell Site

A personal farewell page. Static HTML, zero dependencies, GitHub Pages ready.

## Add Photos

Drop your photos into the `photos/` folder with the exact filenames listed in `photos/README.md`. The site gracefully shows a placeholder until the image exists.

## Deploy to GitHub Pages

```bash
# 1. Create a new GitHub repo (e.g. "farewell-hackerrank") at github.com/new
#    Make it public for free GitHub Pages hosting.

# 2. Initialize and push from this folder
cd farewell-site
git init
git add .
git commit -m "farewell site"
git branch -M main
git remote add origin https://github.com/apoorve73/farewell-hackerrank.git
git push -u origin main

# 3. Enable GitHub Pages
#    GitHub repo → Settings → Pages → Source: Deploy from branch → main / (root)
#    Your site will be live at: https://apoorve73.github.io/farewell-hackerrank/
```

## Or use Vercel (even simpler — one click)

1. Go to [vercel.com](https://vercel.com) → "Add New Project"
2. Import the GitHub repo → Deploy
3. Your site gets a `vercel.app` URL instantly, with a free custom domain option

## File Structure

```
farewell-site/
├── index.html       ← The entire site (one file)
├── photos/          ← Drop your photos here
│   └── README.md    ← Photo filenames guide
├── .nojekyll        ← Tells GitHub Pages to skip Jekyll processing
└── README.md        ← This file
```
