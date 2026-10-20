# 🛍️ Shopping Trends — Purchase Behavior Analysis

> Analysis of 3,900 e-commerce transactions to identify growth levers and optimize the marketing strategy.

---

## 📌 Context & Problem Statement

An e-commerce company wants to understand why its promotional campaigns fail to increase revenue despite an average 25% discount. The objective is to identify 3 key insights and formulate actionable recommendations.

---

## 📊 Data & Methodology

* **Source:** Kaggle — Shopping Trends dataset
* **Volume:** 3,900 transactions over 12 months
* **Tools Used:**
* **PostgreSQL (SQL):** Data extraction, aggregations, and advanced Window Functions.
* **Excel:** Pivot tables, data cleaning, and data visualization.
* **PowerPoint:** Business presentation and storytelling.

---

## 💡 Key Insights

### 1️⃣ Promotions do not increase basket size
**Observation:** 43% of orders use a promo code. The average basket with a promo ($59.28) is lower than without ($60.13).
**Impact:** Promotions cannibalize margin without generating extra value, costing an estimated **5 to 8% of annual margin**.
**Recommendation:** Stop general promotions. Reserve them exclusively for new customer acquisition (A/B testing recommended).

### 2️⃣ Revenue is concentrated in 2 categories
**Observation:** Clothing and Accessories together account for **76% of total revenue** ($178,464 out of $233,000).
**Impact:** A 10% drop in Clothing would cost **$10,426** in revenue.
**Recommendation:** Secure stock and marketing budgets for these two categories first.

### 3️⃣ The "Young Female" segment is underexploited
**Observation:** Adult and Senior make up 77% of revenue. However, young women (Young Female) have the highest average basket in the dataset (**$61.82**), despite a low purchase volume.
**Impact:** Doubling their purchase volume would generate **+$17,000 in revenue**.
**Recommendation:** Launch a targeted premium acquisition campaign for young women.

---

## 📂 Project Structure

* `data/` : Raw dataset (CSV)
* `sql/` : SQL queries used for extraction and analysis
* `visuals/` : Charts exported from Excel (PNG)
* `presentation/` : Final PowerPoint presentation (PDF)

---

## 📬 Contact

**Mira Imanantsoa** — Data Analyst
* 📧 Email: imanantsoamirasoa@gmail.com
* 💼 LinkedIn: github.com/mira-analyzes
* 🐙 GitHub: (coming soon)

E-commerce Transaction Analysis &amp; Business Insights
