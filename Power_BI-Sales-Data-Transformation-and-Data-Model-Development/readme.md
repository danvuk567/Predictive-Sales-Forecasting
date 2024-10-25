# Power BI Sales Data Transformation and Data Model Development

## Data Cleaning

The first step was to import and clean the [SuperStore Data Set Excel file](https://github.com/danvuk567/Predictive-Sales-Forecasting/tree/main/Data-Source-Files/SuperStore%20Sales%20DataSet.xlsx) using **Power Query**. All columns were checked for errors, missing values, duplicates. I used the *Column quality*, *Column distribution* and *Column profile* to identify where there might be missing values, discrepancies, errors and possible duplicates. The *Returns* column had errors which were replaced with 0's and data type changed to *Whole Number*. The last 2 columns *ind1* and *ind2* had null values and were removed.

## Data Mapping

The next approach was to identify how the data could be normalized to seperate tables. Generally, we see that we have orders, customers, products, locations and sales. Customers, products and locations are essentially unique entities and can be extracted from the data as 3 separate Dimension tables. However the *Order ID* was not unique and *Order Date*, *Ship Date*, *Product ID* and *Sales* all had different variations which essentially dictated that orders could not be seperated from sales. The *Row ID+O6G3A1:R6* column is also not unique and connot be used as a unique Order key or Sales key. This observation was made by using the *Group By* feature in Power Query to count > 1 for any combination of these columns. The following **Data Mapping document** was then used to build the initial data model for the valid columns:

[SuperStore Data Mapping](https://github.com/danvuk567/Predictive-Sales-Forecasting/tree/main/Data-Source-Files/SuperStore%20Data%20Mapping.xlsx)

[SuperStore Data Mapping Image](https://github.com/danvuk567/Predictive-Sales-Forecasting/blob/main/images/SuperStore_Data_Mapping.JPG)





