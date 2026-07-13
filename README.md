# AdventureWorks — Global Sales, Customer & Returns Analysis

**Tool:** Power BI | **Domain:** Retail / Sporting Goods | **Period:** January 2020 – June 2022

---

## Project Overview

End-to-end analysis of AdventureWorks' global bicycle and accessories business, covering 56,046 order lines across 25,164 orders, 17,416 customers, and 7 countries. The project combines a multi-page Power BI dashboard (executive summary, geographic map, customer detail, product detail) with a full written business analysis report covering category profitability, revenue trends, geographic performance, returns, and customer segmentation.

---

## Dataset

| Table | Records | Description |
|---|---|---|
| Sales (2020–2022) | 56,046 | Order-line data: date, product, customer, territory, quantity |
| Product Lookup | 293 | SKU, category, subcategory, cost, price |
| Customer Lookup | 18,148 | Income, occupation, education, gender, birth date |
| Territory Lookup | 10 | Region, country, continent |
| Returns Data | 1,809 | Return date, product, quantity |

*Note: 6 non-data footer rows were identified and removed from the Customer Lookup source file during data cleaning.*

---

## Key Findings

- **$24.91M total revenue** and **$10.46M gross profit** (42.0% margin) across the full period
- **Bikes drives 95% of revenue**, but **Accessories is the true margin engine at 62.8%** — more than 20 points above Bikes — and generates more orders despite a fraction of the revenue
- **Revenue has more than tripled since January 2020**, with a clear, sustained acceleration beginning mid-2021
- **Australia is the single strongest country market**, outperforming every individual European or North American country
- **A data coverage gap was identified**: three U.S. territories show a near-total absence of order data, flagged for follow-up before use in regional comparisons
- **Bikes carries the highest return rate (3.08%)** of any category, with several premium road/touring SKUs individually exceeding 5–11%
- **Customer revenue is broadly distributed** with no concentration risk; High-income customers convert at a notably higher per-customer rate

---

## Business Questions Answered

| # | Question |
|---|---|
| 1 | Which categories and subcategories drive the most revenue and profit? |
| 2 | How has revenue trended over the analysis period? |
| 3 | How does performance vary by country and region? |
| 4 | Where are returns concentrated, and which products drive them? |
| 5 | How does revenue break down by customer income and occupation? |

---

## Deliverables

| Deliverable | Description |
|---|---|
| `AdventureWorks_Dashboard.pbix` | Multi-page interactive Power BI dashboard — executive summary, geographic map, customer detail, product detail, decomposition tree, and key influencers pages |
| `AdventureWorks_Business_Analysis_Report.pdf` | Full written business analysis report — executive summary, methodology, findings by business question, and strategic recommendations |

---

## Skills Demonstrated

`Power BI` `Data Modeling` `DAX` `Data Cleaning` `Multi-Table Relationships` `Geographic Analysis` `Customer Segmentation` `Returns Analysis` `Business Report Writing`

---

*Part of my data analytics portfolio — feedback welcome.*
