## Employee Turnover Driver Analysis - A Business Intelligence Portfolio

**Author:** Ahmad Fauzi R

---
### 1. Problem Statement

Recent HR analysis revealed an alarming spike in employee turnover, which has now surpassed **16%**. This attrition is not uniform; it disproportionately affects critical areas, causing a significant talent drain in key revenue-generating teams and the company's core innovation hubs.

The HR department possesses a wealth of employee data, from demographics and compensation to satisfaction scores. However, this information is trapped in static spreadsheets, making it impossible to identify the hidden patterns and root causes driving employees to leave.

A dynamic business intelligence dashboard was required to transform this raw data into actionable insights, enabling leadership to make informed, strategic decisions to improve retention.

---
### 2. The Final Dashboard

This interactive, single-page dashboard was designed to provide an executive-level summary, allowing stakeholders to view key metrics (KPIs) and identify the most statistically significant drivers of turnover at a glance.

[[Screenshot HR - Turn Over.png]]

---
### 3. Key Insights & Findings

Analysis of the data revealed several clear, actionable drivers behind employee attrition:

- **Overtime is the Strongest Predictor:** The most significant insight from the AI analysis is that employees who work overtime (`OverTime = Yes`) are **2.93 times more likely** to leave than their peers. This is, by far, the largest single risk factor.
    
- **Burnout is a Tangible Factor:** The next two largest drivers are low `Work-Life Balance` and low `Environment Satisfaction`. Employees feeling their work-life balance is poor (a score of 1) are **2.05x more likely** to resign.
    
- **The Problem is Concentrated in Specific Roles:** Turnover is not evenly distributed. The highest risk is concentrated in **Sales Representative** and **Laboratory Technician** roles, suggesting systemic issues (likely related to workload or management) within those specific teams.
    
- **It's Not (Just) About the Money:** Further analysis showed that while salary is important, **job satisfaction and environment are stronger drivers than compensation**. High-earning employees are still at high risk of leaving if they are dissatisfied with their work environment and life balance.
    

---
### 4. Actionable Recommendations

Based on these findings, three strategic recommendations are proposed for the HR department:

1. **Launch a Workload & Overtime Audit:** Immediately review overtime policies and workload expectations, especially for the two highest-risk roles: _Sales Representatives_ and _Laboratory Technicians_.
2. **Prioritize Proactive "Stay Interviews":** Instead of relying on "exit interviews" when it's too late, implement proactive "stay interviews" targeting employees with low `Work-Life Balance` and `Environment Satisfaction` scores to identify and solve issues before they resign.
3. **Shift Retention Focus from Compensation to Culture:** The data clearly shows that raising salaries alone will not solve the turnover problem. Investment should be focused on improving work culture, management training, and ensuring reasonable workloads to see the best ROI on retention.

---
### 5. Tools Used

- **Power BI**
    - **Power Query:** For data extraction, transformation, and loading (ETL).
    - **DAX:** For creating custom calculations (e.g., `Turnover Rate`).
    - **AI Visuals (Key Influencers):** For statistical analysis to identify key drivers.
