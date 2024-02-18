# Project Name
> ### **Assignment - Advanced Regression | House Price Prediction**


## Table of Contents
* [General Info](#general-information)
* [Implementation Strategy](#implementation-strategy)
* [Technologies Used](#technologies-used)
* [Conclusion](#conclusion)
* [Acknowledgements](#acknowledgements)


## General Information
### Problem Statement:
Surprise Housing, a US-based company, aims to enter the Australian market by utilizing data analytics to purchase undervalued houses and sell them at a profit. The company has gathered a dataset of house sales in Australia to facilitate this endeavor. This implementation involves building a regression model using regularization techniques to predict the actual value of prospective properties and determine their investment viability.

### Business Objectives:
1. Identify Significant Variables: Determine which variables significantly influence house prices.
2. Assess Model Performance: Evaluate how well the identified variables explain variations in house prices.
3. Optimize Regularization Parameters: Find the optimal values of lambda for ridge and lasso regression to enhance predictive accuracy.

### Business Goal:
- Develop a regression model that predicts house prices based on available independent variables.
- Utilize the model to guide management decisions regarding investment opportunities, focusing on areas with high potential returns.
- Gain insights into the pricing dynamics of the Australian housing market to formulate effective business strategies.

## Implementation Strategy
1. Understand Problem Statement
2. Data Sourcing & Understanding
3. Data Cleaning:
   - Handling Null/Missing values
   - Dealing with Invalid values
   - Analyzing and dropping unmatched behavioral fields
   - Data filtering
   - Imputing rows
   - Managing Outliers
4. Exploratory Data Analysis (EDA) on cleaned data
5. Model Building and Evaluation
6. Lasso & Ridge Regression
7. Observation and Inference
8. Conclusion


## Conclusion
- The equation shows how different features affect the house's sale price.
- The equation suggests that features such as GrLivArea, OverallQual, OverallCond, TotalBsmtSF, and GarageArea have a relatively stronger positive influence on SalePrice, as indicated by their coefficients being positive and relatively larger in magnitude.
- Conversely, features like KitchenQual_TA, MSSubClass, KitchenAbvGr, and PropAge have a negative impact on SalePrice, as their coefficients are negative.
- Features with smaller coefficients (e.g., KitchenAbvGr, WoodDeckSF) contribute less to the prediction of SalePrice.


## Technologies Used
- Python
- Python Libraries:
    - NumPy
    - Pandas
- Data Visualization
    - Matplotlib
    - Seaborn
- Editor:
    - Jupyter Notebooks
- Approach:
    - Exploratory Data Analysis (EDA)
    - Machine learning concepts
    - Simple and Advanced Linear Regression
    - Multiple Linear Regression
    - Lasso & Ridge Regression
    - Buiding a model with Linear Regression


## Acknowledgements

- This project is done as a part of IIIT PGP Case Study.
- References:
    1. **Python**
    - [Start with Python](https://www.python.org/)
    2. **NumPy**
    - [NumPy official doc](https://numpy.org/doc/stable/)
    3. **Pandas**
    - [Pandas official doc](https://pandas.pydata.org/pandas-docs/stable/)
    4. **MatPlotlib**
    - [MatPlotlib official doc](https://matplotlib.org/stable/users/index.html)
    5. **Seaborn**
    - [Seaborn official doc](https://seaborn.pydata.org/)
    6. **EDA:**
    - [Wikipedia - Exploratory Data Analysis](https://en.wikipedia.org/wiki/Exploratory_data_analysis)


## Contributors:
1. Sahadeb Patro
