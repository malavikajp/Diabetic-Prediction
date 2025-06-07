# 🩺 Diabetes Prediction

A simple machine learning project to predict whether a person is diabetic using health data and a Support Vector Machine (SVM) model.

## 📊 Dataset
- Pima Indians Diabetes dataset (`diabetes.csv`)
- Features: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age
- Target: Outcome (0 = Non-diabetic, 1 = Diabetic)

## ⚙️ Workflow
- Data loading & analysis
- Feature scaling with `StandardScaler`
- Train-test split (80/20)
- Model training using `SVC(kernel='linear')`
- Accuracy evaluation on both training & testing data
- Predicts outcome for new patient data

## 🚀 How to Run
1. Clone repo / open notebook in Colab
2. Ensure `diabetes.csv` is in the same directory
3. Run cells in order

## 🧠 Tech Stack
- Python, Pandas, NumPy, Scikit-learn

## 📌 Future Ideas
- Try other classifiers
- Hyperparameter tuning
- Deploy using Streamlit
