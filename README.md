# Comprehensive Financial Analysis: Dunelm Group vs. Chemring Group

**A programmatic, formula-driven financial model built to analyze and compare two vastly different UK market leaders.**

## The Story Behind the Model
What happens when you pit a capital-light retail giant against an asset-intensive defense contractor? 

I built this comprehensive financial model to answer that exact question. This project isn't just a data dump; it's a fully automated, formula-driven Excel architecture generated using excel. It covers 5-6 years of historical financial data (Dunelm FY19–FY24 and Chemring FY20–FY25) to showcase how fundamentally different business models look under the hood of rigorous financial analysis.

Whether you're looking at profitability, liquidity, or market valuation, this model is designed to be fully transparent, strictly color-coded, and audit-ready.

## Model Architecture & Features
The model is split into logically flowing modules, designed to take raw financial statements and distill them into actionable investment metrics:

* **Source Data Sets:** Raw Income Statements, Balance Sheets, Cash Flows, and Supplementary data for both companies.
* **Module 1: Financial Statement Analysis (FSA):** Macro trends across Revenue, GP, EBIT, PAT, EPS, DPS, Assets, Equity, and Debt.
* **Module 2: Profitability Analysis:** A deep dive into Margins, EBITDA, ROE, ROCE, ROA, and Cash Conversion dynamics.
* **Module 3: Efficiency Analysis:** Evaluating operational throughput via Asset Turnover, Inventory Days, DSO, DPO, and Cash Conversion Cycle (CCC).
* **Module 4: Liquidity Analysis:** Stress-testing the balance sheet using Current/Quick/Cash Ratios, Working Capital, and FCF/Dividend cover.
* **Module 5: Solvency & Risk:** Assessing long-term viability via Gearing, Leverage, Interest Cover, DSCR, and Capex Intensity.
* **Module 6: Market & Investment:** Valuation metrics including P/E, P/B, EV/EBITDA, Dividend Yield, TSR, and FCF Yield.

## Key Insights at a Glance
*(Most recent year: Dunelm FY2024 | Chemring FY2025)*

| Metric | Dunelm (Retail) | Chemring (Defence) | The Takeaway |
| :--- | :--- | :--- | :--- |
| **Revenue** | £1,706.5m | £497.5m | Dunelm is ~3.4x larger by top-line volume. |
| **EBIT Margin** | 12.5% | 14.8% | Chemring showing the highest margin in its period; both improving. |
| **ROCE (approx)** | ~36% | ~12% | Highlights the capital-light retail model vs. asset-intensive defense. |
| **Interest Cover**| 21.5x | 12.9x | Both exhibit excellent ability to service their debt. |
| **Op. Cash Flow** | £232.3m | £91.1m | Both companies are strong cash generators. |

## Technical Details & Best Practices
To ensure this model is professional-grade, I implemented strict financial modeling conventions:

* **Python-Generated:** Built from the ground up using `openpyxl`.
* **Transparent Logic:** Column `B` in every analysis sheet contains a plain-text description of the formula used, ensuring complete transparency and easy auditing.
* **Standardized Color-Coding:** 
  * 🔵 **Blue text:** Hardcoded input values (raw data).
  * ⚫ **Black text:** Excel formulas / Calculated outputs.
  * 🔴 **Red background:** Dunelm data columns.
  * 🟢 **Green background:** Chemring data columns.
  * 🟡 **Yellow background:** Formula logic/methodology indicator.

## How to Explore
1. Clone this repository.
2. Open the `.xlsx` file in Excel to explore the interactive, formula-driven sheets.
3. Review the underlying Python scripts (if included) to see how the data pipeline and Excel formatting were automated.

---
*Built as a work sample to demonstrate advanced financial modeling, data structuring.*
