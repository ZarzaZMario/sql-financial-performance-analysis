# sql-financial-performance-analysis
SQL-driven financial performance and marketing ROI analysis across global markets (2017 sales dataset).
# 📊 Financial Performance & Marketing ROI Analysis (SQL)

![SQL](https://img.shields.io/badge/SQL-Data_Queries-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-Financial_Modeling-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Finance](https://img.shields.io/badge/Metrics-Profitability_%26_ROI-00838F?style=for-the-badge)

## 📌 Executive Summary

### Context & Objective
This project evaluates the 2017 global financial performance and marketing return on investment (ROI) across six key international markets: United States, Australia, United Kingdom, Germany, France, and Canada. 

Using SQL database querying and financial aggregation, the analysis contrasts gross profit margins against campaign costs to evaluate marketing capital efficiency.

**Key Financial Metrics Analyzed:**
- `ingresos` (Total Revenues) & `costos` (Cost of Goods Sold - COGS)
- `CostoCampanas` (Marketing & Campaign Expenditures)
- `BeneficioBruto` (Gross Profit = Revenues - COGS)
- `Margen_pct` (Profit Margin % = Gross Profit / Revenues)
- `ROI_pct` (Marketing Return on Investment % = Gross Profit / Campaign Costs)

---

## 📊 Key Findings

| Country | Revenues (USD) | Gross Profit (USD) | Profit Margin (%) | Campaign Cost (USD) | ROI (%) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **United States** | $3,353,939.92 | $1,454,468.60 | 43.37% | $1,920,000.00 | **75.75%** |
| **Australia** | $2,532,003.49 | $1,057,045.31 | 41.75% | $2,150,400.00 | **49.16%** |
| **United Kingdom**| $1,189,636.78 | $508,128.24 | 42.71% | $2,304,000.00 | **22.05%** |
| **Germany** | $1,071,460.42 | $460,165.06 | 42.95% | $2,265,600.00 | **20.31%** |
| **France** | $924,316.93 | $396,519.79 | 42.90% | $2,208,000.00 | **17.96%** |
| **Canada** | $710,205.18 | $317,879.27 | **44.76%** | $1,824,000.00 | **17.43%** |

### Core Strategic Insights
1. **Market Efficiency Dominance:** The **United States** leads in revenue generation ($3.35M), gross profit ($1.45M), and marketing ROI (75.75%), demonstrating high campaign capital efficiency.
2. **Margin vs. ROI Disparity:**
   - **Canada** yields the highest gross margin percentage (44.76%), yet exhibits one of the lowest ROIs (17.43%) due to elevated marketing spend relative to its revenue scale.
   - **Australia** ranks second in overall revenue and ROI (49.16%), but maintains the narrowest profit margin (41.75%).
3. **European Underperformance:** The UK, Germany, and France absorb significant marketing budgets ($2.2M–$2.3M each) while delivering sub-23% ROIs, indicating campaign over-spending or poor audience conversion.

---

## 🎯 Strategic Recommendations

- **Capital Reallocation:** Reallocate marketing budget away from lower-ROI European markets (France, Germany, UK) toward scaling US operations and optimizing Canadian acquisition costs.
- **Cost Structure Audit:** Review operational cost structures in Australia to protect margin percentages without sacrificing revenue growth.
- **Campaign Optimization:** Restructure advertising acquisition funnels in Canada and Europe to lower acquisition costs and raise return thresholds above 30%.

---

## 📁 Repository Structure

```text
├── data/
│   └── SQL_Financial_Performance_Summary.xlsx
└── README.md
