# 📊 Telco Customer Churn Analysis

This repository contains an in-depth analysis of customer churn behavior for a telecommunications company. The project explores what factors influence customers to discontinue their services and identifies strategies to improve retention.

---

## 🧠 Objective

The goal of this analysis is to understand **why customers leave** and to identify actionable insights that can help reduce churn.
The analysis uses data from **7,043 customers**, including demographic, account, and service-related features.

---

## 📁 Dataset Overview

* **Total Records:** 7,043
* **Total Features:** 21
* **Target Variable:** `Churn` (Yes/No)
* **Overall Churn Rate:** ~26.5%

### **Data Categories**

* **Demographics:** Gender, Senior Citizen, Partner, Dependents
* **Account Info:** Tenure, Contract Type, Billing, Payment Method
* **Services:** Phone, Internet, Security, Backup, Streaming, Tech Support

---

## 📈 Key Insights from Analysis

### 🧾 Contract Type and Retention

* **Month-to-Month contracts** account for ~55% of customers but **over 85% of churned users**.
* **Two-Year contracts** contribute to **less than 5%** of total churn.
  ➡️ Longer contracts significantly reduce churn — a two-year customer is nearly **20x less likely** to leave.

---

### 🌐 Internet and Security Services

* **Fiber Optic** users have the highest churn (**~42%**), while **DSL** users churn at only **18%**.
* Customers **without Online Security or Tech Support** are **50% more likely** to churn.
  ➡️ Bundling support and protection services helps retain high-value customers.

---

### 💳 Payment and Billing Behavior

* **Electronic Check** users form **34%** of customers but **58%** of churners.
* **Auto-pay methods** (bank or card) correlate with **<15% churn**.
* **Paperless Billing** customers churn at **33%**, versus **19%** for others.
  ➡️ Digital-first customers may be price-sensitive or less engaged.

---

### 💰 Monthly Charges and Tenure

* Customers paying **>$70/month** churn at **~40%**, while those under **$40** churn at **~12%**.
* **70% of churn** comes from customers with **tenure < 12 months**.
  ➡️ The **first year** is critical — early engagement drives long-term retention.

---

### 📞 Phone & Streaming Services

* Customers **without Phone Service** or **Streaming Options** show **~30% churn**, compared to **~20%** for bundled-service users.
  ➡️ Bundling entertainment and communication services increases satisfaction and retention.

---

## 🎨 Visualization Highlights

* Clear, consistent color palette: **Blue for “No Churn”** and **Orange for “Churn”**.
* Multi-panel count plots effectively show churn trends across categories.
* Clean labels, readable fonts, and white backgrounds enhance interpretability.
* Charts make key insights easy to spot — even for non-technical viewers.

---

## 🧩 Strategic Recommendations

### 🔹 Contract and Loyalty

* Incentivize customers to move from month-to-month to annual contracts.
* Offer loyalty programs or rewards for long-term subscribers.

### 🔹 Service Bundling

* Bundle online security, device protection, and streaming to increase perceived value.
* Target fiber-optic users with retention offers, as they face higher churn.

### 🔹 Pricing and Billing

* Review pricing for high-charge plans; communicate value-added benefits clearly.
* Promote auto-pay methods by offering small discounts or loyalty credits.

### 🔹 Customer Experience

* Improve onboarding for new users — especially in their **first 6 months**.
* Use proactive communication and support to reduce early churn.

---

## 🏁 Conclusion

This analysis demonstrates that **contract type, service bundling, and billing preferences** are the most powerful churn indicators.
Customers with **month-to-month contracts, high monthly charges, and minimal add-on services** represent the highest risk.

By addressing these areas through **targeted retention programs**, the company can potentially reduce churn by **8–12% annually**, leading to a measurable improvement in profitability and customer lifetime value.

---

## 📘 Project Files

* `Churn_Analysis.ipynb` → Full analysis notebook with data exploration and visualizations
* `Customer churn` → Dataset 
* `README.md` → Project overview and executive summary

---

## 🧑‍💻 Author

**[Priyanka Thapa]**
[GitHub Profile](https://github.com/Priyanka0722) 
[LinkedIn Profile](https://www.linkedin.com/.in/priyanka-thapa-799a862bb)  


⭐ *If you found this project insightful, please star this repository!*


