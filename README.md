# 📞Customer Service Management Analysis Dashboard
A Power BI dashboard project for analyzing a 31- days key metrics in customer service operations. This solution helps organizations track call volumes, operator performance, issue resolution, and service quality on a daily basis.

## 📌Overview

This dashboard provides a centralized view of customer service data, designed to support business decisions and process improvements in service management. It includes insights on:

- Operator workload and efficiency

- Call trends by shift and wage type

- Daily issue tracking and order analysis

- Service quality scoring

- Automation usage patterns


## 🛠️Tools used
- Microsft Power BI for dashboard creation
- Power Query for data transformation in Microsoft Power BI
- DAX for advanced calculations in Microsoft Power BI

### 🧭Steps
- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was further cross-examined and it was observed that  in none of the columns; errors & empty values were present.
- Step 5 : The model view was used to explore the connection amoongst the various datasets for analysis.
- Step 6 : Varoius measures were created using DAX expressions to aid analysis such as "Calls", "Opeartors", "Issues raised", "Orders".
- Step  7: In the report view, under the view tab, theme was selected.
- Step 8 : Multiple card visuals were added to the canvas repersenting the measures created in step 6.
- Step 9 : Page 1 of the dashboard shows an overview of the distribution of the infected files and attack types while page 2 shows an overview of the severity distribution
- Step 10 : Various charts and graphs were added to the canvas; each used to visualise a set of the analysis. 

## 📊 Key Metrics Tracked
- Total Calls: 43,000

- Total Operators: 1,283

- Orders Processed: 275,000

- Issues Raised: 162


## Key Insights
-	Operator Distribution: Most operators are at Level 12 (79.16%), with fewer at Level 1 (20.84%).
- Issues Raised by Operator Level: Majority of issues (≈500) are with Level 2 operators.
- Calls by Shift: PM2 and PM1 shifts handle the highest volume (35.47% and 26.06% calls respectively).
- Calls by Wage Type: 66% of calls occur on weekdays, 34% on holidays.
- Issues raised by Order: of the 275,000 orders processed, 1 issue was raised 53.84%; 2 issues in 33.95%; 3 issues in 3.02% and 0 issue in 9.19% of the orders.
- Issues raised by Day: Issue counts remain relatively stable per day, averaging 5–8 issues, but days 8, 11 and 19 recorded the highest number of issue per day of 8 issues.


## 📷 Dashboard Preview
[Image](https://github.com/user-attachments/assets/7bcf42d2-cc13-461e-acff-ca2c6cc865fd)




