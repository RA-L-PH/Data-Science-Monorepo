# Feature Scaling-Encoding

This module focuses on two key preprocessing steps essential for preparing data for machine learning models: **Feature Scaling** and **Feature Encoding**.

## 📂 Contents

| File | Description |
| :--- | :---------- |
| [Feature_Encoding.ipynb](./Feature_Encoding.ipynb) | Techniques to encode categorical variables into numerical values. |
| [Feature_Scaling.ipynb](./Feature_Scaling.ipynb) | Methods for scaling numerical features to standardize ranges. |


---

## 🎯 Purpose

Feature scaling and encoding ensure:
- Fair comparison between features of different scales.
- Faster and more stable convergence of optimization algorithms.
- Improved model performance and accuracy.
- Proper interpretation of categorical variables by machine learning models.

---

## 📘 Topics Covered

### 📌 Feature Encoding
Notebook: [Feature_Encoding.ipynb](./Feature_Encoding.ipynb)

Techniques discussed:
- **Label Encoding**
- **One-Hot Encoding**
- **Ordinal Encoding**
- **Binary Encoding**
- **Frequency Encoding**



---

### 📌 Feature Scaling
Notebook: [Feature_Scaling.ipynb](./Feature_Scaling.ipynb)

Techniques discussed:
- **Min-Max Scaling (Normalization)**
- **Standard Scaling (Z-score Standardization)**
- **Robust Scaling (for outlier-resistant scaling)**
- **Logrithmic Scaling**


---

## ⚙️ Requirements

Install the required Python libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
