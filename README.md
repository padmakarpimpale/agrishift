# AgriShift

Climate-aware crop rotation exploration for NASA Space Apps Challenge 2026.

## Run
Open `index.html` in a browser, or run `python -m http.server 8000` and visit http://localhost:8000.

## Deploy to Vercel
Import this repository into Vercel with framework preset **Other**, no build command, and output directory `.`.

## Data and limitations
The browser requests NASA POWER daily point data for `T2M`, `PRECTOTCORR`, and `RH2M`. Annual summaries and monthly rainfall are calculated from valid daily records. Crop rotation cards are educational examples, not scored or optimized agronomic recommendations. NASA POWER data are gridded estimates, not individual farm measurements.

## Next milestones
- Crop requirement dataset with citations and region-specific planting calendars
- Actual strategy scoring with explicit water and temperature constraints
- Map-based selection and soil data integration
- Accessibility, automated tests, API caching and retry handling
