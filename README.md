# Logistic Regression for Classification

This repository contains a Jupyter Notebook that demonstrates the use of **Logistic Regression** for classification tasks. The notebook covers multiple datasets, including customer churn prediction, synthetic classification data, and breast cancer classification.

## 📌 Features
- **Customer Churn Prediction**
  - Reads `ChurnData.csv`
  - Splits data into training and test sets
  - Trains logistic regression model
  - Evaluates accuracy before and after feature scaling

- **Synthetic Data Classification**
  - Generates and visualizes synthetic datasets for binary classification
  - Tests logistic regression performance on linearly and non-linearly separable data

- **Breast Cancer Classification (Real-World Dataset)**
  - Loads the built-in breast cancer dataset from `scikit-learn`
  - Splits data into training and test sets
  - Trains logistic regression model
  - Evaluates model performance on real-world medical data

## 📂 Files
- `Logistic Regression.ipynb` - Jupyter Notebook with all implementations
- `ChurnData.csv` - Dataset for churn prediction (ensure it is placed in the working directory)

## 🛠 Dependencies
The notebook uses the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

To install missing dependencies, run:
```bash
pip install pandas numpy matplotlib scikit-learn
```

## 🔍 How to Use
1. Open the Jupyter Notebook (`Logistic Regression.ipynb`).
2. Run each cell sequentially to train and evaluate models.
3. Modify parameters (e.g., test size, solver, scaling method) to experiment with different setups.

## 📈 Results
- Logistic Regression achieves reasonable accuracy for all datasets.
- Feature scaling improves model performance in some cases.
- Non-linearly separable data is more challenging for logistic regression.
- The model performs well on **real-world breast cancer data**, demonstrating its practical application in medical diagnosis.


