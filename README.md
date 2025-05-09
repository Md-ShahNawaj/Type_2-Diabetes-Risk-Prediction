# Type 2 Diabetes Risk Prediction

This project uses a healthcare dataset to predict the likelihood of Type 2 Diabetes in individuals using various physiological and medical indicators. The goal is to preprocess the data, perform exploratory data analysis, and apply machine learning models to accurately predict diabetes risk.

---

### Dataset Overview

The dataset includes medical attributes such as:

- Glucose  
- Blood Pressure  
- BMI  
- Insulin  
- Skin Thickness  
- Age  
- Pregnancies  
- Diabetes Pedigree Function  

These features are used to predict whether an individual is likely to have diabetes (`Outcome` variable).

---

### Project Structure

1. **Data Loading & Inspection** – Overview of data shape, types, and preview.
2. **Descriptive Statistics** – Identify skewness, ranges, and potential outliers.
3. **Data Cleaning** – Handle missing or invalid values (e.g., zero values in clinical features).
4. **Exploratory Data Analysis (EDA)** – Visualize distributions and correlations.
5. **Feature Engineering** – Prepare features, scale data, and address class imbalance.
6. **Model Training** – Apply Logistic Regression, Random Forest, and other classifiers.
7. **Evaluation** – Assess models using accuracy, precision, recall, F1 score, and ROC-AUC.

---

### Machine Learning Models

Multiple models are compared to select the most effective for prediction. Techniques like **SMOTE** are used to address class imbalance and improve model generalization.

---

### Key Insights

- Some features had zero values that were likely invalid (e.g., Insulin, BMI).
- **Glucose** and **BMI** were strong predictors of diabetes.
- Proper preprocessing significantly improved model performance and reliability.

---

### Dependencies

- Python 
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- scikit-learn  

### How to Run

1. Clone this repository:
git clone https://github.com/yourusername/diabetes-risk-prediction.git
cd diabetes-risk-prediction

2. Run the Jupyter notebook:
jupyter notebook type-2-diabetes-risk-prediction.ipynb

### Reference

Data sourced from Kaggle: Pima Indians Diabetes Database.
