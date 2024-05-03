Home Sales Data Analysis

### Introduction
In this challenge, you'll utilize SparkSQL to extract key metrics from home sales data. You'll create temporary views, partition the data, cache and uncache a temporary table, and verify the caching status.

### Before You Begin
1. Create a new repository named Home_Sales for this project.
2. Clone the repository to your local machine.
3. Push your changes to GitHub.

### Files
Download the necessary files from the following link: [Module 22 Challenge files](#) (Links to an external site).

### Instructions
1. Rename the provided `Home_Sales_starter_code.ipynb` file to `Home_Sales.ipynb`.
2. Import the required PySpark SQL functions.
3. Read the `home_sales_revised.csv` data into a Spark DataFrame.
4. Create a temporary table named `home_sales`.
5. Answer the following questions using SparkSQL:
    - **Average Price for Four-Bedroom Houses:** Determine the average price for a four-bedroom house sold each year.
    - **Average Price of Homes Built Each Year:** Calculate the average price of homes built each year, having three bedrooms and three bathrooms.
    - **Average Price of Homes with Specific Attributes:** Find the average price of homes built each year, with specific attributes such as three bedrooms, three bathrooms, two floors, and a size of at least 2,000 square feet.
    - **Average Price per "View" Rating:** Calculate the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Measure the runtime for this query.
6. Cache the temporary table `home_sales`.
7. Check if the temporary table is cached.
8. Using the cached data, rerun the query for calculating the average price per "view" rating having an average home price greater than or equal to $350,000. Measure the runtime and compare it with the uncached runtime.
9. Partition the formatted parquet home sales data by the "date_built" field.
10. Create a temporary table for the parquet data.
11. Rerun the query for calculating the average price per "view" rating having an average home price greater than or equal to $350,000 using the parquet data. Measure the runtime and compare it with the uncached runtime.
12. Uncache the `home_sales` temporary table.
13. Verify that the `home_sales` temporary table is uncached using PySpark.

### Conclusion
Download your completed `Home_Sales.ipynb` file and upload it to your "Home_Sales" GitHub repository.
