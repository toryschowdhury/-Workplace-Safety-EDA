# Workplace-Safety-EDA

**Exploratory analysis of OSHA workplace fatalities & injuries**  
Tools: **Excel** (pivot tables, correlation analysis) + **Power BI** (data query, visuals)

---

## 📊 Project Overview

1. **Excel report**  
   - Pivot Tables & Slicers to explore fatalities by program (Federal vs. State)  
   - Identified Federal program with highest fatality rate and California with highest injuries  
   - Calculated correlation (r = 0.122) between “years to inspect” and “fatality rate”

2. **Power BI report**  
   - **Data prep:** Imported and cleaned source in Power Query  
   - **Donut Chart:** Visualizes inspection interval vs. fatality rate  
   - **Bar Chart:** Compares injury/illness counts by state  
   - **Funnel Chart:** Ranks programs by total fatalities  
   - **Slicer:** Fully interactive filter across all visuals

---

## 🔎 Repo Structure

- `data/` – Source Excel workbook (`OSHA_Workplace_Safety.xlsx`)  
- `powerbi/` – Power BI Desktop file (`.pbix`)  
- `documentation/`  
  - **Data_Model_Specs.md** – Data tables, column definitions, calculation logic  
  - **Visual_Descriptions.md** – Purpose & design choices for each chart  
  - **data-flow-diagram.png** – Workflow diagram (Excel → Power BI)  
- `screenshots/` – Static & animated previews of key visuals  
- `.gitignore` – Ignore temp/backups (e.g. `~$*.xlsx`, `*.pbix.bak`)  

---

## 🚀 Getting Started

1. **Clone**:  
   ```bash
   git clone https://github.com/<you>/workplace-safety-eda.git
   cd workplace-safety-eda
