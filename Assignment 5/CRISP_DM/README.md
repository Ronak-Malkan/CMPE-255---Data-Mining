### [Read the Full Analysis on Medium Here!](https://medium.com/@ronakmalkan2062001/navigating-customer-churn-with-crisp-dm-a-kaggle-dataset-case-study-1910fd962a40)

# Customer Churn Prediction Using CRISP-DM Methodology

This project applies the Cross-Industry Standard Process for Data Mining (CRISP-DM) methodology to predict customer churn based on a dataset sourced from Kaggle. The aim is to utilize data mining techniques to identify key predictors of churn and deploy a predictive model to help businesses develop effective customer retention strategies.

## Project Overview

The CRISP-DM methodology guides the data mining process through six phases:

1. **Business Understanding**: Define the project objectives and requirements from a business perspective.
2. **Data Understanding**: Collect initial data, describe data, explore data, and verify data quality.
3. **Data Preparation**: Select data, clean data, construct data, integrate data, and format data.
4. **Modeling**: Select modeling techniques, design test, build model, and assess model.
5. **Evaluation**: Evaluate results, review process, and determine next steps.
6. **Deployment**: Plan deployment, plan monitoring and maintenance, produce final report, and review project.

## Tasks and Process

- **Data Exploration and Visualization**: We analyzed the distribution of the target variable (churn) and examined correlations between features to identify significant predictors.
- **Data Preparation**: Our approach included handling missing values, encoding categorical variables, and normalizing numerical features to prepare data for modeling.
- **Model Training**: We implemented a RandomForestClassifier due to its efficacy with imbalanced datasets, focusing on optimizing for recall to better identify churned customers.

## Results

The model achieved an accuracy of 87%, with a precision of 100% for churn predictions, indicating that it is highly reliable when predicting churn. However, the recall for churned customers was 25%, highlighting a need for improvement in identifying actual churn cases.

## Code Critique and Improvements

- **Data Preparation**: The code effectively handled missing values and encoded categorical variables. However, improvement could be made by ensuring that normalization is only applied to training data to prevent data leakage.
- **Modeling**: While the RandomForestClassifier was a solid choice, the model's performance could benefit from hyperparameter tuning and possibly using more advanced ensemble techniques or deep learning methods to improve recall.
- **General**: The code would benefit from modularization. Wrapping parts of the code into functions or classes could improve readability and reusability.
