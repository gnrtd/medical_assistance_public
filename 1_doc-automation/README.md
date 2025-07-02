# **Medical-field-tech-assist-tools**

- `This project simulates real-world documentation flow in medical testing by generating daily Word report templates for multiple offices, doctors, and shifting schedules.`

## 📁 Project Structure

<details>
<summary><strong>Click to expand pipeline phases</strong></summary>

---

### 🧭 Purpose

Automate the manual process of preparing daily report templates and associated communication artifacts (email drafts) used in outpatient medical testing procedures a week in advance.

### 📁 Repository Structure

- [`scripts/`](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/scripts) – generation scripts 
- [`templates/`](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/templates
) – document templates (screenshots)
- [`visuals/`](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/visuals
) – infographics
- [`docs/`](https://github.com/gnrtd/medical_assistance_public/tblob/main/1_doc-automation/docs) - [project documentation](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/docs/Documentation.jpg)
 
---

### **Components of the project**

- `1_create-daily-report-base (5 variations)` [pic](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/templates/doc_template_sample.png) 
- `2_run-it-by-6-schedules` [pic](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/visuals/Schedule_Monthly_Sample.png)
- `3_create-email-drafts-by-6-schedules` [pic](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/scripts/AppScript_GmailDraftReport.png)

---

### ⚙️ Features

###  [`1_create-daily-report-base`](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/templates/doc_template_sample.png)
- Automates daily generation of a report folder with corresponding name and date, using [6 different schedules](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/visuals/Schedule_Monthly_Sample.jpg) a month.
- Automates daily generation `.docx` pre-report templates for 5 different locations with dynamic:
  - Date of test
  - Office address
  - Assigned doctor
  - Optional add-ons (per office rules)

###  [`2_run-it-by-6-schedules`](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/scripts/PowerShell+TaskScheduler.png)
- Automates execution of the first step via Task Scheduler using predefined schedule-based triggers.

###  [`3_create-email-drafts-by-6-schedules`](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/scripts/AppScript_GmailDraftReport.png)
- Automates daily generation of e-mail drafts (regarding 6 schedules and 5 locations) for proceeding reports to the next step operational process.

- Supports [custom](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/visuals/Schedule_Monthly_Sample.jpg) office visit patterns:
  - weekly on a specific weekday
  - 1st & 3rd weekdays
  - 2nd & 4th weekdays
  - Biweekly office schedules

- [Output folder icon](https://github.com/gnrtd/medical_assistance_public/blob/main/1_doc-automation/visuals/Output_folder.png)

---

### 🛠️ Tech Stack

- **PowerShell**: File/folder automation, date logic, document template population
- **Windows Task Scheduler**: To run script daily
- **Google Apps Script**: Gmail draft creation based on daily templates

---

🔐 Disclaimer All names, schedules, and content are synthetic. This branch is designed strictly for portfolio demonstration and technical evaluation purposes.

</details>




