# Safety KPI Analysis (Python)

**Objective**  
Analyze workplace safety trends for 2024 and compute industry-standard KPIs — TRIR and LTIR — from synthetic incident data.

**Dataset**  
- `safety_incidents_2024.csv` (synthetic): incident date, department, location, injury type, severity (1–10), lost time hours, direct cost (USD), hours worked.

**KPIs**  
- **Incident Count** (monthly)  
- **TRIR**: (recordable incidents × 200,000) / total hours worked  
- **LTIR**: (lost-time incidents × 200,000) / total hours worked

**Artifacts**  
- Notebook: `safety_kpi_analysis.ipynb`  
- Charts: `monthly_incidents.png`, `incidents_by_department.png`, `severity_distribution.png`, `trir_by_month.png`, `ltir_by_month.png`

**How to Reproduce**  
1. Open the notebook in Jupyter or Google Colab.  
2. Ensure `safety_incidents_2024.csv` is in the same folder.  
3. Run all cells to regenerate KPIs and charts.
