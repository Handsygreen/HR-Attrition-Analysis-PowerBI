# HR-Attrition-Analysis-PowerBI
This Power BI project provides a comprehensive visual analysis of employee attrition across departments, age groups, gender, job roles, and education fields. The goal is to empower HR decision-makers with data-driven insights to reduce attrition and improve workforce management.


📁 **Dataset Summary**
The dashboard is based on a cleaned and structured HR dataset which includes fields such as:

Employee ID

Age

Gender

Department

Job Role

Education Field

Attrition Status

Job Satisfaction

Performance Rating

Salary, etc.

All fields were cleaned using Power Query functions like Text.Trim, Text.Proper, and Replace Errors, ensuring consistency and integrity in reporting.

📊 **Key Metrics and KPIs**

Total Employees: 1470

Current Employees: 1233

Attrition Count: 237

Attrition Rate: 16.1%

Average Age: 37 years


 **##Report Views**
🔸 **Page 3: Executive HR Summary** 

**Visuals:**

📌 KPI Cards: Quick summary of workforce and attrition metrics.

📊 **Attrition by Department:** Pie chart showing % distribution (e.g., R&D: 5.1%, Sales: 56.1%).

📉 **Attrition by Age Group and Gender:** Column chart showing highest attrition in the 25–34 age band.

📈 **Attrition by Education Field:** Bar chart highlighting that most attrition occurs among employees from Life Sciences and Medical backgrounds.

🔸 Page 4: **Detailed Attrition Insights**

**Visuals:**

📊 Attrition Count by Job Satisfaction & Role: Matrix table showing breakdown by satisfaction level.

📉 Gender Count by Education Field and Age: Line chart trend.

📊 Employee Count by Role and Gender: Stacked bar chart comparing roles.

🧮 Attrition by Age Group and Gender: Donut charts for different age bands:

Under 25: 52.63% Female

25–34: Highest attrition (112)

Over 55: Lowest attrition (49)

These visuals help pinpoint where attrition is most concentrated demographically and behaviorally.

🛠️ Power BI Features Used
Power Query Editor: for data transformation and cleaning.

DAX Measures:

Attrition Rate (%) = DIVIDE(Attrition Count, Total Employees)

Average Age = AVERAGE(Employee[Age])

Custom Visuals:

Donut Charts

KPI Tiles

Clustered Column Charts

Matrix Tables
