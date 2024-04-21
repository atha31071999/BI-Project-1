
# Adventure Works Bike Shop-Dashboard

### Dashboard Link :
https://app.powerbi.com/groups/me/reports/d4362ef2-db01-4b0b-9f5a-82d819a4b640/ReportSection?experience=power-bi&bookmarkGuid=Bookmarkab1b68cc75e824828834

## Problem Statement

This dashboard helps the Adventure Works understand their customers better. It helps the Adventure Works know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the total orders, total revenue, return rates & profit, thus since by using this dashboard they have identified this problem, they can further work on factors responsible for these unwanted returns.


Also since return rate is 2.17% of the total sales thus they must try to reduce it.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.

- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".

- Step 4 : Removed the errors and blank spaces from the tables.

- Step 5 : Created new measures which contails the DAX for implementing the KPIs such as Total Revenue,Total Profit, Total Returns, Total Distinct Customers, Total Cost, Average Revenue per customer, Return Rate. For calculating various fields and cloumns made use of Aggregation Functions(SUM, AVERAGE,MIN,MAX,COUNTA,etc), Logical functions(IF,AND,etc), Text Functions(CONCATANATE,UPPER,LOWER,etc) ,Date and Time functions(DATE, MONTH, YEAR, DAY,etc) and Time Intelligence functions(TOTALYTD,DATESINPERIOD,TOTALMTD,etc).

- Step 6 :Created Date Hirerchy for calender look up table for start of year, start of month and start of day with respect to sales(monthly, yearly, daily). 

- Step 7 : Created visual reports for 1) Executive dashboard which focus on the main KPIs which are more suitable for the executives. 2) Customer Details view, which focuses on the customer purchases and the KPis like total customers and revenue per customer along with top customer on the basis of total orders and revenue.3) Product details view, which focuses on the product details such as sale of a specific product and return and profit of that particular product.4) Maps view, which highlights the total orders for particular regions on the map.

- Step 8 : Advanced customized Tooltip is added for the sales by order category.

- Step 9 : For exec Dashboard 4 KPIs are added Total Revenue, Orders, Profit, Return Rate.Line chart is added to showcase the monthly revenue trending.Cards are added to show the most ordered and most returned product.KPI cards to show monthly orders, monthly revenue and monthly returns are also added.
           
           
- Step 10 : In customer Details view KPI for revenue per customer and total customers is added along with the list slicers to filer with year and tile slicer to filter Total customer and revenue per customer on the line chart which is added to show the Total customers(Monthly,yearly, daily) with date hirerchy along with zoom slider.Top customer based on revenue along with its total orders and total revenue is also displayed.Two donut charts are also added to show the order by Occupation and ordr by income level.

- Step 11 : A map is added for the country visibility for the total orders. Also, the tile slicer is added to filter the continents for the total orders.

- Step 12 : For the product view the Area charts are added to show the returns trend profit trend for the products.Gauge meter is added to highlight the monthly orders vs target, monthly revenue vs target and monthly profit vs target.

- Step 13 : A rectangle is added to each view wich contains the buttons along with bookmarks to jump to the other views like customer details, product details, maps.

- Step 14 : A filter button is added to the exec dashboard to open the rectangle containing the slicers that filters the report based on the year and continents.

        
- Step 15 : Drill up and drill down filters are present in each line chart and area charts.
        
 - Step 16 : Added a category Tooltip ehich is an advanced customized tooltip showing total orders, total revenue, profit, total returns, return rate on the orders by category clustered bar chart on the exec dashboard view.
 
 ### Snapshots for the dashboard 
 
Find below the snapshots for each view from the adventure Works file-

 ### Executive Dashboard

![Executive Dashboard](https://github.com/atha31071999/Test/assets/81071748/d0901fc7-d98a-4994-a1e7-919f836d1ad5)


### Customer Details

![Customer Details](https://github.com/atha31071999/Test/assets/81071748/1451b12e-bd9f-4a26-a0f8-42571ed5db69)


### Maps

![Maps](https://github.com/atha31071999/Test/assets/81071748/df27d075-f644-4ee8-a54c-ae32ba084f72)


### Product Details

![Product Details](https://github.com/atha31071999/Test/assets/81071748/a444f617-6134-4f5f-8e83-1da24f20d9fe)


### Customized Tooltip

![Advanced Tooltip](https://github.com/atha31071999/Test/assets/81071748/ff568ade-bc70-428f-b15d-c724bf2e1683)
