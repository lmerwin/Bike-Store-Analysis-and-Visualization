# Bike Store Data Analysis and Visualization

## Project Scope
Analize the data from the first 2 years of operation for Peakline Bike Co. to uncover sales trends.  Use those findings to create an interactive dashboard that breaks down sales by stores, category, brand, and product into easily comparable tables and charts.

  ###Secondary Scope
  Improve skills in SQL and Excel, and explore the capabilities of Excel

## Process
###Step 1: Use SQL to perform an exploratory data analysis.
The main categories of business questions I wanted to explore were:
  - sales trends
  - shipping trends
  - customer trends

Discoveries:
  - The original data covered years 2016 to 2018, but the 2018 data exhibited some strange inconsistencies
      - Order_status containted numbers 1-4. 1 meaning pending, 2 meaning processing, 3 meaning rejected, and 4 meaning completed
      - For 2018, the orders through the end of March showed a status of completed, while any orders after that date (going all the way through December) showed a status of either pending or processing
      - 
