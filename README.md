# Ecommerce_Spreadsheet_Project

## Objective: To determine how product page views are converting into purchases.
- <a href="https://docs.google.com/spreadsheets/d/1-ARTIDR_mRWiSXeE4reG6Qy204XO6raobcEHZoXy-So/edit#gid=38637670">Table of Contents</a>
- <a href="https://docs.google.com/spreadsheets/d/1-ARTIDR_mRWiSXeE4reG6Qy204XO6raobcEHZoXy-So/edit#gid=868644233">Executive Summary</a>
- <a href="https://docs.google.com/spreadsheets/d/1-ARTIDR_mRWiSXeE4reG6Qy204XO6raobcEHZoXy-So/edit#gid=837599767">Conversion Funnel</a>
- <a href="https://docs.google.com/spreadsheets/d/1-ARTIDR_mRWiSXeE4reG6Qy204XO6raobcEHZoXy-So/edit#gid=616309302">Purchase Activity</a>
- <a href="https://docs.google.com/spreadsheets/d/1-ARTIDR_mRWiSXeE4reG6Qy204XO6raobcEHZoXy-So/edit#gid=1338259763">First Purchases</a>
- <a href="https://docs.google.com/spreadsheets/d/1-ARTIDR_mRWiSXeE4reG6Qy204XO6raobcEHZoXy-So/edit#gid=1923023327">Cohort Analysis</a>
- <a href="https://docs.google.com/spreadsheets/d/1-ARTIDR_mRWiSXeE4reG6Qy204XO6raobcEHZoXy-So/edit#gid=339269775">Retention Rates</a>
- <a href="https://docs.google.com/spreadsheets/d/1-ARTIDR_mRWiSXeE4reG6Qy204XO6raobcEHZoXy-So/edit#gid=0">Raw User Activity</a>
- <a href="https://docs.google.com/spreadsheets/d/1-ARTIDR_mRWiSXeE4reG6Qy204XO6raobcEHZoXy-So/edit#gid=967348360">Change Log</a>

### Analysis Completed:
#### Part 1: Built a conversion funnel to better understand how users interact with the website.
- Using data from the “raw_user_activity” sheet, created funnel in a pivot table as a new sheet called “conversion_funnel”.
- Counted the unique users for each stage of the funnel.
- Used formulas to create two new columns in pivot table: total conversion rates and conversion rates.

![image](https://github.com/tloo921/Ecommerce_Spreadsheet_Project/assets/156555400/5381475f-c51b-4cfa-a3a4-b643f7f99d41) 


#### Part 2: Built acquisition cohorts based on the month of a user’s first purchase, and tracked cohort metrics month by month.
- Created a new blank sheet tab called “purchase_activity”.
- Used the filters in the “raw_user_activity” sheet, selected only event types that are purchases.
- After applying the filter, copied the entire sheet and pasted the data into “purchase_activity” sheet.
- Using the “purchase_activity” sheet data, inserted a pivot table as a new sheet called “first_purchase”.
- Configured the settings of the pivot table to calculate the minimum event_date for each user.
- Transferred the first purchase dates to a new column in the purchase activity data.  
- Entered first_purchase_date as a column header in cell G1 of the “purchase_activity” sheet.
- Set up monthly data to build and track cohorts.
- Created three new columns in the “purchase_activity” sheet to help build the cohorts: event_month, first_purchase_month, and cohort_age.

![image](https://github.com/tloo921/Ecommerce_Spreadsheet_Project/assets/156555400/882cb1a6-fe5d-433d-94dc-6f73fc0e8aba)


#### Part 3: Calculate retention rates
- Aggregated the purchase data into cohorts and then calculated retention rates for each cohort month by month.
- Using the data from the “purchase_activity” sheet, inserted another pivot table as a new sheet called “cohort_analysis”.
- Configured pivot table so that each represents one cohort, which are based on the month in which customers made their first purchase.
- The pivot table has the count of unique users for each cohort_age in the columns of the pivot table.
- Created a new blank sheet called “retention_rates”.
- Added row labels in cells A3 to A7 for each cohort in chronological order. 
- Added column labels in cells B2 to E2 that represent the cohort ages from 1 to 4 months.
- In cell B3, wrote a formula that calculates the retention rate for each cohort at each cohort age in the table you created, based on the starting cohort sizes.

![image](https://github.com/tloo921/Ecommerce_Spreadsheet_Project/assets/156555400/2be5142a-8164-4c3b-85eb-1b308e317140)


#### Part 4 - Organized and documented spreadsheet
- Filled in the results synopsis and analysis descriptions in the “Executive Summary” sheet.
- Summarized the results and conclusions from analysis with the “conversion_funnel” sheet and the “retention_rates” sheet.
- Explained important properties about the data and any assumptions made in analysis.
- Described the raw data (e.g. timespan, event types, how it was collected, what parts of it was actually used, etc.).
- Explained what data was used to calculate the conversion rates in your funnel. 
- Explained the decisions you made in your cohort analysis of retention rates. 
- Formatted spreadsheets for better readability and added change log to doucment changes made to original raw data file.

## Final Results:
- Purchase conversion rates were 35.61% for users who added items to their cart and 10.34% total coversion rates from view on site to purchase
- Retention rates were highest in the first month after initial purchases for all cohorts
- **Recommendation made: reach out to users who have items in carts for an extended period of time with special promotions or deals to get them to finalize their purchases. Follow up with first time buyers after their purchases to get their opinions on the products and gauge level of satisfation. Possibly also offer discounts on future purchases to return customers to help with retention rates.**
  


