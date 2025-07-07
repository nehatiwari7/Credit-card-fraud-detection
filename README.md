# 💳 Credit Card Fraud Detection
This project uses a Logistic Regression model to detect fraudulent transactions in credit card data using the Kaggle dataset.

## 📌 Dataset Description
- The dataset contains credit card transactions made by European cardholders in September 2013.
- It includes 284,807 transactions, with *492 frauds* (~0.172%).
- Features V1 to V28 are numerical components obtained via PCA (due to privacy).
- 'Time' and 'Amount' are the only original features.
- 'Class' is the target variable (0 = Normal, 1 = Fraudulent).

[🔗 View Dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---
## 🛠️ Technologies Used
- Python 3
- Google Colab
- Libraries: pandas, scikit-learn, numpy, matplotlib, seaborn
---
## 🧠 Model Details
- *Algorithm*: Logistic Regression
- *Evaluation Metrics*: Confusion Matrix, Precision, Recall, AUC-PR (due to class imbalance)
---
## 🚀 How to Run
1. Open the .ipynb file in Google Colab 
2. Run all cells to load the data, preprocess, train, and test the model
3. You can change the input data manually to test predictions
---
## 🧪 Sample Input & Prediction
```python
input_data = pd.DataFrame([[...]])
pred = model.predict(input_data)
---

