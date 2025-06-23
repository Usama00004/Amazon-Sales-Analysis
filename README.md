# Amazon Sales Analysis - Power BI Project

## Project Overview

This Power BI project analyzes **Amazon sales data** from an Excel sheet and showcases the use of various **Time Intelligence functions** to gain insights into sales trends over time. The goal is to uncover valuable business insights such as sales growth, seasonal patterns, and year-over-year comparisons.

## Data Source

- **File**: `Amazon_Sales_Data.xlsx`
- **Contents**:
  - Order Date
  - Product Category
  - Sales Amount
  - Quantity
  - Customer Info
  - Region

## Objectives

- Visualize Amazon sales performance over time.
- Apply Time Intelligence DAX functions to:
  - Calculate YTD (Year-To-Date), QTD (Quarter-To-Date), MTD (Month-To-Date) metrics.
  - Compare current and previous periods (e.g., YoY, MoM growth).
  - Analyze moving averages and cumulative totals.
  - Identify seasonal trends and peak sales periods.

## Time Intelligence Functions Used

| Function       | Purpose                         |
|----------------|----------------------------------|
| `TOTALYTD()`   | Calculates year-to-date values.  |
| `TOTALMTD()`   | Calculates month-to-date values. |
| `TOTALQTD()`   | Calculates quarter-to-date values.|

## Key Visuals

- Sales Trend Line Chart (Monthly & Yearly)
- Year-over-Year Comparison
- Cumulative Sales Analysis
- Top Selling Categories by Time Period
- Heat Map of Sales by Region and Time

## Tools & Technologies

- Power BI Desktop
- Microsoft Excel
- DAX (Data Analysis Expressions)

## How to Use

1. Clone this repository or download the `.pbix` file.
2. Open Power BI Desktop.
3. Load the `Amazon_Sales_Data.xlsx` file.
4. Refresh the data model.
5. Explore the report pages to interact with visuals and filters.

## Notes

- Ensure your system has Power BI Desktop installed.
- Excel file must remain in the same path or be reconnected via **Transform Data > Data Source Settings** if moved.
- All date-related calculations rely on a properly formatted Date Table.

## Contact

For questions or feedback, feel free to reach out:

**Your Name**  
usamatahir00004@gmail.com
