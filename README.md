# 🚗 Road Accident Analysis – Excel | Power BI | SQL | Tableau  

### Comparative Dashboard: 2021 vs 2022  

This project delivers an analytical dashboard solution providing a **comprehensive year-over-year (YoY) analysis** of road accident data between **2021 and 2022**.  
It evaluates accident severity, road types, vehicle involvement, and casualty trends using **data visualization and SQL-based insights**.  

Interactive dashboards built in **Excel, Power BI, and Tableau** enable policymakers and analysts to track accident patterns, evaluate safety improvements, and identify high-risk categories for targeted interventions.  

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Business Problem](#-business-problem)
- [Dataset](#-dataset)
- [Tools & Technologies](#-tools--technologies)
- [Project Structure](#-project-structure)
- [Data Preparation & SQL](#-data-preparation--sql)
- [Key Insights & Findings](#-key-insights--findings)
- [Dashboard Overview](#-dashboard-overview)
- [Challenges Faced](#-challenges-faced)
- [How to Run This Project](#-how-to-run-this-project)
- [Final Recommendations](#-final-recommendations)
- [Author & Contact](#-author--contact)

---

## 🔎 Overview
The **Road Accident Dashboard (2021 vs 2022)** provides actionable insights into the change in total and fatal casualties, accident causes, and severity distribution.  
A **significant YoY decline** across all major indicators reflects an improvement in road safety while highlighting focus areas like **Single Carriageways** and **Slight Casualties**.  

---

## ❗ Business Problem
Despite a reduction in overall accidents and fatalities, **road safety challenges persist** — particularly on single carriageway roads and during daylight hours.  

This project aims to answer:  
- How have accident rates and casualty numbers changed from 2021 to 2022?  
- Which road types and times of day contribute most to accidents?  
- What vehicles are most frequently involved?  
- How can visualization support data-driven policymaking for accident prevention?  

---

## 💾 Dataset
**Source:** Public accident dataset (aggregated national road safety data for 2021 & 2022).  
**Format:** CSV / Excel files loaded into SQL for transformation and joined with lookup tables for accident severity and road type.  

### Key Variables
- Accident ID, Date, Time  
- Casualty Severity (Fatal / Serious / Slight)  
- Road Type (Single Carriageway, Dual, etc.)  
- Vehicle Type (Car, Bike, Bus, etc.)  
- Urban/Rural Indicator  
- Light Conditions (Daylight / Darkness)  

---

## 🛠 Tools & Technologies

| Category | Tool | Purpose |
|-----------|------|----------|
| Database | SQL / MySQL | Data extraction, transformation, and KPI computation |
| Visualization | Tableau | Interactive comparative dashboard |
| Visualization | Power BI | Dynamic visuals and KPI analysis |
| Reporting | Excel | Static dashboard and summarized reporting |
| Documentation | Word / PDF | Executive Summary and Requirements documentation |

---

## 📂 Project Structure
Road_Accident_Analysis/

│

├── src/

│ └── sql/ # SQL scripts for KPI & data transformation

│

├── dashboards/

│ ├── tableau/ # Tableau files (.twb)

│ ├── power_bi/ # Power BI files (.pbix)

│ └── excel/ # Excel dashboards (.xlsx)

│

├── docs/

│ ├── Executive_Summary.pdf

│ └── Requirements.pdf

│

└── README.md # Project Documentation


---

## 🧹 Data Preparation & SQL
All KPI calculations and transformations were completed using **SQL**.  
Scripts included:
- Accident severity aggregation  
- Road type casualty distribution  
- Urban vs. rural split  
- Monthly trend analysis  

**Key queries are stored in:**  
- `ROAD ACCIDENT REPORT SQL QUERIES.docx`  
- `Road Accident SQL.sql`

---

## 🔍 Key Insights & Findings

| KPI | 2021 | 2022 | % Change |
|-----|------|------|-----------|
| Total Casualties | ~222K | ~195.7K | ↓ 11.9% |
| Fatal Casualties | ~4.4K | ~2.9K | ↓ 33.3% |
| Total Accidents | ↓ 6.5–11.7% YoY |  |  |

### Key Highlights
- **Slight Casualties:** ≈84.1% of all incidents  
- **Single Carriageways:** Most accident-prone (≈309.7K casualties)  
- **Urban Areas:** Higher share (≈61.95%) vs. rural (≈38.05%)  
- **Time of Day:** 74% of accidents occur during daylight  
- **Vehicle Type:** Cars dominate (~79.8%), followed by motorcycles (~15.6%)  

### Seasonality
Casualties peak from **August to October**, showing consistent seasonal patterns across both years.  

---

## ⚠️ Challenges Faced

| Challenge Area | Description |
|----------------|-------------|
| Data Integration | Merging multi-year accident data with consistent schema |
| Data Cleaning | Handling missing or inconsistent severity and location fields |
| Visualization | Ensuring uniform KPI comparison between 2021 and 2022 |
| KPI Normalization | Absence of “casualties per 1,000 vehicles” data for deeper normalization |

---

## ▶ How to Run This Project

**1. Database Setup:**  
Load raw accident data into MySQL / SQL Server.  

**2. Run SQL Scripts:**  
Execute transformations and calculations from `ROAD ACCIDENT REPORT SQL QUERIES.docx`.  

**3. Open Dashboards:**  
- Tableau: `Road Accident Analysis - Tableau.twb`  
- Power BI: `Road Accident Dashboard_PBI.pbix`  
- Excel: `Road Accident Dashboard image_Excel.png`  

**4. Explore Filters:**  
Use filters for **Year, Severity, Road Type, Vehicle Type,** and **Time of Day** to compare accident patterns.  

---

## ✅ Final Recommendations

### A. Actionable Safety Interventions
- **Target Single Carriageways:** Conduct safety audits and stricter enforcement.  
- **Focus on Slight Casualties:** Promote awareness on minor accidents and driver alertness.  
- **Vehicle-Specific Actions:**  
  - Cars → Defensive driving programs  
  - Bikes → Visibility & helmet awareness campaigns  

### B. Dashboard Enhancements
- Label KPI timeframes as “2021” and “2022” clearly.  
- Add filters for **Fatal**, **Serious**, and **Slight** casualties in monthly views.  
- Normalize metrics per **1,000 vehicles** (if data available).  
- Introduce an **“After Accident” KPI card** to track post-incident outcomes.  

---

## 👤 Author & Contact
**Soundarya G S**  
*Business / Data Analyst*  

📧 Email: **soundaryags948@gmail.com**  
🔗 LinkedIn: [linkedin.com/in/soundarya-g-s](https://linkedin.com/in/soundarya-g-s)


