# House Price Prediction using Linear Regression
This project implements a linear regression model to predict house prices based on their square footage, the number of bedrooms, and bathrooms. The dataset used for this project is from the Kaggle competition [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview/).

# Overview
The goal of this project is to predict the sale prices of houses using a linear regression model. The model is trained on various features such as lot area, basement full/half bathrooms, full/half bathrooms, and the number of bedrooms above ground.

# Requirements File 

- pandas
+ numpy
* matplotlib
- seaborn
+ scikit-learn

Install the libraries using pip:
```
pip install pandas scikit-learn matplotlib
```

# File descriptions
- train.csv - the training set with house features and their prices 
+ test.csv - the test set with house features for which we need to predict the prices
* submission.csv - The file where the predicted house prices are saved.

# Dataset
The dataset is sourced from the Kaggle House Prices competition. The dataset consists of 81 features describing various aspects of residential homes in Ames, Iowa.

# Features
The features used for training the model are:

- LotArea: Lot size in square feet
+ BsmtFullBath: Number of full bathrooms in the basement
* BsmtHalfBath: Number of half bathrooms in the basement
- FullBath: Number of full bathrooms above ground
- HalfBath: Number of half bathrooms above ground
* BedroomAbvGr: Number of bedrooms above ground

# Model Training and Evaluation
The model training process involves:

1.Loading the dataset.
2.Preprocessing the data by handling missing values and selecting relevant features.
3.Splitting the data into training and validation sets.
4.Training a linear regression model on the training set.
5.Evaluating the model on the validation set.
6.The code also includes visualization of the correlation between features and the target variable, as well as a scatter plot comparing actual and predicted prices.

# Results
The model's performance is evaluated using the following metrics:

1) Mean Absolute Error (MAE)
2) Mean Squared Error (MSE)
3) Root Mean Squared Error (RMSE)
Additionally, the distribution of residuals is plotted to assess the model's performance.

# Acknowledgements
The project uses the dataset from the [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview/) competition on Kaggle.
