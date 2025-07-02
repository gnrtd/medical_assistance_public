# `2_archive-to-csv` 🧪  
**Parse & Normalize Historical Medical Records**

This module handles structured extraction of historical `.docx` reports into a unified `.csv` dataset. It is designed to transform manually filled Word documents into validated, machine-readable data for analytics purposes.

---

## 🔧 Core Features

- **Docx Parsing**: Extracts structured tables from `.docx` test reports  
- **Field Normalization**: Maps varying field formats into standard column names  
- **Rule-Based Cleaning**:  
  - Validates date, weight, height, and other critical fields  
  - Highlights missing or malformed values  
  - Splits composite values into normalized units (e.g., First Name / Last Name)  
- **Conditional Formatting**: Visual tagging of missing or invalid cells  
- **Export Logs**:  
  - Combined master `.csv` with timestamp  


