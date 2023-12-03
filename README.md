# Regression and Imputation Comparison

This repository contains code and analysis for a regression task on predicting median house values in an area. The project was undertaken during the 3rd year of the Bachelor's degree at Newcastle University as part of the Data Engineering course. The main focus is on comparing the performance of two imputation methods, KNN imputation and MICE (Iterative Imputation), in combination with the regression models.

## Imputation Methods

### KNN Imputation
1. Impute missing values in the incomplete dataset (`Houses_0.5_MAR.csv`) using KNN imputation.
2. Train a linear regression model on the imputed dataset (M1).
3. Evaluate and note the performance of the model in predicting median house values.

### MICE (Iterative Imputation)
1. Impute missing values in the incomplete dataset using MICE.
2. Train another linear regression model on the imputed dataset (M2).
3. Evaluate and note the performance of this model.

## Getting Started

To reproduce the results, follow these steps:

1. Install required dependencies using `requirements.txt`.
2. Navigate to the project directory
3. Run the provided notebook.
4. Run the main Jupyter notebook and explore the generated plots/metrics to understand models performance.

## Results

## Conclusion

## Contributors

- Dimitrios Poulimenos ([dpoulimenos](https://www.linkedin.com/in/dpoulimenos/)) - Initial work 
