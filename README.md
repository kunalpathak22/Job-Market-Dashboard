# 📊 Data Science & Analytics Job Market Dashboard | Power BI Solution

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Data_Analysis_Expressions-blue?style=for-the-badge)](https://learn.microsoft.com/en-us/dax/)
[![Power Query](https://img.shields.io/badge/Power_Query-ETL-green?style=for-the-badge)](https://learn.microsoft.com/en-us/power-query/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

An end-to-end interactive **Business Intelligence dashboard** designed to analyze the global data job market. Built with **Power BI**, **Power Query (ETL)**, and **DAX**, this solution consolidates 2024 data science and analytics job posting data into actionable compensation benchmarks, location analytics, and work-model trends for job seekers, hiring managers, and recruiters.

---

## 📌 Business Problem & Executive Summary

Information regarding data science and analytics roles (salaries, remote flexibility, required credentials, hiring platforms) is typically fragmented across multiple job boards. This project solves that problem by transforming unorganized posting data into a centralized, interactive dashboard.

### Key Objectives Achieved:
- **Compensation Benchmarking:** Evaluated median yearly and hourly salaries across job titles, experience levels, and locations.
- **Work Model & Perks Analysis:** Tracked the prevalence of Remote/WFH options, health insurance benefits, and degree requirement distributions.
- **Channel & Location Optimization:** Identified top hiring platforms and geographic job distribution hotspots globally.

---

## 🛠️ Tech Stack & Analytical Methods

| Domain | Tool / Methodology | Key Applications |
|---|---|---|
| **Business Intelligence** | Power BI Desktop | Dashboard layout, UI/UX design, custom visual mapping |
| **ETL & Data Prep** | Power Query (M) | Data cleaning, data type casting, string manipulation, null handling |
| **Data Modeling & Calculations** | DAX (Data Analysis Expressions) | Custom KPIs, implicit & explicit measures, dynamic drill-through filters |
| **Geospatial Analytics** | Azure Maps Visual | Global geospatial job distribution mapping |
| **Interactive Features** | Bookmarks, Action Buttons, Slicers | Dynamic navigation, multi-field filtering, page drill-through |

---

## 📊 Dashboard Architecture & Key Visualizations

The report is structured into two complementary pages designed for both executive summaries and deep-dive analytical investigation:

### 1. Executive Market View (`Page 1: Data Jobs Dashboard`)
Designed as a high-level command center for quick market evaluation:
- **KPI Summary Cards:** Highlights overall job posting volume, median salary, and key market metrics.
- **Hourly vs. Median Salary (Scatter Chart):** Correlates hourly pay rates against annual compensation to identify high-value pricing models.
- **Job Counts by Role (Bar Chart):** Ranks the demand across data analyst, data engineer, data scientist, and related specializations.
- **Jobs Trend Over Time (Line Chart):** Evaluates posting frequency and seasonal hiring patterns.
- **Job Stats Breakdown (Matrix / Table):** Granular, sortable performance overview across multiple job parameters.

### 2. Role Deep-Dive (`Page 2: Job Title Drill Through`)
A context-sensitive drill-through page allowing detailed inspection of specific roles:
- **Salary Gauge Indicators:** Benchmarks specific target roles against global yearly ($USD) and hourly ($USD) pay scales.
- **Workplace & Perk Metrics (Donut Charts):**
  - `Work From Home %` (Remote flexibility index)
  - `No Degree Mention %` (Accessibility vs. credential requirements)
  - `Health Insurance %` (Benefits coverage rate)
- **Job Schedule Types (Treemap):** Breaks down full-time, contract, part-time, and internship distributions.
- **Top Hiring Channels (Bar Chart):** Identifies leading recruitment platforms posting targeted roles.
- **Global Job Distribution (Azure Map):** Interactive geospatial map visualizing international hiring hubs.

---

## 💡 Key Analytical Insights

1. **Remote Compensation Premium:** Roles offering Work From Home (WFH) options demonstrated competitive compensation while expanding candidate talent pools globally.
2. **Skill & Credential Trends:** A significant portion of listings prioritize practical skill demonstration over formal degree requirements (`No Degree Mention %`).
3. **Platform Concentration:** Job posting frequency heavily skews towards key specialized aggregators, highlighting strategic application channels for applicants.

---

## 📁 Repository Structure

```
├── Data_Jobs_Dashboard.pbix   # Primary Power BI report & dataset file
└── README.md                  # Project documentation & portfolio summary
```

---

## 🚀 How to Run & Explore

1. **Prerequisites:** Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Free download).
2. **Clone / Download Repository:**
   ```bash
   git clone https://github.com/your-username/power-bi-data-jobs-dashboard.git
   ```
3. **Open Dashboard:** Double-click [`Data_Jobs_Dashboard.pbix`](Data_Jobs_Dashboard.pbix) to open the interactive report in Power BI Desktop.
4. **Interact:** Use the slicers on Page 1 to filter by title, or right-click any job role to drill through to Page 2 for granular metrics.

---

## 👤 Author & Contact

**Kunal Pathak**  
*Data Analyst / Business Intelligence Professional*

- 💼 **LinkedIn:** [www.linkedin.com/in/kunalpathak22](#)
- ✉️ **Email:** kunalpathak.221100@gmail.com
- 🐙 **GitHub:** [@kunalpathak22](https://github.com/kunalpathak22)

---
*If you find this project valuable, feel free to give it a ⭐️!*
