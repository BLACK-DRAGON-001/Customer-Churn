# 📊 Customer Churn Analysis & Prediction

A data-driven project to analyze and predict customer churn using machine learning, with interactive dashboards built in Power BI for business insights.

---

## 🔍 Problem Statement

Customer churn occurs when customers stop doing business with a company. This project aims to:
- Analyze customer behavior patterns from a telecom dataset.
- Predict churn using supervised learning models.
- Visualize key trends in churn behavior using interactive dashboards.

---

## 📁 Dataset

- **Source**: `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Records**: 7,043
- **Features**: 21 columns including customer demographics, account information, services signed up, and churn status.

---

## 🛠 Tools & Technologies Used

| Task                  | Tools & Libraries                         |
|-----------------------|-------------------------------------------|
| Data Manipulation     | `pandas`, `numpy`                         |
| Data Visualization    | `matplotlib`, `seaborn`, `plotly`         |
| NLP (for reviews)     | `TextBlob`, `NLTK`                        |
| Machine Learning      | `scikit-learn` (`RandomForest`, `LogisticRegression`) |
| Dashboarding          | `Power BI`                                |
| Notebook              | `Jupyter Notebook (.ipynb)`               |

---

## 📈 Key Steps

### 1. 📦 Data Loading & Preprocessing
- Handled missing values (e.g., TotalCharges column).
- Converted categorical variables using Label Encoding / One-Hot Encoding.
- Ensured correct data types.

### 2. 🔍 Exploratory Data Analysis (EDA)
- Churn distribution
- Contract types vs churn
- Tenure & monthly charges analysis
- Services (Internet, TechSupport) vs churn

### 3. 💡 Feature Engineering
- Created tenure groups
- Scaled numerical columns with `StandardScaler`

### 4. 🧠 Machine Learning Models
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- XGBoost (optional)

> Metrics evaluated: **Accuracy**, **Precision**, **Recall**, **F1 Score**, and **ROC-AUC**

### 5. 📊 Power BI Dashboard
- Built an interactive churn dashboard:
  - Churn by contract type, payment method
  - Tenure vs Churn heatmap
  - Monthly Charges trends

---

## 📌 Results

| Model              | Accuracy | F1 Score | AUC  |
|-------------------|----------|----------|------|
| Logistic Regression | 80.1%   | 0.74     | 0.84 |
| Random Forest       | 82.5%   | 0.76     | 0.87 |
| SVM                 | 79.8%   | 0.73     | 0.83 |

- Key Drivers of churn:
  - Month-to-month contracts
  - Lack of online security/tech support
  - High monthly charges

---

Created by Sarthak Dey

### 1. Clone this Repository
```bash
git clone https://github.com/yourusername/customer-churn-analysis.git
cd customer-churn-analysis
