# HR Analytics – Employee Attrition Analysis

## 📌 Project Overview
Employee attrition is a critical challenge for organizations, impacting productivity, costs, and workforce stability. This project focuses on analyzing employee attrition data to identify key trends, patterns, and factors influencing employee turnover. The goal is to provide actionable insights that can support HR leadership in improving employee retention strategies.

---

## 🎯 Business Objective
The HR Director observed an increase in employee attrition and seeks to understand the underlying causes. This analysis aims to:
- Calculate the employee attrition rate
- Identify trends and patterns related to attrition
- Analyze the impact of factors such as age, experience, income, department, and job satisfaction on employee attrition
- Provide data-driven insights and recommendations to reduce attrition

---

## 📊 Dataset Overview
- **Dataset**: HR Employee Attrition Data  
- **Granularity**: Employee-level data  
- **Content**: Demographics, compensation, job role details, satisfaction metrics, and attrition status  

The dataset contains both numerical and categorical variables relevant to workforce analysis.

---

## 🧾 Column Description

| Column Name | Category | Description |
|------------|----------|-------------|
| Age | Numerical | Age of the employee |
| Attrition |Categorical | Indicates whether the employee left the company |
| BusinessTravel | Categorical | Frequency of business travel |
| DailyRate |  Numerical | Daily wage rate |
| Department | Categorical | Department the employee belongs to |
| DistanceFromHome| Numerical | Distance between home and workplace |
| Education |  Numerical | Education level |
| EducationField | Categorical | Field of education |
| EmployeeCount | Numerical | Employee count (constant) |
| EmployeeNumber |Numerical | Unique employee identifier |
| EnvironmentSatisfaction | Numerical | Satisfaction with work environment |
| Gender | object |Gender of the employee |
| HourlyRate | Numerical | Hourly wage |
| JobInvolvement | Numerical | Level of job involvement |
| JobLevel | Numerical | Job level within the company |
| JobRole |  Categorical | Role/designation |
| JobSatisfaction |  Numerical | Job satisfaction score |
| MaritalStatus | Categorical | Marital status |
| MonthlyIncome | Numerical | Monthly income |
| MonthlyRate |  Numerical | Monthly compensation rate |
| NumCompaniesWorked | Numerical | Number of companies previously worked at |
| Over18 |Categorical | Whether employee is over 18 |
| OverTime |Categorical | Whether employee works overtime |
| PercentSalaryHike |  Numerical | Percentage salary hike |
| PerformanceRating |  Numerical | Performance rating |
| RelationshipSatisfaction | Numerical | Relationship satisfaction score |
| StandardHours |  Numerical | Standard working hours |
| StockOptionLevel | Numerical | Stock option level |
| TotalWorkingYears |  Numerical | Total years of experience |
| TrainingTimesLastYear | Numerical | Training sessions last year |
| WorkLifeBalance | Numerical | Work-life balance rating |
| YearsAtCompany | Numerical | Years spent at the company |
| YearsInCurrentRole | Numerical | Years in current role |
| YearsSinceLastPromotion |  Numerical | Years since last promotion |
| YearsWithCurrManager | Numerical | Years with current manager |

---

## 🔍 Exploratory Data Analysis (Python)
Exploratory Data Analysis (EDA) was conducted using Python to:
- Understand data structure and column types
- Separate numerical and categorical features
- Check for missing values
- Analyze distributions and summary statistics
- Identify early trends related to attrition

📘 **Notebook**: `notebooks/HR_Attrition_EDA.ipynb`

---

## 📈 Tableau Dashboards
Interactive dashboards were built in Tableau to visually explore employee attrition trends and relationships.

---

### 📊 Dashboard 1: Employee Demographics & Compensation

![Dashboard 1](tableau dashboard.png)

**Graph 1: Employee Count by Experience**  
This visualization shows employee count by years spent at the company. Attrition is highest during the initial years of employment, despite a large number of employees. As tenure increases, attrition significantly decreases, indicating higher employee stability over time.

**Graph 2: Employee Count by Monthly Income**  
This histogram shows employee distribution across income bands (₹2,000 bins). Employees earning between ₹2,000 and ₹6,000 per month exhibit the highest attrition, suggesting income may be a key driver of turnover.

**Graph 3: Age-wise Employee Count**  
Employees are grouped into age bands (18–25, 26–35, 36–45, 46–55, 55+). The 26–35 and 36–45 age groups have the highest employee concentration and also experience the highest attrition rates.

**Graph 4: Average Monthly Income by Age Group**  
Employees aged 46–55 earn the highest average income, followed by those above 55. Although the 26–35 age group earns close to the company average, this group still experiences the highest attrition, indicating that factors beyond income may influence turnover.

**Graph 5: Attrition by Department**  
R&D has the lowest attrition rate, while Sales and HR show significantly higher attrition (around 20%). This highlights potential role-specific challenges and the need for department-focused retention strategies.

**Graph 6: Job Satisfaction by Attrition**  
A clear inverse relationship exists between job satisfaction and attrition. Higher job satisfaction corresponds to lower attrition rates, emphasizing satisfaction as a key determinant of employee retention.

---

## 💡 Key Business Insights
- Attrition is highest during the early years of employment
- Lower-income employees show a greater tendency to leave
- Employees aged 26–35 represent the most vulnerable attrition group
- Sales and HR departments require focused retention efforts
- Job satisfaction plays a critical role in employee retention

---

## ✅ Recommendations
- Introduce structured career growth and compensation reviews for early-tenure employees
- Enhance engagement and retention initiatives for employees aged 26–35
- Conduct department-specific interventions in Sales and HR
- Improve job satisfaction through feedback mechanisms, role clarity, and work-life balance programs

- Include time-based attrition trends
- Perform deeper satisfaction and engagement analysis
