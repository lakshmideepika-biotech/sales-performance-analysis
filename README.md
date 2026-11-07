# Sales Performance Analysis (Superstore)

## Objective
Find which regions, categories and products make or lose money, using Excel, SQL, Python and Power BI on the same dataset.

## Dataset
Sample Superstore dataset: 9,994 orders, about $2.3M sales and about $286K profit (12.5% profit margin).

## Project Folders
- `Excel_Dashboard`: Excel dashboard with pivot tables and slicers
- `SQL_Analysis`: SQL queries (total sales, region-wise sales, top 5 products)
- `Python_Analysis`: Python charts (sales by category, profit by region, top 5 products)
- `PowerBI_Dashboard`: Power BI dashboard with DAX measures

## Key Findings
- West is the best region: about $725K sales and $108K profit
- Central has the weakest margin: about 7.9%, vs 12.5% overall
- Technology earns the most profit ($145K)
- Furniture has high sales ($742K) but only about $18K profit (2.5% margin)
- Tables lose money (about -$17.7K), and so do Bookcases and Supplies
- Orders with a 30% discount or more lose about $135K in total

## Dashboards
### Power BI
![Power BI Dashboard](PowerBI_Dashboard/sales-dashboard.png.png)

### Excel
![Excel Dashboard](Excel_Dashboard/dashboard.png.png)

## Recommendations
- Reduce heavy discounts (30% and above), since they lose money.
- Review Tables and Bookcases pricing and costs.
- Study what works in the West and apply it to Central.

## Tools Used
Excel, SQL Server (SSMS), Python (Pandas), Power BI (DAX)
