# 🌍 Middle East Economy & Oil Prices Analysis (1990–2024)
<img width="1408" height="768" alt="oil" src="https://github.com/user-attachments/assets/e78b9649-6613-4a3e-aa94-845a34bf72e0" />


This repository provides a **comprehensive data analysis** of 13 Middle Eastern economies from **1990 to 2024**, combined with annual **Brent oil prices**. The project explores how oil price shocks and broader economic events influence **GDP growth, trade, FDI, inflation, unemployment, life expectancy, and regional development**, presented through a polished, light-themed notebook-style analysis.

Built for economic research, policy-minded exploration, and data storytelling, this workflow emphasizes clear visuals, consistent design, and actionable insight.

## 📊 Dataset Overview
**File:** `Middle_East_Economic_Data_1990_2024_with_Oil.csv`  
**Coverage:** 13 Middle Eastern countries, **1990–2024** (balanced panel where data allows)  
**Core content:** macroeconomic indicators + Brent crude oil price (annual average)

### Key variables included
- `Country`, `Country_Code`, `Year`
- `Exports_pct_GDP` and `Imports_pct_GDP` (trade structure)
- `Trade_Balance_pct_GDP` (computed internally for convenience)
- `GDP_current_USD`, `GDP_growth_annual_pct`, `GDP_per_capita_current_USD`
- `FDI_net_inflows_pct_GDP` (net inflows as % of GDP)
- `Inflation_consumer_prices_annual_pct`
- `Life_expectancy_years`
- `Unemployment_total_pct`
- `Brent_Oil_Price_USD_per_barrel` (annual average in USD)

### Data sources (as described in the dataset origin)
- **World Bank Open Data** (economic indicators)
- **Historical Brent crude oil prices**
<img width="684" height="383" alt="ed55019a-a030-4489-a3e6-d58224724d02" src="https://github.com/user-attachments/assets/b7d2e361-b8cb-4814-a5d1-8565145a7929" />

## 🚀 What’s inside this repository
- **Interactive notebook-style analysis** (single cohesive notebook) with a consistent, light earth-tone visual theme
- **Exploratory data analysis (EDA)**: missing-data checks, panel completeness, outlier/contextual review
- **Trend dashboards** at regional and country levels for growth, inflation, unemployment, and life expectancy
- **Oil-price impact analysis** including correlations, event shocks, and comparisons across different economic profiles
- **Trade dependency view**: export-heavy vs import-dependent patterns and shifts over time
- **Wealth indicators**: total regional GDP, GDP per capita, recession years, development snapshots
- **FDI flows**: long-run patterns and sensitivity around instability and oil-price collapses
- **Inflation dynamics**: volatility, distributions, and relation to growth and events
- **Social development lens**: life expectancy improvements tied to income and broader progress
- **Unemployment tracking**: long-run trends and notable spikes around crises
- **Correlation + clustering**: indicator associations and country groupings based on structure (oil dependency, trade balance, etc.)
- **Event & anomaly focus**: Gulf War (1991), Global Financial Crisis (2008), Oil Price Crash (2014), COVID-19 Oil Collapse (2020)
- **Automated report export**: a clean Markdown summary and cleaned/cluster outputs saved locally

## 📄 Outputs generated
When you run the analysis, the project writes files to an `outputs/` folder:
- `Middle_East_Economy_Report.md` — narrative summary with tables, highlights, and key event snapshot  
- `Middle_East_Economic_Data_Cleaned.csv` — a cleaned, analysis-ready copy of the dataset  
- `Middle_East_Country_Cluster_Features.csv` — country-level features used for clustering + assigned clusters and PCA coordinates  

## 🛠️ Requirements
Python **3.9+** is recommended. Install dependencies with:

```bash
pip install -r requirements.txt
```
<img width="1381" height="584" alt="e8528f41-484d-4ee4-b9df-fc6d63bf7d42" src="https://github.com/user-attachments/assets/465b386f-5434-4090-9a72-0b3d96eb7217" />
