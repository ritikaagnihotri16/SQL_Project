# Data Analysis with SQL

## ABOUT

Objective of this project is to explore the Walmart Sales data to understand top performing branches and product lines, sales trend of different products, customer behavior. Aim is to draw insights from exploratory data analysis with SQL. The dataset was obtained from the Kaggle.

## PURPOSE
Purpose of this project is to draw insights from exploratory data analysis with SQL.
Aim is to gain insights into the sales data of Walmart to understand the different factors that affect sales of the different product lines and branches. 

## ABOUT DATA
The dataset was obtained from Kaggle. This dataset contains sales transactions from a three different branches of Walmart, respectively located in Mandalay, Yangon and Naypyitaw. The data contains 17 columns and 1000 rows.

## Data Analysis 

1. Product Analysis

> Conduct analysis on the data to understand the different product lines performance, revenue trends over time.

2. Sales Analysis

> This analysis aims to answer the question of the sales trends of product. The result of this can help use measure the effectiveness of each sales strategy the business applies and what modificatoins are needed to gain more sales.

3. Customer Analysis

> This analysis aims to uncover the different customers segments, purchase trends and the profitability of each customer segment.


## Project Steps

1. **Data Wrangling:** This is the first step where inspection of data is done to make sure **NULL** values and missing values are detected and data replacement methods are used to replace, missing or **NULL** values.

> 1. Build a database
> 2. Create table and insert the data.
> 3. Select columns with null values in them. There are no null values in our database as in creating the tables, we set **NOT NULL** for each field, hence null values are filtered out.

2. **Feature Engineering:** This will help use generate some new columns from existing ones.

> 1. Add a new column named `time_of_day` to give insight of sales in the Morning, Afternoon and Evening. 

> 2. Add a new column named `day_name` that contains the extracted days of the week.

> 3. Add a new column named `month_name` that contains the extracted months.


## Business Questions To Answer

### Generic Question

1. How many unique cities does the data have?
2. In which city is each branch?

### Product

1. How many unique product lines does the data have?
2. What is the most common payment method?
3. What is the most selling product line?
4. What is the total revenue by month?
5. What month had the highest COGS?
6. What product line had the highest revenue?
5. What is the city with the highest revenue?
6. What product line had the highest VAT?
7. Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales
8. Which branch sold more products than average product sold?
9. What is the most common product line by gender?
12. What is the average rating of each product line?
13. What product line has highest profit? 

### Sales

1. Number of sales made in each time of the day per weekday
2. Which of the customer types brings the most revenue?
3. Which city has the highest tax percent/ VAT (**Value Added Tax**)?
4. Which customer type pays the most in VAT?

### Customer

1. How many unique customer types does the data have?
2. How many unique payment methods does the data have?
3. What is the most common customer type?
4. Which customer type buys the most?
5. What is the gender of most of the customers?
6. What is the gender distribution per branch?  
7. What customer type is more satisfied with product (rating)?


