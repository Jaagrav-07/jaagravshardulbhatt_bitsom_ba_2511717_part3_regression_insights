# Model Comparison

# Objective

The objective of this regression analysis is to identify the factors most strongly associated with **monthly sales performance** across retail stores. Three regression models were developed and compared to determine which model provides the most accurate and meaningful predictions for business decision-making.

---

# Model 1: Simple Linear Regression – Marketing Spend

## Dependent Variable

**Monthly Sales**

## Independent Variable

**Marketing Spend**

### Interpretation

This model examines the relationship between marketing expenditure and monthly sales. It evaluates whether increased investment in marketing is associated with higher sales performance.

### Business Usefulness

* Estimates the impact of promotional spending on revenue.
* Supports budgeting and marketing investment decisions.
* Provides a simple measure of marketing effectiveness.

### Limitations

* Does not account for customer footfall.
* Ignores inventory availability.
* Excludes customer ratings and satisfaction.
* Does not consider regional or store-type differences.

---

# Model 2: Simple Linear Regression – Footfall

## Dependent Variable

**Monthly Sales**

## Independent Variable

**Footfall**

### Interpretation

This model evaluates whether stores with higher customer traffic tend to generate greater monthly sales.

### Business Usefulness

* Measures the relationship between customer visits and sales.
* Helps estimate the value of increasing store traffic.
* Assists in evaluating promotional campaigns that drive customer visits.

### Limitations

* Does not consider marketing expenditure.
* Excludes inventory availability.
* Ignores discount strategies.
* Does not account for customer ratings or regional factors.

---

# Model 3: Multiple Linear Regression

## Dependent Variable

**Monthly Sales**

## Independent Variables

* Marketing Spend
* Footfall
* Inventory Availability (%)
* Average Discount (%)
* Customer Rating
* Region (Dummy Variables)
* Store Type (Dummy Variables)

### Interpretation

This model evaluates the combined influence of marketing, operational, customer, and store-specific factors on monthly sales performance.

### Business Usefulness

* Provides a comprehensive explanation of sales performance.
* Captures the combined effect of multiple business drivers.
* Improves prediction accuracy compared with simple regression models.
* Supports strategic planning, forecasting, and resource allocation.

### Limitations

* Regression identifies statistical associations rather than direct causation.
* Results depend on the quality and completeness of the available data.
* Model performance may change if business conditions or customer behavior evolve.

---

# Model Comparison Summary

| Model               | Variables Used                                                                                                            | Expected R² | Business Value |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------- | :---------: | :------------: |
| Simple Regression 1 | Marketing Spend                                                                                                           |   Moderate  |     Medium     |
| Simple Regression 2 | Footfall                                                                                                                  |   Moderate  |     Medium     |
| Multiple Regression | Marketing Spend, Footfall, Inventory Availability, Average Discount, Customer Rating, Region & Store Type Dummy Variables |   Highest   |      High      |

---

# Significant Variables

The analysis indicates that the following variables are expected to contribute significantly to monthly sales performance:

* Marketing Spend
* Footfall
* Inventory Availability
* Customer Rating
* Average Discount Percentage
* Region (Dummy Variables)
* Store Type (Dummy Variables)

Together, these variables provide a comprehensive explanation of variations in sales across retail stores.

---

# Final Model Selected

## Multiple Linear Regression

### Reason for Selection

The Multiple Linear Regression model was selected because it considers several business drivers simultaneously and provides stronger explanatory power than either of the simple regression models.

Compared with the simple models, it offers:

* Higher predictive accuracy.
* Greater explanatory power (higher R²).
* Better representation of real-world business conditions.
* Improved support for forecasting and decision-making.
* More reliable insights into the factors influencing monthly sales.

---

# Conclusion

Based on the comparative analysis, the **Multiple Linear Regression** model is the preferred model for predicting monthly sales performance. By incorporating marketing, operational, customer, and store-specific variables, it provides the most comprehensive and reliable foundation for business forecasting and strategic decision-making.
