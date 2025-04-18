# 💳 Credit Card Fraud Detection

This project focuses on building a classification model to detect fraudulent credit card transactions using machine learning techniques. It uses a Random Forest Classifier to identify patterns based on transaction amount, location, device usage, and user behavior.

---

## 📁 Dataset

The dataset includes transactional data with the following types of features:

- **Amount**: The monetary value of the transaction.
- **Location**: Geographic location where the transaction occurred.
- **Device**: Type of device used for the transaction.
- **User_Behavior**: Patterns like frequency, time, or spending habits.
- **Fraud**: Target variable (`1` for fraud, `0` for normal).

> 📌 You can upload your dataset file (e.g., `credit_card_fraud.csv`) while running the notebook.

---

## 🧠 Model Used

- **Random Forest Classifier**
- Trained using scikit-learn with 80/20 train-test split.

---

## 🔧 Tech Stack

- Python 🐍
- Pandas
- Seaborn & Matplotlib
- Scikit-learn
- Google Colab (for interactive execution)

---

## ⚙️ Workflow

1. **Import Libraries**
2. **Upload and Load Dataset**
3. **Data Cleaning & Preprocessing**
4. **Label Encoding for Categorical Data**
5. **Train/Test Split**
6. **Model Training with Random Forest**
7. **Predictions**
8. **Model Evaluation**
   - Confusion Matrix
   - Accuracy
   - Precision
   - Recall

---

## 📈 Model Performance Metrics

After training the model, the following evaluation metrics are displayed:

- ✅ **Accuracy**: Overall correctness of the model
- 🧪 **Precision**: How many predicted frauds were actual frauds
- 🔍 **Recall**: How many actual frauds were detected

A confusion matrix heatmap is also plotted for visual analysis.

---

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Run each cell step-by-step.
3. Upload your dataset when prompted.
4. View model performance and visualizations.

---

## 💡 Future Improvements

- Handle imbalanced classes using SMOTE or class weighting
- Try advanced models like XGBoost or LightGBM
- Feature engineering for deeper behavioral analysis
- Deployment via Flask or Streamlit

---


