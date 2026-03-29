# 💼 Salaries Case Study  
### Exploratory Data Analysis on San Francisco Employee Salaries  

---

## 🚀 Overview  

This project performs an in-depth **Exploratory Data Analysis (EDA)** on a large salary dataset containing **148,000+ employee records** from San Francisco.  

The goal is to uncover:  

- Salary trends over time  
- High-paying roles  
- Impact of job titles on compensation  
- Data inconsistencies and missing values  

---

## 📊 Dataset  

The dataset contains **148,654 rows and 13 columns**, including:  

- Employee Name  
- Job Title  
- Base Pay  
- Overtime Pay  
- Other Pay  
- Benefits  
- Total Pay  
- Total Pay Benefits  
- Year  

---

## 📌 Problem Statement  

Raw salary datasets often contain:  

- Missing values  
- Mixed data types  
- Inconsistent entries (e.g., "Not provided")  

This project aims to:  

- Clean and preprocess the data  
- Extract meaningful insights  
- Understand salary distributions and trends  

---

## ⚙️ Data Cleaning Steps  

- Removed irrelevant columns:  
  - `Id`, `Notes`, `Agency`, `Status`  

- Handled missing values:  
  - Replaced `"Not provided"` with `NaN`  

- Converted `BasePay` to numeric  

- Identified null values across columns  

---

## 🔍 Missing Values Summary  

- **Benefits:** 36,159 missing  
- **BasePay:** 605 missing  
- **Notes:** completely empty  
- **Status:** 110,535 missing  

---

## 🔎 Exploratory Analysis  

### 📈 Dataset Insights  

- Total records: **148,654**  
- Unique job titles: **2159**  
- Most common job: **Transit Operator**  

---

### 💰 Salary Insights  

- **Maximum Total Pay:** 567,595  
- **Minimum Total Pay:** -618 *(data anomaly)*  
- **Average Total Pay:** ~74,768  

---

### 📅 Salary Trend by Year  

| Year | Avg Base Pay |
|------|-------------|
| 2011 | 63,595 |
| 2012 | 65,436 |
| 2013 | 69,630 |
| 2014 | 66,564 |

👉 Salary increased steadily until 2013  

---

### 🧑‍💼 Job Title Analysis  

- Total unique roles: **2159**  

**Most frequent roles:**
- Transit Operator  
- Special Nurse  
- Registered Nurse  
- Police Officer  

---

### 🔥 Interesting Findings  

- Some employees have **zero salary entries**  
- Presence of **negative salary values** *(data issues)*  
- Large variation in pay across roles  
- High overtime significantly impacts total salary  

---

## 🧪 Sample Queries Performed  

- Employees with specific job roles (e.g., `"CAPTAIN"`)  
- Fire department employee analysis  
- Salary lookup for specific individuals  
- Highest paid employee detection  

---

## 🏗️ Tech Stack  

- Python  
- Pandas  
- NumPy  
- Jupyter Notebook  

---

## 📂 Project Structure  

```
SalariesCaseStudy/
│
├── SalariesCaseStudy.ipynb
├── Salaries.csv
├── README.md
```

---

## 🚀 How to Run  

### 1. Clone the repository  
```bash
git clone https://github.com/your-username/salaries-case-study.git
cd salaries-case-study
```

### 2. Install dependencies  
```bash
pip install pandas numpy jupyter
```

### 3. Run the notebook  
```bash
jupyter notebook SalariesCaseStudy.ipynb
```

---

## 🎯 Key Learnings  

- Handling real-world messy datasets  
- Data cleaning and preprocessing  
- Feature analysis using Pandas  
- Extracting meaningful insights from large datasets  
