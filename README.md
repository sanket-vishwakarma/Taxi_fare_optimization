# 🚕 Maximizing Taxi Driver Revenue Through Payment Type Analysis

## 📌 Table of Contents
- <a href="#overview">Overview & Goal</a>
- <a href="#problem-statement--questions">Problem Statement & Research Questions</a>
- <a href="#dataset-description">Dataset Description</a>
- <a href="#methodology">Methodology: Analysis & Testing</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA) & Key Findings</a>
- <a href="#hypothesis-testing">Hypothesis Testing</a>
- <a href="#driver-revenue-recommendations">Driver Revenue Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<a class="anchor" id="overview"></a>
## 🎯 Overview & Goal
This project focuses on the fast-paced taxi booking sector, where maximizing revenue is essential for long-term success and driver happiness. The goal is to use data-driven insights to maximize revenue streams for taxi drivers.

Specifically, the research aims to determine the relationship between payment type and fare amount to provide actionable recommendations.

---
<a id="problem-statement--questions"></a>
## ❓ Problem Statement & Research Questions
The core problem is optimizing revenue streams for taxi drivers. Our analysis addresses two key questions:

* **Primary Question:** Is there a relationship between the total fare amount and payment type ?
* **Secondary Question:** Can we convince customers towards payment methods that generate higher revenue for drivers, without negatively impacting the customer experience ?

---
<a id="dataset-description"></a>
## 📊 Dataset Description
The analysis was conducted using taxi trip data, focusing on the following key variables:

* `passenger_count`
* `payment_type` (Categorized as 'card' or 'cash') 
* `fare_amount` 
* `trip_distance` 
* `duration` 

---
<a id="methodology"></a>
## 💡 Methodology: Analysis & Testing
The project followed a two-step methodology:

1.  **Descriptive Analysis:** Statistical analysis was performed to summarize key aspects of the data, focusing on fare amounts and payment types.
2.  **Hypothesis Testing:** A **T-test** was conducted to evaluate the relationship between payment type and fare amount, testing the hypothesis that different payment methods influence fare amounts.

---
<a id="exploratory-data-analysis-eda"></a>
## 📈 Exploratory Data Analysis (EDA) & Key Findings

### Payment Preference
* Customers show a **strong preference for card payments**, which account for 67.3% of all transactions.
* Cash payments make up 32.7% of transactions.

### Fare and Distance Metrics
The data indicates that customers prefer to pay more with cards when they have a high fare amount and long trip distance.

| Metric | Payment Type | Mean | Standard Deviation |
| :--- | :--- | :--- | :--- |
| **Fare Amount** | Card  | **$13.1$**  | $5.84$ |
| **Fare Amount** | Cash  | $11.75$  | $5.61$  |
| **Trip Distance** | Card  | **$2.99$**  | $1.99$  |
| **Trip Distance** | Cash | $2.60$  | $1.91$ |

### Passenger Count Analysis
* Single-passenger rides (`passenger_count = 1`) comprise the largest proportion for both payment types.
* There is a noticeable decrease in transactions as the passenger count increases, suggesting large groups are less likely to use taxis or may opt for alternative payment methods.

---
<a id="hypothesis-testing"></a>
## 🔬 Hypothesis Testing
We conducted a T-test to confirm the statistical significance of the difference in average fare.

* **Null Hypothesis ($H_0$):** There is **no** difference in average fare between customers who use credit cards and customers who use cash.
* **Alternative Hypothesis ($H_A$):** There is a **significant difference** in average fare between customers who use credit cards and customers who use cash.

| Statistic | Value |
| :--- | :--- |
| **T-Statistic** | $165.5$  |
| **P-value** | $< 0.05$  |

**Conclusion:** With a P-value of less than 0.05, we **reject the null hypothesis**.This suggests there is indeed a **significant difference** in average fare between the two payment methods.

---
<a id="driver-revenue-recommendations"></a>
## 🌟 Driver Revenue Recommendations
To capitalize on the finding that card payments are associated with higher fares, the following actions are recommended:

* **Encourage Card Payments:** Encourage customers to pay with credit cards to capitalize on the potential for generating more revenue.
* **Implement Incentives:** Offer strategies such as incentives or discounts for credit card transactions to encourage customers to choose this payment method.
* **Enhance Convenience:** Provide seamless and secure credit card payment options to enhance customer convenience and encourage adoption of this preferred method.

---
<a id="author--contact"></a>
## 👤 Author & Contact
* Author - **Sanket Vishwakarma**  
Data Analyst  
📧 Email: sanketvishwakarma4103@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sanket-vishwakarma-9b26b7358/)
