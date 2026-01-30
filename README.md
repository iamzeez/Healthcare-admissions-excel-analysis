# Healthcare Admissions & Cost Analysis (Excel)

## Business Problem

Hospitals face increasing pressure to manage costs, reduce emergency room congestion,
and improve patient flow while maintaining quality care.

This analysis focuses on identifying:
- Cost differences between emergency and elective admissions
- Patient groups with longer hospital stays
- Seasonal admission patterns that affect staffing and resource planning


## Business Context & Data

The dataset contains hospital admission records used to simulate a real-world
hospital operations and cost management scenario.

Each record represents a patient admission with demographic, clinical,
and financial attributes.


## Data Source
- Public healthcare admissions dataset (CSV)
- Link: https://docs.google.com/spreadsheets/d/1qadwfBz_xsBab5-yC4oUZ_SDaJo-RmZh/edit?usp=drive_link&ouid=110898791710591676378&rtpof=true&sd=true

**Key columns include:**
- Patient Age
- Gender
- Admission Type (Emergency / Elective)
- Admission Date
- Discharge Date
- Diagnosis / Condition
- Treatment Cost

## Tools Used
- Microsoft Excel
- Pivot Tables
- Excel formulas (IF / IFS, TRIM, PROPER, XLOOKUP)
- Data validation and formatting

## Data Cleaning (Real-World Data Issues)

The raw dataset contained several common real-world data quality issues:

- Duplicate patient records
- Inconsistent text formatting (mixed casing, extra spaces)
- Currency values stored as text
- Missing values in demographic and cost fields
- Inconsistent date formats

Cleaning steps performed:
- Removed duplicate records
- Standardized text fields using TRIM and PROPER
- Converted cost columns to proper currency format
- Checked and handled missing values
- Ensured consistent date formats


## Data Transformation
To prepare the data for analysis, additional features were created:

- Age Group classification (e.g. 0–18, 19–35, 36–59, 60+)
- Length of Stay calculated from admission and discharge dates
- Monthly admission field derived from admission date

  ## Analytical Approach

The analysis followed a structured approach:
1. Clean and validate raw hospital data
2. Engineer key features (age groups, length of stay, monthly trends)
3. Use pivot tables to identify patterns and outliers
4. Build an executive-style dashboard for decision-making
5. Translate insights into operational recommendations

## Analysis & Dashboard

Pivot tables were used to analyze:
- Admissions by age group
- Emergency vs elective admissions
- Average length of stay by condition
- Monthly admission trends
- Cost distribution across admission types

A dashboard was created to visually summarize key metrics and trends for quick decision-making.

## Key Insights & Recommendations
- Emergency admissions drive higher operational strain compared to elective admissions.
  - Recommendation: Improve preventive care and outpatient services to reduce emergency load.

- Patients aged 56+ have significantly longer average lengths of stay.
  - Recommendation: Introduce early discharge planning for elderly patients.

- Admissions peak during specific months, indicating predictable seasonal demand.
    - Recommendation: Allocate additional staff and resources during peak periods.

## Business Impact

This analysis supports better hospital decision-making by:
- Highlighting cost drivers across admission types
- Enabling proactive staffing and resource allocation
- Improving patient flow and length-of-stay management

 
## Project Structure
- Raw_Data.xlsx – original dataset
- Cleaned_Data – cleaned and validated data
- Transformed_Data – feature-engineered dataset
- Pivot_Tables – analytical summaries
- Dashboard – visual insights
- Insights_Recommendations – findings and actions

## Screenshots
<img width="1919" height="1006" alt="Screenshot 2026-01-28 153251" src="https://github.com/user-attachments/assets/7d26cb3a-3f36-4329-8f45-2d4fd9392efa" />
<img width="1919" height="1006" alt="Screenshot 2026-01-28 153557" src="https://github.com/user-attachments/assets/4ac348dc-a518-42b7-8a10-d21dd20c712f" />




## Next Steps

With additional data, future improvements could include:
- Forecasting admission volume to support budgeting
- Readmission risk analysis
- Department-level performance comparisons




