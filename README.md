# Bike Store Data Analysis and Visualization

## Project Scope
Analize the data from the first 2 years of operation for Peakline Bike Co. to uncover sales trends.  Use those findings to create an interactive dashboard that breaks down the data into easily comparable cahrts and tables.

  ### Secondary Scope
  Improve skills in SQL and Excel, and explore the capabilities of Excel.

## Process
### Step 1: Use SQL to perform an exploratory data analysis.
The main categories of business questions I wanted to explore were:
  - sales trends
  - shipping trends
  - customer trends

Discoveries:
The original data covered years 2016 to 2018, but the 2018 data exhibited some strange inconsistencies.
  - The order_status column containted numbers 1-4. 1 meaning pending, 2 meaning processing, 3 meaning rejected, and 4 meaning completed.
  - For 2018, the orders through the end of March showed a status of completed, while any orders after that date (going all the way through December) showed a status of either pending or processing.
To proceed, I chose to assume that the data was recorded during 2018 making that year incomplete. Therefore my analysis covers 2016 and 2017 being the two complete years of data available.

### Step 2: Prepair the data for visualizaiton
Since this data did not need additional cleaning, I simply used SQL to join the necessary columns into a tabular format to import into Excel. I chose to focus my dashboard on sales from 2016 and 2017.

### Step 3: Visualize the data
1. Aggregated the data using pivot tables focusing on the general groupings:
   - sales by year
   - sales by catagory
   - units sold by category
   - sales by brand
   - units sold by brand
   - top products by sales and units sold
   - year over year growth
   - month over month growth
Apply filters when necesaary to improve the readability of each section.

2. Created slicers for breaking down the data further and focus in on:
   - store
   - category
   - brand
   - month

3. Calculated growth and created charts based on the data from the pivot tables.
   
4. Linked the data from the working page to the dashboard page.  Used formulas and formatting to acheive the desired look.

## Takeaway
Excel is by no means the best program for designing dashboards, but I gained valuble knowledge about it's capabilities particularly when it comes to formatting.

## Dashboard Functionality
To control the dashboard, use the splicer buttons to filter the data.
- to select multiple buttons, click and drag to select buttons next to eachother OR hold ctrl and click to select buttons that are not next to eachother.
    - dashboard will update once you let go of the mouse and/or the cntl button.
The "stores", "categories", and "brands" slicers control all of the tables and charts, the month slicer control everything but the charts.
Slicer options will go away if they are not available under a certain filter, the will reappear when more buttons are selected.
When all the buttons are highlighted, you are seeing the overall company sales data for all months, all brands, all categories, and all stores.

** The download file shows only the dashboard sheet, the working sheet and data source can be "unhidden" if needed


