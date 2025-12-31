
### 🏥 Medical Cost Prediction using Machine Learning
[Try Here](https://huggingface.co/spaces/WajeehaAhmadAbbasi/Medical_insurance_cost_prediction)

#### 📌 Project Overview

This project predicts **individual medical insurance costs** using demographic and lifestyle features. Accurate cost prediction helps insurance providers better assess risk, pricing, and healthcare planning.

Multiple **regression models** were trained and evaluated. Ensemble methods, particularly **Gradient Boosting Regressor**, demonstrated strong performance due to their ability to model non-linear relationships in structured healthcare data.

---

### 🎯 Problem Statement

Given information such as age, BMI, smoking status, number of dependents, and region, predict the **medical insurance charges** for an individual.

---

### 🗂 Dataset Description

**Features**

* Age
* Sex
* BMI (Body Mass Index)
* Children (number of dependents)
* Smoker
* Region

**Target Variable**

* **Charges**: Individual medical expenses billed by health insurance

---

### 🔄 Data Preprocessing

* Encoded categorical variables using **Label Encoding and One-Hot Encoding**
* Scaled numerical features using **StandardScaler**
* Applied feature transformations using **PowerTransformer** to handle skewness
* Used **ColumnTransformer** and **Pipeline** for clean and reproducible preprocessing

---

### ⚙️ Machine Learning Models Implemented

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Support Vector Regressor (SVR)
* Gradient Boosting Regressor

---

### 📈 Model Evaluation

Models were evaluated using:

* **Root Mean Squared Error (RMSE)**
* **Mean Squared Error (MSE)**
* **R² Score**
* **Cross-validation**
---

### 🛠 Tech Stack

* **Language:** Python
* **Libraries:** NumPy, Matplotlib, Plotly, Scikit-learn, Joblib

---

### 🚀 How to Run the Project

```bash
git clone <repository-url>
pip install -r requirements.txt
python medical_cost_prediction.py
```

---

### 💾 Model Deployment

* Trained model saved using **Joblib**
---

### 🔮 Future Improvements

* Hyperparameter tuning using **GridSearchCV**
* Model explainability using **SHAP**


