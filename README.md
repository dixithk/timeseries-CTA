### CHICAGO TRANSIT AUTHORITY


- This notebook provides interesting aspects of the rides data of CTA.
- We have shown how the rides trend from start of 2001 to 2019
- Discussed how the rides trend is effected by weekday/holiday/Saturday
- Discussed how the day of the month, quarter of the year, week of the month could effect the rides
- Discussed the stationarity and normality of the data
- We have used statistical ARIMA based methods to predict and forecast future rides
- We have used Facebook's Prophet tool to forecast future rides
- Using Prophet we analysed and forecasted the rides of one of the most famous station Central Park
- Future work: Verify how LSTM and other traditional ML models could be used to analyse the data. This might need extensive feature engineering, like inclusion of lag features, injected the seasonality pattern etc.
Convert the rides to Log tranformation before feeding into the models to avoid huge computations

#### How to run

- Download ctadataset from https://data.cityofchicago.org/Transportation/CTA-Ridership-L-Station-Entries-Daily-Totals/5neh-572f
- Assuming you have python scientific environment, you might need to install Prophet and it's dependencies
- Run each cell of the notebook step by step
- send your feedback to dkurra@asu.edu
