# Athletic_Sales_Analysis

In this project, I analyzed athletic sales data to uncover trends and patterns. The analysis includes data such as product types, retailers, regions, states, and cities. By examining the, I aimed to provide valuable insights into the sales performance of different categories and regions. I was provided assistance by Sean Morey, the instructor of the class. Brandon Wong, a BCS tutor, was a big help. I lastly could not have been able to finish this code without the help from the BCS Xpert Learning Assistant.

# Data Description

The datasets contain sales information for various athletic products from 2020 and 2021. The key columns used in the analysis are:

* retailer: The name of the retailer.
* region: The geographical region of the sales.
* state: The state where the sales occurred.
* city: The city where the sales occurred.
* product: The type of product sold.
* units_sold: The number of units sold.
* total_sales: The total sales amount.
* invoice_date: The date of the sale.
* sales_method: The method of sale (e.g., In-store, Online, Outlet).

# Analysis Steps

* Data Loading
    - I started by loading the sales data for 2020 and 2021 into Pandas DataFrames.

* Data Cleaning
    - Checked for null values and data types.
    - Converted the invoice_date column to a datetime datatype for accurate time-series analysis.

* Data Aggregation
    - Combined the 2020 and 2021 sales data into a single DataFrame.
    - Calculated the total products sold for each region, state, and city.
    - Calculated the total sales for each region, state, and city.

* Filtering Specific Data

    - To gain insights into specific categories, I filtered the data for women's athletic footwear sales. This allowed me to focus on analyzing trends within this particular product category.

* Creating Pivot Tables
    - Created pivot tables to show the number of products sold and total sales for each retailer, region, state, and city.
    - Generated pivot tables with invoice_date as the index and total_sales as the values to analyze time-series data.

* Resampling
    - Resampled the pivot tables into daily and weekly bins to get the total sales for each day and week.
    - Sorted the resampled data in descending order of total sales to identify the highest sales periods.

# Results

The analysis produced several key insights:

* Total Products Sold by Region, State, and City: Summarized the total number of units sold across different regions, states, and cities.
* Total Sales by Region, State, and City: Summarized the total sales amount across different regions, states, and cities.
* Women's Athletic Footwear Sales: Provided a detailed analysis of women's athletic footwear sales, showing the top-performing regions, states, cities, and retailers.
* Daily and Weekly Sales Trends: Identified sales trends by resampling the data into daily and weekly bins, highlighting peak sales periods.