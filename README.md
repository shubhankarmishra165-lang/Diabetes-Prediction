# 🩺 Diabetes Prediction Using Machine Learning

## 📌 Overview

This project predicts whether a patient is diabetic based on medical attributes such as glucose level, BMI, age, blood pressure, insulin, and other health parameters. It includes data preprocessing, exploratory data analysis (EDA), feature scaling, and machine learning models to achieve accurate predictions.

---

## ✨ Features

- 📊 Exploratory Data Analysis (EDA)
- 📈 Data Visualization
- 🧹 Data Preprocessing
- ⚙️ Feature Scaling using StandardScaler
- 🤖 Logistic Regression Model
- 🌲 Random Forest Classifier
- 📉 Confusion Matrix
- 📊 Model Performance Comparison
- 🔍 Diabetes Prediction on New Data

---

# 📂 Dataset

The project uses the **Pima Indians Diabetes Dataset**.

| Feature | Description |
|---------|-------------|
| Pregnancies | Number of Pregnancies |
| Glucose | Plasma Glucose Concentration |
| BloodPressure | Diastolic Blood Pressure |
| SkinThickness | Skin Fold Thickness |
| Insulin | Serum Insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes Pedigree Function |
| Age | Patient Age |
| Outcome | 0 = Non-Diabetic, 1 = Diabetic |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📊 Exploratory Data Analysis

## Correlation Heatmap

> Replace the image below with your own heatmap.

<p align="center">
<img src="images/heatmap.png" width="650">
</p>

---

# ⚙️ Data Preprocessing

- Checked Missing Values
- Removed Duplicate Records
- Feature Scaling using **StandardScaler**
- Train-Test Split (80% Training, 20% Testing)

---

# 🤖 Machine Learning Models

| Model | Description |
|--------|-------------|
| Logistic Regression | Linear Classification Model |
| Random Forest | Ensemble Decision Tree Model |

---

# 📈 Model Performance

Replace the values below with your actual results.

| Machine Learning Model | Training Accuracy | Testing Accuracy |
|-------------------------|------------------:|-----------------:|
| Logistic Regression | **XX.XX%** | **XX.XX%** |
| Random Forest | **XX.XX%** | **XX.XX%** |

---

# 📉 Confusion Matrix

## Logistic Regression

<p align="center">
<img src="images/lr_confusion_matrix.png" width="500">
</p>

---

## Random Forest

<p align="center">
<img src="images/rf_confusion_matrix.png" width="500">
</p>

---

# 📊 Accuracy Comparison

<p align="center">
<img src="images/model_accuracy.png" width="650">
</p>

---

# 🔍 Sample Prediction

```python
x = np.array([[8,183,64,0,0,23.3,0.672,32]])
prediction = model.predict(x)

print(prediction)
```

Output

```
1 → Diabetic
```

---

# 📁 Project Structure

```
Diabetes-Prediction/
│
├── images/
│   ├── heatmap.png
│   ├── lr_confusion_matrix.png
│   ├── rf_confusion_matrix.png
│
├── Diabetes_Prediction.ipynb
├── diabetes.csv
├── requirements.txt
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Diabetes-Prediction.git
```

Move to the project directory

```bash
cd Diabetes-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 📦 Required Libraries

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 🎯 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- XGBoost
- LightGBM
- CatBoost
- SHAP Explainability
- Streamlit Web App
- Flask/FastAPI Deployment

---

# 👨‍💻 Author

**Shubhankar Mishra**

GitHub: https://github.com/shubhankarmishra165-lang

---

# ⭐ Show Your Support

If you found this project useful, don't forget to ⭐ the repository!
