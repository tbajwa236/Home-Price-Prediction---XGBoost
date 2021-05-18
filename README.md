# Home-Price-Prediction---XGBoost
The dataset is taken from a Kaggle competition. After some EDA, missing value treatment and feature engineering, all the variables were analyzed using statsmodels OLS regression. This step  of statistical data exploration helped in determining that our dataset was much more suited to a non-linear approach. XGBoost regressor (non linear approach) was used and optimized to return an r^2 value of 90.04% and mean squared error of $1.40. Finally, all assumptions of linear regression were checked to make sure the residuals are normally distributed, homoskedastic, have a mean of zero and show no signs of autocorrelation.
