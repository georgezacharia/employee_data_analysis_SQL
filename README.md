# Employee Data Analysis Report

## Project Objective
This project aims to analyze employee data to gain insights into various aspects of employee performance and demographics. The goal is to uncover trends, correlations, and patterns that can inform HR strategies and improve organizational decision-making.

## Columns
- `employee_id`: Unique identifier for each employee
- `department`: Department in which the employee works
- `region`: Geographical region of the employee
- `education`: Level of education attained by the employee
- `gender`: Gender of the employee
- `recruitment_channel`: Source through which the employee was recruited
- `no_of_trainings`: Number of trainings attended by the employee
- `age`: Age of the employee
- `previous_year_rating`: Performance rating from the previous year
- `length_of_service`: Number of years the employee has been with the company
- `KPIs_met_more_than_80`: Number of KPIs met more than 80%
- `awards_won`: Number of awards won by the employee
- `avg_training_score`: Average score from training sessions

## Tools Used
- **Python**: Data cleaning, analysis, and visualization
- **Pandas**: Data manipulation and analysis
- **SQL**: Data querying and aggregation
- **Matplotlib/Seaborn**: Data visualization

## Analysis and Insights

### 1. Employee Distribution by Department
**Query Result:**
- Sales & Marketing: 5458 employees
- Operations: 3524 employees
- Procurement: 2240 employees
- Technology: 2199 employees
- Analytics: 1697 employees
- HR: 833 employees
- Finance: 802 employees
- R&D: 332 employees
- Legal: 332 employees

**Interpretation:**
Sales & Marketing has the highest number of employees, indicating it is a major operational area. Departments like R&D and Legal have fewer employees, which could suggest a more specialized or less expansive function.

**Real-World Application:**
- **Resource Allocation**: Adjust staffing levels or resource allocation based on department size.
- **Strategic Planning**: Focus recruitment efforts on departments with fewer employees if expansion is needed.

### 2. Average Age of Employees by Department
**Query Result:**
- Procurement: 36.17 years
- Operations: 36.15 years
- Technology: 35.03 years
- Sales & Marketing: 34.63 years
- HR: 34.25 years
- Legal: 33.75 years
- R&D: 32.89 years
- Finance: 32.60 years
- Analytics: 32.41 years

**Interpretation:**
The average age of employees varies by department, with HR and Analytics having the youngest average age. This could reflect different career stages or employee demographics in each department.

**Real-World Application:**
- **Succession Planning**: Develop strategies to manage age diversity and plan for retirements.
- **Recruitment Strategies**: Tailor recruitment efforts to attract younger talent where needed.

### 3. Gender Distribution Across Regions
**Query Result:**
- Example: Region 1 has 132 male and 42 female employees.

**Interpretation:**
The gender distribution varies by region, which might indicate regional differences in gender representation or recruitment practices.

**Real-World Application:**
- **Diversity Initiatives**: Implement targeted diversity and inclusion programs based on regional gender imbalances.
- **Policy Development**: Adjust policies to address regional disparities in gender distribution.

### 4. Impact of Education Level on Average Training Scores
**Query Result:**
- Below Secondary: 65.90
- Masters & above: 64.13
- Bachelors: 63.03
- None: 58.29

**Interpretation:**
Employees with lower education levels tend to score higher on average training assessments, which could suggest a higher training effectiveness or different training needs based on education.

**Real-World Application:**
- **Training Programs**: Customize training programs to address educational background and maximize effectiveness.
- **Educational Support**: Offer educational support to improve training outcomes.

### 5. Analysis of KPI Achievement by Length of Service
**Query Result:**
- KPI achievement varies with length of service, showing higher rates in the middle years and lower rates at the extremes.

**Interpretation:**
Employees with mid-range length of service tend to have higher KPI achievement rates, which might suggest that experience contributes to KPI success.

**Real-World Application:**
- **Performance Reviews**: Use length of service data to tailor performance review criteria.
- **Career Development**: Develop career development programs to enhance KPI achievement at different service stages.

### 6. Department-wise Analysis of Employees with Awards
**Query Result:**
- Technology: 2.64% of employees won awards
- Sales & Marketing: 2.20%
- HR: 1.68%

**Interpretation:**
Departments like Technology and Sales & Marketing have higher award percentages, indicating a potentially higher recognition of performance.

**Real-World Application:**
- **Recognition Programs**: Enhance recognition programs in departments with lower award percentages.
- **Benchmarking**: Use award data to benchmark performance and set departmental goals.

### 7. Impact of Number of Trainings on KPI Achievement
**Query Result:**
- Higher number of trainings does not always correlate with higher KPI achievement.

**Interpretation:**
The relationship between the number of trainings and KPI achievement is inconsistent, suggesting that training alone may not be sufficient for KPI success.

**Real-World Application:**
- **Training Effectiveness**: Evaluate the effectiveness of training programs and their impact on KPIs.
- **Customized Training**: Develop more targeted training programs based on KPI needs.

### 8. KPI Achievement Rate by Region
**Query Result:**
- Region 4 has the highest KPI achievement rate at 0.48.

**Interpretation:**
Regional differences in KPI achievement rates indicate varying levels of performance across locations.

**Real-World Application:**
- **Regional Performance Analysis**: Focus on regions with lower KPI achievement rates for performance improvement initiatives.
- **Resource Allocation**: Allocate resources based on regional performance metrics.

### 9. Correlation Between Awards Won and Length of Service
**Query Result:**
- Correlation shows varied award counts across different lengths of service.

**Interpretation:**
Employees with shorter lengths of service show higher counts of awards in some cases, which may reflect recognition of outstanding early performance.

**Real-World Application:**
- **Reward Systems**: Adjust reward systems to recognize both new and long-serving employees effectively.
- **Career Path Planning**: Use award data to inform career development and reward strategies.

### 10. Awards Won by Department
**Query Result:**
- Sales & Marketing: 120 awards
- Operations: 89 awards
- Technology: 58 awards

**Interpretation:**
Sales & Marketing leads in awards, which might indicate higher recognition or a larger number of employees eligible for awards.

**Real-World Application:**
- **Award Distribution**: Ensure fair distribution of awards across departments.
- **Performance Metrics**: Use award data to assess departmental performance and set benchmarks.

### 11. Average Training Score by Recruitment Channel
**Query Result:**
- Referred: 64.51
- Other: 63.40
- Sourcing: 62.82

**Interpretation:**
Employees recruited through referrals have higher average training scores, suggesting a potentially more effective recruitment channel.

**Real-World Application:**
- **Recruitment Strategy**: Focus on successful recruitment channels to improve training outcomes.
- **Referral Programs**: Enhance referral programs to leverage higher-performing recruits.

### 12. Average Training Score of Employees with More Than 3 Years of Service
**Query Result:**
- Average training score: 63.12

**Interpretation:**
Employees with more than 3 years of service have a stable average training score, indicating sustained performance.

**Real-World Application:**
- **Ongoing Training**: Continue to provide training opportunities for long-serving employees to maintain their performance levels.
- **Career Development**: Support career development to keep long-serving employees engaged and effective.

### 13. Average Training Score by Gender
**Query Result:**
- Female: 63.68
- Male: 62.97

**Interpretation:**
Female employees have a slightly higher average training score compared to male employees, which may reflect differences in training outcomes by gender.

**Real-World Application:**
- **Gender-Specific Training**: Consider gender-based approaches to training programs to address any disparities.
- **Performance Tracking**: Track training outcomes by gender to ensure equitable development opportunities.

## Conclusion
This analysis provides a comprehensive view of employee demographics, performance, and training outcomes. The insights gained can help drive strategic HR decisions, improve training programs, and enhance overall organizational performance. By leveraging these insights, organizations can make data-driven decisions to optimize employee management and development strategies.

**George Zacharia**
