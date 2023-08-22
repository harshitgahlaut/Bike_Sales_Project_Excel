# Bike_Sales_Project_Excel

## Project Description
In this project, I have analysed a bike company's data to understand different factors that are considered by the customers before making a purchase decision. The final output of this project is a dashboard which provides a comprehensive overview of bike sales data, allowing stakeholders to analyse trends, identify patterns, and make informed decisions.

**__Disclaimer__** : _All datasets and reports do not represent any institution comapny or country and is just a dummy dataset to demonstrate Excel capabilities._
## Data Sourcing
After downloading  the dataset file in Excel format, we start by creating 3 new sheets:
1.	"Working" sheet: a copy of the original data where we can perform all the cleaning procedures, without worrying about transforming or even losing our raw table,
2.	"Pivot Calculation" sheet: where we create Pivot Tables according to our need
3.	"Dashboard" sheet: where we insert the visualizations of our analysis as well as the slicers to filter our data

## Data Cleaning and Transformation
This stage began with getting to know the dataset and checking for any data quality issues.
1.	Removing duplicates, unwanted cells and irrelevant columns
2.	Replacing values with more meaningful entries  using FIND and REPLACE functions
eg: M with Married in the "MaritalStatus" column,
    F with Female in the "Gender" column
  	etc
3.	Changing the data type of "Income" column to currency
4.	Creating a conditional column based on the "Age" column to make out 3 different age brackets.using NESTED IF function.

## Data Analysis
Five pivot tables were created to summarise the data and help identify trends in the dataset focusing on relationship between Bike Purchase and other factrs such as Average Income, commute distance, Profession Home ownership and age.
Below is a snippet of the pivot tables in Excel.
![]()

## Data Visualization
Finally, the dashboard was created by inserting and  customizing the pivot charts of corresponding  pivot table.
For user friendly and interactive experience  3 "Slicers" were added.
Below is a snippet of the final dashboard in Excel.
![]()

## Insights
From the analysis, we get to know the following information about bike purchasers:
- Both Male and female with higher average income in their respective category were more likely to purchase bike
- The majority of bike purchasers were in the 31-54 year age bracket i.e the Middle Age group
- People with a 0-1 MILE COMUTE WERE MOST LIKELY TO PURCHASE a bike FOLOWED BY  2-5 mile 
- People with a 5+ mile commute were more likely not to purchase a bike
- Homeowners were more likely to purchase bike
- Professionals formed  the majority of the bike customers

## Recommendations based on the Analysis
- Middle Age Group (31-54) shows the highest number of purchases. The management should ensure that it should target this segmen of population.
- An inverse linear relationship indicates that as the commuters' distance increases, they prefer other means of transportation other than bike riding so the company should focus on short distance commuters

## End
Thank you for your time. Feel free to give your valuable suggestions and connect with me on
https://www.linkedin.com/in/harshitt-gahlaut/
