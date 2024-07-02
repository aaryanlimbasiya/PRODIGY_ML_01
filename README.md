# PRODIGY_ML_01
Here Is First Task Assigned To Me By PRODIGYINFOTECH.

# Objective

The aim of the linear regression model was to predict house prices in the Boston Housing dataset based on features such as the number of rooms (rm), the percentage of lower status population (lstat), and the pupil-teacher ratio (ptratio).

# Process Summary

# 1.Data Understanding & Cleaning:

The dataset was loaded and inspected for missing values, which were absent. Key features (rm, lstat, ptratio) were selected based on domain knowledge and correlation analysis.

# 2.Exploratory Data Analysis (EDA):

Pairplots and a heatmap of the correlation matrix provided insights into relationships between variables. 

# 3.Data Preparation:

The selected features were standardized using StandardScaler to ensure they are on a comparable scale.

# 4.Model Building:

A linear regression model was built using the selected and scaled features. Recursive Feature Elimination (RFE) was used to confirm the importance of the chosen features.

# 5.Residual Analysis:

Residuals from training data were plotted to check for patterns, ensuring no obvious deviations from linearity.

# 6.Model Evaluation:

The model's performance was evaluated on the test set using Mean Squared Error (MSE) and R-squared (R²) metrics. MSE provided a measure of the average squared difference between observed and predicted values. R² indicated how well the model explained the variance in the target variable.

# 7.Visualization:

Plots of predicted vs actual values and residuals vs predicted values were created to visually assess model performance. Results

Mean Squared Error (MSE): [Specific value from code output] R-squared (R²): [Specific value from code output] Model Coefficients: rm: [Coefficient value] lstat: [Coefficient value] ptratio: [Coefficient value]

# Key Insights:

The selected features (rm, lstat, ptratio) were found to be significant predictors of house prices. The R² value indicates how well these features collectively explain the variance in house prices, with a higher R² indicating a better fit. Residual plots did not show significant patterns, indicating a good fit of the linear regression model to the training data.

# Conclusion

The linear regression model effectively predicted house prices based on the selected features. While the model provides valuable insights, additional features and more sophisticated models could further improve accuracy. The current model is a robust starting point for understanding the key factors influencing house prices in the Boston area.
