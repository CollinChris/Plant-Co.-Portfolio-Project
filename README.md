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

A single page report was created on Power BI Desktop & it was then published to Power BI Service.


### [1] Total Number of Customers = 129880

   Number of satisfied Customers (Male) = 28159 (21.68 %)

   Number of satisfied Customers (Female) = 28269 (21.76 %)

   Number of neutral/unsatisfied customers (Male) = 35822 (27.58 %)

   Number of neutral/unsatisfied customers (Female) = 37630 (28.97 %)


           thus, higher number of customers are neutral/unsatisfied.
           
### [2] Average Ratings

    a) Baggage Handling - 3.63/5
    b) Check-in Service - 3.31/5
    c) Cleanliness - 3.29/5
    d) Ease of online booking - 2.88/5
    e) Food & Drink - 3.21/5
    f) In-flight Entertainment - 3.36/5
    g) In-flight service - 3.64/5
    h) In-flight Wifi service - 2.81/5
    i) Leg room service - 3.37/5
    j) On-board service - 3.38/5
    k) Online boarding - 3.33/5
    l) Seat comfort - 3.44/5
    m) Departure & arrival convenience - 3.22/5
  
  while calculating average rating, null values have been ignored as they were not relevant for some customers. 
  
  These ratings will change if different visual filters will be applied.  
  
  ### [3] Average Delay 
  
      a) Average delay in arrival(minutes) - 15.09
      b) Average delay in departure(minutes) - 14.71
Average delay will change if different visual filters will be applied.

 ### [4] Some other insights
 
 ### Class
 
 1.1) 47.87 % customers travelled by Business class.
 
 1.2) 44.89 % customers travelled by Economy class.
 
 1.3) 7.25 % customers travelled by Economy plus class.
 
         thus, maximum customers travelled by Business class.
 
 ### Age Group
 
 2.1)  21.69 % customers belong to '0-25' age group.
 
 2.2)  52.44 % customers belong to '25-50' age group.
 
 2.3)  25.57 % customers belong to '50-75' age group.
 
 2.4)  0.31 % customers belong to '75-100' age group.
 
         thus, maximum customers belong to '25-50' age group.
         
### Customer Type

3.1) 18.31 % customers have customer type 'First time'.

3.2) 81.69 % customers have customer type 'returning'.
       
       thus, more customers have customer type 'returning'.

### Type of travel

4.1) 69.06 % customers have travel type 'Business'.

4.2) 30.94 % customers have travel type 'Personal'.

        thus, more customers have travel type 'Business'.


