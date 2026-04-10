# Where the Birds Are

A data visualization of birding across Newfoundland & Labrador, built for the Johnson Geo Centre using the eBird 2025 dataset.

<img width="4800" height="7200" alt="infographic(36)" src="https://github.com/user-attachments/assets/70abd3c8-46e3-4633-a9f9-2cda41e41a32" />


## What This Is

A 36×24 inch infographic poster and an interactive Dash dashboard — both generated from `birds.csv` with Python. The poster has three visualizations:

1. **Geographic Hotspot Map** — every birding locality, sized by observations, coloured by species diversity
2. **County Species Richness** — bar chart ranking all 11 counties by unique species
3. **IBA Species Composition** — stacked bars showing bird-group breakdown at the top 8 Important Bird Areas

## Quick Start

```bash
pip install pandas numpy matplotlib geopandas pillow requests dash plotly

# Generate the poster
python infographic.py

# Run the dashboard
python dashboard.py
```

## Files

```
birds.csv            eBird 2025 data for NL
infographic.py       Poster script (single Jupyter cell)
dashboard.py         Interactive Dash dashboard
portfolio.html       Project portfolio page
```

## Key Stats

- **27,000+** observations
- **280+** unique species
- **1,400+** birding localities
- **~65%** of observations from the Avalon Peninsula alone

## Built With

Python · Matplotlib · Pandas · GeoPandas · Pillow · Plotly Dash

## Data

[eBird Basic Dataset (2025)](https://ebird.org) — Cornell Lab of Ornithology. Map boundaries from [Natural Earth](https://www.naturalearthdata.com/).

---

*Produced for the Johnson Geo Centre, St. John's, NL · 2025*
