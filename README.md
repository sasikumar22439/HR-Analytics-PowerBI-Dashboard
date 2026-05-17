# 📊 HR Analytics Dashboard – Power BI Project

## 📌 Project Overview

The HR Analytics Dashboard is an interactive Business Intelligence solution developed using Power BI to analyze employee attrition trends and workforce data. The dashboard helps HR teams and management understand employee behavior, identify attrition patterns, and make data-driven decisions to improve employee retention and organizational performance.

This project focuses on transforming raw HR data into meaningful insights using data visualization, KPI tracking, and analytical reporting techniques.

---

# 🎯 Project Objectives

- Analyze employee attrition trends
- Monitor workforce demographics
- Identify departments with high attrition
- Track salary-based attrition patterns
- Improve HR decision-making through data insights
- Build an interactive and visually appealing dashboard

---

# 🧰 Tools & Technologies Used

- Power BI
- Microsoft Excel
- SQL
- DAX (Data Analysis Expressions)
- Data Cleaning
- Data Visualization
- Business Intelligence Reporting

---

# 📁 Dataset Information

The dataset contains detailed HR employee records including:

- Employee ID
- Age
- Gender
- Department
- Job Role
- Education Field
- Marital Status
- Monthly Income
- Salary Slab
- Years at Company
- Attrition Status
- Job Satisfaction
- Work Experience

---

# 🏗 Project Workflow

1. Data Collection  
2. Data Cleaning & Transformation  
3. Data Modeling  
4. DAX Measure Creation  
5. Dashboard Design  
6. KPI Development  
7. Insight Generation  
8. Business Recommendations

---

# 📊 Dashboard KPIs

| KPI | Value |
|------|------|
| Total Employees | 1470 |
| Attrition Count | 237 |
| Attrition Rate | 16.08% |
| Average Age | 37 |
| Average Salary | 6.50K |
| Average Years at Company | 7 |

---

# 📈 Dashboard Features

## ✅ Employee Attrition Analysis
Analyzes overall employee attrition across the organization.

## ✅ Department-wise Attrition
Tracks attrition trends across:
- Sales
- Human Resources
- Research & Development

## ✅ Age Group Analysis
Identifies attrition distribution among different employee age groups.

## ✅ Salary Slab Analysis
Analyzes attrition patterns based on employee salary ranges.

## ✅ Education Field Analysis
Displays employee attrition based on educational backgrounds.

## ✅ Gender-based Analysis
Provides workforce distribution and attrition insights by gender.

## ✅ Years at Company Analysis
Tracks attrition based on employee experience within the company.

---

# 🧮 DAX Measures Used

## Attrition Rate

```DAX
Attrition Rate =
DIVIDE(
    COUNT(Employee[Attrition]),
    COUNT(Employee[EmployeeID])
) * 100
```

## Total Employees

```DAX
Total Employees =
COUNT(Employee[EmployeeID])
```

## Average Salary

```DAX
Average Salary =
AVERAGE(Employee[MonthlyIncome])
```

---

# 🔍 Key Insights

- Employees aged 26–35 show the highest attrition.
- Sales department has significant employee turnover.
- Employees with lower salary slabs have higher attrition rates.
- Attrition is higher among employees with fewer years at the company.
- Life Sciences and Medical education fields show increased attrition.

---

# 💡 Business Recommendations

- Improve employee engagement programs.
- Review compensation strategies for lower salary groups.
- Focus retention strategies on high attrition departments.
- Enhance career growth opportunities for early-stage employees.
- Strengthen employee satisfaction initiatives.

---

# 🧠 Skills Demonstrated

- Data Analysis
- Dashboard Development
- Data Visualization
- DAX Calculations
- HR Analytics
- Business Intelligence
- Insight Generation
- Data Cleaning
- Problem Solving
- Analytical Thinking

---

# 📷 Dashboard Preview

## Main Dashboard

![Dashboard Preview](dashboard.png)

---

# 📚 What I Learned

Through this project, I improved my skills in:
- Power BI Dashboard Development
- DAX Functions
- HR Data Analysis
- KPI Reporting
- Data Storytelling
- Business Insight Generation
- Interactive Visualization Design

---

# ⚡ Challenges Faced

- Handling inconsistent HR data
- Building optimized DAX calculations
- Designing user-friendly dashboard layouts
- Creating meaningful KPI metrics
- Improving dashboard performance and readability

---

# 🚀 Future Enhancements

- Predictive Attrition Analysis using Machine Learning
- SQL Database Integration
- Real-time Dashboard Updates
- Power BI Service Deployment
- Advanced HR KPI Monitoring
- Role-Level Security Implementation

---

# 📂 Files Included

| File Name | Description |
|-----------|-------------|
| HR_Analytics.pbix | Power BI Dashboard File |
| employee_data.xlsx | Dataset Used |
| dashboard.png | Dashboard Screenshot |
| README.md | Project Documentation |

---

# 💼 Use Case

This dashboard can be used by:
- HR Teams
- Business Analysts
- Management Teams
- Recruiters
- Data Analysts

to monitor employee trends, reduce attrition, and support workforce planning.

---

# 🔑 Keywords

Power BI, HR Analytics, Data Analysis, Dashboard Development, Business Intelligence, Data Visualization, DAX, SQL, Excel Analytics, Employee Attrition Analysis, Interactive Dashboard

---

# 👨‍💻 Author

## Sasi Kumar

### Roles
- Data Analyst
- Power BI Developer
- Python Developer
- Data Engineering Enthusiast

---

# 🔗 Connect With Me

## GitHub
https://github.com/sasikumar22439

## LinkedIn
www.linkedin.com/in/puletipalli-sasi-kumar-1b30b8338

---

# ⭐ Project Highlights

✔ Interactive Dashboard  
✔ HR Analytics Reporting  
✔ KPI Monitoring  
✔ Business Intelligence Solution  
✔ Real-world Dataset Analysis  
✔ Data-driven Decision Support  
✔ Professional Dashboard Design  

---

# 📌 Conclusion

The HR Analytics Dashboard provides meaningful insights into employee attrition trends and workforce behavior using Power BI visualizations and analytical reporting techniques. The project demonstrates strong skills in data analysis, dashboard development, business intelligence, and insight generation, helping organizations make informed HR decisions and improve employee retention strategies.

```

