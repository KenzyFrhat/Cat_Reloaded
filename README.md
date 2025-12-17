# 📊 **Intermediate Data Analysis Tasks**
*A structured set of hands-on tasks covering NumPy, Data Cleaning, and Data Visualization.*

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-Data%20Computing-blue?logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

<p align="center">
  <b>Clean notebooks</b> • <b>Real datasets</b> • <b>Analytical thinking</b> • <b>Evaluation-ready</b>
</p>

---

# 🌟 **Overview**

This repository contains a collection of **intermediate-level data analysis tasks** designed to evaluate practical skills in:

- Numerical computing with **NumPy**
- **Data cleaning & preprocessing** using Pandas
- **Exploratory data analysis and visualization**

Each task is implemented in a **self-contained Jupyter Notebook**, with clear reasoning, step-by-step processing, and meaningful visual insights.

---

# ✨ **What This Repository Demonstrates**

### 🧮 1. NumPy Fundamentals
- Difference between NumPy arrays and Python lists  
- 2D array indexing and slicing  
- Understanding the `axis` parameter in aggregation functions  
- Element-wise (`*`) vs matrix (`@`) multiplication  

### 🧹 2. Real-World Data Cleaning
- Handling missing values and duplicates  
- Dropping low-quality columns  
- Renaming columns with consistent conventions  
- Statistical imputation (mean & mode)  
- Distribution analysis after cleaning  

### 📈 3. Insightful Data Visualization
- Income and age distribution analysis  
- Approval vs rejection comparisons  
- Categorical analysis (loan purpose, home ownership)  
- Data-driven interpretation of results  

---

# 🗂️ **Project Structure**

```bash
TASKS_TO_JOIN/
│
├── .venv/                     # Local virtual environment
│
├── Data_Cleaning/
│   ├── candyhierarchy2017.xlsx
│   └── Data_Cleaning.ipynb
│
├── Data_Visualization/
│   ├── Loan approval prediction.csv
│   └── Data_Visualization.ipynb
│
├── Numpy.ipynb                # NumPy concepts & questions
│
├── Cat_Reloaded_Img.png       # Supplementary image asset
│
└── README.md
```

---

# 🧪 **Task Breakdown**

## 🔹 Task 1: NumPy Questions
**Notebook:** `Numpy.ipynb`

Focuses on conceptual understanding supported by code examples, including array operations, indexing, and matrix algebra.

---

## 🔹 Task 2: Data Cleaning
**Dataset:** `candyhierarchy2017.xlsx`  
**Notebook:** `Data_Cleaning/Data_Cleaning.ipynb`

### Key Steps
- Dataset exploration
- Missing value & duplicate detection
- Column filtering based on NaN ratios
- Mode imputation:
  - `Q1: GOING OUT?`
  - `Gender`
- Mean imputation:
  - `Age`
- Age distribution visualization
- Top 10 loved & hated candies visualization

---

## 🔹 Task 3: Data Visualization
**Dataset:** Loan Approval Dataset (Kaggle)  
**Notebook:** `Data_Visualization/Data_Visualization.ipynb`

### Analysis Dimensions
- **Income vs Age**
- **Loan Purpose**
- **Home Ownership & Approval Likelihood**

Each visualization is followed by interpretation and reasoning.

---

# 🚀 **Environment & Usage**

### Requirements
- Python 3.9+
- NumPy
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

### Run Locally
```bash
jupyter notebook
```

Open the desired notebook and run cells sequentially.

---

# 📌 **Evaluation Notes**

- Each notebook is independent and reproducible  
- Code is structured and readable  
- Emphasis is placed on **why** decisions were made, not just results  
- Suitable for academic evaluation or portfolio review  

---

# 🛣️ **Possible Extensions**
- Feature engineering
- Predictive modeling
- Dashboard-style visualizations
- Automated data quality checks

---

# 📄 **License**
This project is for educational purposes.

---

#  👩‍💻 **Author**
**Kenzy Frhat**  
Created as part of an intermediate-level data analysis assessment.
