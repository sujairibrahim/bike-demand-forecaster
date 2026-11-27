# Bike Demand Forecaster

Hourly bike-sharing demand forecasting project built around time-series exploratory analysis, leakage-free temporal validation, and tabular forecasting models.

## Repository Structure

```text
bike-demand-forecaster/
├── data/
│   └── hour.csv          # Hourly bike-sharing demand dataset
├── notebooks/
│   └── 01_eda.ipynb      # Data loading, exploration, and summary statistics
├── requirements.txt      # Python environment dependencies
└── README.md
```

## Getting Started

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab notebooks/01_eda.ipynb
```

## Roadmap

- [x] Initial dataset ingestion (`data/hour.csv`) and exploratory data analysis (`notebooks/01_eda.ipynb`)
- [ ] Chronological train/validation/test split and baseline forecasting models ([#1](https://github.com/sujairibrahim/bike-demand-forecaster/issues/1))
- [ ] Feature engineering (calendar, lag, rolling, and weather signals) and error analysis
- [ ] Reproducible training pipeline and serving interface
