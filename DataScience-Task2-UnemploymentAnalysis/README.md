# Unemployment Analysis with Python

## Overview

This project performs Exploratory Data Analysis (EDA) on unemployment data in India using Python. The objective is to identify regional and temporal trends in unemployment and analyze the impact of the COVID-19 pandemic on unemployment rates across different states.

## Objective

- Perform Exploratory Data Analysis (EDA) on unemployment data.
- Analyze unemployment trends across different regions.
- Study monthly unemployment patterns.
- Compare unemployment rates before and after the COVID-19 pandemic.
- Visualize relationships between unemployment, employment, and labour participation rates.

## Dataset

Dataset Name: **Unemployment in India**

The dataset contains the following information:

- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

1. Loaded the dataset using Pandas.
2. Inspected the dataset using `head()`, `shape`, `info()`, and `isnull().sum()`.
3. Cleaned the dataset by removing extra spaces from column names.
4. Converted the Date column to datetime format.
5. Performed Exploratory Data Analysis (EDA).
6. Created visualizations to identify trends and patterns.
7. Compared unemployment rates before and after COVID-19.

## Visualizations

The notebook includes the following analyses:

- Region-wise average unemployment rate
- Month-wise unemployment trend
- Time-series analysis for Maharashtra, Tamil Nadu, and Karnataka
- Top 10 states with the highest average unemployment rate
- Correlation heatmap
- Pre-COVID vs Post-COVID unemployment comparison

## Project Structure

DataScience-Task2-UnemploymentAnalysis
│
├── UnemploymentAnalysis.ipynb
├── Unemployment in India.csv
└── README.md

## How to Run

1. Clone the repository.

git clone https://github.com/meruflin/OIBSIP.git

2. Install the required libraries.

pip install pandas matplotlib seaborn jupyter

3. Open `UnemploymentAnalysis.ipynb` in Jupyter Notebook or Visual Studio Code.

4. Run all cells in sequence.

## Conclusion

This project demonstrates how Exploratory Data Analysis can be used to understand unemployment trends in India. The analysis highlights regional differences, monthly variations, and the impact of the COVID-19 pandemic through meaningful visualizations and statistical summaries.

## Author

**Meruflin Jeeva**

Oasis Infobyte Internship

Task 2 – Unemployment Analysis with Python