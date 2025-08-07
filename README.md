# Regional Sales Analysis

**Formal Project Description:**  
This project conducts an in-depth exploratory analysis of five years of U.S. regional sales data, uncovering seasonal trends, top-performing SKUs, channel profitability, and customer segmentation insights to inform data-driven sales and marketing strategies.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Problem Statement](#problem-statement)  
- [Data Description](#data-description)  
- [Approach](#approach)  
- [Project Structure](#project-structure)  
- [Key Insights](#key-insights)  
- [Recommendations](#recommendations)  
- [Dashboard Preview](#dashboard-preview)   

---

## Project Overview

Sales teams often lack clear, data-driven visibility into regional performance, making it difficult to identify growth opportunities. This project analyzes historical sales, margins, and customer data across regions, products, and channels to surface actionable insights and build an interactive dashboard for self-serve analysis.

---

## Problem Statement

- Inconsistent revenue and profit performance across U.S. regions  
- Lack of visibility into seasonal patterns, top SKUs, and channel profitability  
- **Goal:** Leverage five years of historical data to pinpoint growth levers and optimize regional strategies  

---

## Data Description

- **data/Regional Sales Dataset.xlsx**: Raw tables for sales, products, customers, regions, and budgets  
- **data/Sales_data(EDA Exported).csv**: Cleaned, merged dataset ready for analysis  
- **notebooks/EDA_Regional_Sales_Analysis.ipynb**: Jupyter notebook containing data preparation and exploratory analysis code  
- **dashboard/SALES REPORT.pbix**: Interactive Power BI dashboard file  
- **presentation/PPT --- Regional Sales Analysis.pptx**: Slide deck summarizing findings and recommendations  

---

## Approach

1. **Data Pre-processing & Cleaning:** Normalize and merge raw tables; handle missing values and duplicates  
2. **Feature Engineering:** Create `profit`, `profit_margin_pct`, and calendar features (month, season)  
3. **Exploratory Data Analysis:** Visualize trends, outliers, correlations, and distributions  
4. **Insights Extraction:** Identify seasonality, SKU concentration, and regional performance drivers  
5. **Dashboard Development:** Build an interactive Power BI report for dynamic slicing by time, region, and channel  

---

## Project Structure

Regional-Sales-Analysis/
├─ data/
│ ├─ Regional Sales Dataset.xlsx
│ └─ Sales_data(EDA Exported).csv
├─ notebooks/
│ └─ EDA_Regional_Sales_Analysis.ipynb
├─ dashboard/
│ └─ SALES REPORT.pbix
├─ presentation/
│ └─ PPT --- Regional Sales Analysis.pptx
├─ README.md
└─ requirements.txt

yaml
Copy
Edit

---

## Key Insights

- **Seasonality:** Revenue peaks in May–June and dips in January; a notable drop observed in early 2017  
- **SKU Concentration:** Products 25 & 26 drive ~25% of total sales; lower-tier SKUs underperform  
- **Channel Performance:** Wholesale accounts for 54% of sales volume; Export yields the highest average margins  
- **Regional Leaders:** California dominates with the highest revenue and orders; Northeast lags behind other regions  
- **Customer Segmentation:** Top customers generate a disproportionate share of revenue; opportunity to rebalance discounting strategies  

---

## Recommendations

- **Seasonal Promotions:** Launch targeted campaigns in April and amplify January offers to smooth revenue swings  
- **SKU Optimization:** Focus investment on top SKUs (25 & 26) and reevaluate or phase out low-margin products  
- **Channel Expansion:** Incentivize export partnerships for high margins and offer volume deals in wholesale  
- **Regional Investment:** Replicate California’s playbook in underperforming regions (Midwest & Northeast)  
- **Margin Monitoring:** Flag orders below target margin thresholds and analyze cost drivers  

---

## Dashboard Preview

Open the `dashboard/SALES REPORT.pbix` file in Power BI Desktop to explore interactive views, including:

- Performance Summary by Region and Channel  
- Customer Segmentation Analysis  
- Revenue Scenarios and Forecasting visuals  

