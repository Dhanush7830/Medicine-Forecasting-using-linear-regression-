# Medicine Demand Forecasting

Static dashboard comparing linear regression and random forest forecasts for medicines in chiller and dry storage. Sample data, illustrative figures.

## Files
- `index.html` the whole dashboard (HTML + CSS, no build step)
- `images/` chart PNGs the page expects, each as `<name>-light.png` and `<name>-dark.png`

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

## Publish on GitHub Pages
1. Create a repo and push these files to `main`.
2. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)`.
3. Your site appears at `https://<username>.github.io/<repo>/` after about a minute.

## Charts
If a PNG is missing the page shows a labelled placeholder instead of a broken image. Export the charts from your Python notebook with the filenames listed in `index.html` (`src="images/..."`).
