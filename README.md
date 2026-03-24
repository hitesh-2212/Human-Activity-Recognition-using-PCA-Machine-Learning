# 🧠 Human Activity Recognition using PCA & Machine Learning

## 📌 Project Overview
This project focuses on analyzing high-dimensional sensor data and applying Principal Component Analysis (PCA) to reduce dimensionality while maintaining model performance.

The goal is to evaluate the impact of PCA on machine learning models and improve computational efficiency.

---

[Download Dataset](https://archive.ics.uci.edu/dataset/240/human%2Bactivity%2Brecognition%2Busing%2Bsmartphones)

## 📂 Dataset
- Dataset: Human Activity Recognition (HAR)
- Source: UCI Machine Learning Repository
- Features: 561 numerical features
- Target: 6 activity classes (Walking, Sitting, Standing, etc.)

---

## 🎯 Problem Statement
High-dimensional datasets often contain redundant and correlated features, leading to increased computational cost and complexity.

This project aims to:
- Analyze high-dimensional data
- Apply PCA for dimensionality reduction
- Compare model performance before and after PCA

---

## 🛠️ Project Workflow

### 1. Data Preprocessing
- Combined train and test datasets
- Checked for missing values (none found)
- Standardized features using StandardScaler

### 2. Exploratory Data Analysis (EDA)
- Analyzed feature distributions
- Checked feature correlations
- Identified high dimensionality and redundancy

### 3. PCA (Dimensionality Reduction)
- Applied PCA on scaled data
- Used explained variance to select optimal components
- Reduced features from **561 → 125**

### 4. Visualization
- Compared raw feature scatter vs PCA-based scatter
- Observed improved structure after PCA

### 5. Machine Learning Model
- Model used: Logistic Regression
- Trained on:
  - Original dataset
  - PCA-transformed dataset

---

## 📊 Results

| Model | Accuracy |
|------|--------|
| Without PCA | 98.25% |
| With PCA (125 components) | 97.28% |

---

## 💡 Key Insights
- PCA reduced dimensionality by ~78%
- Minimal accuracy loss (~1%)
- Improved computational efficiency
- Reduced model complexity

---

## 🧠 Conclusion
PCA proved to be highly effective in reducing feature space while maintaining strong model performance. This demonstrates its importance in handling high-dimensional real-world datasets.

---

## 🚀 Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 📈 Future Improvements
- Real-time activity prediction
- Deploy as a web application

---

## 🙌 Acknowledgements
- UCI Machine Learning Repository for dataset
