
# `3_analytics-insights` 📊  
**Tableau Dashboard for Medical Test Insights**

This module delivers business-ready visual analytics built on the cleaned dataset from Phase 2. It provides visibility into patient test patterns, doctor performance, and office load over time.

---

## 📌 Objectives

- Transform raw test data into actionable dashboards
- Enable slicing by doctor, office, test type, age range, and gender
- Identify patterns in patient visits, test type, and abnormal results

---

## 📈 Key Dashboards

- **Daily Operations Overview**  
  - Patient count by office/offices  
  - Test volume by week/month/quarter  
  - Total value of abnormal results  

- **Medical Insights**  
  - Test abnormality rate by type  
  - Gender and age-based trends  
  - Extraweight research  

---

## 📁 Input

- Cleaned CSV from Phase 2: `master_combined_YYYYMMDD_HHMM.csv`
- (Optional) `doctor`, `office`, or `test_type` lookup tables from SQL

---

## 🔗 Integration

- Import the CSV into Tableau 
- Create relationships between fact tables and dimension tables
- Use calculated fields, groups and sets

---

## 🧠 Business Use Cases

- **Ops Management**: Optimize staff allocation and office scheduling  
- **Medical Review**: Spot abnormal result clusters by location or period  
- **Executive Reporting**: Export ready-to-present visuals with trends

---

> 📎 **Disclaimer:**  
> All data used in this project is **synthetic** and **artificially generated** for demonstration and development purposes only.  
> It does not contain any real patient information and should not be used for clinical or diagnostic decisions.


