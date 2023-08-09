# FIFA Player Analysis and Rating Prediction

This repository contains code for analyzing FIFA player statistics and performing a linear regression model to predict player ratings. The code is written in Python and utilizes various libraries for data analysis, visualization, and modeling.

## Table of Contents
1. [Introduction](#introduction)
2. [Dependencies](#dependencies)
3. [Data Cleaning](#data-cleaning)
4. [Data Analysis](#data-analysis)
5. [Exploratory Data Analysis](#exploratory-data-analysis)
6. [Modeling](#modeling)
7. [Results](#results)

## Introduction
This project focuses on analyzing FIFA player statistics using a dataset and building a linear regression model to predict player ratings based on various attributes. The code provides step-by-step instructions on data cleaning, analysis, visualization, and modeling.

## Dependencies
To run the code in this repository, you need the following dependencies:
- Python (>=3.6)
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Eli5
- Missingno
- Other necessary libraries (install using `pip` or `conda`)
## Data Cleaning
- The code begins with data cleaning by removing unnecessary columns.
- Missing values in 'Height' and 'Weight' are handled by dropping corresponding rows.

## Data Analysis
- The dataset is analyzed to determine the number of countries and clubs represented.
- Top countries and clubs with the highest number of players are identified.
- Maximum potential and overall performance players are highlighted.

## Exploratory Data Analysis
- Visualizations explore relationships between player attributes and ratings.
- Heatmaps show correlations between various attributes.
- Boxen plots compare player attributes based on age and preferred foot.

## Modeling
- Data is preprocessed, including converting categorical variables.
- Linear Regression is applied to predict player ratings.
- R-squared score and RMSE are calculated to evaluate the model's performance.
- Permutation Importance analysis is conducted to identify key features.

## Results
- The code provides insights into player attributes, their impact on ratings, and key features affecting predictions.
- Visualizations aid in understanding trends and relationships within the dataset.

