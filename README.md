# Regression-Based Business Insights & Model Interpretation

## Repository Overview

This project applies **Simple Linear Regression** and **Multiple Linear Regression** to analyze business data and identify the factors influencing sales performance. The analysis compares both models and recommends the most suitable model for business forecasting.

---

# Repository Structure

```
part3_regression_insights/
│
├── data/
│   └── business_regression_data.xlsx
│
├── analysis/
│   ├── regression_workbook.xlsx
│   ├── model_comparison.md
│   └── residual_analysis.md
│
├── outputs/
│   ├── regression_summary.xlsx
│   ├── simple_regression_output.png
│   ├── multiple_regression_output.png
│   ├── residuals_preview.png
│   ├── model_comparison_preview.png
│   ├── final_recommendation.md
│   └── model_equations.md
│
└── README.md
```

---

# Objective

The objective of this project is to:

* Build a Simple Linear Regression model.
* Build a Multiple Linear Regression model.
* Compare the performance of both models.
* Interpret regression coefficients and statistical measures.
* Analyze residuals.
* Recommend the best model for business decision-making.

---

# Dataset

The dataset contains business-related information including:

* Sales (Dependent Variable)
* Marketing Spend
* Customer Age
* Customer Income
* Gender
* Region

Categorical variables were converted into **dummy variables** before building the multiple regression model.

---

# Regression Models

## Simple Linear Regression

Dependent Variable:

* Sales

Independent Variable:

* Marketing Spend

Purpose:

* Evaluate the effect of marketing expenditure on sales.

---

## Multiple Linear Regression

Dependent Variable:

* Sales

Independent Variables:

* Marketing Spend
* Customer Age
* Customer Income
* Gender (Dummy Variable)
* Region (Dummy Variable)

Purpose:

* Improve prediction accuracy by considering multiple business factors.

---

# Model Comparison

| Metric              | Simple Regression | Multiple Regression |
| ------------------- | ----------------: | ------------------: |
| R²                  |              0.68 |                0.89 |
| Adjusted R²         |              0.67 |                0.88 |
| Predictors          |                 1 |                   5 |
| Prediction Accuracy |          Moderate |                High |
| Residual Error      |            Higher |               Lower |

**Selected Model:** Multiple Linear Regression

---

# Residual Analysis

Residual analysis indicates:

* Residuals are randomly distributed.
* Mean residual is approximately zero.
* Constant variance is observed.
* No significant outliers were detected.
* Model assumptions are reasonably satisfied.

---

# Business Recommendation

The Multiple Linear Regression model is recommended because it:

* Produces higher prediction accuracy.
* Achieves a higher R² value.
* Reduces prediction error.
* Captures demographic and regional effects.
* Supports better business planning and forecasting.

---

# Assumptions

The regression analysis assumes:

* Linear relationship between variables.
* Independent observations.
* Normally distributed residuals.
* Homoscedasticity (constant variance).
* No severe multicollinearity.

---

# Limitations

* Results depend on the available dataset.
* External economic factors are not included.
* Future business conditions may affect prediction accuracy.
* Model performance should be validated with new data periodically.

---

# Screenshots Included

* simple_regression_output.png
* multiple_regression_output.png
* residuals_preview.png
* model_comparison_preview.png

---

# Conclusion

The Multiple Linear Regression model provides the best overall performance for predicting sales and is recommended for business forecasting, performance analysis, and strategic decision-making.
