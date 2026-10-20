# Healthcare Disease & Treatment Analysis Dashboard

An interactive healthcare analytics dashboard exploring patient demographics, admission patterns, medication billing, test results, and other descriptive metrics.

## Project Overview

This project demonstrates an end-to-end data analytics workflow: inspecting and preparing structured data, querying and summarizing records, and presenting results through an interactive Power BI dashboard.

> **Dataset & privacy note:** The raw CSV is not included in this repository while its source, sharing permissions, and privacy requirements are being verified. The source file contains name-related fields alongside healthcare-related information. Do not publish patient-level data unless you have confirmed that it is synthetic or otherwise authorized for public sharing.

## Dashboard Preview

![Healthcare Disease & Treatment Analysis Dashboard](assets/healthcare_dashboard.png)

## Tools & Technologies

- **MySQL** — querying, filtering, grouping, and aggregating records.
- **Power BI** — KPI cards, interactive charts, slicers, and dashboard layout.
- **Microsoft Excel** — initial data inspection and validation.
- **Python** — data exploration and preparation.
- **pandas** — tabular data manipulation and data-quality checks.
- **NumPy** — numerical operations and analysis.

## Dashboard Features

- KPI cards for patient record count, average age, average stay duration, and total billing.
- Patient distribution by age group.
- Patient counts by gender and test result.
- Total billing by medication.
- Admission type comparison by gender.
- Patient distribution by blood type.
- Filters for year, hospital, insurance provider, gender, blood type, medical condition, and admission type.

## Example Questions Explored

- How are patient records distributed across age groups?
- How do patient counts compare across admission types and gender?
- How does total billing vary by medication category?
- How are records distributed by blood type and test result?
- How can interactive filters help explore subsets of the data?

## Workflow

1. Inspect source data and review field types, missing values, duplicates, and unusual values.
2. Use Excel and Python (pandas/NumPy) for initial data checks and preparation.
3. Use MySQL queries to group and aggregate data for analysis.
4. Build measures and visualizations in Power BI.
5. Validate dashboard totals against the underlying data before sharing results.

## Important Notes

- This is a **descriptive portfolio project**, not a clinical study or medical decision-support tool.
- Billing currency and full business context should be verified before interpreting billing amounts.
- Dashboard values describe the dataset and should not be treated as general medical conclusions.
- Confirm the dataset license and ensure no real patient-identifying or sensitive information is exposed before sharing publicly.

## Project Files

- `README.md` — project overview and documentation.
- `assets/healthcare_dashboard.png` — dashboard screenshot.
- Add your Power BI `.pbix` file and SQL scripts if you wish to share them and they contain no sensitive information.

## Future Improvements

- Add documented SQL scripts for dashboard metrics.
- Include a reproducible Python data-quality notebook.
- Document KPI definitions and validate dashboard measures against SQL results.
- Add detailed findings after validating the source data.

## Author

**Padmakar**

**Tools:** MySQL | Power BI | Excel | Python | pandas | NumPy
