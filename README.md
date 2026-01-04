# 👨🏻‍💻Customer Behavior Data Analyst Portfolio Project
---

## ⚙️ Challenges & Solutions

### 1️⃣ Handling Incomplete & Inconsistent Data

**Challenge:**
The raw dataset contained missing values, particularly **37 null entries in the `Review Rating` column**, which could skew customer satisfaction analysis and dashboard KPIs.

**Solution:**
Used **Python (Pandas)** to perform **category-wise median imputation**, ensuring ratings remained realistic within each product segment. This preserved data integrity while avoiding bias introduced by global averages.

**Impact:**
Improved reliability of customer sentiment metrics and ensured accurate downstream visualizations in Power BI.

---

### 2️⃣ Creating Business-Ready Features from Raw Data

**Challenge:**
Raw attributes such as age and purchase timestamps were not directly useful for business analysis or segmentation.

**Solution:**
Performed **feature engineering in Python** to create:

* `age_group` → Enabled demographic revenue analysis
* `purchase_frequency_days` → Captured customer buying behavior
* Customer lifecycle labels (New / Returning / Loyal)

**Impact:**
Allowed deeper customer segmentation, retention analysis, and actionable insights for marketing strategy.

---

### 3️⃣ Ensuring Scalable & Structured Analysis

**Challenge:**
Analyzing complex customer behavior using flat files limited query flexibility and scalability.

**Solution:**
Loaded the cleaned dataset into a **PostgreSQL database**, enabling:

* Efficient multi-table joins
* Advanced aggregations
* Repeatable business queries using SQL

**Impact:**
Replicated an **industry-grade analytics workflow**, making the project closer to real-world data team environments.

---

### 4️⃣ Translating SQL Outputs into Executive Insights

**Challenge:**
Raw SQL results are often difficult for non-technical stakeholders to interpret.

**Solution:**
Integrated SQL outputs into **Power BI dashboards** with:

* Clear KPIs
* Interactive filters (Age Group, Category, Subscription)
* Visual storytelling for revenue, retention, and product performance

**Impact:**
Converted technical findings into **decision-ready insights** suitable for leadership and business teams.

---

### 5️⃣ Aligning Analysis with Business Objectives

**Challenge:**
Avoiding “analysis without impact” and ensuring insights aligned with revenue and retention goals.

**Solution:**
Framed insights around:

* Subscription conversion opportunities
* Loyalty uplift strategies
* Shipping optimization
* Review score improvement

**Impact:**
Delivered **data-driven recommendations** directly tied to revenue growth, customer retention, and customer experience.

---

### ✅ Tools & Technologies Used

* **Python:** Pandas, NumPy (Data Cleaning & Feature Engineering)
* **SQL:** PostgreSQL (Business Analysis)
* **Power BI:** KPI Dashboards & Visual Storytelling

---

<img width="1287" height="725" alt="Screenshot 2026-01-04 211027" src="https://github.com/user-attachments/assets/23d8050a-c376-4d70-83b0-773a14153aae" />

