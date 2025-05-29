# Spotify Song Popularity Analysis
Project Overview
For the final project in my CISC3225:Data Tools and Algorithm course at Brooklyn College, I analyzed  a dataset of approximately 114,000 spotify songs to uncover the factors influencing song popularity. Using Python libraries such as pandas, NumPy, scikit-learn, and statistical testing methods (Kruskal-Wallis, Chi-Squared), I performed extensive data cleaning, exploratory data analysis (EDA), cluster analysis, feature engineering, and machine learning modeling. 

Key Steps
Data Preparation: Handled missing values, transformed data types, and prepared categorical variables for modeling using one-hot encoding.
Cluster Analysis: Applied K-Means clustering to identify distinct audio profiles within the dataset and visualized these clusters using Principal Component Analysis (PCA).
Feature Engineering: Created categorical features representing the top 20 artists and genres, and transformed the duration variable using a logarithmic transformation.
Exploratory Data Analysis: Identified trends in song popularity across different genres, audio features, and categorical variables.
Model Development: Built Random Forest Regression models to predict song popularity based on both categorical and continuous variables. I then developed a Random Forest Classifier to predict broad song genres based on audio features.
Model Evaluation: Assessed model performance using R² scores for regression models and F1-scores for classification models. Conducted statistical tests (Kruskal-Wallis, Chi-Squared) to evaluate the significance of genre and explicit content on popularity.

Data Source: https://www.kaggle.com/datasets/thedevastator/spotify-tracks-genre-dataset

Read the full written report here: https://docs.google.com/document/d/1oI0G2-on5nPM-Z1wLNkL9xNwBcJpx6TzH5r7Srn6zdw/edit?tab=t.0
