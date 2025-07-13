# 📊 Customer Churn Prediction using Logistic Regression

This project uses **Logistic Regression** to predict whether a customer will churn (leave the service) or not. It's a classic **binary classification** problem, solved using **Python**, **Pandas**, **Scikit-learn**, and **Jupyter Notebook**.

---

## 📌 Problem Statement

Many companies lose customers and revenue because they don’t predict who might leave. In this project, we use historical customer data to **train a model that can predict churn**, helping businesses take action.

---

## 📁 Dataset

We use the **Telco Customer Churn dataset**, which includes:

- `Gender`
- `Age`
- `Salary`
- `Country`
- `SubscriptionType`
- `Churned` (Target column: Yes/No)

✅ Null values are handled  
✅ Categorical variables are encoded  
✅ Data is scaled  
✅ Logistic Regression model is trained and evaluated

---

## 📦 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

---

## 🧠 ML Algorithm

### Logistic Regression

- Used for **binary classification**
- Predicts the probability of churn (1) or not churn (0)
- Easy to interpret and useful for linear decision boundaries

---

## 🛠️ Steps Followed

1. **Loaded and explored** the data
2. **Handled missing values**
3. **Encoded** categorical features using `pd.get_dummies`
4. **Feature scaling** using `StandardScaler`
5. **Train-Test Split** (80% train, 20% test)
6. **Model Training** using `LogisticRegression()`
7. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-Score)

---

## 📈 Results

- **Accuracy**: `78.82%`
- **Confusion Matrix**: [[915 118] [180 194]]

---

 **Classification Report**:

| Class (Churned) | Precision | Recall | F1-score | Support |
|------------------|-----------|--------|----------|---------|
| 0 (Not Churned)  | 0.84      | 0.89   | 0.86     | 1033    |
| 1 (Churned)      | 0.62      | 0.52   | 0.57     | 374     |
| **Accuracy**     |           |        | **0.7882** | 1407    |
| **Macro Avg**    | 0.73      | 0.70   | 0.71     |         |
| **Weighted Avg** | 0.79      | 0.79   | 0.78     |         |

---

## 📂 How to Run

1. Clone the repository
 ```bash
 git clone https://github.com/your-username/Customer-Churn-Prediction.git


