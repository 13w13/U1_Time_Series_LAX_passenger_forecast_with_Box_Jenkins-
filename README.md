# U1_Time_Series_LAX_passenger_prediction_with_Box_Jenkins-

Time Series project
--

**Objectives**: Apply Box-Jenkins methodology to forecast airport traffic time
series.  
Data: You have to download monthly data of air traffic from a specific
airport. The series should contain about 100 observations.
Report: A zip file named name1-name2.zip must be submitted on C@mpus
with:
- your R project (datasets and script) file,
- A ppt presentation summarizing and interpreting the results.
Your presentation should contain tables and graphs useful for your analysis as
well as comments for each of them. More precisely, you should develop the
following items:
1) Description of the time series
2) Stationarity: Is your series stationary? Include graphs and tables to justify
your analysis (acf, pacf, graph of the series). Explain how you
transformed the data in order to reach stationarity (log transformation,
differentiation with different orders).
3) Apply Box-Jenkins methodology to build an ARMA process on the
stationary data.
a. Identify the orders p and q using the ACF and PACF.
b. Comment the significance of the coefficients. If necessary, modify
the model until all the coefficients are significant.
c. Residual diagnostic: check for the normality, the non
autocorrelation assumption and the homoscedasticity of the
residuals.
d. Comment the information criteria values (AIC, SBC) to select the
best model.
4) Validate the model with an in-sample and out-of-sample analysis and do
a forecast for the next three periods.
--
LAX_passenger_prediction_with_Box_Jenkins

**Data** : This is a dataset hosted by the city of Los Angeles. The organization has an open data platform found here and they update their information according the amount of data that is brought in. Explore Los Angeles's Data using Kaggle and all of the data sources available through the city of Los Angeles organization page!

    Update Frequency: This dataset is updated daily.

**Acknowledgements**

This dataset is maintained using Socrata's API and Kaggle's API. Socrata has assisted countless organizations with hosting their open data and has been an integral part of the process of bringing more data to the public. 

**Outline**  : 
We are going to analyze the data, visualize our data to understand it better.
After that, we will focus on time series prediction to predict the number of passengers for future dates.

For time series prediction, we will apply Box Jenkins methodology. 
