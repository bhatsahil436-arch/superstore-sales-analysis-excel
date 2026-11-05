# Superstore Sales Analysis | Excel

Excel version of my Superstore case study (SQL, Python, Power BI, Excel).
All 19 business questions are answered twice in Excel, with formulas and with
pivot tables, and every result matches my SQL and Power BI output.

## Key Metrics
- Total Sales: 2,296,919.49
- Total Profit: 286,409.08
- Profit Margin: 12.47%
- Total Orders: 5,009
- Avg Order Value: 458.56

## Key Findings
- Discounts above 20% lose money: -135K profit, against +321K with no discount.
- 1,870 order lines (18.7%) are loss-making, at a 48.1% average discount.
- Texas, Ohio, Pennsylvania and Illinois are the biggest loss-making states.
- Sales fell 2.8% in 2015, then grew 29.5% in 2016 and 20.4% in 2017.
- 98.5% of customers (781 of 793) are repeat buyers.

## Workbook Structure
| Sheet | Purpose |
|---|---|
| CLEAN CHECKS | Data quality checks and raw vs clean proof |
| CLEAN | Cleaned data with helper columns |
| ANALYSIS | Q1 to Q19, each by formula and pivot table |
| Q15_WORK, CUSTOMER_SUMMARY | Helper tables for ranking and customer groups |
| MINI DASHBOARD | KPI cards and charts |

## Excel Skills Used
SUMIFS, COUNTIFS, AVERAGEIFS, MINIFS, MAXIFS, UNIQUE, FILTER, SORT,
SORTBY, XLOOKUP, pivot tables, ranking, running totals, helper columns,
data cleaning and validation, charts.

## Screenshots
![Dashboard](screenshots/1-dashboard.png)
![Clean Checks](screenshots/2-clean-checks.png)

## Where to find the answers
Open `Superstore_Excel_Dashboard.xlsx` and go to the **ANALYSIS** sheet.

## Related Projects
- Power BI dashboard: [https://github.com/bhatsahil436-arch/-superstore-sales-analysis-powerbi]
- SQL case study: [https://github.com/bhatsahil436-arch/superstore-sql-case-study.git]
- Python EDA:[https://github.com/bhatsahil436-arch/superstore-sales-analysis-python.git]
  

