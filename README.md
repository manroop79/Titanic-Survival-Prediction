# Titanic-Survival-Prediction

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Visualizations](#visualizations)
- [Feature Engineering](#feature-engineering)
- [Logistic Regression](#logistic-regression)
- [Survival Prediction](#survival-prediction)
- [Model Evaluation](#model-evaluation)
- [Results](#results)

## Project Overview
This project focuses on predicting the survival of passengers aboard the Titanic using machine learning techniques. Leveraging the dataset's attributes, the goal is to build a robust model capable of accurately classifying passengers as survivors or non-survivors based on various features.
It also explores the classifications of those survived on the basis of gender, passenger class, income levels, etc.

## Data Sources
The dataset used in this analysis was sourced from titanic_train.csv and titanic_test.csv. The train dataset comprises of a comprehensive record of Titanic passengers, including various attributes such as age, class, fare, and survival status whereas the test dataset does not contain the record of the survival status.

## Tools Used
The analysis was conducted using a variety of tools and technologies, including:
- Python
- Scikit-learn
- Plotly
- Jupyter Notebooks
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning and Preprocessing
The raw dataset underwent rigorous data cleaning and preprocessing, including handling missing values, addressing outliers, using pd.get_dummies to generate linear data and standardizing data formats to ensure the dataset's integrity and prepare it for analysis.

## Exploratory Data Analysis (EDA)
The exploratory data analysis phase focused on understanding the dataset's characteristics, uncovering patterns, and identifying potential correlations between different features. Various statistical and visual exploration techniques were employed to gain insights into the data's distribution and characteristics.
Insights were discovered related to survival based on gender, Pclass, etc.

## Visualizations
A range of visualizations, including bar plots, histograms, boxplots and plotly visualisations  were generated to provide a comprehensive understanding of the data. These visual representations helped in identifying key trends and relationships within the dataset.

## Feature Engineering
The feature engineering process involved creating new features and transforming existing ones to improve the model's predictive performance. Techniques such as one-hot encoding and feature scaling were applied to enhance the dataset's predictive power.

## Logistic Regression
Utilizing the logistic regression algorithm, a predictive model was trained to classify passengers into survival and non-survival groups based on the engineered features and other relevant attributes.

## Survival Prediction
The trained logistic regression model was used to predict survival probabilities for new data points, providing valuable insights into the likelihood of passenger survival under various scenarios.

## Model Evaluation
The model's performance was evaluated using various metrics, including accuracy, precision, recall, and F1 score, to assess its effectiveness in predicting passenger survival.

## Results
The results of the analysis shed light on the key determinants of survival aboard the Titanic, highlighting the significance of certain demographic and socio-economic factors in influencing the chances of survival.
