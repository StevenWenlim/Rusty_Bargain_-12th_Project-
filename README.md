# Sure-Tomorrow_11thProject
This is my project in sprint 12, which is Numeric Method.

In this sprint, I learned the key concepts in numeric method: gradient descent, gradient ascent, and neural networks.

# Project Overview
Rusty Bargain is a company that deals with used cars that is currently developing an application to attract new buyers. Inside the application, we can find the market price of a car. Here i have access to historical data: specifications, versions, and vehicle prices. I need to create a model to determine its value.
Rusty Bargain is interested in:
  1. Prediction accuracy;
  2. Model speed in making predictions;
  3. Time required to train the model. 

After analyzing the data, we can conclude that:
Models that use the gradient boost method (XGBoost, LightGBM, and CatBoost) produce better predictions, as seen from the RMSE values they generate. When assessed in terms of the model's accuracy in predicting, XGBoost is the best model, followed by LightGBM, CatBoost, RandomForest, DecisionTree, and LinearRegression in last place. However, XGBoost requires the longest processing time compared to other models, so if assessed based on overall performance, the best model order is LightGBM, CatBoost, Random Forest, XGBoost, Decision Tree, and Linear Regression in last place.

Based on the analysis that has been conducted, my recommendation for Rusty Bargain would be to use a gradient boosting model like XGBoost, LightGBM, or CatBoost to develop their car price prediction model.

However, when considering the processing time of the model, it is important to keep the user experience in mind. Users expect an application that is fast and responsive. While XGBoost may be the most accurate model, its longer processing time may result in a slower application, which can negatively impact the user experience.

Therefore, Rusty Bargain may want to consider using a model with a faster processing time, such as LightGBM or CatBoost, to ensure a good user experience. These models have shown to have good accuracy and faster processing times, which can result in a more responsive application that meets user expectations.
