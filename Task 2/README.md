# 🪙 Task 2: Cryptocurrency Portfolio & Risk Analysis (12-Month)

**Internship Track:** Finance & Investment Analysis  
**Organization:** CodeAlpha  
**Author / Analyst:** A. Mohammed Aslam  
**Analysis Window:** July 28, 2025 – July 28, 2026 (Daily Closing Prices)  
**Primary Currency:** Indian Rupees (INR / ₹)  

---

## 📌 1. Project Overview & Objectives
This repository contains the deliverables for **Task 2 of the CodeAlpha Finance & Investment Analysis Internship**. The project delivers a comprehensive 12-month performance, price trajectory, and drawdown risk evaluation of three leading digital assets:
* **Bitcoin (BTC)**
* **Ethereum (ETH)**
* **Solana (SOL)**

The primary objective is to evaluate capital preservation characteristics, comparative drawdown risks, and asset volatility to formulate a structured **risk-adjusted portfolio allocation framework** for investors.

---

## 📂 2. Repository Contents

| File Name | File Type | Description |
| :--- | :--- | :--- |
| **`Task_2_Crypto_Analysis_Mohammed_Aslam.xlsx`** | Excel Workbook | Primary analytical workbook containing individual asset tabs (`Bitcoin`, `Ethereum`, `Solana`), the `Summary` comparison table, and embedded performance visualizations. |
| **`Task_2_Crypto_Analysis_Report.pdf`** | PDF Report | Complete 3-page executive research report detailing empirical metrics, visual price trajectories, structural beta evaluation, and strategic recommendations. |
| **`... - Bitcoin.csv`** | CSV Dataset | Raw 1-year daily historical closing price dataset for Bitcoin (BTC/INR). |
| **`... - Ethereum.csv`** | CSV Dataset | Raw 1-year daily historical closing price dataset for Ethereum (ETH/INR). |
| **`... - Solana.csv`** | CSV Dataset | Raw 1-year daily historical closing price dataset for Solana (SOL/INR). |

---

## 📊 3. Executive Performance Summary

| Asset Name | Starting Price (INR) | Ending Price (INR) | 1-Year Return (%) | 52-Week High (INR) | 52-Week Low (INR) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Bitcoin (BTC)** | ₹10,351,153.20 | ₹6,247,126.18 | **-39.65%** | ₹11,031,645.85 | ₹5,639,316.42 |
| **Ethereum (ETH)** | ₹336,552.53 | ₹186,476.72 | **-44.59%** | ₹419,789.14 | ₹146,702.79 |
| **Solana (SOL)** | ₹16,378.28 | ₹7,337.56 | **-55.20%** | ₹21,815.44 | ₹5,904.60 |

---

## 🔍 4. Key Analytical Insights
1. **Defensive Relative Performance (Bitcoin):**
   * Bitcoin exhibited the lowest overall drawdown (**-39.65%**) among the analyzed assets, outperforming Ethereum by ~500 bps and Solana by ~1,550 bps.
   * Demonstrates lower relative standard deviation, confirming BTC's role as the primary defensive anchor during macroeconomic market consolidations.
2. **Altcoin Volatility & High Beta (Ethereum & Solana):**
   * **Solana (SOL)** recorded the most severe drawdown (**-55.20%**), reflecting high beta and asymmetric sensitivity to liquidity contraction cycles.
   * **Ethereum (ETH)** experienced moderate downside (**-44.59%**), tracking between Bitcoin's relative stability and Solana's speculative volatility while maintaining strong settlement layer liquidity.

---

## 💡 5. Strategic Portfolio Allocation Framework
Based on empirical 12-month risk-return profiles, the following allocation structure is recommended for capital preservation and upside capture:

* **Core-Satellite Allocation:**
  * **60% – 70% Bitcoin (BTC):** Core allocation to anchor portfolio volatility and mitigate severe capital drawdowns.
  * **20% – 25% Ethereum (ETH):** Tactical growth allocation to capture decentralized infrastructure yield with moderate risk.
  * **10% – 15% Solana (SOL):** Capped satellite exposure to limit maximum drawdown while preserving exposure to high-beta momentum during bullish reversals.
* **Execution Strategy (DCA):**
  * Due to wide spreads between 52-week highs and lows across all assets, lump-sum capital deployment is discouraged.
  * Implement systematic **Dollar-Cost Averaging (DCA)** over a 4 to 6-month horizon to smooth entry basis and cushion volatility.

---

## 🛠️ 6. Methodology & Tools Used
* **Data Extraction:** Google Finance API (`GOOGLEFINANCE`) for daily closing prices (`CURRENCY:BTCINR`, `CURRENCY:ETHINR`, `CURRENCY:SOLINR`).
* **Data Analysis & Spreadsheets:** Microsoft Excel / Google Sheets (Return calculations, `MAX`/`MIN` price bounds, Standard Deviation risk modeling).
* **Data Visualization:** Bar charts for total return comparison and normalized 100-base line charts for 12-month price trajectory mapping.
* **Reporting:** Executive PDF report generation and Markdown documentation.
