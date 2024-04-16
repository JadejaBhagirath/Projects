The retail store (WALMART) is facing issues in managing inventory to match demand with supply across multiple outlets in the country.

Problem Statement: 
The retail store is facing issues in managing inventory to match demand with supply across multiple outlets in the country.

Project Objective: 
The objective is to analyze historical sales data and build a prediction model to forecast sales for the next X number of months/years.



The dataset contains the following columns:
> Store: Store number
> Date: Date of sales
> Weekly_Sales: Sales for the week
> Holiday_Flag: Binary indicator if the week contains a holiday (1) or not (0)
> Temperature: Temperature of the week
> Fuel_Price: Fuel price of the week
> CPI: Consumer Price Index of the week
> Unemployment: Unemployment rate of the week
> Data Pre-processing Steps and Inspiration:
> Checked for null values: No null values found.
> Checked statistics of columns: Provides an overview of the numerical columns.
> Checked data types: Date column needs to be converted to datetime format.
> Outlier Detection: Visualized boxplots for numerical columns, decided not to remove outliers as they might contain valuable information.
> Analyzed sales by stores: Identified stores with higher and lower sales.
> Converted date to datetime format and set it as the index.

> Choosing the Algorithm for the Project: 
ARIMA (AutoRegressive Integrated Moving Average) model is chosen for time series forecasting.
Motivation and Reasons For Choosing the Algorithm:
The initial implementation using ARIMA shows promising results in forecasting sales for the retail store. Further optimization and integration with additional factors can improve the accuracy of the forecasts.
References:
Documentation of Python libraries used (pandas, numpy, matplotlib, seaborn, statsmodels, sklearn)
Time series forecasting literature for understanding ARIMA and other techniques.
