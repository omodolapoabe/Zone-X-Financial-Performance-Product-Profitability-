Zone X: Financial Performance & Product Profitability Analysis (2024 vs 2025)
Project Overview

This project takes a messy two-year sales ledger for Zone X, a business selling two products (Asobe Shirt and Zen T-Shirt), and turns it into a clean dataset, a set of PivotTables and two interactive Excel dashboards. The analysis compares 2024 and 2025 to explain why profit grew by about 20% while revenue grew by only about 2%, and which product was behind the change.
The raw data starts at 258 transaction records across 7 columns and ends at 249 cleaned records covering January 2024 to December 2025. All figures are in Nigerian Naira (₦).

Problem Statement
The business had financial data for two financial years, but the raw dataset was not structured in a way that made it easy to evaluate performance, spot trends, compare years or see which products drove revenue and profit. Without a consolidated view, it was hard to answer questions such as:

How did financial performance change between 2024 and 2025?
Did revenue and profit rise or fall?
How effectively were expenses managed?
Which months and quarters performed best?
Which products generated the most revenue and profit, and which had the strongest margin?
What contributed to the change in overall profitability?

Objectives
Clean and standardise the financial dataset so it is reliable for analysis.
Compare revenue, expenses and profit between 2024 and 2025.
Analyse monthly and quarterly trends.
Evaluate changes in profit margin.
Compare product-level revenue and profit performance and identify the top performer.
Determine whether changes in product performance contributed to the overall change in profitability.
Build an interactive Excel dashboard that lets users compare financial years and products.
Provide business recommendations based on the findings.

Data Preparation
The workbook keeps the original Messy Financial Data sheet alongside the Cleaned Data sheet. The main issues and fixes:
Issue in raw data	Fix
Dates in many formats (10/27/2024, 15/09/2025, 15 July 2024, 2025/07/06, 04-Oct-2025) plus stray whitespace	Standardised to a single Excel date type
Product names with inconsistent case and leading spaces (zen t-shirt, ZEN T-SHIRT,  Asobe Shirt)	Trimmed and standardised to two clean product names
Revenue, Expenses and Profit stored as text in some rows (12,433,378.00)	Converted to numeric
Blank Month or Product values	Reviewed column by column instead of replacing every blank with zero, since a blank means different things in different fields
Duplicate rows	Removed
Months sorting alphabetically in charts	Added a Month No. field so months appear in calendar order

Derived fields added: Month No., Quarter, Profit Margin (Profit ÷ Revenue) and Expenses Ratio (Expenses ÷ Revenue). Financial Year was also checked against the cleaned date.

Revenue − Expenses = Profit holds on every cleaned row.

Analysis layer: After cleaning, PivotTables summarise monthly revenue, profit and margin, revenue vs expenses, product revenue, profit and margin, quarterly profit and year-over-year profit. PivotCharts built from them feed the dashboards.

Tools Used
Microsoft Excel: data cleaning, formulas, PivotTables, PivotCharts, slicers and dashboard design
Data cleaning: date parsing, text standardisation, type conversion, handling missing values and duplicates
Financial analysis: year-over-year comparison, margin analysis, product contribution, monthly and quarterly trend analysis
Key Insights

Overall performance

Metric	2024	2025	Change
Revenue	₦1,194.74M	₦1,221.34M	+2.23%
Expenses	₦642.70M	₦556.21M	−13.46%
Profit	₦552.03M	₦665.14M	+20.49%
Overall profit margin (Profit ÷ Revenue)	46.2%	54.5%	+8.3 pts

By product

Product	Revenue 2024 → 2025	Profit 2024 → 2025	Avg. profit margin 2024 → 2025*
Zen T-Shirt	₦663.55M → ₦871.63M (+31.36%)	₦348.77M → ₦518.43M (+48.65%)	48.06% → 54.88%
Asobe Shirt	₦531.19M → ₦349.71M (−34.16%)	₦203.27M → ₦146.71M (−27.82%)	37.26% → 43.26%

*Average of the per-transaction profit margins. Calculated as total profit ÷ total revenue, the margins are 52.6% → 59.5% for Zen and 38.3% → 42.0% for Asobe. The direction is the same either way.

Revenue was nearly flat, but profit was not. Cutting expenses by 13.5% while revenue held steady lifted profit by about a fifth.
A product shift sits underneath the flat revenue. Zen T-Shirt grew strongly while Asobe Shirt lost about a third of its revenue. Zen's growth more than covered Asobe's decline, so the headline number hides a large change in the product mix.
Zen is both bigger and more profitable per naira of sales. Its margin is roughly 10 to 15 points above Asobe's in both years.
Asobe's margin improved even as its sales fell, because its expenses dropped by about 38%. This points to a demand problem rather than a cost problem.
2025 was stronger in the second half. Q4 2025 profit was ₦178.3M against ₦87.8M in Q4 2024, while Q1 2025 was weaker than Q1 2024 (₦124.7M vs ₦153.6M).
Recommendations
Prioritise Zen T-Shirt. It leads on revenue growth, profit growth and margin, so it deserves more focus on stock availability, marketing, promotions, retention and distribution.
Investigate Asobe Shirt's decline. Look at demand, pricing, competition, positioning, marketing and stock. The aim is to understand why demand fell, not to drop the product automatically.
Maintain cost control. Identify which cost lines produced the 13.5% reduction and confirm the savings can be sustained without hurting quality or sales.
Focus on profitable growth. Revenue growth alone is not enough, so prioritise products and activities that deliver both sales and healthy margins.
Review product performance monthly. Track revenue, profit, margin, growth rate and product contribution so declines are caught early.
Dashboard Features

Both dashboards are built from PivotTables and PivotCharts and use slicers, so viewers can switch views without touching the data.

Dashboard 1: Financial Performance

Revenue, expenses, profit, profit margin and year-over-year profit growth
Monthly trends
Filter: Product slicer (Asobe Shirt, Zen T-Shirt, or both)

Dashboard 2: Product & Profitability

Product revenue, expenses, profit and profit margin
Quarterly profit and top-performing products
Filters: Financial Year slicer (2024, 2025, or both) and Product slicer

How to use: Download Zone_X_Financial_Analysis.xlsx, open it in desktop Excel (slicers work best there), go to either dashboard sheet and use the slicers to compare years and products.

Conclusions

Zone X achieved only modest revenue growth in 2025 but much stronger profitability. Revenue rose about 2.23% while expenses fell about 13.46%, which pushed profit up about 20.49%. At product level, the business shifted from Asobe Shirt towards Zen T-Shirt: Zen grew in both revenue and profit and carries a considerably higher margin, while Asobe declined on both. Better cost management and a move towards the stronger product were the key drivers of the improvement.

<img width="1743" height="814" alt="image" src="https://github.com/user-attachments/assets/ad2350da-b9c8-4dd7-8eca-5c7cc96fb165" />

<img width="1423" height="808" alt="image" src="https://github.com/user-attachments/assets/99e4e098-0632-4f03-97d6-266a8f296c17" />


