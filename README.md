# Intermediate Data Analysis Tasks

This repository contains a collection of **intermediate-level data analysis tasks** designed to assess and demonstrate proficiency in **NumPy**, **data cleaning**, and **data visualization** using Python.  
Each task is organized into a clear, self-contained structure with its own dataset and Jupyter Notebook.

---

## Repository Overview

The project is divided into three main tasks:

1. **NumPy Fundamentals** – Conceptual and practical understanding of NumPy arrays and operations.
2. **Data Cleaning** – Cleaning, preprocessing, and exploratory analysis of a real-world dataset.
3. **Data Visualization** – Extracting insights through visual exploration of a loan approval dataset.

The repository is structured to be **readable, evaluable, and reproducible** for reviewers, instructors, or collaborators.

---

## Repository Structure

```
TASKS_TO_JOIN/
│
├── .venv/
│   └── Virtual environment (local use only)
│
├── Data_Cleaning/
│   ├── candyhierarchy2017.xlsx
│   └── Data_Cleaning.ipynb
│
├── Data_Visualization/
│   ├── Loan approval prediction.csv
│   └── Data_Visualization.ipynb
│
├── Numpy.ipynb
│
├── Cat_Reloaded_Img.png
│   └── Supplementary image asset
│
└── README.md
```

---

## Task 1: NumPy Questions

**Notebook:** `Numpy.ipynb`

This task focuses on understanding the conceptual and operational differences between NumPy and native Python structures.

### Covered Topics
- Difference between NumPy arrays and Python lists
- Indexing elements in 2D NumPy arrays
- Understanding the `axis` parameter in aggregation functions such as `numpy.sum()`
- Element-wise multiplication (`*`) vs matrix multiplication (`@`) for 2D arrays

---

## Task 2: Data Cleaning

**Directory:** `Data_Cleaning/`  
**Dataset:** `candyhierarchy2017.xlsx`  
**Notebook:** `Data_Cleaning.ipynb`

### Objectives
- Explore the dataset
- Detect missing values and duplicates
- Clean and preprocess the data
- Drop columns with excessive missing values
- Rename columns using a consistent naming style
- Handle missing values:
  - Q1: GOING OUT? → mode
  - Gender → mode
  - Age → mean
- Visualize age distribution after cleaning
- Visualize top 10 loved and hated candies

---

## Task 3: Data Visualization

**Directory:** `Data_Visualization/`  
**Dataset:** `Loan approval prediction.csv`  
**Notebook:** `Data_Visualization.ipynb`

### Analysis Areas

#### Income & Age
- Income distribution
- Income variability across age groups
- Approval vs rejection comparison

#### Loan Purpose
- Most frequent loan purposes
- Highest approvals
- Highest rejections

#### Home Ownership & Loan Approval
- Most common home-ownership type among approved applicants
- Relationship between mortgage ownership and approval likelihood

---

## Environment & Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Notes for Reviewers

- Each notebook is self-contained
- Code is clearly structured with explanations
- Focus is on analytical reasoning and clarity

---

## Author

Created as part of an intermediate-level data analysis assessment.
