# Car Price Prediction with Machine Learning

## Overview

This project builds a machine learning regression model to predict the selling price of used cars based on features such as brand, model year, mileage, fuel type, and transmission. The project includes data cleaning, feature engineering, exploratory data analysis (EDA), model training, evaluation, and comparison of multiple regression models.

## Objective

* Build a regression model to predict used car prices.
* Clean and preprocess the dataset.
* Perform feature engineering to create meaningful features.
* Analyze relationships between different variables using visualizations.
* Train and compare multiple machine learning regression models.
* Evaluate model performance using standard regression metrics.

## Dataset

Dataset Name: **Used Cars Dataset**

The dataset contains information about used cars, including:

* Brand
* Model
* Model Year
* Mileage
* Fuel Type
* Engine
* Transmission
* Exterior Color
* Interior Color
* Accident History
* Clean Title
* Selling Price

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Loaded the dataset using Pandas.
2. Inspected the dataset structure and checked for missing values.
3. Removed duplicate records.
4. Filled missing categorical values.
5. Cleaned the `price` and `milage` columns by converting them into numerical format.
6. Created a new feature (`car_age`) from the model year.
7. Performed Exploratory Data Analysis (EDA) using multiple visualizations.
8. Encoded categorical variables using One-Hot Encoding.
9. Split the dataset into training and testing sets.
10. Trained Linear Regression and Random Forest Regressor models.
11. Evaluated both models using MAE, RMSE, and R² Score.
12. Visualized feature importance for the best-performing model.

## Visualizations

The notebook includes the following analyses:

* Distribution of Car Prices
* Selling Price by Fuel Type
* Selling Price vs Car Age
* Correlation Heatmap
* Feature Importance Chart

## Machine Learning Models

The following regression models were trained and compared:

* Linear Regression
* Random Forest Regressor

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

The Random Forest Regressor achieved better performance than the Linear Regression model and was selected as the better predictive model.

## Project Structure

DataScience-Task3-CarPricePrediction
│
├── CarPricePrediction.ipynb
├── used_cars.csv
└── README.md

## How to Run

1. Clone the repository.

git clone https://github.com/meruflin/OIBSIP.git

2. Install the required libraries.

pip install pandas matplotlib seaborn scikit-learn jupyter

3. Open `CarPricePrediction.ipynb` using Jupyter Notebook or Visual Studio Code.

4. Run all notebook cells in sequence.

## Conclusion

This project demonstrates the complete machine learning workflow for predicting used car prices. The dataset was cleaned, analyzed, and transformed before training two regression models. After evaluating both models, the Random Forest Regressor produced better prediction performance than the Linear Regression model. The project highlights the importance of data preprocessing, feature engineering, and model evaluation in building effective machine learning solutions.

## Author

**Meruflin Jeeva**

Oasis Infobyte Internship

Task 3 – Car Price Prediction with Machine Learning
