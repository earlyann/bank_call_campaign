# Call Campaign for Term Deposit - XGBoost Model

### Overview
This GitHub project focuses on a call campaign conducted by a bank to promote term deposit. A term deposit is a financial investment product offered by banks, where a fixed amount of money is deposited for a specific period, typically ranging from a few months to a few years, at a fixed interest rate. It is a low-risk investment option and provides a guaranteed return at the end of the agreed term. The goal is to develop a predictive model using XGBoost to identify factors that lead to positive responses for term deposit agreements. The project prioritizes recall as the most important evaluation metric, aiming to maximize the correct identification of positive cases.

### Technologies Used
- Python/Pandas
- Seaborn for visualizations
- XGBoost
- SciKit-Learn
- ImbalanceLearn
  
### Project Description
The project involves building an XGBoost model to predict customer responses to the bank's call campaign for term deposit subscriptions. By analyzing various customer attributes such as age, job, marital status, education, and previous campaign outcomes, the model aims to identify factors that contribute to positive responses.

To ensure the best model performance, various machine learning algorithms were explored. Logistic regression, LGBM, CatBoost, HistGradient Booster, and Random Forest classifiers were evaluated and compared based on their recall performance. The XGBoost algorithm emerged as the most effective model for this specific task, given its ability to handle complex relationships and capture non-linear patterns in the data.

In an attempt to facilitate classification, Gaussian Mixture Models (GMM) and k-means clustering were considered to group customers based on their attributes. However, no clear groupings were found that significantly improved the classification performance.

The project includes several notebooks that provide a comprehensive exploration of different models, including logistic regression, LGBM, CatBoost, HistGradient Booster, and Random Forest. Each model's implementation, hyperparameter tuning, and performance evaluation are presented, with a focus on recall optimization.

Furthermore, visualizations are used to gain insights into the data, assess feature importance, and interpret the results. The notebook also documents the attempted use of GMM and k-means clustering for grouping analysis.

### Conclusion

##### Status: In progress
##### Author: Lacey Morgan


Data source: https://www.kaggle.com/datasets/vstacknocopyright/bank-marketing
