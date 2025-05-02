# ML Pipeline Project

This repository contains a complete machine learning pipeline from preprocessing to model evaluation.

## Notebooks Overview
### Data Preprocessing

**Key operations:**
- `import pandas as pd`
- `df_train = pd.read_csv('application_train.csv')`
- `def null_percentage(data):`
- `print("The shape of the training dataset is: {}".format(df_train.shape))`
- `# Dropping columns that contain more than 50 percent null values per feature`

### Exploratory Data Analysis (EDA)

## Exploratory Data Analysis (EDA)

**Key operations:**
- `import numpy as np`
- `df = pd.read_csv("application_train.csv")`
- `df.head()`
- `print("The total shape of the dataframe: {}".format(df.shape))`
- `df.describe()`

### Machine Learning Models

# Home Loan Default Prediction

With the help of machine learning, it is possible to predict the chances of a person whether they would pay the loan back or not. Therefore, one would be able to understand and use different machine learning models to understand the behavior of the user and whether there is a possibility to pay back the loan. Using different machine learning models, we are going to be predicting the chances of a person paying back the loan respectively.

The output that we are going to be predicting whether a person would pay the loan back or not is a discrete variable. We are going to be using different machine learning models and understand the behaviour of different customers. In addition to this, we are going to be importing various libraries that are important for machine learning. We see that there are different libraries that could be used for deploying machine learning and deep learning models. 

We first start the project by importing various libraries that are important for data visualization purposes respectively. There are different machine learning models that we are going to be using in order to get the predictions. We see that there are some machine learning models that are important. 

We are now going to be dividing the data into training and test set. 

**Key operations:**
- `import numpy as np`
- `df_train = pd.read_csv('application_train.csv')`
- `print("The type of data that is present based on different features is:")`
- `df_train.shape`
- `df_train.select_dtypes('object').head()`

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn, scikit-learn, missingno, warnings

## How to Run
1. Run `Data Preprocessing.ipynb` to clean and prepare the data.
2. Run `Exploratory Data Analysis (EDA).ipynb` for visualizations and data insights.
3. Run `Machine Learning Models.ipynb` to train and evaluate multiple ML models.

## Notes
- Dataset used: `application_train.csv`, `application_test.csv`
- Imputation strategies used: mean, median, mode
- Encoding: One-hot encoding for categorical variables
- Feature scaling applied
