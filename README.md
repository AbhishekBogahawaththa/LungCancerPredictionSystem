# 🧬 Lung Cancer Data Preprocessing & PCA Pipeline

This project implements a **complete preprocessing pipeline** for a lung cancer dataset, preparing it for machine learning applications.  
It includes **data cleaning, feature engineering, encoding, scaling, PCA dimensionality reduction, and correlation analysis**.

---

## 📂 Project Structure

---

## 🔑 Features
- **Data Cleaning**
  - Handles missing values (median for numeric, mode for categorical)
  - Removes outliers using the IQR method

- **Feature Engineering & Encoding**
  - Label Encoding for high-cardinality columns
  - One-Hot Encoding for categorical variables
  - Optional engineered features (e.g., interactions, BMI × cholesterol)

- **Data Splitting & Balancing**
  - Train-test split with stratification
  - SMOTE oversampling (optional)

- **Scaling & Dimensionality Reduction**
  - Scales features with MinMaxScaler
  - Reduces dimensionality using PCA (retains 95% variance)

- **Correlation Analysis**
  - Correlation matrix for numerical + engineered features
  - Optional heatmap visualization

- **Outputs**
  - Saves processed **train** and **test** datasets with PCA components

---

## 🚀 Usage
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
