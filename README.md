# 📊 Patient Data Visualization & Analysis using Power BI

## 📁 Project Overview

In the healthcare industry, managing and analyzing patient data is essential for enhancing care quality and operational efficiency. This project focuses on analyzing and visualizing patient data using **Microsoft Power BI**, transforming raw healthcare data into actionable insights through interactive dashboards.

---

## 🎯 Objectives

- Analyze trends in patient data over time.
- Examine case volumes across specialties, case types, and age groups.
- Understand the distribution of case types within specialties and age profiles.
- Present findings using an interactive Power BI dashboard.

---

## 📦 Dataset Description

The dataset includes the following fields:

- `Archive Date`
- `Speciality HIPE`
- `Speciality Name`
- `Case Type` (Inpatient, Day Case, Outpatient)
- `Adult Child`
- `Age Profile` (0–15, 16–54, 55–64, 65+)
- `Time Bands`
- `Total`

**Records**: 453,120  
**Specialties**: 79  
**Case Types**: 3  
**Age Groups**: Multiple, ranging from 0-15 to 65+

---

## 🧹 Data Cleaning & Preparation

- Handled missing values by removing or correcting incomplete records.
- Converted data types (e.g., `Archive Date` to datetime).
- Cleaned mismatched entries (e.g., "Child" vs " Child").
- Established relationships between tables using Power BI’s data model.

---

## 🛠️ Tools & Features Used

### 💻 Power BI Capabilities

- **Data Import**: From Excel file.
- **Power Query Editor**: For data transformation and preparation.
- **DAX**: Created measures and calculated columns.
- **Custom Visuals**: Funnel, pie, and bar charts.
- **Interactivity**: Drill-throughs, slicers, toggle buttons.

---

## 📊 Dashboard Highlights

### 🔍 Key Visualizations

- **Trend Analysis**: Line charts showing case trends by type and specialty over time.
- **Case Volume**: Bar/pie charts for total cases by type, specialty, and age group.
- **Time Period Analysis**: Line charts exploring average and median wait times across groups.
- **Case Mix Analysis**: Funnel and pie charts showing specialty and age group distributions.

### ⚙️ Interactivity Features

- **Slicers**: Filter by age, specialty, case type.
- **Drill-throughs**: For detailed data exploration.
- **Responsive Layout**: Designed for multiple screen sizes.

---

## 📈 Key Insights

- **Growth in Outpatient Cases**: Notable increase from 2018 to 2021.
- **Case Type Distribution**:
  - Outpatient: 72%
  - Day Case: 17%
  - Inpatient: 11%
- **Specialty Trends**: Orthopedics and General Surgery lead in case volumes.
- **Age Group Patterns**: Older age groups experience longer wait times.
- **Case Mix**: High variability across specialties and age profiles.

---

## ✅ Summary

This project demonstrated how data visualization can:
- Improve understanding of patient case patterns.
- Assist in identifying bottlenecks and operational inefficiencies.
- Help healthcare professionals make data-driven decisions.

---

## 🔮 Future Enhancements

- **Expand Dataset**: Include outcomes, treatment costs, and hospital resources.
- **Predictive Modeling**: Use machine learning for forecasting trends and resource needs.
- **Real-Time Data**: Integrate live data sources into dashboards.
- **User Feedback**: Collect feedback from clinicians to refine the dashboard.
- **Detailed Time Analysis**: Incorporate patient acuity and resource availability.



