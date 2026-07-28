# WeatherPy + VacationPy

## Problem
How do city weather patterns look across random global samples — and where would you actually want to vacation given those conditions?

## What we built
- **WeatherPy**: sample cities, hit OpenWeather, and chart temperature / humidity / cloud / wind relationships
- **VacationPy**: overlay pleasant-weather picks on GeoViews / Geoapify-style maps and heat layers

Notebooks: `WeatherPy.ipynb`, `VacationPy.ipynb`. Outputs land in `output_data/`.

## How to run
1. Copy `api_keys.example.py` → `api_keys.py` and add your own OpenWeather + Geoapify keys (never commit real keys).
2. Install deps and run the notebooks:
```bash
pip install citipy matplotlib pandas requests hvplot geoviews jupyter
jupyter notebook WeatherPy.ipynb
```

## Stack
Python · OpenWeather API · citipy · pandas · matplotlib · hvPlot / GeoViews · Jupyter

## Fun closer
Random cities are chaotic good — until the humidity plot tells on the tropics.
