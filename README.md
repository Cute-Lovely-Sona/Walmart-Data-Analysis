# 🛒 Walmart Case Study – Sales & Customer Insights

📄 [Download Full Report (PDF)](https://drive.google.com/file/d/1vW_fF0CVlI5rf4UBvqD3ZvPVBrggSaeK/view?usp=sharing)  
📊 Data Analysis | 🎯 Business Insights | 📌 EDA + Strategy

---

## 📂 Dataset Structure

The dataset consists of transactional records of three Walmart branches, capturing sales and customer behavior data.

| Column               | Description                                          |
|----------------------|------------------------------------------------------|
| Invoice ID           | Unique identifier for each transaction               |
| Branch               | Branch where the sale took place (A, B, or C)        |
| City                 | City of the branch                                   |
| Customer Type        | Member or Normal                                     |
| Gender               | Gender of the customer                               |
| Product Line         | Product category (e.g., Food, Electronics)           |
| Unit Price           | Price per item                                       |
| Quantity             | Number of items sold                                 |
| Tax, Total           | Calculated per transaction                           |
| Date, Time           | Transaction timestamp                                |
| Payment              | Payment method used (Cash, Card, E-wallet)           |
| COGS                 | Cost of goods sold                                   |
| Gross Income         | Profit earned                                        |
| Rating               | Customer rating (out of 10)                          |

---

## 🚀 Project Overview

This project analyzes Walmart's transactional sales data across its branches to extract insights into product performance, customer behavior, and operational efficiency. The case study involves cleaning, analyzing, and visualizing the data to help stakeholders make data-driven decisions. 

Analyzed **550,068 customer transactions** from Walmart, focusing on **demographics** and **purchase behavior** across gender, age, marital status, and product categories.

---

## 🧠 Business Objectives

- Which branch is generating the highest revenue and customer satisfaction?
- Which product lines are most profitable?
- What payment methods are preferred?
- When are the busiest times and days?
- How does customer behavior influence gross income and ratings?

---

## 📊 Key Business Insights

### 🏬 Branch Performance
- **Branch C** is the **top performer** in gross income, quantity sold, and average customer rating.
- **Branch B** has the **lowest revenue and rating**, indicating areas for improvement.
- **Branch A** shows balanced performance with strong product-specific sales.

### 📦 Product Line Insights
- **Food and Beverages** has the **highest quantity sold**.
- **Electronic Accessories** drives the **most gross income** despite lower volume.
- **Home and Lifestyle** shows lower profitability.

### 💳 Payment Method Trends
- **E-wallet** and **Credit Cards** dominate across all branches.
- **Branch C** has the **highest use of digital payments**.

### ⭐ Customer Ratings
- Average customer rating is **~7.0/10** across branches.
- **Branch C** leads in customer satisfaction.
- Higher total purchases can slightly reduce rating (possibly due to longer wait times).

### ⏰ Temporal Insights
- **Evenings (5 PM – 8 PM)** are the busiest.
- **Weekends (Friday–Sunday)** see the highest traffic and sales.

---

## 📈 Metrics Snapshot by Branch

| Branch | Avg Rating | Gross Income | Top Product Line     | Sales Peak |
|--------|------------|---------------|-----------------------|-------------|
| A      | 6.9        | Medium        | Health and Beauty     | Friday      |
| B      | 6.8        | Low           | Food and Beverages    | Saturday    |
| C      | 7.2        | High          | Electronic Accessories| Sunday      |

---

## 💼 Strategic Recommendations

- 📦 Promote high-margin product lines via combo or bundle offers.
- 🧍‍♂️ Improve staff efficiency and customer experience in **Branch B**.
- 💳 Offer discounts on **digital payment methods** to increase usage.
- 🕒 Schedule promotions around **evenings and weekends**.
- 📊 Use product-specific insights to **adjust inventory per branch**.

---

### 📌 Key Metrics

- **Spending Patterns** analyzed by:
  - Gender
  - Age Groups
  - Marital Status
  - Product Categories

---

### 👨‍👩‍👧 Gender-Based Insights

- 🧑‍🤝‍🧑 **75%** of customers were **male**
- 🧔 Males **spent more** than females overall
- 📉 Female spending was **~20% lower** than male spending

---

### 🎯 Age Group Insights

- 🧑 **26–35 age group** accounted for **~40%** of all purchases (📈 highest share)
- 🧓 **36–45 age group** followed with **~20%**
  
> ✅ *Young adults are Walmart's most active customer base.*

---

### 📦 Product Category Preferences

- 📌 **Category 5** was the most purchased
- Followed by **Category 1** and **Category 8**

> ✅ *Optimize inventory and marketing around top categories.*

---

### 📊 Statistical Insights

- 💍 **Married customers** spent **8.8% less** than unmarried customers
- 📉 Spending by marital status shows significant behavior differences

---

### 📏 Confidence Intervals

- 🧔 Male Spending: **₹895,617 to ₹955,070**
- 👩 Female Spending: **₹673,254 to ₹750,794**

> ✅ *Statistically significant difference in average spending by gender.*

---

### 📈 Actionable Business Insights

- 🎯 Focus marketing efforts on **26–35 age group**
- 🛍 Promote **top product categories (5, 1, 8)** through seasonal campaigns
- 👫 Adjust offers for **married vs unmarried segments**
- 🧠 Explore gender-based personalization in ad targeting

---

### 🛠 Tech Stack Used

- **Python**:
  - `Pandas` – Data Cleaning & Manipulation
  - `Matplotlib` & `Seaborn` – Data Visualization
  - `SciPy` – Statistical Testing
  - `Colab Notebook` for EDA Workflow

---

## 📸 Sample Visualizations

```markdown
![📊 Average Spending by Marital Status with 95% Confidence Intervals]([images/revenue_by_branch.png](https://drive.google.com/file/d/1Q2HjGmerQVKMHrnLsRA4XkIoW85IqS9y/view?usp=sharing)  
![📦 Outlier Removal in Product Category Data (Before & After Clipping)]([images/top_product_lines.png](https://drive.google.com/file/d/1mTg2jNpnrppUCbeGD0olW-d0c2sWOzFE/view?usp=sharing)  
![📈 KDE Plot of Total Purchase Amount by Marital Status]([images/customer_ratings.png)](https://drive.google.com/file/d/14jwxtUuaioXhZeMugizh8pk9ySvaySab/view?usp=sharing)  
![🔍 Confidence Interval Comparison by Gender and Sample Size]([images/sales_by_time.png)](https://drive.google.com/file/d/1Ht2ecYNo9g3-blFZuXj2fDMY85Djlr9P/view?usp=sharing)
![🧑‍🤝‍🧑 Spending Distribution by Gender Across Age Groups](https://drive.google.com/file/d/100qBREDYoCdZYPa-C7N1mMfrxFuqaDRI/view?usp=sharing
![📊 Total Purchase Amount by Age Group and Marital Status]([images/sales_by_time.png)](https://drive.google.com/file/d/1Q2HjGmerQVKMHrnLsRA4XkIoW85IqS9y/view?usp=sharing)
