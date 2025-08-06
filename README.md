# 🛒 Walmart Case Study – Sales & Customer Insights

📄 [Download Full Report (PDF)](./Walmart_Case_Study.pdf)  
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

## 🛠 Tools & Technologies Used

- **Python**
- **Pandas**, **NumPy** – data cleaning and manipulation
- **Matplotlib**, **Seaborn** – data visualization
- **Jupyter Notebook**
- *(Optional)* Tableau/Power BI – dashboard (if added later)

---

## 📸 Sample Visualizations

```markdown
![Revenue by Branch](images/revenue_by_branch.png)  
![Top Product Lines](images/top_product_lines.png)  
![Customer Rating Distribution](images/customer_ratings.png)  
![Sales by Time](images/sales_by_time.png)
