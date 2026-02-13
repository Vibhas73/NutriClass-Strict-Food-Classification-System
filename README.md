# 🥗 NutriClass: Food Classification Using Nutritional Data

## 📌 Project Overview
NutriClass is a machine learning project that classifies food items based on their nutritional attributes such as calories, protein, carbohydrates, fats, sugar, and other dietary metrics. The goal is to build a **multi-class classification system** that predicts the **exact food name** from nutritional data, supporting strict and personalized diet planning.

This project focuses on **classification (not recommendation)** to ensure one-to-one mapping between nutritional requirements and allowed food items, which is critical in health and fitness use cases.

---

## 🎯 Business Use Cases
- **Smart Dietary Applications** – Automatically classify foods based on nutritional balance
- **Health Monitoring Tools** – Assist dietitians and nutritionists in diet planning
- **Food Logging Systems** – Auto-classify user-entered meals
- **Grocery / Meal Planning Apps** – Ensure compliance with strict diet plans
- **Educational Platforms** – Learn food categories through AI-based insights

---

## 🧠 Problem Statement
With increasing dietary awareness, accurately identifying food items using nutritional data is valuable. This project develops a machine learning model that classifies foods into predefined categories (food names) using tabular nutritional data.

---

## 🗂️ Dataset
- **Type**: Tabular food nutrition dataset
- **Features**: Calories, Protein, Carbohydrates, Fats, Sugar, Fiber, Sodium, etc.
- **Target Variable**: `Food Name`
- **Nature**: Imbalanced multi-class dataset

---

## 🔬 Project Approach

### 1️⃣ Data Understanding & Exploration
- Load and inspect dataset structure
- Analyze class distribution and imbalance
- Visualize sample entries and feature relationships

### 2️⃣ Data Preprocessing
- Handle missing values
- Remove duplicate records
- Detect and treat outliers
- Standardize numerical features

### 3️⃣ Feature Engineering
- Encode target labels using Label Encoding
- Apply dimensionality reduction (PCA)

### 4️⃣ Model Selection & Training
The following classifiers were trained and compared:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gradient Boosting Classifier

### 5️⃣ Model Evaluation
Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### 6️⃣ Real-Time Prediction (Business Perspective)
The trained model can be used in real-time applications where users input nutritional requirements, and the system predicts the **exact allowed food name** that matches the diet plan.

---

## 📊 Results & Insights
- Random Forest emerged as the **best-performing model** due to:
  - Handling non-linear feature relationships
  - Robustness to noise and imbalance
  - Consistently high accuracy and F1-score
- Ensemble models performed better than linear models on tabular nutritional data

---

## 📈 Visualizations Included
- Class distribution plots
- Correlation heatmaps
- Model accuracy comparison charts
- Confusion matrices
- Feature importance plot (Random Forest)

---

## 🛠️ Technical Stack

### Languages & Libraries
- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Scikit-learn** – ML models & evaluation
- **Matplotlib / Seaborn** – Data visualization

### Concepts Applied
- Data Preprocessing
- Feature Engineering
- Classification Modeling
- Model Evaluation
- Visualization

---

## ▶️ How to Run the Project
1. Clone the repository
   ```bash
   git clone https://github.com/your-username/NutriClass.git
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook or Python scripts
