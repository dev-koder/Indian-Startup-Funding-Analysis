# 🌟 Indian Startup Funding Analysis (2015–2020)
### *A Data Analytics Mini-Project using Python*

--- 

## 📌 1. Project Objective
The goal of this project is to deeply analyze the **Indian Startup Funding ecosystem** from 2015–2020 and extract meaningful insights using:

- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Statistical Testing  
- Machine Learning (Clustering)

This project answers questions like:
- Which cities attract the highest funding?
- Which industries dominate?
- Does location influence funding?
- Can startups be grouped based on funding behavior?

---

## 📂 Project Structure
```
📁 Indian-Startup-Funding-Analysis/
│
├── 📄 DevKushwaha_240616.ipynb      # Jupyter Notebook
├── 📄 README.md                     # This File
├── 📁 data/
│      └── startup_funding.csv       # Dataset (if allowed)
└── 📁 assets/
       └── images/                   # Plots and charts
```

---

## 2. Dataset Description
**Dataset:** Indian Startup Funding  
**Source:** Kaggle  
**Years:** 2015–2020  

**Columns:** Startup Name, Industry Vertical, City, Investors, Funding Amount (USD), Investment Type, Date.

---

## 3. Methods Used

### a) Data Cleaning & Preparation
- Removed irrelevant/duplicate columns  
- Fixed missing values  
- Cleaned text fields  
- Numeric conversion of funding  
- Log transformation  
- Extracted year  
- Dropped unnecessary columns  

---

### b) Exploratory Data Analysis (EDA)
- Funding distribution (skewed)
- Industry & city-level analysis  
- Yearly trends  
- Correlation heatmap  

---

### c) Statistical Analysis – Two-Sample T-Test
**Question:** Is funding in Bengaluru significantly different from Delhi?

✔ p-value = **0.024** → Significant difference found.

---

### d) Machine Learning – K-Means Clustering
**Features:** Log_Amount, Year  
**Optimal Clusters:** 3  

- Cluster 0 → High funding in recent years  
- Cluster 1 → Low funding across all years  
- Cluster 2 → Medium funding in early years  

---

## 4. Key Insights
- Funding is uneven  
- Bengaluru dominates  
- Tech, Ecommerce, Internet sectors lead  
- Funding rose sharply after 2017  
- Three natural startup groups exist  

---

## 5. Conclusion
This project provides a complete picture of India's startup funding ecosystem and shows how funding behavior evolved between 2015–2020 using **Data Cleaning, EDA, ML, and Statistics**.

---

## Created by Dev Kushwaha with Python
