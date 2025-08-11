# Credit Card Fraud Detection
[Credit_card_Fraud_detection.ipynb](https://github.com/Anujjadaun97/Credit-Card-Fraud-Detection/blob/main/Credit_card_Fraud_detection.ipynb)
## 📌 Project Overview

This project aims to detect fraudulent credit card transactions using **machine learning classification algorithms**.
Given the highly imbalanced nature of fraud detection datasets, the focus is on applying **data preprocessing, resampling techniques, and classification models** to improve detection accuracy.
Data - [Credit Card Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
---

## 📂 Project Structure

```
Credit_card_Fraud_detection.ipynb   # Main Jupyter Notebook
Credit Card Dataset                 # Dataset 
README.md                           # Project Documentation
```

---

## 🚀 Features

* Data loading and preprocessing
* Handling **class imbalance** with techniques like SMOTE
* Exploratory Data Analysis (EDA) with visualizations
* Feature scaling for model compatibility
* Training and evaluating classification models
* Performance comparison using metrics like precision, recall, F1-score, and ROC-AUC

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE, RandomOverSampler)

---

## 📊 Workflow

1. **Data Preprocessing** – Handle missing data, scale features
2. **EDA** – Identify patterns and anomalies
3. **Class Balancing** – Apply SMOTE or oversampling
4. **Model Building** – Train algorithms such as:

   * Logistic Regression
   * Decision Tree
   * Random Forest
   * XGBoost
5. **Model Evaluation** – Compare models with metrics suitable for imbalanced data

---

## 📈 Results

* Achieved high recall for detecting fraudulent transactions
* Balanced model performance between **fraud detection rate** and **false positives**
* ROC-AUC score indicates strong separation between classes

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the notebook:

```bash
jupyter notebook Credit_card_Fraud_detection.ipynb
```

---

## 📌 Future Enhancements

* Deploy as a real-time fraud detection API
* Implement deep learning models like **LSTMs** for sequence-based fraud patterns
* Add model explainability with **SHAP** or **LIME**

---

## 📜 License

This project is licensed under the MIT License.

---
