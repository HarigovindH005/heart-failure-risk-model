# 💓 Heart Failure Risk Prediction

This project is a machine learning-powered web application that predicts the likelihood of a **heart failure event** based on patient clinical data. It leverages a **Random Forest Classifier** trained on a dataset of real-world health metrics and provides predictions through an interactive Flask web interface.

---

## 🩺 Project Overview

Cardiovascular diseases are the leading cause of death globally. Among them, heart failure is particularly dangerous but preventable if detected early. This project aims to assist in the **early identification of patients at risk**, enabling timely medical intervention and better prognosis.

---

## 🔍 Key Features

- ✅ Predicts risk of heart failure using clinical data
- ✅ Trained with 80%+ accuracy using Random Forest
- ✅ Web-based UI for easy interaction
- ✅ Built with Flask, Bootstrap, and scikit-learn
- ✅ Clean, responsive design suitable for clinics or demos

---

## 📊 Dataset

The dataset contains health records of patients with the following attributes:

| Feature | Description |
|--------|-------------|
| `age` | Age of the patient |
| `anaemia` | Decrease of red blood cells (1 = Yes, 0 = No) |
| `creatinine_phosphokinase` | CPK enzyme level in the blood |
| `diabetes` | Patient has diabetes (1 = Yes, 0 = No) |
| `ejection_fraction` | Percentage of blood leaving the heart at each contraction |
| `high_blood_pressure` | Whether the patient has hypertension |
| `platelets` | Platelet count in the blood |
| `serum_creatinine` | Level of creatinine in the blood |
| `serum_sodium` | Level of sodium in the blood |
| `sex` | 1 = Male, 0 = Female |
| `smoking` | Whether the patient smokes |
| `time` | Follow-up period in days |

---

## 🧠 Machine Learning Model

- **Algorithm**: Random Forest Classifier
- **Accuracy**: ~80%
- **Preprocessing**: Feature scaling with `StandardScaler`
- **Frameworks**: scikit-learn, joblib

---

## 🌐 Web Application

The user interface is built with **Flask** and styled using **Bootstrap 5**. It allows users to:

- Input patient clinical data
- Submit the form for prediction
- Receive a real-time risk result:  
  ❤️ *Low Risk* or 💔 *High Risk of Heart Failure*

---

## ⚙️ How to Run Locally

### Prerequisites

- Python 3.7+
- pip

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/heart-failure-predictor.git
cd heart-failure-predictor
```
### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Application 
```bash
python app.py
```

Visit http://127.0.0.1:5000/ in your browser.
