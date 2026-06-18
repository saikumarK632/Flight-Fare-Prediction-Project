# Flight-Fare-Prediction-Project
 
# ✈️ Flight Fare Prediction Using Machine Learning

Flight Fare Prediction is a Machine Learning regression project that focuses on predicting airline ticket prices based on different travel-related features. Airline fares are not fixed and can change depending on several factors such as airline type, travel route, journey date, departure time, arrival time, duration, and number of stops. The main goal of this project is to develop a reliable machine learning model that can estimate flight prices accurately using historical flight data.

The project uses a flight booking dataset containing information about different flights. The dataset includes features such as airline name, source city, destination city, journey date, departure time, arrival time, total travel duration, number of stops, and ticket price. The flight price is considered as the target variable, making this a supervised learning regression problem.

Before building the model, data preprocessing and exploratory data analysis are performed. Missing values are handled, duplicate records are removed, and data types are converted into suitable formats. Date and time features are extracted to create useful variables such as journey day and journey month. Categorical features like airline, source, and destination are transformed into numerical values using encoding techniques. Feature engineering is applied to improve the quality of input data and enhance model performance.

Multiple machine learning algorithms are implemented and compared, including Linear Regression, Ridge Regression, Lasso Regression, Decision Tree Regressor, Random Forest Regressor, and XGBoost Regressor. Model performance is evaluated using important regression metrics such as R² Score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Cross Validation Score.

The analysis shows that ensemble-based models such as Random Forest and XGBoost perform better compared to traditional linear models. This is because flight pricing data contains complex and non-linear relationships. Ensemble models are capable of learning these patterns, handling outliers, and providing better prediction accuracy.

Key insights from this project include that airline, route, travel duration, and number of stops strongly influence flight prices. Peak travel periods and longer routes can significantly increase ticket costs. Feature importance analysis helps identify the most influential factors affecting fare prediction.

This project demonstrates a complete end-to-end machine learning workflow, including data cleaning, feature engineering, visualization, model training, evaluation, and performance comparison. The final prediction system can help estimate flight fares and can be extended into real-world applications such as travel recommendation systems and intelligent fare prediction platforms.
