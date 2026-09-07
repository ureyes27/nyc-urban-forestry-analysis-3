# NYC Urban Forestry Analysis

An independent, reproducible analysis of New York City street-tree conditions and potential maintenance priorities using official NYC Open Data.

## Research question

**How do street-tree health patterns differ across NYC boroughs and common species, and where might maintenance attention be prioritized?**

This is a descriptive and exploratory project. It will identify patterns and possible priority areas without treating observational relationships as proof of cause and effect.

## Current status

**Phase 1 — Data orientation and quality audit**

The first notebook loads selected fields from the complete census, checks its structure, measures missingness, and records observations before analysis decisions are made.

## Official data source

- [2015 Street Tree Census – Tree Data](https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh)
- Publisher: NYC Department of Parks & Recreation
- Collection period: May 2015–October 2016
- Direct CSV endpoint: `https://data.cityofnewyork.us/api/views/uvpi-gqnh/rows.csv?accessType=DOWNLOAD`

The large raw dataset is downloaded on demand and is not committed to this repository.

## Planned analysis

1. Validate fields, categories, duplicates, and missing values.
2. Establish a defensible analysis population, especially for living trees.
3. Compare health distributions across boroughs.
4. Compare common species while avoiding unstable conclusions from small groups.
5. Explore stewardship, guards, sidewalk conditions, diameter, and reported problems.
6. Build clear charts and summarize limitations.
7. Prepare a public-facing report for possible submission to the NYC Open Data Project Gallery.

## Repository structure

- `notebooks/01_data_exploration.ipynb` — source validation and initial audit
- `requirements.txt` — core Python packages
- `.gitignore` — excludes downloaded data and temporary files
- `README.md` — purpose, method, sources, and progress

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, Google Colab, JuCode, and GitHub.

## Reproducibility and AI use

AI may assist with code drafting, debugging, documentation, and interpretation checks. Every result will still be produced from visible code, checked against the data, and reported with assumptions and limitations.

## Intended submission route

NYC Open Data accepts non-competitive submissions to its [Project Gallery](https://opendata.cityofnewyork.us/project-submit/). Submission will occur only after the analysis and presentation are complete.
