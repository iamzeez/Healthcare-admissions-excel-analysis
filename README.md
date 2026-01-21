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
- Link: [healthcare_dataset mubby.csv](https://github.com/user-attachments/files/24768408/healthcare_dataset.mubby.csv)

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
<img width="1919" height="1009" alt="Screenshot 2026-01-19 132723" src="https://github.com/user-attachments/assets/e4fa1e1e-8157-4fb9-92c2-0b5edb8b4f60" />
<img width="1919" height="1007" alt="Screenshot 2026-01-19 132641" src="https://github.com/user-attachments/assets/9d465bcf-015c-4486-8e8e-4f680db11bf7" />


## Next Steps

With additional data, future improvements could include:
- Forecasting admission volume to support budgeting
- Readmission risk analysis
- Department-level performance comparisons




