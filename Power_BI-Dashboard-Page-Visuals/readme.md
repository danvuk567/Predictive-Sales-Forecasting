# Power BI Dashboard Page Visuals

## Sales Region Dimension Slicer

The visuals on the Dashboard page can be filtered by *Region* from the *Region* table using a *Slicer* and *Tile* Style.

![Dashboard Region Slicer](https://github.com/danvuk567/Predictive-Sales-Forecasting/blob/main/images/Power_BI_Dashboard_Region_Slicer.jpg?raw=true)

## Sales KPI Card Visuals

The following **Card visual** KPIs aggregate the sales from the *Sales* table as a sum of *Sales*, sum of *Quantity*, sum of *Profit* and average of *DaystoDelivery*. Overall, Superstore appears to be a profitable business with 11% profit by the end of 2020.

![Dashboard Sales KPI Cards](https://github.com/danvuk567/Predictive-Sales-Forecasting/blob/main/images/Power_BI_Dashboard_Sales_KPI_Cards.jpg?raw=true)

## Sales Donut Charts

The **Donut Charts** aggregate the sales from the *Sales* table as a sum of *Sales* by *Region* from the *Region* table, *Segment* from the *Customers* table, and *Payment Mode* from the *Sales* table. Approximately **half (48%)** of the sales were to **Consumers Segemnt** by the end of 2020. Also, a **large portion (43%)** of the sales had **COD payment Mode** by the end of 2020.

![Dashboard Donut Charts](https://github.com/danvuk567/Predictive-Sales-Forecasting/blob/main/images/Power_BI_Dashboard_Donut_Charts.jpg?raw=true)

## Monthly Sales Area Charts

The following **Area Charts** compare Monthly Profit vs. prior year Monthly Profit and Monthly Sales vs. prior year Monthly Sales. *Month Long* from the *MonthCal* table is used for the *X-Axis*, *Year* from the *Calendar* table, and *Profit* and *Sales* from the *Sales* table in the *Legend*. Although sales revenue has increased each month in 2020 compared to prior year, October and December of 2020 have shown significant decrease in profit compared to 2019. If we filter the page by Central Region of the US, we see almost no profit in **October 2020 ($597)** vs. **October 2019 ($10,761)**. We also see a small loss in **December 2020 ($1,238)** vs. **December 2019 ($7,281)**.

![Dashboard Area Charts](https://github.com/danvuk567/Predictive-Sales-Forecasting/blob/main/images/Power_BI_Dashboard_Area_Charts.jpg?raw=true)

The **Clustered Bar Charts** aggregate the sales from the *Sales* table as a sum of *Sales* by *Ship Mode* from the *Sales* table, *Sub-Category* from the *Product* table, and *Category* from the *Product* table. 
The Sub-Category Chart and the Category Chart were both filtered by top 3 sales.

![Dashboard Clustered Bar Charts](https://github.com/danvuk567/Predictive-Sales-Forecasting/blob/main/images/Power_BI_Dashboard_Clustered_Bar_Charts.jpg?raw=true)

## Sales and Profit by State Map Chart

The *Map Chart* uses the *State* from the *Region* table, the sum of *Sales* from the *Sales* table for the *Bubble Size* and sum of *Profit from the *Sales* table in the *Tooltips*. In exploring the map overall and 
by Region, **Texas** had the 3rd largest sales revenue of **$116K** with the highest loss in profit of **-$14K**. This US state appears to have costs associated with the products sold that are higher than most states.

![Dashboard Map Chart](https://github.com/danvuk567/Predictive-Sales-Forecasting/blob/main/images/Power_BI_Dashboard_Map_Chart.jpg?raw=true)

Here is the final version of the Superstore Dashboard page:

![Dashboard Page](https://github.com/danvuk567/Predictive-Sales-Forecasting/blob/main/images/Power_BI-Dashboard-Page.jpg?raw=true)
