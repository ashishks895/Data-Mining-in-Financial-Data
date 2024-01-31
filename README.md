Predicting stock market prices is important because it can help investors make informed decisions about buying and selling stocks. 
By understanding trends and patterns in stock prices, investors can make predictions about future market conditions and adjust their portfolios accordingly. 
Additionally, stock market prediction can also be used by traders and financial institutions to inform their investment decisions and risk management strategies. 
Overall, the ability to accurately predict stock market prices can lead to improved financial outcomes for individuals and institutions alike.

**Financial Data Collection:** 
* Collected five-year stock price data of 5 stocks. You can choose any stocks you'd like to analyze.
* You can have multiple ways of collecting financial data with Python, here is a reference: https://www.alpharithms.com/python-financial-data-491110/


MACHINE LEARNING MODEL USED:
* Linear Regression is a statistical method that is used to predict the value of an output variable based on one or more input variables. 
In the context of stock market prediction, linear regression can be used to model the relationship between the historical prices of a stock and other financial indicators such as earnings, dividends, and market index.

* LSTM (Long Short-Term Memory) is a type of Recurrent Neural Network (RNN) that is specifically designed to handle sequential data. 
LSTM can be used to predict stock prices by analyzing the historical prices of a stock and other financial indicators such as earnings, dividends, and market index.

* Random Forest is an ensemble learning method that combines multiple decision trees to improve the accuracy of the predictions. 
Random Forest can be used to predict stock prices by analyzing the historical prices of a stock and other financial indicators such as earnings, dividends, and market index. The algorithm will build multiple decision trees and take the average of their predictions.

* In summary, Linear Regression, LSTM and Random Forest are all machine learning algorithms that can be used to predict stock prices. They all work by analyzing the historical prices of a stock and other financial indicators, but each algorithm has its own strengths and weaknesses. 
Linear Regression is simple and easy to implement, but its predictions may not be accurate for complex data. LSTM and Random Forest are more powerful algorithms that can handle complex data and make accurate predictions, but they require more computational resources and are more difficult to implement.


RESULTS:

* Based on the mean squared error, Random Forest has the lowest error of 0.796, followed by Linear Regression with 5.425e-27 and LSTM with 55.152.

* Based on th RMSE, Random Forest has the lowest error of 0.8922, followed by Linear Regression with 7.4e-14 and LSTM with 7.426.

* R-squared error is a measure of how well the model fits the data. A value of 1.0 represents a perfect fit, while a value of 0.0 represents a poor fit. 
In this case, Linear Regression has the highest R-squared error of 1.0, followed by Random Forest with 0.999 and LSTM with 0.996

* Mean Absolute Error (MAE) is a measure of how close the predictions are to the actual values. The lower the MAE, the better the model is at predicting the target variable. 
In this case, Random Forest has the lowest MAE of 0.358, followed by Linear Regression with 6.7e-14 and LSTM with 4.7.

* Overall, Random Forest seems to perform the best among the three models in terms of mean squared error, Root Mean Squared Error, R-squared error, and MAE.
