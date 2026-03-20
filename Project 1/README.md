# 🚢 SONAR Rock vs Mine Prediction

A Machine Learning project that classifies underwater objects as **Rock** or **Mine** using sonar signal data.

---

## 🌊 Problem Statement

In a wartime scenario, submarines must navigate through oceans where enemy mines are deployed. These mines can explode when objects come near them. However, not all detected objects are dangerous — some are just natural rocks.

The goal of this project is to build a system that can accurately predict whether an object is a **Mine (M)** or a **Rock (R)** using sonar signals.

---

## 📡 How It Works

- The submarine sends **sonar signals** underwater  
- Signals bounce off objects and return  
- These signals are analyzed using Machine Learning  
- The model predicts whether the object is a **Rock** or a **Mine**

---

## ⚙️ Workflow

1. **Data Collection**
   - Sonar signals collected from rocks and metal cylinders

2. **Data Preprocessing**
   - Cleaning and formatting the dataset
   - Converting labels into numerical form

3. **Train-Test Split**
   - Splitting data for training and evaluation

4. **Model Training**
   - Logistic Regression (Binary Classification)

5. **Prediction**
   - Predict object type from new sonar input

---

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Model Performance

- Training Accuracy: ~ 83.42245989304813 %
- Testing Accuracy: ~ 76.19047619047619 %

---