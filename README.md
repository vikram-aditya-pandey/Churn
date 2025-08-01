# 📊 Customer Churn Analysis

## 📌 Objective
Analyze telecom customer data to identify key factors driving customer churn and derive actionable business insights.

---

## 🔍 Key Correlations
Top features most positively correlated with churn:
- **InternetService_Fiber optic** (+0.31)
- **PaymentMethod_Electronic check** (+0.30)
- **MonthlyCharges** (~+0.19)
- **PaperlessBilling** (~+0.19)

---

## 🔀 Feature Interaction Insights

### 1. Monthly Charges × Paperless Billing
- Churn increases with higher monthly charges, especially for customers using paperless billing.
- 📌 *High-paying, digitally billed customers churn more — possibly due to reduced engagement or price sensitivity.*

### 2. Fiber Optic Internet × Electronic Check
- Customers using fiber optic and paying via electronic check churn at **53%**, the highest among all groups.
- 📌 *A mismatch between modern service and outdated payment may cause dissatisfaction.*

---

## ✅ Business Recommendations
| Focus Area | Recommendation |
|------------|----------------|
| High spenders with digital billing | Offer loyalty rewards or priority support |
| Fiber optic + manual payers | Promote digital/auto payment options |
| Electronic check users | Encourage transition to modern billing methods |

---

## 📁 Files
- `Customer Churn.csv` — dataset
- `Customer Churn.ipynb` — full EDA notebook with cleaning, visualization, and insights
