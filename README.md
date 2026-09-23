# Navigating the Data Job Market: Skills vs. Pay

### 5-Second Recruiter Summary
An end-to-end **Power BI** business intelligence dashboard that cleans, models, and visualizes a global dataset of **407K+ data job postings**. The project transforms raw data into an interactive market intelligence tool, featuring robust data modeling architectures, advanced DAX calculations, and a highly responsive user interface.

---

## Dashboard Preview
![Dashboard Preview](https://github.com/deepika-analyst/powerbi-data-job-market-analysis/blob/main/Data%20Jobs%20Dashboard.png)

## Tools, Technical Knowledge & Skills Applied

### Data Modeling & Architecture
* **Star Schema Architecture:** Designed and implemented efficient relationships between central fact tables (`job_postings_fact`) and surrounding dimension tables.
* **Row Context Architecture:** Engineered custom calculated columns crossing relationship bridges via `COUNTROWS(RELATEDTABLE(...))` to evaluate row-by-row skill counts across hundreds of thousands of records.
* **Calculated Tables:** Formatted and generated independent lookup tables to optimize filter logic and support reporting structures.

###  DAX (Data Analysis Expressions) & Metrics
* **Advanced DAX Formulas:** Developed performance-optimized DAX expressions for statistical aggregation, complex comparisons, and responsive user selection logic.
* **Custom Measures:** Built explicit measures to isolate key performance indicators (KPIs) like Gross Median Salary, Median Hourly Pay, and aggregate Job Counts.
* **KPI Card Visuals:** Designed high-level, interactive summary metrics displaying overall market metrics (**407K Job Count**, **5 Skills per Job**, **\$113.75K Median Salary**, and **\$47.62 Median Hourly Pay**).

### Report UI/UX & Interactivity
* **Field Parameters:** Programmed dynamic parameter toggles (`Select Parameter for V1`), allowing end-users to instantly swap out X-axis and Y-axis variables (Job Count, Median Salary, Skills Count, Median Hourly Pay) inside a single chart.
* **Advanced Slicers:** Integrated multi-select dropdown slicers filtering the entire report layout by specific technical skills and professional job titles.
* **Clear All Slicers Button:** Configured action-based bookmark buttons to immediately reset report states and clear user filter selections with a single click.

---

## Key Insights from the Data
* **Market Demand:** Python and SQL dominate requirements, combining for over **437K** total skill mentions.
* **Salary Leaders:** Senior Data Scientists lead compensation rankings with a gross median salary of **\$156K**.
* **Skill Thresholds:** Across all entry levels and senior tracks, the industry average trends steadily at **5 core tech skills** per job profile.

---

## Dataset used 
* [job_postings_fact](https://github.com/deepika-analyst/powerbi-data-job-market-analysis/blob/main/job_postings_fact.csv%20(1).zip)
* [skills.dim](https://github.com/deepika-analyst/powerbi-data-job-market-analysis/blob/main/company_dim.csv)
* [skills_job.dim](https://github.com/deepika-analyst/powerbi-data-job-market-analysis/blob/main/skills_dim.csv)
* [company_dim]()

---

## Acknowledgments
* **Credits:** Built using datasets and concepts from **Luke Barousse (DataNerd)**'s free YouTube data analyst curriculum.
