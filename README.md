# Home Sales Data Analysis Project
![Home Sales](image/home_sales.jpg)
In this project, I will utilize my knowledge of SparkSQL to analyze and derive key insights from home sales data. I will perform various tasks, including creating temporary views, partitioning data, caching and uncaching tables, and more, to answer specific questions about the dataset.

## Project Instructions

1. **Rename Notebook**: I'll start by renaming the `Home_Sales_starter_code.ipynb` file to `Home_Sales.ipynb`.

2. **Import Libraries**: I will import the necessary PySpark SQL functions for this assignment, ensuring I have the appropriate libraries available.

3. **Data Loading**: I'll read the `home_sales_revised.csv` data provided in the starter code into a Spark DataFrame using the appropriate PySpark SQL functions.

4. **Creating a Temporary Table**: Next, I'll create a temporary table called `home_sales` from the DataFrame.

5. **Answer Questions with SparkSQL**: I will utilize SparkSQL to answer the following questions, rounding off my answers to two decimal places:
   - What is the average price for a four-bedroom house sold for each year?
   - What is the average price of a home for each year it was built that has three bedrooms and three bathrooms?
   - What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?
   - What is the "view" rating for homes costing more than or equal to $350,000? I will determine the run time for this query and round off my answer to two decimal places.

6. **Caching**: I will cache my temporary table `home_sales` and verify if it is cached.

7. **Query with Cached Data**: Using the cached data, I will run the query that filters out the view ratings with an average price of greater than or equal to $350,000. I'll determine the runtime and compare it to the uncached runtime.

8. **Partitioning Data**: I will partition the formatted Parquet home sales data by the "date_built" field.

9. **Creating a Temporary Table for Parquet Data**: I'll create a temporary table for the Parquet data and validate it.

10. **Query on Parquet Data**: I will run the query that filters out the view ratings with an average price of greater than or equal to $350,000 on the Parquet data. I'll determine the runtime and compare it to the uncached runtime.

11. **Uncaching the Temporary Table**: Finally, I will uncache the `home_sales` temporary table and verify that it is uncached using PySpark.

## Dataset Used

- [Home Sales](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv)

## Getting Started

 - Clone the Git Hub Repo: Home_Sales
 - Assess the code via: [Home_Sales.ipynb](Home_Sales.ipynb) 
 - Run the code