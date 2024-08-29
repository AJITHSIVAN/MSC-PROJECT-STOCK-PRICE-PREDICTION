Title: This research is focused on the development of Stock Market Prediction using historical information and innovative machine-learning algorithms.

Purpose: The purpose of this research is to enable investors and traders to make better decisions in their financial investment and also to minimize the risks in the financial investment.

Function Implemented
In this implementation, the linear regression model function  LinearRegression() is applied which takes the input of the training data "x_train" which contains the training part of 'open','high','low','volume','symbol' features of the dataset and "y_train" which contains the training part of 'close' features of the dataset and then predicts the developed model on the "x_test" value using the predict() function.
the output of the model after taking the input value is providing prediction values of stock with dates, rmse, mse, mae and r square value.

This research also implements the Random forest model function "RandomForestRegressor()" which takes the input of the training data "x_train" and "y_train" and then predicts the development model on the "x_test" value using the predict() function. 
The output of the model after taking the input value is providing prediction values of stock with dates, rmse, mse, mae and r square value.

In this implementation of the Artificial Neural network model, the "Sequential()" model function is used which dense and dropout layers are implemented with the "relu" activation function. This model is trained using 100 epochs with a validation percentage 20%. takes input of standard scaled data of features for x_train and y_train.

The output of the model after taking the input value is providing prediction values of stock with dates, rmse, mse, mae and r square value.
