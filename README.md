# Model Performance Analysis: Predicting the Target Variable

This repository contains a quick performance analysis of three machine learning models—**Linear Regression**, **Decision Tree**, and **Random Forest**—to identify the best-performing model for predicting the target variable.

## Summary of Results

After evaluating the models based on three performance metrics (MAE, MSE, and R²), the **Random Forest** model emerged as the best performer due to its balance of accuracy, robustness, and ability to handle complex patterns.

### Performance Metrics Comparison:

| Metric         | Linear Regression | Decision Tree | Random Forest |
|----------------|-------------------|---------------|---------------|
| **MAE**        | 361.07            | 479.23        | 384.17        |
| **MSE**        | 800,546.46        | 1,222,025.30  | 792,336.30    |
| **R²**         | 0.17              | -0.26         | 0.18          |

## Final Model: Random Forest

The **Random Forest** model was selected as the final model due to its superior performance:

- **MAE**: 384.17  
- **MSE**: 792,336.30  
- **R²**: 0.18  

### Why Random Forest was Chosen:
1. **Lower MSE**: Random Forest
