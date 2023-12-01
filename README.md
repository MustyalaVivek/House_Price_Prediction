# House_Price_Prediction

Certainly! House price prediction is a common machine learning task where the goal is to predict the price of a house based on various features such as the number of bedrooms, square footage, location, etc.

This code performs the following steps:

Load the dataset: Reads the dataset, assuming it's in a CSV format. Adjust the filename accordingly.

Split the dataset: Splits the dataset into training and testing sets using train_test_split.

Create and train a linear regression model: Uses scikit-learn's LinearRegression to create a linear regression model and trains it on the training data.

Make predictions: Predictions are made on the testing data using the trained model.

Evaluate the model: The Mean Squared Error (MSE) and R-squared are calculated to evaluate the performance of the model.

Visualize predictions vs. actual prices: A scatter plot is created to visualize how well the predicted prices align with the actual prices.

Example prediction for a new house: Demonstrates how to use the trained model to predict the price for a new house with given features.
