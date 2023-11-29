# EE8603 Final Term Project - Abalone

The primary objective of this project was to analyze and predict the age of abalone using a dataset that encompassed various physical measurement. The conventional method of age determination, involving the laborious task of cutting shells and counting rings, was circumvented in favor of a machine learning approach.

The initial phase involved data preprocessing, including the encoding of categorical variables and scaling numerical features. PyCaret, an automated machine-learning library, was employed to systematically compare different regression models. The evaluated models included Linear Regression, Decision Tree, Random Forest, and advanced ensemble methods like CatBoost, XGBoost, LR, and LightGBM.

After comparing different models, we found that the CatBoost Regressor worked the best for predicting the age of abalones. It consistently gave the most accurate predictions, with the lowest errors (MAE, MSE, RMSE) and the highest R-squared value. We chose CatBoost as the final model because it handles different types of data really well and doesn't get thrown off by complex relationships in the dataset. Its ability to keep things accurate without overcomplicating matters made it a great fit for our diverse dataset. So, when it comes to predicting abalone age, CatBoost stood out as the go-to choice.

In summary, this project showcased the effectiveness of machine learning in predicting the age of abalone based on various physical and contextual features. The success of the CatBoost model underscores the potential of advanced ensemble techniques in deciphering complex patterns and relationships within biological datasets, offering a promising avenue for understanding and forecasting age-related patterns in marine organisms.
