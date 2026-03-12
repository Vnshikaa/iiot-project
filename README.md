House Price Prediction using Linear Regression

📌 Project Overview:

This project predicts house prices based on the living area of a house (sqft_living) using a Linear Regression model.

The goal is to understand the relationship between the size of a house and its market price and build a simple machine learning model to make predictions.

🎯 Objective:

Analyze the relationship between house size (square feet) and price

Build a Linear Regression model to predict house prices

Visualize the data and regression line

Evaluate the model performance using Mean Squared Error (MSE)

📊 Dataset:

The dataset contains housing information including:

sqft_living – Area of the house in square feet

price – Price of the house

These features are used to train and test the machine learning model.

🛠 Technologies Used:

Python
NumPy
Pandas
Matplotlib
Scikit-learn
Google Colab

⚙️ Model Used:

Linear Regression-

Linear regression models the relationship between the independent variable (sqft_living) and the dependent variable (price) by fitting a straight line to the data.

📈 Data Visualization:

A scatter plot was created to visualize the relationship between house size and price.

The red line represents the Linear Regression model prediction line.

This helps to understand how house prices generally increase with larger living areas.

📉 Model Evaluation:

The model performance was evaluated using Mean Squared Error (MSE).

Lower MSE values indicate better prediction accuracy.

Example result:
MSE ≈ 9.9e10

📌 Project Workflow:

Import libraries

Load dataset

Select features (sqft_living)

Split data into training and testing sets

Train Linear Regression model

Predict house prices

Visualize regression line

Evaluate model using MSE

📷 Output:

The model generates a scatter plot showing:

Actual house prices

Predicted regression line

This demonstrates how house prices change with increasing living area.

🚀 Future Improvements:

Use multiple features such as bedrooms, bathrooms, and location

Try advanced models like Random Forest or Gradient Boosting 

Improve prediction accuracy with feature engineering
