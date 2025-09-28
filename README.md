# Sonar Rock vs Mine Prediction 🎯

This project is a **machine learning model** that predicts whether an object detected by sonar signals is a **rock** or a **mine (metal cylinder)**.
It is implemented and executed using **Google Colab**, making it easy to run in the cloud without local setup.

---

## 📌 Problem Statement

Sonar is widely used in **underwater object detection**.

* **Rock (R):** Natural underwater rock formations.
* **Mine (M):** Metal objects such as mines or cylinders.

The objective is to classify sonar signals as **Rock** or **Mine** using supervised machine learning.

---

## 📂 Dataset

* **Source:** [UCI Machine Learning Repository – Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+sonar+mines+vs+rocks)
* **Features:** 60 numerical values (0.0–1.0) representing sonar signal strength.
* **Target:** `R` (Rock) or `M` (Mine).

---

## 🛠️ Tech Stack

* **Google Colab** (Jupyter Notebook environment)
* **Python Libraries:**

  * NumPy
  * Pandas
  * Matplotlib / Seaborn
  * Scikit-learn

---

## ⚙️ Workflow

1. **Load dataset** into Colab
2. **Exploratory Data Analysis (EDA):** Distribution, visualization, correlation
3. **Data Preprocessing:** Label encoding, scaling, splitting
4. **Model Training:** Logistic Regression / SVM / Random Forest
5. **Model Evaluation:** Accuracy, confusion matrix, classification report
6. **Prediction on new data:** User can input sonar readings to test results

---

## 🚀 Running the Project on Colab

1. Open the Colab notebook:
   [![Open In Colab]

2. Make a copy in your Google Drive.

3. Run all cells.

4. Try predictions with custom inputs.

---

## 📊 Results

* Achieved accuracy of **83.4%** for training data and **76%** for test data.
* Model successfully distinguishes rocks from mines using sonar data.

---
