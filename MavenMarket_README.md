Maven Market
Dashboard Link :
https://app.powerbi.com/view?r=eyJrIjoiMTIyZThmMWUtNWM4Ny00MDcyLWJiZTQtMjI2MmUyYThhMmJkIiwidCI6IjJjNTQ5N2QzLTg3NjQtNDBiNy05OGM3LTRjYjY0NjJjZDgyZiJ9

Problem Statement
Maven Market, a multi-national grocery chain with locations in Canada, Mexico and the United States.Created a dashboard which shows the top 30 transactions based on product brand along with the profit, returns and other important KPIs.

Steps followed
Step 1 : Load data into Power BI Desktop, dataset is a csv file.

Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".

Step 4 : Removed the errors and blank spaces from the tables.

Step 5 : Created new measures which contains the DAX for implementing the KPIs such as Total Revenue,Total Profit, Total Returns, All Transactions, Last month revenue, profit and returns, Weekend trasnactions, YTD revenue, etc. For calculating various fields and cloumns made use of Aggregation Functions(SUM, AVERAGE,MIN,MAX,COUNTA,etc), Logical functions(IF,AND,etc), Text Functions(CONCATANATE,UPPER,LOWER,etc) ,Date and Time functions(DATE, MONTH, YEAR, DAY,etc) and Time Intelligence functions(TOTALYTD,DATESINPERIOD,TOTALMTD,etc).

Step 6 :Created Date Hirerchy for calender look up table for start of year, start of month and start of day with respect to sales(monthly, yearly, daily).

Step 7 : Created visual reports showcasing the main KPI cards i.e. Current month Transactions, current month profit and current month returns.

Step 8 : Created a matrix to visualize the top 30 total transactions with Top N filters based on product brands along with the Profit margin,Total profit and return rate for the same product brands.

Step 9 : Added a map to highligh the total transactions for all 3 countries i.e. USA, Canada and Mexico. Also, added the country level slicer for the report.

Step 10 : Added a column chart for weekly revenue trending which shows the total revenue at the start of the week.

Step 11 : Added a Gauge to show the revenue vs target indicator.

Snapshots for the dashboard
Find below the snapshots for the Maven Market full Report Dashboard -

![Screenshot 2024-05-05 221356](https://github.com/atha31071999/BI-Project-1/assets/81071748/af8a9876-b78e-483c-a60a-8f1e8e660ccb)
