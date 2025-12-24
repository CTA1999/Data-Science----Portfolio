### Project Overview
This project uses multiple linear regression to predict NFL quarterback passer rating
based on passing efficiency and performance metrics. The goal was to evaluate how
feature engineering impacts model accuracy and interpretability.

### Feature Engineering
To improve model performance and interpretability, I engineered efficiency-based
features such as Completion Percentage (Cmp/Att) and Touchdowns per Attempt (TD/Att).
These metrics better capture quarterback efficiency than raw counts.

## Model Performance Comparison
- Baseline Model MSE: 39.35
- Feature-Engineered Model MSE: 16.28

Feature engineering reduced prediction error, indicating that efficiency-based
features better explain passer rating variation.
