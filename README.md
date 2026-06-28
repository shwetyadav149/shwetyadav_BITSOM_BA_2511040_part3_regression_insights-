# Regression-Based Business Insights & Model Interpretation

## Business Problem

The retail leadership team wanted to identify the major factors influencing monthly store sales in order to improve decision making related to marketing investments, staffing, inventory management, and discount strategies.

## Dataset Description

The dataset contains monthly operational and sales information for retail stores across multiple regions and store types.

### Dependent Variable

* monthly_sales

### Independent Variables

* marketing_spend
* footfall
* avg_discount_pct
* staff_count
* inventory_availability_pct
* competitor_distance_km
* customer_rating
* holiday_flag
* region
* store_type

## Regression Approach

The analysis included:

1. Data cleaning and missing value treatment.
2. Dummy variable creation for categorical variables.
3. Simple linear regression models.
4. Multiple linear regression model.
5. Residual analysis.
6. Model comparison.

## Dummy Variable Approach

Categorical variables were converted into dummy variables using one-hot encoding with drop_first=True to avoid multicollinearity.

Reference categories:

* Region Reference Category: East
* Store Type Reference Category: Mall

## Model Comparison Summary

The multiple regression model achieved the highest explanatory power and outperformed individual simple regression models.

## Final Model Selected

The final selected model was the multiple regression model including marketing spend, footfall, inventory availability, customer rating, discount percentage and dummy variables.

## Business Recommendation

Leadership should focus primarily on improving:

* Marketing effectiveness
* Customer footfall
* Inventory availability
* Customer experience

## Assumptions and Limitations

* Regression identifies associations but does not prove causation.
* External factors such as seasonality and local events were not included.
* Results depend on historical patterns.

## Screenshots Included

* Simple Regression Output
* Multiple Regression Output
* Residual Analysis Preview
* Model Comparison Preview
