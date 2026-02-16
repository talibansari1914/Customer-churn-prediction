# 📊 Customer Churn Prediction Project

## 📌 Project Overview
This project focuses on predicting customer churn using Machine Learning models.  <br>
Customer churn prediction helps businesses identify customers who are likely to leave, allowing proactive retention strategies.<br>

The project includes:<br>
- Data Analysis (EDA)<br>
- Data Preprocessing<br>
- Feature Engineering<br>
- Model Building<br>
- Model Evaluation<br>
- Performance Comparison<br>

---

## 📂 Dataset Information

- Dataset Name: Telco Customer Churn<br>
- Rows: 7043<br>
- Columns: 33<br>
- Target Variable: `Churn`<br>
    - 0 → No Churn<br>
    - 1 → Churn<br>

The dataset contains customer demographic details, service subscriptions, account information, and billing details.<br>

---

## 🛠️ Technologies & Libraries Used

- Python<br>
- Pandas<br>
- NumPy<br>
- Matplotlib<br>
- Seaborn<br>
- Scikit-learn<br>
- XGBoost<br>

---

## 🔎 Exploratory Data Analysis (EDA)

Steps performed:<br>

- Checked dataset shape<br>
- Inspected data types<br>
- Identified missing values<br>
- Checked class imbalance<br>
- Visualized categorical and numerical features<br>
- Analyzed churn distribution<br>

Key Observations:<br>
- Dataset is imbalanced (Non-churn customers > Churn customers)<br>
- Contract type, tenure, monthly charges, and internet service strongly impact churn<br>

---

## 🧹 Data Preprocessing

Steps performed:<br>

1. Removed unnecessary columns<br>
2. Handled missing values<br>
3. Converted categorical variables using:<br>
   - OneHotEncoder<br>
4. Scaled numerical features using:<br>
   - StandardScaler<br>
5. Used ColumnTransformer for pipeline-based preprocessing<br>
6. Split data:<br>
   - 80% Training<br>
   - 20% Testing<br>

---

## 🤖 Models Implemented

### 1️⃣ Logistic Regression
- Baseline model<br>
- Good interpretability<br>

### 2️⃣ Random Forest Classifier
- Ensemble model<br>
- Handles non-linearity well<br>
- Provides feature importance<br>

### 3️⃣ XGBoost Classifier
- Gradient Boosting model<br>
- High performance<br>
- Best overall accuracy & ROC-AUC<br>

---

## 📈 Model Evaluation Metrics

Evaluation Metrics Used:<br>

- Confusion Matrix<br>
- Precision<br>
- Recall<br>
- F1-Score<br>
- ROC-AUC Score<br>
- ROC Curve<br>

### 📊 Confusion Matrix (Best Model)

[[763 272]<br>
[ 82 292]]<br>


### 📈 ROC-AUC Score

0.8360<br>


This indicates strong classification performance.<br>

---

## 🔥 Feature Importance

Important features affecting churn:<br>

- Contract Type<br>
- Tenure<br>
- Monthly Charges<br>
- Total Charges<br>
- Internet Service<br>
- Payment Method<br>

These features can help business analysts design retention strategies.<br>

---

## 💼 Business Insights

- Customers with month-to-month contracts are more likely to churn.<br>
- Higher monthly charges increase churn probability.<br>
- Customers with short tenure have higher churn risk.<br>
- Electronic check payment method customers churn more.<br>

---

## 🚀 Business Applications

- Customer retention strategy<br>
- Targeted marketing campaigns<br>
- Discount offers for high-risk customers<br>
- Personalized subscription plans<br>
- Churn risk dashboard for business analysts<br>

---

## 📌 How to Run the Project

1. Install required libraries:<br>
- pip install pandas numpy matplotlib seaborn scikit-learn xgboost<br>

2. Place dataset file:<br>
- Telco_customer_churn.xlsx<br>

3. Run the notebook:<br>

---

## 📊 Project Workflow Summary

1. Data Loading  <br>
2. Data Understanding  <br>
3. Data Cleaning  <br>
4. EDA  <br>
5.Train-Test Split <br>  
6.Encoding & Scaling <br>   
7. Model Training  <br>
8. Evaluation  <br>
9. Performance Comparison  <br>

---

## 👤 Author

**Abbu Talib Ansari**<br>
Aspiring Data Scientist | AI & ML Enthusiast  <br>
GitHub:https://github.com/talibansari1914

---

⭐ If you found this project helpful, consider improving it further by:
- Hyperparameter tuning
- SMOTE for imbalance handling
- Cross-validation
- Model deployment using Flask or FastAPI



