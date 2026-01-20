# Perth Job Market Analysis (SEEK)

## Overview
This project analyzes job postings in **Perth, Western Australia**, scraped from SEEK.
The goal is to understand the local job market structure and identify hiring patterns,
with a particular focus on **Sales and Business Development roles**.

This project is designed as a **practical data analytics portfolio**, demonstrating
how raw job-market data can be cleaned, analyzed, and translated into actionable insights
for job seekers and business decision-making.

---

## Key Questions
- What types of roles are most in demand in Perth?
- How strong is the demand for Sales & Business Development positions?
- Which companies are hiring repeatedly?
- How recent are the job postings?
- What is the difference between Featured and non-Featured roles?

---

## Dataset
- **Source**: SEEK job cards (Perth region)
- **Records**: 541 job postings after cleaning
- **Key fields**:
  - Job title
  - Company
  - Category
  - Employment type
  - Location
  - Posted days
  - Featured status
  - Salary (if available)

---

## Project Structure
seek-perth-jobs-analysis/
├─ data/
│ ├─ raw/
│ │ └─ seek.xlsx
│ └─ cleaned/
│ └─ seek_cleaned_perth_jobs.xlsx
├─ notebooks/
│ ├─ 01_data_cleaning_and_eda.ipynb
│ └─ 02_sales_bd_job_analysis.ipynb
├─ requirements.txt
└─ README.md
---

## Analysis Workflow
1. **Data Cleaning**
   - Removed duplicates
   - Standardized job titles and employment types
   - Separated location, posted days, and Featured flags
   - Prepared a clean dataset suitable for analysis

2. **Exploratory Data Analysis (EDA)**
   - Identified the most common job titles and categories
   - Analyzed job posting freshness
   - Compared Featured vs non-Featured roles

3. **Sales & Business Development Focus**
   - Filtered Sales / BD related roles using keyword matching
   - Identified top hiring companies
   - Analyzed recent hiring trends (last 7–14 days)

---

## Key Insights
- Sales and Business Development roles represent a significant share of Perth job postings.
- Business Development Manager and Sales Representative are among the most common titles.
- A small group of companies shows repeated hiring activity, indicating sustained demand.
- Featured roles suggest higher competition and employer urgency.

---

## Tools & Skills Demonstrated
- Python
- Pandas
- Data cleaning & transformation
- Exploratory data analysis (EDA)
- Data-driven job market analysis
- Git & GitHub for version control

---

## Why This Project Matters
This project demonstrates the ability to:
- Work with messy, real-world data
- Translate raw data into meaningful business insights
- Apply data analytics to practical decision-making scenarios
- Communicate findings clearly to non-technical stakeholders

---

## Author
**Joshua Kang**  
Data Analytics & Business Development Background  
Location: Perth, Western Australia

