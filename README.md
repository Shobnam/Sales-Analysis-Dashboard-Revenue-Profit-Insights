# Sales-Analysis-Dashboard-Revenue-Profit-Insights
Interactive Power BI dashboard that analyzes order-level sales data to surface where revenue and profit are concentrated (by month, segment, category, ship mode and geography) and to highlight operational KPIs (sales, profit, quantity, avg delivery days)
# Sales Analysis Dashboard

**Interactive Power BI dashboard** that analyzes sales, profit and operations metrics by month, segment, category and geography.

## Preview
# Sales Analysis Dashboard

**Interactive Power BI dashboard** that analyzes sales, profit and operations metrics by month, segment, category and geography.

## Preview
<img width="1310" height="735" alt="image" src="https://github.com/user-attachments/assets/2160b021-3895-44ac-add7-4be9f5a06a27" />


## Key metrics (from dashboard)
- Total Sales: **341.01K**
- Total Profit: **27.45K**
- Quantity sold: **5239**
- Avg Delivery Days: **4**

## Key insights (summary)
- Consumer segment contributes ~48% of revenue.
- Standard shipping generates the highest sales (~0.21M).
- Top categories: Office Supplies (0.15M), Furniture (0.11M), Technology (0.09M).
- Top sub-categories: Chairs, Binders, Phones.

## Files
- `data/sales_data.csv` — sample data
- `powerbi/Sales_Analysis.pbix` — Power BI Desktop file
- `notebooks/` — data prep (optional)
- `assets/` — screenshots and GIF
- `README.md` — this file

## How to run locally
1. Download Power BI Desktop (Windows).
2. Open `powerbi/Sales_Analysis.pbix`.
3. If using local CSV, update the data source to `data/sales_data.csv` (Transform Data → Data source settings).
4. Refresh the report.

## Measures (examples)
- `Total Sales = SUM('Sales'[Sales])`
- `Avg Delivery Days = AVERAGE('Sales'[DeliveryDays])`

## Reproduce steps
1. Load the CSV into Power BI.
2. Perform the transformations in Power Query (types, DeliveryDays, YearMonth).
3. Create Date table and connect OrderDate.
4. Add DAX measures and build visuals per report pages.

## License
MIT


## Key metrics (from dashboard)
- Total Sales: **341.01K**
- Total Profit: **27.45K**
- Quantity sold: **5239**
- Avg Delivery Days: **4**

## Key insights (summary)
- Consumer segment contributes ~48% of revenue.
- Standard shipping generates the highest sales (~0.21M).
- Top categories: Office Supplies (0.15M), Furniture (0.11M), Technology (0.09M).
- Top sub-categories: Chairs, Binders, Phones.

## Files
- `data/sales_data.csv` — sample data
- `powerbi/Sales_Analysis.pbix` — Power BI Desktop file
- `notebooks/` — data prep (optional)
- `assets/` — screenshots and GIF
- `README.md` — this file

## How to run locally
1. Download Power BI Desktop (Windows).
2. Open `powerbi/Sales_Analysis.pbix`.
3. If using local CSV, update the data source to `data/sales_data.csv` (Transform Data → Data source settings).
4. Refresh the report.

## Measures (examples)
- `Total Sales = SUM('Sales'[Sales])`
- `Avg Delivery Days = AVERAGE('Sales'[DeliveryDays])`

## Reproduce steps
1. Load the CSV into Power BI.
2. Perform the transformations in Power Query (types, DeliveryDays, YearMonth).
3. Create Date table and connect OrderDate.
4. Add DAX measures and build visuals per report pages.

## License
MIT
