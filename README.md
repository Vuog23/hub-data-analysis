<div align="center">

# 📊 HUB Data Analysis Projects

### *Ho Chi Minh City University of Banking*

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> A collection of student data analysis projects from **HUB (Trường Đại học Ngân hàng TP. Hồ Chí Minh)**, covering Vietnamese stock market analysis, HR/salary modeling, global retail market insights, and survey-based behavioral research — all powered by Python and machine learning.

</div>

---

## 📁 Table of Contents

- [Overview](#-overview)
- [Projects](#-projects)
  - [HUB — Vietnamese Stock: CMM (Camimex)](#hub--vietnamese-stock-cmm-camimex)
  - [HUB1 — HR &amp; Salary Analysis](#hub1--hr--salary-analysis)
  - [HUB2 — Vietnamese Stock: HTG (Hòa Thọ Textile)](#hub2--vietnamese-stock-htg-hòa-thọ-textile)
  - [HUB3 — Survey Data: Service Quality &amp; Behavioral Intent](#hub3--survey-data-service-quality--behavioral-intent)
  - [HUB4 — Vietnamese Stock: WCS (Bến xe Miền Tây)](#hub4--vietnamese-stock-wcs-bến-xe-miền-tây)
  - [HUB5 — Global Superstore: Indonesia Market](#hub5--global-superstore-indonesia-market)
  - [HUB6 — Global Superstore: Turkey Market](#hub6--global-superstore-turkey-market)
  - [HUB7 — Vietnamese Stock: PAN (Tập đoàn PAN)](#hub7--vietnamese-stock-pan-tập-đoàn-pan)
  - [HUB8 — Employee HR Deep Dive](#hub8--employee-hr-deep-dive)
- [Tech Stack](#-tech-stack)
- [Quick Start](#-quick-start)
- [Project Summary Table](#-project-summary-table)

---

## 🌟 Overview

This repository contains **9 independent data analysis projects** developed by students of **Ho Chi Minh City University of Banking (HUB)**. Each project follows a complete data science pipeline:

```
Data Collection → Cleaning → Exploratory Analysis → Modeling → Evaluation → Insights
```

**Topics covered:**

- 📈 **Vietnamese Stock Market** — technical analysis and price prediction on HOSE/HNX listed companies
- 👥 **Human Resources** — salary modeling, demographic analysis, and employee clustering
- 🛒 **Global Retail** — market-level profitability analysis (Indonesia & Turkey)
- 📋 **Survey Research** — Likert-scale behavioral data with classification and clustering

---

## 🗂 Projects

---

### HUB — Vietnamese Stock: CMM (Camimex)

> **File:** [`HUB/vnstock_company_analysis.ipynb`](HUB/vnstock_company_analysis.ipynb)

**Dataset:** 1,155 companies listed on HOSE/HNX — focused on **CMM (Camimex Group)** stock data (Aug–Sep 2023, 41 transactions).

| Metric                | Value                               |
| --------------------- | ----------------------------------- |
| Average Close Price   | 7,126.83 VND                        |
| Price Range           | 6,100 – 7,700 VND                  |
| Model                 | Linear Regression (Volume → Price) |
| Predictions Generated | 10 future price points              |

**Techniques:** Exploratory Data Analysis · Linear Regression · Price Visualization

---

### HUB1 — HR & Salary Analysis

> **File:** [`HUB1/job_analysis.ipynb`](HUB1/job_analysis.ipynb)

**Dataset:** 10,000 employee records — Name, Birthday, Gender, Hometown, Job Type, Salary, Marital Status (9,996 usable after cleaning).

| Metric                       | Value                                 |
| ---------------------------- | ------------------------------------- |
| Ridge Regression R²         | **99.66%**                      |
| Logistic Regression Accuracy | 61.5%                                 |
| K-Means Clusters             | 3 groups                              |
| Savings Packages Modeled     | 3 (flexible / short-term / long-term) |

**Techniques:** Data Cleaning · Ridge Regression · GridSearchCV · Logistic Regression · K-Means Clustering · Interest Rate Calculation

---

### HUB2 — Vietnamese Stock: HTG (Hòa Thọ Textile)

> **File:** [`HUB2/vnstock_company_analysis.ipynb`](HUB2/vnstock_company_analysis.ipynb)

**Dataset:** HOSE/HNX listing — focused on **HTG (Hòa Thọ Textile)** stock (Aug–Sep 2023, 42 transactions).

| Metric              | Value                               |
| ------------------- | ----------------------------------- |
| Average Close Price | 28,880.95 VND                       |
| Price Range         | 26,700 – 32,800 VND                |
| Prediction Range    | 28,427 – 30,588 VND                |
| Model               | Linear Regression (Volume → Close) |

**Techniques:** Technical Analysis · Volume Distribution · Linear Regression

---

### HUB3 — Survey Data: Service Quality & Behavioral Intent

> **File:** [`HUB3/linear_regression_kmeans.ipynb`](HUB3/linear_regression_kmeans.ipynb)

**Dataset:** Questionnaire survey with Likert-scale (1–5) responses across Service Quality (SQ1–SQ8), Satisfaction (SAT1–SAT2), Attitude (ATT1–ATT2), and Behavioral Intention (BI1–BI2) dimensions.

| Metric                       | Value |
| ---------------------------- | ----- |
| Linear Regression R²        | 0.497 |
| RMSE                         | 0.872 |
| Logistic Regression Accuracy | 61.5% |
| Silhouette Score (k=3)       | 0.163 |

**Techniques:** Linear Regression · Logistic Regression · K-Means Clustering · PCA Visualization · Confusion Matrix

---

### HUB4 — Vietnamese Stock: WCS (Bến xe Miền Tây)

> **Files:** [`HUB4/vnstock_company_analysis.ipynb`](HUB4/vnstock_company_analysis.ipynb) · [`HUB4/evidence.pdf`](HUB4/evidence.pdf)

**Dataset:** HOSE/HNX listing — focused on **WCS** stock (Jul–Sep 2023, 36 transactions). Highest-priced stock in the collection.

| Metric                    | Value                    |
| ------------------------- | ------------------------ |
| Average Close Price       | 174,619 VND              |
| Price Range               | 162,000 – 180,000 VND   |
| Training R²              | **96.05%**         |
| Test R² (5 future dates) | **99%**            |
| K-Means Clusters          | 3 (outlier day detected) |

**Techniques:** Multi-variable Linear Regression · Volume Threshold Analysis · K-Means Clustering · Color-coded Visualization

---

### HUB5 — Global Superstore: Indonesia Market

> **File:** [`HUB5/global_superstore_analysis.ipynb`](HUB5/global_superstore_analysis.ipynb)

**Dataset:** Global Superstore dataset (51,290 records) — filtered to **Indonesia** (1,390 records, 2.71% of total). Fields include Order ID, Ship Date, Customer, Product Category, Sales, Profit, Shipping Cost.

| Metric               | Value                          |
| -------------------- | ------------------------------ |
| Total Customers      | 469                            |
| Total Products       | 1,003                          |
| Total Sales          | 404,887.58                     |
| Total Profit         | ✅**+15,608.72**         |
| Top Category         | Technology (profit: 15,291.37) |
| Loss-making Category | Furniture (-1,377.12)          |
| Peak Sales Month     | June (60,315)                  |

**Techniques:** EDA · Category & Segment Analysis · Time Series Trend · Geographic Breakdown

---

### HUB6 — Global Superstore: Turkey Market

> **File:** [`HUB6/global_superstore_analysis.ipynb`](HUB6/global_superstore_analysis.ipynb)

**Dataset:** Global Superstore dataset — filtered to **Turkey** (1,378 records, 2.69% of total).

| Metric                 | Value                                  |
| ---------------------- | -------------------------------------- |
| Total Customers        | 463                                    |
| Total Sales            | 108,507.90                             |
| Total Profit           | ❌**-98,447.28 (critical loss)** |
| Furniture Margin       | -87.34%                                |
| Office Supplies Margin | -87.60%                                |
| Technology Margin      | -91.62%                                |

> ⚠️ **Key Finding:** All three product categories are operating at a loss in Turkey. The analysis recommends an urgent review of pricing strategy, cost structure, and shipping optimization.

**Techniques:** Market Profitability Analysis · Segment Breakdown · State-level Analysis · Business Recommendations

---

### HUB7 — Vietnamese Stock: PAN (Tập đoàn PAN)

> **File:** [`HUB7/vnstock_company_analysis.ipynb`](HUB7/vnstock_company_analysis.ipynb)

**Dataset:** HOSE/HNX listing — focused on **PAN Group** stock (Aug–Sep 2023, 42 transactions).

| Metric              | Value                                 |
| ------------------- | ------------------------------------- |
| Average Close Price | 22,075 VND                            |
| Price Range         | 20,100 – 23,600 VND                  |
| Prediction Range    | 21,849 – 22,356 VND                  |
| Visualizations      | 4-panel price chart + volume bar plot |

**Techniques:** Technical Analysis · Volume Analysis · Linear Regression · Multi-panel Visualization

---

### HUB8 — Employee HR Deep Dive

> **Files:** [`HUB8/employee_analysis.ipynb`](HUB8/employee_analysis.ipynb) · [`HUB8/employee_sample_data.csv`](HUB8/employee_sample_data.csv) · [`HUB8/employee_processed.csv`](HUB8/employee_processed.csv)

**Dataset:** 1,213 employees — Job Title, Department, Gender, Age, Hire/Exit Dates, Annual Salary, Bonus %, Location. Most comprehensive HR dataset in the collection.

| Metric                | Value                 |
| --------------------- | --------------------- |
| Employees Analyzed    | 1,213                 |
| Company Avg. Salary   | $110,005              |
| Salary Prediction R² | **93.0%**       |
| Largest Department    | IT (347 employees)    |
| Gender Split          | Female 632 / Male 581 |

**Top Salary Drivers (from regression coefficients):**

| Job Title      | Salary Premium |
| -------------- | -------------- |
| Vice President | +$179,000      |
| Director       | +$114,000      |
| Sr. Manager    | +$96,000       |

**K-Means Clusters (k=3):**

| Cluster | Avg Age | Avg Salary | Profile              |
| ------- | ------- | ---------- | -------------------- |
| 0       | 54.7    | $86,000    | Senior, moderate pay |
| 1       | 40.4    | $186,500   | High earners         |
| 2       | 36.1    | $71,700    | Young, entry-level   |

**Techniques:** Feature Engineering · Descriptive Statistics · Linear Regression · K-Means Clustering · StandardScaler · Train-Test Split

---

## 🛠 Tech Stack

| Category                    | Tools                                                                              |
| --------------------------- | ---------------------------------------------------------------------------------- |
| **Language**          | Python 3.10+                                                                       |
| **Environment**       | Jupyter Notebook                                                                   |
| **Data Manipulation** | `pandas`, `numpy`                                                              |
| **Visualization**     | `matplotlib`, `seaborn`                                                        |
| **Machine Learning**  | `scikit-learn` — Linear/Ridge/Logistic Regression, K-Means, PCA, GridSearchCV   |
| **Data Sources**      | `vnstock` (Vietnamese stock data), Global Superstore dataset, Custom HR datasets |

---

## 🚀 Quick Start

**1. Clone the repository**

```bash
git clone https://github.com/Vuog23/HUB.git
cd HUB
```

**2. Install dependencies**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter vnstock
```

**3. Launch Jupyter**

```bash
jupyter notebook
```

**4. Open any project folder** and run the `.ipynb` notebook of your choice.

---

## 📊 Project Summary Table

| Project    | Domain           | Dataset Size  | Key Model            | Best Score            |
| ---------- | ---------------- | ------------- | -------------------- | --------------------- |
| [HUB](HUB/)   | 🇻🇳 Stock (CMM) | 41 records    | Linear Regression    | Price prediction ✅   |
| [HUB1](HUB1/) | 👥 HR / Salary   | 9,996 records | Ridge + K-Means      | R² =**99.66%** |
| [HUB2](HUB2/) | 🇻🇳 Stock (HTG) | 42 records    | Linear Regression    | Price prediction ✅   |
| [HUB3](HUB3/) | 📋 Survey        | ~77 records   | Logistic + K-Means   | Acc = 61.5%           |
| [HUB4](HUB4/) | 🇻🇳 Stock (WCS) | 36 records    | Multi-var Regression | R² =**99%**    |
| [HUB5](HUB5/) | 🛒 Retail (ID)   | 1,390 records | EDA                  | Profit: +15,608       |
| [HUB6](HUB6/) | 🛒 Retail (TR)   | 1,378 records | Market Analysis      | Loss: -98,447 ⚠️    |
| [HUB7](HUB7/) | 🇻🇳 Stock (PAN) | 42 records    | Linear Regression    | Price prediction ✅   |
| [HUB8](HUB8/) | 👥 HR Deep Dive  | 1,213 records | Linear + K-Means     | R² =**93%**    |
