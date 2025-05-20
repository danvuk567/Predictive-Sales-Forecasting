# Power BI Forecasting Page Visuals

The following **Line Chart** shows the total daily sales by order date. The Power BI **Forecast** analytics feature, which uses exponential smoothing, is set up with a 15-day forecast length. There doesn't appear to be any clear seasonality in the data and sales can vary drastically from day to day, so the seasonality is set to 1 day. This provide us with a simple straightforward view of daily patterns. The last day is ignored to start seeing the model at work and a 95% confidence interval is used which provides us with a reasonable range of prediction. Sales are estimated to increase to around **$5.3K** from **$2.8K** with the possiblity of dropping down to **$1K** but also possibly increasing up to **$9.5K**.

![Forecasting Line Chart](https://github.com/danvuk567/Predictive-Sales-Forecasting/blob/main/images/Power_BI_Sales_Forecasting_Line_Chart.jpg?raw=true)

The **Clustered Bar Char** list total sales by state. **California** had the largest sales at **$0.34M** but **Texas** had the 3rd largest sales at **$0.12M** which was also observed in the *Sales and Profit by State Map Chart* along with a **-14K** loss in profit. 

![Forecasting Clustered Bar Chart](https://github.com/danvuk567/Predictive-Sales-Forecasting/blob/main/images/Power_BI_Sales_Forecasting_Clustered_Bar_Chart.jpg?raw=true)

Here is the final version of the Superstore Forecasting page:

![Forecasting Page](https://github.com/danvuk567/Predictive-Sales-Forecasting/blob/main/images/Power_BI-Forecasting-Page.jpg?raw=true)<br/><br/>

:arrow_right: **Back to:** [Home Page](https://github.com/danvuk567/Predictive-Sales-Forecasting)
