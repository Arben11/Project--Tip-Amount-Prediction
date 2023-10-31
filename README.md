# Tip Amount Prediction of New York Taxi 
### Project Requirements:

This project involves conducting a comprehensive descriptive and engineering analysis of a dataset. The goal is to leverage machine learning techniques to predict the tip amount given by taxi service users.

### Dataset Background:

The dataset has been sourced from the TCL New York City Taxi and represents data collected during February 2016. It encompasses various features, including pick-up and drop-off date and time, locations, trip distances, fare details, rate types, payment types, and the number of passengers as reported by the driver. These features play a crucial role in estimating the target variable, which is the tip amount.

### Approach:

Given that the target variable, "tip amount," is a real number and constitutes a numeric variable, this project is designed as a regression task. Before training machine learning models, several modifications will be made to the dataset. This includes feature engineering to enhance the models' ability to predict the tip amount. After thorough feature engineering and data exploration, we will implement three different models. The selection of these models is based on their time and space complexity. We will begin with Linear Regression as a baseline model and subsequently train more complex models such as Decision Trees and XGBoost.

### Models Performance:

Below we will present the performance of the models:

- Linear Regression:
Root Mean Squared Error (RMSE): 0.42
R-squared (R^2): 0.97

- Decision Tree:
Root Mean Squared Error (RMSE): 0.568629
R-squared (R^2): 0.95

- XGBoost:
Root Mean Squared Error (RMSE): 0.51857
R-squared (R^2): 0.96

### Conclusion:
It is evident from the results that a relatively simple model like Linear Regression outperforms more complex models like XGBoost and Decision Tree. This suggests that the features within the dataset exhibit a linear relationship with the target variable. The predictive model created here can serve as a baseline for developing more dynamic tip amount prediction models that factor in additional variables, such as holidays, music events, neighborhoods, and more.
