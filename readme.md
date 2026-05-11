# 🚀 Spaceship Titanic - Kaggle Competition Solution

## 📌 Overview

This project presents a complete machine learning pipeline for the Kaggle **Spaceship Titanic** competition. The objective is to predict whether passengers were transported to another dimension during a mysterious anomaly aboard the spaceship Titanic.

The notebook includes:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Missing Value Handling
- Categorical Encoding
- Ensemble Machine Learning Models
- Hyperparameter Optimization
- Cross Validation
- Kaggle Submission Generation

---

# 🧠 Problem Statement

The Spaceship Titanic encountered a spacetime anomaly while traveling through the cosmos. Using passenger information such as demographics, spending patterns, cabin details, and travel data, the goal is to predict whether a passenger was transported to another dimension.

This is a **Binary Classification Problem**.

---

# 📂 Dataset Information

The dataset contains passenger records with multiple categorical and numerical features.

## Files

| File                    | Description       |
| ----------------------- | ----------------- |
| `train.csv`             | Training dataset  |
| `test.csv`              | Testing dataset   |
| `sample_submission.csv` | Submission format |

---

# 📊 Features

| Feature      | Description                 |
| ------------ | --------------------------- |
| PassengerId  | Unique Passenger Identifier |
| HomePlanet   | Origin Planet               |
| CryoSleep    | Passenger in CryoSleep      |
| Cabin        | Cabin Information           |
| Destination  | Destination Planet          |
| Age          | Passenger Age               |
| VIP          | VIP Status                  |
| RoomService  | Spending on Room Service    |
| FoodCourt    | Spending on Food Court      |
| ShoppingMall | Shopping Expenses           |
| Spa          | Spa Expenses                |
| VRDeck       | VR Deck Expenses            |
| Name         | Passenger Name              |
| Transported  | Target Variable             |

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- CatBoost
- XGBoost
- LightGBM

---

# 📈 Exploratory Data Analysis

The project performs detailed EDA including:

- Missing Value Analysis
- Target Variable Distribution
- Correlation Heatmaps
- Numerical Feature Distributions
- Feature Relationship Analysis

---

# 🏗️ Feature Engineering

Several advanced features were created to improve model performance:

## Cabin Features

- Deck
- Cabin Number
- Side

## Spending Features

- TotalSpend
- NoSpending

## Group Features

- Group
- GroupSize

## Passenger Features

- AgeGroup
- LuxuryPassenger

---

# 🧹 Data Preprocessing

The preprocessing pipeline includes:

- Missing Value Imputation
- Label Encoding
- Numerical Scaling
- Feature Alignment
- Data Cleaning

---

# 🤖 Machine Learning Models

The following models were used:

| Model              | Purpose                  |
| ------------------ | ------------------------ |
| CatBoostClassifier | Main High Accuracy Model |
| XGBoostClassifier  | Gradient Boosting        |
| LightGBMClassifier | Fast Gradient Boosting   |
| VotingClassifier   | Ensemble Learning        |

---

# 📊 Evaluation Metrics

The project uses:

- Accuracy Score
- Cross Validation Accuracy
- Confusion Matrix
- Classification Report

---

# 🚀 Model Performance

| Model          | Accuracy     |
| -------------- | ------------ |
| Random Forest  | ~0.79        |
| CatBoost       | ~0.81        |
| Ensemble Model | ~0.82 - 0.84 |

---
