# Online Retail Store Analysis

![](https://github.com/TheGreatFateemah/Online-Sales-Report/blob/main/Online%20store%20image.jpeg)

## Introduction

This is a Power BI project on sales analysis of an online retail store. The project is to provide insights that would be valuable to the CEO and CMO of the business.

## Problem Statement

1. 	Which region is generating the highest revenue, and which region is generating the lowest?
2.	What is the monthly trend of revenue?
3.	Which months generated the most revenue?
4.	Who are the top customers and how do they contribute to the total revenue?

## Skills Demonstrated

-	Data cleaning
-	Quick measure
-	Filters

## Data Transformation

I used Power Query to clean and transform the data.
-	I filtered the quantity and unit price column to remove any value less than 1
-	I changed the data type of the unit price column to decimal
-	I also changed the data type of the customer ID column from number to text to avoid it being summarized in the report
-	I created a Quick measure to calculate revenue (Quantity * Unit Price)

## Modelling

No modelling was required because all the data was contained in one excel sheet.

## Visualization
The report comprises 3 pages:
1.	Monthly trend of revenue in 2011
2.	Revenue by Region
3.	Top customers

You can view the report [here](https://app.powerbi.com/links/4A-P-n-3RX?ctid=05099fa7-fe06-4a4d-8079-3c425fe8734b&pbi_source=linkShare)

## Analysis:

### Monthly Trend of Revenue in 2011:
A total revenue of 8.81M was generated in 2011 with November having the highest revenue and February having the lowest.
Across all 12 months in 2011, the sum of revenue ranged from 462,730.28 to 1.37M. November accounted for 15.54% of total revenue. Revenue in November was 195.92% higher than February.

![](https://github.com/TheGreatFateemah/Online-Sales-Report/blob/main/Monthly-Trend.jpg)

### Revenue by Region:
EIRE(Ireland) generated the highest revenue and Saudi Arabia generated the lowest revenue.

![](https://github.com/TheGreatFateemah/Online-Sales-Report/blob/main/Revenue-by-Region.jpg)

### Top Customers:
The customer with customer ID 18102 generated the highest revenue among the top 10 customers which is 18% of the total revenue generated.

![](https://github.com/TheGreatFateemah/Online-Sales-Report/blob/main/Top-Customers.jpg)

## Conclusions and Recommendation

-	The store should focus on EIRE(Ireland) and check the products that sold well so it can be more focused on.
-	The customers with high revenue should also be compensated so they can continue patronizing. 








