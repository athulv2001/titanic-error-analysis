# Titanic Survival Prediction – Error Analysis

## Objective
The objective of this notebook is to analyze model prediction errors and understand how different types of errors affect different passenger groups.

## Why Error Analysis Matters
Different prediction errors lead to different real-world consequences. Understanding these errors helps identify model limitations and potential bias.

## Error Types
- False Positives
- False Negatives

## Group-Level Analysis
This section will explore how errors vary across groups such as gender, passenger class, and age.

## Observations
Key patterns and insights from the analysis will be summarized here.

## Initial Observations

- False negatives are particularly important in this problem because predicting non-survival for passengers who actually survived represents a critical failure.
- Passengers from third class may experience a higher rate of false negatives due to historical and social priorities present in the data.
- Such patterns suggest that the model may inherit historical bias rather than learning purely objective survival factors.
