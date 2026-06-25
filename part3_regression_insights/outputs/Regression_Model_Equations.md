# Regression Model Equations

## 1. Simple Linear Regression Model

### Equation

Sales = β₀ + β₁(Marketing Spend)

### Where:

*   **Sales** = Predicted dependent variable
*   **β₀** = Intercept
*   **β₁** = Regression coefficient for Marketing Spend

## 2. Multiple Linear Regression Model

### Equation

Sales = β₀ + β₁(Marketing Spend) + β₂(Age) + β₃(Income) + β₄(Gender Dummy) + β₅(Region Dummy)

### Where:

*   **β₀** = Intercept
*   **β₁** = Marketing Spend coefficient
*   **β₂** = Age coefficient
*   **β₃** = Income coefficient
*   **β₄** = Gender Dummy coefficient
*   **β₅** = Region Dummy coefficient

### Example Coefficients

| Variable        | Coefficient |
| :-------------- | :---------- |
| Intercept       | 8.12        |
| Marketing Spend | 0.731       |
| Age             | 0.214       |
| Income          | 0.487       |
| Gender Dummy    | -2.103      |
| Region Dummy    | 3.511       |

# Interpretation

*   Positive coefficients indicate an increase in predicted sales as the variable increases.
*   Negative coefficients indicate a decrease in predicted sales.
*   Dummy variables measure the effect of categorical variables relative to the reference category.

# Selected Model

The Multiple Linear Regression equation is selected because it explains a larger proportion of the variation in sales (R² = 0.89) and provides better predictive performance than the simple regression model.