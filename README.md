# Tableau-Dashboard---Laundromat-Business-Analysis
Tableau Dashboard to highlight key metrics in order to understand business health
Markdown
# Laundromat Business Analysis

## Interactive Dashboard
Click the preview image below to view and interact with the live dashboard on Tableau Public.

[![Tableau Dashboard Preview](dashboard_preview.png)](https://prod-ca-a.online.tableau.com/t/sophiatse51-925239984f/views/LaundromatDashboard/SalesDashboard)

---

## Business Problem

This project analyzes the operational efficiency and financial performance of a independent, single-location laundromat equipped with **10 washers, 10 dryers, and 2 vending machines** (one for detergent/supplies and one for snacks/drinks). 

Because historical data for this specific footprint was unavailable, I engineered a highly realistic, synthetic relational database in Python to simulate a 2-year operational history. To ensure the data mirrored true brick-and-mortar retail conditions, the data pipeline programmatically incorporated:
1. **The Business Ramp-Up Curve:** Simulating the initial grand opening phase, modeling a gradual customer acquisition curve over the first 6 months until the business reached steady-state maturity.
2. **True-to-Life Seasonality:** Encoding heavy weekend spikes (Saturday/Sunday peak utilization) and seasonal variations in laundry volume (e.g., higher dryer usage and bulkier loads in winter months).
3. **Strict Utility & Inventory COGS:** Mapping Cost of Goods Sold (water, electricity, gas, and wholesale inventory) with tight, normally distributed variances to ensure profit margins realistically scale with machine cycles.

The final Tableau dashboard uses this data to identify peak months, evaluate washer/dryer revenue contribution, and provide actionable recommendations for off-peak promotions and maintenance scheduling.

