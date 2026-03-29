# Interview Preparation Guide: Data Analyst / BI Role

---

## 📊 SKILLS OVERVIEW & GAPS ANALYSIS

### Your Strengths (Well-Positioned)
✅ **SQL Expertise** – Your resume shows advanced SQL optimization (partition pruning, CTEs, aggregations, window functions)  
✅ **Python Proficiency** – Strong background with PySpark, pandas, and data manipulation  
✅ **ETL/Data Pipeline Knowledge** – 5+ years designing enterprise pipelines; familiar with orchestration, data quality frameworks  
✅ **Data Architecture** – Experience with data modeling, schema design, and lakehouse/warehouse concepts  
✅ **Cloud Platforms** – AWS expertise (S3, Glue, Lambda, Redshift); transferable to cloud-based analytics  
✅ **Git & Version Control** – Demonstrated in your DevOps/Terraform work  
✅ **Data Governance** – Built validation frameworks with Great Expectations; understand lineage and quality  

### Skills to Emphasize / Refresh
⚠️ **Apache Superset** – No direct mention on resume; this is a *required* tool. **Prepare to learn quickly and highlight transferable dashboard design knowledge from Redshift/analytics exposure.**  
⚠️ **Power BI** – Not mentioned; required expertise in DAX, Power Query, data modeling. **This is a gap; prepare concrete examples of how SQL/ETL knowledge transfers.**  
⚠️ **Excel Advanced** – Resume doesn't detail advanced formulas, pivot tables, Power Query. **Emphasize automation scripting and data preparation instead.**  
⚠️ **Statistical Analysis** – You have a Master's in Data Science (expected May 2026); **highlight statistical thinking, hypothesis testing, and analytical rigor.**  

### Messaging Strategy
- **Reposition your seniority:** You're overqualified as a pure data analyst—frame this as a **strategic career shift** from infrastructure/engineering to analytics and storytelling.
- **Bridge the tools gap:** Superset and Power BI are *visual* tools built on SQL/data modeling—both of which you excel at. Learn the UI and features before the interview.
- **Lead with communication:** Your experience collaborating with data science and BI teams shows you *understand* what analysts need. Emphasize translation of technical work into business value.

---

## 🎯 TECHNICAL QUESTIONS (50)

### SQL & Database Fundamentals (8 questions)
1. Walk me through your approach to optimizing a slow-running SQL query. What tools do you use to identify bottlenecks?
2. Explain the difference between INNER JOIN, LEFT JOIN, and FULL OUTER JOIN with a real-world example.
3. When would you use a CTE (Common Table Expression) instead of a subquery? What are the trade-offs?
4. How do you use window functions (ROW_NUMBER, RANK, LAG) in analytical queries? Give an example.
5. Describe a scenario where you'd use aggregation functions (SUM, AVG, COUNT) combined with GROUP BY and HAVING.
6. What is query plan analysis, and how have you used it to improve performance?
7. Explain indexing strategies. When would you create an index vs. avoid it?
8. How do you handle missing data or NULL values in SQL queries? Walk through your approach.

### Python for Data Analysis (8 questions)
9. Compare pandas DataFrames vs. SQL for data transformation. When would you choose one over the other?
10. How do you handle large datasets that don't fit in memory? What pandas functions help optimize this?
11. Walk me through your process for data cleaning: handling duplicates, outliers, and inconsistent formats.
12. Explain the difference between map(), apply(), and applymap() in pandas. When would you use each?
13. How would you validate data quality in Python? Give an example from your work.
14. Describe a time you used NumPy or SciPy for statistical analysis. What was the business impact?
15. How do you create reproducible data pipelines in Python? What tools do you use?
16. What's your approach to error handling and logging in Python scripts?

### ETL & Data Pipelines (6 questions)
17. Walk me through the architecture of a data pipeline you've built. How do you ensure idempotency and data consistency?
18. Explain the bronze-silver-gold (medallion) architecture. Why is this approach valuable?
19. How do you handle schema evolution in long-running pipelines?
20. Describe your experience with Airflow DAGs. How do you handle failures and retries?
21. What's the difference between batch and real-time ETL? When would you use each?
22. How do you monitor and alert on data pipeline failures in production?

### Data Visualization & Analytics Tools (10 questions)
23. Describe your experience designing dashboards. What principles do you follow for effective visualization?
24. When would you use a bar chart vs. a line chart vs. a scatter plot? Give real examples.
25. How do you handle drill-down and filtering in dashboards? What user experience considerations matter?
26. Explain how you'd integrate a SQL database with a BI tool (like Superset or Power BI).
27. What is a calculated field or measure in a BI tool? How would you create one?
28. How do you balance real-time data refreshes with report performance?
29. Describe a time you identified a data quality issue through visualization. How did you fix it?
30. What makes a good KPI dashboard vs. a bad one?
31. How do you handle drill-through and drill-down navigation in dashboards?
32. Explain cardinality issues in BI tools and how you'd resolve them.

### Data Modeling & Architecture (6 questions)
33. Walk me through your approach to designing a star schema or dimensional model.
34. What's the difference between normalization and denormalization? When would you use each?
35. How do you design fact and dimension tables? Give an example.
36. Explain slowly changing dimensions (SCD). How would you implement SCD Type 1, 2, or 3?
37. What is a data mart, and how does it differ from a data warehouse?
38. How do you design for scalability when building analytics tables?

### Cloud & Infrastructure (6 questions)
39. Describe your experience with AWS for analytics (S3, Redshift, Glue, etc.). How would this apply to a BI role?
40. Explain the difference between row-based and columnar databases. When is each useful?
41. How do you approach data security and access control in cloud analytics platforms?
42. What's your experience with data versioning and managing data lineage?
43. How do you think about infrastructure costs in analytics projects?
44. Describe a time you automated infrastructure setup. How would that apply to analytics tools?

### Practical Data Analysis & Problem-Solving (6 questions)
45. Walk me through a time you discovered a metric discrepancy between two data sources. How did you investigate and resolve it?
46. Describe your approach to A/B testing or statistical experiment analysis.
47. How do you validate assumptions in data before building reports on it?
48. Walk me through how you'd approach a request: "We need a dashboard showing customer churn trends."
49. Tell me about a time you had to communicate a counterintuitive finding to non-technical stakeholders.
50. How do you stay current with data analytics trends and tools?

---

## 🤝 BEHAVIORAL & GET-TO-KNOW-YOU QUESTIONS (25)

### Career Trajectory & Motivation (5 questions)
1. Your background is in data engineering and infrastructure—what attracts you to a data analyst/BI role?
2. Tell me about a time you had to learn a new tool or technology quickly. How did you approach it?
3. You have experience with large-scale pipelines—how would you approach working with smaller, faster-moving datasets in an analytics context?
4. What aspects of your current/previous roles have you enjoyed most? Where do you see yourself in 2 years?
5. Why are you interested in this role at this company specifically?

### Collaboration & Communication (5 questions)
6. Describe a time you worked with a non-technical stakeholder. How did you explain complex data concepts?
7. Tell me about a time you had conflicting priorities from different teams. How did you handle it?
8. Your resume mentions cross-team collaboration with data science and BI teams—walk me through a specific project. What was your role?
9. Have you ever had to push back on a data request? When and why?
10. Tell me about a time you received critical feedback about your work. How did you respond?

### Problem-Solving & Analytical Thinking (5 questions)
11. Tell me about a time you identified an inefficiency in a process and fixed it.
12. Describe a time you approached a problem from first principles rather than following a standard approach.
13. Walk me through your debugging process when you encounter an error in a data query or script.
14. Tell me about the most complex analysis or insight you've discovered. What was the impact?
15. How do you handle uncertainty in data or ambiguous requirements?

### Ownership & Initiative (3 questions)
16. Tell me about a time you went above and beyond to deliver value to your stakeholders.
17. Describe a project where you took ownership from start to finish. What were the challenges?
18. Tell me about a time you proposed a new approach or tool to improve your team's work.

### Learning & Growth (4 questions)
19. What's a skill you're currently developing or want to develop?
20. Tell me about a time you failed at something. What did you learn?
21. How do you stay organized when juggling multiple priorities and stakeholders?
22. Describe your approach to documentation and knowledge sharing.

### Cultural Fit (3 questions)
23. What does a healthy team dynamic look like to you?
24. How do you prefer to receive feedback?
25. Tell me about a time you had to adapt to a different work style or environment.

---

## 📋 PREPARATION CHECKLIST

### Before the Interview
- [ ] Deep dive into **Apache Superset documentation** and **build a simple dashboard** (1–2 hours)
- [ ] Review **Power BI fundamentals** (DAX basics, Power Query) via Microsoft Learn (2–3 hours)
- [ ] Prepare **2–3 concrete project examples** from your resume that showcase SQL, Python, and analytics thinking
- [ ] Practice explaining **engineering concepts to business stakeholders** (this is your strength—lean on it)
- [ ] Research the **company's analytics stack and recent initiatives** (if available)
- [ ] Prepare questions about the role, team, and success metrics

### Mock Interview Practice
- Record yourself answering 5–10 technical questions aloud
- Practice the STAR method for behavioral questions
- Time yourself on explanations (aim for 2–3 minutes per answer)

### Day Of
- Bring examples of dashboards, queries, or analyses you're proud of
- Show enthusiasm about learning Superset/Power BI
- Ask clarifying questions—it demonstrates analytical thinking

---

## 🎓 QUICK REFERENCE: Bridge Your Skills to This Role

| Your Strength | JD Requirement | How to Frame It |
|---|---|---|
| PySpark, large-scale data processing | Python for data manipulation | "I've built production pipelines; BI analytics is a natural extension of that analytical mindset." |
| Redshift, data warehouse design | SQL optimization, database integration | "I've designed schemas for analytics; I understand query performance from both sides." |
| Airflow orchestration | ETL workflows, data pipelines | "I've built and monitored production pipelines; I understand what clean data requires." |
| AWS, Terraform, infrastructure | Cloud platforms, data governance | "I understand infrastructure requirements for scalable analytics systems." |
| Great Expectations, data validation | Data quality principles, data governance | "I've implemented frameworks to catch data issues early—critical for reliable reporting." |
| Master's in Data Science (in progress) | Statistical analysis, analytical rigor | "I'm bringing quantitative rigor to analytics; hypothesis testing is core to my approach." |