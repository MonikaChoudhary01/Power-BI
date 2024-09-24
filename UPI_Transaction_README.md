# UPI Transaction Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)


### Project Overview
This data Analysis Project aim to provide insight into the UPI over the past year.
By analyzing various aspacts we seeks to identify the trends and make data driven recommandations and gain deeper understanding of UPI emergence.

### Data source
 UPI Transaction Data : The Primary data is been used for this projects in upi_transaction.csv , containing information for upi transaction .


### Tools:
- Excel -  Data Cleaning [Download Here()]
- Postgres server - Data Analysis
- Power BI - Creating Reports

### Data Cleaning and Preperation :
In the initial phase of data cleaning we perform below tasks:
1. Data Loading and inspection
2. Handling missing values
3. Data Cleaning and formatting


### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:
- What is the overall sales trend?
- Which products are top sellers?
- What are the peak sales periods?

### Data Analysis

Include some interesting code/features worked with

```sql
SELECT * FROM table1
WHERE cond = 2;
```

- What is the overall sales trend?
- Which products are top sellers?
- What are the peak sales periods?


### Results/Findings

The analysis results are summarized as follows:
1. The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
2. Product Category A is the best-performing category in terms of sales and revenue.
3. Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.

### Recommendations

Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue.
- Focus on expanding and promoting products in Category A.
- Implement a customer segmentation strategy to target high-LTV customers effectively.

### Limitations

I had to remove all zero values from budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue.

### References

1. SQL for Businesses by werty.
2. [Stack Overflow](https://stack.com)



### Data Analysis
Include some interesting code/features worked with
