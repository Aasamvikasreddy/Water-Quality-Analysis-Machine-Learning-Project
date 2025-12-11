# Water Potability Prediction using Machine Learning

## 📌 Project Description
Access to clean and safe drinking water is essential for public health.  
This project uses Machine Learning techniques to analyze water quality
parameters and predict whether water is potable (safe to drink).
The project also includes regression models to predict a key water quality
parameter (pH value).

---

## 🎯 Objectives
- To analyze water quality data using exploratory data analysis.
- To predict water potability using classification algorithms.
- To predict pH value using regression techniques.
- To evaluate the performance of different machine learning models.

---

## 📂 Dataset
- **Dataset Name:** Water Potability Dataset
- **Source:** Data.gov.in
- **File:** `water_potability.csv`
- **Number of Records:** 3,276
- **Features:**
  - pH
  - Hardness
  - Solids
  - Chloramines
  - Sulfate
  - Conductivity
  - Organic Carbon
  - Trihalomethanes
  - Turbidity
- **Target Variable:**
  - `Potability` (0 = Not Safe, 1 = Safe)

---

## ⚙️ Machine Learning Models Used

### Classification Models
- Logistic Regression
- Decision Tree Classifier

### Regression Models
- Linear Regression
- Decision Tree Regressor

---

## 🧪 Data Preprocessing
- Handled missing values using median imputation.
- Removed duplicate records.
- Applied feature scaling using StandardScaler.
- Performed feature selection using correlation analysis.
- Handled class imbalance using `class_weight = "balanced"`.

---

## 📊 Model Evaluation

### Classification Metrics
- Accuracy
- F1 Score
- Confusion Matrix
- Classification Report

### Regression Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## ✅ Results
- Classification models achieved balanced accuracy despite class imbalance.
- Decision Tree performed better after depth control and class balancing.
- Regression models successfully predicted pH with reasonable error.
- Feature selection helped improve overall model stability.

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Water-Potability-ML-Project.git
2. Install required libraries:
   pip install -r requirements.txt
3. Open the jupyter notebook
   jupyter notebook Water_Potability_ML.ipynb
