# Sales Prediction Using Python

## Overview

This project develops machine learning regression models to predict product sales based on advertising expenditure across TV, Radio, and Newspaper media channels. The project includes data analysis, visualization, model training, evaluation, and comparison of multiple regression algorithms.

## Objective

* Predict product sales using advertising budgets.
* Analyze the relationship between advertising channels and sales.
* Train and compare multiple regression models.
* Evaluate model performance using regression metrics.
* Identify the advertising channel with the greatest impact on sales.

## Dataset

**Dataset Name:** Advertising Sales Dataset

The dataset contains advertising budgets for:

* TV Advertising
* Radio Advertising
* Newspaper Advertising

Target Variable:

* Sales

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Loaded and explored the dataset.
2. Removed the unnecessary index column.
3. Performed Exploratory Data Analysis (EDA).
4. Created scatter plots for each advertising channel against sales.
5. Generated a correlation heatmap.
6. Split the dataset into training and testing sets.
7. Trained two regression models:

   * Linear Regression
   * Random Forest Regressor
8. Evaluated both models using:

   * Mean Absolute Error (MAE)
   * Root Mean Squared Error (RMSE)
   * R² Score
9. Generated a residual plot for the best-performing model.
10. Analyzed feature importance to determine the most influential advertising channel.

## Machine Learning Models

* Linear Regression
* Random Forest Regressor

## Model Performance

| Model                   |       MAE |      RMSE |   R² Score |
| ----------------------- | --------: | --------: | ---------: |
| Linear Regression       |     1.461 |     1.782 |     0.8994 |
| Random Forest Regressor | **0.620** | **0.769** | **0.9813** |

The Random Forest Regressor achieved the best overall performance and was selected as the final model.

## Visualizations

The notebook includes:

* Pair Plot
* Sales vs TV Advertising
* Sales vs Radio Advertising
* Sales vs Newspaper Advertising
* Correlation Heatmap
* Residual Plot
* Feature Importance Chart

## Project Structure

DataScience-Task5-SalesPrediction
│
├── SalesPrediction.ipynb
├── sales.csv
└── README.md

## How to Run

1. Clone the repository.

git clone https://github.com/meruflin/OIBSIP.git

2. Install the required libraries.

pip install pandas matplotlib seaborn scikit-learn jupyter

3. Open `SalesPrediction.ipynb`.

4. Run all notebook cells in sequence.

## Conclusion

This project demonstrates the application of regression techniques for predicting product sales using advertising expenditure. Among the evaluated models, the Random Forest Regressor achieved the highest predictive accuracy with an R² Score of 98.13%. Feature importance analysis showed that TV advertising had the greatest impact on sales, making it the most effective advertising channel for this dataset.

## Author

**Meruflin Jeeva**

Oasis Infobyte Internship

Task 5 – Sales Prediction Using Python
