# 🏥 Hospital Readmission Risk Prediction

This project predicts whether a patient is likely to be readmitted to the hospital within 30 days of discharge using patient and treatment data.

## 📌 Objective

To build a logistic regression model that identifies patients at risk of early readmission. This can help hospitals reduce costs and improve care.

## 📂 Project Structure


## 🧪 Steps Performed

- Data cleaning and target variable creation
- Exploratory Data Analysis (EDA)
- Feature selection and encoding
- Logistic Regression model
- Model evaluation (Confusion Matrix, ROC Curve)

## 📊 Model Performance

| Metric            | Logistic Regression | Random Forest     |
|------------------|---------------------|--------------------|
| **Accuracy**      | 88.84%              | 88.07%             |
| **AUC Score**     | 56.10%              | 57.71%             |

🧪 Random Forest showed slightly better discriminatory power (AUC), while Logistic Regression had a marginally better accuracy. Both models were evaluated with proper validation.

- **Toolkits Used**: `pandas`, `seaborn`, `matplotlib`, `sklearn`

## 🔗 Visual Samples

![Confusion Matrix](Visuals/confusion_matrix.png)
![ROC Curve](Visuals/roc_curve.png)

---

## 📎 Author

Milan Suthar  
MSc Statistics & Computing | Data Analyst  
[LinkedIn Profile](https://www.linkedin.com/in/milan-kumar-suthar-3b95b0281/)
