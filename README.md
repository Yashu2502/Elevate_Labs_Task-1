# Elevate_Labs_Task-1
EDA on Customer Personality Analysis dataset

### Data Overview : 
- 2,240 rows and 29 columns.
- 2D data.
### Data Cleaning :
- Handled missing values(24) in income column with the median using fillna method.
- Standardized categorical fields(education and marital_status). 
- Converted dt_customer to proper datetime format.
- Renamed all columns to clean lowercase snake_case.
### Univariate Analysis :
- Most Customers are Graduates or Masters.
- Marital Status is mostly Married or Together.
- Income distribution is right-skewed.
### Bivariate Analysis :
- Higher education often correlates with higher income.
- Customers who spend more on wine also tend to spend more on meat products.
- recency varies widely across income groups.
### Correlation Insights :
- Stronger positive correlations among product spending categories.
- income positively correlates with spending, but not with recency.
