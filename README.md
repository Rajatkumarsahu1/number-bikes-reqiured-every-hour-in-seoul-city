# number-bikes-reqiured-every-hour-in-seoul-city
Title: Seoul Bike Prediction

Objective: To accurately predict the number of bikes required per hour in Seoul based on historical data, in order to optimize the allocation of resources for the city's bike-sharing program.

Methodology: The project began with the collection of data from Kaggle. This data was then subjected to deep exploratory data analysis (EDA) in order to understand the patterns and trends within the data, as well as to identify and remove any potential outliers that could impact the modeling process. Once the EDA was complete, the data was split into train and test sets, with the train set being used to train the machine learning models and the test set being reserved for evaluating the models' performance.

Three different models were trained on the train set: linear regression, random forest regressor, and XGBoost regressor. These models were chosen because they are commonly used for prediction tasks, and they are known to be effective at handling large datasets with many features. To fine-tune the models, hyperparameter tuning was performed, which involved adjusting the parameters of the models in order to optimize their performance.

Once the models were trained, they were used to predict the number of bikes required per hour in the test set. The results of these predictions were then evaluated using appropriate evaluation metrics, and the final model was chosen based on its performance.

Results: The results of the project showed that the chosen model was able to accurately predict the number of bikes required per hour in Seoul, with a high level of accuracy. This demonstrates the effectiveness of machine learning techniques for forecasting demand for bike-sharing programs in urban environments.

Conclusion: The Seoul Bike Prediction project was a success, as it was able to accurately predict the number of bikes required per hour in Seoul based on historical data. This information can be used by the city to optimize the allocation of resources for its bike-sharing program, helping to ensure that there are enough bikes available to meet the demand of the city's residents and visitors.
