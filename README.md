# COVID-19-Clinical-Trials-EDA-Pandas
<p align="center">
  <img src="https://max-website20-images.s3.ap-south-1.amazonaws.com/Coronavirus_COVID_19_1_017dbd1590.jpg" width="450" alt="Project Logo">
</p>

<h1 align="center"> COVID-19 Clinical Trials — Exploratory Data Analysis</h1>

<p align="center">
  An end-to-end Data Analysis project using Python, Pandas & Matplotlib.
</p>

---

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on a publicly available dataset containing **COVID-19 clinical trials** data.  
The goal is to explore trends, missing data patterns, trial status, countries involved, phases, demographics, and other important variables.

Dataset Source:  
➡️ ClinicalTrials.gov (Referenced in project PDF)

---

## 🎯 Project Objectives

- Understand the dataset structure and contents  
- Perform cleaning & preprocessing  
- Handle missing values logically (MCAR, MAR, NMAR classification)  
- Create new derived features (e.g., Country extracted from Location)  
- Perform statistical analysis  
- Generate meaningful visualizations  
- Summarize insights from the analysis  

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data Cleaning & EDA |
| NumPy | Computations |
| Matplotlib / Seaborn | Visualizations |
| Jupyter Notebook | Implementation |

---

## 📂 Dataset Details

- Rows: **5783**
- Columns: **25 after cleaning**
- Data Type: Mixed (Categorical + Numerical)
- Contains information about:
  - Study Title  
  - Country  
  - Gender & Age Group  
  - Trial Phase  
  - Status  
  - Dates (Start, Completion, Posted)  
  - Enrollment Size  

---

## Data Cleaning Steps

✔️ Dropped irrelevant features (`Study Documents`, `Results First Posted`)  
✔️ Checked missing values & handled them strategically  
✔️ Filled categorical nulls using `"Missing <feature>"` method  
✔️ Filled numerical missing values (`Enrollment`) using **median** due to skewness  
✔️ Removed duplicates  
✔️ Derived new feature: `Country`  

---

## 📊 Visualizations Included

- Top countries contributing to trials  
- Distribution of study status  
- Gender participation in trials  
- Most active start month  
- KDE distribution of enrollment size  

---

