# IBM HR Attrition Analytics Dashboard

## 📌 Task Overview
**Task 03 — Interactive Visualization | SkillCraft Technology Internship**

Built an interactive HR analytics dashboard using Tableau Public on the 
IBM HR Employee Attrition dataset to answer:
> *"Why are employees leaving?"*

---

## 🔗 Live Dashboard
👉 [View on Tableau Public](https://public.tableau.com/app/profile/mneddula.reena/viz/IBMHRAttritionAnalyticsDashboard_17794517359880/IBMHRAttritionDashboard?publish=yes)
---

## 📁 Dataset
- **Source:** IBM HR Analytics Employee Attrition Dataset
- **Platform:** [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Records:** 1,470 employees
- **Key Columns:** Attrition, Department, Age, JobSatisfaction, 
  MonthlyIncome, OverTime, YearsAtCompany, Gender

---

## 📈 Dashboard Features

| Visual | Chart Type | Insight |
|---|---|---|
| KPI Cards | Text | Total Employees, Attrition Count, Attrition Rate %, Avg Years in Company |
| Attrition by Department | Pie Chart | Which department loses the most people |
| Attrition by Age Group | Treemap | Which age group has highest attrition volume |
| Attrition by Gender | Stacked Bar | Gender-wise attrition split |
| Job Satisfaction by Role | Bar Chart | Roles with lowest average satisfaction among attrition employees |
| Overtime vs Attrition | Stacked Bar | Impact of overtime on attrition |

**Interactive Filters:** Department · Age Group · OverTime

---

## 🔍 Key Insights

1. **Research & Development** has the highest attrition count — 133 out of 237 total attritions, though **Sales** has the highest attrition *rate* at ~20.6% (92 out of 446 employees)
2. **Age group 26–35** records the highest attrition volume with 116 employees leaving — nearly half of all attritions
3. **Overtime employees** are 3.4× more likely to leave — 127 out of 416 OT workers left (30.5%) vs 110 out of 1,054 non-OT workers (10.4%)
4. **Human Resources** role has the lowest average job satisfaction score (2.17) among employees who left, followed by Managers (2.40)
5. **Male employees** account for 63% of attritions (150 out of 237) vs Female at 37% (87 out of 237)
6. **Overall attrition rate** is 16.12% across 1,470 employees with an average tenure of 7.01 years

---

## 💡 HR Recommendations

Based on the analysis, three priority actions emerge for the HR team:

- **Address overtime burnout** — with a 30.5% attrition rate among overtime employees vs 10.4% for others, workload redistribution or compensation review in high-OT departments is critical
- **Focus retention on the 26–35 age band** — this group accounts for 49% of all attritions; targeted career development programs and promotion pathways may improve retention
- **Review Sales department compensation** — Sales has the highest attrition rate (~20.6%) combined with below-average job satisfaction, suggesting a salary or growth structure issue

---

## 🛠️ Tools Used
- **Tableau Public** — Dashboard & Visualization
- **IBM HR Dataset (CSV)** — Data Source
- **Kaggle** — Dataset Platform

---
## 📂 Repository Contents

| File | Description |
|---|---|
| `IBM_HR_Attrition_Dashboard.twbx` | Tableau workbook file (packaged with data) |
| `HR_Employee_Attrition_Dataset.csv` | Raw dataset — 1,470 employees, 35 columns |
| `01_Dashboard.png` | Full dashboard screenshot |
| `02_Dept_Attrition_PieChart.png` | Attrition by Department chart |
| `03_AgeGroup_Attrition_Treemap.png` | Attrition by Age Group treemap |
| `04_Gender_Attrition_BarChart.png` | Attrition by Gender chart |
| `05_JobSatisfaction_BarChart.png` | Job Satisfaction by Role chart |
| `06_Overtime_Attrition_BarChart.png` | Overtime vs Attrition chart |
| `README.md` | Project documentation |
