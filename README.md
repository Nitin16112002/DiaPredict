# **DiaPredict**

## **📌 Project Overview**
This project focuses on developing a **machine learning model** to predict **diabetes** based on key health indicators such as **glucose levels, BMI, blood pressure, and family history**. The model assists healthcare professionals in **early diagnosis** and **preventive care recommendations**.

---

## **📂 Dataset** 
The dataset contains the following features:

| Feature | Description |
|---------|------------|
| **Pregnancies** | Number of times pregnant |
| **Glucose** | Plasma glucose concentration |
| **BloodPressure** | Diastolic blood pressure (mm Hg) |
| **SkinThickness** | Triceps skinfold thickness (mm) |
| **Insulin** | Serum insulin level (mu U/ml) |
| **BMI** | Body mass index (weight in kg/(height in m)^2) |
| **DiabetesPedigreeFunction** | Family history of diabetes (higher values = greater risk) |
| **Age** | Age of the patient (years) |
| **Outcome** | Target variable (1 = Diabetic, 0 = Non-Diabetic) |

---

## **📊 Model Performance**
The model was trained and evaluated using **accuracy, precision, recall, F1-score, and ROC-AUC**.

### **✅ Key Metrics**
| Metric | Score |
|--------|-------|
| **Training Accuracy** | 77.20% |
| **Test Accuracy** | 81.17% |
| **Cross-Validation Score** | 75.25% |
| **ROC-AUC Score** | 87.77% |

### **📌 Precision, Recall & F1-Score**
| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| **0 (Non-Diabetic Patients)** | 82% | 91% | 87% | 102 |
| **1 (Diabetic Patients)** | 78% | 62% | 69% | 52 |

- The model **performs well overall**, with **high accuracy and an AUC score of 87.77%**.
- However, **recall for diabetic patients is lower (62%)**, meaning some diabetic cases are **misclassified as non-diabetic**.

---

## **⚙️ Technologies Used**
- **Python 🐍**
- **Pandas & NumPy** for data manipulation
- **Scikit-Learn** for model training and evaluation
- **Matplotlib & Seaborn** for data visualization
- **Jupyter Notebook** for experimentation

---


