# 🚗 CO2 Emission Prediction By Vehicles using Machine Learning

## 📌 Overview
This project predicts CO2 emission levels of vehicles using machine learning techniques. It analyzes vehicle attributes such as engine size, fuel consumption, cylinders, and fuel type to estimate emissions and classify them into categories like Low, Medium, and High.

The project demonstrates a complete machine learning pipeline from data preprocessing to model evaluation and comparison.

---

## 🎯 Problem Statement
To build a machine learning model that can accurately predict CO2 emissions of vehicles and classify them based on environmental impact.

---

## 🌍 Motivation
- Rising environmental pollution due to vehicle emissions  
- Need for automated prediction systems  
- Limitations of traditional/manual methods  
- Importance of sustainable solutions using data science  

---

## 📂 Dataset
- Source: Canada Vehicle CO2 Emissions Dataset (Kaggle)  
- Records: ~7000+ vehicles  
- Features:
  - Engine Size  
  - Cylinders  
  - Fuel Type  
  - Fuel Consumption  
  - Transmission  
  - CO2 Emissions (g/km)  

---

## ⚙️ Project Workflow

### 📘 1. Analysis & Preprocessing  
📄 `Analysis_and_Preprocessing.ipynb`

- Data loading and inspection  
- Handling missing values and duplicates  
- Encoding categorical features  
- Feature selection  
- Exploratory Data Analysis (EDA):
  - Scatter plots  
  - Box plots  
  - Correlation matrix  

📊 Outputs are stored in:
- `images/` folder (visualizations)

---

### 🤖 2. Model Building & Evaluation  
📄 `Model_and_Evaluation.ipynb`

- Train-test split (80:20)  
- Conversion of CO2 values into emission categories  
- Model training using:
  - AdaBoost  
  - Random Forest  
  - XGBoost  
  - Voting Classifier  
- Performance evaluation using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - Confusion Matrix  

📁 Outputs stored in:
- `results/` folder (metrics, tables, reports)

---

## 🤖 Machine Learning Models

### 🔹 AdaBoost
Improves performance by focusing on misclassified samples iteratively.

### 🔹 Random Forest
Uses multiple decision trees to improve stability and reduce overfitting.

### 🔹 XGBoost
Gradient boosting algorithm with high efficiency and accuracy.

### 🔹 Voting Classifier
Combines predictions from multiple models to improve overall performance.

---

## 📊 Results

- ✅ Best Model: **XGBoost Classifier**  
- 🎯 Accuracy Achieved: **98%**  

### 📌 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

📁 Detailed outputs available in:
- `results/` folder  
📊 Graphs available in:
- `images/` folder  

---

## 📈 Visualizations
- Scatter Plots  
- Box Plots  
- Correlation Matrix  
- Confusion Matrix  

(All stored in the `images/` directory)

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  

---

## 📂 Project Structure
co2-emission-project/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   ├── Analysis_and_Preprocessing.ipynb
│   └── Model_and_Evaluation.ipynb
│
├── images/
│   └── (EDA graphs, plots)
│
├── results/
│   └── (model outputs, evaluation metrics)
│
└── README.md
