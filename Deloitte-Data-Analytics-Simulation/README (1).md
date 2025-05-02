
# Deloitte Australia Data Analytics Job Simulation – May 2025

This project was completed as part of the Deloitte Forage Virtual Job Simulation. It includes two core tasks using Tableau and Excel:

## 🧠 Project Tasks

### 1. Telemetry Dashboard (Tableau)
Analyzed machine telemetry data from four Daikibo factories to answer:
- In which location did machines break the most?
- Which machines had the most frequent breakdowns in that location?

**Tools Used:** Tableau Desktop Public Edition  
**Outcome:** Created an interactive dashboard to visualize downtime per factory and device type.  
[View Screenshot of Dashboard](./Tableau%20Dashboard%20(screenshot).png)

### 2. Equality Score Classification (Excel)
Processed employee compensation data to classify job roles into:
- `Fair`
- `Unfair`
- `Highly Discriminative`

**Method:**  
Used Excel with a formula to classify equality scores:
```excel
=IF(ABS(C2)<=10,"Fair",IF(ABS(C2)<=20,"Unfair","Highly Discriminative"))
```

## 📁 File Structure

- `data/`: contains the telemetry JSON file.
- `excel-analysis/`: contains the solved equality table.
- `Tableau Dashboard (screenshot).png`: output of the Tableau visualization.

## 🏆 Skills Demonstrated
- Data classification and rule-based logic in Excel
- Dashboard creation and filtering in Tableau
- Real-world business scenario analysis
- Visual storytelling with data

## 📌 Keywords
`Tableau`, `Excel`, `Telemetry`, `Deloitte`, `Equality Score`, `Data Analytics`, `Virtual Internship`

## 🔗 Certificate Statement
> Successfully completed Deloitte Australia Data Analytics Job Simulation on Forage (May 2025).
