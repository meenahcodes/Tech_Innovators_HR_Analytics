# Tech Innovators Inc. HR Analytics Dashboard

## Project Summary

This project presents an end-to-end HR analytics solution for **Tech Innovators Inc.**, a technology and consulting organisation headquartered in New York, United States. The dashboard was developed to support HR leaders with clearer visibility into workforce performance, training completion, employee engagement, benefit utilisation, and workforce demographics.

The analysis brings together employee performance, benefits utilisation, and demographic data into a structured Power BI report. The dashboard helps identify development gaps, compare performance across departments, understand benefit value, and translate workforce insights into practical HR actions.

---

## Business Problem

As Tech Innovators Inc. expanded its workforce and service offerings, HR operations became more complex. The organisation needed better visibility into two connected areas:

1. **Employee performance and development**
   - Performance reviews were largely periodic rather than insight-led.
   - HR needed a clearer way to identify high performers, low performers, and employees requiring development support.
   - Training completion and engagement needed to be monitored more effectively.

2. **Employee benefit utilisation and satisfaction**
   - The company offered several benefits, but there was limited visibility into which benefits employees used and valued most.
   - HR needed better evidence to support benefit optimisation and resource allocation.

This dashboard addresses these challenges by giving HR decision-makers a structured view of workforce performance, training gaps, benefit value, and priority action areas.

---

## Project Objectives

The main objectives of this project were to:

- Track key HR performance indicators across the workforce.
- Analyse employee performance, engagement, attendance, and project delivery outcomes.
- Measure training completion and identify development gaps.
- Assess benefit utilisation and employee satisfaction with benefits.
- Segment employees by department, location, gender, age group, and tenure group.
- Identify development-risk employees for targeted HR intervention.
- Translate analytical findings into clear business recommendations.

---

## Tools and Technologies

| Tool / Technology | Purpose |
|---|---|
| **Power BI** | Dashboard design, data modelling, and visual analytics |
| **Power Query** | Data cleaning, transformation, and preparation |
| **DAX** | KPI measures, rates, averages, and analytical calculations |
| **Excel / CSV** | Structured source data storage |
| **GitHub** | Project documentation and version sharing |

---

## Data Sources

The report uses three structured HR datasets:

| Dataset | Description |
|---|---|
| **Employee Demographics Data** | Contains employee age, gender, tenure, and location |
| **Employee Performance Data** | Contains department, role, performance rating, training status, project delivery success rate, attendance rate, and engagement score |
| **Employee Benefits Data** | Contains benefit type, utilisation frequency, and employee satisfaction with benefits |

The datasets are connected using **Employee ID**.

---

## Data Model

The Power BI model links the three tables through `Employee ID`.

| Relationship | Type | Description |
|---|---|---|
| Employee Demographics → Employee Performance | One-to-one | Each employee has one performance record |
| Employee Demographics → Employee Benefits | One-to-many | Each employee can have multiple benefit records |

This model allows performance, benefit, and demographic insights to be analysed together.

---

## Dashboard Pages

The Power BI report contains five pages:

### 1. Executive Overview

Provides a high-level summary of the main HR KPIs, including total employees, attendance rate, training completion, performance, engagement, benefit satisfaction, and development-risk employees.

### 2. Workforce Demographics

Analyses the workforce by location, gender, age group, and tenure group. It also compares performance patterns across demographic segments.

### 3. Performance and Training Analysis

Explores employee performance, engagement, training completion, project delivery success, and development-risk employees by department.

### 4. Benefits Utilisation and Satisfaction

Evaluates benefit usage, benefit satisfaction, usage by location, benefit usage by department, and benefit satisfaction by department.

### 5. HR Action Plan

Converts dashboard insights into practical HR recommendations, prioritising actions around training completion, development-risk employees, engagement, performance improvement, and benefit optimisation.

---

## Key KPIs

| KPI | Value |
|---|---:|
| Total Employees | 244 |
| Average Attendance Rate | 90.6% |
| Training Completion Rate | 48.8% |
| Training Gap Rate | 51.2% |
| Average Performance Rating | 3.2 |
| Average Engagement Score | 3.0 |
| Average Benefit Satisfaction | 3.1 |
| High Performer Rate | 45.1% |
| Low Performer Rate | 36.1% |
| Development Risk Employees | 84 |
| Development Risk Rate | 34% |
| Benefit Participation Rate | 100% |

---

## Key Insights

### Workforce and Performance

- The workforce contains **244 employees**.
- Attendance is strong at **90.6%**, suggesting workforce availability is not the main issue.
- Average performance is **3.2**, indicating moderate overall performance.
- Average engagement is **3.0**, suggesting room for improvement in employee motivation and connection.
- **45.1%** of employees are high performers, while **36.1%** fall into the low performer group.
- **84 employees** are classified as development-risk employees based on training, performance, and engagement indicators.

### Training and Development

- Training completion is low at **48.8%**.
- The training gap is **51.2%**, meaning more than half of employees have not completed training.
- Employees who completed training show slightly stronger average performance and engagement than employees who did not complete training.
- Sales, IT, and Finance show the highest counts of development-risk employees.

### Workforce Demographics

- New York has the largest employee group, followed by Remote, Austin, and San Francisco.
- The largest age group is **30–39**, followed by **40–49**.
- Employees aged **30–39** form the largest workforce segment but show lower average performance than some other age groups.
- The workforce has a balanced spread across physical and remote locations, meaning HR support must work effectively for both office-based and remote employees.

### Benefits Utilisation and Satisfaction

- Benefit participation is **100%**, meaning every employee has at least one benefit record.
- Gym Membership and Health Insurance are the most used benefits.
- Health Insurance shows strong utilisation and strong satisfaction, making it a high-value benefit.
- Wellness Program has low satisfaction and should be reviewed.
- Paid Time-Off shows very low recorded usage but very high satisfaction, which may indicate separate tracking or under-recording.

---

## Business Recommendations

### 1. Improve training completion

Training completion is below 50%, making it the most urgent HR development issue.

**Recommended action:**  
Launch department-level training follow-up, identify barriers to completion, and monitor completion rates monthly.

### 2. Prioritise development-risk employees

The dashboard identifies 84 employees requiring development support.

**Recommended action:**  
Create targeted coaching and support plans for employees with incomplete training and low performance or engagement indicators.

### 3. Strengthen engagement

Average engagement is moderate at 3.0, with some departments showing weaker engagement.

**Recommended action:**  
Introduce engagement pulse surveys, regular manager check-ins, recognition initiatives, and department-level engagement reviews.

### 4. Improve performance support

The low performer rate is 36.1%, which requires structured intervention.

**Recommended action:**  
Develop performance improvement plans, mentoring support, and role-specific coaching for employees with lower performance ratings.

### 5. Optimise benefits value

Benefit usage is high, but satisfaction differs across benefit types.

**Recommended action:**  
Maintain high-value benefits such as Health Insurance, review the Wellness Program, and investigate how Paid Time-Off usage is recorded.

---


## Dashboard Preview

Add dashboard screenshots to the `/images` folder and embed them here.

### Executive Overview

![Executive Overview](images/executive_overview.png)

### Workforce Demographics

![Workforce Demographics](images/workforce_demographics.png)

### Performance and Training Analysis

![Performance and Training Analysis](images/performance_training_analysis.png)

### Benefits Utilisation and Satisfaction

![Benefits Utilisation and Satisfaction](images/benefits_utilisation_satisfaction_analysis.png)

### HR Action Plan

![HR Action Plan](images/hr_action_plan.png)

---

## Skills Demonstrated

This project demonstrates:

- Business intelligence reporting
- HR analytics
- Power BI dashboard development
- Power Query data cleaning
- Data modelling and relationship management
- DAX measure creation
- KPI design
- Workforce segmentation
- Benefit utilisation analysis
- Performance and engagement analysis
- Data storytelling
- Business recommendation development
- Executive reporting

---

## Conclusion

The Tech Innovators Inc. HR Analytics Dashboard provides a structured view of workforce performance, training completion, employee engagement, benefit utilisation, and demographic patterns. The analysis shows that the organisation has strong attendance and high benefit participation, but it also highlights important development gaps, moderate engagement, and a sizeable group of development-risk employees.

The dashboard supports HR leaders in moving from reactive reporting to proactive workforce management by identifying where intervention is needed and which actions should be prioritised.
