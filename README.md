# 🩺 Diabetes Prediction Using Support Vector Machine (SVM)

This project uses Machine Learning to predict whether a person is diabetic based on health-related parameters. It leverages a Support Vector Machine (SVM) classifier and uses real-world data for training and evaluation.

---

## 📌 Project Overview

- **Goal**: Predict diabetes using health metrics such as glucose level, BMI, insulin, and more.
- **Dataset**: Pima Indians Diabetes Dataset (`diabetes.csv`)
- **Model Used**: Support Vector Machine (SVM) with linear kernel

---

## 💡 Key Features

- 📊 Exploratory Data Analysis (EDA)
- ⚙️ Data Preprocessing using `StandardScaler`
- ✂️ Train-Test Split with `train_test_split`
- 🧠 SVM Model Training and Evaluation
- 🧪 Prediction on custom input data
- 📈 Performance metrics: Accuracy, Precision, Recall, F1-Score

---

## 📁 Dataset Columns

- `Pregnancies`
- `Glucose`
- `BloodPressure`
- `SkinThickness`
- `Insulin`
- `BMI`
- `DiabetesPedigreeFunction`
- `Age`
- `Outcome` (Target: 0 = Non-diabetic, 1 = Diabetic)

---

## 🧠 Machine Learning Model

- **Model**: `SVC(kernel='linear')` from `scikit-learn`
- **Why SVM?**: 
  - Works well for binary classification
  - Effective in high-dimensional spaces
  - Uses a linear decision boundary in this case

---

## 🔄 Workflow

1. Load and explore the dataset
2. Split data into features (X) and labels (Y)
3. Standardize features using `StandardScaler`
4. Split dataset into training and test sets
5. Train the SVM model
6. Evaluate model accuracy on both sets
7. Use trained model to predict diabetes for new input data


