# Time-Series-House-Property-Sales
Source: https://www.kaggle.com/datasets/htagholdings/property-sales?resource=download . Time series is a popular form of analysis that corporate types like to use for the benefit of their business. It allows a company to forecast their future sales/prices/etc. and it is fairly straight forward to use. You usually just need some dates and values next to those dates in order to find a trend and make a forecast. Here, I took a data set from Kaggle related to the prices of properties and how much bedrooms they have. I decided to go with some standard EDA processes like making line plots and boxplots. Then I separated the data into 7 different subsets, one for each combination of property types (house and unit) and number of bedrooms (1-5). With these subsets in the data, I used ARIMA to create forecast models to see how the prices would change until Q4 of 2022. As simple as that. One thing should be noted though is that all forecasting models are highly vulnerable to the volatile state of the economy, so that should always be noted when doing time series analysis.

Update 06/22/22: Now includes better forecasting plots!
