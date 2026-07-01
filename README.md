# ❤️ Heart Disease Prediction using Support Vector Machine (SVM)

## 📌 Project Overview

Heart Disease Prediction is a Machine Learning web application developed using **Python**, **Scikit-learn**, and **Streamlit**. The application predicts whether a patient is at **High Risk** or **Low Risk** of heart disease based on various medical attributes.

The model was trained using a **Support Vector Machine (SVM)** classifier and achieved an **accuracy of 89.46%** on the test dataset.

The project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, deployment, and creating an interactive web application.

---

# 🌐 Live Demo

**Streamlit App:**

> https://heart-disease-prediction-xjzvefokjlwecskpf9ydbv.streamlit.app/

---

# 📊 Model Performance

| Metric | Value |
|---------|--------|
| Algorithm | Support Vector Machine (SVM) |
| Accuracy | **89.46%** |
| Feature Scaling | StandardScaler |
| Train-Test Split | 80:20 |
| Target Variable | HeartDisease |

---

# 🚀 Features

- ❤️ Heart disease risk prediction
- 📊 Machine Learning model using SVM
- 📈 89.46% prediction accuracy
- 📋 User-friendly Streamlit interface
- ⚡ Real-time prediction
- 🔄 Automatic data preprocessing
- 📦 Saved model using Joblib
- ☁️ Deployed on Streamlit Community Cloud
- 🖥️ Responsive and interactive interface

---

# 🧠 Machine Learning Workflow

The project follows a complete end-to-end machine learning pipeline.

## 1. Data Collection

The Heart Disease dataset contains various medical attributes of patients.

---

## 2. Data Preprocessing

The dataset was cleaned before model training by performing:

- Removing unnecessary values
- Handling categorical variables
- One-Hot Encoding
- Feature Scaling using StandardScaler
- Preparing training and testing datasets

---

## 3. Feature Engineering

Categorical features were converted into numerical features using **One-Hot Encoding**.

Examples:

```
Sex
↓

Male → Sex_M = 1
Female → Sex_M = 0
```

```
ChestPainType

ATA
NAP
ASY
TA
```

were converted into multiple binary columns.

---

## 4. Feature Scaling

Numerical features were standardized using:

```
StandardScaler
```

Scaled Features:

- Age
- RestingBP
- Cholesterol
- MaxHR
- Oldpeak

---

## 5. Model Training

Multiple machine learning algorithms were tested:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- **Support Vector Machine (Best Model)**

The Support Vector Machine achieved the highest performance.

---

# 📈 Model Evaluation

The model was evaluated using:

- Accuracy Score
- F1 Score

Final Accuracy:

# ⭐ 89.46%

---

# 📂 Dataset Features

| Feature | Description |
|-----------|-------------------------------|
| Age | Age of patient |
| Sex | Male / Female |
| ChestPainType | Chest pain category |
| RestingBP | Resting blood pressure |
| Cholesterol | Serum cholesterol |
| FastingBS | Fasting blood sugar |
| RestingECG | ECG results |
| MaxHR | Maximum heart rate |
| ExerciseAngina | Exercise-induced angina |
| Oldpeak | ST depression |
| ST_Slope | Slope of ST segment |
| HeartDisease | Target variable |

---

# 🛠️ Technologies Used

### Programming Language

- Python

### Machine Learning

- Scikit-learn

### Libraries

- Pandas
- NumPy
- Joblib

### Deployment

- Streamlit

### Version Control

- Git
- GitHub

---

# 📂 Project Structure

```
heart-disease-prediction/
│
├── app.py
├── Heart_Disease_Prediction.ipynb
├── heart.csv
├── SVM_heart.pkl
├── scaler.pkl
├── columns.pkl
├── requirements.txt
├── README.md
│
└── screenshots/
      home.png
      prediction.png
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yugsaxena102/heart-disease-prediction.git
```

Go to project folder

```bash
cd heart-disease-prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Streamlit

```bash
streamlit run app.py
```

---

# 📸 Screenshots

## Home Page

(Add screenshot here)

---

## Prediction Result

(Add screenshot here)

---

# 💡 Future Improvements

- Deep Learning implementation
- Random Forest comparison
- XGBoost implementation
- Probability prediction
- SHAP Explainability
- Feature Importance visualization
- User authentication
- Database integration
- Medical report generation
- Cloud deployment using Docker

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing
- Feature engineering
- One-Hot Encoding
- StandardScaler
- Support Vector Machine (SVM)
- Model evaluation
- Saving models with Joblib
- Streamlit web development
- Git and GitHub
- Cloud deployment

---



GitHub

https://github.com/yugsaxena102

---

# 🙏 Acknowledgements

- Scikit-learn
- Streamlit
- Pandas
- NumPy
- UCI/Kaggle Heart Disease Dataset

---
