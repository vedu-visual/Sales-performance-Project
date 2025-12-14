# 📊 Sales Data Cleaning & Exploratory & Descriptive Data Analysis 

## 📌 Project Overview

This project focuses on cleaning, preprocessing, and analyzing retail sales data using **Python (Pandas)**. The goal is to transform raw Excel sales data into a clean, analysis-ready dataset and extract meaningful **business insights** related to revenue, profit, customer demographics, and sales performance across regions and channels.


---

## 🗂 Dataset Description

The dataset contains **100 retail sales transactions** with the following attributes:

* Customer ID
* Customer Age
* Customer Gender
* Product Category
* Cost (per unit)
* Sales Price (per unit)
* Quantity
* Date of Purchase
* Region
* Sales Channel (Online / In-store)

> **Source:** Excel file (`project Sales.xlsx`)

---

## 🛠 Tools & Technologies

* Python 🐍
* Pandas
* Jupyter Notebook
* Excel

---

## 🧹 Data Cleaning Steps

The following steps were performed to ensure data quality:

1. **Loaded Excel data** using `pandas.read_excel()`
2. **Checked missing values** using `isnull().sum()` (No missing values found)
3. **Verified data types** for numeric, categorical, and datetime columns
4. **Identified and removed duplicate records** using `drop_duplicates()`
5. **Removed irrelevant column** (`Unnamed: 0` – Excel index column)

The cleaned dataset was stored as `cleaned_data` for further analysis.

---

## 🔧 Feature Engineering

Additional business metrics were created to enhance analysis:

* **Revenue** = Sales Price × Quantity
* **Total Cost** = Cost × Quantity
* **Profit** = Revenue − Total Cost
* **Age Groups** created for customer segmentation

These metrics enabled deeper financial and customer behavior analysis.

---

## 📊 Exploratory Data Analysis (EDA)

Key analyses performed:

* Revenue and profit distribution analysis
* Profit by **Product Category**
* Revenue by **Sales Channel** (Online vs In-store)
* Region-wise revenue performance
* Customer age group segmentation and revenue contribution
* Sorting and ranking customers by age

---

## 📈 Key Insights (Example)

* Certain product categories contribute disproportionately higher profits
* Online sales channels generate higher revenue in specific regions
* Customers in specific age groups show higher purchasing value

*(Insights may vary depending on visualization and aggregation level)*

---

## 📁 Project Structure

```text
├── project Sales.xlsx
├── sales_data_analysis.ipynb
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone this repository
2. Install required libraries:

   ```bash
   pip install pandas openpyxl
   ```
3. Open the Jupyter Notebook
4. Run cells sequentially to reproduce the analysis

---

## 🎯 Skills Demonstrated

* Data Cleaning & Validation
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Business-Oriented Data Analysis
* Python & Pandas proficiency

---

## 📬 Contact

If you have suggestions, feedback, or would like to collaborate:

**Vedant Ratnakar**
Aspiring Data Analyst 

---

⭐ *If you found this project useful, consider giving it a star!*



