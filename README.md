# credit_card_financial_dashbaord
## Project Objective: 
To develop a comprehensive credit card weekly dashboard that provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations effectively.

## Dataset: 
Financial Dataset

## Steps

### Step 1: Data Cleaning in Excel
We began by cleaning the raw data in Excel, addressing issues such as inconsistent date formats and other data anomalies. This step ensured that our dataset was consistent and ready for further analysis.

### Step 2: Loading Data into MySQL Database (ccdb1)
Once the data was cleaned and formatted appropriately, we loaded it into our MySQL database named ccdb1. This allowed us to centralize our data storage and access it efficiently for further processing.For this we created tables in datbase and created columns same as the csv file.Afte that we load the data in the tables.

### Step 3: Data Transformation and Enrichment in Power BI
Using Power BI, we connected to the ccdb1 database and retrieved the cleaned dataset. Through the power of DAX (Data Analysis Expressions), we performed additional data transformations and created new calculated columns necessary for our visualization needs.

### Step 4: Dashboard Creation
We had created two comprehensive dashboards: 
 
Credit Card Customer Report:
It consists 
KPI(Revenue,Total Interest, Income, CSS[Customer Satisfaction Score]), 
Slicier(Quarter,Week_start_day, Gender,Card Type, Card Category)
Vizualizations(Revenue by card week[Line Chart], Revenue by AgeGroup[BarChart], Revenue by Income[Bar Chart], Revenue by Marital Status[Bar Chart], Revenue by Education[Bar Chart],Revenue by Depedents[Bar Chart], Top 5 States [BarChart] and a table/matrix)
   
  
Credit Card Transaction Report:
KPI(Revenue,Total Interest, Txn Amt, Txn Count) 
Slicier(Quarter,Week_start_day, Gender,Card Category)
Vizualizations(Revenue by card Type[Bar Chart], Revenue by Job[Bar Chart], Qtr Revenue and Total Txn Count[Col & Line Chart], Revenue by Expenditure Type [Bar Chart],Revenue by Education[Bar Chart],Revenue by Card Category [Bar Chart] and a table/matrix)

##Now the dashbaord and insights are ready to share with stakeholders and to make inform decision
