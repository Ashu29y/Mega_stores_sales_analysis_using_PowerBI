# Mega store Sales Analysis

## Problem Statement

This dashboard helps the  understand their customers  better based on sales report. It also helps in identifying the KPI's , design an interactive and visually appealing dashboard, it add interactive visualizationsand filtering capabilities to allow users to  explore the data at various levels of granularity .

Since, we observe that there is  decline in the total sales in the month of october and november still the profit increases as there maybe some kind of seasonality is present . 

Also since the profit in the month of april decreases which further needs to be analysed and incresed .


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : For calculating column delevery days, we used the DAX query " Delivery_Days = DATEDIFF('SuperStore_Sales_Dataset (2)'[Order Date],'SuperStore_Sales_Dataset (2)'[Ship Date],DAY) " 
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : Visual filters (Slicers) were added for four fields named "North", "South", "West" & "East".
- Step 7 : Four card visuals were added to the canvas, every cards represents the KPI's of the data.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
- Step 8 : A bar chart was also added to the report design area representing various fields as shown in the dashboard_snapo
- Step 9 : In the report view, under the insert two line charts which shows the sales and profit respictively on the monthly basis of two years data i.e. 2019 and 2020 in a same line charts .
- Step 10 : In the next sheet the line charts is used to futher forcaste the sales of mega store for next 30 days.
 - Step 18 : The report was then published to Power BI Service.
 
 
![Publish_Message](https://github.com/Ashu29y/Mega_stores_sales_analysis_using_PowerBI/assets/125810482/22384464-54cd-48ff-80e3-3e7f4d27dfa2)


# Snapshot of Dashboard (Power BI Service)


# Insights

A single page report was created on Power BI Desktop & it was shared on github account.

Following inferences can be drawn from the dashboard;

### [1] sales by Category

   Applied the filter and visualise the top three Category

   Sales of office supplies have the maximum sales worth 0.20 millions , giving the total profit of 33.97 thosand dollars .

   sales of technology = 0.16 M (28.54 thosand dollars profit)

   sales of furnitures = 0.16 M (5.36 thosand dollars profit)
          
### [2] Sales by region
**Central**
    
    a) top performing state : Texas
    b) Total sales : 105.51 thosand dollars
    c) Profit : Non-profitable region

**East**  

    a)  top performing state : New York
    b) Total sales : 117.07 thosand dollars
    c)  Profit : profitable region

 **South**  

    a) top performing state : Florida
    b) Total sales : 72.98 thosand dollars
    c) Profit : Low-profitable region

**West**  

    a) top performing state : California
    b) Total sales : 155.95 thosand dollars
    c) Profit : High-profitable region
  
  ### [3] Average Delivery_Days 
  
      the average delevery days taken to deliver the item is 4 in every region . this is visualised by Usingthe card

 ### [4] Some other insights
 
 4.1) there is  decline in the total sales in the month of october and november still the profit increases as there maybe some kind of seasonality is present .
 
 4.2) Most of the customers prefers standard class delivery mode.
 
 4.3) More than 50% of customers prefers the cash of delivery options .
 

 
 
