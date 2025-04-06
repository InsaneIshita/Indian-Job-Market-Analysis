#  Indian Job Market Analysis - Power BI Report

This project presents a **2-page interactive Power BI report** analyzing job listings in India. The dataset spans from **late December 2024 to January 2025**, sourced from Kaggle. The objective is to uncover real-world insights on job trends, skill demands, company hiring patterns, salaries, and more — helping both job seekers and recruiters understand the current job landscape.

##  Tools & Techniques Used
- **Power BI Desktop**
- **Power Query Editor**: For data cleaning and transformation (e.g., splitting comma-separated values, removing nulls, unpivoting columns)
- **DAX**: For creating KPIs, averages, percentages, and aggregated measures
- **Visuals**: Bar charts, donut charts, KPIs, scatter plots, slicers

##  Key Insights

### 🔹 Page 1: Job Market Overview
-  **Top In-Demand Skills**: `Python`, `React`, and `UI/UX` are the most sought-after skills, each offering an average salary of **₹4.1 LPA**.
-  **Top Hiring Companies**: Roles like `Cyber Security Analyst`, `Financial Analyst`, and `Graphic Designer` are actively recruited by **Amazon**, **Google**, and **Wipro**.
-  **Top Job Location**: **Hyderabad** leads in the number of job postings.
-  **Work Mode Distribution**:
  - **Remote**: 34%
  - **On-site**: 33%
  - **Hybrid**: 33%
-  **Job Portal Distribution**: **Naukri.com** and **Indeed** host more job listings than LinkedIn.
-  **Job Type Insights**: **Part-time jobs (26%)** slightly outnumber **contract-based jobs (24%)**.

### 🔹 Page 2: Salary, Experience & Company Analysis
-  **Highest Paying Job Title**: `Business Analyst` offers the highest average salary of **₹13.5 LPA**.
-  **Top Education Preferences**: Jobs majorly require candidates with **B.Tech** or **B.Sc** degrees.
-  **Company Size vs Salary**: **Large companies** offer noticeably higher average salaries than smaller ones.
-  **Jobs vs Applicants**: There’s a significant gap between the **number of job postings** and **total number of applicants**, indicating high competition.
-  **Experience vs Salary**: There is **very little to no increase** in salary with increased experience levels.

##  Data Preparation
- Used **Power Query** to:
  - Split comma-separated fields like skills into individual rows.
  - Clean inconsistent data formats.
  - Remove duplicates, null values, and standardize categorical fields.
- Created multiple **DAX measures** for:
  - Average salary, most common job titles, top skills, and experience levels.
  - Percentage breakdowns of job types, portals, and work modes.
  - KPIs for top city and in-demand skill.

## ⚠️ Data Disclaimer
This analysis is based on a dataset covering approximately one month of job listings and may not fully reflect the **entire Indian job market**. Observations such as **consistently high salaries** or **imbalanced applicant numbers** could be due to sampling bias or limitations of the original data source. This project aims to demonstrate **data analysis and visualization capabilities** rather than serve as a definitive market report.


## 📁 Dataset Source
[Kaggle - India Job Market Dataset (2024–25)](https://www.kaggle.com/datasets/murli05/india-job-market-dataset-csv)

---

##  Contact

📧 **Gmail**: singhishita3299@gmail.com  
🔗 **LinkedIn**: [linkedin.com/in/ishitasingh3299](https://www.linkedin.com/in/ishitasingh3299)

---

**Explore the `.pbix` file to interact with filters, slicers, and visuals for deeper insights!**

