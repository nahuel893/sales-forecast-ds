# Sales Forecasting

Proyecto de forecasting de ventas usando series temporales y modelos de ML.

## Estructura

```
sales-forecasting/
├── data/
│   ├── raw/           # datos originales (sintéticos o reales anonimizados)
│   └── processed/     # datos limpios
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_decomposition.ipynb
│   ├── 03_sarima.ipynb
│   ├── 04_prophet.ipynb
│   └── 05_lgbm_features.ipynb
├── src/
│   ├── features.py    # lag features, rolling stats
│   ├── train.py
│   └── evaluate.py
├── dashboard/         # Plotly Dash para presentar resultados
├── mlflow/            # experimentos trackeados
├── README.md
└── requirements.txt
```

## Setup

```bash
pip install -r requirements.txt
```
