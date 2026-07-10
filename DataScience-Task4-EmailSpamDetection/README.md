# Email Spam Detection with Machine Learning

## Overview

This project develops a Natural Language Processing (NLP) model to classify SMS messages as either spam or ham (legitimate messages). The project covers text preprocessing, feature extraction using TF-IDF Vectorization, model training, evaluation, and comparison of multiple machine learning classification algorithms.

## Objective

* Build a binary classification model to detect spam messages.
* Clean and preprocess text data.
* Convert text into numerical features using TF-IDF Vectorization.
* Train and compare multiple machine learning models.
* Evaluate model performance using classification metrics.
* Visualize frequently occurring words using WordClouds.

## Dataset

Dataset Name: **SMS Spam Collection Dataset**

The dataset contains SMS messages labeled as:

* **Ham** – Legitimate messages
* **Spam** – Unwanted promotional or fraudulent messages

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* NLTK
* WordCloud
* Jupyter Notebook

## Project Workflow

1. Loaded the SMS Spam Collection dataset.
2. Removed unnecessary columns and renamed the remaining columns.
3. Removed duplicate messages.
4. Analyzed the class distribution of spam and ham messages.
5. Performed text preprocessing:

   * Converted text to lowercase
   * Removed punctuation and special characters
   * Removed stopwords
   * Applied stemming
6. Converted text into numerical features using TF-IDF Vectorization.
7. Split the dataset into training and testing sets.
8. Trained two machine learning models:

   * Multinomial Naive Bayes
   * Logistic Regression
9. Evaluated the models using Accuracy, Precision, Recall, F1 Score, and Confusion Matrix.
10. Generated WordCloud visualizations for spam and ham messages.
11. Compared model performance and selected the best-performing model.

## Text Preprocessing

The following preprocessing steps were applied to improve text quality before model training:

* Lowercase conversion
* Removal of punctuation and special characters
* Stopword removal
* Word stemming using Porter Stemmer

## Feature Extraction

TF-IDF (Term Frequency–Inverse Document Frequency) was used to convert text messages into numerical feature vectors. This technique assigns higher importance to words that are significant within a message while reducing the influence of commonly occurring words.

## Machine Learning Models

The following classifiers were trained and compared:

* Multinomial Naive Bayes
* Logistic Regression

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

Among the two models, **Multinomial Naive Bayes** achieved better overall performance and was selected as the best-performing classifier.

## Visualizations

The notebook includes:

* Spam vs Ham Distribution
* Confusion Matrix (Naive Bayes)
* Confusion Matrix (Logistic Regression)
* Spam WordCloud
* Ham WordCloud

## Project Structure

```text
DataScience-Task4-EmailSpamDetection
│
├── EmailSpamDetection.ipynb
├── spam.csv
└── README.md
```

## How to Run

1. Clone the repository.

git clone https://github.com/meruflin/OIBSIP.git

2. Install the required libraries.

pip install pandas matplotlib seaborn scikit-learn nltk wordcloud jupyter

3. Open `EmailSpamDetection.ipynb` using Jupyter Notebook or Visual Studio Code.

4. Run all notebook cells in sequence.

## Conclusion

This project demonstrates the application of Natural Language Processing (NLP) and machine learning techniques for spam detection. After preprocessing the text and extracting features using TF-IDF Vectorization, two classification models were trained and evaluated. The Multinomial Naive Bayes model achieved the best performance, making it a suitable choice for detecting spam messages accurately and efficiently.

## Author

**Meruflin Jeeva**

Oasis Infobyte Internship

Task 4 – Email Spam Detection with Machine Learning
