# 💳 CrediWise: Predict. Approve. Prosper.

A Machine Learning-based Loan Eligibility Prediction System that automates the loan approval process by analyzing applicant information and predicting whether a loan application should be approved or rejected. The project compares multiple classification algorithms to identify the most accurate model for loan prediction.

---

## 📌 Project Overview

Traditional loan approval processes are often time-consuming, manual, and prone to inconsistencies. CrediWise leverages Machine Learning to assist financial institutions in making faster, data-driven, and more reliable loan approval decisions.

The system analyzes applicant details such as income, credit history, education, marital status, employment status, loan amount, and property area to predict loan eligibility.

---

## ✨ Features

- Automated loan eligibility prediction
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Feature transformation using Log Scaling
- Multiple Machine Learning model comparison
- Hyperparameter tuning
- Confusion Matrix visualization
- Cross-validation for model evaluation

---

## 📂 Dataset

**Dataset:** Loan Prediction Dataset (Kaggle)

The dataset contains applicant information including:

- Loan ID
- Gender
- Married
- Dependents
- Education
- Self Employed
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area
- Loan Status (Target Variable)

---

## ⚙️ Project Workflow

```text
Loan Prediction Dataset
          │
          ▼
Data Preprocessing
          │
          ▼
Missing Value Handling
          │
          ▼
Exploratory Data Analysis
          │
          ▼
Feature Engineering
          │
          ▼
Log Transformation
          │
          ▼
Label Encoding
          │
          ▼
Train-Test Split
          │
          ▼
Machine Learning Models
    ├── Logistic Regression
    ├── Decision Tree
    └── Random Forest
          │
          ▼
Model Comparison
          │
          ▼
Hyperparameter Tuning
          │
          ▼
Confusion Matrix
          │
          ▼
Loan Approval Prediction
```

---

## 🧹 Data Preprocessing

The dataset is prepared using several preprocessing techniques:

- Handling missing values
- Mean imputation for numerical features
- Mode imputation for categorical features
- Feature engineering
- Log transformation for skewed data
- Label Encoding
- Feature selection

---

## 📊 Exploratory Data Analysis

EDA is performed to better understand the dataset through visualizations such as:

- Categorical feature distribution
- Numerical feature distribution
- Log-transformed distributions
- Correlation Heatmap
- Loan Status distribution

---

## 🛠 Feature Engineering

Additional features are created to improve prediction performance.

### Total Income

```python
Total_Income = ApplicantIncome + CoapplicantIncome
```

Logarithmic transformation is applied to:

- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Total Income

This helps reduce skewness and improves model performance.

---

## 🤖 Machine Learning Models

The following supervised learning algorithms were implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Each model is evaluated using:

- Accuracy
- Cross Validation Score

---

## 🎯 Hyperparameter Tuning

The Random Forest model is further optimized by tuning parameters such as:

- Number of Estimators
- Maximum Depth
- Minimum Samples Split
- Maximum Features

This improves the model's predictive performance.

---

## 📈 Model Evaluation

Evaluation techniques include:

- Accuracy Score
- Cross Validation
- Confusion Matrix

The best-performing model is selected based on its overall prediction performance.

---

## 🛠 Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Development Environment

- Jupyter Notebook
- Google Colab

---

## 📁 Project Structure

```text
CrediWise/
│
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
│
├── notebook/
│   └── CrediWise.ipynb
│
├── docs/
│   └── CrediWiseDocumentation.pdf
│
└── data/
    └── README.md
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/CrediWise.git
```

2. Navigate to the project directory

```bash
cd CrediWise
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Open the notebook

```bash
jupyter notebook
```

5. Run all cells in `CrediWise.ipynb`

---

## 📊 Results

- Successfully automated loan eligibility prediction.
- Compared Logistic Regression, Decision Tree, and Random Forest models.
- Applied feature engineering and preprocessing to improve prediction quality.
- Achieved improved performance through Random Forest hyperparameter tuning.
- Generated confusion matrix and cross-validation metrics for model evaluation.

---

## 🔮 Future Enhancements

- Deploy as a web application using Flask or Streamlit
- Integrate real-time loan application forms
- Implement XGBoost and LightGBM
- Use SHAP for explainable AI
- Connect with external credit score APIs
- Cloud deployment using AWS or Azure

---

## 📷 Sample Outputs

You can include screenshots of:

- Missing Value Handling
- EDA Visualizations
- Correlation Heatmap
- Model Comparison
- Hyperparameter Tuning
- Confusion Matrix

---

## 👩‍💻 Author

- **Akanksha**

Bachelor of Technology (CSE - Data Science)

---

## 📜 License

This project is developed for academic and educational purposes.
