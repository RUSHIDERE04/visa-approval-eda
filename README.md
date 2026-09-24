# US Visa Application — Exploratory Data Analysis
Exploratory data analysis on a US work visa applications dataset (25,480 records, 12 features), identifying applicant, job, employer, and regional characteristics associated with visa case outcomes.

## Objective
Understand which applicant, employer, job, and regional characteristics are associated with visa case outcomes (`Certified` vs. `Denied`) and summarize the findings through exploratory analysis and visualizations.

## Dataset
* **Rows:** 25,480
* **Columns:** 12
* **Target variable:** `case_status` (`Certified` / `Denied`)
* **Features:** `continent`, `education_of_employee`, `has_job_experience`, `requires_job_training`, `no_of_employees`, `yr_of_estab`, `region_of_employment`, `prevailing_wage`, `unit_of_wage`, `full_time_position`

## Tools & Libraries
`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn`

## Workflow

1. **Data Understanding**
   * Reviewed shape, data types, and summary statistics
   * Checked for missing values and duplicate records

2. **Data Cleaning**
   * Handled missing values, including targeted median imputation for `prevailing_wage`
   * Removed duplicate rows

3. **Univariate Analysis**

   * Analyzed distributions of case status, education level, full-time position, and job experience

4. **Bivariate Analysis**
   * Education vs. case status
   * Job experience vs. case status
   * Number of employees vs. case status
   * Prevailing wage vs. case status

5. **Geographical Analysis**
   * Analyzed certification outcomes across regions of employment

6. **Feature Engineering**
   * Derived an `age_of_company` feature from `yr_of_estab`
   * Analyzed company age in relation to case status

7. **Correlation Analysis**
   * Examined correlations among key numerical features such as employees, company age, and prevailing wage

## Key Insights
* Out of 25,480 applications, **17,018 were Certified and 8,462 were Denied** (~67% Certified).
* Full-time positions showed different certification rates compared with part-time positions.
* Certification outcomes varied across different prevailing wage levels.
* Certification outcomes varied across applicants with and without prior job experience.
* Certification rates differed across employee education levels.
* Certification outcomes varied across company size and company age groups.

## Skills Demonstrated
**Data Cleaning & Deduplication · EDA · Data Visualization · Geographical/Segment Analysis · Feature Engineering · Correlation Analysis · Insight Generation**

*This project is part of my Data Analytics portfolio.*
