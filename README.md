# Titanic-Survival-Prediction

This project aims to predict the survival of passengers in the Titanic disaster using machine learning. The repository contains code for data loading, exploratory data analysis (EDA), preprocessing, model selection, training, and evaluation.

## Dependencies
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* Naive bayes

## Data
The dataset used is the Titanic dataset, typically available on Kaggle. It contains passenger information like age, gender, class, fare, and survival status.

##  Workflow
1.  **Data Loading**: The `load_data` function loads the training and testing data.
2.  **Exploratory Data Analysis (EDA)**: The `explore_data` function provides insights into the data through visualizations and descriptive statistics.
3.  **Data Preprocessing**: The `preprocess_data` function prepares the data for model training.
4.  **Model Training**: The `train_model` function trains a selected model (default is Random Forest) with optional hyperparameter tuning using GridSearchCV.
5.  **Model Evaluation**: The `evaluate_model` function assesses the model's performance on a validation set.
6.  **Prediction and Submission**: The `make_predictions` function generates a submission file (submission.csv) with predictions on the test data.
