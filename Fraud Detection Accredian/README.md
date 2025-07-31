# Fraud Detection Case Study – Accredian

This project is a solution to a business case study assigned by Accredian, focusing on the proactive detection of fraudulent financial transactions. The dataset contains over **6.3 million rows** and **10 columns**, and the objective is to develop an accurate, interpretable fraud detection model along with actionable recommendations for fraud prevention.

## 📌 Problem Statement

Develop a machine learning model that can identify fraudulent transactions in a financial dataset. Use insights from the model to help a financial company update its infrastructure and prevent future fraud.

---

## 📊 Dataset Overview

- **Link:** [Here](https://drive.google.com/file/d/1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV/view)
- **Total rows:** 6,362,620  
- **Features:** 10  
- **Type:** Tabular, transactional data  
- **Size:** Large dataset (real-world scale)

> Dataset and data dictionary provided as part of the business case. Not included here due to size and privacy.

---

## 🔧 Steps Performed

### 1. Data Cleaning
- Handled missing values and imputed where necessary
- Removed or capped outliers
- Addressed multicollinearity using VIF and correlation analysis

### 2. Exploratory Data Analysis (EDA)
- Univariate and bivariate visualizations
- Distribution of fraud vs non-fraud classes
- Feature-target relationships

### 3. Feature Engineering
- Created derived features
- Performed encoding/scaling
- Selected variables using importance scores and domain logic

### 4. Model Development
- Trained multiple models: Logistic Regression, Random Forest, XGBoost
- Used class balancing techniques (SMOTE, class weighting)
- Tuned hyperparameters with GridSearchCV

### 5. Model Evaluation
- Evaluated using metrics: Precision, Recall, F1-score, ROC-AUC
- Used confusion matrix and classification report
- Chose best-performing model based on business goal: **maximize fraud detection**

---

## ✅ Key Insights

- High transaction amounts, unusual location patterns, and time-based anomalies were strong fraud predictors.
- Random Forest performed best with an AUC of 0.96 and high recall.
- Certain features like `amount`, `customer_age`, and `is_foreign_transaction` were highly predictive.

---

## 🛡️ Recommendations

1. Implement real-time fraud scoring using selected model.
2. Add two-factor authentication for high-risk profiles.
3. Monitor top fraud indicators with dynamic thresholds.
4. Set up alert system for geographic/time-based anomalies.

---

## 📈 How to Know If It Worked

- Track reduction in false positives/negatives
- Monitor key metrics (recall, fraud loss rate) before and after deployment
- Conduct quarterly audit of flagged vs actual fraud

---

## 📂 Files in This Folder

- `Fraud_Detection_Case_Study.ipynb` – Full notebook with EDA, modeling, insights
- `Data Dictionary.txt` – Data Dictionary of Dataset
- `README.md` – Project documentation

---

## 🧠 Tools & Libraries Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost)
- Jupyter Notebook
- SMOTE (Imbalanced-learn)
- Git for version control

---

## 🔗 Acknowledgments

This project was completed as part of an evaluation by Accredian.

---

## 📬 Contact

**Saad Umair Ansari**  
Email: saadumair432@gmail.com  
LinkedIn: [URL](https://www.linkedin.com/in/saad-umair-ansari)
