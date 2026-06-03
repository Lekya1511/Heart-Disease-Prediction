# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early detection and diagnosis play a crucial role in reducing mortality rates and improving patient care. This project aims to develop a Machine Learning model capable of predicting the likelihood of heart disease based on various medical attributes and patient health records.

The model analyzes patient data such as age, sex, blood pressure, cholesterol level, heart rate, chest pain type, and other clinical features to determine whether a person is at risk of heart disease.

This project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, visualization, model training, evaluation, and prediction.

---

## 🎯 Problem Statement

Heart disease remains a major global health challenge, causing millions of deaths every year. Traditional diagnosis methods often require multiple medical tests, expert interpretation, and considerable time.

There is a need for an intelligent system that can assist healthcare professionals by quickly identifying individuals who may be at risk of heart disease based on available clinical data.

The objective of this project is to build a Machine Learning model that accurately predicts the presence of heart disease using patient medical information, thereby supporting early diagnosis and treatment planning.

---

## 💡 Proposed Solution

This project provides a Machine Learning-based predictive system that:

- Collects and analyzes patient medical data.
- Performs data cleaning and preprocessing.
- Conducts Exploratory Data Analysis (EDA).
- Visualizes important relationships within the dataset.
- Trains a classification model on historical patient records.
- Predicts whether a patient is likely to have heart disease.
- Evaluates model performance using standard classification metrics.

The system helps healthcare professionals make faster and more informed decisions by leveraging data-driven insights.

---

## 📊 Dataset Description

The dataset contains patient medical information used for heart disease prediction.

### Features Used

| Feature | Description |
|----------|-------------|
| Age | Age of the patient |
| Sex | Gender of the patient |
| Chest Pain Type | Type of chest pain experienced |
| Resting Blood Pressure | Blood pressure level |
| Cholesterol | Serum cholesterol level |
| Fasting Blood Sugar | Blood sugar level |
| Resting ECG | Resting electrocardiographic results |
| Maximum Heart Rate | Maximum heart rate achieved |
| Exercise Induced Angina | Chest pain during exercise |
| ST Depression | ST depression induced by exercise |
| Slope | Slope of peak exercise ST segment |
| Number of Major Vessels | Number of major vessels colored by fluoroscopy |
| Thalassemia | Blood disorder information |
| Target | Presence or absence of heart disease |

### Target Variable

- **0** → No Heart Disease
- **1** → Heart Disease Present

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset Inspection
- Missing Value Analysis
- Statistical Summary
- Feature Distribution Analysis
- Correlation Analysis
- Count Plots
- Histograms
- Target Variable Visualization

EDA helps understand data patterns and identify important features that influence heart disease prediction.

---

## ⚙️ Project Workflow

```text
Data Collection
       ↓
Data Preprocessing
       ↓
Exploratory Data Analysis
       ↓
Data Visualization
       ↓
Feature Selection
       ↓
Train-Test Split
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Prediction
```

---

## 🤖 Machine Learning Process

### Data Preprocessing

- Handling missing values
- Data cleaning
- Feature preparation
- Dataset inspection

### Model Training

The dataset is divided into:

- Training Set
- Testing Set

The Machine Learning model is trained using the training dataset and evaluated using unseen test data.

### Prediction

The trained model predicts whether a patient is likely to have heart disease based on the input features.

---

## 📈 Model Evaluation

The model performance is evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1 Score

These metrics help determine how effectively the model predicts heart disease cases.

---

## 📊 Visualizations Included

The notebook includes various visualizations such as:

- Histograms
- Count Plots
- Correlation Heatmaps
- Feature Distribution Graphs
- Target Variable Analysis

These visualizations provide deeper insights into the dataset and model behavior.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📁 Project Structure

```text
Heart-Disease-Prediction/
│
├── Heart Disease Prediction.ipynb
├── heart.csv
├── requirements.txt
├── README.md
│
└── Outputs & Visualizations
```

---

## 🚀 Execution Process

### Step 1: Clone the Repository

```bash
git clone https://github.com/Lekya1511/Heart-Disease-Prediction.git
```

### Step 2: Navigate to Project Directory

```bash
cd Heart-Disease-Prediction
```

### Step 3: Install Required Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the Notebook

Click on:

```text
Heart Disease Prediction.ipynb
```

### Step 6: Execute the Notebook

Run all cells using:

```text
Kernel → Restart & Run All
```

or execute each cell individually using:

```text
Shift + Enter
```

---

## 📋 Expected Results

After executing the notebook:

✅ Dataset overview will be displayed

✅ Statistical analysis will be performed

✅ Data visualizations will be generated

✅ Machine Learning model will be trained

✅ Prediction results will be produced

✅ Model accuracy and evaluation metrics will be displayed

---

## 🌟 Future Enhancements

- Develop a Flask-based web application
- Build a Streamlit dashboard
- Implement real-time heart disease prediction
- Compare multiple Machine Learning algorithms
- Perform hyperparameter tuning
- Deploy the model on cloud platforms

---

## 🎓 Learning Outcomes

This project demonstrates:

- Data Preprocessing Techniques
- Exploratory Data Analysis
- Data Visualization
- Machine Learning Classification
- Model Evaluation
- Healthcare Data Analytics

---

## Author

### Lekya Dosakayala

B.Tech Computer Science and Engineering

GitHub: https://github.com/Lekya1511

LinkedIn: https://www.linkedin.com/in/lekya-dosakayala-b252b0320/

Email: lekyadosakayala@gmail.com
