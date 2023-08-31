# Project Name: Energy and Weather Data Analysis

## Introduction
This project involves the analysis of energy consumption and weather data to gain insights and make predictions. The project is divided into several tasks, each addressing specific aspects of the data.

## Task 1: Data Preprocessing
In this task, we start by loading two datasets: weather data and energy data. We preprocess the data, aggregating it by date to create a consolidated dataset for further analysis.

## Task 2: Dataset Splitting
The dataset is split into training and testing sets. The training set includes the majority of the data, while the testing set consists of the most recent 31 days. These sets are used for model training and evaluation.

## Task 3: Energy Consumption Prediction
We utilize Linear Regression to predict energy consumption based on weather and other factors. The root mean squared error (RMSE) is used to evaluate the model's accuracy. Predicted values are saved in the "task3.csv" file.

## Task 4: Temperature Classification
We classify temperatures as high (above 35°C) or not high using Logistic Regression. The F1 score is used to evaluate the classification model's performance. The results are saved in the "task4.csv" file.

## Task 5: Time-Based Analysis
We analyze energy consumption patterns based on time of day. For example, we observe that air conditioning usage is highest during the night, while microwave usage peaks during the day. This analysis helps identify usage trends.

## Conclusion
This project provides valuable insights into energy consumption patterns and temperature classifications based on weather data. The code and generated files are available for further analysis or use.
