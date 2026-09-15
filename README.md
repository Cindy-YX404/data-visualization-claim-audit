# Data Visualization: Claim Critique and Alternative Design

A portfolio project that critiques and redesigns three published data visualizations across energy, economics, and public health.

## Project highlights

- Compared chart claims with what the underlying data directly supports.
- Designed alternatives using part-to-whole, distribution, and correlation views.
- Documented chart choices, rejected alternatives, and transformation decisions.
- Built reproducible evidence probes to classify claims as supported, unverified, unsupported, or contradicted.
- Used Python, pandas, NumPy, and Matplotlib in a reproducible Jupyter notebook.

## Case studies

1. **US electricity generation (2025)** — a horizontal bar chart makes source shares easier to compare on a common baseline.
2. **US income distribution (1980 vs 2020)** — grouped bars compare cumulative income shares at matched population shares.
3. **Health spending and life expectancy (2023)** — a median-based quadrant scatter plot reveals the overall association and notable exceptions.

## Repository structure

- `data_visualization_claim_audit.ipynb` — complete analysis, visualizations, decision records, and claim audits
- `data/` — supplied source datasets
- `original_chart_1.png` to `original_chart_3.png` — source visualizations used in the critique

## Run locally

```bash
python -m pip install -r requirements.txt
jupyter notebook data_visualization_claim_audit.ipynb
```

The notebook is designed to run from the repository root.

## Data sources

- [U.S. Energy Information Administration](https://www.eia.gov/energyexplained/electricity/electricity-in-the-us.php)
- [OpenStax, Principles of Economics 3e](https://openstax.org/books/principles-economics-3e/pages/15-4-income-inequality-measurement-and-causes)
- [Our World in Data](https://ourworldindata.org/grapher/life-expectancy-vs-health-expenditure)

## Notes

This is a public portfolio version of a coursework project. Personal identifiers and grading-only scaffolding have been removed. AI assistance is disclosed inside the notebook, and factual claims are paired with data-based verification steps.
