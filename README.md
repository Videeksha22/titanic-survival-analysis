# 📊Titanic Survival Prediction – Machine Learning Project

## Project Overview
This project performs Exploratory Data Analysis (EDA) and applies multiple machine learning classification algorithms on the Titanic dataset to predict passenger survival. The goal is to analyze key factors influencing survival and compare the performance of different ML models.

## Dataset
The dataset contains information about Titanic passengers, including:
- Passenger class
- Sex
- Age
- Fare
- Embarkation port
- Survival status

**Dataset Source:**  
Kaggle – Titanic: Machine Learning from Disaster  
https://www.kaggle.com/competitions/titanic/data

The `train.csv` file from Kaggle is used and renamed as `titanic.csv`.

## Steps Performed
- Data loading and inspection
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Handling missing values
- Encoding categorical variables
- Feature selection
- Train-test split
- Training multiple machine learning models
- Model evaluation and comparison

## Machine Learning Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree Classifier
- Random Forest Classifier
- Naive Bayes

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run
1. Clone the repository
   ```bash
   git clone <https://github.com/Videeksha22/titanic-survival-analysis>
2. Navigate to the project directory:
   ```bash
   cd Titanic-ML-Classification
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
4. Open the notebook:
   ```bash
   jupyter notebook Titanic_final.ipynb
