Plant Co. Portfolio Project

A Power BI project on a dummy dataset of a company selling plants.

# Plant Co.

![Image](https://github.com/user-attachments/assets/a1f615db-4294-4eed-9583-86e6e65f7fc7)

### Dashboard Link : Currently I am using the free version of Power BI Services so the link might not be functioning, the Power BI file itself will be uploaded along with this text file as well.
https://app.powerbi.com/groups/me/reports/77d0a338-9887-4cfd-9f8e-45b5e02d1edc/c866b177ff5d17a46565?experience=power-bi

## Problem Statement

Since this was a dummy dataset, the problem statements were not defined, but while creating the dashboard I have formed my own problem statements based on the data found.

- The gross profit comparison of Year to Date and Prior Year to Date went from a -265k to -77k in 2023 to 2024 respectively, find insights within the data to suggest reasons why and what actionable strageties that could be implemented to continue this upward trend.

- Create a dashboard that provides users value by showcasing important metrics and relationships between these features that would be key for improving business strategies.

- Find out which branches/countries/products are the least profitable and suggest follow up actions.

- Find out which accounts are the most profitable so that resources may be focused on them instead of being spread out to not so profitable accounts.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a xls file. Excel file contains 3 tables called "Plant_Fact", "Accounts, & "Plant Hierarcy" and will be renamed in Power BI to "Fact_Sales", "Dim_Accounts", & "Dim_Products" respectively for easier identification.
- Step 2 : Cleaning the data, we begin by opening power query editor & checking "column distribution", "column quality" & "column profile" options. The data seems fine so all wwe do is remove duplicates from each table.
- Step 3 : Create new tables for "Dim_Date", "Slicer Values"(To toggle between Gross Profit, Quanity, & Sales values in the charts), & "Measures" to prepare what we need to create valuable visualizations for the data.
- Step 4 : Create DAX formulas for "Gross Profit", "Quantity", & "Sales" for "Year to Date"(YTD) and "Prior Year to Date"(PYTD) values to compare trends.
![Image](https://github.com/user-attachments/assets/8c777d4f-b0e4-4600-9196-ff6b4368120e)
![Image](https://github.com/user-attachments/assets/4b27f696-ef67-4023-bf2c-7fe9ab0cd6f9)
