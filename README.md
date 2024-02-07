## Sales Transaction Analysis

### Description
This project involves the analysis of sales transaction data conducted at a retail store. The transaction data includes information such as transaction date, payment method, invoice ID, branch, city, customer type, customer gender, product type purchased, unit price, and quantity of items purchased.

### Project Steps
1. **Data Collection and Cleaning:**
   - Transaction data is downloaded from Google Sheets and read using pandas.
   - Data cleaning is performed to handle missing values, outliers, and incorrect formats.
   - The 'Date' column is converted to datetime data type.
   - A new column 'Revenue' is created by multiplying unit price with quantity.

2. **Initial Data Exploration (EDA):**
   - Distribution and summary statistics of each column are examined.
   - Spelling errors in the 'Gender' column are identified and corrected.
   - Visualizations are performed to understand the number of transactions by payment method, branch, city, customer type, customer gender, and product type.

3. **Daily Trend Analysis:**
   - Data is aggregated by date to observe daily trends in revenue and quantity of items sold.
   - Daily trends are visualized using line plots.

4. **Payment Analysis:**
   - Data is aggregated by payment method to view total revenue and number of transactions for each payment method.
   - Visualizations are created using bar plots to compare total revenue from each payment method.

5. **Gender and Product-Based Analysis:**
   - Data is aggregated by gender and product type to observe the number of transactions (invoices) for each combination of gender and product type.
   - Visualizations are created using bar plots with hue based on gender to compare the number of transactions based on product type.

### Libraries and Usage
This project utilizes libraries such as pandas, numpy, matplotlib, and seaborn for data analysis and visualization. Transaction data is read from Google Sheets and stored in DataFrame format. Visualizations are created using various types of plots including line plots, bar plots, and pie charts.

### About the Data
The sales transaction data contains information on over 1000 transactions conducted over a certain period of time. Each transaction includes details such as transaction date, payment method, branch, city, customer type, customer gender, product type purchased, unit price, and quantity of items purchased. The analysis aims to provide insights into customer purchasing patterns, sales performance, and customer preferences based on product type and gender.
