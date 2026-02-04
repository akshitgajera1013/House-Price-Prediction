🏠 California Housing Price Prediction (End-to-End ML Project)
📌 Overview
  This project is an end-to-end Machine Learning solution for predicting median house prices in California using the California Housing dataset.
  It demonstrates the complete ML workflow — from data preprocessing to model training, evaluation, and inference using a production-ready pipeline.

🎯 Problem Statement
  Accurately predicting house prices is a classic regression problem in real estate analytics.
  The goal of this project is to build a robust ML model that predicts the median house value based on demographic and geographical features.

📂 Project Structure
  ├── housing.csv           # Dataset
  ├── Train_model.py        # Model training & evaluation
  ├── Test_model.py         # Inference using saved model
  ├── model.pkl             # Trained ML model
  ├── pipeline.pkl          # Data preprocessing pipeline
  ├── input.csv             # Unseen test data for prediction
  ├── output.csv            # Model predictions
  └── README.md             # Project documentation

📊 Dataset Description
  The dataset contains information about housing districts in California, including:
  Longitude
  Latitude
  Housing median age
  Total rooms & bedrooms
  Population
  Households
  Median income
  Ocean proximity (categorical feature)

🔄 ML Workflow
  Data loading and exploration
  Stratified train-test split based on median income
  Feature separation (numerical & categorical)
  Data preprocessing using pipelines
  Model training and cross-validation
  Model selection
  Model serialization
  Inference on unseen data

🚀 How to Run the Project
  1️⃣ Clone the Repository
  git clone https://github.com/your-username/california-housing-price-prediction.git
  cd california-housing-price-prediction

2️⃣ Install Dependencies
  pip install -r requirements.txt

3️⃣ Train the Model
  python Train_model.py

4️⃣ Run Inference
  python Test_model.py
Predictions will be saved in output.csv.

📦 Requirements
  Python 3.8+
  numpy
  pandas
  scikit-learn
  joblib

🧠 Key Learnings
  Importance of stratified sampling
  Using pipelines for clean ML workflows
  Handling categorical & numerical features correctly
  Model evaluation using cross-validation
  Saving and reusing trained ML models

👤 Author
  Akshit Gajera
  Aspiring Data Scientist | Machine Learning Enthusiast

⭐ Acknowledgement
  Dataset inspired by the California Housing Dataset commonly used in ML regression problems.

