# SweetliftSalesAnalysis

The project assigned to me during the thirteenth sprint involves Time Series Analysis.

Throughout this sprint, I dived into time series analysis on its key principles including resampling, moving averages, trends, seasonality, and predictive model creation.

# **Project Insight**

A taxi enterprise known as Sweet Lift has collected historical data related to taxi orders at the airport. As a Data Scientist, I was assigned to develop a model that capable to create a prediction the quantity of taxi orders for the following hour. The objective is to attract more drivers during peak hour, aiming for an evaluation metric, Root Mean Square Error (RMSE), on the test set that does not exceed 48.

The comparative analysis of models using XGBRegressor and Prophet led to the conclusion that the Prophet model exhibits superior prediction performance amongst all, with an RMSE value of 39.19. Conversely, the XGBRegressor model was found to have an RMSE value of 62. Of course, this is exceeded our expected RMSE value by 48.

Hence, I advocate for Sweet Lift to implement the Prophet model for forecasting the number of taxi orders in the upcoming hour. This model, characterized by a higher RMSE value, and was selected to harmonize the demands of customers with the availability of the fleet, in pursuit of enhancing service quality and customer satisfaction.
