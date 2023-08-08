# Predicting Walmart Store Sales with Machine Learning

## Description 
Our group created an XGBoost model to predict sales for WalMart stores from the years 2010-2013. We preprocessed the data by extracting the year from the dataframe, getting the week 
number and creating a graph. Then, we preprocessed the data using Standardscaler. Next we made our target and features arrays and splitted the data into
testing and training sets. We then created our first XGBoost model. We got an r-squared score of 0.90
Even though our r-squared score was over 0.80, we still optimized the model to see if we can get a higher score.

## Libraries to install
- Pandas - Conda install Pandas
- MatPlotLib - Conda install matplotlib
- Scikit-learn - Conda install scikit-learn
- XGBoost - pip install xgboost

## Data Source
https://www.kaggle.com/datasets/yasserh/walmart-dataset

## Data Visualizations 
1. Line chart - shows Walmart’s US Store Sales from the years 2010-2012.
2. Correlation Matrix - explores the relationships between Walmart's weekly sales and key influencing factors.
3. Linear Regression - a powerful tool for comprehending and forecasting Walmart's sales trajectory over time.
4. Standard Scaler - used to preprocess the input features before training our predictive model.
5. XG Boost Predictive Model - a powerful and popular machine learning algorithm designed for both regression and classification tasks.

## Process
1. Import Dependencies
2. Data Gathering:
Access the data source and extract CSV files. 
3. Backend Development:
Clean the data of missing values and unnecessary information.
Extract the date from the dataframe. 
4. Preprocessing Methods:
Implement StandardScaler. 
Get target and features arrays 'Weekly_Sales'. 
Split into testing and training sets. 
6. Visualizations:
(Line Chart, Correlation Matrix, Linear Regression) to help tell a story. 
7. Frontend Development:
Run XGBoost. 
Train the regression model. 
8. User Interaction:
Aggregate based on the week 'Weekly_Sales', 'Sales_predicted'. 
Calculate r2 score on test data and compare to r2 score on training data. 

## Credits
- [Nicole](https://github.com/Nicolemarie717) 
- [Michael](https://github.com/dibartm)
- [Matt](https://github.com/matthewdvp)
- [Reid](https://github.com/Reid04278)
