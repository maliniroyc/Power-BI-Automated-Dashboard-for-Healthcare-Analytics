# Power-BI-Automated-Dashboard-for-Healthcare-Analytics

## Healthcare Financial Dashboard (Power BI): </br>
I built a Power BI dashboard that streamlined financial reporting for a simulated healthcare center, reducing manual analysis time by 50% and enabling real-time tracking of KPIs like Billing Amount, Treatment Cost, and Out-of-Pocket expenses. The dashboard revealed critical trends and procedure-level billing insights by state and provider, supporting data-driven decisions in healthcare management. </br>
• Financial Analysis: Uncovered inefficiencies and optimized cost breakdowns across key billing categories. </br>
• Provider Insights: Evaluated provider performance based on treatment and insurance-related metrics. </br>
• Trends and KPIs: Identified billing patterns and calculated KPI averages to highlight high-cost procedures and regions. </br>
• Tools Used: Power BI, Power Query, DAX, PowerPoint </br>

📊 Healthcare Financial Dashboard
---------------------------------
**Overview:**
Developed a Power BI dashboard to optimize financial reporting for a simulated healthcare provider. The dashboard tracks KPIs like Billing Amount, Treatment Cost, Insurance Coverage, and more, revealing insights into high-cost procedures, city/state breakdowns, and provider department performance.

🔍 Objective
----------------
Streamline manual financial reporting and visualize critical billing KPIs in healthcare.

🛠️ Tools & Technologies
------------------------
Power BI

Power Query

DAX

Excel/CSV

PowerPoint (for presentation)

📁 Dataset Details
----------------------
Simulated hospital financial dataset

Metrics: Billing Amount, Medication Cost, Treatment Cost, Insurance Coverage, Room Charges, Procedure Type, Department, State/City

Format: Tabular (.csv/.xlsx)

📈 Data Analysis Steps (Power BI)
-----------------------------------
Data Loading & Cleaning

Imported raw financial data from Excel/CSV.

Cleaned column headers, renamed for clarity.

Ensured proper data types (e.g., Currency, Date, Text).

Data Modeling

Defined relationships between entities: Location ↔ Procedure ↔ Department ↔ Financials.

Created calendar table for time-based filtering.

DAX Measures Created

Total Billing Amount

Average Billing per Visit

Average Treatment Cost, Out-of-Pocket Cost

% by Procedure, % by Department

**KPI Visuals**

Total & Average values for Billing, Medication, Treatment, Insurance, Out-of-Pocket

Slicers for Race, Year/Quarter, and City/State

Dark mode toggle for presentation use

**Charts Used**

Map: Billing by City

Bar Charts: Billing by Procedure & Department

Stacked Bars: Diagnosis vs Service Type

Tooltips with % Share and absolute figures

**Insights Delivered**

Identified X-Ray and CT Scans as top contributors to billing

Orthopedics and Cardiology drove 50%+ of total costs

Fractures and Asthma often required Inpatient care

Average out-of-pocket cost per patient: £403.50

🎯 Key Business Insights
-------------------------
Reduced manual reporting time by 50% using interactive dashboard

Highlighted cost-heavy departments for budgeting (e.g., Orthopedics)

City-level heatmap revealed resource-intensive locations (e.g., London, Birmingham)

Real-time filters allowed stakeholder-specific views and decision-making

📷 Screenshots
------------------

LIGHT MODE </br>

![Main Light Dashboard](https://github.com/user-attachments/assets/e2e462af-4b94-4bbf-9a20-c5d13b18cece)


DARK MODE </br>

![Dark Mode Dashboard](https://github.com/user-attachments/assets/bbfd34c5-9810-471c-80e9-2a4c9bf0249c)



| File                        | Description                   |
| --------------------------- | ----------------------------- |
| `Healthcare Insight Dashboard.pbix` | Main Power BI dashboard       |
| `dataset.csv`       | Source dataset                |
| `README.md`                 | Project documentation         |
| `background`     | Power Point slides |

