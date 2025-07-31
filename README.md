# 🏥 Oakcrest Medical – Power BI Dashboard Project

## 📌 Project Overview

As a volunteer data analyst at *Oakcrest Medical*, a private healthcare facility, I worked on uncovering key patterns, operational bottlenecks, and financial insights from hospital data spanning **2022 to 2025**. This dashboard was built to support internal performance reviews and strategic decision-making.

> ℹ️ **Disclaimer:** For confidentiality reasons, I recreated this analysis using fictional data and renamed the institution *Oakcrest Medical*. The structure, techniques, and insights reflect the real project I completed during my volunteer role.

---

## 🎯 Project Objectives

- Track admission trends and patient flow across departments  
- Analyze the success, cost, and recurrence of medical procedures  
- Evaluate billing recovery and outstanding balances across payment types  
- Provide leadership with an interactive, insight-driven report for decision support  

---

## 🗂️ Dataset Overview

The fictional dataset simulates 4 years of hospital operations with the following CSV files:

| Table         | Description |
|---------------|-------------|
| `patients.csv`     | Demographic and contact data of 27,000+ patients |
| `admissions.csv`   | Records of patient check-in and discharge |
| `procedures.csv`   | Treatments and clinical operations performed |
| `departments.csv`  | Hospital departments and their capacity |
| `billing.csv`      | Total cost, amount paid, and coverage breakdowns |

---

## 💡 Key Features

- 🔄 Calendar-linked date filtering across all report pages  
- 📊 Dynamic KPIs for each area (Admissions, Procedures, Billing)  
- 📈 Year-on-year visual trends with insights from 2022–2025  
- 📌 Departmental and payment-type breakdowns  
- 🛠️ Built with Power BI  

---

## 📌 Dashboard Pages

### 1. Admissions Overview
- Total admissions, readmission rate, avg. length of stay  
- Admissions by department, discharge status  
- Monthly admission patterns and department performance

### 2. Procedures Analysis
- Volume and outcome of procedures by type and department  
- Avg. procedure cost and repeat rate  
- Success rate trends and outcome tables

### 3. Billing Summary
- Total billings vs. amount paid and outstanding balance  
- Recovery rate, payment type and coverage analysis  
- Departmental billing breakdowns

---

## 🛠️ Tools Used

| Tool       | Purpose                       |
|------------|-------------------------------|
| Power BI   | Dashboard creation and interactivity |
| DAX        | Custom KPI calculations and filters |
| CSV Files  | clean and structured datasets as source|
| Power Query| Data transformation and modelling |                                        |
---

## 🔐 Ethical Considerations

This project is a **simulation of a real volunteer engagement**. While I worked with actual hospital data during the role, this version uses false names and generated data to respect the institution’s privacy. The project retains the same analytical logic and visualization methods.

---

## 📁 Repository Structure

```
Oakcrest_Medical/
│
├── data/                         # Contains all CSV files
│   ├── patients.csv
│   ├── admissions.csv
│   ├── procedures.csv
│   ├── departments.csv
│   └── billing.csv
│
├── README.md                  # This file
│                  
│
├── documentation/
│   └── Results_and_Insights.md    # Full KPI summaries and visual insights
│
├── images/                     
│   └── admission.png   # Dashboard screenshots 
├   └── billing.png
├   └── procedure.png 
├── dashboard/                     # Power BI source file
    └── Oakcrest_dashboard.pbix

---

## 📊 Results & Insights

Full analysis is presented separately in Results_and_Insights.md , broken down by year and by page (Admissions, Procedures, Billings).

---

## 📌 Final Notes

This project showcases my ability to work on sensitive data in a structured and ethical way, while building professional-grade dashboards that support healthcare analysis and performance reviews.
