# titanic-error-analysis
Error analysis and bias exploration of a Titanic survival classifier

# Titanic Survival Prediction – Error Analysis

## Problem Statement
The goal of this project is to analyze the errors made by a machine learning model that predicts passenger survival on the Titanic. Instead of focusing only on accuracy, this project emphasizes understanding where and why the model fails.

## Dataset
The dataset used is the classic Titanic passenger dataset, which contains demographic and ticket-related information such as age, gender, passenger class, fare, and survival status.

## Objective
The primary objective of this project is to perform error analysis and identify potential bias in model predictions across different passenger groups.

## Methodology
A simple classification model is trained to predict survival outcomes. Model performance is evaluated using a confusion matrix, with particular attention to false positives and false negatives. Error patterns are analyzed across passenger groups such as gender and ticket class.

## Key Insights
This section will summarize the main findings from the error analysis, including observed bias patterns and limitations of the model.

## Group-Level Analysis

The prediction errors are not evenly distributed across passenger groups. Gender and passenger class strongly influence model behavior.

Female passengers tend to have fewer false negatives, as their higher survival rates are well represented in the data. In contrast, third-class passengers may experience a higher number of false negatives, where survival is underestimated by the model.

These patterns suggest that the model relies heavily on historical survival trends, which can result in biased predictions for underrepresented or lower-priority groups.

