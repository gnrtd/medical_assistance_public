# **Medical-field-tech-assist-tools**

- `This project simulates real-world documentation flow in medical testing by generating daily Word report templates for multiple offices, doctors, and shifting schedules.`

## 📁 Project Structure

<details>
<summary><strong>Click to expand pipeline phases</strong></summary>

### 🛠️ Creation of Public version is in progress
### 🚀 Original version was launched on March 2025, tested and works properly

---

### 🧭 Purpose

Automate the manual process of preparing daily report templates and associated communication artifacts (email drafts) used in outpatient medical testing procedures a week in advance.

### 📁 Repository Structure

- [`scripts/`](https://github.com/gnrtd/medical_assistance_public/tree/main/scripts) – generation scripts 
- [`templates/`](https://github.com/gnrtd/medical_assistance_public/tree/main/docs
) – document templates (screenshots)
- [`visuals/`](https://github.com/gnrtd/medical_assistance_public/tree/main/visuals
) – infographics
- [`docs/`](https://github.com/gnrtd/medical_assistance_public/tree/main/docs) - [project documentation](https://github.com/gnrtd/medical_assistance_public/blob/main/docs/Documentation.jpg)
 
---

### **Components of the project**

- `1_create-daily-report-base (5 variations)` 
- `2_run-it-by-6-schedules`
- `3_create-email-drafts-by-6-schedules` 

---

### ⚙️ Features

###  [`1_create-daily-report-base`](https://github.com/gnrtd/medical_assistance_public/blob/main/templates/created_WordReport_template.png)
- Automates daily generation of a report folder with corresponding name and date, using [6 different schedules](https://github.com/gnrtd/medical_assistance_public/blob/main/visuals/Schedule_Monthly_Sample.jpg) a month.
- Automates daily generation `.docx` pre-report templates for 5 different locations with dynamic:
  - Date of test
  - Office address
  - Assigned doctor
  - Optional add-ons (per office rules)

###  [`2_run-it-by-6-schedules`](https://github.com/gnrtd/medical_assistance_public/blob/main/scripts/PowerShell%2BTaskScheduler.png)
- Automates execution of the first step via Task Scheduler using predefined schedule-based triggers.

###  [`3_create-email-drafts-by-6-schedules`](https://github.com/gnrtd/medical_assistance_public/blob/main/scripts/AppScript_GmailDraftReport.png)
- Automates daily generation of e-mail drafts (regarding 6 schedules and 5 locations) for proceeding reports to the next step operational process.

- Supports [custom](https://github.com/gnrtd/medical_assistance_public/blob/main/visuals/Schedule_Monthly_Sample.jpg) office visit patterns:
  - weekly on a specific weekday
  - 1st & 3rd weekdays
  - 2nd & 4th weekdays
  - Biweekly office schedules

- [JSON AppScript](file https://github.com/gnrtd/medical_assistance_public/blob/main/scripts/AppScript_GmailDraftReport.json)
- [Output folder icon](https://github.com/gnrtd/medical_assistance_public/blob/main/visuals/Output_folder.png)

---

### 🛠️ Tech Stack

- **PowerShell**: File/folder automation, date logic, document template population
- **Windows Task Scheduler**: To run script daily
- **Google Apps Script**: Gmail draft creation based on daily templates

---

🔐 Disclaimer All names, schedules, and content are synthetic. This branch is designed strictly for portfolio demonstration and technical evaluation purposes.

</details>




