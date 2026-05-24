# 🧠 Breast Cancer Classification using Machine Learning

This project builds a machine learning model to classify breast cancer tumors as **malignant or benign** based on diagnostic features.

---

## 📌 Problem Statement

Early detection of breast cancer is critical for effective treatment.  
This project uses machine learning to classify tumors as:

- **Malignant (0): Cancerous**
- **Benign (1): Non-cancerous**

---

## 📊 Dataset Information

- Source: Breast Cancer Wisconsin Dataset (sklearn)
- Total Samples: 569
- Features: 30 numeric features computed from digitized cell images
- Target Classes:
  - 0 → Malignant
  - 1 → Benign

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn

---

## 🤖 Machine Learning Model

- Algorithm: Logistic Regression
- Type: Binary Classification

---

## 🔄 Workflow

1. Load dataset from `sklearn.datasets`
2. Convert dataset into DataFrame
3. Perform data exploration and preprocessing
4. Split dataset into training and testing sets (80/20)
5. Train Logistic Regression model
6. Evaluate model performance
7. Build a prediction system for new input data

---

## 📈 Model Performance

- Training Accuracy: ~94%
- Testing Accuracy: ~93%

### Evaluation Metrics:
- Accuracy Score
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🧪 Prediction Example

The model predicts whether a tumor is:

- **Malignant (0)** → Cancerous
- **Benign (1)** → Non-cancerous
