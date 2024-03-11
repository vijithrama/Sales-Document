# Sales-Document
A demo of how to document your DA projects
# Sales Data Analysis
### Dashboard

[Sales Project.pdf](https://github.com/vijithrama/Sales-Document/files/14560512/Sales.Project.pdf)

### Project Overview

This data analysis project aims to provide  insights into the sales performance of a e-commerce company over the past years.By analysing various aspects of the sales data,we seek to identify trends,make data-driven recommendations,and gain a deeper understanding of the company's performance.

### Data Sources
Sales Data :The primary dataset used for this analysis is the "sales_data.csv" file,Containing detailed information about each sale made by the company.

### Tools

-Power BI -Data Cleaning ,Data Analysis,Creating Report [Download here](https://microsoft.com)

### Company Requirements

-Customers can place orders for various products sold by the company online.
-Company delivers the products in least possible time depending upon the customer's address.
-Customers can choose either cash on delivery option or they can pay online while placing the order.
-Company follows 10 days return policy.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in some of the columns has errors & empty values were present .
- Step 5 : Remove the errors in all the fileds and blank spaces .
- Step 6 : Changing data types for required fields and Append four data sets into one column  because of each data sets containing same number of columns and data types.
- Step 7 : Close and apply all the changes then creating viualisation in powerbi desktop.This report consist of 4 pages.
- Step 8 : In the report view ,under the insert tab, using shapes option from elements group a rectangle was inserted to create a title of the report.Two slicers were added for select the customer id to know the 
           specified customer detail and date slicer for user to know company sales for specific time .
  Step 9 : New measure was created to find total number of orders.

            Following DAX expression was written for the same,
        
              Total Number of Orders = DISTINCTCOUNT('Sales Combined'[Order ID])
  
            A card visual was used to represent Total Number  of Orders.

  
  

  ![Screenshot 2024-03-06 162613](https://github.com/vijithrama/Sales-Document/assets/162402373/b9475079-f06a-475e-9a38-c2230b603b83)

  
  
 Step 10 :  New measure was created to find Total Sales.

            Following DAX expression was written for the same,
        
              Total Sales = SUM('Sales Combined'[Sales])
  
            A card visual was used to represent Total Sales.

  ![Screenshot 2024-03-06 162633](https://github.com/vijithrama/Sales-Document/assets/162402373/7797cf25-5fe0-488e-a998-cdd86fcbd12a)


 Step 11 :  Exploratory Data Analysis involved exploring the sales data to create a power BI report to answer the following qouestions,such as:

          -Top/Bottom 5 product by sales.
          -Sales by region.
          -All details about the products ordered  in a given order.
          -Number of orders by time of the day.
          -Number of orders by date.
          -Sales by month.
          -Number of orders by month
          -Top/Bottom 5 product by cost.
          -Five Most & Least ordered products.
          -Relationship between sales and quantity ordered.
      
Step 12 : The report was then published to Power BI Service.

  ![Publish_Message]![Screenshot 2024-03-11 195148](https://github.com/vijithrama/Sales-Document/assets/162402373/f3c7102b-52f4-4b75-92ba-a0d7dbf11ab2)

  # Snapshot of Dashboard (Power BI Service)

![dashboard_snapo]
![Screenshot 2024-03-06 112033](https://github.com/vijithrama/Sales-Document/assets/162402373/6636eb61-b525-44e9-b19d-26b779840896)

# Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload]![Screenshot 2024-03-11 195836](https://github.com/vijithrama/Sales-Document/assets/162402373/6ddda01c-b8ed-4059-ae54-bde1778c6454)

# Insights

A Four page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Orders = 3948

   Total Sales =  $ 780.23 K

   High Number of Orders  =  1078 (27.30) %

   High Order in Month = February

   High Sales by Month = March ( $202 K)

   High Sales by Product = MacBook Pro Laptop ($184 K)

   Lowest Sales = $ 9 K (LG Washing Machine & 20in Monitor)

   High Sales by Region = Los Angels


   

           

