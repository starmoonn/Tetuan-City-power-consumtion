# Tetuan-City-power-consumtion
The project predicts the total power consumption of three zones in Tetouan City using Linear Regression.

## Project Description:
This project aims to predict the total power consumption of three zones in Tetouan City, Morocco, using machine learning. It utilizes a Linear Regression model to establish a relationship between weather features (temperature, humidity, wind speed, diffuse flows) and power consumption. By training the model on historical data, it can forecast future power consumption based on weather conditions. The project evaluates the model's accuracy using metrics like MAE, MSE, and RMSE, and further assesses its generalization performance through 5-fold cross-validation.

## Workflow Representation:

Here's a breakdown of the project workflow in steps:

**1. Data Acquisition and Preparation:**
- Obtain the "Tetuan City power consumption" dataset from the UCI Machine Learning Repository.
- Load the dataset into a Pandas DataFrame.
- Clean and preprocess the data (handle missing values if any, convert data types if needed).
- Create a new target variable 'all_power_consumption' by summing the power consumption of all three zones.
- Select relevant features (temperature, humidity, wind speed, diffuse flows) and the target variable.

**2. Model Training and Evaluation:**
- Split the data into training and testing sets (e.g., 80% for training, 20% for testing).
- Initialize a Linear Regression model.
- Train the model using the training data.
- Make predictions on the test data using the trained model.
- Evaluate the model's performance using metrics like MAE, MSE, and RMSE.
- Visualize the predictions against the actual values using a plot.

**3. Cross-Validation:**
- Perform 5-fold cross-validation to assess the model's generalization performance.
- Calculate the average MAE and MSE scores across the folds.
- Visualize the cross-validation results to understand the model's stability.

**4. Conclusion and Insights:**
- Analyze the model's performance metrics and cross-validation results.
- Draw conclusions about the model's accuracy and generalization ability.
- Gain insights into the relationship between weather features and power consumption in Tetouan City.
