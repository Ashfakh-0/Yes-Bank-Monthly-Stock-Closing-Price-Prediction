# Yes-Bank-Monthly-Stock-Closing-Price-Prediction
# project overview

This project focuses on predicting the monthly closing price of Yes Bank stock using machine learning techniques. The objective is to build an accurate regression model using historical stock price data (Open, High, Low) to forecast the closing price.

The project follows a complete end-to-end machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model building, evaluation, and hyperparameter tuning.

# 🎯 Problem Statement

The goal of this project is to develop a ML model that can accurately predict the monthly closing price of Yes Bank stock using historical Open, High, and Low price data to support financial analysis and investment decision-making.

# 📊 Dataset Information

The dataset contains 185 records with the following features:
Date
Open
High
Low
Close (Target Variable)

# 🔎 Exploratory Data Analysis (EDA)

Checked for missing and duplicate values
Performed correlation analysis
Visualized data using heatmaps and boxplots
Identified strong positive linear relationships between Open, High, Low, and Close prices
Applied IQR method for outlier treatment

# Data Preprocessing

Removed Date column
Selected Open, High, and Low as independent variables
Applied StandardScaler for feature scaling
Split data into training and testing sets

# Machine Learning Models Used

Linear Regression
Random Forest Regressor

# 📈 Model Evaluation Metrics

The models were evaluated using:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score

# 🔧 Hyperparameter Tuning

GridSearchCV was applied to optimize the Random Forest model parameters. Although tuning improved performance slightly, Linear Regression still provided better accuracy and lower error.

# 🛠️ Technologies & Libraries Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

# 📌 Key Insights

Strong linear relationship exists between Open, High, Low, and Close prices
Linear Regression achieved high predictive accuracy
The model explains approximately 99% of variance in closing price

# 🚀 Conclusion

This project demonstrates how machine learning regression techniques can effectively predict stock closing prices when strong linear relationships exist in the data. The final model provides reliable predictions that can support financial forecasting and investment planning.
