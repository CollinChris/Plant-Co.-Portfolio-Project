Plant Co. Portfolio Project

A Power BI project on a dummy dataset of a company selling plants.

# Plant Co.

![Image](https://github.com/user-attachments/assets/a1f615db-4294-4eed-9583-86e6e65f7fc7)

### Dashboard Link : Currently I am using the free version of Power BI Services so the link might not be functioning, the Power BI file itself will be uploaded along with this text file as well.
https://app.powerbi.com/groups/me/reports/77d0a338-9887-4cfd-9f8e-45b5e02d1edc/c866b177ff5d17a46565?experience=power-bi

## Content

- Problem Statement
- Steps followed
- Insights & Possible Follow-up Actions
- Summary

## Problem Statement

Since this was a dummy dataset, the problem statements were not defined, but while creating the dashboard I have formed my own problem statements based on the data found.

- The gross profit comparison of Year to Date and Prior Year to Date went from a -265k to -77k in 2023 to 2024 respectively, find insights within the data to suggest reasons why and what actionable strageties that could be implemented to continue this upward trend.

- Create a dashboard that provides users value by showcasing important metrics and relationships between these features that would be key for improving business strategies.

- Find out which branches/countries/products are the least profitable and suggest follow up actions.

- Find out which accounts are the most profitable so that resources may be focused on them instead of being spread out to not so profitable accounts.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a xls file. Excel file contains 3 tables called "Plant_Fact", "Accounts, & "Plant Hierarcy" and will be renamed in Power BI to "Fact_Sales", "Dim_Accounts", & "Dim_Products" respectively for easier identification.

- Step 2 : Cleaning the data, we begin by opening power query editor & checking "column distribution", "column quality" & "column profile" options. The data seems fine so all we do is remove duplicates from each table.

- Step 3 : Create new tables for "Dim_Date", "Slicer Values"(To toggle between Gross Profit, Quanity, & Sales values in the charts), & "Measures" to prepare what we need to create valuable visualizations for the data. Also, create data hierarcies and relationships in the data model so that the visualisations can be drilled down and explored.

- Step 4 : Create DAX formulas for "Gross Profit", "Quantity", & "Sales" for "Year to Date"(YTD) and "Prior Year to Date"(PYTD) values to compare trends.

![Image](https://github.com/user-attachments/assets/8c777d4f-b0e4-4600-9196-ff6b4368120e)
![Image](https://github.com/user-attachments/assets/4b27f696-ef67-4023-bf2c-7fe9ab0cd6f9)

- Step 5 : Pick and test visualizations for our dashboard to consider what can provide the most value to our users. In this respect, we have chosen a card to display "YTD", "YTD vs PYTD", "PYTD", "GP %", to display margins within the company's profitability which can be toggled and drilled with Treemaps, Waterfall Charts, Bar Charts, Scatter Charts, & Line & Stacked Column Charts.

![Image](https://github.com/user-attachments/assets/056cea9a-ab7b-44c4-81f7-673262e420e0)

(For example, in this screenshot here, we can see that in 2023, the bottom region for plant sales was China, which months were the least profitable from the Waterfall Chart, which accounts had the most Gross Profit % to refocus efforts to those accounts, and we can drill down into the Waterfall Chart to see which products had the most loss, in this case it was the "Indoor" plant products)


- Step 6 : Formatting and cleaning up the visualizations so it's easier to view the information and slightly more pleasant to look at for users.(The screenshots provided are post-formatting)

- Step 7 : Published to Power BI Service(though in this case since I have not paid for the subscription, the dashboard can't be shared, the Power BI file is included in this Github for access instead).

# Insights & Possible Follow-Up Actions

![Image](https://github.com/user-attachments/assets/e74306f0-9ab4-4909-a302-c0b736478323)

- In 2023, the products attributing to the most of the the -265k decline in gross profit compared to the previous year, were Indoor and Landscape plants(-237k, -106k), compared to the Outdoor plants which increased by 77k, indicating a rise in popularity of outdoor plants. This shows an increase in popularity of outdoor plants so we could focus inventory on Outdoor plants or focus marketing on Indoor/Landscape plants depending on what the targets of the business owners are.

- Similiar in 2024, the Indoor/Landscape plants attributed to the most decline(though not as much which might indicate that previous year efforts to increase sales/profitability in these products worked or there might have been an increase in demand, further analysis can be done to determine which and what directions can be followed from that point)  while Outdoor plants maintained a slight upward trend so it shows the trends are consistent so far.

![Image](https://github.com/user-attachments/assets/38f4d640-6b15-450d-8499-a4ba75ae9836)

![Image](https://github.com/user-attachments/assets/2f7f2548-39f2-4a9c-ae7e-e9de28774483)

- From 2023 to 2024, China went from being the bottom country with gross profit of -405k to being profitable at 1.62k in 2024, with the most profit being in February, so it is worthwhile to analyze marketing strategies that within that time or to check in other features(such as Chinese New Year) may have affect that positive trend for future actions.

![Image](https://github.com/user-attachments/assets/0854f1c9-84e9-4cec-9eb8-710c70158db4)

- In 2024, the bottom country in Sales was Canada, declining 73k from the previous year, from  the screenshot given, I have circled the accounts with the most gross profit in red at the bottom left of the dashboard. We can focus business strategies to market to those accounts or ones with similiar demographics to those.

# Summary

- From the insights above, it can be shown how the dashboard can be used to find further insights for the users/business, and depending on which direction to stakeholders decide to go, we can use the relationships between the data to do further analysis to suggest the best courses of action and form business strategies.
