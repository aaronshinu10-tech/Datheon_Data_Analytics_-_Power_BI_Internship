# Superstore Retail Sales - Exploratory Data Analysis (EDA)

This repository contains the exploratory data analysis (EDA) and business insights for the Superstore retail sales dataset.

## 📁 Repository Structure
- `Superstore_Retail_Sales_EDA.ipynb`: Complete Jupyter Notebook containing data wrangling, missing-value profiling, statistical aggregations, and visual analysis.
- `superstore_sales.csv`: The underlying Superstore retail sales dataset.
- `superstore_eda_analysis.png`: High-resolution visualization charts generated from the analysis.
- `Superstore_Retail_Sales_EDA_Report.docx`: Professional executive business report summarizing findings and recommendations.

## 📊 Key Executive Findings
1. **Technology Leads Profitability:** Technology generated $836,154 in revenue (33.2% of total) and delivered the highest category profit at $145,455 (17.40% margin).
2. **Sub-Category Losses:** Heavy discounting on items like Tables (-$17,725) and Bookcases (-$3,473) resulted in net operating losses.
3. **Discount Threshold Effect:** Discounts exceeding 20% consistently destroy operating margins, peaking at a -180% return on sales for 80% discount orders.
4. **Regional Disparities:** The West region leads in profitability ($108,418 profit, 14.94% margin), whereas the Central region lags behind (7.92% margin) due to unprofitable discounting.
5. **Segment Efficiency:** Home Office achieves the highest profit efficiency with a 14.03% profit margin ($60,299 profit on $429,653 sales).


## 📊 Task 2: Executive Sales Dashboard (Power BI)
Interactive business intelligence dashboard built to monitor key retail performance metrics, product profitability, and temporal sales trends.

* **`superstore_executive_dashboard.pbix`** : The complete Power BI report file featuring a fully configured Star Schema, custom DAX measures (`Total Sales`, `Total Profit`, `Profit Margin %`, `YoY Sales Growth %`), and dynamic slicers.
* **`dashboard_preview.pdf`** : Executive PDF export of the final report canvas.

### **Key Dashboard Features:**
* **Top-Level KPI Scorecards:** Real-time tracking of Total Sales, Total Profit, and Profit Margin %.
* **Temporal Trend Analysis:** Chronologically sorted monthly sales line chart highlighting business seasonality and peak performance periods across 2015–2018.
* **Product Performance Treemap:** Category and Sub-Category hierarchy color-saturated by profitability to easily identify high-performing assets and loss-making margins.
* **Interactive Filtering:** Dynamic `Segment` and `Year` slicers enabling multi-dimensional slicing for stakeholders.
