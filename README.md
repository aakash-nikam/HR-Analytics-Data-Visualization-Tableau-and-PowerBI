HR Analytics – Data Visualization in Tableau and Power BI

Author: Akash Nikam (DBS – MSc Data Analytics)
Tools: Tableau, Power BI

Project Overview

This project builds an HR analytics dashboard in Tableau and Power BI to understand workforce stability and attrition. The goal is to provide HR with an interactive view of headcount, attrition rate, at-risk segments, and likely drivers of exits so they can plan targeted retention actions and hiring. The deliverables include packaged workbooks, a concise report, and a presentation script.

Both tools present comparable visuals and KPIs so stakeholders can assess each platform’s strengths side by side. The Tableau/Power BI comparison and visualization intent are summarized in the report and script included in reports/.

Tech and Files

Tableau workbook: tableau/DV Tableau.twbx

Power BI report: powerbi/DV power bi.pbix

Data: data/HR.csv (sample HR attrition dataset)

Documentation: reports/dv.pdf, reports/Data_Visualization_Presentation_Script.docx
The report outlines objectives, KPIs, and how each tool builds the visuals; the script provides a clean narration for presenting the dashboards.

Dataset

The dataset contains employee demographics, job roles, compensation fields, tenure, and a churn flag indicating whether the employee left. It supports metrics such as headcount, attrition count/rate, and role- or education-level breakdowns used in the dashboards.

Repository Structure
data/HR.csv
tableau/DV Tableau.twbx
powerbi/DV power bi.pbix
reports/dv.pdf
reports/Data_Visualization_Presentation_Script.docx
results/
  ├─ tableau_dashboard.png
  ├─ powerbi_dashboard.png
  ├─ heatmap_job_satisfaction.png
  ├─ attrition_by_education.png
  └─ kpi_cards.png

Visuals Included

KPI cards: total employees, attrition count, attrition rate, active employees, average age.

Job satisfaction matrix by role (heatmap).

Attrition by education field and department.

Age-band and gender views.
Tableau emphasizes rapid on-canvas formatting; Power BI emphasizes model-driven visuals and DAX-based KPIs. The report discusses the trade-offs and build steps in each tool.

How to Open and Explore

Tableau

Open tableau/DV Tableau.twbx in Tableau Desktop.

If prompted, point the datasource to data/HR.csv.

Explore worksheets and the dashboard; adjust filters to see interactions.

Power BI

Open powerbi/DV power bi.pbix in Power BI Desktop.

Confirm the data source path to data/HR.csv.

Review the KPI cards, heatmaps, and attrition breakdowns; use slicers to filter.

Screenshots

High-level previews are under results/ for quick review in GitHub.

Design Notes

KPIs are built as DAX measures in Power BI and as calculated measures/cards in Tableau.

Heatmaps use a role-by-satisfaction grid to surface patterns; attrition is broken down by education, department, and age bands.

The presentation script provides a slide-by-slide talking track aligned to the dashboards.

Future Enhancements

Add trend pages with rolling twelve-month attrition.

Enrich with compensation bands and promotion history.

Publish to Tableau Server or Power BI Service with scheduled refresh.

Academic Artefacts

Report: reports/dv.pdf

Presentation script: reports/Data_Visualization_Presentation_Script.docx

Contact

Akash Nikam — MSc Data Analytics, Dublin Business School
Email: aakashn3118@gmail.com
