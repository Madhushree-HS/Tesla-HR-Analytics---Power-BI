# 🧾Tesla-HR Analytics | Power-BI

_An automated Excel-based attendance tracking system that records, categorizes, and analyzes employee attendance data using dynamic formulas and cross-sheet references.._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#problem-statement">Problem Statement</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#Method">Method</a>
- <a href="#key insights">Key-Insights</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>

---
<h2><a class="anchor" id="overview"></a>📘Overview</h2>

An automated Excel-based solution designed to streamline monthly attendance management for Tesla employees. The system dynamically calculates attendance metrics — including present days, leaves, WFH days, and additional leave categories using a centralized "Attendance Key" sheet as its single source of truth. With multi-month support, it offers HR teams a reliable and structured overview of employee attendance patterns at a glance.

---
<h2><a class="anchor" id="problem-statement"></a>🎯Problem-Statement</h2>

**Manual attendance tracking is time-consuming and prone to errors. There is a need for a standardized, automated system to:**
      Accurately track daily attendance statuses.
      Categorize different types of leaves and absences.
      Generate summary metrics for each employee.
      Support HR in payroll processing, compliance, and attendance reporting.


---
<h2><a class="anchor" id="dataset"></a>📂Dataset</h2>

**Source:** Monthly attendance sheets (e.g., June 2022, May 2022).
**Fields Included:**
    Employee Code, Employee Name
    Daily attendance codes (P, WO, WFH, PL, SL, ML, LWP, BRL, etc.)
    Monthly summary columns: Total Present Days, Work from Home, Paid Leave, Sick Leave, etc.
**Size:** Multiple employees (90+ rows per month), 30+ days per month.

---

<h2><a class="anchor" id="tools--technologies"></a>🛠 Tools & Technologies</h2>

**Power BI** ETL process,Data Cleaning,Data Modeling
**SQL** Data aggregation, filtering, and joining
**Excel/CSV** Optional data export for visualization

---
<h2><a class="anchor" id="Method"></a>⚙ Method</h2>

**Data Entry:** Daily attendance is logged using standardized codes.
**Automated Calculation:**
    Total present days = Sum of present and work-from-home days.
    Leave breakdowns using COUNTIF formulas referencing the Attendance Key.
**Cross-Sheet Consistency:** All monthly sheets pull definitions from a shared key sheet to ensure uniformity.
**Scalability:** Template can be duplicated for additional months.

---
<h2><a class="anchor" id="key-insights"></a>📊 Key-insights</h2>

1. The system allows for real-time attendance summary per employee.
2. Supports half-day and full-day leave tracking.
3. Highlights patterns like extended leaves, frequent absenteeism, or high work-from-home usage.
4. Enables monthly comparison

---
<h2><a class="anchor" id="dashboard"></a>📈 Dashboard</h2>

**Output**: Each employee’s attendance summary per month, including:
Total Present Days,Work from Home,Paid Leave,Sick Leave,Floating Holidays,Bereavement Leave,Leave Without Pay,Weekly Offs,Holiday Offs,Menstrual Leave
**Layout**: Table format with rows per employee and columns for each attendance type.

---
<h2><a class="anchor" id="how-to-run-this-project"></a>▶ How to Run This Project</h2>

1. Open the Excel file: Attendance Track- Excel.xlsx
2. Navigate between sheets: June 2022, May 2022
3. Update daily attendance in the date columns using codes from the Attendance Key sheet.
4. Summary columns (AI:AS) auto-populate using formulas.
5. No macros or external tools required—works in any Excel-supported environment.

---
<h2><a class="anchor" id="final-recommendations"></a>✅ Final Recommendations</h2>

**Results:** The system efficiently automates attendance summarization, reduces manual errors, and provides clear visibility into employee attendance trends.

**Conclusion:** This Excel-based solution is a cost-effective, scalable, and user-friendly tool for SMEs to manage attendance without specialized software. It can be further enhanced with pivot tables, charts, or Power BI integration for deeper analytics.

---



