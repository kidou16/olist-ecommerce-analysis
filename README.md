# 🇧🇷 Olist E-Commerce Business & Operations Analysis

## Project Overview
Comprehensive analysis of the Olist Brazilian E-Commerce dataset (100,000+ orders from 2016-2018). 
The goal was to transform raw transactional data into actionable business insights regarding 
revenue drivers, customer segmentation, and logistical performance.

## Live Dashboard
[View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/yugal.jagtap/viz/CustomerRevenueAnalyticsOlistBrazil/OlistBRDashboard)

## Notebooks
- [SQLite Analysis & Business Insights](olist_analysis.ipynb)
- [BigQuery Migration Guide](olist_bigquery.ipynb)

## Tech Stack
- **Data Processing:** Python (Pandas, SQLAlchemy)
- **Database:** SQLite, Google BigQuery
- **Cloud:** Google Cloud Platform
- **Visualization:** Tableau Public
- **Environment:** Jupyter Notebook

## Key Business Insights
- **Revenue Concentration:** Credit cards are the primary revenue driver, capturing 78% of total R$16M revenue
- **Geographic Dominance:** São Paulo (SP) has 3x higher customer density than any other state
- **Logistics Friction:** AL and MA show disproportionately high late delivery rates relative to their customer base size
- **Product Performance:** Bed, Bath & Table and Health & Beauty are the core pillars of GMV

## Methodology
1. **Data Extraction:** Queried and joined 8 relational tables using SQL
2. **Analysis:** Wrote 10+ business-driven SQL queries covering revenue, logistics, customer behavior and seller performance
3. **Documentation:** Documented findings with business recommendations in Jupyter Notebook
4. **Visualization:** Built interactive dashboard in Tableau Public

## Dataset
[Olist Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) via Kaggle

## Author
Yugal Jagtap
