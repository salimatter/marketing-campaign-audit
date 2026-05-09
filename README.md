# marketing-campaign-audit
360° digital marketing performance audit for three beauty e-commerce brands - Nykaa, Purplle and Tira Beauty. End-to-end analysis using Python (EDA), SQL/DuckDB (metric modeling) and Power BI (dashboard). Based on simulated campaign data covering 12 months.

## Project Status
EDA complete. Dataset limitation identified and documented, synthetically balanced data yields negligible variance across all dimensions (brands, channels, campaign types). 
Full findings in notebook conclusion.

## What this project demonstrates
- Professional EDA methodology applicable to any marketing dataset
- Data quality assessment and limitation identification
- Feature engineering for marketing analytics (CTR, CVR, channel_type)
- Critical thinking : recognizing and documenting when data doesn't support meaningful analysis

## Stack
- Python (pandas, seaborn, matplotlib) — EDA and data quality
- SQL/DuckDB — metric validation (in progress)
- Power BI — not applicable on this dataset (flat synthetic data) See next project for full SQL + Power BI implementation

## Structure
notebooks/ — EDA notebook
sql/       — DuckDB queries (in progress)
data/      — source CSV files (not included)

## Dataset
Simulated campaign performance data for three Indian beauty e-commerce brands. Limitation : perfectly balanced synthetic distributions limit comparative analysis. Documented in notebook conclusion.
