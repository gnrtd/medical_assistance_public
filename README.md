### [medical_assistance_public](https://github.com/gnrtd/medical_assistance_public/tree/1_doc-automation)
### Branch: `1_doc-automation` — Daily Medical Report Automation

This branch contains the automation layer of the **[**Automated Analytics Pipeline for Medical test**](https://github.com/gnrtd/medical_assistance_public)** project. It simulates real-world documentation flow in medical testing by generating daily Word report templates for multiple offices, doctors, and shifting schedules.

---

### 🧭 Purpose

Automate the manual process of preparing daily report templates and associated communication artifacts (email drafts) used in outpatient medical testing procedures a week in advance.

### 📁 Repository Structure
- `scripts/` – generation scripts (screenshots)
- `templates/` – document templates
- `visuals/` – infographics
- `docs/` – documentation

---

### ⚙️ Features

- Auto-creates dated folder structure for upcoming week (configurable).
- Generates `.docx` report templates with:
  - Office name
  - Date of test
  - Assigned doctor
  - Optional add-ons (per office rules)
- Automatically drafts emails in Gmail for each daily report.
- Supports custom office visit patterns:
  - 1st & 3rd weekdays
  - 2nd & 4th weekdays
  - Biweekly / weekly office schedules

---

### 🛠️ Tech Stack

- **PowerShell**: File/folder automation, date logic, document template population
- **Google Apps Script**: Gmail draft creation based on daily templates
- **Windows Task Scheduler** (optional): To run script weekly

---

🔐 Disclaimer
All names, schedules, and content are synthetic. This branch is designed strictly for portfolio demonstration and technical evaluation purposes.
