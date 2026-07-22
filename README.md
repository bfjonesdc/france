# France Wildfire Monitor

A single-page interactive map of wildfire burnt areas in France, powered by
[EFFIS / Copernicus EMS](https://forest-fire.emergency.copernicus.eu/) WMS
layers on a Leaflet dark basemap (CARTO / OpenStreetMap).

Features:

- Live current fire season plus archived seasons back to 2016
- Adjustable overlay opacity
- Click any burnt area for fire details (ID, area, commune, dates) via WMS GetFeatureInfo

## Deploying on Vercel

This is a static site — `index.html` at the repo root, no build step.

1. Go to [vercel.com/new](https://vercel.com/new) and import this repository.
2. Leave **Framework Preset** as **Other**; no build command or output directory needed.
3. Deploy.

## Local preview

Any static server works, e.g.:

```sh
npx serve .
```
