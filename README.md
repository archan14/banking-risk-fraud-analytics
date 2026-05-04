# Banking Risk & Fraud Analytics

Fraud detection and financial risk analytics — suspicious transaction patterns, high-risk customer identification, and daily monitoring dashboards built with **SQL · Python · Power BI**.

> Dataset: **5,000 customers · 10 branches · 50,000+ transactions · 2023–2024**

---

## Quick Start

```bash
pip install -r requirements.txt
python3 python/data_generator.py
python3 python/analysis.py
open reports/report.html
jupyter notebook notebooks/banking_fraud_analysis.ipynb
```

---

## Key Analyses

- **Fraud Transaction Patterns** — amount anomalies, velocity checks, channel risk, time-of-day patterns
- **High-Risk Customer Identification** — risk scoring, behavioral flags, network clustering
- **Daily Transaction Monitoring** — KPI alerts, threshold breaches, rolling averages
- **Window Function Analytics** — running totals, peer comparison, percentile ranking
- **Anomaly Detection** — Isolation Forest + Z-score flagging

---

## Stack

| Tool | Purpose |
|------|---------|
| **SQLite** | Portable database (PostgreSQL/MySQL compatible queries) |
| **pandas + numpy** | Data wrangling and metric computation |
| **scikit-learn** | Isolation Forest anomaly detection |
| **matplotlib + seaborn** | Publication-quality charts |
| **Power BI Desktop** | Interactive fraud monitoring dashboard |
| **Jupyter** | Step-by-step EDA notebook |
