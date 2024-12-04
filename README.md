# Car_Price_Prediction-Regression

<img src="https://github.com/Shaikh-areeb/Car_Price_Prediction-Regression/blob/main/Car%20Price%20image.jpeg" alt="car" width="600"/>
![car](https://github.com/Shaikh-areeb/Car_Price_Prediction-Regression/blob/main/Car%20Price%20image.jpeg)

# Project Overview

This project focuses on developing a machine learning regression model to predict the selling price of a car based on multiple features. 
The model aims to provide accurate price estimates by learning from historical data.

# Dataset Features

The dataset includes the following features:

1. Car Brand: The manufacturer or brand of the car (e.g., Toyota, Honda, etc.)
2. Year: The year the car was purchased or manufactured
3. Sold Price: The price at which the car was previously sold
4. Present Price: The current market price of the car
5. KMS Driven: Total kilometers driven by the car
6. Fuel Type: The type of fuel used by the car (e.g., Petrol, Diesel, etc.)
7. Seller Type: Whether the seller is a dealer or an individua
8. Transmission Type: The type of transmission (Manual or Automatic)
9. Owner: The number of previous owners of the car

# Objective

The primary goal of this project is to build a predictive model that can estimate a car's price based on these features, 
enabling potential buyers and sellers to have a more informed understanding of the vehicle's value.

# Approach

Data Preprocessing: Cleaned and prepared the dataset by handling missing values, encoding categorical features, and scaling numerical features.
Model Selection: Implemented and trained various regression models (e.g., Linear Regression, Decision Tree, Random Forest) to identify the best-performing model.
Model Evaluation: Evaluated model performance using appropriate metrics such as Mean Squared Error (MSE) and R-squared (R²) score to assess accuracy and predictive power.
Hyperparameter Tuning: Applied techniques like GridSearchCV to fine-tune model parameters for better performance.

# Tools & Technologies

Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Machine Learning Models: Linear Regression, Lasso 

## Model Performance

| Model              | MSE       | R² Score  |
|--------------------|-----------|-----------|
| Linear Regression  | 2.518926  | 83.110695 |
| Lasso Regression   | 2.518926  | 83.110695 |


# Conclusion

This project demonstrates how regression models can be used to predict car prices based on a combination of historical sales data and technical features. 
The trained model can assist car buyers and sellers by providing price estimates that are data-driven and reliable.
