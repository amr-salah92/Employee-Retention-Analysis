## Table of Contents

1. [Project Background](#project-background)
2. [Project Objectives](#project-objectives)
3. [Data Overview & Initial Assessment](#data-overview--initial-assessment)
4. [Executive Summary](#executive-summary)
5. [Departmental Analysis & Recommendations](#departmental-analysis--recommendations)
   - [Sales Department](#sales-department)
   - [Technical Department](#technical-department)
   - [HR Department](#hr-department)
   - [Support Department](#support-department)
   - [Accounting Department](#accounting-department)
   - [Management Department](#management-department)
6. [Company-Wide Evaluations](#company-wide-evaluations)
7. [Employee Tenure Insights](#employee-tenure-insights)
8. [In-Depth Insights](#in-depth-insights)
9. [Strategic Recommendations](#strategic-recommendations)
10. [Technical Methodology](#technical-methodology)
11. [Assumptions & Considerations](#assumptions--considerations)

---

## Project Background

Corporation employs over 15,000 individuals across Sales, Technical, HR, Support, Accounting, and Management departments. Over the past five years, the company has experienced a 23% attrition rate, significantly impacting productivity, increasing hiring costs, and raising concerns about workforce stability.

**Key business metrics affected include:**

- Employee satisfaction levels
- Workload distribution across teams
- Retention rates
- Career growth and promotion opportunities

---

## Project Objectives

This analysis aims to:

1. **Identify Key Drivers of Employee Turnover**: Evaluate factors such as job satisfaction, performance evaluations, salary, and career advancement opportunities.

2. **Assess Workload Impact on Retention**: Investigate how workload (measured through project count and working hours) correlates with attrition.

3. **Evaluate Career Progression and Promotions**: Understand the role of promotions in employee retention.

4. **Analyze Salary Trends and Departmental Disparities**: Identify salary-related retention issues across departments.

---

## Data Overview & Initial Assessment

The company's main database consists of a single table containing **14,999** records with the following **10 columns**:

1. **satisfaction_level** (`float`) - Employee satisfaction score (0 to 1 scale).
2. **last_evaluation** (`float`) - Last performance evaluation score (0 to 1 scale).
3. **number_project** (`int`) - Number of projects an employee has worked on.
4. **average_monthly_hours** (`int`) - Average monthly hours worked.
5. **time_spend_company** (`int`) - Tenure in years at the company.
6. **Work_accident** (`int`) - Indicator of work-related accidents (0: No, 1: Yes).
7. **left** (`int`) - Indicator of whether the employee left the company (0: No, 1: Yes).
8. **promotion_last_5years** (`int`) - Indicator of promotion in the last 5 years (0: No, 1: Yes).
9. **Department** (`string`) - Department name.
10. **salary** (`string`) - Salary level (`low`, `medium`, `high`).

![Screenshot_4-2-2025_11448_dbdiagram io](https://github.com/user-attachments/assets/8694ce21-7442-4d2a-9a3d-1f525efefca8)

---

## Executive Summary

Our analysis highlights salary dissatisfaction, limited promotion opportunities, high workloads, and declining job satisfaction as key contributors to attrition, particularly in the Sales and Technical departments.

### Key Findings:

- **Salary Disparities**: A significant portion of employees who left were on low or medium salaries, despite receiving high performance evaluations.
- **Promotion Deficiency**: Only 2.13% of employees were promoted in the last five years, leading to stagnation.
- **High Performer Attrition**: 53% of employees who left had above-average performance evaluations.
- **Workplace Safety**: While 14.46% of employees experienced work-related accidents, only 169 of the employees who left had experienced a work accident (5% of total left employees). This indicates a need for improved safety protocols to reduce the total number of accidents, but it's not a primary driver of attrition.

Addressing these challenges through strategic initiatives can improve retention, enhance workforce stability, and optimize operational costs.

---

## Departmental Analysis & Recommendations

### Sales Department

- **Attrition Rate**: 28% of all Employees left (highest among all departments).

**Key Issues:**

- 69% of employees left due to low salaries & 30% left due to medium salaries(27% of them had above-average performance evaluations & Satisfaction)
- Promotion rate among departed employees was only 0.69%.
- Highest number of work accidents, though not a primary reason for leaving.

![Screenshot_4-2-2025_152642_chatgpt com](https://github.com/user-attachments/assets/6c040993-5883-4c76-9c80-1e74f9755afd)

**Recommendations:**

- Increase compensation for low and medium salary brackets.
- Implement structured career advancement opportunities.
- Enhance workplace safety measures.



### Technical Department

- **Attrition Rate**: 19.5%.

**Key Issues:**

- 26% of departing employees had above-average satisfaction and evaluations.
- High workload (average 214 monthly hours).
- Lowest promotion rate among all departments (0.43%).

![Screenshot_4-2-2025_152952_chatgpt com](https://github.com/user-attachments/assets/f75e8e24-3ba8-4998-99a6-d6720887d88b)

**Recommendations:**

- Establish clear promotion pathways.
- Adjust salaries to retain high performers.
- Optimize workload distribution and staffing.

### HR Department

- **Attrition Rate**: Significant, primarily due to salary concerns.

**Key Issues:**

- 49% left due to medium salaries, 45% due to low salaries.
- No promotions recorded among employees who left.

![Screenshot_4-2-2025_153338_chatgpt com](https://github.com/user-attachments/assets/33e9ac48-e875-431d-9df9-c6c8e2620a0f)

**Recommendations:**

- Improve compensation structures.
- Introduce leadership development initiatives.
- Increase engagement through employee recognition programs.

### Support Department

- **Attrition Rate**: High due to salary issues.

**Key Issues:**

- 51% left due to low salary.
- 42% left due to medium salary.
- Third-highest number of work accidents, though not a primary driver of attrition.

![Screenshot_4-2-2025_155219_chatgpt com](https://github.com/user-attachments/assets/37c19c71-1536-4af1-a4b7-5088f8be44b2)

**Recommendations:**

- Offer better pay scales to reduce turnover.
- Continue to implement safety training and protocols for overall well-being.

### Accounting Department

- **Attrition Rate**: Due to low satisfaction and salary issues.

**Key Issues:**

- Lowest satisfaction levels among all departments.
- Equal number of employees left due to medium and low salaries (100 employees each).

**Recommendations:**

- Increase job satisfaction through team-building and recognition programs.
- Align salaries with market rates.

### Management Department

- **Attrition Rate**: Lower compared to other departments.

**Key Issues:**

- Highest number of projects.
- Moderate satisfaction levels.
- Least number of work accidents.
- Fewer employees left due to salary issues.

**Recommendations:**

- Distribute workload evenly.
- Provide leadership training and growth opportunities.

---

## Company-Wide Evaluations

- **Least Likely to Leave**:
  - Employees with last evaluations between 0.58 and 0.76 had the lowest attrition rates.
- **High Performers Leaving**:
  - 53% of all employees who left had above-average last evaluations.
  - 27% had above-average satisfaction levels.

![Screenshot_4-2-2025_15622_chatgpt com](https://github.com/user-attachments/assets/805575ce-d8e6-48bf-bb58-d495923ee38d)

---

## Employee Tenure Insights

- **Peak Attrition Year**:
  - Maximum number of employees left during their third year at the company.

![Screenshot_4-2-2025_145954_chatgpt com](https://github.com/user-attachments/assets/1e7ac71b-a87d-4248-ba9c-098fb61c4418)

---

## In-Depth Insights

### Company Last Evaluation

- **Evaluation Scores and Attrition**:
  - Employees with moderate performance evaluations (0.58 to 0.76) were less likely to leave.
  - High performers (above 0.76) had higher attrition, possibly due to feeling undervalued or lacking advancement.

![Screenshot_4-2-2025_145828_chatgpt com](https://github.com/user-attachments/assets/9be2412c-702b-4698-b11e-f2bf4d29b0e1)

### Company Left Employees

- **Tenure and Attrition**:
  - The third year marks a critical point where employees are most likely to leave.
  - Possible reasons include stagnation, lack of promotion, or reevaluation of career goals.



---

## Strategic Recommendations

1. **Develop Clear Promotion Criteria**
   - Increase promotion opportunities beyond the 2.13% current rate.
   - Establish mentorship and leadership development programs.

2. **Salary Restructuring**
   - Adjust compensation to industry benchmarks.
   - Focus on retaining high-performing employees in R&D and Product Management, where attrition due to salary concerns is highest.

![Screenshot_4-2-2025_154424_chatgpt com](https://github.com/user-attachments/assets/ae413160-a597-41d8-b39b-a238c316ac84)


3. **Optimize Workload Distribution**
   - Reduce burnout in high-demand departments.
   - Ensure equitable distribution of projects.
![Screenshot_4-2-2025_154650_chatgpt com](https://github.com/user-attachments/assets/861ab483-dce7-4071-9215-d714cae79378)


4. **Retain High Performers**
   - Develop targeted retention plans for employees with above-average evaluations.
   - Offer performance-based incentives.

5. **Address High Third-Year Attrition**
   - Introduce mid-term retention bonuses.
   - Conduct career planning sessions in the second and third years.

![Screenshot_4-2-2025_145954_chatgpt com](https://github.com/user-attachments/assets/ed4f54f5-9f33-4d40-a8a8-498bf3696400)

6. **Enhance Employee Engagement & Well-Being**
   - Implement regular feedback and career growth discussions.
   - Strengthen workplace culture through team-building initiatives.

7. **Continue Improving Safety Measures**
   - Invest in safety training, regular audits, and workplace improvements to reduce the total number of accidents, enhancing overall employee well-being.

![Screenshot_4-2-2025_154858_chatgpt com](https://github.com/user-attachments/assets/e752e072-1775-4201-9251-72997ba2483e)

---

## Technical Methodology

**Tools Used:**

- **Excel**: Data cleaning, exploratory analysis.
- **Power BI**: Interactive dashboard development.

**Dashboard:**
- A comprehensive Power BI dashboard visualizing trends and insights is available
  

---

## Assumptions & Considerations

1. **Data Accuracy**: Assumed to be complete and correctly recorded.
2. **Promotion Data**: Limited to the last five years.
3. **Tenure Calculation**: Based on full years at the company.
4. **External Factors**: Economic conditions and personal decisions were not included.

---

By implementing these strategic initiatives,Corporation can reduce attrition, enhance employee satisfaction, and build a more resilient workforce.
