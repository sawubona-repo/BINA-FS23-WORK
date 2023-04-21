## Regression + Time Series in R
#### last update 14/4/23 dbe - minor corrections

![Download](https://user-images.githubusercontent.com/52699611/168089692-b75237d8-a5ba-4fda-8b89-9b6d4cb88e08.png)

Any data recorded with some fixed interval of time is called as **time series data**. This fixed interval can be hourly, daily, monthly or yearly. e.g. hourly temp reading, daily changing fuel prices, monthly electricity bill, annul company profit report etc. In time series data, time will always be an *independent variable* and there can be one or many *dependent variable*.

**Time series forecasting** is the process of analyzing time series data using statistics and modeling to make predictions and inform strategic decision-making.  
It’s not always an exact prediction, and likelihood of forecasts can vary wildly—especially when dealing with the commonly fluctuating variables in time series data as well as factors outside our control.

There is a monthly time series data of the (international) **Air Passengers** of Pan Am airline in the United Stades of America from 1 Jan 1949 to 1 Dec 1960. Each row contains the air passenger number for a month of that particular year. The numbers were obtained from the Federal Aviation Administration. The company used the data to predict future demand before ordering new aircraft and training aircrew.  

### R/RStudio Examples for Regression + Time Series Analysis and Forecasting

* The analysis and prediction of  the relationship between 'TV advertising' and 'sales' using a simple [Linear Regression model](https://github.com/sawubona-gmbh/BINA-FS23-WORK/blob/2169897e52586ca9a08a78cf0fb4454b1faed2c5/LB10-Regression+TimeSeries/R/R-CODE_linear-nonlinear_REGRESSION_v2.R))

* The [ARIMA based analysis and forecast](https://github.com/sawubona-gmbh/BINA-FS23-WORK/blob/2169897e52586ca9a08a78cf0fb4454b1faed2c5/LB10-Regression+TimeSeries/R/R-Code_TIMESERIES_v5.R) for the Air Passengers dataset

--- 
* see [RPubs](https://rpubs.com/neharaut05/TimeSeries_AirPassangerForecast) for more information on Time Series analysis with R/RStudio on the Air Passenger Data
* you will also find on [Data Science Show](https://youtu.be/aZkg8JyKlrg) a multitude of introductional and explanational video tutorials on Time Series and Regression Analysis with R/RStudio
* see [RPubs](https://rpubs.com/amitnke/lrad) for a detailled description on Linear Regression Analysis with R/RStudio on the Advertising Data   
---   
