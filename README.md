# Assignment 8: Supervised Learning Classification

## Student Information

**Name:** OBAJE PAUL
**Course:** MACHINE LEARNING

## Project Overview

This project demonstrates a supervised machine learning classification workflow using the Breast Cancer Wisconsin dataset. The objective is to classify observations into malignant and benign classes based on diagnostic features.

The project covers data preprocessing, exploratory data analysis, model training, evaluation, interpretation, and deployment considerations.

## Dataset

The Breast Cancer Wisconsin dataset was obtained from the Scikit-learn datasets collection.

The dataset contains numerical diagnostic features and a binary target representing the two classes.

## Data Preprocessing

The following preprocessing steps were performed:

* Checked for missing values
* Checked for duplicate records
* Removed duplicate records
* Removed missing records where necessary
* Separated features from the target variable
* Divided the data into training and testing sets using an 80:20 split
* Standardized features for Logistic Regression

## Exploratory Data Analysis

The analysis included:

* Target class distribution
* Feature correlation analysis
* Feature relationships with the target classes

The correlation analysis showed that several diagnostic features have strong relationships with each other. This indicates that some features contain overlapping information.

## Machine Learning Models

Two classification models were implemented:

1. Logistic Regression
2. Random Forest Classifier

## Model Evaluation

The models were evaluated using accuracy, precision, recall, F1-score and ROC-AUC.

| Model               | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
| ------------------- | -------: | --------: | -----: | -------: | ------: |
| Logistic Regression |   98.25% |    98.61% | 98.61% |   98.61% |  99.54% |
| Random Forest       |   95.61% |    95.89% | 97.22% |   96.55% |  99.31% |

## Best Model

Logistic Regression achieved the best overall performance on the test data.

It recorded the highest accuracy, precision, recall, F1-score and ROC-AUC compared with Random Forest. Based on these results, Logistic Regression was selected as the preferred model for this project.

## Model Interpretation

Confusion matrices were used to examine correct and incorrect classifications. ROC curves were also used to compare the ability of both models to distinguish between the two classes.

The high ROC-AUC scores indicate that both models performed very well at separating the two classes.

## Deployment and Monitoring

The selected model could be deployed as an API using a framework such as Flask or FastAPI. The model and preprocessing steps should be saved together so that new data is processed consistently.

After deployment, the system should be monitored for missing or invalid inputs, changes in incoming data, and decreases in model performance. The model can be retrained when its performance declines or when newer representative data becomes available.

## Files

* `Assignment_8_Supervised_Learning_Classification_OBAJE_PAUL.ipynb` — Complete Google Colab notebook containing the analysis and machine learning implementation.
* Assignment 8 PDF report — Project summary and findings.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* GitHub

## Google Colab

The completed notebook is available through the Google Colab link provided with the assignment submission.
