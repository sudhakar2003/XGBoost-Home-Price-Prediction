# XGBoost-Home-Price-Prediction
This project aims to predict house prices based on factors such as income, schools, hospitals, and crime rates using the XGBoost regression model. Here's a description of the project components:

1. **Dataset**: The project assumes the availability of a dataset containing columns for income, schools (quality or ratings), hospitals (proximity or quality), crime rates (per capita or area), and corresponding house prices. This dataset is used to train and test the predictive model.

2. **Data Preprocessing**: The dataset is split into features (income, schools, hospitals, crime rates) and the target variable (house prices). It is also split into training and test sets using the `train_test_split` function from `sklearn.model_selection`.

3. **Model Training**: The XGBoost regressor is used to train a regression model on the training data. XGBoost is a popular gradient boosting library known for its performance and efficiency in handling large datasets.

4. **Model Evaluation**: The trained model is evaluated using metrics such as Mean Squared Error (MSE) and R-squared. These metrics help assess the performance of the model in predicting house prices based on the input features.

5. **Prediction**: The trained model is used to predict house prices for new data points. For example, given a new set of values for income, schools, hospitals, and crime rates, the model can predict the price of a house based on these factors.

Overall, this project demonstrates how machine learning techniques, specifically using XGBoost, can be applied to predict house prices based on various factors, providing valuable insights for real estate pricing and decision-making.
