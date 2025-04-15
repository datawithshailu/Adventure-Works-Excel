# Adventure Works Sales Dashboard

This repository contains an Excel-based dashboard built using the Adventure Works Cycles sample database. Adventure Works Cycles is a multinational company that manufactures and sells metal and composite bicycles to commercial markets in North America, Europe, and Asia. This dashboard consolidates and visualizes sales and financial data to help analyze company performance across multiple metrics.

## Project Overview

The goal of this project is to create an interactive dashboard that provides insights into Adventure Works Cycles’ sales and financial performance. By integrating data from multiple sources, the dashboard allows users to perform detailed analysis on sales, profits, product performance, and regional breakdowns.

### Features:
- Year-wise sales analysis with Top 5 markets by sales.
- Quarter-wise sales analysis in a pie chart.
- Month-wise sales trend displayed in a line chart.
- Top 5 products by region in a bar chart.
- Top 5 customers by region, with a bar-line chart showing product counts and profit.
- Combination chart displaying sales amount and product standard cost for each month.
- Key metrics such as total sales, total profit, and average sales by region.
- Two interactive slicers for filtering data by year and region.

## Data Sources

The dashboard pulls data from the following sheets:
- **Fact Internet Sales**: Contains transactional sales data, including product IDs, order quantity, unit price, and unit discount.
- **Product**: Provides product-related data such as product name, unit price, and product standard cost.
- **Customer**: Includes customer details like full name, region, and customer ID.
- **Date Key**: Contains date-related information, which is used to calculate metrics by time (year, quarter, month, etc.).

## Key Features and Visualizations

1. **Top 5 Markets Year-Wise Bar Chart**:
   - This bar chart displays the top 5 markets based on sales for each year, enabling easy comparison across years.

2. **Quarter-Wise Sales Pie Chart**:
   - A pie chart showing the sales distribution across different quarters of the year.

3. **Month-Wise Sales Line Chart**:
   - A line chart that tracks monthly sales trends, offering a clear view of sales fluctuations over time.

4. **Top 5 Products by Region**:
   - A bar chart that shows the top 5 products by region based on sales, helping identify the most popular products in each region.

5. **Top 5 Customers by Region Bar-Line Chart**:
   - A combined bar and line chart displaying the top 5 customers by region. The bar shows the count of product names, while the line represents the sum of profit for those customers.

6. **Combination Chart of Monthly Sales and Product Standard Cost**:
   - A combination chart that visualizes both the total sales amount and the sum of product standard costs for each month.

7. **Year-Wise Bar Chart**:
   - A bar chart visualizing total sales year-wise, offering a clear overview of sales trends across multiple years.

8. **Key Metrics for Regions**:
   - Metrics for total sales, total profit, average sales, and total number of sales, broken down by region. These help assess regional performance in various key areas.

9. **Slicers for Year and Region**:
   - Two slicers have been added to the dashboard to filter data by year and region. These slicers provide a more interactive and dynamic experience.

## How to Use the Dashboard

1. Open the `Adventure_Works_Sales_Dashboard.xlsx` file in Excel.
2. Use the slicers to filter the data by **Year** and **Region**.
3. Review the various visualizations:
   - The **Top 5 Markets Year-Wise Bar Chart** will show the best-performing markets for each year.
   - The **Quarter-Wise Sales Pie Chart** will display the sales distribution by quarter.
   - The **Month-Wise Sales Line Chart** will track sales over time.
   - Explore the **Top 5 Products by Region** and **Top 5 Customers by Region** to understand product and customer performance.
   - Use the **Combination Chart** to compare sales amounts and product standard costs.
4. Analyze the **Year-Wise Bar Chart** and **Key Metrics by Region** to understand overall and regional performance.
5. Refresh the data and pivot tables when new data is added to ensure the dashboard remains up-to-date.

## Contributing

If you would like to contribute to this project, you are welcome to fork the repository, make changes, and submit a pull request. Feel free to suggest new charts, features, or improvements for the dashboard!



