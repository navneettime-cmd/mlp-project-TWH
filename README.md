# The Whole Truth: Clean Protein Bars landing page

Single-page static landing page for Google Ads traffic (keyword: "clean protein bars India").
Everything is in `index.html`: CSS and the small sticky-bar script are inline, and the logo, favicon,
hero photo, celebrity photos, press logos and social icons are embedded in the file.
No build step, no dependencies.

## Files
- `index.html`: the whole page
- `README.md`: this file

## Preview locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Deploy on Vercel
1. Create a new GitHub repository and upload both files to its root.
2. In Vercel: Add New → Project → import the repository.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty. Root Directory: `./`.
4. Click Deploy. Every later push to the main branch redeploys automatically.

## After deploying
- Run Google PageSpeed Insights (mobile) on the live URL. Target: 70+.
- Hard-refresh on phone and desktop to make sure you are not seeing a cached older version.
