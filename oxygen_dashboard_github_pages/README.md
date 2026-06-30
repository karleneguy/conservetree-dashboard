# Making Oxygen Therapy Visible Dashboard

This repository is ready for GitHub Pages.

## Files

- `index.html` — the published dashboard page. GitHub Pages uses this as the entry file.
- `.nojekyll` — tells GitHub Pages to serve this as plain static files.
- `province_territory_metrics.csv` — demo source data.
- `monthly_monitoring.csv` — demo source data.
- `visible_site_status.csv` — demo source data.
- `making_oxygen_therapy_visible_dashboard.png` — static dashboard preview image.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `oxygen-dashboard`.
2. Upload all files in this folder to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then save.
6. Your dashboard will be published at:
   `https://YOUR-USERNAME.github.io/oxygen-dashboard/`

## Embed in Squarespace

Replace the URL below with your published GitHub Pages URL:

```html
<div style="width:100%; max-width:1680px; margin:0 auto;">
  <iframe
    id="oxygen-therapy-dashboard"
    src="https://YOUR-USERNAME.github.io/oxygen-dashboard/"
    title="Making Oxygen Therapy Visible Program Dashboard"
    loading="lazy"
    style="width:100%; height:980px; border:0; border-radius:14px; overflow:hidden; display:block;"
  ></iframe>
</div>
```
