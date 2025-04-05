

# 🩺 Pima Diabetes Prediction

This project uses the Pima Indians Diabetes dataset to predict whether a patient has diabetes based on key medical attributes. A K-Nearest Neighbors (KNN) machine learning algorithm is implemented for classification, supported by data preprocessing, feature scaling, and model evaluation techniques.


## 📁 Dataset Overview

The dataset includes the following features:

| Feature                   | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `Pregnancies`             | Number of times pregnant                                                    |
| `Glucose`                 | Plasma glucose concentration after 2 hours in an oral glucose tolerance test |
| `BloodPressure`           | Diastolic blood pressure (mm Hg)                                           |
| `SkinThickness`           | Triceps skin fold thickness (mm)                                           |
| `Insulin`                 | 2-Hour serum insulin (mu U/ml)                                             |
| `BMI`                     | Body Mass Index (weight in kg/(height in m)^2)                             |
| `DiabetesPedigreeFunction` | A function scoring diabetes likelihood based on family history             |
| `Age`                     | Age of the patient (years)                                                 |
| `Outcome`                 | Class variable (0 = non-diabetic, 1 = diabetic)                             |

---

## 🚀 Project Workflow

### 1. 📊 Data Preprocessing
- Checked for null and duplicate values
- Scaled features using `StandardScaler` to improve KNN performance

### 2. 🤖 Model Building
- Used **K-Nearest Neighbors (KNN)** for classification
- Optimized value of `k` using accuracy plots

### 3. ✅ Evaluation
- Evaluated model using:
  - Accuracy score
  - Confusion matrix
  - Classification report

📈 Results

- Best Test Accuracy: **78.35%**
- Best `k` Value: **11**
- Model provides a good balance between precision and recall
- Useful for early diabetes risk screening


🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook


 📌 Future Improvements

- Add a web app interface using Streamlit or Flask
- Try different models (Logistic Regression, Random Forest)
- Handle class imbalance (SMOTE, undersampling)
- Use cross-validation for more reliable evaluation

---

## 🙌 Acknowledgements

- Dataset: [Pima Indians Diabetes Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
!
