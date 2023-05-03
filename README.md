# Capstone_YesBank_Prediction

Capstone2:

Project Name - Yes Bank Stock Closing Price Prediction

PROBLEM STATEMENT
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

Algorithm used:
1.Linear regression

2.Lasso regression

3.Ridge Regression

4.ElasticNet regression

5.SVR

6.XGBoost

Features(Column):

1)Open:Opening price of the stock of particular day

2)High:It's the highest price at which a stock traded during a period

3)Low:It's lowest price at which stock traded during a period

4)Close:Closing price of a stock at the end of a Trading Day

5)Date:In our data its monthly observation of stock since it listed

Conclusion

a)Exploratory Data Analysis

1.from 2016 to 2018 stock closing price increase but after year 2018 it started decreasing because of Rana Kapoor case

2.same pattern of observations for the opening price also .

3.And according to above two reason the point that the stock price of yes bank falls down after 2018 and it is not beneficial for investors to invest

4.after plotting distplot we got to know that data for dependent and indepent variables are rightly skewed for that we applied log transformation.

5.next we got to know that independent features are highly correlated after plotting scatter plots.

6.after using heat map we also get that independent features are highly correlated this cuase high multicollinearity

7.after calculating vif we get that all the available features are most important for closing price prediction so will not drop it from data set.

b)dependent variable strongly dependent on independent variables

c)we get highest accuracy of 99.99%

d)ridge and lasso has near about same R2 score

e)where as elastic net shows lowest R2 score and high MSE ,RMSE,MAE,MAPE values

f)XGBoost Regressor end up with Highest r2 value and the predicted values are nearly equal to the actual values as we got 99 % accuracy
