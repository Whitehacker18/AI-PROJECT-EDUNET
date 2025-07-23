# project description
This Python script builds an end-to-end machine learning pipeline that predicts employee salaries based on various features such as experience, education level, job role, location, and performance rating. Since no real-world data is provided, the script first generates synthetic employee data with realistic distributions and salary calculations.

The pipeline includes:

Data generation: Creates synthetic employee records and calculates salary based on weighted factors like experience, education, job role, performance, and city cost-of-living adjustments.

Preprocessing: Categorical features are one-hot encoded, and numerical features are standardized using scikit-learn’s preprocessing tools.

Model training: A Random Forest Regressor is used to learn the relationship between employee features and salary.

Evaluation: The model’s performance is evaluated using metrics like MAE, RMSE, and R².

Model persistence: The trained model pipeline is saved to disk using joblib for future use.

Prediction demo: The script loads the saved model and demonstrates predicting salaries for new employee profiles.
