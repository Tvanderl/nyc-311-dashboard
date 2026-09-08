# Publish the NYC 311 dashboard for school

This folder contains a neutral, standalone static website. `index.html` is the file a static host should serve.

## Recommended: temporary HTTPS link

1. On the laptop, open [Netlify Drop](https://app.netlify.com/drop).
2. Drag this **school-demo** folder onto the page.
3. Netlify provides a public `https://...netlify.app` link.
4. Open that link once on your phone using mobile data and once on the school network before the presentation.

No local server needs to run after publishing. The page has no ChatGPT, Codex or local-file wording.

## Data behaviour

The dashboard runs entirely in the browser and reads its aggregates and source records from the official NYC Open Data API over HTTPS. This keeps the dashboard current.

The school network must allow access to `https://data.cityofnewyork.us`. If it blocks that official domain, the public website opens but live figures cannot load. Test this in advance. For a fully offline contingency, use a prepared Excel/Access snapshot in the final Power BI version.

## Alternative: GitHub Pages

Create a repository, upload the contents of this folder to the repository root, enable GitHub Pages in the repository settings, and use the generated HTTPS link.
