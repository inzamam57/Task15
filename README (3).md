# Breast Cancer Classification using Machine Learning Pipeline

## 📌 Project Overview

This project builds a complete Machine Learning pipeline for Breast
Cancer classification. The pipeline includes preprocessing, model
training, evaluation, and model saving.

------------------------------------------------------------------------

## 📂 Dataset

-   File: `breast-cancer.csv`
-   Target Column: `diagnosis`
-   Type: Binary Classification

------------------------------------------------------------------------

## ⚙️ Steps Performed

### 1️⃣ Load Dataset

-   Loaded dataset using Pandas.
-   Checked dataset shape and previewed data.

### 2️⃣ Feature & Target Separation

-   Separated independent variables (X) and target variable (y).

### 3️⃣ Feature Identification

-   Identified numerical features.
-   Identified categorical features.

### 4️⃣ Preprocessing using ColumnTransformer

-   Applied StandardScaler to numerical features.
-   Applied OneHotEncoder to categorical features.

### 5️⃣ ML Pipeline Creation

-   Combined preprocessing and RandomForestClassifier using Pipeline.

### 6️⃣ Train-Test Split

-   Used 80-20 split with stratification.

### 7️⃣ Model Training

-   Trained pipeline on training dataset.

### 8️⃣ Evaluation Metrics

-   Accuracy
-   Precision
-   Recall
-   F1-Score
-   Classification Report

------------------------------------------------------------------------

## 📊 Model Performance

RandomForest performs very well on this dataset with high accuracy and
balanced precision-recall performance.

------------------------------------------------------------------------

## 💾 Saved Model

The trained pipeline is saved as:

breast_cancer_pipeline_model.pkl

It includes: - Preprocessing - Encoding - Scaling - Trained RandomForest
Model

------------------------------------------------------------------------

## ▶️ How to Load Saved Model

``` python
import joblib
model = joblib.load("breast_cancer_pipeline_model.pkl")
```

------------------------------------------------------------------------

## 🚀 Tools & Libraries Used

-   Python
-   Pandas
-   Scikit-learn
-   Joblib
-   Google Colab

------------------------------------------------------------------------

## 📎 Author

Machine Learning Pipeline Implementation
