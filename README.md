
# Deloitte Australia – Data Analytics Job Simulation (May 2025)

## Project Overview

This project is based on the Deloitte Australia Data Analytics Job Simulation completed via Forage in May 2025. The simulation was designed to replicate a real-world analytics task for Deloitte’s client, Daikibo – a multinational manufacturing company with operations in Japan, Germany, and China.

The primary focus was to analyze machine telemetry data and assess employee equality scores across factories using tools like Tableau and Excel.

---

## Objective

1. Determine which factory had the highest machine downtime during May 2021.
2. Identify the machine types that failed most frequently at the selected location.
3. Classify employee equality scores to highlight fairness and potential discrimination patterns across factories and roles.

These tasks simulate typical work a data analyst might perform in a consulting environment, offering experience in data cleaning, visualization, and basic business intelligence.

---

## Dataset Summary

### 1. Factory Telemetry Data
- Format: JSON
- Frequency: One entry every 10 minutes per machine
- Coverage: Four factories (Tokyo, Osaka, Berlin, Shenzhen) with 9 machine types

### 2. Equality Table
- Format: Excel
- Columns: Factory, Job Role, Equality Score
- Task: Add an `Equality Class` column to categorize scores into:
  - Fair (±10)
  - Unfair (>10 or <-10 up to ±20)
  - Highly Discriminative (>±20)

---

## Tools Used

- Tableau Public – For dashboard creation and visualization
- Microsoft Excel – For data classification and analysis
- Jupyter Notebook (optional) – For organizing tasks or future extensions

---

## Deliverables

### 1. Tableau Dashboard

A two-part interactive dashboard:

- **Chart 1**: Down Time per Factory
- **Chart 2**: Down Time per Device Type (filters dynamically based on Chart 1)

The Unhealthy metric was created as a calculated field to represent 10-minute intervals of machine downtime.

**Live Dashboard Link**:  
[View on Tableau Public](https://public.tableau.com/app/profile/surya.prakash.jayaseelan/viz/Daikibo_Telemetry_Dashboard/Dashboard1?publish=yes)
![Feature Importance Chart](TableauDashboard(screenshot).png)
### 2. Equality Score Classification

In Excel, a new column was added based on the following rules:

- If score is between -10 and +10 → Fair
- If score is between -20 and -10 or between +10 and +20 → Unfair
- If score is less than -20 or greater than +20 → Highly Discriminative

---

## Key Insights

- Tokyo (Factory Meiyo) experienced the most machine downtimes.
- Specific machine types were more prone to failures and identified via filtering.
- The equality analysis revealed role-based disparities in some factories, offering opportunities for policy correction.

---

## Folder Structure

```
Deloitte-Analytics-Project/
│
├── README.md
├── daikibo-telemetry-data.json
├── Task 5 Equality Table solved.xlsx
├── Tableau Dashboard Screenshot.png
└── /optional-notebooks/
```

---

## Outcome

This project demonstrates a business-oriented approach to data analytics using common industry tools. It highlights the importance of turning raw data into actionable insights and delivers a clear communication structure suitable for clients or stakeholders.
