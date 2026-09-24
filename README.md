# US Visa Approval — Exploratory Data Analysis
Exploratory data analysis on a US work visa applications dataset (25,480 records, 12 features), identifying the key factors that influence visa case approval.

## Objective
Understand which applicant, employer, and job characteristics (education, experience, wage, company size/age, region) are associated with visa approval (`Certified`) vs. denial (`Denied`), and turn the findings into clear, actionable insights.

## Dataset
- **Rows:** 25,480 | **Columns:** 12
- **Target variable:** `case_status` (Certified / Denied)
- **Features:** continent, education_of_employee, has_job_experience, requires_job_training, no_of_employees, yr_of_estab, region_of_employment, prevailing_wage, unit_of_wage, full_time_position

## Tools & Libraries
`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn`

## Workflow
1. **Data Understanding**
   - Reviewed shape, data types, and summary statistics
   - Checked for missing values and duplicate records

2. **Data Cleaning**
   - Handled missing values (including targeted median imputation for `prevailing_wage`)
   - Removed duplicate rows

3. **Univariate Analysis**
   - Distribution of case status, education level, full-time position, and job experience

4. **Bivariate Analysis**
   - Education vs. visa status
   - Job experience vs. visa status
   - Number of employees vs. visa status
   - Prevailing wage vs. visa status

5. **Geographical Analysis**
   - Approval outcomes by region of employment

6. **Feature Engineering**
   - Derived a new `age_of_company` feature from `yr_of_estab`
   - Analyzed company age vs. case status

7. **Correlation Analysis**
   - Correlation heatmap across key numerical features (employees, company age, wage)

## Key Insights
- Out of 25,480 applications, **17,018 were Certified and 8,462 were Denied** (~67% approval rate).
- **Full-time positions** show higher approval rates than part-time roles.
- **Higher prevailing wages** are associated with a greater likelihood of approval.
- **Job experience** has a strong positive relationship with certification outcomes.
- **Education level** of the employee visibly affects visa decisions.
- **Larger and older companies** tend to show better approval outcomes than smaller/newer ones.

## Skills Demonstrated
Data cleaning & deduplication · Univariate & bivariate analysis · Geographical/segment analysis · Feature engineering · Correlation analysis · Translating EDA findings into business insights
---
*This project is part of my Data Analytics portfolio.*
