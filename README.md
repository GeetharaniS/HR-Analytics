# 📊 End-to-End HR Analytics EDA & Interactive Excel Dashboard

![Excel](https://img.shields.io/badge/Tool-Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-HR_Analytics-blue?style=for-the-badge)
![Data](https://img.shields.io/badge/Dataset-1%2C500_Employees-orange?style=for-the-badge)

An enterprise-grade HR Data Analytics project evaluating workforce dynamics, attrition drivers, performance metrics, employee engagement (eNPS), compliance overdues, and recruitment efficiency across 1,500 employees.

---

## 🚀 Key Highlights & Executive Summary

* **Active Headcount vs Target**: **1,500 employees** (1,237 Active / 263 Exited) with a **92.1%** target fill rate.
* **Overall Attrition Rate**: **17.53%** (81.7% Voluntary, 18.3% Involuntary).
* **Regrettable Talent Loss**: **33.46%** (88 top-tier/critical skill employees lost).
* **Early Attrition Rate (<12 Months)**: **45.25%** (119 early exits, highlighting onboarding gaps).
* **Enterprise Payroll**: **₹291.54 Cr Total Annual CTC** (Avg. ₹19.44 Lakhs per employee).
* **eNPS Score**: **+12.4** (Promoters: 34.2%, Passives: 44.0%, Detractors: 21.8%).

---

## 📈 Key Findings & Insights

### 1. Attrition Drivers
* **Department Vulnerability**: **Sales** recorded the highest attrition rate (**25.12%**), followed by **Operations** (**18.62%**) and **Customer Support** (**17.87%**). **Engineering** maintained high stability (**14.95%**).
* **Junior Level (L1) Burnout**: L1 employees accounted for **48% of all exits**. Overtime exceeding **25 hours/month** increased exit risk by **3.2x**.
* **Commute & Work Mode Impact**: Employees with long commutes (>25 km) working **On-Site** showed a **24.5%** exit rate, compared to **11.2%** for **Remote** workers.

### 2. Exit Review Sentiment
* **42%** of exits cited uncompetitive market compensation or delayed appraisal hikes.
* **28%** cited low managerial alignment or lack of career development pathways.

### 3. Early Warning Indicators
* Exiting employees exhibited a sharp spike in **unplanned absences** (sick/casual leaves) during the **60–90 days prior to resignation** (increasing from 0.8 to 3.4 days/month).

---

## 📁 Repository Structure

```
├── 00_README_metrics_guide.md       # Metrics definition and guidelines
├── 01_departments.csv               # Department budgets and targets
├── 02_employees.csv                 # Master demographic and CTC data
├── 03_attrition_exits.csv           # Exit reasons, dates, and regretability
├── 04_exit_reviews_raw.csv          # Qualitative exit feedback & ratings
├── 05_performance.csv               # Performance reviews, hikes & training
├── 06_engagement_survey.csv         # eNPS and survey scores
├── 07_compliance_trainings.csv      # Mandatory compliance course statuses
├── 08_compliance_employee_records.csv# BGV, NDA, and grievance records
├── 09_attendance_leave.csv          # Presence, leave, and overtime tracking
├── 10_recruitment.csv                # Requisition timelines and sourcing cost
├── HR_Analytics_EDA_Dashboard.xlsx  # Formatted Excel Summary Dashboard
└── README.md                        # Project documentation
```

---

## 🛠️ Dashboard Architecture

The repository includes a ready-to-use **`HR_Analytics_EDA_Dashboard.xlsx`** workbook structured into key analytical blocks:

1. **Executive KPI Header**: Instant visibility into Headcount, Attrition Rate, Regrettable Loss %, Early Exits, and Total Payroll.
2. **Departmental Breakdown**: Cross-tabulation of target vs. actual headcount, exit counts, average CTC, and retention metrics paired with visual column charts.
3. **Exit Drivers Analysis**: Categorical distribution of departure reasons (Compensation, Career Growth, Work-Life Balance, Commute, Leadership).
4. **Demographics & Equity**: Compensation distribution by Job Level (L1–L5) and gender pay parity auditing.
5. **Engagement & Compliance Audit**: eNPS net score breakdown and overdue compliance training tracking.

---

## 💡 Strategic Recommendations

1. **Structured Onboarding Support**: Implement 30-60-90 day milestone reviews and buddy systems to curb the **45.25% early attrition rate**.
2. **Targeted Sales Retention**: Benchmark L1/L2 Sales compensation packages against regional standards and improve hybrid flexibility.
3. **Automated Attendance Alerts**: Set up early-warning alerts when an employee's unplanned leave frequency spikes by >150% over a 60-day window.
4. **Compliance Push**: Address the **1,173 overdue training modules** through automated manager reminders.

---

## 🎯 How to Use

1. Clone or download the repository.
2. Open `HR_Analytics_EDA_Dashboard.xlsx` in **Microsoft Excel** or **Google Sheets**.
3. Explore the KPI cards, interactive tables, and charts to analyze workforce trends.
