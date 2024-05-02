# Vehicle Performance Prediction
This repository contains the code and resources for predicting vehicle performance, specifically mileage (kilometers per liter, kmpl), using regression analysis. The project aims to provide insights into the factors influencing vehicle fuel efficiency and enable data-driven decision-making in the automotive sector.

## Problem Statement
In the automotive industry, optimizing vehicle performance and fuel efficiency is crucial for reducing operational costs, minimizing environmental impact, and meeting regulatory requirements. This project focuses on predicting vehicle mileage based on technical specifications to support decision-making processes related to vehicle design, engineering, and operations.

## Dataset Information
The dataset used in this project consists of technical specifications of cars, including features such as cylinders, displacement, horsepower, weight, acceleration, model year, origin, and mileage (kmpl). The goal is to analyze the relationships between these features and predict vehicle performance accurately.
The Dataset can be accessed through [https://drive.google.com/file/d/1tB9aB-zI4o8_AXo09v2nyXQU9mSC2WdR/view?usp=sharing]

## Methodology
The project follows the following methodology:
Data Exploration: Explore the dataset to understand its structure, distributions, and relationships between variables. Perform exploratory data analysis (EDA) to gain insights into the factors influencing vehicle performance.
Data Preprocessing: Preprocess the data by handling missing values, encoding categorical variables, and scaling numerical features to prepare it for modeling.
Regression Analysis: Train regression models using techniques such as linear regression with stochastic gradient descent (SGD) to predict vehicle mileage based on technical specifications.
Model Evaluation: Evaluate the performance of the trained models using metrics such as Mean Squared Error (MSE), R-squared (R2) score, and visualizations to assess their accuracy and reliability.
Interpretation and Conclusion: Interpret the results of the regression analysis, draw conclusions about the factors influencing vehicle performance, and provide recommendations for improving fuel efficiency and optimizing vehicle operations.
## Results
The regression model demonstrates moderate performance, with an MSE of approximately 2.65 and an R2 score of around 0.73.
Negative correlations are observed between weight, cylinders, displacement, and vehicle mileage, highlighting the importance of considering these factors in vehicle design and engineering.
