# Free Fares, Full Platforms?

This is a FIT2179 Data Visualisation 2 working site about recent Victorian public transport demand and network pressure in the context of the 2026 fare-free period.

## Local Preview

Run a static server from this folder and open the local URL:

```bash
python -m http.server 8017
```

## Data

The visualisation uses derived CSV/GeoJSON files in `data/`, created from official Victorian Government datasets:

- Monthly average patronage by day type and by mode.
- Annual metropolitan train station patronage, FY2024-25.
- Transport Victoria's 2026 free public transport announcement is used as policy context.

The latest public monthly patronage file used here reaches January 2026, so the March-May 2026 free-fare period is described as context rather than measured as final open-data patronage.

## Vega-Lite Specs

Readable Vega-Lite descriptions for the ten charts are collected in:

```text
specs/charts.json
```
