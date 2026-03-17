# 📊 A/B Testing and Hypothesis Prioritization for an E-commerce Platform

## 🧠 Business Problem

An e-commerce company aimed to increase revenue by testing product and marketing hypotheses.  
The goal of this project was to prioritize these hypotheses and evaluate the impact of a product change through an A/B test.

---

## 📁 Dataset

The analysis is based on three datasets:

- **hypotheses_us.csv** → hypotheses with Reach, Impact, Confidence, and Effort  
- **orders_us.csv** → transaction data (revenue, users, groups)  
- **visits_us.csv** → daily visits per test group  

---

## ⚙️ Methodology

The analysis was conducted in the following steps:

1. Hypothesis prioritization using **ICE and RICE frameworks**
2. Data preprocessing and validation
3. Outlier detection and removal:
   - Users with more than **2 orders**
   - Orders above the **99th percentile (830.3)**
4. Exploratory data analysis:
   - Cumulative revenue
   - Conversion rate
   - Average order value
5. Statistical testing using the **Mann–Whitney U test**

---

## 📈 Key Findings

- ✅ **+19% increase in conversion rate (Group B)** *(statistically significant)*
- ❌ No significant difference in **average order value**
- 💰 Higher revenue driven by **conversion increase**
- 🔍 Results remained consistent after removing outliers

---

## 🚀 Business Recommendation

👉 **Stop the experiment and implement version B**

The tested variation increases the probability of purchase without affecting the average order value, resulting in higher total revenue.

---

## 🛠️ Tools

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- SciPy  