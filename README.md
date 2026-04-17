# 🩺 Diabetes Prediction using Machine Learning

## 📌 Project Name

**DiabetesGuard AI: Early Diabetes Prediction System**

---

## 📖 Project Description

This project is a Machine Learning-based system that predicts whether a person is diabetic or not using medical diagnostic data. It uses classification algorithms such as Logistic Regression and Random Forest to analyze patient health indicators and provide predictions.

The goal is to help in early detection of diabetes using data science techniques.

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* Jupyter Notebook / Python Script

---

## 📊 Dataset

The dataset used is the **Pima Indians Diabetes Dataset**, which includes features like:

* Glucose level
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Age
* Pregnancies

Target variable:

* **Outcome (0 = Healthy, 1 = Diabetic)**

---

## 🧠 Machine Learning Models Used

* Logistic Regression
* Random Forest Classifier
* Tuned Logistic Regression (GridSearchCV)

---

## 🔄 Workflow

1. Import libraries
2. Load dataset
3. Data cleaning (handling zeros and missing values)
4. Data visualization
5. Feature scaling
6. Train/test split
7. Model training
8. Model evaluation
9. Hyperparameter tuning
10. Model comparison
11. Save & load model

---

## 📈 Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC-AUC Curve
* Cross Validation Score

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/diabetes-guard-ai.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the script

```bash
python diabetes_prediction.py
```

---

## 📦 Requirements

Create a `requirements.txt` file with:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
```

---

## 📊 Results

The model achieves good accuracy in predicting diabetes cases and shows that Random Forest performs better compared to Logistic Regression in most cases.

---

## 💾 Model Saving

The trained model and scaler are saved using Joblib:

* diabetes_model.pkl
* scaler.pkl

---

## 📌 Future Improvements

* Deploy using Flask or Streamlit
* Add real-time prediction web app
* Improve accuracy with advanced models (XGBoost, Neural Networks)

---

## 👨‍💻 Author

Developed by: **Ahmed Osama**

---

## 📜 License

This project is for educational purposes only.
