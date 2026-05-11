# Predicting Guest Satisfaction Based on Airbnb Service Features

This project aims to predict Airbnb guest satisfaction based on several service and property features such as cleanliness rating, superhost status, business type, bedrooms, price, and restaurant accessibility. The analysis was conducted using Airbnb listing data consisting of 41,714 observations.

The project workflow includes data understanding, exploratory data analysis (EDA), correlation analysis, feature selection, data preprocessing, train-test split, feature scaling, and predictive modeling using Linear Regression. The selected features used in the model are Cleanliness Rating, Bedrooms, Restraunt Index, Business, Superhost, and Private Room, while Guest Satisfaction is used as the target variable.

Based on the analysis results, Cleanliness Rating was identified as the most influential feature affecting guest satisfaction, followed by Superhost status. Meanwhile, Business-type listings and Private Room features showed a negative relationship with guest satisfaction.

The evaluation results of the Linear Regression model are:
- MAE  : 3.71
- RMSE : 5.70
- R²   : 0.524

These results indicate that the model is capable of explaining approximately 52.4% of the variation in guest satisfaction. Overall, the model shows a fairly good performance in predicting Airbnb guest satisfaction based on service-related features.

Technologies used in this project include Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and Jupyter Notebook.
