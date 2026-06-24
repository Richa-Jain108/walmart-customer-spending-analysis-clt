# 🛒 Walmart Customer Spending Analysis 

### End-to-End Customer Purchase Behavior Analysis Using Exploratory Data Analysis (EDA), Confidence Intervals, and the Central Limit Theorem (CLT)

This project analyzes Walmart's Black Friday transaction data to understand customer spending behavior across gender, age groups, marital status, city categories, and other demographic factors. Using statistical inference techniques such as Confidence Intervals and the Central Limit Theorem (CLT), the analysis evaluates whether observed spending differences can be generalized to Walmart's broader customer population.

The objective is to transform transactional data into actionable business insights that can support customer targeting, inventory planning, marketing strategy, and revenue optimization.

---

## 📄 Project Deliverables

| Resource                                                                                                                                                            | Description                                                                                                           |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| 📓 **[Google Colab Notebook](https://github.com/Richa-Jain108/walmart-customer-spending-analysis-clt/blob/main/notebooks/walmart-customer-spending-analysis-clt.ipynb)** | Complete analysis, code implementation, visualizations, statistical inference, business insights, and recommendations |
| 📑 **[Analysis Report (PDF)](https://github.com/Richa-Jain108/walmart-customer-spending-analysis-clt/blob/main/reports/Walmart%20Analysis%20Report.pdf)**           | Detailed business report containing findings, confidence interval analysis, CLT implementation, and recommendations   |
| 📊 **[Dataset](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/293/original/walmart_data.csv?1641285094)**                                       | Walmart Black Friday transaction dataset used for analysis                                                            |

---

## 📌 Business Problem

### About Walmart

Walmart is one of the world's largest retail corporations, serving millions of customers through its network of supercenters, discount stores, and e-commerce channels.

Understanding customer spending patterns is critical for:

* Personalized marketing
* Customer segmentation
* Inventory optimization
* Promotional campaign planning
* Revenue growth

The Walmart management team wants to understand:

* Do male and female customers spend differently during Black Friday?
* Can spending patterns observed in the sample be generalized to the population?
* Are spending behaviors influenced by age, marital status, or city category?
* Which customer segments drive the highest purchase volume?
* How can Walmart use these insights to improve business outcomes?

---

## 🎯 Project Objectives

This analysis focuses on answering the following business questions:

### Customer Spending Analysis

* Do women spend more on Black Friday than men?
* What is the average purchase amount for different customer segments?
* Are observed spending differences statistically significant?

### Statistical Inference

* Estimate population spending behavior using sample data.
* Construct Confidence Intervals for customer spending.
* Apply the Central Limit Theorem (CLT) across multiple sample sizes.
* Evaluate the reliability of spending estimates.

### Customer Segmentation

* Analyze spending patterns across age groups.
* Compare married vs unmarried customer behavior.
* Study city category and customer tenure effects.
* Identify high-value customer segments.

### Business Recommendations

* Develop targeted marketing strategies.
* Improve promotional planning.
* Optimize product assortment.
* Support data-driven decision making.

---

## 📊 Dataset Overview

The dataset contains transactional purchase information from Walmart's Black Friday sales event.

### Dataset Size

* **550,068 transactions**
* **5,891 unique customers**
* **3,631 unique products**

### Features

| Feature                    | Description                 |
| -------------------------- | --------------------------- |
| User_ID                    | Unique customer identifier  |
| Product_ID                 | Unique product identifier   |
| Gender                     | Customer gender             |
| Age                        | Age group                   |
| Occupation                 | Occupation category         |
| City_Category              | City classification (A/B/C) |
| Stay_In_Current_City_Years | Years in current city       |
| Marital_Status             | Married / Unmarried         |
| Product_Category           | Product category            |
| Purchase                   | Purchase amount             |

---

## 🛠️ Tools & Technologies

### Programming

* Python
* Jupyter Notebook

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

### Statistical Techniques

* Exploratory Data Analysis (EDA)
* Outlier Detection
* Confidence Intervals
* Central Limit Theorem (CLT)
* Sampling Distribution Analysis
* Statistical Inference

---

## 🔍 Analytical Approach

### 1. Data Understanding & Cleaning

* Dataset structure review
* Data type validation
* Missing value analysis
* Outlier detection
* Data transformation

### 2. Exploratory Data Analysis (EDA)

* Purchase distribution analysis
* Gender-based spending patterns
* Age group segmentation
* City category analysis
* Product category analysis
* Customer behavior exploration

### 3. Statistical Inference

* Sampling strategy implementation
* Confidence Interval estimation
* Population mean estimation
* CLT validation across multiple sample sizes
* Distribution comparison

### 4. Business Insight Generation

* Customer segment evaluation
* Revenue-driving demographics
* Spending behavior analysis
* Strategic recommendation development

---

## 📈 Key Findings

### Customer Demographics

* Male customers account for approximately **75%** of all transactions.
* The **26–35 age group** represents the largest customer segment.
* Most customers belong to City Category **B**.

### Spending Behavior

* Average purchase amount: **$9,264**
* Median purchase amount: **$8,047**
* Spending distribution is right-skewed, indicating the presence of high-value purchases.

### Product Trends

* Product Categories **5, 1, and 8** dominate transaction volume.
* These categories consistently perform well across age groups.

### Statistical Inference Results

* Confidence Intervals reveal measurable differences between customer segments.
* Sampling distributions become increasingly normal as sample size grows, validating the Central Limit Theorem.
* Population spending estimates become more stable with larger sample sizes.

### Customer Segmentation Insights

* Gender influences purchase behavior.
* Age has a stronger impact on spending patterns than marital status.
* Certain customer segments demonstrate consistently higher spending potential.

---

## 💡 Business Recommendations

### 1. Target High-Value Customer Segments

Focus marketing efforts on age groups and demographics that consistently generate higher purchase amounts.

### 2. Optimize Inventory Planning

Maintain stronger inventory levels for Product Categories 5, 1, and 8, which contribute significantly to overall sales.

### 3. Implement Personalized Promotions

Use demographic segmentation to deliver more relevant offers and improve campaign performance.

### 4. Improve Customer Retention

Develop loyalty initiatives tailored to high-value customer segments identified during the analysis.

### 5. Leverage Statistical Monitoring

Use confidence intervals and sampling-based monitoring techniques to evaluate future campaign performance and customer behavior changes.

---

## 📂 Repository Structure

```text
walmart-customer-spending-analysis-clt/
│
├── data/
│   └── walmart_data.txt
│
├── notebooks/
│   └── walmart-customer-spending-analysis-clt.ipynb
│
├── reports/
│   └── Walmart Analysis Report.pdf
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Deliverables

✔️ Data Cleaning & Preprocessing

✔️ Exploratory Data Analysis (EDA)

✔️ Customer Segmentation Analysis

✔️ Confidence Interval Estimation

✔️ Central Limit Theorem (CLT) Validation

✔️ Statistical Inference

✔️ Business Insights

✔️ Strategic Recommendations

✔️ Jupyter Notebook

✔️ Executive Report

---

## 👤 Author

### Richa Jain

Data Analyst specializing in Business Analytics, Statistical Analysis, Data Visualization, and Data-Driven Decision Making.

Passionate about transforming raw data into actionable business insights that drive measurable business outcomes.
