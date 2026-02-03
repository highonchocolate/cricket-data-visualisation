# ICC T20 World Cup 2024 Data Visualisation (R)

A data visualisation / analytics project built in **R** using ball-by-ball and match-level IPL data.

Highlights:
- Feature engineering and KPI aggregation (runs, wickets, dot balls, extras, boundaries)
- PCA on team performance KPIs
- Visual analysis with ggplot2
- Chord diagram exploration of team matchups

## Dashboard screenshots

These are screenshots of the final Tableau dashboard/views.

<img src="docs/screenshots/final/dashboard_01.png" width="900" />
<img src="docs/screenshots/final/dashboard_02.png" width="900" />
<img src="docs/screenshots/final/dashboard_03.png" width="900" />
<img src="docs/screenshots/final/dashboard_04.png" width="900" />
<img src="docs/screenshots/final/dashboard_05.png" width="900" />

## Design process (Sheets 1–5)

These pages show the design sheet process used to decide layout and visual choices.

<img src="docs/screenshots/design/design_sheet_01.png" width="900" />
<img src="docs/screenshots/design/design_sheet_02.png" width="900" />
<img src="docs/screenshots/design/design_sheet_03.png" width="900" />
<img src="docs/screenshots/design/design_sheet_04.png" width="900" />
<img src="docs/screenshots/design/design_sheet_05.png" width="900" />

## How to run

```bash
# from repo root
R -q -e "rmarkdown::render('report/DVP_static_viz.Rmd', output_file='index.html', output_dir='docs')"
```

The rendered HTML will be at: `docs/index.html`

## Repo structure
- `report/` – RMarkdown analysis
- `data/` – datasets used (CSV)
- `docs/` – rendered HTML output
- `docs/screenshots/` – screenshots for GitHub README
- `outputs/` – precomputed intermediate .rds files

## License
MIT
