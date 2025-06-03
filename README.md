# Parkinson-s-Disease-Progression-Prediction-Using-Feedforward-Neural-Network
# 🧠 Parkinson’s Disease Progression Prediction Using Feedforward Neural Network

This project uses a Feedforward Neural Network (FNN) for predicting the progression stage of Parkinson’s disease based on clinical and behavioral data. It aims to support early diagnosis and treatment planning.

---

## 📊 Dataset Description

The dataset includes 500 patient records with the following features:

- Age
- Gender
- Years_Since_Diagnosis
- UPDRS_Score (Unified Parkinson’s Disease Rating Scale)
- Tremor_Severity
- Motor_Function
- Speech_Difficulty
- Balance_Problems
- Medications
- Exercise_Level

**Target Variable:**
- Disease_Progression (Numeric label from 1 to 5)

*Categorical variables are encoded using LabelEncoder.*

---

## 🧠 Model Architecture

The FNN model is built using TensorFlow/Keras with the following layers:

- Input: 11 features
- Hidden Layers: 64 → 32 → 16 neurons (ReLU activation)
- Output: 1 neuron for regression
- Loss Function: Mean Squared Error (MSE)
- Optimizer: Adam

---

## ✅ Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Approximate Classification Accuracy (rounded predictions)


---

## 💡 Future Enhancements

- Add dropout for regularization
- Try XGBoost or ensemble techniques
- Include cross-validation
- Build a Streamlit web app for user interaction

---

---

## 🙏 Acknowledgements

- Inspired by real-world healthcare machine learning projects.
- Dataset simulated or sourced from open datasets related to Parkinson’s disease.

---

## 📬 Contact

For queries or collaborations:

📧 speranzadeejoemini@gmail.com

---

⭐ If you found this helpful, give the repo a star!


