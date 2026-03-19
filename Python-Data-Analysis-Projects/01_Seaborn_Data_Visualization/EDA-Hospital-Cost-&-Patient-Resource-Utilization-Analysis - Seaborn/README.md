# 📊 Hospital Cost & Patient Resource Utilization Analysis – Seaborn

## 📌 Project Overview

This project analyzes **1.08M+ hospital discharge records** to uncover key drivers of **healthcare costs and hospital resource utilization**.

Using **Python (Pandas, Seaborn, Matplotlib)**, the analysis identifies patterns in **patient volume, severity of illness, and treatment costs**, helping simulate real-world healthcare decision-making scenarios.

The goal is to provide **data-driven insights** that can support hospitals in improving **cost efficiency, resource allocation, and operational planning**.

---

## Table of Contents

1. [Objectives](#objectives)
2. [Dashboard Preview](#dashboard-preview)
3. [Key Insights](#key-insights)
4. [Business Recommendations](#business-recommendations)
5. [Key Visualizations](#key-visualizations)
6. [Dataset Information](#dataset-information)
7. [Dataset Link](#dataset-link)
8. [Tools & Technologies](#tools--technologies)
9. [Data Cleaning & Preparation](#data-cleaning--preparation)
10. [Visualizations Included (EDA)](#visualizations-included-eda)
11. [Project Structure](#project-structure)
12. [How to Run](#how-to-run)
13. [Author](#author)

--

## 💼 Business Problem
Healthcare systems face challenges in managing:

- Rising treatment costs- 
- Uneven distribution of patient load
- Inefficient resource allocation

This project investigates how **severity of illness, patient volume, and hospital characteristics** influence treatment costs and workload distribution.

---

## 🎯 Objectives

- Analyze **hospital patient volume (discharges)**
- Study the **impact of illness severity on treatment cost**
- Compare **hospital-wise cost variations**
- Examine the **relationship between patient volume and hospital cost**
- Understand **distribution of hospital charges vs actual costs**
- Identify patterns in **healthcare resource utilization**

---

## 🔄 Project Workflow

1. Data Collection (Kaggle Dataset)
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis
4. Data Visualization using Seaborn & Matplotlib
5. Insight Generation
6. Business Recommendations

---

## 📊 Key Metrics

- Total Records: **1,081,672+**
- Dataset Size: **150 MB**
- Key Cost Driver: **Severity of Illness**
- Highest Patient Volume: **Mount Sinai Hospital (511K+ discharges)**
- Key Observation: **Significant gap between charges and actual cost**

---

## 📂 Dataset Information

The dataset includes:

- Health Service Area, Hospital County, Facility Name
- Patient Demographics (Age, Gender, Race)
- Admission Type & Disposition
- Severity of Illness & Risk of Mortality
- Length of Stay & Discharges
- Mean Charges & Mean Cost

---

## 📂 Dataset Link:

Dataset size: 150 MB

The dataset is too large to upload to GitHub.  
You can download it from Kaggle:

https://www.kaggle.com/datasets/wajahat1064/hospital-inpatient-cost-data-by-new-york-state

---

## 🛠️ Tools & Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

---

## 🧹 Data Cleaning & Preparation

- Checked data structure and types
- Handled missing values
- Removed unnecessary columns and irrelevent columns
- Checked duplicates
- Standardized categorical variables
- Prepared dataset for Analysis

---

## 📊 Key Analysis & Visual Insights

- Severity of Illness Distribution
- Hospital-wise Patient Volume
- Mean Treatment Cost by Severity
- Patient Volume vs Treatment Cost
- Distribution of Hospital Charges
- Resource Utilization across Hospitals
- Medical vs Surgical Cases Trend

---

## 📷 Sample Visualizations

--

## 📈 Key Insights

- Patients with **extreme severity conditions drive the highest treatment costs**, making them the primary contributors to healthcare expenditure.
- **Mount Sinai Hospital handles the highest patient volume**, indicating heavy workload concentration in a few hospitals.
- A **significant gap exists between hospital charges and actual treatment costs**, highlighting pricing inefficiencies.
- Patient volume is **unevenly distributed**, with large hospitals managing the majority of cases.
- Higher patient volume does not always directly translate to higher costs, indicating **operational and efficiency differences across hospitals**.

---

## 🚀 Business Recommendations

- Allocate more resources to **high-severity cases** to manage rising treatment costs effectively.
- Optimize pricing strategies to reduce the gap between **charges and actual costs**.
- Improve operational efficiency in **high-volume hospitals** to balance workload distribution.
- Use historical data to implement **predictive planning for patient inflow and severity trends**.
- Ensure **transparent billing practices** to improve trust and cost management.

---

## 💡 Project Impact

- Identified key **cost-driving factors in healthcare systems**.
- Highlighted **resource imbalance across hospitals**.
- Provided insights for **cost optimization and operational efficiency**.
- Simulated a **real-world healthcare analytics use case**.

---

## 📂 Project Structure

Hospital-EDA-Seaborn/
│
├── hospital_eda_analysis.ipynb
├── dataset.csv
├── seaborn_visualizations.png
└── README.md

---

## ▶️ How to Run

```bash
pip install pandas seaborn matplotlib numpy
python hospital_eda_analysis.ipynb
```
---

## 👨‍💻 Author

Dhammadeep Gajbhiye
Aspiring Data Analyst | Python | Power BI | SQL

LinkedIn: (https://linkedin.com/in/dhammadeep-gajbhiye-57b38b16a/)
GitHub: (https://github.com/dhammdeepgajbhiye32)


⭐ If you like this project

Give it a star ⭐ on GitHub — it helps showcase the project!