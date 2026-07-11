# Task 1: Stock Market Performance Analysis Report

This directory contains all data assets, interactive models, and the final analytical report for **Task 1** of the CodeAlpha Finance & Investment Analysis Internship. 

---

## 🔍 Project Objective
To conduct a comprehensive 1-year historical evaluation of three major Indian large-cap equities—**Tata Consultancy Services (TCS)**, **Reliance Industries**, and **Infosys**—tracking daily performance, structural volatility, valuation multiples, and core macroeconomic drivers from **July 2025 to July 2026**.

## 🛠️ Data Engineering & ETL Pipeline
1. **Data Acquisition:** Pulled $244$ days of continuous daily historical closing prices for each security via the `GOOGLEFINANCE` API engine.
2. **Data Transformation (Power Query):** 
   * Cleansed timestamps by truncating `Date/Time` down to a standardized `Date` format to eliminate chart plotting noise.
   * Engineered custom corporate identifier columns (`Company`) across separate inputs.
   * Executed a vertical query append to aggregate all entities into a single, highly performant unified table structure containing $732$ records (`Stock_Data`).
3. **Data Visualization:** Generated a responsive multi-series **Power BI Line Chart** mapping smooth daily tracking trends across the 12-month period, eliminating aggregate hierarchy distortions.

---

## 📊 Core Analytical Metrics (As of July 2026)

| Company | Market Capitalization | P/E Ratio | 1-Year Net Change | 52-Week High | 52-Week Low |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **TCS** | ₹7,40,896 Cr | 14.80x | **-35.80%** | ₹3,324.90 | ₹1,982.60 |
| **Reliance** | ₹1,731,754 Cr | 18.11x | **-11.86%** | ₹1,592.30 | ₹1,258.80 |
| **Infosys** | ₹433,899 Cr | 14.72x | **-31.99%** | ₹1,689.80 | ₹985.30 |

---

## 💡 Key Financial Takeaways
* **IT Sector Corrections:** Macroeconomic pressures created a heavy downward cycle for tech spending over the past 12 months, leading to deep corrections for TCS (-35.80%) and Infosys (-31.99%). However, strong Q1 earnings and rapidly expanding enterprise AI pipelines (TCS reaching a \$2.6 Billion annualized AI run rate) highlight these compressed P/E valuations (around 14.7x) as historically cheap entry margins.
* **Defensive Asset Performance:** Reliance Industries acted as the definitive portfolio anchor. Supported by its massive ₹17.3 Trillion market cap, it displayed superior defensive risk resilience against broader index volatility, absorbing market corrections with a minimal annual decline of just -11.86%.

---

## 📁 File Structure & Deliverables
*   `TCS_1Year_Daily - Sheet1.csv` - Cleaned source historical daily pricing for TCS.
*   `Reliance_1Year_Daily - Sheet1.csv` - Cleaned source historical daily pricing for Reliance Industries.
*   `Infosys_1Year_Daily - Sheet1.csv` - Cleaned source historical daily pricing for Infosys.
*   `Task_1_Stock_Analysis.pbix` - Production-ready Power BI Desktop data model and interactive line chart.
*   `Task_1_Stock_Analysis_Report.pdf` - The final comprehensive, executive-ready financial evaluation document.
