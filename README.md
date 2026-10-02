# 90 Days to Become an AI Engineer – learning site

Single-file website (`index.html`). No build step, no server code.

## Run locally
Double-click `index.html`, or run `python -m http.server` in this folder and open http://localhost:8000.

## Deploy
- **Vercel / Netlify:** drag this folder into the dashboard (or `vercel` from this folder).
- **GitHub Pages:** push to a repo, Settings → Pages → deploy from the main branch.

## How students use it
Each student opens the site, enters their name and start date, and locks it. Weeks, ship dates and the 92-day tracker count from that date.
Progress is saved in the student's own browser (localStorage). The "progress code" section moves it to another device.

Based on "90 Days to Become an AI Engineer: The Oct → Dec Roadmap" by Sakshi Jaiswal (AI in Plain English).
