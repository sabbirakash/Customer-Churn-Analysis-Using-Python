# 📉 Customer Churn Analysis Using Python

<p align="center">
  <img src="https://github.com/sabbirakash/Customer-Churn-Analysis-Using-Python/blob/main/Customer-Churn-Analysis-Banner.png" alt="Customer Churn Analysis Banner">
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</p>

---

# 📌 Project Overview

Customer retention is one of the most important challenges for subscription-based businesses. Understanding why customers leave helps organizations improve customer satisfaction, reduce revenue loss, and develop effective retention strategies.

This project performs an **Exploratory Data Analysis (EDA)** on a customer churn dataset using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**. Various demographic characteristics, service usage patterns, contract types, and payment methods are analyzed to identify the major factors influencing customer churn.

The project focuses on transforming raw customer data into meaningful business insights through visualization and statistical exploration.

---

# 🎯 Project Objectives

- Perform data cleaning and preprocessing.
- Explore customer demographics.
- Analyze churn distribution.
- Identify factors affecting customer churn.
- Discover customer behavior patterns.
- Generate actionable business insights through visualizations.

---

# 📂 Dataset Information

The dataset contains customer information including:

- Customer Demographics
- Senior Citizen Status
- Partner & Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming Services
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Customer Churn Status

---

# 🛠️ Tools & Technologies

| Category | Tools |
|----------|-------|
| Programming Language | Python |
| IDE | Jupyter Notebook |
| Libraries | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Version Control | Git |
| Repository Hosting | GitHub |

---

# 📋 Project Workflow

## 1️⃣ Data Collection

- Imported customer churn dataset.
- Loaded dataset into Pandas DataFrame.

---

## 2️⃣ Data Cleaning

Performed several preprocessing steps:

- Checked missing values
- Removed duplicate records
- Converted data types
- Replaced blank values in **TotalCharges**
- Converted SeniorCitizen values from **0/1** to **Yes/No**
- Prepared dataset for visualization

---

## 3️⃣ Exploratory Data Analysis (EDA)

The following analyses were performed:

- Overall churn distribution
- Gender-wise churn
- Senior Citizen analysis
- Tenure analysis
- Contract type analysis
- Internet service analysis
- Online Security analysis
- Online Backup analysis
- Device Protection analysis
- Tech Support analysis
- Streaming TV analysis
- Streaming Movies analysis
- Payment Method analysis

---

# 📊 Key Business Insights

## 📌 Overall Churn

- Around **26.5%** of customers have churned.
- Nearly three-fourths of customers are retained.

---

## 👥 Gender Analysis

- Male and female customers show very similar churn behavior.
- Gender has minimal influence on customer churn.

---

## 👴 Senior Citizen Analysis

- Senior citizens exhibit a higher churn rate than non-senior customers.
- This customer segment requires additional retention efforts.

---

## ⏳ Tenure Analysis

- Customers with very short tenure are more likely to churn.
- Long-term customers show significantly higher retention.

---

## 📝 Contract Type

- Month-to-month contracts experience the highest churn.
- One-year and two-year contracts have much lower churn rates.

---

## 🌐 Internet Service

- Customers using Fiber Optic Internet have the highest churn percentage.
- Internet service quality and pricing may influence customer decisions.

---

## 🔒 Online Security

- Customers without Online Security are considerably more likely to churn.
- Additional security services improve customer retention.

---

## 💾 Online Backup

- Customers without Online Backup churn more frequently.
- Value-added services encourage customer loyalty.

---

## 🖥 Device Protection

- Device Protection subscribers have better retention.
- Customers without this service are more likely to leave.

---

## 🎧 Tech Support

- Tech Support has a strong positive impact on retention.
- Customers receiving technical assistance remain longer.

---

## 📺 Streaming Services

- Streaming TV and Streaming Movies have relatively smaller impacts on churn compared to contract and support services.

---

## 💳 Payment Method

- Customers using **Electronic Check** experience the highest churn.
- Payment behavior can indicate customer satisfaction and engagement.

---

# 📈 Conclusion

This analysis demonstrates that customer churn is primarily influenced by **contract type**, **customer tenure**, **internet service**, **technical support**, and **additional value-added services** rather than demographic factors such as gender.

Businesses can significantly improve customer retention by encouraging long-term contracts, enhancing customer support, promoting additional service packages, and closely monitoring high-risk customer segments.

---

# 📁 Project Structure

```
Customer-Churn-Analysis-Using-Python
│
├── Dataset/
│   └── Customer-Churn.csv
│
├── Notebook/
│   └── TCA analysis.ipynb
│
├── Images/
│   ├── Customer Churn Analysis Banner.png
│   └── Dashboard Screenshots
│
├── README.md
└── LICENSE
```

---

# 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/sabbirakash/Customer-Churn-Analysis-Using-Python.git
```

### Navigate

```bash
cd Customer-Churn-Analysis-Using-Python
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```
TCA analysis.ipynb
```

---

# 📚 Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 👨‍💻 Author

**Sabbir Uddin Akash**

🌐 Portfolio: [Sabbir Uddin Akash](https://sabbirakash.github.io)

💼 LinkedIn: [Sabbir Uddin Akash](https://www.linkedin.com/in/sabbirakash)

💻 GitHub: [sabbirakash](https://github.com/sabbirakash)

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It motivates me to build more Data Analytics and Python projects.

---
