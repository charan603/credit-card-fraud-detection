# Credit Card Fraud Detection

##  About......................................................................................

This project uses machine learning to detect fraudulent credit card transactions.
It works on an imbalanced dataset and applies techniques to improve fraud detection accuracy.

---

## Features...................................................................................

* Data preprocessing and cleaning
* Handling imbalanced data using SMOTE
* Training machine learning models
* Model evaluation using different metrics

---

##  Dataset...................................................................................

link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

* Contains transaction data with features `V1` to `V28` (PCA transformed)
* `Amount` and `Time` columns included
* `Class` column:

  * `0` → Normal transaction
  * `1` → Fraud

---

##  How it Works...............................................................................


1. Load dataset
2. Scale features
3. Split data into train and test
4. Apply SMOTE to balance data
5. Train model (Logistic Regression)
6. Evaluate using metrics like accuracy, precision, recall

---

##  Evaluation Metrics..........................................................................


* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC Curve

---

##  Tech Stack...................................................................................


* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## ▶️ How to Run................................................................................


###  Run on Google Colab (Recommended)

1. Open Google Colab: https://colab.research.google.com
2. Click on **Upload Notebook**
3. Upload `Creditcard_Fraud.ipynb`
4. Upload the dataset file (`creditcard_fraud_detection.csv`) when prompted
5. Run all cells step by step (**Runtime → Run all**)

---

###  Run on Jupyter Notebook (Local)

1. Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn
```

2. Clone this repository:

```bash
git clone 
cd your-repo-name
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `Creditcard_Fraud.ipynb`

5. Run all cells

---

###  Notes

* Make sure the dataset file is in the same folder as the notebook
* For Colab, you may need to re-upload the dataset each session


##  Files...................................................................................


* `Creditcard_Fraud.ipynb` → Main notebook
* `creditcard_fraud_detection.csv` → Dataset

---

## 👤 Author...................................................................................


Charan Rayala
