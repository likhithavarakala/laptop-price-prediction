# Laptop Price Prediction

## Overview
This project aims to predict laptop prices using the "Laptop Price Prediction" dataset obtained from Kaggle. The dataset consists of 1303 rows and 12 variables, including information such as laptop specifications, manufacturer details, and pricing.

## Dataset Information
**Columns:**
- **Laptop_Id:** Unique ID of the laptop
- **Company:** Manufacturer of the laptop
- **TypeName:** Type of laptop (Notebook, Ultrabook, Gaming, etc.)
- **Inches:** Screen size
- **ScreenResolution:** Screen resolution of the laptop
- **Cpu:** CPU brand, type, and speed
- **Ram:** Laptop RAM
- **Memory:** Hard Disk / SSD Memory
- **Gpu:** Graphics Processing Units (GPU)
- **OpSys:** Operating System
- **Weight:** Weight of the laptop in kg
- **Price:** Price of the laptop in INR

## Questions Explored
1. **Factors Affecting Laptop Price:**
   - Explored the aspects influencing the final cost of a laptop.
2. **Model Comparison:**
   - Compared the performance of three regression models: Multiple Linear Regression, Ridge Regression, and Lasso Regression.

## Methods Used
### Exploratory Data Analysis (EDA)
- **Data Cleaning:**
  - Removed unnecessary characters from certain columns.
  - Split columns to obtain meaningful information.
- **Visualizations:**
  - Created bar plots and boxplots to visualize the distribution of companies and mean prices.

### Multiple Linear Regression
- Explored relationships between independent variables and the dependent variable (Price).
- Identified statistically significant predictors.
- Utilized significant predictors for a more accurate model.

### Regularization Techniques
- **Ridge Regression:**
  - Introduced a regularization factor to handle multicollinearity.
  - Shrank coefficients to prevent overfitting.
- **Lasso Regression:**
  - Applied L1 regularization to minimize and eliminate coefficients.
  - Favored simpler models with fewer parameters.

### Model Comparison
- Evaluated models based on Root Mean Squared Error (RMSE) and R-squared values.
- Compared performance:
  - **Linear Regression:** RMSE 23993.28, R-square 63%
  - **Ridge Regression:** RMSE 17056.5, R-square 76%
  - **Lasso Regression:** RMSE 17183.55, R-square 75%

## Conclusion
- Identified significant factors influencing laptop prices.
- Ridge Regression demonstrated the best performance among the models.
- The project provides insights into laptop pricing and serves as a foundation for further analysis.
