## Project Overview

This project involves forecasting oil production using various machine learning models. It aims to develop accurate predictive models to estimate future oil production based on historical data from the Permian Basin.

## Introduction

Accurate forecasting of oil production is crucial for operational planning and strategic decision-making in the oil and gas industry. Traditional methods often fall short in capturing the complex patterns in production data. This project explores machine learning techniques to enhance prediction accuracy.

## Dataset

The dataset comprises production and reservoir data from approximately 300-400 wells in the Permian Basin, sourced from Enverus and the Railroad Commission of Texas' Oil & Gas Division.

## Data Preprocessing

- **Missing Values**: Handled using imputation techniques.
- **Outliers**: Detected and removed to ensure data quality.
- **Standardization**: Applied to input features and target variables.

## Exploratory Data Analysis (EDA)

EDA was conducted to understand data distribution, correlations, and patterns, guiding feature selection and model development.

## Methodology

### Models Used

1. **Linear Regression**
2. **Lasso Regression**
3. **Ridge Regression**
4. **K-Nearest Neighbors (KNN)**
5. **Decision Trees**
6. **Random Forest**
7. **XGBoost**
8. **ARIMA (for time-series analysis)**

### Workflow

1. **Data Collection and Preprocessing**
2. **Feature Selection**
3. **Data Transformation**
4. **Dataset Splitting**
5. **Model Training and Hyperparameter Tuning**
6. **Model Evaluation and Testing**

### Performance Metrics

- **R² Score**: Measures the proportion of variance in the dependent variable predictable from the independent variables.
- **RMSE**: Root Mean Square Error, indicating the average magnitude of errors between observed and predicted values.

## Results and Discussion

The Random Forest model performed the best, achieving an R² score close to 0.99 and the lowest RMSE among all models. The empirical results highlight the superiority of machine learning models over traditional methods in forecasting oil production.

## Conclusion

This project demonstrates the potential of machine learning in improving the accuracy of oil production forecasting. The data-driven approach provides significant value to the oil and gas industry, enabling optimized resource allocation, risk mitigation, and enhanced profitability.

## Future Work

Future research could explore the integration of ensemble methods and deep learning architectures to address the nonlinear and dynamic nature of oil production data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
