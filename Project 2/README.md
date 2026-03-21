# 🩺 Diabetes Prediction with Machine Learning

- Predict diabetes in patients using **Python** and **Support Vector Machine (SVM)**!  
- This project leverages machine learning to classify whether a patient has diabetes or not based on health metrics.  

---


# 🔬 Problem Statement

Diabetes is a chronic disease that affects millions worldwide. Early detection can help prevent severe complications.

The goal of this project is to build a system that can accurately predict whether a patient has Diabetes (1) or No Diabetes (0) using medical and personal health data.

---

## 🔍 Project Overview
This project demonstrates how to build a **predictive model** using Python and ML techniques.


# ⚙️ How It Works
- Patient health data is collected (e.g., glucose levels, BMI, age)
- Data is preprocessed and cleaned
- A Support Vector Machine (SVM) model is trained on historical data
- The trained model predicts whether a patient has diabetes

---


## 🧩 Workflow

1. **Load Dataset** 
    - Use the Pima Indians Diabetes Dataset (`diabetes.csv`).  
2. **Data Preprocessing**
    - Handle missing values, scale features, and clean data.  
3. **Train-Test Split**
    - Split data into training and testing sets.  
4. **Build SVM Model** 
    - Train a **Support Vector Machine(SVM)** classifier.  
5. **Predict & Evaluate**
    - Make predictions on new data and evaluate the model with metrics like accuracy, precision, and recall.  

---

## 📊 Dataset

The dataset includes 8 features and 1 target label:

|        Features          |             Description                |
|--------------------------|----------------------------------------|
| Pregnancies              | Number of pregnancies                  |
| Glucose                  | Plasma glucose concentration           |
| BloodPressure            | Diastolic blood pressure (mm Hg)       |
| SkinThickness            | Triceps skin fold thickness (mm)       |
| Insulin                  | 2-Hour serum insulin (mu U/ml)         |
| BMI                      | Body mass index                        |
| DiabetesPedigreeFunction | Diabetes pedigree function             |
| Age                      | Age in years                           |
| Outcome                  | Target (0 = No Diabetes, 1 = Diabetes) |


---

# 🛠️ Tech Stack
Python
NumPy
Pandas
Scikit-learn
Jupyter Notebook

--- 

# 📊 Model Performance
Training Accuracy: ~ 78.4370477568741 %
Testing Accuracy: ~ 77.92207792207793 %

---