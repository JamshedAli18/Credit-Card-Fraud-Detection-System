# 💳 Credit Card Fraud Detection System

This project uses **machine learning** to detect fraudulent credit card transactions. Using a real-world dataset from **Kaggle**, we trained and evaluated a model that can identify fraud with **high accuracy and reliability**.

---

## 📁 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Records**: 284,807 transactions
- **Fraud cases**: 492 (highly imbalanced)
- **Features**:
  - `V1` to `V28`: PCA-transformed features (due to confidentiality)
  - `Amount`, `Time`: Actual transaction details
  - `Class`: Target variable (0 = Normal, 1 = Fraud)

---

## 🔍 What Was Done

1. **Exploratory Data Analysis (EDA)**  
   - Visualized class imbalance  
   - Checked data distribution and missing values  

2. **Data Preprocessing**  
   - Scaled `Amount` and `Time` features using `StandardScaler`  
   - Split the dataset into training and testing sets  

3. **Model Training**  
   - Used `RandomForestClassifier` for classification  
   - Handled class imbalance with stratified split  

4. **Model Evaluation**  
   - Evaluated using key metrics: Accuracy, Precision, Recall, F1 Score, ROC AUC  
   - Plotted Confusion Matrix  

---

## ✅ Results

| Metric         | Value         |
|----------------|---------------|
| Accuracy       | **0.9996**    |
| Precision      | **0.9412**    |
| Recall         | **0.8163**    |
| F1 Score       | **0.8743**    |
| ROC AUC Score  | **0.9081**    |

> The model performs very well, especially considering the highly imbalanced nature of the dataset.

---


## 💡 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (RandomForestClassifier, Metrics)

---

## 📌 How to Run

1. Open the project in **Kaggle Notebook**
2. Upload the dataset or load it via Kaggle Datasets
3. Run all cells – results will be printed and plotted

---

## 🙌 Author

This project is built and maintained by [Your Name]  
Feel free to fork, improve, and contribute!

