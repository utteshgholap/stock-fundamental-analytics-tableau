# 📈 Stock Fundamental Analytics Dashboard (Tableau)

An interactive corporate finance and equity research dashboard engineered in **Tableau Desktop**, evaluating balance sheet strength, income statement profitability, liquidity ratios, and cash flow sustainability across S&P 500 companies.

---

## 📊 Dashboard Visual Overview

![Stock Fundamental Analytics Dashboard](images/dashboard_preview.jpg)

---

## 📌 Analytical Scope & Core Financial Metrics

This dashboard analyzes fundamental financial data (comprising over 1,780 financial reporting periods across S&P 500 tickers) across five core pillars of fundamental analysis:

### 1. Revenue & Earnings Generation (Scale & Profitability)
* **Top 10 Stocks by Total Revenue:** Evaluates top-line commercial scale, isolating global market leaders (such as Walmart `WMT`, ExxonMobil `XOM`, and Chevron `CVX`).
* **Top 10 Stocks by Net Income:** Measures bottom-line net profit delivery, visualised through packed bubble clusters to compare market earnings concentration (led by Apple `AAPL`, ExxonMobil `XOM`, and JPMorgan Chase `JPM`).
* **Multi-Tier Margin Decomposition:**
  * **Gross Margin (%)**: Isolates core product profitability and pricing leverage.
  * **Operating Margin (%)**: Benchmarks overhead, SG&A efficiency, and operational execution.
  * **Net Profit Margin (%)**: Analyzes final bottom-line margins after interest, tax, and non-operating deductions.

### 2. Capital Efficiency & Shareholder Returns
* **After-Tax Return on Equity (ROE) Ranking:** Slices equity efficiency to demonstrate how effectively corporate management reinvests shareholder capital to drive earnings expansion.

### 3. Liquidity & Short-Term Financial Health
* **Current Ratio ($Current\ Assets / Current\ Liabilities$):** Evaluates short-term working capital adequacy across different capital structures.
* **Cash Ratio ($Cash\ \&\ Equivalents / Current\ Liabilities$):** Strictest liquidity diagnostic, identifying firms capable of clearing immediate obligations without liquidating receivables or inventory.

### 4. Earnings Quality & Cash Flow Reconciliation
* **Revenue vs. Net Income (Scatter Matrix):** Identifies margin compression and volume-vs-profitability clusters.
* **Operating Cash Flow vs. Net Income:** Directly verifies **earnings quality** by comparing accrual-based accounting profits against actual cold operating cash generated (highlighting firms like Apple `AAPL` demonstrating exceptional cash conversion).

### 5. Leverage & Balance Sheet Solvency
* **Total Assets vs. Total Liabilities:** Maps enterprise balance sheet scale, clearly distinguishing heavily leveraged financial institutions (`JPM`, `BAC`, `WFC`, `C`) from asset-light, capital-efficient tech/consumer leaders.
* **Debt-to-Equity (D/E) Ratio Distribution:** Evaluates financial leverage risk, spotting over-leveraged capital structures versus conservative cash-rich enterprises.

---

## 🛠️ Tableau Technical Architecture & Implementation

* **Visual Analytics & Chart Formats:**
  * Horizontal benchmark bar charts with ranking sorting filters.
  * Packed bubble clusters for proportional net income comparison.
  * Dual-axis and multi-variable scatter plots for cash flow & balance sheet regression.
  * Segmented pie/donut distribution for ROE sector cohorts.
* **Calculated Fields & Ratios:**
  * Standardized financial formulas for margins, quick liquidity, and capital structure ratios.
  * Custom dimension grouping and Top-N parameter filtering.
* **Data Source:** Financial statement fundamental data covering balance sheets, income statements, and cash flow statement line items.

---

## 🚀 How to Run & Explore

1. Clone this repository:
   ```bash
   git clone [https://github.com/utteshgholap/stock-fundamental-analytics-tableau.git](https://github.com/utteshgholap/stock-fundamental-analytics-tableau.git)
