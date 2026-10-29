# Hospital Readmission Analysis | Tableau

## Project Overview
This project uses Tableau to explore hospital readmission patterns and present healthcare performance indicators through an interactive dashboard. It is designed to help hospital leadership compare readmission patterns across patient groups and services and identify areas for further investigation.

## Business Problem
Hospital readmissions within 30 days of discharge are an important healthcare performance concern. Readmission rates can affect patient outcomes and may have financial implications for hospitals under programs monitored by the Centers for Medicare & Medicaid Services (CMS).

This dashboard supports data-driven discussion of readmission performance and potential operational improvements. It does not establish the causes of readmissions or prove that a particular intervention will reduce them.

## Project Objectives
- Review the overall 30-day readmission rate.
- Compare readmission patterns across age groups.
- Explore readmissions by service type, geographic area, and gender.
- Provide interactive filters for selected patient groups.
- Present key performance indicators in an accessible dashboard.

## Tools and Skills
- Tableau
- Data visualization
- KPI reporting
- Interactive dashboard design
- Data storytelling

## Dataset Overview
The WGU project documents describe patient-level hospital encounter data with demographic characteristics, clinical and operational variables, length of stay, and a 30-day readmission indicator.

**Dataset source and sharing note:** Add the original dataset source and license information before publishing. Do not upload patient-level data unless you have confirmed it is safe and permitted to share.

## Dashboard Preview
![Hospital Readmission Analysis Tableau Dashboard](images/hospital_readmission_dashboard.png)

 Dashboard

 1. Readmission Rate
Displays the readmission rate to provide a high-level view of performance. Confirm whether the current filters are applied before describing the value as an overall hospital-wide rate.

 2. Readmission by Service Type
Compares readmission rates across services shown in the dashboard, including Intravenous, Blood Work, MRI, and CT Scan.

 3. Readmission by Age Group
Compares readmission patterns across age categories.

 4. Geographic Area and Gender
Explores patterns across rural, suburban, and urban areas for the selected gender.

 5. Interactive Filters
Includes age-group and gender filters so users can explore selected patient populations.

 6. Key Performance Indicators
Displays total readmissions and average length of stay.

 Initial Observations from the Dashboard Screenshot
The supplied screenshot displays:
- Average length of stay: 34.46 days
- Total readmissions: 3,669
- Displayed readmission rate: 36.7%
- Service-level readmission rates ranging from 35.2% to 39.8% in the visible chart
- Age-group readmission rates ranging from 34.4% to 37.9% in the visible chart

Important:** The screenshot has filters selected for Male and ages 60, 70, and 80. These displayed values may therefore represent a filtered subset, not the entire dataset. Verify the filters and calculations in Tableau before presenting these as overall results.

 Data Storytelling and Accessibility
The dashboard uses a top-down sequence, beginning with high-level indicators and then showing more detailed comparisons. Design considerations described in the project include clear labels, readable text, consistent formatting, and color choices intended to be accessible to users with color-vision deficiencies.

 Business Value
The dashboard helps users explore readmission patterns and identify questions for further investigation. Findings may inform discussions about discharge planning, follow-up care, and operational improvement, subject to further validation.

 Limitations
- Findings depend on the quality and representativeness of the source dataset.
- Differences between groups do not necessarily indicate causation.
- The dashboard is an exploratory tool and should not be used alone to make clinical decisions.
- Dataset source and redistribution permissions should be documented before public release.

 Project Files
- `README.md` — project description and dashboard documentation
- `images/hospital_readmission_dashboard.png` — dashboard screenshot

If you choose to publish the Tableau workbook, first check that it contains no identifiable patient information and that you have permission to share the workbook and its underlying data.


Obadah Elabhari

