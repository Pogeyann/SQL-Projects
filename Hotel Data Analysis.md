# Data Analysis project

# HOTEL DATA ANALYSIS

I am developing a Database to Analyze and Visualize Hotel Booking Data 

Requirements:-

Build a visual story or dashboard using PowerBi to present to your stakeholders

* Is our hotel revenue growing by year?
 
  we have two hotel types so it would be good to segment revenue by hotel type.
 * Should we increase our parking lot size?
 
   we want to  understand if there is a trend is guest with personal cars
  * What trends can we see in the data?
    
    Focus on average daily rate and guests to explore seasonality
   
   Here's the Data analysis project pipeline
   
   * Build a Database
   * Develop the SQL query
   * Connect Power BI to the database
    
  1. <ins>Building a Database</ins>
  we have hotel datas of 2018 and 2019.
  * At first Open Microsoft SQL server studio ,Create a database & name project
  * In database project right click and go to tasks and then import data
  * choose **Data source** Microssoft excel ,then browse our data and choose microsoft excel 2016
  * select sql server client 11.0 and then select a copy from all tables
  * Here select all datas and Run immediately
  * Now we have created our database and brought table inside,& these tables in SQL form
  * we gonna navigate to new query, and exploring the data using SQL
  * Union three tables ![image](https://user-images.githubusercontent.com/109593081/211749492-aa86d42a-ea68-4a60-a055-48883a225953.png)
* adding 2 columns
* Connecting powerBI using sql server database -![image](https://user-images.githubusercontent.com/109593081/211766733-ce589f6f-7a89-4f53-b619-9d0da458b7f2.png)
* created hotel - ![image](https://user-images.githubusercontent.com/109593081/211794334-33aabfb0-a136-4025-953e-1f5d54380004.png)

* Performed ETL 
![image](https://user-images.githubusercontent.com/109593081/211794921-1779415f-564b-40e1-b07c-8e164f3ba9ae.png)
* Created new column using calculated fields,Using Transform fields - ![image](https://user-images.githubusercontent.com/109593081/211795263-144e4209-df12-4427-a442-16ac84b30b49.png)
* Created new measures in report

parking percentage = SUM(Query1[required_car_parking_spaces])/[Total nights]

Total nights = sum(Query1[stays_in_week_nights])+SUM(Query1[stays_in_weekend_nights])
* PowerBI Dashboard created ![image](https://user-images.githubusercontent.com/109593081/211798304-44211a73-922c-4f00-b163-c3c2d0012e38.png)


Submission file [Hotel Data Analysis](Hotel analysis.pbix)

