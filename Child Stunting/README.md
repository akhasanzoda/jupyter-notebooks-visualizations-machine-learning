# Pediatric Growth Pattern Analysis

## Project Overview
This repository contains the analysis of pediatric growth patterns based on a dataset of children's ages, heights, genders, and nutritional statuses. The primary goal was to uncover insights into the growth trajectories and identify clusters of similar growth patterns. Advanced analytics, including regression analysis and clustering, were employed to achieve this objective.

## Objectives
- **Exploratory Data Analysis (EDA)**: To understand the data distribution, identify any patterns or anomalies, and prepare the data for further analysis.
- **Statistical Testing**: To determine if there are significant differences in height across genders and different nutritional statuses.
- **Regression Analysis**: To develop a model that can predict the height of a child based on age, gender, and nutritional status.
- **Clustering**: To identify natural groupings in the data that represent different growth patterns.

## Methods
- **Data Cleaning**: Renaming columns for clarity, encoding categorical variables, and handling missing values.
- **Visualization**: Creating distribution plots, boxplots, and scatter plots to visualize the data and the results of the analyses.
- **Statistical Analysis**: Performing t-tests and ANOVA to assess differences in height across different groups.
- **Machine Learning**: Using XGBoost for regression analysis and K-Means for clustering.

## Results
- **Statistical Testing**: Significant differences were found in height between males and females and across different nutritional statuses.
- **Regression Model**: A linear regression model was developed, achieving an R-squared of 0.90, indicating a high level of variance in height explained by the model.
- **Clustering**: Three distinct clusters were identified, representing different stages of growth, with the cluster centroids providing a reference for the average height within each age group.

## Conclusions
The analysis revealed that gender and nutritional status are significant factors in the variation of children's heights. The growth patterns showed a clear progression with age, and the clustering provided a visual and analytical method to categorize these patterns. These findings can assist healthcare professionals in understanding typical growth trajectories and tailoring interventions for children's health.

How to Run
Instructions on how to run the analysis, including installing dependencies, setting up the environment, and executing the scripts/notebooks.

## Dependencies
Python 3.8+
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
