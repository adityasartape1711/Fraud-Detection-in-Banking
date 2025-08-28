#Fraud Detection in Banking

##  Project Overview

Fraudulent transactions are a major concern in the banking sector, leading to significant financial losses and security risks. This project aims to build a **machine learning-based fraud detection system** that identifies suspicious transactions in real-time.

The model is trained on historical transaction data and uses **statistical analysis, feature engineering, and classification algorithms** to detect anomalies that indicate fraud.

---

##  Objectives

* Detect fraudulent banking transactions with high accuracy.
* Reduce false positives while ensuring genuine transactions remain unaffected.
* Provide insights into the transaction patterns that lead to fraud.

---

##  Dataset

* The dataset contains anonymized **banking transaction records**.
* Features include transaction details such as amount, time, type, and other anonymized variables.
* Target variable:

  * `0` → Legitimate Transaction
  * `1` → Fraudulent Transaction

*(Replace with your actual dataset name and description if needed)*

---

##  Tech Stack

* **Programming Language:** Python
* **Libraries & Tools:**

  * Pandas, NumPy – Data preprocessing
  * Matplotlib, Seaborn – Data visualization
  * Scikit-learn – Machine learning models
  * XGBoost / Random Forest / Logistic Regression – Classification algorithms

---

##  Exploratory Data Analysis (EDA)

* Distribution of fraudulent vs non-fraudulent transactions
* Correlation between features
* Data imbalance handling (SMOTE / undersampling / oversampling)

---

##  Machine Learning Models

Implemented and compared multiple models:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

Evaluation Metrics:

* Accuracy
* Precision, Recall, F1-score
* ROC-AUC Curve

---

## Results

* Training Logistic Regression...
   Accuracy: 1.0000
   F1-Score: 0.9985
   AUC: 0.9992

 * Training Random Forest (Fast Config)...
   Accuracy: 1.0000
   F1-Score: 0.9985
   AUC: 0.9995

 * Best Model: Random Forest
   AUC Score: 0.9995

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/fraud-detection-banking.git
   cd fraud-detection-banking
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook / Python script:

   ```bash
   jupyter notebook Fraud_Detection.ipynb
   ```

---

##  Future Improvements

* Deploy as a **web application** using Flask/Django.
* Integrate **real-time fraud detection API** for banking systems.
* Experiment with **Deep Learning models (LSTMs/Autoencoders)** for anomaly detection.

---

##  Contributing

Contributions are welcome! Feel free to fork the repo, raise issues, or submit pull requests.

---

## Author

 **Aditya Sartape**

