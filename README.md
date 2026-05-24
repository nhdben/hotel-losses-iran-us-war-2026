# Measuring RevPAR Collapse Under Geopolitical Stress
## Hotel Losses by Chain & Big Hotels | Iran–US Conflict 2026

![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![Python](https://img.shields.io/badge/Python-3.12-blue)
![Tool](https://img.shields.io/badge/Tool-Power%20BI-F2C811?logo=powerbi)

---

## Overview

Analyzing the financial and operational impact of the Iran–US conflict on the 
Middle East hospitality sector, across 36 landmark hotels, 15 hotel chains, 
and 10 countries, showing how geopolitical escalation translates into measurable 
revenue loss, occupancy collapse, and long-term recovery uncertainty.

---

## Key Findings

- **Peak Crisis** drove average revenue loss to **69.7%** : nearly double Active Conflict (40%). Damage persisted into Post-Ceasefire at 42.5%.
- **Atlantis The Palm** absorbed the single largest loss at **$218M**, followed by Hilton Mecca ($164M) and Ritz-Carlton Riyadh ($130M).
- **UAE suffered the greatest country-level loss at $8.54B** : nearly double Saudi Arabia ($4.62B), reflecting Dubai's structural dependence on international tourism.
- **Corporate travel bans and flight rerouting** were the dominant cancellation drivers : institutional decisions, not individual fear, cut off demand.
- A linear regression on four variables explained **94.8% of revenue loss variance** (R² = 0.9482). Occupancy rate is the strongest predictor (coefficient: -14.65).
- **Egypt is the only market projected to fully recover** by 2027H2 under the Optimistic scenario.

---

## Dataset

| File | Rows | Description |
|---|---|---|
| `big_hotels_impact.csv` | 180 | 36 landmark hotels across 5 conflict phases |
| `booking_cancellations.csv` | 600 | Individual cancellation records |
| `conflict_timeline_hotel.csv` | 22 | Key conflict events and estimated revenue impact |
| `country_tourism_impact.csv` | 100 | Country-level tourism and GDP data |
| `hotel_chain_performance.csv` | 3,390 | Monthly chain-level performance |
| `recovery_forecast.csv` | 840 | Recovery scenarios by country and hotel tier |

---

## Methods

- Exploratory Data Analysis (EDA)
- Correlation analysis
- Linear regression (scikit-learn) — R² = 0.9482
- Recovery scenario forecasting

---

## Tools

- Python, pandas, matplotlib, seaborn, scikit-learn
- Power BI (dashboard — in progress)
- Jupyter Notebook

---

## Author

**Nour Elhouda Bencherif**  
Elhouda Lab — Analytics · Culture · Consulting  
[github.com/nhdben](https://github.com/nhdben)
