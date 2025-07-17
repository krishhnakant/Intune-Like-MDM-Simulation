# Intune-Like MDM Simulation (Academic Project)

## 🧠 Project Overview

This project simulates a basic Mobile Device Management (MDM) system inspired by Microsoft Intune, built using Python and SQLite. It enforces device compliance policies such as firewall status, encryption, and password strength. The results are logged in a local database and visualized using Power BI to replicate enterprise-level reporting.

Designed for demonstrating understanding of policy enforcement, compliance monitoring, and endpoint support as required in roles like Systems Analyst or IT Support Engineer.

---

## 🧰 Technologies Used

- Python 3.x
- SQLite (Database)
- Power BI Desktop
- Pandas
- Simulated endpoints (Windows 10/11)

---

## 🗂️ Folder Structure

mdm_simulation/
├── device_check.py # Simulates Windows device info
├── mdm_policy.py # Policy definitions and compliance checks
├── compliance_logger.py # Logs compliance data into SQLite
├── main.py # Main runner that integrates modules
├── generate_csv.py # Exports compliance data for Power BI
├── database.db # SQLite database (auto-generated)
├── compliance_data.csv # CSV output for Power BI
└── dashboard.pbix # Power BI dashboard (optional)


---

## ⚙️ Features

- Simulates basic MDM policy enforcement:
  - Password must be ≥ 8 characters
  - Firewall must be enabled
  - Encryption must be enabled
- Automatically generates random endpoint data
- Logs compliance results to a database
- Exports to CSV for reporting
- Power BI dashboard for management view

---

## 🚀 How to Run

1. **Install requirements**  
Ensure you have Python 3 and Power BI Desktop installed.

2. **Run simulation**  
python main.py
This will simulate 10 random devices and log their compliance.

3. **Export to CSV (for reporting)**  
python generate_csv.py

4. **Load into Power BI**  
- Open Power BI Desktop  
- Load `compliance_data.csv`  
- Create visualizations (pie charts, tables, trends)

---

## 📊 Power BI Dashboard Suggestions

- Pie chart: Compliant vs Non-compliant
- Table: Device ID, OS version, Username, Compliance Status
- Line chart: Compliance trend over time

---

## 📌 Use Cases

- Showcase understanding of SCCM/Intune-style compliance
- Demonstrate skills in system administration and reporting
- Simulate enterprise IT device monitoring

---

## 👨‍💻 Author

**Addanki Krishnakanth**  
Email: krishnakanthaddanki@gmail.com  
GitHub: https://github.com/krishhnakant  
LinkedIn: https://www.linkedin.com/in/krishnakanth-addanki-86b41424a/

---

## 📄 License

This is an academic simulation intended for learning and demonstration purposes only. Not for production use.


