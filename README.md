# NYC Racing Calendar static web app

This package contains the calendar as a static web app. The visual design and interaction are unchanged from the review version.

Files:
- `index.html` — the page to publish.
- `nyc_running_race_calendar_data.json` — editable race data. Update this file when race details change.
- `nyc_running_race_calendar.html` — same as `index.html`, included for reference.

Recommended hosting:
1. Create a free Cloudflare Pages, Netlify, Vercel, or GitHub Pages project.
2. Upload/deploy the contents of this folder.
3. The calendar will be available at the provided URL.
4. To update races later, replace `nyc_running_race_calendar_data.json` and redeploy.

Substack usage:
- Add a navigation link or post link to the hosted calendar URL.
- Do not paste the HTML directly into Substack if you want filters/search/month navigation to keep working.
