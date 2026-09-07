# NYC Urban Forestry Analysis

An independent, reproducible analysis of New York City street-tree conditions and potential maintenance priorities using official NYC Open Data.

## Research question

**How do street-tree health patterns differ across NYC boroughs and common species, and where might maintenance attention be prioritized?**

This is a descriptive and exploratory project. It will identify patterns and possible priority areas without treating observational relationships as proof of cause and effect.

## Current status

**Dataset inspection — structure, completeness, and measurement limitations**

The first notebook uses compact server-side queries to inspect the complete census, measure missingness, test category consistency, and document measurement limitations without downloading the full dataset.

## Official data source

- [2015 Street Tree Census – Tree Data](https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh)
- Publisher: NYC Department of Parks & Recreation
- Collection period: May 2015–October 2016
- Direct CSV endpoint: `https://data.cityofnewyork.us/api/views/uvpi-gqnh/rows.csv?accessType=DOWNLOAD`

The large raw dataset is downloaded on demand and is not committed to this repository.

## Planned analysis

1. Inspect fields, categories, duplicates, and meaningful missingness.
2. Establish a defensible analysis population, especially for living trees.
3. Compare health distributions across boroughs.
4. Compare common species while avoiding unstable conclusions from small groups.
5. Explore stewardship, guards, sidewalk conditions, diameter, and reported problems.
6. Build clear charts and summarize limitations.
7. Prepare a public-facing report for possible submission to the NYC Open Data Project Gallery.

## Repository structure

- `notebooks/01_data_exploration.ipynb` — lightweight source inspection and anomaly documentation
- `requirements.txt` — core Python packages
- `.gitignore` — excludes downloaded data and temporary files
- `README.md` — purpose, method, sources, and progress

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, Google Colab, JuCode, and GitHub.

## Reproducibility and AI use

AI may assist with code drafting, debugging, documentation, and interpretation checks. Every result will still be produced from visible code, checked against the data, and reported with assumptions and limitations.

## Intended submission route

NYC Open Data accepts non-competitive submissions to its [Project Gallery](https://opendata.cityofnewyork.us/project-submit/). Submission will occur only after the analysis and presentation are complete.
