In this project, we analyze a dataset on the price paid by ward, England
and Wales, from year ending December 1995 to year ending March 2022 published
by the Office for National Statistics and HM Land Registry. We use
various Python libraries and techniques to analyze and visualize the data.
The results obtained from the different linear regression analysis provide
insights into the ability of the year feature to predict house prices. The mean
squared error, R-squared score, and mean absolute error for the different Wards
indicate that the linear regression model provides reasonable predictions for
house prices based on the year feature. However, the relatively high mean
squared error and mean absolute error suggest that the linear regression model
may not be the best model for predicting house prices for this data. That
is why polynomial regressions models were carried out on the different Ward
dataset and we noticed that in some cases, the polynomial regression model
had a better performance why for some Ward data, the polynomial regressionmodel performance was approximately similar to the linear regression model.
And example such case where both model have almost same performance is on
the Abbey data. Since the two models are almost similar, we then tried a third
type of regression called the RandomForest regression.
The Random Forest Regression model performed the best, with the lowest
MSE and MAE, and the highest R2 score. The Polynomial Regression model
also performed well, with lower MSE and MAE than the Linear Regression
model, and a higher R2 score indicating that the Linear Regression model performed
the worst as shown on the code.
