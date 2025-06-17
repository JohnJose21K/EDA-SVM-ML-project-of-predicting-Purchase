# EDA-SVM-ML-project-of-predicting-Purchase

🛒 Online Shoppers Purchase Intention Analysis using SVM

This project analyzes the behavioral data of online shoppers to predict their purchase intention using machine learning techniques — primarily Support Vector Machines (SVM). The dataset is clean, rich in features, and provides a great case study for classification and feature engineering.

---

## 📂 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset)
- **Size**: ~12,000 sessions
- **Target Variable**: `Revenue` (Boolean indicating whether a transaction was completed)

---

## 🔍 Project Highlights

### 🔧 Data Cleaning & Preprocessing
- Checked for missing values (result: **none** 🚫)
- Converted object and boolean types to categorical for modeling compatibility
- Applied manual type correction for feature consistency
- Split features into **numerical** and **categorical** groups

### 📊 Exploratory Data Analysis
- Developed **custom KDE-based visualization function** to plot univariate numerical distributions
- Highlighted key statistical metrics:
  - Mean, Median, Std Deviation
  - Skewness, Kurtosis
  - Mean ± 1σ intervals
- Used `seaborn` and `matplotlib` to interpret behavioral trends

### 🧠 Model Building
- Trained **Support Vector Machine (SVM)** classifier using `scikit-learn`
- Preprocessing included:
  - Label encoding of categorical features
  - Feature scaling where necessary
- Model tuned and validated using train/test split

---

## 📈 Results

| Metric           | Value     |
|------------------|-----------|
| rbf , gamma          | 1e-05      |
| F1-score   Train     | 0.72       |
| F1-score   Val       | 0.36       |
| F1-score   Test      | 0.36       |

> 📌 _Note: Add real values after evaluation._

---

## 🛠️ Tools & Libraries

- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📁 Repository Structure


```bash
.
├── Assignment_SVM.ipynb     # Main notebook with full analysis
├── online_shoppers_intention.xlsx # Dataset
├── README.md                # Project documentation
