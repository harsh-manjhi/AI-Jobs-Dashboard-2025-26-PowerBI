# AI-Jobs-Dashboard-2025-26-PowerBI

> A Power BI dashboard project built during the Microsoft Elevate AICTE Internship, February 2026.

---

##  About the Project

The AI industry is growing fast, but understanding its job market is not easy. This project takes a dataset of 1,500 real AI job postings from 2025 and 2026 and turns it into an interactive Power BI dashboard — so that anyone can understand salaries, hiring trends, and remote work culture in the AI field at a glance.

---

##  Dashboard Highlights

- ✅ 1,500 job postings analyzed
- ✅ 14 countries covered
- ✅ 12 industries compared
- ✅ 25 unique AI job titles

---

##  Questions the Dashboard Answers

- Which AI roles pay the most?
- How does experience level affect salary?
- Which industries and company sizes hire the most AI talent?
- How common is remote work in the AI field?

---

##   Tools & Techniques Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard design & visuals |
| Power Query Editor | Data cleaning & transformation |
| DAX | Custom measures & KPIs |
| Kaggle | Dataset source |

---

##   DAX Measures Built
```dax
Total Jobs = COUNTROWS('ai_jobs_market_2025_2026')

Average Salary USD = AVERAGE('ai_jobs_market_2025_2026'[annual_salary_usd])

Remote Work % = DIVIDE(COUNTROWS(FILTER('ai_jobs_market_2025_2026', 'ai_jobs_market_2025_2026'[remote_work] = "Fully Remote")), [Total Jobs])

Senior Role % = DIVIDE(COUNTROWS(FILTER('ai_jobs_market_2025_2026', 'ai_jobs_market_2025_2026'[is_senior] = 1)), [Total Jobs])
```

---

##   Files in this Repository

| File | Description |
|------|-------------|
| `ai_jobs_market_2025_2026.csv` | Raw dataset used for analysis |
| `powerbi_project_aicte_internship_h.pbix` | Power BI dashboard file |
| `MS Elevate AICTE Internship - Project Presentation.pdf` | Project presentation (PDF) |

---

##   Key Findings

- Average AI salary globally is around **$166K USD**
- **Finance and Healthcare** are emerging as top AI hiring sectors, not just Technology
- Experience level has a **direct and significant** impact on salary
- A large portion of AI jobs offer **remote or hybrid** work options

---

##   Submitted By

**Harsh Manjhi**
Lakshmi Narain College of Technology — MCA
📧 harshmanjhi822@gmail.com
