# California House Price Prediction (ML algo.)

This project implements an end-to-end Machine Learning pipeline to predict median house prices in California using the California Housing dataset.
The workflow covers the complete ML lifecycle, including data preprocessing, stratified train-test splitting, feature engineering, model training, evaluation, and deployment-ready inference.

🔹 Key Highlights
  Stratified sampling based on median income to avoid sampling bias
  Separate numerical and categorical preprocessing pipelines
  Numerical: median imputation + standard scaling
  Categorical: one-hot encoding
  Modular pipeline design using ColumnTransformer & Pipeline
  Trained and compared multiple models:
  Linear Regression
  Decision Tree Regressor
  Random Forest Regressor
  Model evaluation using Cross-Validation RMSE
  Final model serialized using Joblib
  Supports real-world inference on unseen data via saved pipeline & model

🔹 Project Structure
  Train_model.py
  Data loading & preprocessing
  Stratified train-test split
  Pipeline creation
  Model training & cross-validation
  Test_model.py
  Loads trained model & pipeline
  Performs predictions on unseen data
  Saves predicted house prices to output file

🔹 Tech Stack
  Python
  NumPy, Pandas
  Scikit-Learn
  Joblib

🔹 Use Case
This project demonstrates industry-level ML practices, making it suitable for:
  Data Science portfolios
  ML interviews
  Real-world regression problem understanding
  Joblib

🔹 Use Case
  This project demonstrates industry-level ML practices, making it suitable for:
  Data Science portfolios
  ML interviews

Real-world regression problem understanding
