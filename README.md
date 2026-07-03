# 🍷 Wine Quality Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-orange)

---

## 📌 Project Overview

Wine quality depends on several physicochemical properties such as acidity, sugar content, alcohol percentage, pH level, and sulphates.

This project uses **Machine Learning** to predict wine quality based on these chemical properties. The model analyzes input features and predicts whether the wine quality is **low, medium, or high**, or outputs a quality score.

This helps automate quality testing in the wine industry and reduces manual evaluation effort.

---

## 🎯 Objective

The main goals of this project are:

* Analyze wine quality dataset
* Perform data preprocessing
* Explore important chemical features
* Train Machine Learning models
* Predict wine quality accurately

---

## 📂 Dataset Information

The dataset contains physicochemical properties of wine such as:

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol

### Target Variable

**Quality Score** (usually ranges from 0–10)

Example:

* 3–4 → Low Quality
* 5–6 → Medium Quality
* 7–8 → High Quality

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Platform:** Google Colab

### Libraries Used

* pandas
* NumPy
* Matplotlib
* Seaborn
* scikit-learn

---

## 🔄 Project Workflow

### 1️⃣ Data Loading

* Import dataset into Colab
* Read CSV file
* Check dataset shape

### 2️⃣ Data Preprocessing

* Handle missing values
* Remove duplicates
* Detect outliers
* Normalize numerical features

### 3️⃣ Exploratory Data Analysis (EDA)

Analyzed:

* Feature distributions
* Correlation matrix
* Relationship between alcohol and quality
* Effect of acidity on quality

### 4️⃣ Feature Engineering

* Feature scaling
* Data transformation
* Train-test split

### 5️⃣ Model Training

Machine Learning models used:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

### 6️⃣ Model Evaluation

Metrics used:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 📊 Machine Learning Pipeline

```text id="winepipe1"
Raw Dataset
   ↓
Data Cleaning
   ↓
EDA
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Evaluation
   ↓
Prediction
```

---

## 🚀 Results

The trained model successfully predicts wine quality based on chemical features.

### Key Outcomes

✔ Automated wine quality assessment
✔ Reduced manual testing effort
✔ Improved quality prediction accuracy

---

## 📈 Sample Insights

* Higher alcohol content often correlates with better quality
* Excess volatile acidity reduces quality
* Sulphates and citric acid influence taste significantly

---
