Supply Chain & Operations Dashboard 

An interactive Power BI dashboard analyzing 180,000+ real-world supply chain orders to uncover delivery performance issues, sales trends, and profitability across regions.

Business Problem
A company shipping products globally had no visibility into delivery delays, supplier performance, or regional profitability. This dashboard consolidates 180K+ order records into a single interactive report for operations and leadership teams.

Key Insights
- Only "45.17%" of orders were delivered on time — a major operational red flag

Tools & Skills Used
- Power Query — cleaned 180K+ rows, reduced 53 columns to 16 relevant fields, fixed data types, built custom calculated columns
- Data Modeling — built a star-schema model with a custom date table and relationships
- DAX — created measures including On-Time Delivery Rate, Total Profit, Avg Days Taken
- Power BI — built a 4-page interactive report with slicers, drill-throughs, and navigation buttons

Dashboard Pages
1. Overview — KPI cards, monthly sales trend, delivery status breakdown
2. Delivery Performance — late vs on-time orders by region and shipping mode
3. Sales & Profit — category-wise sales, profit by customer segment
4. Regional Breakdown — country/region-level sales and profit, region × segment matrix

Screenshots
![Overview Page]("C:\Krishna\Projects\Supply Chain Operations\Screenshot_overview.png")
![Delivery Performance]("C:\Krishna\Projects\Supply Chain Operations\Screenshot _deliveryperformance.png")

Files
- `Supply Chain Dashboard.pbix` — full Power BI file (open in Power BI Desktop, free download)

Dataset
[DataCo Smart Supply Chain Dataset](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis) — Kaggle, 180,000+ rows
